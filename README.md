# Practice 1.1 - Installing and configuring Web Development Tools

### 2DAW - DWEC Bilingual. 

> **Student Name**: Oscar Carmena Martin

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
    I had it already installed.
2. **Create a new folder called `p1.1-frontend-tools`and open it as a workspace in VSCode. Copy the current `README.md` inside it**.
    ![Text to display](img/pregunta2.png)
3. **What functionalities do the following VSCode extensions add?**
   - **Bootstrap 5 quick Snippets** It helps you to link bootstrap to your html and helps with the code
   - **Live Server** It lets you create a server where you can see what you are doing while you are doing it
   - **Prettier** It gives color to the letters depending what they are(gives one color to tags, other to variables...)
   - **Markdown All in One** It helps you to write in markdown 
4. **Install the extensions listed in the previous point in VSCode**.
   
   
   
   
    ![Text to display](img/pregunta4.png)
    
    ![Text to display](img/pregunta4(1).png)



5. **What other extensions do you know that you consider interesting for developing in JavaScript**?
   - JavaScript(ES6) code snippets
   - Reactjs code snippets
   - ESLint
6. **Find in VSCode the option in `Settings` to `Format On Save` and activate it. What effect has this option?**
    It formats the document/program just by clicking save.
### Create a Hello World in JS

7. **Create an `index.html` file inside your worspace folder.**
    
    
    
    ![Text to display](img/pregunta7.png)
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

     ![Text to display](img/pregunta8.png)
9.  **Create a new file called `app.js` and add this two lines**

    ````javascript
    console.log("Hello Console!")
    document.body.innerHTML = "<h1>Hello document!<h1>"
    ````

    ![Text to display](img/pregunta9.png)
10. **Import the script in your html using one of the techniques explained in class. Explain here the technique, show the code and justify why did you choose this technique**.
    I've put the src to link the JavaScript to the HTML, i used that technique because it's the correct way to link an external JavaScript file.


     ![Text to display](img/pregunta10.png)
11. **Launch `index.html` in Live Server and check that the script is running. Click right button and select inspect to show the developer tools and take a look on the console.**
    

    ![Text to display](img/pregunta11.png)


12. **Change some message in the JS code and sava changes. You can check that Live Server refreshes the web page.**


     ![Text to display](img/pregunta12.png)


### Create a simple form with Bootstrap 4. 

13. **At this point, we are going to create a page called `form.html` starting from the `Bs5-$` template provided by the Bootstrap extension we added. What files does this template import in the html by default?**
    It imports these 3 files:
    - https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css
    - https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js
    - https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js
   
14. **Create a `<div>`with the class `.container` to wrap all the sections in the web page**
    

    ![Text to display](img/pregunta13.png)

    
15. **Add a standard navigation bar inside the nav area using the `bs5-navbar-standard` snippet inside the container**
    

    ![Text to display](img/pregunta15.png)

16. **Inside the main area create a form using Bootstrap to collect data from a new user who wants to register at an academy that offers courses. We can copy code from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/forms/overview/)**. 


    ![Text to display](img/pregunta16.png)

### Install Git, and upload your project to GitHub

17. **Install [git](https://git-scm.com/) in your computer**. I had it already installed
    
18. **Init the git project**


    ![alt text](image-2.png)
    

19. **Log in to your GitHub account provided by IES Azarquiel** I have already done it
    
20. **Follow the teacher on GitHub at the following link: [https://github.com/jeatzr/](https://github.com/jeatzr/)** Done
    
21. **Create a new empty project on GitHub named `p1.1-frontend-tools`.**Done
    
22. **Follow the instructions in the command line provided by GitHub to add your files, create the first commit and push it. Notice that in out case we have to add all files to the staged area with `git add .`, not just`git add README.md`**  Done
    
23. **To finish, submit the link of your GH repo to the task in our Classroom.**"# p1.1-frontend-tools" 
