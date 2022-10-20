<p align="center"><img src="assets/hacktoberfest-header.png" alt="hacktoberfest" width="100%"/></a></p>

# Hello Hacker !!

Welcome to Hacktoberfest 2022! Begin your Open Source Journey as a contributor by learning to make Pull Requests to a repository. What better place than here to do the same!

## Make your first PR!

1. Fork this repository to your account by clicking the **Fork** button on this repo



![image](https://user-images.githubusercontent.com/92500255/196726470-ee7a9874-c2e4-4bcc-a8e1-01eed8174c73.png)

2. You now have this repo in your github account. You must be able to see it in `github.com/your-github-username/hacktoberfest-2022`

3. Go ahead and **clone** this repository from your account to your PC. At this point, make sure you have Git installed in your PC. Refer this [documentation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) from git for instructions. By using the command
   `git clone https://github.com/<your-github-username>/hacktoberfest-2022` you can clone the repository.Now, you will find this repository/folder in your PC.

4. Open [Google-Colaboratory](https://colab.research.google.com/) in your browser and open a New Notebook.

![image](https://user-images.githubusercontent.com/92500255/196042622-c7de2849-95b0-409b-8c35-827cc9d3d71a.png)

5. Click on Connect 
![image](https://user-images.githubusercontent.com/92500255/196051258-2f9cd23d-ea24-4a2e-a4c9-342b845435fa.png)


5. In the new notebook,

   - Copy
   
    ```Python
   !pip install pyfiglet
   import pyfiglet as pf
   name=input('\n\n\nEnter your name: ')
   f = pf.figlet_format(name, font = "slant")
   print(f)  
    ```
   and paste it in the code cell. Click on the run button to execute the code to get the output as follows:
  ![image](https://user-images.githubusercontent.com/92500255/196051862-1f38d3b8-7fdc-4d87-98ff-47822c95aae7.png)

   
6. Enter your name, and take the screenshot of the output
![image](https://user-images.githubusercontent.com/92500255/196053364-618d432c-f25d-4afa-8108-e8a217246ef3.png)



7. Now, save this screenshot in the Contributors/Screenshot folder , in the repository cloned in Step-3. Make sure to rename the screenshot with your name. For example: `screenshot_<your-name>`


![image](https://user-images.githubusercontent.com/92500255/196086967-45cccdb4-15da-4653-b756-c94490b0045f.png)



8. Open the Contributors folder **README.md** using your favourite text editor and follow the following steps: 
   - Copy
      ```
      <tr>
      <td align="center"><a href="https://github.com/vishalj0501"><img src="https://avatars.githubusercontent.com/u/92500255?s=40&v=4"                   
      width="100px;" alt=""/><br /><sub><b>Vishal</b></sub></a><br /></td>
      <td align="center"><img src="Screenshot/screenshot_vishal.png"></td>
      </tr>
      ```
      
   and paste it in a newline just after the arrow shown in the below image.
![image](https://user-images.githubusercontent.com/92500255/196140583-cd545011-6dc2-4334-aad5-3e3659179156.png)


   
   and then change the `href` link with your GitHub account link, the First img src link with your avatar link and name with your actual name.
To get avatar link follow these steps:
 - Login to your Github account and click on the profile icon which appears at the left most side of the page.
![image](https://user-images.githubusercontent.com/92500255/196055705-c658217e-d34f-471d-982e-94993a616523.png)
- Then right click on the big avatar which appears at the left side of the screen.

![image](https://user-images.githubusercontent.com/92500255/196728483-e20e7800-8fef-4bf1-8000-ad35173a0916.png)


**Cool!** you have copied the avatar link now you have to just paste it in place of the first img src link.


and then the Second img src - the path of the screenshot which in the Screenshot folder: `Screenshot/<screenshot_your-name>`
 
 
9. After doing all these, save the file and close the editor.

10. Now commit your changes by following the below steps

   - Open terminal/command prompt inside the cloned folder
   - Run `git add .` to stage the file for committing.
   - Let's commit! Run `git commit -m "Your commit message"` Get creative with your commit message. You can follow the        below format
     - `"[your name]: Add me as contributor"`
   - Now let's get these changes to your GitHub repo. Run `git push origin main`
 

11. You are almost done! Now head over to the original [repository](https://github.com/vishalj0501/hacktoberfest-2022) from which you forked and click on **Pull Requests**
   ![image](https://user-images.githubusercontent.com/92500255/196056260-f18c7e66-ed4c-4d91-845f-47da947f6857.png)

12. From here, I'll leave you on your own. Make a stunning PR using this flashy green button
![image](https://user-images.githubusercontent.com/92500255/196056387-8e4d4b17-db1b-4b90-ad46-b7e613214c41.png)
   
13. Google will be your best friend in case you get stuck at any point from now. Now go ahead and make your first cool PR!!

