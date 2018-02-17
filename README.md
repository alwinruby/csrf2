# CSRF Simple Example


1. Installations

        npm init -y

        npm install express body-parser --save


2. Create index.js file

        This is a simple application which will run on port 3000 and take an input from the application as a POST and simply take it to another page

3. Launch the app

        node .

        check on http://localhost:3000/

4. Create the POST

        http://localhost:3000/entry

5. Install CSRSF and cookie-parser

        This implements an anti csrfToken

        npm install cookie-parser csurf --save


6. Amend index.js

        add csrf elements

        use the csrf Middleware


7. Use http://csrf-attack.glitch.me/ to attack the domain.
