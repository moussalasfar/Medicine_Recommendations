Medicine Recommendation System
This is a Flask-based web application that provides personalized medicine recommendations based on user input. The system allows users to register, log in, and receive medicine recommendations by entering a disease name. The application also includes a contact page for users to send inquiries via email.

Features
User Authentication: Register and log in with an email and password.
Medicine Recommendation: Enter a disease name to get a list of the 10 most relevant medicines.
Contact Form: Users can send messages via the contact page using SMTP.
Personalized Dashboard: Display the first letter of the user's email in a circle on the recommendation page.
Project Structure
_____________________________________________________________________________________

Medicine_Recommendations/
│
├── app.py
├── medicine_recommendations.ipynb
├── data/
│   └── medicines.csv
├── static/
│   ├── css/
│   │   ├── style.css
|   |   ├── ss.css
|   |   ├── style.css.map
│   │   └── style_recommend.css
│   ├── fonts/
│   │   └── material-icon/
│   │       └── css/
│   │           └── material-design-iconic-font.min.css
│   ├── images/
│   │   ├── signin.png
│   │   └── signup.png
│   ├── js/
│   │   └── main.js
│   └── vendor/
│       └── jquery/
|           ├── jquery-ui.min.js
│           └── jquery.min.js
├── templates/
│   ├── index.html
│   ├── login_custom.html
│   ├── register_custom.html
│   ├── recommendation.html
│   └── contact.html
└── requirements.txt
