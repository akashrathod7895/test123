pipeline {
    agent any 
    stages {
         stage ("install-httpd") {
                steps {
                    sh "yum install httpd -y"
                    sh "service httpd start"
                    sh "chkconfing httpd on"
                    sh "cd /var/www/html"
                    sh "cp /root/.jenkins/workspace/project/index.html ."
                    sh "cd /"
                    sh "chmod -R 777 /var"
                    
                    
                }
                
            }
            
        
        
        
    }
    
}
