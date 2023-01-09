
### 📗 Table of Contents
📖 About the Project
🛠 Built With
Tech Stack
Key Features
🚀 Live Demo
💻 Getting Started
 Setup
Prerequisites
Install
Run tests
👥 Authors
🤝 Contributing
⭐️ Show your support
🙏 Acknowledgements
📖 Hello World App
This is a RoR and React Hello World App the loads a list of greetings from the backend in a frontend page.

### 🛠 Built With
Tech Stack
Ruby
Rails Framework
PostgreSQL
React
Redux
React Router
Key Features
Loads a greetings from the backend in a frontend page.
(back to top)

### 💻 Getting Started
To get a local copy up and running, follow these steps.

Prerequisites
In order to run this project you need:

Ruby runtime environment.
If you dont have installed on your computer, you can download it from here.

PostgreSQL.
If you dont have PostgreSQL installed on your computer, you can download it from here.

Rails.
If you dont have Rails installed on your computer, you can download it from here.

Setup
If you have installed git you can clone the code to your machine, or download a ZIP of all the files directly.

Download the ZIP , or run the following git command to clone the files to your machine:

Install
Once the files are on your machine, open the blog-app folder in your code editor. Run the following command in your terminal to install the required gems and run the application:
Install gem packages with:

bundle install
Open the config/database.yml file in the project directory and change the username and password to your PostgreSQL username and password. Edit the default section of the file to look like this:
 default: &default
  adapter: postgresql
  encoding: unicode
  pool: <%= ENV.fetch("RAILS_MAX_THREADS") { 5 } %>
  username: <your PostgreSQL role username>
  password: <your PostgreSQL role password>
Create the database with:
rails db:create
Run the migrations with:
rails db:migrate
Finally, run the server with:
bin/dev
(back to top)

### 👥 Authors
Mention all of the collaborators of this project.

👤 Nonhlanhla Mndebele 

GitHub: @29td
Twitter: @nonhlanhlaMndeb6
LinkedIn: LinkedIn
(back to top)

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Feel free to check the issues page.

(back to top)

⭐️ Show your support
If you like this project give it a ⭐️!

(back to top)

🙏 Acknowledgments
I would like to thank Microverse for the idea of this project.

(back to top)

📝 License
This project is MIT licensed.

(back to top)
