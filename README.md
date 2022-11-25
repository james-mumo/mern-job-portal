## ⚠ Disclaimer

Hey, I'm James and I'm a FullStack Developer. I have no problem with sharing code...YOU CAN USE IT BUT WITH ATTRIBUTION...I spent a lot of time buildin this project and such it is always disheartening for someone to copy my work and claim as His/Hers without linking back to me.

## 📞 Contact Me 📞

- 📱 Whatsapp +254743597468

- 📧 E-Mail mumojames98@gmail.com

## 

## 💼 Qazify Job Portal 💼

In this MERN web app, login sessions are persistent and REST APIs are securely protected by JWT token verification.
After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resume and edit profile.
And, an applicant can view jobs, perform fuzzy search with various filters, apply for jobs with an SOP, view applications, upload profile picture, upload resume and edit profile. Hence, it is an all in one solution for a job application system.

Directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## 🚀 Instructions for initializing web app

- Install Node JS, MongoDB in the machine.
- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444 whch is set as the default port.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.

## 🛠 Dependencies

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

# 💻🖥 Machine Specifications

Details of the machine on which the webapp was tested:

- Operating System: Windows 10 Pro Version 21H2
- Terminal: Bash
- Processor: Intel(R) Core(TM) i5-3437U CPU @ 1.90GHz 2.40 GHz
- RAM: 10 GB
