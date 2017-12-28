node {

    checkout scm

    stage "Deploy"
        sh cd /wordpress-pv
        sh kubectl apply -f ."
}
