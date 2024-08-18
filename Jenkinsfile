pipeline{

  agent  {

             label {

                      label "slave-1"
              
                                 }
    
    
  }

     stages {

              stage ( " installing httpd" ) {

                steps {

                        sh "sudo yum install httpd -y "
                  
                }

                stage ("start httpd") {

                     sh "service httpd start"
                     sh " chmod -R 777 /var/www/html "
                     sh ""
                  
                }
              }

       
       
     }

  
}
