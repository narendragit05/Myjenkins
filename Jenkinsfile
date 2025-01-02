pipeline{
 agent any
 environment{
      PATH= "/opt/maven/bin:$PATH"
 }

  stages{
     stage("git clone"){
        steps{
           git url : "https://github.com/narendragit05/war-web-project.git"
        }
     }

     stage('build'){
       steps{
         sh 'mvn clean package'
       }
     }
  }
}
