# Preparing Your Windows OS for Development
## Installing Git on Your Machine
You can follow along with the steps listed below or you can also follow along with the video I created on [YouTube](https://youtu.be/9vGEInAqHZs).
1. Open your favorite browser along with your favorite search engine
1. Search for "git download"
   1. Click on the "Go to download" link
   1. https://www.git-scm.com/downloads
1. The website automatically detects the operating system
   1. click on the link to install git for Windows
1. Once the download completes
   1. Click on the installer to begin the install process
   1. By default, Windows will ask you if you want t allow this app to install
   1. Click "Yes" to begin installing
1. First screen is the license agreement - this is pretty standard for many application you're installing.
   1. You're welcome to read thru it otherwise click on "Next"
1. Next is the location where the application will be installed
   1. For most users you can accept the default
   1. Click on "Next"
1. Next is the components of the application that you want to install
   1. The only option I was recommend here is if you want a short cut on your desktop
   1. Otherwise, leave the defaults and click "Next"
1. Next we'll see the name that you would like to use when searching for the application on the Windows Search
   1. Again, you can leave the default setting
   1. Click "Next"
1. Next we'll see a selection for an editor used when adding comments
   1. We'll going to talk more about this in future.
	 1. It's important to learn how to use the Vi Editor. 
	 1. For now you can accept the default
	 1. Click "Next"
1. Next you'll need to select the command line to use
	 1. I recommend you select "Use Git from Git Bash only"
   1. The reason I like this choice is because as developers we'll finding the need to depend on the command line.
   1. Learning the Git Bash command line sets you up for an easy transition to the command line of other Operating Systems such as Mac OS and Ubuntu Linux
   1. Click "Next"
1. Next you'll be asked to select what SSL/TLS library to use
   1. What are all these acronyms?
   1. SSL stands for "Secure Socket Layer"
   1. TLS stands for "Transport Layer Security"
   1. Together they secure the communication between the Git Host provider and your machine
   1. For our use, we'll accept the default setting of "Use the OpenSSL library"
   1. Click "Next"
1. Next you'll need to select "How to treat line endings"
   1. The reason you need to make a selection here is because Windows treats line endings different than other Operating Systems.
   1. The default selection of "Checkout Windows-style, commit Unix-style" allows for the best flexibility.
   1. This will allow you to collaborate with others that are using other Operating Systems such as Mac OS & Ubuntu Linux.
1. Next you'll need to select the "Terminal Emulator"
   1. TTY stands for "TeleTYpewriter"
   1. For our use, we'll be selecting the default TTY Emulator call "MinTTY"
   1. Click "Next"
1. Finally, you can select which features you want to enable
   1. The default settings are fine
      1. Leave the first 2 options enabled
      1. Disable the third option "Enable symbolic links"
      1. Click "Install"
1. Once the install is complete
   1. Select the option "Launch Git Bash"
   1. Unselect "View Release Notes"

Once you have Git installed on your machine continue with the following lectures and return here for the challenge after learning a little about Git Source Control.

## Creating an account on https://www.github.com
1. You can watch this on creating an account on Github
   1. https://youtu.be/cxDC8_cYdl4

## Git Workflow
In this lecture you will learn about Git and it's workflow.

1. Clone
1. Branching
1. Committing your changes
1. Pushing to Github
1. Performing a Pull-Request
1. Pull changes from Github
1. You can watch the lecture to learn more about the workflow
   1. https://youtu.be/BwzsmcFHDGw
   
## The Challenge
Once you have completed the lecture take some time to complete the following challenges:

1. Create a repo on Github called `datascripts`
1. Add a ReadMe file
1. Make it private
1. Clone it to your machine
1. Modify the ReadMe file
   1. Make sure you follow the proper workflow prior to modifying

You'll need this repository to move on to the next lecture. Good luck!
