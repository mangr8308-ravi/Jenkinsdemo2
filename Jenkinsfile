node {
    try {
    stage('Checkout Code') {
        checkout scm
    }
    stage('Extract Data') {
        bat 'C:\\Users\\RAVI\\AppData\\Local\\Programs\\Python\\Python313\\python.exe'
    }
    }
    catch(err) {
        echo "pipeline error : ${err}"
    }
    finally {
        echo "pipeline completed"
    }
}