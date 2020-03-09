node {
    stage('GITHUB'){
        #test123
        git 'https://github.com/cherukurisai451/maven.git'
    }
    stage('build'){
        sh label: '', script: 'mvn -f web/pom.xml clean package'
    }
}
