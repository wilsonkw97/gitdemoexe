<h1 align="center">Forward School Demo</h1>

<!-- Table of Contents -->
# Table of Contents
<li>
    <a href ="#Getting-Started">Getting Started</a>
</li>
<li>
    <a href="#Start-building">Start building</a>
</li>

<!-- Table of Contents -->
## Link to Github
<a href="https://github.com">Access GitHub</a>

<!-- Getting Started -->
## Getting Started
Some steps on getting your Git setup on your local environment

* Getting a SSH key 
    ``` sh
    ssh-keygen -t rsa ## Using the default name by leaving blank at file name will store at your C drive under your Users folder.
    ```

* Creating a directory for you to work with Git
    ```sh
    mkdir "any name you like"
    ```

* Creating files for your project
    ``` sh
    echo "text to display">> filename #.md is for markdown file, .txt is for text file
    ```

* Change your working directory and initialize git
    ``` sh
    cd "your directory name"
    git init
    ```


<!-- Building up your GitHub repository -->
## Start building

* Add the files you created to this git environment
    ``` sh
    git add filename #you can use git add . if only one file
    ```

* Creating a commit
    ``` sh
    git commit -m "any name you like"
    ```

* Create a main branch
    ``` sh
    git branch -m main
    ```

* Link your local to your GitHub repository
    ``` sh
    git remote add origin "url/ssh" #Using SSH allows a smoother connection and not requiring you to authenticate every single time
    ```

* Pushing your files to the main branch of the repository
    ``` sh
    git push -u origin main
    ```