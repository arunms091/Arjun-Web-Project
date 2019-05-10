node{
    stage("code checkout")
    {
        git credentialsId: 'ab1d7809-b93f-4642-b705-e865832db23a', url: 'https://github.com/arunms091/Arjun-Web-Project.git'
    }
    stage("maven")
    {
        bat "mvn clean package"
    }
}
