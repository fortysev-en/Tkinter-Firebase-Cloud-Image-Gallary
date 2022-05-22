<h1 align="center">Tkinter Firebase Image Gallary App</h1>
<h6 align="center"><a href="https://thefortyseven.dev/">by fortyseven</a></h6>

<p align="center">
    <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.9-blue">
  </a>
  <a href="">
    <img src="https://img.shields.io/badge/Version-1.0-yellow">
  </a>
    <a href="https://github.com/fortysev-en/FirebaseTkinterApp">
    <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen">
  </a>
    <a href="http://thefortyseven.dev">
    <img src="https://img.shields.io/badge/Blogs-%E2%9A%8F-lightgrey">
  </a>
<a href="https://thefortyseven.dev/tkinter-firebase-cloud-image-gallary">
    <img src="https://img.shields.io/badge/Tutorial-%F0%9F%9B%88-brightgreen">
  </a>
</p>

<p align="center">
  <b>This</b> is an open source tool which uses Fireabse as a backend to store images and Tkinter as a frontend 
to display images, it can be extended further and used as a template or boiler plate to generate a user based app 
with login and signup feature.
</p>


## Key Features -
### App Features:
* Login Page
* SignUp New User Page
* UPLOAD BULK Images
* VIEW Images
* Required Email Verification for Login
* Reset Password
* Contains App Logo
* FREE
* Disclaimer Page
* About Page
* Donate Page
* Auto UPDATE check feature


## Setup -
Simply install all the dependencies by:  
`pip install -r requirements.txt`

Firebase Setup:  
1. Make sure you create a project and then a web app in firebase.  
2. Get the `SDK setup and configuration` from `Project Settings`.  
3. Copy YOUR OWN API keys as mentioned below and add it in `FirebaseTkinterApp`
```
const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: "",
  "serviceAccount": "<path to your service_account.json>"
};
```

```NOTE: To get the serviceAccount file, in your firebase project, goto Project Settings -> Service Accounts -> generate new private keys. This will give you a json file. ```

4. Add a version file in that projects Cloud Storage and add below in it.  
`{"version" : "1.0"}`

5. That's it! You can now continue with the project!

#
## Support ❤ Donate -
You can show your support by a donation. <a href="https://thefortyseven.dev/donatePage">Click Here!</a>\
PS: It will also encourage me to develop more such projects.