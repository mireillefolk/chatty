# Chatty Social Media Site
Welcome to Chatty, your go-to social media platform for connecting with friends, sharing updates, and engaging in meaningful conversations. Built using PHP, MySQL, and JavaScript, Chatty offers a user-friendly interface and robust features to enhance your social networking experience.

## FEATURES 

### User Authentication and Authorization
- Secure user registration and login system.
- Password hashing for enhanced security.

### Profile Management
- Personalized user profiles with customizable avatars and cover photos.
- Editable user profile information, including bio and contact details.

### News Feed
- Dynamic news feed displaying posts from friends and followed users.
- Like, comment, and share functionality for engaging with posts.
- Real-time updates with AJAX for seamless user experience.

### Messaging
- Notification alerts for new messages and message requests.

### Search and Discovery
- Search functionality to find users, and posts 

### Notifications
- Notification system to alert users about new friend requests, messages, and post interactions.
- Notification preferences for customizing notification settings.

## INSTALLATION.

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/mireillefolk/chatty.git
* Set up the database: 
- download and install a development server xampp or wamp and place the project in the htdocs folder if it's xampp or wwww folder if it's wamp 
- go to localhost/phpmyadmin and Create a MySQL database named social.
- navigate project files and Import the social.sql file into the database social.
* Configure database connection:
- Update the config.php file in the includes directory with the MySQL database credentials.
* Start the PHP development server:
- Open your web browser and navigate to http://localhost/chatty to access Chatty.

#### Technologies Used
**** PHP: Server-side scripting language for backend development.
**** MySQL: Relational database management system for storing user data and posts.
**** JavaScript: Client-side scripting language for dynamic web interactions.
**** HTML/CSS: Markup and styling languages for creating the user interface.
**** AJAX: Asynchronous JavaScript and XML for real-time updates and seamless interactions.
**** Bootstrap: Frontend framework for responsive and mobile-friendly design.

#### Contributing
Contributions are welcome! If you'd like to contribute to Chatty, please fork the repository and submit a pull request with your changes.

#### License
This project is licensed under the MIT License - see the LICENSE file for details.

#### Author
Chatty is developed and maintained by Your jof dorian guefack.

#### CSS

@font-face {
	font-family: 'Bellota-LightItalic';
	src: url('../fonts/Bellota-LightItalic.otf');
}
@font-face {
	font-family: 'Bellota-BoldItalic';
	src: url('../fonts/Bellota-BoldItalic.otf');
}

html, body {
	height: 100%;
	min-height: 100%;
}

form {
	text-align: center;
}

body{
	margin: 0;
	padding: 0;
}

a {
	text-decoration: none;
	color: #3498db;
}

.wrapper {
	background-image: url("../images/backgrounds/desktop.jpg");
	background-size: 100%;
	width: 100%;
	height: 100%;
	min-width: 950px;

}

.login_box {
	font-family: 'Bellota-LightItalic', sans-serif;
	position: relative;
	margin-right: auto;
	margin-left: auto;
	top: 7%;
	width: 35%;
	background-color: #ffffff;
	border: 1px solid #EDEDED;
	border-radius: 7px;
	padding: 5px;
	opacity: 0.98;
}

.login_header {
	font-family: 'Bellota-LightItalic', sans-serif;
	width: 100%;
	height: 90px;
	background-color: #3498db;
	color: #fff;
	text-align: center;
	border-top-left-radius: 7px;
	border-top-right-radius: 7px;
}

.login_header h1 {
	font-family: 'Bellota-BoldItalic', sans-serif;
	margin-top: 0;
	margin-bottom: 0;
	color: #2C6C96;
	text-shadow: #73B6E2 0.5px 0.5px 0px;
	font-size: 250%;
}

input[type="submit"] {
	background-color: #3498db;
	border: 1px solid #3498db;
	border-radius: 3px;
	margin: 5px 0 10px 0;
	padding: 5px 10px 5px 10px;
	color: #2C6C96;
	text-shadow: #73B6E2 0.5px 0.5px 0px;
	font-family: 'Bellota-BoldItalic', sans-serif;
	font-size: 100%;
}

input[type="text"], input[type="email"], input[type="password"] {
	border: 1px solid #e5e5e5;
	margin-top: 5px;
	width: 70%;
	height: 35px;
	margin-bottom: 10px;
	padding-left: 5px;
}

input[type="text"]:hover, input[type="email"]:hover, input[type="password"]:hover {
	border-color: #3498db;
}

#second {
	display: none;
}




