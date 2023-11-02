ITT440
Assessment 1 (10%): Individual Assignment


###Editor/IDE: Gedit
Gedit, short for GNOME Text Editor, is a simple and lightweight text editor designed for the GNOME desktop environment.
GNOME is a popular desktop environment used in various Linux distributions, and Gedit is the default text editor for GNOME.
It was GNOME's default text editor and part of the GNOME Core Applications until GNOME version 42 in March 2022, which 
changed the default text editor to GNOME Text Editor.Designed as a general-purpose text editor, gedit emphasizes simplicity
and ease of use, with a clean and simple GUI, according to the philosophy of the GNOME project. It includes tools for editing 
source code and structured text such as markup languages. It is free and open-source software under the GNU General Public 
License version 2 or later. Gedit is also available for macOS and at one time had a Windows version, which as of May 2020 was 
no longer available. By July 2017, gedit was not being maintained by any developers, but in August 2017 two developers volunteered 
to commence work on it again.

Here are some key features and characteristics of Gedit:
1. User-Friendly Interface
2. Syntax Highlighting
3. Autosave and Auto-Recovery
4. Spell Checking
5. Plugins
6. Search and Replace
7. Multiple Tabs
8. Customizable
9. Integration with GNOME
10. Cross-Platform
11. Free and Open Source


Here's how to get started:
1. Open Gedit

2. Create or open a document.

3. Type and edit text in the document as you would.

4. Save document.

5. Can select text and change the font, size and style from "Edit" menu.

6. Gedit can automatically apply syntax highlighting if you're working with code or markup languages.

7. Use "Find" and "Replace" options in the "Search" menu to search for specific text in the document.
   You can also use keyboard shortcuts like Ctrl+F for Find and Ctrl+H for replace.
   
8. If you want to check the spelling in your document, go to the "Edit" menu and select "Check Spelling." 
   Gedit will underline misspelled words, and you can right-click on them to see suggested corrections.
   
9. If you want to work on multiple documents simultaneously, you can open them in separate tabs. 
   Click on the "+" icon in the tab bar to create a new tab for a new document.
   
10. To close a document, click the "X" on the document's tab. To quit Gedit, click the "X" in the main 
    window or use the "File" menu and select "Quit."
	
11. Gedit allows some degree of customization. You can access the preferences menu by going to "Edit" and 
    selecting "Preferences." Here, you can modify settings related to fonts, colors, and other aspects of the editor.
	
	
	
###Framework: Telnetlib

Telnetlib is a Python module that provides a high-level interface for interacting with Telnet sessions over a network. 
Telnet is a network protocol that allows users to access and manage remote systems or devices through a command-line 
interface. The telnetlib module in Python simplifies the process of establishing Telnet connections and sending 
commands to remote devices programmatically. It is a part of Python's standard library, so you don't need to install it separately.

The telnetlib module provides a Telnet class that implements the Telnet protocol. See RFC 854 for details about the protocol. 
In addition, it provides symbolic constants for the protocol characters (see below), and for the telnet options. 
The symbolic names of the telnet options follow the definitions in arpa/telnet.h, with the leading TELOPT_ removed. 
For symbolic names of options which are traditionally not included in arpa/telnet.h, see the module source itself.

Here are some of the key significances and benefits:
1. Automation and Scripting
2. Network Device Configuration
3. Testing and Debugging
4. Remote Monitoring
5. Custom Automation Tasks
6. Compatibility and Portability
7. Integration with Python Ecosystem
8. Cost-Efficient Solution

Here are the step-by-step instructions on how to use:
1. Import telnetlib: To get started, you need to import the telnetlib module in your Python script, write code 
		import telnetlib

2. Create a Telnet Connection: You should create a Telnet connection by specifying the hostname or IP address and the port number. 
   You can also set a timeout value to handle network delays, write code 
		tn = telnetlib.Telnet("hostname_or_ip", port, timeout)
   
   Replace "hostname_or_ip" with the address of the remote device you want to connect to and port with the Telnet port.
   
3. Log in to the Remote System: To log in to the remote system, you'll need to send your login credentials (username and password) 
   to the device. Write code 
		tn.read_until(b"login: ")
		tn.write(b"your_username\n")
		tn.read_until(b"Password: ")
		tn.write(b"your_password\n")
		
   Replace "your_username" and "your_password" with your actual login credentials.
   
4. Interact with the Remote Device: You can send commands to the remote device and receive responses using the write and read_until methods.
	Write code:
		tn.write(b"command\n")
		response = tn.read_until(b"prompt")
		
	Replace "command" with the specific command you want to execute, and "prompt" with the expected prompt or string that 
	indicates the end of the command's response.
		
5. Process and Display the Response: You can process and display the response from the remote device as needed for your task.
	Write code:
		print(response.decode("utf-8"))
		
	The decode("utf-8") method is used to convert the binary response to a human-readable string.
	
6. Close the Telnet Connection: Always close the Telnet connection when you are done to release resources and properly terminate the session:
		tn.close()
		
7. Handle Exceptions: Be sure to implement error handling and exception handling in your script to deal with potential issues, such as 
network errors, login failures, or timeouts. You can use try-except blocks to capture exceptions and take appropriate actions.
	Write code:
		import telnetlib

		hostname = "example.com"
		port = 23
		timeout = 10

		try:
			tn = telnetlib.Telnet(hostname, port, timeout)
			tn.read_until(b"login: ")
			tn.write(b"your_username\n")
			tn.read_until(b"Password: ")
			tn.write(b"your_password\n")
    
			tn.write(b"show version\n")
			response = tn.read_until(b"prompt")
    
			print(response.decode("utf-8"))
    
			tn.close()
		except Exception as e:
			print(f"An error occurred: {str(e)}")

	Please replace "example.com", port, "your_username", "your_password", "show version", and "prompt" with 
	the appropriate values for your specific use case



###Library: Pulsar
