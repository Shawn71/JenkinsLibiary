@Library("mylib@main") _
import org.devops.Tools

def tools = new Tools()

pipeline{
    agent any
    options {
          skipDefaultCheckout true
        }
    stages{
        stage("build"){
            steps{
                script{
                   value = tools.PrintMsg("shawn")
                   println(value)
                }
            }
        }
    }
}
