
# CREATE A WEB PAGE

    - Before we can create a window for our application, we need to create the content that will be loaded into it. In Electron, each window displays web contents that can be loaded from either a local HTML file or a remote URL.

    - For this tutorial, you will be doing the former. Create an index.html file in the root folder of your project:


    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="UTF-8">
            <!-- https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP -->
            <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self'">
            <title>Hello World!</title>
        </head>
        <body>
            <h1>Hello World!</h1>
            We are using Node.js <span id="node-version"></span>,
            Chromium <span id="chrome-version"></span>,
            and Electron <span id="electron-version"></span>.
        </body>
    </html>