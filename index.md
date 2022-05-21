# Developer Docs
Everything you need to know about FinDesk's plugin architecture
## FinDesk
FinDesk is a web based financial managment system which is expandble using plugins.

## What FinDesk offers
Out of the box FinDesk offers a basic Financial managment system with plugin architecture built-in. A few sample plugins are also available for FinDesk however, its functionality can be expanded by building you own plugins and integrating them into FinDesk.
## How the documentation is organized
 The documentation will help you in getting started with FinDesk Plugin development. The documentation uses a tutorial based approach that helps you understand core concept of plugin developemnt using a REST API as example.

 ## Core Concepts
 FinDesk aims to reduce the learning curve for plugin development especially for Django developers. Since FinDesk is based on Django, its functionality can be increased while using all the tools tha Django has to offer. FinDesk utilizes Django's concept of reusable components i.e. `apps` and with minimun effort convert them into plugins that can be incorporated in FinDesk on runtime.

___

## Getting Started

### 1. Install Python
___

Being a Python based framework, FinDesk requires Python. Python includes a lightweight database called SQLite so you won’t need to set up a database just yet.

Get the latest version of Python at https://www.python.org/downloads/ or with your operating system’s package manager.

### 2. Download FinDesk
___
You can download latest release of FinDesk from [this link](https://github.com/SaadJamilAkhtar/FinDesk)

### 3. Install Deps
___
You can install all required dependencies by navigatin to FinDesk folder in a terminal and running command  
`pip install -r requirements.txt`

### 4. Run server
___
Run FinDesk on your local machine using command  
`python manage.py runserver`


___

[Getting started with plugin development](./pluginDevelopment.md)




