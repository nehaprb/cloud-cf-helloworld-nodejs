

@Library(['piper-library-os@2716054392ead88ecba5c984967d1ab64279db02'])
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
}

stage('build') {
    mtaBuild script: this
}
