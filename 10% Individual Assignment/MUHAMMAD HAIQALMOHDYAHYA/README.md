# 2310-ITT440

NAME : MUHAMMAD HAIQAL BIN MOHD YAHYA
TASK : ASSIGNMENT 1 ( PYTHON FOR NETWORK ENGINEER )

	-TOOLS ( EDITOR, LIBRARY, FRAMEWORK )-

EDITOR : IDLE

IDle, or Integrated Development and Learning Environment, is a straightforward and lightweight Python IDE that comes bundled with the standard Python distribution. 
Designed with simplicity in mind, IDLE caters to beginners and learners, providing an interactive Python shell for quick experimentation with code and a script 
editor with features like syntax highlighting and basic debugging tools. While it may lack some of the advanced features found in more robust IDEs, IDLE serves 
as an accessible starting point for those new to Python, offering a user-friendly environment for writing and running Python scripts. Its inclusion with the 
standard Python package ensures that users can begin coding without the need for additional installations, making it a convenient choice for introductory 
programming and learning exercises.

LIBRARY : PSUTIL

`psutil` is a powerful and cross-platform Python library that facilitates easy access to system-related information and process management. Short for 
"process and system utilities," it provides a consistent and straightforward interface for retrieving details on CPU usage, memory usage, disk I/O, 
network activity, and more. Network engineers, system administrators, and developers can leverage `psutil` to monitor and optimize system performance, 
analyze resource utilization, and gain insights into running processes. Its versatility makes it a valuable tool for tasks such as process manipulation, 
real-time system monitoring, and crafting applications that require comprehensive information about a computer's state. With its ease of use and platform 
compatibility, `psutil` stands out as a go-to library for system-related operations in Python.

FRAMEWORK : BEHAVE

Behave is a Python testing framework that follows the principles of behavior-driven development (BDD), allowing developers to write tests in a natural language 
format for enhanced collaboration between technical and non-technical team members. It leverages the Gherkin language with keywords like "Given," "When," and 
"Then" to describe system behavior in a human-readable manner. Tests are organized in feature files using Gherkin syntax, and the associated step definitions 
are implemented in Python. Behave facilitates clear communication of requirements, making it easier to understand and maintain test scenarios. By combining the 
benefits of BDD with the simplicity of Python, Behave offers a powerful and user-friendly approach to writing and executing behavior-driven tests.


	-SIGNIFICANCE OF THE TOOLS-
	
> IDLE 

IDLE (Integrated Development and Learning Environment) in Python holds significance for several reasons:-

1. **Accessibility for Beginners:** 
	IDLE is designed to be beginner-friendly, providing a simple and accessible environment for individuals who are new to programming and Python. 
	Its straightforward interface and interactive shell make it easy for beginners to learn and experiment with Python code.

2. **Interactive Shell:** 
	The interactive Python shell within IDLE allows users to execute Python commands and see immediate results. 
	This is particularly valuable for learning and testing small code snippets.

3. **Script Editing:** 
	IDLE includes a script editor with features like syntax highlighting, making it suitable for writing and running Python scripts. 
	While not as feature-rich as some other IDEs, it provides a basic environment for script development.

4. **Bundled with Python:** 
	IDLE comes pre-installed with the standard Python distribution, eliminating the need for users to install a separate IDE for basic Python programming. 
	This ensures that users can start coding immediately after installing Python.

5. **Educational Purpose:** 
	IDLE is often recommended for educational settings, such as classrooms and workshops, due to its simplicity and ease of use. 
	It serves as a practical tool for introducing programming concepts to learners.

6. **Cross-Platform Compatibility:** 
	IDLE is available on various operating systems, including Windows, macOS, and Linux, making it a consistent environment for Python development across different platforms.

While IDLE may not be as feature-rich or powerful as some other Python IDEs, its significance lies in its role as a starting point for beginners and a quick, accessible 
tool for basic Python coding tasks. As users advance in their programming skills, they may explore more feature-packed IDEs for larger and more complex projects.

> PSUTIL 

The `psutil` library in Python holds significant importance for system monitoring, resource management, and process manipulation. 
Here are some key aspects of its significance:-

1. **Cross-Platform Compatibility:** 
	`psutil` is designed to work across various operating systems, including Windows, Linux, and macOS. 
	This cross-platform support makes it a versatile choice for developers working on different environments.

2. **System Monitoring:** 
	The library provides a simple and consistent interface for retrieving real-time information about system resources. 
	This includes CPU usage, memory usage, disk I/O, network activity, and more. This information is crucial for monitoring and optimizing system performance.

3. **Process Management:** 
	`psutil` allows developers to gather detailed information about running processes, such as CPU and memory usage, status, and resource consumption. 
	This is valuable for process management, optimization, and troubleshooting.

