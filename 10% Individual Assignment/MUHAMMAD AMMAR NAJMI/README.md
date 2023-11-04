### NAME		: Muhammad Ammar Najmi Bin Md Yussanirul Sha'amsul Kamal 
### STUDENT ID  : (2022196487)
### GROUP       : M3CS2554A

# Assessment 1 (10%): Individual Assignment.



## PyCharm
 
	PyCharm is a robust and feature-rich IDE created especially for Python development. 
	It offers cutting-edge debugging features, advanced code support, and integration 
	with other development frameworks and tools. The features PyCharm offers include 
	code navigation, refactoring, version control integration,and support for virtual 
	environments. Both a free Community Edition and a paid Professional Edition with 
	further features are offered.

## Significance of PyCharm.

	The significance of PyCharm is about Code assistance. PyCharm provides intelligent 
	code completion, code inspection, and quick fixes, which help developers write clean 
	and error-free Python code. It offers suggestions and auto-completions based on the 
	context, reducing the chances of syntax and logic errors. Next, Code Navigation. 
	PyCharm makes it easy to navigate through large codebases with features like "Go to Definition," 
	"Find Usages," and "Refactoring." This is especially useful for understanding and modifying existing code.
	After that, Code templates and generations. PyCharm allows developers to create custom code templates and 
	provides code generation features to accelerate development. For debugging, PyCharm offers a robust and 
	user-friendly debugging environment with features like breakpoints, variable inspection, interactive debugging, 
	and integration with popular debuggers like pdb and IPython.
	
## How to Use PyCharm
	
	1. Open PyCharm and create a new Python project.
	2. Create a new Python file in your project (right-click on your project folder in the Project pane and select "New" > "Python File").
	3. Give your Python file a name, for example, "hello.py."

	Now, you can write a simple "Hello, World!" program in your "hello.py" file:

	```python
	print("Hello, World!")
	```

	To run this code in PyCharm:

	1. Click the green "Run" button in the top right corner of the editor.
	2. You should see the output "Hello, World!" in the console at the bottom of the PyCharm window.


 
# Flask

	Flask is a lightweight web framework for Python that is designed to make it easy to build web applications.
	It is often referred to as a "micro" framework because it provides the essentials for building web applications 
	without imposing a lot of predefined structure or libraries on the developer. Flask gives you the flexibility to choose 
	the components and extensions you want to use, allowing you to build web applications that suit your specific needs.
 
## Significance of Flask.

	The significance of Flask is Lightweight and Minimalistic: Flask is often described as a "micro" framework because it provides 
	the essential components for building web applications without imposing a lot of predefined structure or libraries. This minimalistic
	approach allows developers to have more flexibility in choosing components and libraries, making Flask a great choice for building small 
	to medium-sized web applications and APIs.Next, Ease of Learning.Flask simplicity and minimalism make it easy to learn for both beginner
	and experienced developers. Its small and clear codebase makes it an excellent choice for those new to web development.After that, Deployment Option.
	Flask applications can be deployed on a variety of web servers, such as Gunicorn, uWSGI, or behind a reverse proxy like Nginx or Apache. This flexibility 
	allows you to choose the deployment method that best suits your needs.
	
## How to Use Flask in PyCharm
	
	
	1. **Install Flask**:
   Before you start, make sure you have Flask installed. You can install it using pip if you haven't already:

   ```bash
   pip install Flask
   ```

	2. **Create a New Flask Project**:
   Open PyCharm and create a new Python project if you haven't already. Then, create a new Python file in the project for your Flask application.

	3. **Write Your Flask Application**:
   In your Python file (e.g., `app.py`), write a simple Flask application. Here's a minimal example:

	```python
	from flask import Flask

	app = Flask(__name__)

	@app.route('/')
	def hello_world():
    return 'Hello, Flask!'

	if __name__ == '__main__':
    app.run()
	```

	This code creates a Flask web application with a single route that responds with "Hello, Flask!" when you access the root URL.

	4. **Run Your Flask Application**:
	To run your Flask application in PyCharm, follow these steps:

		- Right-click on your Python file (e.g., `app.py`) in the Project pane.
		- Choose "Run 'app'."

   Alternatively, you can run your Flask application from the terminal:

   ```bash
   python app.py
   ```

	5. **Access Your Flask Application**:
   Once your Flask application is running, open a web browser and go to `http://127.0.0.1:5000/` or `http://localhost:5000/`. You should see the "Hello, Flask!" message displayed in your browser.

	6. **Stop the Application**:
   To stop the Flask application in PyCharm, simply stop the running process in the terminal or click the "Stop" button in PyCharm's console.


	



# NCClient

	NCClient is a Python library designed for network engineers and developers working with network devices that support the NETCONF (Network Configuration Protocol) 
	or YANG (Yet Another Next Generation) data modelling. NETCONF is a network management protocol used to configure and manage network devices in a standardized way, and 
	YANG is a modelling language used to describe the structure and semantics of network device configuration and operational data.By using ncclient in conjunction with YANG models, 
	network engineers can create scripts and automation workflows that streamline the management of network devices, reducing manual configuration errors and saving time in network operations. 
	It is a valuable tool in the field of network automation and programmability, particularly for organizations that are adopting Software-Defined Networking (SDN) principles and 
	need to manage their network infrastructure programmatically.

## Significance of NCClient.

	The significance of NCClient is NETCONF support. NCClient s specifically designed to work with the NETCONF protocol. NETCONF is a network management protocol that allows for the configuration 
	and management of network devices in a standardized, vendor-agnostic way. This is crucial for network automation and consistent configuration of network equipment.Next, Network automation. Network engineers 
	and administrators can use ncclient to automate the configuration, provisioning, and management of network devices. This leads to improved efficiency, consistency, and reduced manual errors in network operations.
	After that, Secure Communication.  NETCONF typically uses SSH for secure communication, and ncclient provides built-in support for SSH, ensuring secure and authenticated access to network devices.Furthermore, 
	operational data Retrieval. NCClient allows for the retrieval of operational data from network devices, which is important for monitoring and troubleshooting network issues.

## How to Use NCClient in Kali Linux


	To use the `ncclient` library in Kali Linux without connecting to a network device, you can create a simple Python script that sets up a basic NETCONF client using `ncclient` to interact with a NETCONF server. 
	Here's a minimal example:

	1. **Install the `ncclient` library** if it's not already installed in your Python environment:

	```bash
	pip install ncclient
	```

	2. Create a Python script (e.g., `simple_ncclient.py`) to interact with a local NETCONF server. This script demonstrates how to connect to a fictional NETCONF server running on your localhost.

	```
	python
	from ncclient import manager

	# Replace these variables with your device's actual credentials
	HOST = "192.168.253.128"
	USER = "ammar1"
	PASS = "ammar123"
	
	def connect_to_device():
    try:
        with manager.connect(host=HOST, username=USER, password=PASS, hostkey_verify=False) as m:
            for capability in m.server_capabilities:
                print(capability)
    except Exception as e:
        print(f"An error occurred: {e}")

	if __name__ == "__main__":
    connect_to_device()
	```

	In this script, we use the `ncclient` library to establish a connection to a NETCONF server. 
	Replace the placeholders with the actual connection details if you have a specific NETCONF server in mind.


## Demonstrate tools Pycharm,Flask and Ncclient.

[![Watch the video](https://img.youtube.com/vi/9xnfHxV0Tb4/0.jpg)](https://www.youtube.com/watch?v=9xnfHxV0Tb4)

