pipeline{

    agent any 

    stages{

        stage('Git Checkout'){

            steps{

                script{
                    gitCheckout{
                        branch: 'main',
                        url: "https://github.com/avinashkunapareddy11/mrdevops_java_app.git"
                    }
                }
            }
        }
    }
}