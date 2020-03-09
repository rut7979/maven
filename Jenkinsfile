node {
    stage('GITHUB'){
        #test123
        git 'https://github.com/rut7979/maven.git'
    }
    stage('build'){
        sh label: '', script: 'mvn -f web/pom.xml clean package'
    }
}
