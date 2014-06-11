twitter-streaming-nodejs
========================

Shows how to stream real time twitter data to Google Maps using NodeJS.


<h2>Step 1: Configure Twitter API creds</h2>
Update Cloudfoundry application manifest to include your Twitter credentials:
<code>
    env:
       consumer_key: <ADD_ME>
       consumer_secret: <ADD_ME>
       access_token_key: <ADD_ME>
       access_token_secret: <ADD_ME>
</code>
<h2>Step 2: Create an AWS Elastic Beanstalk application</h2>
Access Elastic Beanstalk from the console. Choose to create a new application and give it a name and description.
