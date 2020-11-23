  @Library('piper-lib-os') _
node() {
    stage('prepare') {
        echo "starting stage prepare"
        checkout scm
        echo "checkout scm successful"
        //setupCommonPipelineEnvironment script:this
         echo "end of stage prepare"
    }
    
    stage('build') {
    mtaBuild script: this
}

}
