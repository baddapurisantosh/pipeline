node {
    def server
    def buildInfo
    def rtMaven
    
    stage ('Clone') {
        git url: 'https://github.com/jfrog/project-examples.git'
    }
 
   
    stage ('test') {
         goals: 'clean test'
    }
    
}
