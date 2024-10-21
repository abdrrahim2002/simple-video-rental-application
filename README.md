# Video rental application (Movie Mania)

<br>

## Overview
**Movie Mania** is a simple video rental application developed using Django. This project focuses on the fundamental concepts of the Django framework, providing a straightforward interface to manage a collection of movies.

<br>

## Features
- **Movie Listings**: View a list of movies, each with its genre, stock number, and daily rental rate.
- **API Integration**: Created an API using **django-tastypie** to expose movie data in JSON format, making it easy to share and access across multiple platforms.

<br>

<div align='center'>
  <img src='https://raw.githubusercontent.com/abdrrahim2002/simple-video-rental-application/refs/heads/main/images/home%20page.png' alt='home'>

  
  <img src='https://raw.githubusercontent.com/abdrrahim2002/simple-video-rental-application/refs/heads/main/images/detail%20page.png' alt='detail'>

  ---

  **Example of API response**
  
  <img src='https://raw.githubusercontent.com/abdrrahim2002/simple-video-rental-application/refs/heads/main/images/API%20result.png' alt='api' >
</div>

<br>

## Learning Objectives
Throughout this tutorial, I have learned:
- Understanding the fundamental aspects of the Django framework
- Creating and managing models, views, and templates.
- Implementing an API using django-tastypie for data sharing in JSON format.
- Focusing on functionality and logic rather than styling.

<br>

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/abdrrahim2002/simple-video-rental-application.git
cd simple-video-rental-application/
```

2. Create a virtual environment:

```
virtualenv venv
source venv/bin/activate
```

3. Install the required packages:

```
pip install -r requirements.txt
```

4. Create the database:

```
python manage.py makemigrations
python manage.py migrate
```

5. Create super user :

```
python manage.py createsuperuser
```

6. Run the Django development server:

```
python manage.py runserver
```

7. Open your browser and enter to the admin section to start add you movies infos by visiting `http://127.0.0.1:8000/admin`

8. to see the api response visit `http://127.0.0.1:8000/api/movies/`

<br>

## Acknowledgments

Special thanks ❤️ to [Mosh Hamedani](https://github.com/mosh-hamedani) for the excellent tutorial that guided me through this project. His teaching has been invaluable in enhancing my understanding of Django.

<br>

Thank you for taking the time to check out **Movie Mania!** I hope you find it insightful and enjoyable!
