# Django Personal Blog App

<img src="previews/demo.gif" height="300"/>

<br/>

## Learning Goals and Objectives
* **The primary goal of this project is to gain hands-on practice for developing web applications using Django.<br/>This project serves as a practical application to reinforce Django concepts and best practices such as listed below.**
   <details>
      <summary>Django Project Structure</summary>
      <p>Understand the project's folder structure, including the settings, URLs, and app organization in a Django project.</p>
   </details>
   <details>
      <summary>Views and Template</summary>
      <p>Gain experience in creating views and templates to render dynamic content and user interfaces.</p>
   </details>
   <details>
      <summary>Understanding Models and Databases</summary>
      <p>Learn how to define database models, create migrations, and manage the database schema using Django's Object-Relational Mapping (ORM)..</p>
   </details>
   <details>
      <summary>CRUD Operations</summary>
      <p>Learn how to perform Create, Read, Update, and Delete (CRUD) operations, which are fundamental to web applications.</p>
   </details>
    <details>
      <summary>Form Handling</summary>
      <p>Understand form handling in Django, including form validation and submission.</p>
   </details>

* *In the context of this personal blog, only the admin or super user can create and publish posts from admin interface.<br/>Readers, however, can directly comment on posts without the need for user registration, simplifying the user experience.*

## Installation
To run this Django Personal Blog App, you need to have Python on your system. If you haven't already, you can download and install them from the following link:
- [Python](https://www.python.org/downloads/)

Once you have Python and Django installed, you can follow these steps to set up the project:

1. Clone this repository to your local machine or download and extract the ZIP file.

2. Navigate to the project directory using your terminal or command prompt.

3. Create a virtual environment to isolate your project dependencies:
   ```bash
   python -m venv myenv
   ```

4. Activate the virtual environment:
     ```
    > On windows -> venv\Scripts\activate
    > On linux -> source myenv/bin/activate
     ```

5. Install the project dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```

6. Run the database migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

7. Create a superuser account to manage the blog (Optional, as the test superuser is included in the project):
   ```bash
   python manage.py createsuperuser
   ```

## Getting Started
After completing the installation, you can start the development server and access the Django Personal Blog App by following these steps:

1. Start the development server:
   ```bash
   python manage.py runserver
   ```

2. Open a web browser and navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access the blog homepage.

3. To access the admin panel, go to [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/), and log in with the superuser credentials created earlier.<br/>Alternatively you can login using the test superuser with the below credentials.
     ```
    > Username -> blog_admin
    > Password -> admin@1234
     ```

## Usage
The Django Personal Blog App provides the following features:

### 1. Read Posts
- Users can view all blog posts on the homepage.

### 2. Comment on Posts
- Users can leave comments on blog posts. Comments can be added at the bottom of each blog post.

### 3. Filter Posts by Categories
- Posts can be categorized by topics, and users can filter posts based on these categories.

### 4. Post Management
- Admin users can create, edit, and delete blog posts through the admin panel.

<br/>

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

<br/>

#### **Thank you for using the Django Personal Blog App! If you have any questions, suggestions or encounter any issues, please don't hesitate to [DM me](https://twitter.com/randomdotfloat)**