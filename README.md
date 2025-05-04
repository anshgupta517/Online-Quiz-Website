
# Online-Quiz-Website in Django

This project is an online quiz website built using Python.

##  Key Features

*   **Online Quizzes:** Allows users to take quizzes online.
*   **Django Framework:** Built using the Django framework for robust web development.
*   **Database Integration:** Uses a database (likely SQLite by default) to store quiz data and user information.
* Implemented core features including secure user authentication (registration, login, logout), dynamic loading of multiple-choice questions from a database, and immediate post-submission feedback with detailed scoring (total score, correct/wrong count, percentage).
* Created a separate administrative view for authorized staff to easily add and manage quiz questions.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/anshgupta517/Online-Quiz-Website.git
    cd Online-Quiz-Website
    ```


2.  **Apply Migrations:**

    Navigate to the directory containing `manage.py` and run the following commands:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

3.  **Load Fixtures (Optional):**

    The project includes a `fixtures.json` file.  You can load this data into your database using:

    ```bash
    python manage.py loaddata fixtures.json
    ```

4.  **Run the development server:**

    ```bash
    python manage.py runserver
    ```

    This will start the server, and you can access the website in your browser, usually at `http://127.0.0.1:8000/`.



