

# Git clone and Enjoy! $:)$

## About this repositary

This contains serevral books and lecture notes (lecture notes are mostly related to high energy physics).

## For those who are new to Git

### Git Installation:
*  linux users to install Git use
    ```
    bash
    sudo apt install git
    ```
* For winodows users you can install Git using winget
    ```
    Command Prompt
    winget install --id Git.Git -e --Source Winget
    ```
### Cloning Git repositary:
* For linux users
    ```
    bash
    git clone git@github.com:abasak08/physics_books.git
    ```
* For Windows users
    ```
    Command Prompt
    git clone git@github.com:abasak08/physics_books.git
    ```
    
*If you face any issue feel free to contact me*
* Email: [anirbanb.physics@gmail.com](mailto:anirbanb.physics@gmail.com)  
* GitHub : [@abasak08](https://github.com/abasak08)

<details>
<summary>Having Problem while viewing the pdf in local machine</summary>

* If you having problem cloning then use Git LFS to pull the repo.
    * To install lfs `git lfs install`
    **Hopefully you have Git installed in your machine**
    * To add remote url use `git remote add origin git@github.com:abasak08/physics_books.git`
    * If you already have a `Git origin` (`.git`) you need to modify that using: `git remote set-url origin git@github.com:abasak08/physics_books.git`
      * To check you already have an remote `origin` or not use : `git remote -v`
      * Should show something like this:
        ```
        bash
        origin	git@github.com:abasak08/physics_books.git (fetch)`
        origin	git@github.com:abasak08/physics_books.git (push)`
        ```
        * *If you see something like this you are good to go.* 
    * To pull the repo use : `git lfs pull`
* **I think this will solve your issue. If not feel free to contact me (email:`anirbanb.physics@gmail.com`)**
* If you want to contribute feel free to ask me I will be very glad to add your collection to this repo.

</details>