pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Shiva Kumar'
                  }
            }
	    stage('FetchandBuild'){
		  steps {
			build job: 'FetchandBuild'
		  }
	    }
            
      }
}
