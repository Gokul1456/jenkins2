pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }

        stage('update my this part') 
        {
            steps 
            {
                echo 'Test App'
            }
        }

        stage('hello integration  webhook ') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }

    post
    {

    	always
    	{
    	  mail bcc: '', body: '', cc: '', from: '', replyTo: '', subject: 'create project', to: 'gokulavasan145@gmail.com'
    	}

    }
}
