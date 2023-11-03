2310-ITT440

NAME		: MOHAMAD HAMIZAN BIN MOHD ISHAK
STUDENT NO 	: 2022971069
GROUP		: M3CS2554A	


### Framework/Template

1. What is Dash
The Dash framework is an open-source Python library used for building analytical web applications.
Developed by Plotly, Dash enables developers to create interactive, web-based data visualizations, 
dashboards, and applications using Python.

2. Description
It's particularly useful for building data visualization tools and dashboards. With Dash, you can 
use Python code to design and customize web-based graphs, charts, and other interactive elements 
without needing to delve deeply into web development languages like HTML, CSS, or JavaScript.


3. Significance
Dash allows users to leverage their existing Python skills to build web-based applications. 
Other that, : It enables the creation of interactive and customizable data visualizations, such 
as graphs, charts, and dashboards, providing a way to communicate data insights effectively.
It allows for quick prototyping and development of interactive web applications, saving time and effort
for developers who need to showcase their data analysis or models in a user-friendly format.

4. Demonstrate
 
To use Dash on a Linux system, you'll need Python installed and then you can follow these steps:

i. Make sure you have Python installed on your Linux system. 
You can check if it's installed by opening a terminal and typing python 

	/* --version or python3 --version

ii. Install Dash: You'll need to install the Dash library for Python. You can use pip, which is a package manager for Python.


	/*  pip install dash

iii. Create a Dash App: Once you have Dash installed, you can create your Dash application. You can use a text editor or an IDE like Visual Studio Code, Sublime Text, or any other of your choice.

	/*	Here's a basic example of a Dash app:


			import dash
			import dash_core_components as dcc
			import dash_html_components as html

			app = dash.Dash(__name__)

			app.layout = html.Div(children=[
				html.H1('Hello Dash'),
				dcc.Graph(
					id='example-graph',
					figure={
						'data': [
							{'x': [1, 2, 3], 'y': [4, 1, 2], 'type': 'bar', 'name': 'SF'},
							{'x': [1, 2, 3], 'y': [2, 4, 5], 'type': 'bar', 'name': 'Montreal'},
						],
						'layout': {
							'title': 'Dash Data Visualization'
						}
					}
				)
			])

			if __name__ == '__main__':
				app.run_server(debug=True)
	
iv. Run the Dash App: Save the code in a file, for example, 
		
	/*	my_dash_app.py. 

Then in the terminal, navigate  to the directory containing the file and run it using:



	/* python my_dash_app.py

It will start the development server and tell you where you can view your Dash app (typically at http://127.0.0.1:8050/).

This is a simple example to get you started with Dash on Linux. Dash is quite versatile and allows for complex web 
applications with interactive visualizations, so you can build upon this basic example to create more elaborate projects.


	

### Libraries/Modules


1. What is Netmiko
Netmiko is an open-source that was created to make network devices configuration and management more automated. 

2. Description
Network automation has been completely transformed by the Netmiko library,
It's a great tool for network engineers and administrators since it abstracts the complexity of 
interfacing with various device models and manufacturers.

3. Significance
i.		Consistency in network configurations and modifications is guaranteed,
ii.		Network engineers can be sure configurations are implemented consistently to every device,
iv.		Support for various vendors' network devices, including Cisco, Juniper, Arista, Huawei, and others
v.		Providing a simple and consistent way to connect and communicate with devices using Python.
vi.		Providing resources and support for users to learn and implement network automation effectively.


4. Demonstrate
To use Netmiko, a multi-vendor library for SSH connections to network devices, on Linux, you can follow these steps:

Ensure Python is Installed: Verify that Python is installed on your Linux system. Most distributions come with Python by default. You can check the version by running python --version or python3 --version in the terminal.

i.	Install Netmiko:
Open a terminal and use pip (Python's package manager) to install Netmiko. Run the following command:


		/*	pip install netmiko

Write Python Scripts Using Netmiko:
After installing Netmiko, you can create Python scripts that utilize Netmiko for connecting to and managing network devices. 
You can use your preferred text editor or Integrated Development Environment (IDE) to write your Python scripts.

For instance, here is a simple example of how you might connect to a network device using Netmiko:

ii.	Here's a basic example of a Netmiko app:

			from netmiko import ConnectHandler

			device = {
				'device_type': 'cisco_ios',
				'host': '192.168.1.1',
				'username': 'your_username',
				'password': 'your_password',
			}

			connection = ConnectHandler(**device)
			output = connection.send_command('show version')
			print(output)
			connection.disconnect()


Replace '192.168.1.1', 'your_username', and 'your_password' with your actual device IP address, 
username, and password, and adjust the commands according to what you want to execute on the network device.

iii.	Run Python Scripts:
Save your Python script with a .py extension, for example, 
		
		/*	my_netmiko_script.py. 

Then, execute the script from the terminal using:
		
		/*	python my_netmiko_script.py
		

Check Output:
The script will establish a connection to the specified device, execute the provided command ('show version' in the example), 
retrieve the output, print it to the terminal, and then disconnect from the device.

By following these steps, you should be able to install Netmiko on your Linux system, create Python scripts that use Netmiko, 
and execute them to interact with network devices. Always refer to the Netmiko documentation for more advanced functionalities 
and specific use cases related to network device management.




### Editor/EDI


1. What is Jupyter
Jupyter is an open-source project that provides an interactive environment for programming in several languages, including Python, 
R, and Julia. The core component of Jupyter is the Jupyter Notebook, a web application that allows users to create and share documents 
containing live code, equations, visualizations, and narrative text.

The Jupyter Notebook supports various programming languages via kernels, which are language-specific execution environments. 
Each kernel allows the Jupyter Notebook to execute code written in that language.

2. Description
Jupyter Notebook runs in a web browser and can be installed locally on your machine, typically through the Anaconda distribution or by 
installing Jupyter directly via Python's package manager (pip or conda). It can also be used in cloud environments or provided as a 
service by various platforms.

Additionally, JupyterLab is an evolution of the Jupyter Notebook, providing an improved interface with additional functionalities, 
offering a more comprehensive and extensible environment compared to the traditional Jupyter Notebook.

3. Significance
i. 		Jupyter provides an interactive platform where users can write, execute, and 
		modify code in a step-by-step manner.
ii.		Jupyter supports various programming languages through its kernel system.
		Some of the languages supported by Jupyter is Python, R code, Julia, JavaScript, 
		Scala code,  C++, Ruby, Haskell, Go, and more.
iii.	Creation of documents combining live code, visualizations, and explanatory text,
		making it easier to explore data, create graphs, and explain findings all in one place.
iv		A useful educational tool for teaching coding, data science and other computational 
		concepts due to its interactive and explanatory nature.
		
		

DEMO :
[![Click to watch the video](https://img.youtube.com/vi/TFrJ2iqWfp0/0.jpg)](https://www.youtube.com/watch?v=TFrJ2iqWfp0)




