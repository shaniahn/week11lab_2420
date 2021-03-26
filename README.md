# week11lab_2420

# How to Install & Use the Weather Script, Service File, and Timer

1. Download the 3 files as a ZIP.
2. Unzip the files.
3. Create a new directory called documents under your home (~) directory.
4. Move the currentweather file into the newly created directory called documents. 
5. While in the ~/documents directory, type in the command 'chmod +x currentweather'.
5. Move the weather.service and weather.timer files into your ~/etc/systemd/system directory.
6. While in the ~/etc/systemd/system directory, type in the command 'sudo systemctl daemon-reload' and press the Enter key. This will update the list so that systemctl is aware of all unit files.
7. While in the same directory as Step 6, type in the command 'sudo systemctl start weather.timer' and press the Enter key. This will start the timer to tell the service file when to execute the currentweather script.
8. The script should be running every hour and the output will be to a file called weather.txt in your ~/documents directory.
