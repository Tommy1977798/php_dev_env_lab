# php_dev_env_lab
 Lab Title: Setting Up a PHP Development Environment

 Objective:  
Set up and test a local PHP environment for application development.

Steps:  
1. Install Tools: Use XAMPP to set up PHP, Apache, and MySQL.  
2. Create a Project: Write a simple `hello.php` file:
3. Run the Environment:  
   - Start the server (e.g., `http://localhost/myapp`).  
   - For Docker:  
     ```bash
     docker run --rm -v $(pwd):/usr/src/myapp -w /usr/src/myapp -p 8080:80 php:8.2-apache
     ```  
4. Test: Open in a browser to confirm setup.

Outcome:  
A working PHP environment ready for development and testing.
