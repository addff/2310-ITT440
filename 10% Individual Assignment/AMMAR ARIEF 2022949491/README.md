# 2310-ITT440

## NAME: AMMAR ARIEF BIN AINOL AHMAM (2022949491)

## TITLE: PYTHON FOR NETWORK ENGINEER


### OBJECTIVE
- To search for library or tools that can help Network engineer and introduced usable editor and framework




### Editor: Notepad ++


![notepad++](https://github.com/addff/2310-ITT440/assets/84883844/597c8617-2a46-46b0-a02b-5ac0dbf5d6aa)

Notepad++ is a popular and free source code editor and text editor for Windows. It was developed by Don Ho and is distributed under the GNU General Public License. Notepad++ is known for its user-friendly interface and its extensive support for various programming languages and file formats.


###### Significance Of Notepad++ :

- Free and Open Source: Notepad++ is free to use, and its open-source nature means that its source code is publicly available. This transparency allows users to inspect and modify the software, as well as contribute to its development.

- Lightweight: Notepad++ is a lightweight application, which means it doesn't consume a significant amount of system resources. It loads quickly and runs smoothly even on older or less powerful computers.

- Extensible: Notepad++ supports a wide range of plugins that can be used to enhance its functionality. This extensibility allows users to add features and capabilities as needed.

- Multi-Language Support: It supports a wide variety of languages and character encodings, making it a versatile choice for users around the world.

- Community and Support: It has a strong and active user community, which means you can find help, tutorials, and plugins created by other users to extend its functionality.



---
## Library/module: python-whois

python-whois is a Python library used to retrieve WHOIS information for domain names. WHOIS is a protocol and a database used to look up information about domain names, such as the domain's owner, registration date, expiration date, and more. It is commonly used to find out details about a specific domain, including contact information for the domain registrar and registrant.

*or simply a library to see website information*


- Open Source: Python-whois is open-source, which means it is freely available for anyone to use, modify, and contribute to. Its open-source nature encourages collaboration and the development of additional features and improvements.

- Domain Management: It provides a convenient way to retrieve WHOIS information, making it a valuable tool for domain name management. Whether you're managing your own domains or need to look up details about domains for various purposes, Python-whois simplifies the process.

- Automation: Python-whois allows for the automation of WHOIS queries, which is useful for organizations or individuals who need to perform large-scale or repetitive domain lookups. This can save time and effort compared to manually querying WHOIS information for numerous domains.

- Cybersecurity: WHOIS data can be used for cybersecurity purposes, such as identifying the owners of domains associated with potentially malicious activities. Security professionals and researchers often use Python-whois to gather information on suspicious domains.

- Data Analysis: WHOIS data can be used for data analysis and research purposes, and Python-whois facilitates the extraction and parsing of this data for further analysis.

- Open Source: Python-whois is open-source, which means it is freely available for anyone to use, modify, and contribute to. Its open-source nature encourages collaboration and the development of additional features and improvements.


###### Exact code used:

``` py

import whois
import country_converter as coco

web_pop = [' "https://www.nationalgeographic.com/" ', ' "https://www.espn.com/" ', ' "https://www.nytimes.com/" ', ' "https://www.bbc.com/" ', ' "http://www.cnn.com/" ', ' "http://www.yahoo.com/" ', ' "http://www.apple.com/" ', ' "http://www.microsoft.com/" ', ' "http://www.ebay.com/" ', ' "http://www.netflix.com/" ', ' "www.pinterest.com/" ', ' "http://www.reddit.com/" ', ' "http://www.wikipedia.org/" ', ' "http://www.linkedin.com/" ', ' "http://www.instagram.com/" ', ' "http://www.twitter.com/" ', ' "http://www.amazon.com/" ', ' "http://www.youtube.com/" ', ' "http://www.facebook.com/" ', ' "http://www.google.com/" ']


for x in web_pop:
    res = whois.whois(x)
    
    if res.domain_name != None:
        print (res.domain_name)
    
    if res.creation_date != None:
        print (res.creation_date)
    
    if res.expiration_date != None:
        print (res.expiration_date)
    
    if res.emails != None:
        print (res.emails)
    
    if res.address != None:
        print(res.address)
    
    if res.country != None:
        print (coco.convert(names=res.country, to="name_short"))
        
    print ("                 ")
    print ("                 ")
 

```
```
//example input

res = whois.whois("https://www.bbc.com")
print (res.domain_name)
print (res.creation_date)
print (res.expiration_date)
print (res.emails)
print(res.address)
print (coco.convert(names=res.country, to="name_short"))

//example output

BBC.COM
1989-07-15 04:00:00
2030-07-14 04:00:00
['domainabuse@tucows.com', 'hostmaster@bbc.co.uk']
REDACTED FOR PRIVACY //address
United Kingdom 
```

```
//include 20 most popular website
//Technically there is 2 library
```


---

### Framework: pynecone/reflex

![reflex](https://github.com/addff/2310-ITT440/assets/84883844/99df6a5e-4ed1-4df7-888f-734f5c121dd7)

Reflex is an open-source, full-stack Python framework that makes it easy to build and deploy web apps in minutes. Reflex is a full-stack framework for building and deploying web apps.

*Reflex or Pynecone is a web framework!*




###### Significance Of pynecone :

**Pure Python**

Use Python for everything. Don't worry about learning a new language.

**Easy to Learn**

Build and share your first app in minutes. No webdev experience required.

**Full Flexibility**

Remain as flexible as traditional web frameworks. Reflex is easy to get started with, but powerful enough for advanced use cases.

Build anything from small data science apps to large, multi-page websites.

This entire site was built and deployed with Reflex!

**Batteries Included**

No need to reach for a bunch of different tools. Reflex handles the frontend, backend, and deployment of your app.

###### Exact code use: 

``` py
import pynecone as rx



def index() -> rx.Component:
    return rx.container(
        rx.heading(
            "hello my name is ammar",
            text_align="center",
            color="blue",

        ),
        rx.button(
            
            "click me",
            bg = "#fef2f2",
            color = "#b91c1c",
            border_radius = "lg",
            

        )
    )

# Add state and page to the app.
app = rx.App()
app.add_page(index)
app.compile()
```


##### video included below: 
[![video included below](https://img.youtube.com/vi/g3Kd1tH_KUg/0.jpg)](https://www.youtube.com/watch?v=g3Kd1tH_KUg)