4. **Easy-to-Use API:** 
	The library offers an intuitive and easy-to-use API, making it accessible for developers to retrieve complex system information with minimal code. 
	This simplicity contributes to faster development and efficient resource utilization.

5. **Network Information:** 
	`psutil` provides insights into network-related information, including open ports, network connections, and data transfer rates. 
	This is beneficial for network-related tasks and monitoring network activity.

6. **Disk Usage Information:** 
	Developers can use `psutil` to retrieve disk usage statistics, helping in tasks like monitoring available disk space, identifying storage-intensive processes, 
	and optimizing disk usage.

7. **Battery Information (on supported platforms):** 
	For systems with batteries, `psutil` can provide information about battery status, which is useful for developing power-efficient applications 
	and monitoring battery health.

8. **Automation and Scripting:** 
	Network engineers and system administrators often use `psutil` in automation scripts for tasks such as resource monitoring, alerting, 
	and managing processes, contributing to efficient system administration.

In summary, the significance of the `psutil` library lies in its ability to provide a unified and platform-independent interface for accessing critical system information. 
This makes it a valuable tool for developers, system administrators, and network engineers involved in system monitoring, optimization, and automation.

> BEHAVE

Behave is a Python testing framework that follows the principles of behavior-driven development (BDD), and its significance lies in several key aspects:-

1. **Natural Language Syntax:** 
	Behave utilizes Gherkin syntax, incorporating keywords like "Given," "When," and "Then," which allows for the creation of human-readable test scenarios. 
	This natural language approach makes it easier for non-technical stakeholders to understand and participate in the testing process.

2. **Collaboration Between Teams:** 
	Behave fosters collaboration between developers, QA teams, and business stakeholders. By using a common language, everyone involved in the project can 
	contribute to defining and understanding the expected behavior of the system.

3. **Structured Test Scenarios:** 
	Behave encourages the creation of structured and well-defined test scenarios, making it easier to organize and maintain tests. Each scenario corresponds 
	to a specific behavior, enhancing clarity and reducing ambiguity in test descriptions.

4. **Reusability of Step Definitions:** 
	Step definitions in Behave are reusable, allowing for the creation of modular and maintainable test code. This contributes to code readability and 
	simplifies the management of test suites.

5. **Integration with Python:** 
	Behave seamlessly integrates with Python, leveraging its capabilities for test automation. This enables developers to utilize Python libraries and 
	tools within their Behave tests, enhancing the flexibility and extensibility of the testing framework.

6. **Detailed Test Reports:** 
	Behave generates detailed and readable test reports, providing insights into test outcomes and facilitating the identification of issues. 
	This helps in debugging and analyzing test results effectively.

7. **Continuous Integration Support:** 
	Behave is compatible with popular continuous integration (CI) tools, enabling the integration of behavior-driven tests into the CI/CD 
	(Continuous Integration/Continuous Deployment) pipeline. This ensures that tests are automatically executed during the development and deployment process.

8. **Test Automation for Complex Systems:** 
	Behave is suitable for testing complex systems where the behavior of the system is critical. It allows for the creation of end-to-end tests that 
	mimic user interactions and ensure that the software behaves as expected in various scenarios.

In summary, the significance of Behave lies in its ability to facilitate collaboration, enhance test readability, and provide a structured approach to behavior-driven 
testing. Its integration with Python and support for natural language make it a valuable framework for developing and maintaining high-quality automated tests.


	-HOW TO USE THE TOOLS-
	
> IDLE

Using IDLE (Integrated Development and Learning Environment) for Python is quite straightforward. Here's a basic guide to get you started:-

1. **Opening IDLE:**
   - On Windows: You can find IDLE in the Start menu. Look for "IDLE (Python x.x)" where "x.x" is your Python version.
   - On macOS/Linux: Open a terminal and type `idle` or `idle3` (depending on your Python version) and press Enter.

2. **Interactive Shell:**
   - Once IDLE is open, you'll see the Python shell window. This is an interactive environment where you can enter Python commands and see immediate results.

3. **Creating a New Script:**
   - Click on "File" in the menu and choose "New File" to open a new script window.

4. **Writing Python Code:**
   - In the script window, you can write your Python code. For example:

    print("Hello, IDLE!")
    
5. **Running the Script:**
   - Save your script with a `.py` extension. Click on "Run" in the menu and choose "Run Module" or press `F5`. Alternatively, you can right-click in the 
	script window and choose "Run Module."

6. **Interactive Debugging (Optional):**
   - IDLE has a basic integrated debugger. You can set breakpoints and run your script in debugging mode. To do this, click on "Debug" in the menu and 
	choose "Debugger" or press `Ctrl + F5`.

7. **Closing IDLE:**
   - When you're done, you can close IDLE by clicking on the "X" button in the upper right corner of the Python shell or script window.

