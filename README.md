# Library Management 
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Dionysius%20Ogero-red)

---

## Screenshots 

### Homepage 
![homepage snap](https://raw.githubusercontent.com/DeveloperDionz/librarymanagement/main/static/screenshots/homepage.png)

### Admin Dashboard 
![dashboard snap](https://raw.githubusercontent.com/DeveloperDionz/librarymanagement/main/static/screenshots/adminhomepage.png)

### Available Book 
![invoice snap](https://raw.githubusercontent.com/DeveloperDionz/librarymanagement/main/static/screenshots/availablebook.png)


### Issue Book 
![issue book snap](https://raw.githubusercontent.com/DeveloperDionz/librarymanagement/main/static/screenshots/issuebook.png)

### Issued Book 
![issued book snap](https://raw.githubusercontent.com/DeveloperDionz/librarymanagement/main/static/screenshots/bookissued.png)

---

## Functions 

### Admin 
- Create Admin account and Login. 
- Can Add, View, Book 
- Can Issue Book (added by Admin) to registered student. 
- Can view Issued book with issued date and expiry date. 
- Can view Fine (10 rupees for each day after expiry date). 
- Can View Students that are registered into system.  

### Student 
- Create account and Login. 
- Can view their issued book only with expiry date and fine (if there are any, otherwise 0) 

---

## HOW TO RUN THIS PROJECT 
1. Install Python latest version (Don't Forget to Tick Add to Path while installing Python)
2. Open Terminal and Execute the Following Commands:
   ```bash
   python -m pip install -r requirements.txt
Download This Project Zip Folder and Extract it.
Move to the project folder in Terminal. Then run the following Commands:
 ```bash
 py manage.py makemigrations
 py manage.py migrate
 py manage.py runserver
Download this project as a ZIP folder and extract it.
Now enter the following URL in your browser installed on your PC:
 ```bash
 http://127.0.0.1:8000/
CHANGES REQUIRED FOR CONTACT US PAGE
In the `settings.py` file, you have to give your email and password:

 ```bash
 EMAIL_HOST_USER = 'youremail@gmail.com'
 EMAIL_HOST_PASSWORD = 'your email password'
 EMAIL_RECEIVING_USER = 'youremail@gmail.com'
Drawbacks/LoopHoles
Anyone can be Admin.
Feedback
Any suggestions and feedback are welcome. You can message me on Facebook
