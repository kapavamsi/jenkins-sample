pipeline{
    agent any
        stages{
            stage("Clean Up"){
                steps{
                    deleteDir()
                }
            }

            stage("Stage-1"){
                steps{
                    echo "Stage:1 This is STAGE:1" 
                }
            }

             stage("Stage-2"){
                steps{
                    echo "Stage:2 This is STAGE:2" 
                }
            }

        } 
    
}