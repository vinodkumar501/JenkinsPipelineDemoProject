pipeline{
agent any
tools { 
        maven 'mvn-3.8.4' 
        jdk 'jdk-1.8' 
    }
stages 
{
stage('Build') 
{
steps{
echo "Building the Code.........."
sh "mvn clean"                             //bat "mvn clean" --> for windows
}
}
stage('Test') 
{
steps{
echo "Testing the Code.........."
sh "mvn test"
}
}
stage('Compile') 
{
steps{
echo "Compiling the Project.........."
sh "mvn compile"
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
}
}
}
}
