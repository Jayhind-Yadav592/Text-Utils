📝 TextUtils – Django Mini Project

TextUtils is a simple Django-based web application that allows users to perform multiple text-processing operations such as removing punctuation, converting text to uppercase, removing extra spaces, and removing new lines. This project is beginner-friendly and ideal for learning Django fundamentals like views, templates, forms, and URL routing.

🚀 Features

Remove punctuations from text

Convert text to UPPERCASE

Remove new lines

Remove extra spaces

Multiple operations can be applied together

Clean UI using Bootstrap

CSRF protected form submission

🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, Bootstrap

Template Engine: Django Templates

📁 Project Structure
mysite/
│
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── templates/
│   ├── index.html
│   └── analyze.html
│
├── views.py
├── manage.py
└── README.md

⚙️ How It Works

User enters text in the textarea.

User selects one or more operations using checkboxes.

Form is submitted using POST method.

Django processes the text based on selected options.

The analyzed text is displayed on a new page.

🧠 Core Logic (Views)

index(request) → Renders the home page

analyze(request) →

Reads text from POST request

Applies selected operations step-by-step

Sends final processed text to template

🌐 URL Configuration
urlpatterns = [
    path('admin/', admin.site.urls),
    path('', view.index, name='index'),
    path('analyze', view.analyze, name='analyze')
]

▶️ How to Run the Project

Clone the repository or copy the project folder

Install Django

pip install django


Run the server

python manage.py runserver


Open browser and go to

http://127.0.0.1:8000/

📸 Screens Included

Home page with text input and options

Analyzed result page showing processed text

👨‍💻 Author

Jayhind Yadav
Beginner Django Developer 🚀