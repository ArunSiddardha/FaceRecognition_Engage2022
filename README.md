<div id="top"></div>



<!-- PROJECT LOGO -->
<br />
<div align="center">
 
  <h1 align="center">Face Recognition Demonstration</h1>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#how-to-use">How to Use</a>
    </li>
    <li>
      <a href="#key-features">Key Features</a>
      <ul>
        <li><a href="#login-and-register">Login and Register</a></li>
        <li><a href="#lost-and-found-portal">Lost and Found Portal</a></li>
        <li><a href="#tracking-attendance">Tracking Attendance</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Introduction

This project is built under microsoft engage mentorship program 2022.This Web app consists of three demonstrations of facial recognition
* Login Security
* Finding missing people
* Tracking Attendance

This Project is based upon computer vision applications and pre-built machine learning models.


<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This project is built using.

- Python : Server Side  Framework
- Flask : Backend Framework
- SQLALchemy : Database
- DeepFace : Face Recognition
- RetinaFace : Face Detection 


<!-- GETTING STARTED -->
## How to use

- Install python version 3.8
```sh
  sudo apt-get install python3.8
  ```

- Clone this repository
```sh
  git clone https://github.com/ArunSiddardha/FaceRecognition_Engage2022.git
  ```
- Change the working directory
```sh
  cd FaceRecognition_Engage2022
  ```
- Create a python virtual environment in the working directory

```sh
    python -m venv myenv
```

- Activate the python Virtual environment

```sh
    source myenv/bin/activate
```
- Install all the required packages

```sh
    pip3 install -r requirements.txt
```

- Run the flask server
```sh
    python app.py 
```

- Run the app on the browser
```sh
    http://localhost:5000/ or whatever port it gives 
```


<p align="right">(<a href="#top">back to top</a>)</p>


## Key Features

### Login and Register
- Registration using users face & username
- Login using users face & usernmae

### Lost and Found Portal
- Lost Portal
    - users can upload the picture of lost people with their details of contact
    -  If the person is found in our databse then details to contact the person will be given to you
    - If the lost people were not found in the database then the picture gets saved in the lost people database so if anyone finds them using this portal then they will be given your contact detials
- Found Portal
    - Users can upload the picture of found people along with the details of contact
    - If the persons face is found in the database then it will give u the person to contact so that u can contact them
    - IF they are not found in the databse then the picture gets saved in our database so if anyone is looking for them using this portal they will be given the details of contact

### Tracking Attendance
- Course Registration
    - Students have to register for the course using their roll No and their face
- Taking Attendance
    - Teachers can take attendance using this portal and the attendance gets marked in the attendance sheet
- Classroom Strength
    - Teachers can upload the pic of their classroom of their course and get the strenght present on the class room on a particular day
- Checking Attendance
    - Teachers can check the class strength and the students attendance using this portal



<p align="right">(<a href="#top">back to top</a>)</p>
