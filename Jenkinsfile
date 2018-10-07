node {
    stage('build'){
        echo "building"
    }
}
stage('Deploy approval'){
    input "Deploy to prod?"
}
node {
    stage('deploy to Dev'){
        echo "deploying"
    }
}
