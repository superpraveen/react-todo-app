pipeline {
    agent any
    environment {
        name = "PG"
    }
    parameters {
        //string(name: 'person', defaultValue: "PG")
        //choice(name: 'City, choices:['Jaipur', 'Pune']')
        booleanParam(name: "REACT", defaultValue: false)
        booleanParam(name: "STRAPI", defaultValue: false)
    }
    stages {
        stage('Parameter') {
            steps {
                sh 'echo Hello ${name}'
            }
        }
        stage('Build') {
            steps {
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo ${BUILD_ID}'
            }
        }
    }
}
