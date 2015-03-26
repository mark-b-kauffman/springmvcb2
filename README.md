Spring ExternalLink B2
=====================

This project is based from an example Building Block (B2) for Blackboard Learn using the Spring APIs that Blackboard provides for third party developers. There is also code in the extlink folder and bb-manifest that inserts an ExternalLink on a content page that points to a simple bbNG:learningSystemPage. This code demonstrates our breadcrumb stacking issue.

### Clone to local repo
bitbucket: git clone https://markkauffman2000@bitbucket.org/markkauffman2000/spring-extlink-example-b2.git spring-extlink-example-b2

### Building
To build the project, just run:

./gradlew build

### Deploying
To deploy the B2 to your Learn server, run:

./gradlew -Dserver=host:port deployB2

Example: ./gradlew -Dserver=localhost:9876 deployB2
