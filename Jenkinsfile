node {

   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/sunlove123/onlinebanking.git'
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
   }
   stage('Build') {
      // Run the maven build

         sh "mvn clean package -DskipTests=True"
     
   }
   stage('Results') {
         sh "mvn cln"
   }
}
