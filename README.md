# flashcard_app

## Description

Flashcards are a great tool to help memorize vocabulary when learning a new language. This app was specifically built to learn Dutch from French words but can easily be updated for any other language or even any other discipline where flashcards could be a help for students out there. 

More stecifically, the way this app works was inspired by the **Leitner System** to implement spaced repetition in the language learning process:
> In the Leitner System, flashcards are sorted into groups according to how well the learner knows each one in Leitner's learning box. The learners try to recall the solution written on a flashcard. If they succeed, they send the card to the next group. If they fail, they send it back to the first group. 



## Requirements & Installation
In the project folder, type in `pip install -r requirements.txt` from your CLI. 
You can also manually install each package, refering to the `requirements.txt` document. 


Using the following line, you can configure the Django project:
`django-admin startproject flashcards .` 

The final `.` is to prevent Django from creating a nested project directory (you'd end up with a `flashcards/` containing a `flashcards/` subdirectory). 

To run the development web server on your local machine, simply type in your CLI `python3 manage.py runserver`.
Your webapp can be visualised locally from your usual web browser using `http://localhost:8000` or `http://127.0.0.1:8000`.


## Data 


### NLP Methods

## Demo