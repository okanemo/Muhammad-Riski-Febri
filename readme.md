# PatientLab
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://okanemo.herokuapp.com)
PatientLab is an project built with Vue.js, Node.js, Express, MongoDB. Also its dockerized.
<br/>

## Project Architecture 
FullStack
<br/>

### Backend API
https://okanemo-backend.herokuapp.com
<br/>

### Frontend / Project Demo
https://okanemo.herokuapp.com
<br/> 

### Find This Project at Docker Hub
https://hub.docker.com/r/rincoreiys123/patientlabvue
<br/>
<br/>

## Installation
### Prerequisites
- Must have docker and node.js installed on your PC PROPERLY
<br/>

### Node.js (local) Environment
1. Download this repository
2. Open this repository using VSCode 
    - Run backend (by terminal) !IMPORTANT
        ``` 
            cd backend
            npm install
            npm start
        ```
        <br/>
    - Run frontend (by terminal)
        ```
            cd frontend
            npm install
            npm run serve
        ```
3. Open it at browser with this URL http://localhost:8080   
<br/>

### Docker Container Installation
1. Run image 
    ```
        docker run -p 8080:80 rincoreiys123/patientlabvue:latest
    ```
    its remote repository, so ignore "Unable find image" warning

2. Open it at browser http://localhost:8080   
<br/>
    







