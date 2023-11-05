2310-ITT440

NAME: AHMAD ZIKRY BIN ADAM

MATRIX NUMBER: 2023375187

GROUP: M3CS2554B

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### EDITOR

###Ninja IDE:

1) What is Ninja IDE?

Ninja-IDE (Ninja Is Not Just Another IDE) is an open-source integrated development environment (IDE) designed primarily for Python developers. It offers a range of features and tools aimed at simplifying the development process, including code highlighting, completion, and refactoring. Ninja-IDE aimed to provide a lightweight, yet feature-rich environment for Python development. However, it's worth noting that development on Ninja-IDE slowed down in recent years, and as of my last knowledge update in January 2022, the project might not have the same level of active development or support as other more widely-used IDEs like PyCharm, Visual Studio Code, or Atom. Developers might want to consider the current status and community support before choosing Ninja-IDE for their projects.
   
2) Description of Ninja IDE.

Ninja-IDE, short for "Ninja Is Not Just Another IDE," is an open-source integrated development environment primarily tailored for Python developers. It was created with the intention of providing a lightweight yet functional environment for Python programming. Ninja-IDE, though focused on Python, supports other programming languages as well. However, it was more tailored to cater to the Python development community with tools and features specifically designed for Python coding.

3) Advantages of Ninja IDE.

NINJA-IDE (Ninja Integrated Development Environment) was a Python-centric integrated development environment that offered various features and advantages for developers. Some of these advantages included:

      i.  Cross-platform compatibility: NINJA-IDE was designed to work on multiple operating systems, including Windows, macOS, 
          and Linux, providing a consistent experience for developers across different platforms.
      
      ii. Code autocompletion: It offered intelligent code completion, which helped in speeding up the coding process by 
          suggesting methods, functions, and variable names as you typed.
      
      iii.Code generation: NINJA-IDE had features for automatically generating code snippets, reducing the need for manual 
          typing and helping developers with boilerplate code.
      
      iv. Integrated development tools: The IDE included various tools to aid development, such as a version control system, a
          built-in terminal, a Python debugger, and support for various plugins, streamlining the development process by having
          these tools within the same environment.
      
      v.  Customizability: It allowed developers to customize and extend its functionality by adding plugins or creating their own.
          This flexibility allowed tailoring the environment to specific needs.
  
4) How to install Ninja IDE

       i.  Download Python: Ninja-IDE is built using Python, so you'll need Python installed on your system. Download and install
           Python from the official Python website (https://www.python.org/). Ensure you select the option to add Python to your
           system's PATH during installation.
      
       ii. Install Ninja-IDE using pip (Python package manager):
          
       a) Open a terminal or command prompt.
         
       b) Use the following command to install Ninja-IDE via pip:
          
             pip install ninja-ide

iii.Launch Ninja-IDE

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### LIBRARY

###PyGame:

1) What is PyGame?

Pygame is a popular set of Python modules designed for writing video games. It provides functionalities for game development, including graphics, sound, input devices (like keyboard, mouse, and controllers), and handling events. With Pygame, developers can create games and multimedia applications in a relatively straightforward manner, as it abstracts complexities related to graphics and sound, making it more accessible for beginners while still powerful enough for more complex projects. Pygame uses the Simple DirectMedia Layer (SDL) library under the hood, allowing for interaction with various multimedia components and ensuring portability across different platforms. It’s used for both 2D and simple 3D game development and has a strong community that offers plenty of tutorials, resources, and examples for aspiring game developers.

2) Description of PyGame.

Pygame is a popular and versatile Python library used for developing 2D games, multimedia applications, and interactive programs. It provides a wide range of tools and functionalities that make it easier for developers to create games without having to handle low-level details, such as directly manipulating graphics or managing sound.

3) Advantages of PyGame.

Pygame is a popular set of Python modules designed for writing video games. It's built on top of the Simple DirectMedia Layer (SDL), which provides low-level access to audio, keyboard, mouse, and display. Here are some of the advantages of using Pygame:

      i.  Simple and Easy to Learn: Pygame is relatively easy to learn, especially for those already familiar with Python. It 
          abstracts away some of the complexity of working directly with graphics and sound libraries.
      
      ii. Cross-Platform: It is compatible with various operating systems, including Windows, macOS, and Linux, allowing 
          developers to create games that can run on different platforms.
      
      iii.Abstraction of Low-Level Tasks: Pygame abstracts away some complex low-level tasks related to graphics, sound, and 
          user input, providing an easier way to create games without getting deep into system-specific details.
      
      iv. Multi-Media Support: Pygame offers various modules for handling multimedia, including graphics, sound, and input from
          devices such as keyboards and mice, making it a comprehensive library for game development.
      
      v.  Active Community and Resources: There's an active and supportive community around Pygame, which means there are plenty
          of tutorials, guides, and resources available for newcomers and experienced developers alike.

4) How to install PyGame.

To install Pygame, a popular library for creating games in Python, you can follow these steps. Please note, you need to have Python installed on your system before installing Pygame.

Here are the general steps:

      i.  Install Python: If you haven't installed Python, visit the official Python website (https://www.python.org/) to download
          and install the latest version compatible with your operating system. Ensure you select the option to add Python to your
          system's PATH during installation.
      
      ii. Open a Terminal or Command Prompt:
      
      a) Windows: You can open Command Prompt by searching for it in the Start Menu or using the Win + R key combination, then typing cmd.
      
      iii.Install Pygame using pip:

