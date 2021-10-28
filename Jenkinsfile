pipeline{
    agent{
        label "docker_Siddharth"
    }
    
    stages{
        stage("Clone github repository"){
            steps{
                echo "clone github repository"
            }
        }
        
        stage("Build code"){
            steps{
                echo "build the code"
            }
        }
        
        stage("Do unit testing"){
            steps{
                echo "unit testing passed"
            }
        }
        
        stage("Do acceptance testing"){
            steps{
                echo "acceptance testing passed"
            }
        }
        
        stage("Delivery to production"){
            steps{
                echo "delivered successfully"
            }
        }
    }
    
    post{
        success{
            echo "Successfully excuted in production"
        }
        failure{
            echo "Please check the code once again"
        }
    }
}
