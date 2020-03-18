node {
    def server
    def buildInfo
    def rtMaven
    
    stage ('Clone') {
        git url: 'https://github.com/jfrog/project-examples.git'
    }
 
   
    stage ('package') {
        rtMaven.run pom: 'maven-example/pom.xml', goals: 'clean test'
    }
    
}
