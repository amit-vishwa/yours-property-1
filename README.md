# Yours-property
This is a mock project

### Step 1 :
Download and extract zip file
### Step 2 :
run command -> npm i 
### step 3 :
now do the mentioned things from below Note section.
### step 4 :
now run the project on localhost -> npm start

https://yoursproperty.herokuapp.com/


# Note :
Two extra files needs to be added along with required dependency packages to run the project, they are - (to be kept in server.js level directory)

1) .env file :

// For firebase configuration -

apiKey: ""

authDomain: ""

projectId: ""

storageBucket: ""

messagingSenderId: ""

appId: ""

measurementId: ""


// For storage of images in AWS Bucket -

AWS_ACCESS_KEY=''

AWS_SECRET_KEY=''


// For nodemailer in feedback form of home.html -

PASSWORD=''

EMAIL=''


2) xxxx-firebase-adminsdk-xxxxx-xxxxxxx.json file :

{

"type": "",

"project_id": "",

"private_key_id": "",

"private_key": "-----BEGIN PRIVATE KEY-----\nxxx......x...xxx...xxxxxx\n-----END PRIVATE KEY-----\n",   // very long key will be there

"client_email": "",

"client_id": "",

"auth_uri": "",

"token_uri": "",

"auth_provider_x509_cert_url": "",

"client_x509_cert_url": ""

}


