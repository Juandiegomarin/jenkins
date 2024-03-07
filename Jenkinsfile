pipeline{

    agent any
    
    stages{
        stage('subiendo'){
            steps{
            
                echo 'subiendo practica'
                sh 'npm install'
                sh 'npm run build'
                
            }
        }

        stage('copia de archivos'){
        
            steps{
            
                echo 'copia de archivos'
                sh ‘cp -r build/* /var/www/html/despliegue/'
            }
        }

    }

}
