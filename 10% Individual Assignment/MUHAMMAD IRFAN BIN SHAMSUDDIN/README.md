# MUHAMMAD IRFAN BIN SHAMSUDDIN (2021862488)
 
# ITT440 - 10% Individual Assignment


## Openpyxl
### 1. What is Openpyxl?
		Openpyxl is a Python library for reading and writing Excel (xlsx) files. 
		It allows you to manipulate Excel spreadsheets, create new ones, modify 
		existing ones, and perform various operations on Excel data using Python. 
		It's a handy tool for automating tasks involving Excel files and is commonly 
		used in data analysis, report generation, and other data-related applications.

### 2. Advantages of Openpyxl
		> Ease of Use: Openpyxl provides a user-friendly interface for working with 
		Excel files in Python, making it relatively easy to understand and implement.

		> Read and Write Support: It supports both reading from and writing 
		to Excel files, allowing for a wide range of data manipulation tasks.

		> Compatibility: Openpyxl supports the .xlsx format, which is the 
		default format for	Excel files in recent versions. This ensures
		compatibility with the latest Excel files.

		> Rich Feature Set: It offers a variety of features, such as styling cells, 
		handling formulas, and working with charts, providing a comprehensive 
		toolkit for Excel file manipulation.

		> Active Development: Openpyxl is actively maintained and developed, 
		which means that it is continually updated to support the latest Excel 
		features and to fix any bugs or issues.

		> Open Source: Being an open-source library, Openpyxl is free to use, and 
		its source code is accessible for inspection and modification, providing 
		transparency and flexibility.

		> Community Support: Due to its popularity, there is a supportive community 
		around Openpyxl. This means you can find resources, tutorials,
		and assistance from other users and developers.

		> Openpyxl is a reliable and widely used library for Excel file manipulation 
		in Python. Its active development and community support contribute to its 
		effectiveness and versatility. While it may not cover every possible Excel 
		feature, it addresses most common use cases and continues to evolve with 
		the changing landscape of Excel functionality.
		
## FastAPI
### 1. What is FastAPI?
		FastAPI is a modern, fast (as the name suggests), web framework for building 
		APIs with Python 3.7+ based on standard Python type hints. It is designed to 
		be easy to use, fast to develop with, and to provide high performance.

### 2. Advantage of FastAPI

		> Fast Performance: As the name suggests, FastAPI is designed for high performance.
		It leverages asynchronous programming and is built on top of Starlette, making it 
		efficient, particularly for I/O-bound operations.

		> Automatic API Documentation: FastAPI generates interactive and detailed API 
		documentation automatically based on your code, using the OpenAPI and JSON Schema
		standards. This makes it easy for developers to understand and test the API.

		> Type Safety: FastAPI uses Python type hints for request and response data, providing
		automatic validation and serialization. This not only improves code clarity but also 
		enables type checking during development.

		> Dependency Injection: It has a built-in dependency injection system that simplifies 
		the organization and reuse of code. This is particularly useful for managing 
		dependencies in a clean and maintainable way.

		> Security Features: FastAPI comes with built-in security features, including support
		for OAuth2 and API key authentication. This helps in implementing secure APIs without 
		the need for extensive manual configuration.

		> Asynchronous Support: FastAPI seamlessly integrates with asynchronous code, allowing
		you to handle a large number of concurrent requests efficiently.

		> Intuitive Syntax: The framework is designed to have an intuitive and easy-to-understand 
		syntax, resembling Python's syntax. This makes it accessible to developers and helps 
		in rapid development.

		> Automatic Validation and Serialization: FastAPI automatically validates incoming
		request data and serializes outgoing responses based on the defined data types. This
		reduces the likelihood of errors and simplifies data handling.

		> Active Development and Community Support: FastAPI is actively developed and has a
		growing community. This ensures that the framework is regularly updated with new 
		features and improvements, and there is community support for problem-solving.

		> Compatibility with Python Ecosystem: FastAPI seamlessly integrates with other Python
		libraries and frameworks, allowing you to leverage the broader Python ecosystem for 
		various functionalities.

### 3. Command For FastAPI
		from fastapi import FastAPI
		app = FastAPI()
		@app.get("/")
		async def root():
		    return {"message": "my name is muhammad irfan bin shamsuddin"}
		@app.get("/hello/{name}")
		async def say_hello(name: str):
		    return {"message": f"Hello {name}"}

## Komodo IDE
### 1. What is Komodo IDE?
		Komodo IDE is an integrated development environment (IDE) for software development, 
  		primarily focusing on dynamic languages such as Python, Ruby, PHP, JavaScript, HTML, 
    	and CSS. It is developed by ActiveState.

### 2. What is the advantages for using this Komodo IDE?
		> Multi-Language Support: Komodo IDE supports a wide range of programming languages,
 		making it versatile for developers who work with diverse technologies. This is particularly 
  		beneficial for those who work on projects involving multiple languages.

		> Code Intelligence: The IDE provides advanced code intelligence features, including 
  		code completion, syntax highlighting, and code browsing. This enhances developer
    	productivity by offering context-aware suggestions and quick access to relevant information.

		> Integrated Debugger: Komodo IDE comes with a built-in debugger, allowing developers 
  		to efficiently identify and fix issues within their code. This includes support for 
    	remote debugging, making it useful for debugging applications running on different servers.

		> Version Control Integration: It integrates seamlessly with popular version control systems 
  		such as Git, Mercurial, and Subversion. This facilitates collaborative development by 
		providing versioning and code repository management directly within the IDE.

		> Customization: Komodo IDE is highly customizable, allowing developers to tailor the environment
  		to their preferences. This includes customizing themes, keyboard shortcuts, and other aspects of
  		the IDE for an optimized development experience.

		> Project Management: The IDE offers features for managing projects, organizing files, and
  		navigating codebases effectively. This is crucial for developers working on large and complex projects.

		> Web Development Support: Komodo IDE includes features specific to web development, 
  		making it suitable for projects involving HTML, CSS, JavaScript, and other web technologies. 
    	This includes tools for building and maintaining modern web applications.

		> Extensibility: Developers can extend the functionality of Komodo IDE by creating and
  		integrating add-ons. This extensibility allows developers to tailor the IDE to their
    	specific needs or leverage community-contributed extensions.

		> User-Friendly Interface: Komodo IDE is designed with a user-friendly and intuitive
  		interface, making it accessible to developers with varying levels of experience. 
    	The interface is crafted to enhance productivity and ease of use.

		> Active Development and Support: Komodo IDE is actively developed and maintained by 
  		ActiveState. This ensures that the IDE receives regular updates, bug fixes,
    	and improvements, and there is ongoing support for users.

DEMO Video for Komodo IDE, FastAPI and Openpyxl

[![Video](https://img.youtube.com/vi/hDCUhxmAIVE/maxresdefault.jpg)](https://www.youtube.com/watch?v=hDCUhxmAIVE)
