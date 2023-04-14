pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
                bat "git clone https://github.com/divyanshgarg604/jenkins-demo.git"
            }
        }
//         stage('install') {
//             steps {
//                 bat "mvn install -f TicketBookingServiceJunitTesting"
//             }
//         }
//         stage('test') {
//             steps {
//                 bat "mvn test -f TicketBookingServiceJunitTesting"
//             }
//         }
//         stage('package') {
//             steps {
//                 bat "mvn package -f TicketBookingServiceJunitTesting"
//             }
//         }
    }
}
