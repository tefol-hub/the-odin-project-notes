# Prerequisites 

## How Does the Web Work?

### Knowledge Check
1. **What is a web server?**
   This is a server that hosts a website and sends requested webpages that are related to this website to be displayed in the browser.

2. **What is a network?**
   It is a group of computers or devices that are connected to and can communicate with each other through wires (communication can also happen wirelessly) connected to a switch.

3. **What is the internet?**
   It is a larger global network connected to multiple smaller networks together through routers and ISPs.

4. **What is an IP address?**
   It is a collection 4 sets of numbers demarcating the location or address of a device/computer that is connected to the internet.

5. **What is a router?**
   It is a special computer that connects multiples networks together. It particularly connects them to the internet by routing messages or packets from the networks to their destination by traversing them through a network of ISPs and other routers, ie the internet.

6. **What is an ISP?**
   It is a company or organization that is in charge of managing multiple routers on the internet and providing internet access to networks and devices.

7. **What are packets and how are they used to transfer data?**
   They are a collection of 1s and 0s representing chunks of data stemming from one computer and being sent over the internet to another computer or device.

8. **What is a client?**
   This is a computer/device that makes/sends requests to other computers, namely servers.

9. **What is a server?**
   Servers are computers that respond to client requests by executing said requests and/or sending back a response of the requested data.

10. **What is a web page?**
    It is a page or document from a website hosted on a server, that is served or sent to be displayed on a clients browser.

11. **What is a web browser?**
   It is a technology or service that displays websites and their web pages to the client device.

12. **What is a search engine?**
   It is a web service that allows you to query and find websites in a web browser.

13. **What is a DNS request?**
   It is a request to DNS servers to locate the IP address of the domain name that is being queried 

14. **Which browser are you currently using?**
   I am currently using Google Chrome.

15. **In your own words, describe the process that takes place when you initiate a search on google.com in terms of what we discussed.**
   When I type google.com in the search bar and click enter, if the IP address of the domain name I typed in is not located in memory then my computer makes a request to a DNS Resolver. The resolver will look for the google.com IP address and if it isn't available in memory it then queries the Root DNS Server. If the Root DNS Server does not find the address in memory it directs the resolver to the TLD (Top Level Domain) Server with .com domains and if it also doesn't have it the TLD server directs the resolver to the Authoritative Domain Name Server. This server which holds the IP address of google.com wull then return it to the resolver which then in turn returns it to my device/computer.


## Installations

### Knowledge Check
1. **What operating systems does The Odin Project support**
   Unix based OSs like ubuntu and macos.
   
2. **What browser does The Oding Project support?**
   Google Chrome
   
   
## Text Editors

### Knowledge Check
1. **What is a code editor**
   A special tool that allows you easily write, edit and configure.
   
2. **What code editor does The Oding Project support?**
   Visual Studio Code.


## Command Line Basics

### Knowledge Check
1. **What is the command line?**
   The command line is a program that allows you to type out instructions to your computer.

2. **How do you open the command line on your computer?**
   Ctrl + alt + T at least on linux.

3. **How can you navigate to a particular directory?**
   By using the cd command followed by the directory.

4. **Where will cd on its own navigate you to?**
   Back to the home directory.

5. **Where will cd .. navigate you to?**
   To the parent directory.

6. **How do you display the name of the directory you are currently in?**
   By entering the command pwd which stands for "print working directory".

7. **How do you display the contents of the directory you are currently in?**
  By entering the command ls.

8. **How do you create a new directory?**
   By entering the command mkdir followed by the directory.

9. **How do you create a new file?**
   By entering the command touch followed by the name of the file and its type.

10. **How do you destroy a directory or file?**
    By entering the command rm with the -r argument (recursive) to delete both a directory and its contents thus the command in full will be rm -r -i [directory/], the i flag being for shell to ask for confirmation before executing the command. 

11. **How do you rename a directory or file?**
    By entering the command mv -i (optional to make shell ask for confirmation) followed by the current file or directory name followed by the new name of the file or directory. ie, mv -i [current-name] [new-name]


## Setting up Git

### Knowledge Check
1. **What is Git?**
   It is a file version control system.

2. **What is GitHub?**
   It is a service that allows you host programming projects online and manage them with git.

3. **What authentication method are we setting up with Git: SSH or HTTPS?**
   SSH

## Introduction to Git

### Knowledge Check
1. **What kind of program is Git?**
It is a Version Control System that keeps track of any changes made and saved to a project.

2. **What are the differences between Git and a text editor in terms of what they save and their record keeping?**
A text editor saves the text editor keeps only the latest record of the text in a file whereas git keeps a record or snapshot of every single save along with each of the changes made to the file.

3. **Does Git work at a local or remote level?**
It works at a local level.

4. **Does GitHub work at a local or remote level?**
GitHub works at a remote level.

5. **Why is Git useful for developers?**
It helps with auditing their work and track changes they make to their code bases, which is especially useful if errors are made in the development process, whereby the developer can simply revert back to prior versions of the code.

6. **Why are Git and GitHub useful for a team of developers?**
They allow for easy collaboration on a shared codebase whereby changes can easily be audited and merged.


## Git Basics

### Knowledge Check
1. **How do you create a new repository on GitHub?**
By clicking the + button on the top right of your github page and clicking on "New Repository".

2. **How do you copy a repository onto your local machine from GitHub?**
By navigating to your project directory in the terminal and entering "git clone git@github.com:repo-ssh-link.git".

3. **What is the default name of your remote connection?**
It is "origin".

4. **Explain what origin is in git push origin main.**
The "origin" refers or points to the specific remote that is connected to your project.

5. **Explain what main is in git push origin main.**
The "main" keyword refers to the main branch of your project.

6. **Explain the two-stage system that Git uses to save files.**
It first adds them to the staging area with the command "git add ." or "git add file-to-commit.txt", then create a snapshot of the file in the database with "git commit -m "Message explaining changes made"".

7. **How do you check the status of your current repository?**
By entering "git status".

8. **How do you add files to the staging area in Git?**
By entering the command "git add " followed by the file you want to add or the whole directory with a period(.).

9. **How do you commit the files in the staging area and add a descriptive message?**
With the command "git commit -m "descriptive message"".

10. **How do you push your changes to your repository on GitHub?**
With the command "git push origin main" which applies your changes specifically to the main branch.

11. **How do you look at the history of your previous commits?**
With the command "git log".
