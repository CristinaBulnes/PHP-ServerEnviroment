# PHP-ServerEnviroment
Explore the content of the variable $_SERVER where we can find information about the server environment and the client

## Project description 📋
_At this project, we are going to make an analysis about the local PHP server variables $_SERVER and $_SESSION, and put it into practice making a exercise that consist in create a login which will allow you to access another PHP file and view the content only if you are logged in_

### Documents
<ol>
  <li>Initial analysis</li>
    <ul>
      <li><a href="#### Analysis of the local PHP server variable $_SERVER">server_variables.php</a></li>
      <li><a href="#### Analysis of the local PHP server variable $_SESSION">session_variables.php</a></li>
      <li><a href="#### Server configuration">configuration.php</a></li>
    </ul>
  <li>Practical exercise</li>
    <ul>
      <li><a href="#### Index page">index.php</a></li>
      <li><a href="#### Panel page">panel.php</a></li>
      <li><a href="#### Validation page">validate.php</a></li>
      <li><a href="#### Close session">close_session.php</a></li>
    </ul>
</ol>

### Initial analyse
#### Analysis of the local PHP server variable $_SERVER
_At the server_variable.php document you can see the content on the server variable_

#### Analysis of the local PHP server variable $_SESSION
_At the session_variable.php document you can see how a session is started and the content on the session variable_

#### Server configuration
_At the configuration.php document you can see the changes that have been applied to the php.ini file_

##### Locate and edit php.ini file
<ul>
  <li>Change the time zone to Europe / Madrid</li>
  <li>Maximum execution time "max_execution_time" from 30 to 60 seconds</li>
  <li>Add a comment at the end of the file</li>
</ul>

### EXERCISE
_The exercise consist in a login which will allow you to access another PHP file and view the content only if you are logged in._

#### Index page
_Here is the login page which ask for email and password. If you log in or are already logged in, you will be automatically redirected to the second file "panel.php"_

#### Panel page
_Here is going to be indicate on the screen if the user who is accessing it is logged in or not. This page also contain a button to log out (which will destroy the current session) and redirect you to the "index.php" file._

#### Validation page
_Here is going to be done all the login validations. This page is going to recive the form data by the POST method and is going to redirect the user depending on whether the login is correct or not._

#### Close session
_This file is going to destroy the session and redirect to the login page._
