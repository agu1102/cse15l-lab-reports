# Lab Report 1

**Kathy Gu**

For taking the course of CSE15L, it is essential for you to know how to log into your course-specific account `ieng6` .

* The first step is setting up your CSE15L account. It has been already created to your school account as a additional account. By log into [Link]https://sdacs.ucsd.edu/~icc/index.php using your school account, you can check your specific ETS account associated with your student ID. To reset your password, follow the exact steps in the tutorial [Link]https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit.

* The second step is installing VScode in your computer. The download website for Visual Studio Code is [Link]https://code.visualstudio.com/ and follow the instructions to install the correct version of it depending on your computer operating system. The opening page of VScode looks like this. ![image](https://user-images.githubusercontent.com/122497644/212789872-37c5bc7e-b632-4b25-a4a2-c0a1cbd7c6a3.png)

* The third step is to do the remotely connect using the VScode you just installed and your CSE15L account. For Window users, firstly install git in your computer. https://gitforwindows.org/ and then follow the instructions [Link]https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994 to use bash in VScode. Then, by opening a terminal in VScode and use ssh to log into your specific account. "$ ssh cs15lwi23(your course specific account letters)@ieng6.ucsd.edu" , typing "yes" as you are connnected to this server the first time, and finally by typing your password and pressing enter, your terminal is connected to a computer in the CSE basement. As you successfully finish the steps, your page would by look like this. ![image](https://user-images.githubusercontent.com/122497644/212798969-cc3d4d58-3ab6-4966-b415-306919f46afc.png)

* The fourth and also the final step is to try to run some commands for example cd, ls, pwd, mkdir, and cp on both your computer and the remote computer. There are some useful commands to try: `cd ~`;`cd`;`ls -lat`;`ls -a`;`cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`;`cat/home/linux/ieng6/cs15lwi23/public/hello.txt`;etc. Try to understand what each commans means. <img width="838" alt="cda4202fdcf0c8e01e94ce4955ef2f0" src="https://user-images.githubusercontent.com/122497644/212794923-a5435e49-4395-4100-b767-750402dd2bae.png">

* To log out the remote server, you can to "Ctrl-D" or by typing in command "exit". 

And those are all the steps you need to follow for the remote access.:)
