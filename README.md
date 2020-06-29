### 1) Run the script
This is a copy & paste & run script but you need to do 2 changes:\
     <PASSWORD>: set your user passoword
     <TOKEN>: paste your ngrok token

### 2) Install Remote - SSH extension
Then you have to open your VSC and install __Remote - SSH__ extension.
https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh

### 3) Edit the configuration file
Use Ctrl+Shift+P and search for: Command 'Remote-SSH: Open Configuration' and paste the output of the script.

### 4) Connect to colab
Use Ctrl+Shift+P and search for: Command 'Remote-SSH: Connect to Host...'\
Select colab-ssh.\
Confirm that you have a LINUX server.\
Enter the password that you change in the script.\
Wait for VSCode to download some files to your colab folder to run the VSC server.\

### 5) Navigate to colab notebook folder
If everthing is ok you will see a pop-up to navigate trought google drive folders.\
Load a jupyter notebook from drive/colab notebooks.

### 6) Installing Python extension on VSC server
Before opening in the VSC workspance you need to install Python extension on the VSC server.\
Go yo extension tab on the left and search for Python extension.\
You will see that is already installed in your local VSC but not in the server. Install it.

### 7) Now yes....
Open now your jupyter notebook. VSC code will do everthing you are use to.\
It will configure workspace and ask for a python path: Select: /usr/bin/python
You will see that .vscode folder is now living in colab folder with a settings.json with this path.

### 8) Now yes.... yes
Is everything ok the jupyter server is going to start. You can now use VSC code as your coding best friend and run your script on your colab ...your also best friend.
