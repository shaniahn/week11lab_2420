# week11lab_2420

# How to install and use Weather script, service file, and timer

1. Download the 3 files as a ZIP.
2. Unzip the files.
3. Create a new directory called documents under your home (~) directory.
4. Move the currentweather file into the newly created directory called documents. 
5. While in the ~/documents directory, type in the command 'chmod +x currentweather'.
5. Move the weather.service and weather.timer files into your ~/etc/systemd/system directory.
6. While in the ~/etc/systemd/system directory, type in the command 'sudo systemctl daemon-reload' and press the Enter key
7. The script should be running every hour and the output will be to a file called weather.txt in your ~/documents directory.
