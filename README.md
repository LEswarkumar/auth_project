**Django User Authentication Application**


**Overview**
This is a Django-based web application that includes user authentication features such as sign-up, login, password management, and restricted pages for logged-in users. The app provides a clean and simple interface to handle user accounts.

**Bootstrap**
Use Bootstrap for formating the templates.

**Features**
**Sign Up:**

Users can register with a username, email, and password.
Automatic login after successful registration.

**Login:**

Allows users to log in using their username or email and password.

**Forgot Password:**

Users can request a password reset via email.

**Change Password:**

Authenticated users can update their password.

**Dashboard:**

Restricted to logged-in users. Displays a greeting and links to profile and logout.

**Profile:**

Shows user details (username, email, date joined, etc.). Restricted to logged-in users.

**Logout:**

Logs the user out and redirects to the homepage.

**Application Flow**

**Homepage:**

Accessible to everyone.

**Authentication Pages:**

Sign Up, Login, and Forgot Password.

**Restricted Pages:**

Dashboard and Profile (only accessible to authenticated users).
