# Practice 1.1 - Installing and configuring Web Development Tools

### 2DAW - DWEC Bilingual. 

> **Student Name**:  Aitor González Barrera

#### Files included in this repository:

Ennumerate and explain each one of the files included in this repo.

- File 1
- File 2
- Etc...

#### Instructions: 

- Fill your name and lastname and answer the questions in the current `README.md` file. You have to submit the activity as a GitHub repo link that has to include the 

- You can add images to this tocument with the syntax:

    ```md
    ![Text to display](link/to/the/image)
    ```

- Any other question about Markdown language you can find in the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### Install and configure VSCode

1. **Install `VSCode` in your computer**.

    I have already installed from last year.

2. **Create a new folder called `p1.1-frontend-tools`and open it as a workspace in VSCode. Copy the current `README.md` inside it**

    Done.

    ![vs-installed](img/Captura%20de%20pantalla%202024-09-16%20114101.png)

3. **What functionalities do the following VSCode extensions add?**
   - **Bootstrap 5 quick Snippets**
    It makes working with Bootstrap framework easier by giving shortcuts to funcionalities of this framework.

   - **Live Server**
    This extension creates a local server that simulates the use of a server so you can test your code.

   - **Prettier**
    It changes the code color and format so it can be more reable and pleasing for our eyes.

   - **Markdown All in One**
    It provides shortcuts and tools to improve the ways to make markdown files.

4. **Install the extensions listed in the previous point in VSCode**.

    ![extesions-installed](img/installed-extesions.png)

1. **What other extensions do you know that you consider interesting for developing in JavaScript?**
   - HTML CSS Support: 
   - IntelliSense for CSS class names in HTML
   - JavaScript (ES6) code snippets

2. **Find in VSCode the option in `Settings` to `Format On Save` and activate it. What effect has this option?**

    ![extesions-installed](img/format-on-save.png)

    I dont see a effect after activation of this option.

### Create a Hello World in JS

7. **Create an `index.html` file inside your worspace folder.**
    
    Done.

    ![extesions-installed](img/create-index.png)

8. **Create the basic html structure using the `!` snippet and change the title to 'Hello World'**

    ````html
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Hello World</title>
    </head>
    <body>
      
    </body>
    </html>
    ````

    Created with the `!` snippet:

    ![html-snippet](img/image.png)
    ![hello-world](img/hello-world.png)

9.  **Create a new file called `app.js` and add this two lines**

    ```javascript
    console.log("Hello Console!")
    document.body.innerHTML = "<h1>Hello document!<h1>"
    ```

    Just created:

    ![js-created](img/js-created.png)

10. **Import the script in your html using one of the techniques explained in class. Explain here the technique, show the code and justify why did you choose this technique**.

    ![linking-js](img/linking-js.png)

    I used the external technique that means i used a link to refer to the script in another file.

    I placed the script tag at the end so it will be load after the rest of the page has been already loaded.

    I prefer this because i think it is cleaner to see the code in differents files even if in this case the code is just two lines. 

11. **Launch `index.html` in Live Server and check that the script is running. Click right button and select inspect to show the developer tools and take a look on the console.**

    It is working!
    ![script-running](img/script-running.png)

12. **Change some message in the JS code and sava changes. You can check that Live Server refreshes the web page.**

    Test:

    ![test-js](img/prueba-js.png)

    It works.

    ![result-js](img/resultado-js.png)

### Create a simple form with Bootstrap 5. 

13. **At this point, we are going to create a page called `form.html` starting from the `Bs5-$` template provided by the Bootstrap extension we added. What files does this template import in the html by default?**

    It imports:
    1. **Bootstrap css in the header:**
    
        ![importedCss](img/importedCss.png)
    
    2. **Pooper javascript in the body:**
    
        ![importedPopperJS](img/importedPopperjs.png)
    
    3. **Bootstrap javascript in the body:**
    
        ![importedBootstratJs](img/importedBootstratJs.png)

14. **Create a `<div>`with the class `.container` to wrap all the sections in the web page**

    Here:

    ![container](img/container.png)

15. **Add a standard navigation bar inside the nav area using the `bs5-navbar-default` snippet inside the container**

    Done:

    ![navbar](img/navbar.png)

    Result:

    ![navbar2](img/navbar2.png)


16. **Inside the main area create a form using Bootstrap to collect data from a new user who wants to register at an academy that offers courses. We can copy code from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/forms/overview/)**. 

    HTML:
    
    ![formHtml](img/formHtml.png)

    Outcome:
    
    ![form](img/form.png)

### Install Git, and upload your project to GitHub

17. **Install [git](https://git-scm.com/) in your computer**.
    
    Done:
    
    ![gitInstalled](img/gitInstalled.png)
    
18. **Init the git project**
    
    Result:

    ![init](img/init.png)


19. **Log in to your GitHub account provided by IES Azarquiel**
    
    ![LogIn](img/logIn.png)

20. **Follow the teacher on GitHub at the following link: [https://github.com/jeatzr/](https://github.com/jeatzr/)**
    
    ![followed](img/followed.png)

21. **Create a new empty repository on GitHub named `p1.1-frontend-tools`.**
    
    ![newRepository](img/newRepository.png)

22. **Follow the instructions in the command line provided by GitHub to add your files, create the first commit and push it. Notice that in out case we have to add all files to the staged area with `git add .`, not just`git add README.md`** 
    
    ![commit](img/commit.png)

23. **To finish, submit the link of your GH repo to the task in our Classroom.**

    ![submit](img/submit.png)