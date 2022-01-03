# Flask-tutorial

Think about the user typing in your website URL in their browser.

When the user enters the URL in the browser, they are making a request to the web server.

As a developer, you would have to write some Python code to handle requests and deal with CGI which is a standard environment that Python and other web development programming languages use to create web pages dynamically. And you would have to write the same code over and over again for every web app that you built.

Now, because that is a repetitive task, someone put all that code together and created a bunch of Python files. These bunch of files were called flask. So, flask is a framework which when loaded in Python automatically executes the routine code and lets you focus on the specific parts of your website.

HTML is a markup language used to render webpages. Try to remember these three things about creating HTML pages:

    An HTML document must start with a declaration that specifies the document type: <!DOCTYPE html>.
    The HTML document itself always begins with <html> and ends with </html>.
    The visible part of the HTML document is between <body> and </body>. The area outside that is used to reference Javascript files, CSS, or other features.
    
    
Remember that HTML template files HTML goes inside the templates' folder. CSS stylesheets are considered static files. There is no interaction with their code, like there is with HTML templates. Therefore, flask has reserved a separate folder where you should put static files such as CSS, Javascript, images or other files. That folder should be created by you and should be named static. It’s also good practice to create another folder inside static and name it css.

Venv is a Python standard library that creates a virtual environment with an isolated Python installation. That installation will serve only for our flask web application, and not any other purposes. That allows us to deploy a clean application to the online server. venv comes shipped with Python, so you don’t need to install it.
