//scripted
// node{
//     stage('Build'){
//         echo "build"
//     }
//     stage('Test'){
//         echo "test"
//     }
// }

//declarative
pipeline{
    agent any
    stage{
        stage('Build'){
            steps{
                echo "build completed"
            }
        }
        stage('Test'){
            steps{
                echo "testing completed"
            }
        }
        stage('Integrated Test'){
            steps{
                echo "integration completed"
            }
        }
    }

}