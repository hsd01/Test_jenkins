pipeline{
    agent any
    stages{
    stage("clone | checkout"){
        steps{
            bat("""
            pwd
            dir
            """)
        }
    }
    stage("Run python"){
        steps{
            bat("""
            cd Test_jenkins
            dir
            pwd
            python main.py
            """)
        }
    }
    stage("All done"){
        steps{
        echo "Hell its fine"
    }
    }
    }
}
