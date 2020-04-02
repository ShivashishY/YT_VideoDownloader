# YouTube Video Downloader
YouTube Downloader which provides search query and functions without ads..
Please ensure your internet connectivity to avoid errors.

# Instruction
# Create Executable from Python Script

Step 1: Install python setup and Add Python to Windows Path

Step 2: Open the Windows Command Prompt

Step 3: Install the Pyinstaller Package

```ruby

pip install pyinstaller

```

Step 4: Save your Python Script by downloading from this branch

Step 5: Create the Executable using Pyinstaller
        Simply go to the Command Prompt, and then type:
        cd followed by the location where your Python script is stored.
        
```ruby

cd C:\Users\Test1\Desktop\MyPython

```

Next, use the following template to create the executable:

```ruby

pyinstaller --onefile pythonScriptName.py

```
Once you’re done, press Enter for the last time.


Step 6: Run the Executable
Your executable should now get created at the location that you specified.

In my case, I went back to the location where I originally stored the the script (C:\Users\Test1\Desktop\MyPython). Few additional files got created at that location. To find the executable file, open the "dist" folder.

# Now you’ll see the executable file.
# Once you click on the file, you should be able to launch your program (if you get an error message, you may need to install Visual C++ Redistributable).
