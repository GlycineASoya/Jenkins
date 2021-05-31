pipeline {
    agent any

    parameters {
        string(defaultValue: "test1,test2", description: 'SkippedTags', name: 'skippedTags')
    }

    stages {
        stage ('return default values') {
            steps {
                sh("echo ${skippedTags}")
            }
        }
    }
}