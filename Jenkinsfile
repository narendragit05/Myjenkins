pipeline{
 agents any
   environment{
      PATH= "/opt/maven/bin:$PATH
   }

   stages{
     stage("git clone"){
        steps{
           git url : ""
        }
     }

     stage('build'){
       steps{
         sh 'mvn clean package'
       }
      }
    }
}
