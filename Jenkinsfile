pipeline {
    agent any 
    stages {
         stage ("install-httpd") {
                steps {
                    sh "yum install httpd -y"
                    sh "service httpd start"
                    sh "chkconfig httpd on"
                    sh "cp /root/.jenkins/workspace/project/index.html /var/www/html"
                    sh "cd /"
                    sh "chmod -R 777 /var"
                    
                    
                }
                
            }
            
        
        
        
    }
    
}