a) Enter the following command in the terminal:
   bash

       pip install pygame


If you have Python 3.x installed, you might need to use pip3 instead of pip:

   bash

       pip3 install pygame
       
iv. Verify the installation:

After the installation is completed, you can verify whether Pygame is installed correctly by opening a Python shell and importing Pygame:

python

        import pygame
        
If no errors occur, the installation was successful.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### FRAMEWORK

###Pytest:

1) What is Pytest?
   
Pytest is a testing framework for Python that allows for simple and scalable testing. It is widely used due to its ease of use, scalability, and extensibility. Pytest helps you write simple and maintainable tests for your Python codebase.

Key features of Pytest include:

      i.  Fixture Support: Pytest provides a way to use fixtures, which are functions that can set up preconditions for your test. 
          Fixtures can be used to create test data, set up connections, or perform any necessary setup before running your tests.
      
      ii. Assertions: Pytest uses Python’s assert statement, making it intuitive to write and read assertions. It also provides a 
          wide range of assertion helpers that make it easier to perform different types of checks in your tests.
      
      iii.Parameterization: Pytest allows you to run the same test with different inputs using parameterization. This is very useful
          for testing a function or method with various input values.
      
      iv. Plugins and Extensibility: Pytest has a rich ecosystem of plugins that extend its functionality. You can use plugins to 
          generate test reports, integrate with other tools, or even create custom plugins tailored to your needs.
      
      v.  Integration with Other Testing Tools: Pytest can work seamlessly with other testing tools and libraries, making it versatile
          and adaptable to different testing requirements.

2) Description of PyTest.

Pytest is a popular testing framework for Python that simplifies the process of writing and executing tests. It provides a comprehensive and flexible set of tools for testing Python code. Here's an overview of its key features:

      i.  Simplicity: Pytest offers a straightforward syntax that allows you to write concise test cases using plain assert statements,
          making it easy to learn and use. Test functions are identified by their name prefix 'test_' and can be organized in a modular
          way within Python files or across multiple files.
      
      ii. Fixture Support: The fixture system in Pytest helps set up and manage the test environment. Fixtures are reusable functions that
          provide a way to create and initialize resources required for testing. They assist in the setup and cleanup of common test dependencies.
      
      iii.Parameterization: Pytest supports parameterized testing, enabling the execution of the same test with multiple inputs. This feature is 
          useful for testing functions or methods with various sets of input data, reducing the need for repetitive test code.
      
      iv. Assertions: It supports Python's assert statement and provides an extensive set of assertion helpers for more detailed and informative
          test failures. Pytest generates detailed reports when assertions fail, aiding in debugging and identifying issues quickly.
      
      v.  Plugin Ecosystem: Pytest has a rich ecosystem of plugins that extend its capabilities. These plugins offer additional functionalities
          such as code coverage analysis, test result reporting, integration with other tools, and support for various types of tests (e.g., Django, Flask, 
          and more).

3) Advantages of Pytest

Pytest offers several advantages that contribute to its popularity among developers for testing Python applications. Some of the key advantages include:

      i.  Simplicity and Readability: Pytest has a simple and easy-to-understand syntax. It uses Python’s assert statement and offers a clean,
          readable way to write test cases, making it accessible to both beginners and experienced developers.
      
      ii. Fixture System: The fixture system in Pytest enables easy setup and management of test environments. Fixtures provide a way to create
          and initialize resources required for testing, facilitating reusable and modular test code.
      
      iii.Parameterization: Pytest supports parameterized testing, allowing the same test function to be run with multiple inputs.
          This feature reduces code duplication, making tests more concise and manageable.
      
      iv. Powerful Assertions: Pytest provides a rich set of assertion helpers for more detailed and informative test failure reports.
          These assertions make it easier to identify issues and debug failed tests.
      
      v.  Extensive Plugin Ecosystem: Pytest has a large ecosystem of plugins that extend its functionality. These plugins cover various
          aspects such as generating reports, code coverage analysis, integration with other tools, and support for testing frameworks and libraries.

4) How to install Pytest.

To install Pytest for your Python environment, you can use Python's package manager, pip. Here are the steps:

i.  Open a Terminal or Command Prompt: You'll need to access the command line on your system.

ii. Install Pytest using pip: Use the following command to install Pytest:

bash

    pip install pytest
    
If you are using Python 3 and have both Python 2 and Python 3 installed, you might need to use pip3:

bash

    pip3 install pytest
    
iii.Check Installation: Once the installation is complete, you can verify that Pytest is installed by checking the version:

bash

    pytest --version
    
This command should display the installed version of Pytest.

Additionally, you can also create a virtual environment to manage your project dependencies. To create a virtual environment:

i.  Install virtualenv (if not already installed):

bash

    pip install virtualenv
    
ii. Create a Virtual Environment:

bash

    virtualenv myenv
    
Replace myenv with the name you want to give to your virtual environment.

iii.Activate the Virtual Environment:

On Windows:

bash

    myenv\Scripts\activate

iv. Install Pytest within the Virtual Environment:

Once your virtual environment is activated, install Pytest as previously described:

bash

    pip install pytest
    
This method isolates the Python environment for your project and helps manage dependencies without affecting the global Python installation.

After the installation, you can start using Pytest to write and run your test cases within your project.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### DEMO NINJA IDE, PYGAME AND PYTEST

[![Watch the video](https://img.youtube.com/vi/hESNf3QstpE/hqdefault.jpg)](https://www.youtube.com/embed/hESNf3QstpE)


