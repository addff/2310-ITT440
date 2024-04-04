ITT440
Assessment 1 (10%): Individual Assignment


### Editor/IDE: Gedit
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
	
	
	
### Framework: Telnetlib

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

3. Create a Telnet Connection: You should create a Telnet connection by specifying the hostname or IP address and the port number. 
   You can also set a timeout value to handle network delays, write code 

		tn = telnetlib.Telnet("hostname_or_ip", port, timeout)
   
   Replace "hostname_or_ip" with the address of the remote device you want to connect to and port with the Telnet port.
   
4. Log in to the Remote System: To log in to the remote system, you'll need to send your login credentials (username and password) 
   to the device. Write code
   
		tn.read_until(b"login: ")
		tn.write(b"your_username\n")
		tn.read_until(b"Password: ")
		tn.write(b"your_password\n")
		
   Replace "your_username" and "your_password" with your actual login credentials.
   
6. Interact with the Remote Device: You can send commands to the remote device and receive responses using the write and read_until methods.
	Write code:

		tn.write(b"command\n")
		response = tn.read_until(b"prompt")
		
	Replace "command" with the specific command you want to execute, and "prompt" with the expected prompt or string that 
	indicates the end of the command's response.
		
8. Process and Display the Response: You can process and display the response from the remote device as needed for your task.
	Write code:

		print(response.decode("utf-8"))
		
	The decode("utf-8") method is used to convert the binary response to a human-readable string.
	
10. Close the Telnet Connection: Always close the Telnet connection when you are done to release resources and properly terminate the session:
    
		tn.close()
		
11. Handle Exceptions: Be sure to implement error handling and exception handling in your script to deal with potential issues, such as 
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



### Library: Pulsar
The exact details and purpose of such a library or software would depend on the specific context and domain it is associated with. There are 
numerous software projects and libraries with diverse functionalities, and it's important to provide more context to identify the specific 
"Pulsar" library or software you are interested in. If you have a more specific question about a particular "Pulsar," please provide 
additional context, and I'll be happy to provide more detailed information. As of my last knowledge update in January 2022, Apache Pulsar was 
an open-source distributed messaging and event streaming platform developed under the Apache Software Foundation.

Here's the significances:
1. Distributed Messaging and Event Streaming.
2. Multi-Tenancy
3. Scalability
4. Durable Message Storage
5. Strong Consistency
6. Integration with Apache Projects
7. Community and Ecosystem
8. Use Cases

Here's the steps including installation, configuration, and integration into your application.
1. Download the official Apache Pulsar distribution:

 	   wget https://archive.apache.org/dist/pulsar/pulsar-3.1.1/apache-pulsar-3.1.1-bin.tar.gz

2. Once downloaded, unpack the tar file:

  	 tar xvfz apache-pulsar-3.1.1-bin.tar.gz

3. For the rest of this quickstart all commands are run from the root of the distribution folder, so switch to it:

  	 cd apache-pulsar-3.1.1

4. List the contents by executing:

  	 ls -1F

5. Run this command to start a standalone Pulsar cluster:

 	  bin/pulsar standalone

6. Pulsar stores messages in topics. It's a good practice to explicitly create topics before using them, even if Pulsar can automatically create topics when they are referenced.
To create a new topic, run this command:

   	bin/pulsar-admin topics create persistent://public/default/my-topic

7. You can use the pulsar command line tool to write messages to a topic. This is useful for experimentation, but in practice you'll use the Producer API in your application code, or Pulsar IO connectors for pulling data in from other systems to Pulsar.
Run this command to produce a message:

   	bin/pulsar-client produce my-topic --messages 'Hello Pulsar!'

8. Now that some messages have been written to the topic, run this command to launch the consumer and read those messages back:

   	bin/pulsar-client consume my-topic -s 'my-subscription' -p Earliest -n 0

9. You'll see the messages you produce in the previous step:

		----- got message -----
   
   key:[null], properties:[], content:Hello Pulsar!

11. Leave the consume command from the previous step running. If you've already closed it, just re-run it.
Now open a new terminal window and produce more messages. The default message separator is ,:


   	 bin/pulsar-client produce my-topic --messages "$(seq -s, -f 'Message NO.%g' 1 10)"

12. Once you've finished you can shut down the Pulsar cluster. Press Ctrl-C in the terminal window in which you started the cluster.

DEMO Video for Gedit, Telnetlib and Apache Pulsar

[![Video](https://img.youtube.com/vi/4qycZ7tvSAg/0.jpg)](https://www.youtube.com/watch?v=4qycZ7tvSAg)





