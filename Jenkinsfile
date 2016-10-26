node('small') {

    stage 'Hello'

    echo 'Hello, world!'
    if (env.BRANCH_NAME == 'master') {
        echo "master"
    } else if (env.BRANCH_NAME.startsWith("PR-") {
        echo "pull request"
    }

    sh 'env'
}
