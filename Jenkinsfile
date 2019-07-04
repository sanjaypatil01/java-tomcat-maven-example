pipeline {
    agent any
    stages {
        stage ('initialize') {
            steps {
                /*For windows machine */
               bat...
               echo "M2_HOME = %M2_HOME%"
               echo "PATH = %PATH%" 
               ...             
            }
        }

        stage ('Build') {
            steps {
                echo 'Hello World ....!'                  
            }
        }    
    }
}