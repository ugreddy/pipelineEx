node {
    
    stage('scm') {
    // some block
    git 'https://github.com/wakaleo/game-of-life.git'
    }
    stage('build') {
    // some block
     bat label: '', script: 'mvn package'
    }
    stage('artifacts') {
    archiveArtifacts 'C:/Program Files (x86)/Jenkins/workspace/govarddan-night-build-pipeline-1/gameoflife-web/target/*.war'
    }
}
