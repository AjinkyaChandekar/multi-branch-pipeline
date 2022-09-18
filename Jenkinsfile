pipeline {
   agent any
   stages {
      stage('STAGE 01') {
         steps {
            sh """
            echo "STAGE 01"
            """
            }
        }
      stage('STAGE 02') {
         steps {
            sh """
            echo "STAGE 01"
            """
            }
        }
   }
}

#MULTI-BRANCH PIPELINE
// pipeline {
//     agent {
//         docker {
//             image 'node:lts-alpine'
//             args '-p 3000:3000 -p 5000:5000' 
//         }
//     }
//     environment {
//         CI = 'true'
//     }
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'npm install'
//             }
//         }
//         stage('Test') {
//             steps {
//                 sh './jenkins/scripts/test.sh'
//             }
//         }
//     }
// }
