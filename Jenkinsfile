env.dockerimagename="buildon/buildon:v2"
node {

   stage('Preparation') { //for display purposes
      checkout scm           
   }
   stage('Build') {
      // Run the maven build<appndid>

         sh "mvn clean package -DskipTests=True"
     
   }
}
