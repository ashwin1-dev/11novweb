pipeline {
     agent any
     
     stages {
          stage('build') {
               steps {
                   sh 'sudo rm -rf /var/www/html'
                   sh 'sudo yum install httpd -y'
                   sh 'sudo systemctl start httpd'
                   sh 'sudo git clone https://github.com/ashwin1-dev/24-apr-web1.git  /var/www/html'
               }
          }
     }
}
