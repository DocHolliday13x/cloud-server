# LAB - Class 16

## Project: cloud-server

### Author: Ryan Eastman

![GIF](https://media.giphy.com/media/GyLc9e3hTYFWw/giphy.gif)

### Problem Domain

The goal for today is to deploy a simple Node.js server to EC2, using Elastic Beanstalk.

1. **Choose a server you’ve built previously**:
   - Option 1: A simple API or Web Server
   - Option 2: A socket.io event Hub
The server should not require a database.
Check in your server to GitHub.

2. **Task 1**:

   - Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
   Manually deploy your application to this environment by uploading a .zip file

3. **Task 2**:

   - Using the same server, create a new environment using Elastic Beanstalk from your terminal
Manually deploy your application to this environment by using eb deploy

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/DocHolliday13x/cloud-server/actions)
- [AWS Deploy](http://cloud-server-dev22.us-west-2.elasticbeanstalk.com/)
- [Review Deploy](http://lab16-env.eba-pgkchucs.us-west-2.elasticbeanstalk.com/)
<!-- - [back-end server url](http://xyz.com) (when applicable)
- [front-end application](http://xyz.com) (when applicable) -->

### Collaborators

- Ryan Gallaway
- Reece Renninger
- Ike Steoger
- Stephen Clemmer
- Keelan Fisher
- Reviewed W/entire class

### Setup

#### `.env` requirements (where applicable)

PORT=3001

#### How to initialize/run your application (where applicable)

- `nodemon` to start server

#### How to use your library (where applicable)

#### Features / Routes

- Feature One: Details of feature
- GET : `/hello` - specific route to hit
- GET : `/` - specific route to hit
- GET : `/greet` - specific route to hit
- GET : `/banana` - specific route to hit

#### Tests

- How do you run tests?
- Any tests of note?
- Describe any tests that you did not complete, skipped, etc

#### UML

- ![UML](./assets/lab16UML.png)
