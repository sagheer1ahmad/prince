pipeline
{
    agent any
    stages
    {
        stage ('cloning from github')
        {
            steps
            {
               sh 'touch abc.txt'
            }
        }
         stage ('testing the code')
        {
            steps
            {
                sh 'touch bca.txt'
            }
        }
         stage ('building the code')
        {
            steps
            {
                sh 'touch cab.txt'
            }
        }
        stage ('deploying the code')
        {
            steps 
            {
                sh 'touch cba.txt'
            }
        }
        stage ('send slack message')
        {
            steps
            {
                slackSend channel: 'devops', message: 'build code is failure or sucees'
            }
        }
        
    }
}
