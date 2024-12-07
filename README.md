🚀 Social Media Platform - Django Project
Welcome to the Social Media Platform built using Django! 🎉 This project creates a basic yet feature-rich social media platform where users can register, log in, post updates, connect with friends, and more. It's designed as a foundation you can customize and expand to create your own unique social media experience! 🌟

📚 Table of Contents
Features
Getting Started
Prerequisites
Installation
Requirements
Usage
Contributing

🔑 Features
✨ User registration and authentication
🎨 Custom user profiles with profile pictures and bio
📜 News feed displaying posts from friends
✍️ Post creation and deletion
👍 Like posts from friends
👥 Follow users to see their posts on your home feed
🚶‍♂️ Unfollow users
🔍 User search functionality
📱 Responsive and user-friendly design

🚀 Getting Started
📌 Prerequisites
Before you begin, ensure you have the following installed:

Python (version 3.6 or higher) 🐍
Django (version 3.2 or higher) 📦
Git (for version control) 🛠️

🔧 Installation
Clone the Repository
Clone the project to your local machine:

git clone https://github.com/Ayushsav/social-media.git

Navigate to the Project Directory
Change to the project directory:
cd social-media

Set Up a Virtual Environment
It's recommended to use a virtual environment to manage dependencies:
virtualenv venv

Activate the Virtual Environment
On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate
Install Project Dependencies
Install the required dependencies:

bash
Copy code
pip install pillow

Generate requirements.txt
Create a requirements.txt file to track all installed dependencies:
pip freeze > requirements.txt


Apply Database Migrations
Run the following command to set up the database:
python manage.py migrate

Create a Superuser Account
Create an admin account to access the Django admin interface:
python manage.py createsuperuser

Run the Development Server
Start the development server:
python manage.py runserver

Access the Platform
Open your browser and navigate to:
http://127.0.0.1:8000 🌐

📝 Usage
Register/Login: Create a new account or log in with an existing one.

Customize Profile: Upload a profile picture and write a bio.

Search for Users: Find people by their username.

Create & Delete Posts: Share your thoughts and delete posts if needed.

Like Posts: Show your appreciation for others' posts 👍
Follow & Unfollow Users: Follow users to see their posts on your feed and unfollow when you wish 👥
Explore News Feed: View posts from users you follow 📰
Log Out: Sign out when you're done using the platform 🚪

🤝 Contributing
We welcome contributions to this project! If you'd like to contribute, follow these steps:

Fork the Repository: Create a copy of the project under your GitHub account 🍴
Create a New Branch: Switch to a new branch for your feature or bug fix:

git checkout -b feature-name

Make Changes & Commit: Modify the code and commit your changes:
git commit -m "Add feature"

Push Changes: Push your changes to your branch:
git push origin feature-name

Open a Pull Request: Submit a pull request with a description of your changes 🚀

✨ Contribute, create, and make this social media platform your own! ✨
