pipeline {
    agent any
    
    tools {
        gradle 'gradle-juego'
    }
    
    stages {
        stage ("compilar") {
            steps {
                echo 'executing gradle'
                sh './gradlew -v'
            }
         
          }
            
        }
            
}
