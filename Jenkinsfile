node {
    def server
    def buildInfo
    def rtMaven
    
    stage ('Clone') {
        git url: 'https://github.com/jfrog/project-examples.git'
    }
 
   
    stage ('test') {
        rtMaven.run pom: 'maven-example/pom.xml', goals: 'clean test'
    }
    
}
