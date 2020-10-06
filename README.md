# Google drive file upload using web application with OAuth 2.0 

### Tools and Technologies used :
- intelliJ idea - IDE
- XAMPP - server
- Google developer console : ``` https://console.developers.google.com/ ```
- HTML
- CSS
- Bottstrap
- Javascript
 -------------- 
### Creation of Client ID, and Client Secret

- login to google developer console : ``` https://console.developers.google.com/ ```
- create new project.
- enable ```google drive api``` service.
- configure oauth concent screen with required parameters.(application name, support email).
- Create OAuth client ID credential.
    - register as web application.
    - enter name of the OAuth client.
    - authorized javascript origin URI :  ``` https://localhost/OAuth2 ```
    - authorized redirect URI as : ``` https://localhost/OAuth2/upload.html ```
    - click save.
- Client ID and Client secret will be prompt.


### Project setup steps

- clone the project to the project inside “C:/xampp/htdocs/” folder.
- create Client ID and Client secret from the developer console. (see above Create Client ID, and Client Secret)
- update the Client ID and Client secret in home.html and update.js files.
- start XAMPP server.
- go to following URL: ``` https://localhost/OAuth2/ ```
 --------------
### Execution

- go to following URL: ``` https://localhost/OAuth2/ ```
- click on sign-in button.
<img src="/application snaps/home.jpeg" alt="home page" width="400" height="300" />

- .verify application.
<img src="/application snaps/authorization.jpeg" alt="home page" width="400" height="300" />

- choose files to upload and see the file name, type, size and upload.
<img src="/application snaps/upload.jpeg" alt="home page" width="400" height="500" />

- check goole drive for the uploaded image.
