# appgen - tool for generate applications

## Description:
### This tool helps create the structure of an application, including database
### For now it generates for Python and PHP


## Instalation

- Download appgen: [appgen files](https://github.com/ortizdavid/appgen-files)
- Add appgen to **PATH** environment variable


## Usage:

**appgen** **-name** application_name **-lang** language **-type** application_type **-db** <database>

##  Commands:
- **appgen**:     First command
- **list-langs**: List all supported languages and applications
- **help**:       Shows helps for appgen
- **-name**:      Project Name
- **-lang**:      Programming Language
- **-type**:      Type of application (mvc, api)
- **-db**:        database 

## Examples:

1. Create a MVC App with Python and MySQL:
    ``
    appgen -name PythonMVC -lang python -type mvc -db mysql 
    ``

2. Creates an API with Python and Postgres:
    ``
    appgen -name PythonAPI -lang python -type api -db postgres    
    `` 

3. Show help comands:
    ``
    appgen help 
    ``   

4. List all suportded languages:
    ``
    appgen list-langs 
    ``                                                      

## Author:
- Name:         Ortiz de Arcanjo António David
- Phone:        +244 936 166 699
- Email:        ortizaad1994@gmail.com
- Github:       https://www.github.com/ortizdavid
- LinkedIn:     https://www.linkedin.com/in/ortiz-david


## AppGen Flow

<img src="AppGen Flow.jpg">


## Generating API

![Generating API](Appgen-API.gif)
