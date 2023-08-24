# Intelligent-Video-Surveillance-System-using-Deep-Learning
Image Processing Project -------Readme file---------

Dataset: The following link can be used to download the dataset used for this code- on clicking download will start #http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/Avenue_Dataset.zip

Softwares required: FFmpeg and Python version 3.8 and above and any editor that runs python code -->FFmpeg Here are the steps to download and set up FFmpeg 4.4 version on both Windows and Ubuntu:
For Windows:

Step 1: Download FFmpeg
	- Go to the FFmpeg website: https://ffmpeg.org/download.html
	- Scroll down to the "Windows" section.
	- Click on the "Windows builds" link.
	- Under the "Release" section, click on the link corresponding to "ffmpeg-*-static.zip" for the latest 4.4 version.
	- Save the downloaded zip file to your desired location.

Step 2: Extract FFmpeg
	- Extract the contents of the downloaded zip file to a folder of your choice.

Step 3: Add FFmpeg to System Path (Environment Variables)
	- Open the Start menu and search for "Edit the system environment variables" (or "Environment Variables").
	- Click on "Edit the system environment variables" to open the System Properties dialog.
	- In the System Properties dialog, click on the "Environment Variables" button.
	- In the "System Variables" section, scroll down and find the "Path" variable.
	- Select the "Path" variable and click on the "Edit" button.
	- In the "Edit Environment Variable" dialog, click on the "New" button.
	- Enter the path to the folder where you extracted FFmpeg (e.g., `C:\path\to\ffmpeg\bin`) and click "OK" on all open dialogs to save the changes.

Step 4: Verify FFmpeg Installation
	- Open a new command prompt (CMD) or PowerShell window.
	- Type `ffmpeg -version` and press Enter.
	- If FFmpeg is properly installed and added to the system path, it will display the version information.

For Ubuntu:

	Step 1: Update System Packages
		- Open a terminal.
		- Run the following commands:
		```
		sudo apt update
		sudo apt upgrade
		```

	Step 2: Install FFmpeg
		- Run the following command:
			sudo apt install ffmpeg
		- Enter your password if prompted and confirm the installation.

	Step 3: Verify FFmpeg Installation
		- In the terminal, type `ffmpeg -version` and press Enter.
		- If FFmpeg is installed correctly, it will display the version information.

That's it! You have now downloaded and set up FFmpeg 4.4 version on both Windows and Ubuntu.
