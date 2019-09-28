# cicd-pipeline-train-schedule-jenkins

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities. Has Jenkins integration with configured webhook for automatic builds. Set up a webhook to trigger Jenkins whenever changes are made to the repo in GitHub.


## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)

Where do I go to configure webhook permissions? Github or Jenkins? Probably Github. 

Created a new access token. 

Updated webhook IP 

Testing webhook. Status: build didn't auto start.
Testing webhook 2. Tried: checked github and jenkins configuration. 
Testing webhook 3. Tried: configured new api key. 
Testing webhook 4. Tried: configured git and cloned repo on la-server. 
Testing webhook 5. Tried:  Github webhook pointing to the wrong Jenkins server
Testing webhook 6. Tried: Followed Triggering Builds with Git Hooks
Testing webhook 7. Tried: deleted email notification post build step 
Testing webhook 8. Status: webhooks successful. Fix: make sure Payload URL is pointing to correct Jenkins server. 
