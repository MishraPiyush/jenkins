
      node{
        stage('Clone repository') {
            container('httpd')
       {
                sh 'whoami'
                sh 'hostname -i'
                sh 'git clone -b master https://github.com/MishraPiyush/XmlFeatures'
       }
        }

        stage('Maven Build') {
              container('httpd')
       {
            
                    sh 'cp Jenkinsfile /var/www/html'
                   
       }
        
    }
      }