Remember, IDLE is a basic and lightweight IDE, suitable for learning and small projects. For more complex development, you might consider using other IDEs like 
PyCharm, Visual Studio Code, or others based on your preferences and project requirements.

> PSUTIL

Using `psutil` is relatively straightforward. Here's a basic guide on how to use this Python library:

1. **Installation:**
   - Before using `psutil`, make sure it is installed. You can install it using the following command:

     ```bash
     pip install psutil
     ```

2. **Importing `psutil`:**
   - In your Python script or interactive environment, import the `psutil` module:

     ```python
     import psutil
     ```

3. **System Information:**
   - Retrieve basic information about the system, such as CPU count, CPU usage, memory usage, and disk usage:

     ```python
     # Get CPU count
     cpu_count = psutil.cpu_count()
     print(f"CPU Count: {cpu_count}")

     # Get CPU usage
     cpu_usage = psutil.cpu_percent(interval=1)
     print(f"CPU Usage: {cpu_usage}%")

     # Get memory usage
     memory = psutil.virtual_memory()
     print(f"Total Memory: {memory.total} bytes")
     print(f"Used Memory: {memory.used} bytes")

     # Get disk usage
     disk = psutil.disk_usage('/')
     print(f"Total Disk Space: {disk.total} bytes")
     print(f"Used Disk Space: {disk.used} bytes")
     ```

4. **Process Information:**
   - Retrieve information about running processes:

     ```python
     # Get a list of all running processes
     processes = psutil.process_iter(attrs=['pid', 'name', 'cpu_percent', 'memory_percent'])
     for process in processes:
         print(process.info)

     # Get information about a specific process (replace PID with the desired process ID)
     pid = 1234
     process = psutil.Process(pid)
     print(f"Process Name: {process.name()}")
     print(f"CPU Percent: {process.cpu_percent()}%")
     print(f"Memory Percent: {process.memory_percent()}%")
     ```

5. **Network Information:**
   - Retrieve information about network connections:

     ```python
     # Get a list of network connections
     connections = psutil.net_connections(kind='inet')
     for conn in connections:
         print(conn)
     ```

6. **Battery Information (if applicable):**
   - Retrieve information about the battery (if running on a system with a battery):

     ```python
     try:
         battery = psutil.sensors_battery()
         percent = battery.percent
         power_plugged = battery.power_plugged
         print(f"Battery Percent: {percent}%")
         print(f"Power Plugged In: {power_plugged}")
     except AttributeError:
         print("Battery information not available.")
     ```

Remember to customize these examples based on your specific use case and project requirements. `psutil` provides a wide range of functionalities for system monitoring 
and process management.

> BEHAVE

Using the Behave framework involves defining feature files with scenarios written in Gherkin syntax and implementing corresponding step definitions in Python. 
Here's a basic guide on how to use Behave:-

1. **Installation:**
   - Before using Behave, make sure it is installed. You can install it using the following command:

     ```bash
     pip install behave
     ```

2. **Create a Feature File:**
   - Create a feature file (e.g., `my_feature.feature`) using Gherkin syntax. Specify scenarios and steps that describe the behavior of your application. For example:

     ```gherkin
     Feature: Simple Arithmetic Operations

       Scenario: Add two numbers
         Given I have entered 5 into the calculator
         And I have entered 7 into the calculator
         When I press add
         Then the result should be 12 on the screen
     ```

3. **Create Step Definitions:**
   - Create a Python file (e.g., `steps.py`) to implement step definitions for the scenarios defined in the feature file. Map each step to a Python function. For example:

     ```python
     from behave import given, when, then

     @given('I have entered {number:d} into the calculator')
     def step_given_enter_number(context, number):
         context.result = number

     @when('I press add')
     def step_when_press_add(context):
         context.result += context.number

     @then('the result should be {expected_result:d} on the screen')
     def step_then_check_result(context, expected_result):
         assert context.result == expected_result
     ```

4. **Run Behave:**
   - Open a terminal in the project directory and run Behave:

     ```bash
     behave
     ```

   - Behave will automatically discover and execute your feature files, and the output will indicate whether the scenarios passed or failed.

5. **Review Reports:**
   - Behave generates detailed reports in various formats. You can customize the report format and location. By default, a summary is displayed in the terminal.

   - You can generate more detailed reports using additional parameters, such as:

     ```bash
     behave -f allure_behave.formatter:AllureFormatter -o allure-results
     ```

     This example generates Allure reports in the `allure-results` directory. You'll need to install the `allure-behave` package for this.

6. **Modify and Iterate:**
   - Update your feature files and step definitions based on your application changes or new requirements. Run Behave again to ensure that your scenarios still pass.

This is a basic guide to get you started with Behave. The framework provides many advanced features for testing and collaboration.


