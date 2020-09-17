pipeline{
	agent any

    stages {
        stage('Build') {
            steps{
				echo 'Test pipline'

				bat """
					dir
				"""

				bat """
					ping www.baidu.com
				"""

				bat "adb"
             }
        }
    }
}