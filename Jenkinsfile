pipeline{

  agent  {

             label {

                      label "slave-1"
              
                                 }
    
    
  }

     stages {

              stage ( "one" ) {

                steps {

                        sh "sudo yum install httpd -y "
                  
                }
              }

                stage ("two") {

                  steps {

                     sh "service httpd start"
                     sh " chmod -R 777 /var/www/html "
                     sh "sudo cp -r index.html /var/www/html "
                  }
                }
              }

       
       
     }

  
}
