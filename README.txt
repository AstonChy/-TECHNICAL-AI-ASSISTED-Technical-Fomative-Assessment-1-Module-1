POS CodeIgniter 4 Activity Files

These files are meant to be copied into the CodeIgniter 4 project created in step 1.

1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Copy the contents of its app folder into your project's app folder.
4. In your project root, rename env to .env if needed.
5. Set this in .env:

   app.baseURL = 'http://localhost:8080/'
   CI_ENVIRONMENT = development

6. Open the project terminal and run:

   php spark serve

7. Test these pages:
   http://localhost:8080/
   http://localhost:8080/about
   http://localhost:8080/customers
   http://localhost:8080/users

Important: This is not a complete CodeIgniter installation. It contains the
activity files and should be copied into the CodeIgniter project from step 1.
