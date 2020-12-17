# pythonCLI
Simple command line tool written in python.

Run the program on the command line using "python hex2dec.py 0x123"
to convert your hexadecimal number to decimal. 

If you want the program to look and behave like a shell command, follow these steps:
1. Mark the python script as an executable:
        $chmod +x hex2dec.py

2. If your hex2dec file has the .py extension, simply "mv hex2dec.py hex2dec"

3. In your users home directory, create a bin directory:
    "$ mkdir -p ~/bin"

4. Copy the script to the bin:
    "$ cp hex2dec ~/bin"

5. Now add ~/bin to your system PATH. You can accomplish this in two ways:
 
     - Add the this line to .profile or .bash_profile in your home directory: export PATH=$PATH":$HOME/bin".
     - You can either use an editor to do it or run the following command to do that: echo 'export PATH=$PATH":$HOME/bin"' >> .profile
     - Changes to .profile or .bash_profile only go into effect when your shell reloads these files. You can trigger a reload by either opening a new terminal window or running this command: source .profile

   Or in windows, you can copy the file location "user/youruser/bin" to your PATH by editing your environment variables.