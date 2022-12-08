1)On GitHub.com, navigate to the main page of the repository.

2)To clone your repository using the command line using HTTPS, under "Quick setup", click

 . To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, then click

 . Empty repository clone URL button

 . Alternatively, to clone your repository in Desktop, click

 Set up in Desktop and follow the prompts to complete the clone. Empty repository clone desktop button

3)Open Git Bash.

4)hange the current working directory to the location where you want the cloned directory.

5)Type git clone, and then paste the URL you copied earlier.

$ git clone https://github.com/arsheriff2k3/file_transfer_app.git

6)Press Enter to create your local clone.

 msg: $ git clone https://github.com/arsheriff2k3/file_transfer_app.git

    Cloning into Spoon-Knife... remote: Counting objects: 10, done. remote: Compressing objects: 100% (8/8), done. remove: Total 10 (delta 1), reused 10 (delta 1) Unpacking objects: 100% (10/10), done.

    After Showing this msg Cloning was completed.Now you can change the code and create newproject.

 Finally we are going to run our project.



step 1 : Open our Project folder in Visual Studio Code and Open Terminal window, Now we need to install our project dependencies , so we open a terminal window. 
         Go to project path folder using 
         Command : cd 
         For mac Command : pipenv install |
         For windows Command : py -m venv .
         ![Screenshot (42)](https://user-images.githubusercontent.com/109596307/206517575-dec460df-bc57-4473-ba42-66591d3f8c56.png)

step 2 : Active our vitual environment.
         for mac :
         pipenv shell |
         for windows :
         foldername/Scripts/activate.bat
         ![Screenshot (43)](https://user-images.githubusercontent.com/109596307/202862087-1b5c864d-6063-455a-9833-bacfaf6a6738.png)

step 3 : Select python interpreter in vscode.
         1)Press the python show in the figure.
         ![Screenshot (44)](https://user-images.githubusercontent.com/109596307/202862136-8923f982-abb9-4d77-96dd-22c20200ad66.png)
         2)Select the path of interpreter.
         ![Screenshot (45)](https://user-images.githubusercontent.com/109596307/202862199-d5910807-8bd5-4640-9ce6-b7059e6faf81.png)
         for windows select scripts/pythow.exe as show in the picture below.
         ![Screenshot (48)](https://user-images.githubusercontent.com/109596307/202862352-fc7baff1-dc70-411e-9213-e15e0dfd37c5.png)
         3)successfully selected as show in the below fig.
         ![Screenshot (49)](https://user-images.githubusercontent.com/109596307/202862464-32508c49-29dc-4b17-bf9c-e8e4b80a3a7a.png)

step 4 : Run server command : python manage.py runserver
         ![Screenshot (56)](https://user-images.githubusercontent.com/109596307/202863116-047389d4-9573-4bef-84a0-4dade3196f9d.png)
         
Successfully our project run on localhost....
![Screenshot (61)](https://user-images.githubusercontent.com/109596307/206519170-52471105-d230-47ff-9583-b43fcdf1675d.png)
