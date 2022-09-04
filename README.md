# ECommerce Website in Php
![e-Commerce logo]( https://github.com/shourya2002-geek/ECommerce_Php/blob/master/media/logo/logo.jpeg)

This is a project about a website for e-Commerce. It is not a complete e-commerce system, however it serves as a basis for building one. This project uses MVC design pattern, made in PHP.

<hr />

## Requirements
- jQuery
- Bootstrap 4
- Adblock disabled in the page (this is because adblock blocks urls with 'ad' in the name)

## Project organization
![](https://github.com/shourya2002-geek/ECommerce_Php/blob/master/media/uml/uml.png?raw=true)

### /
|Name| Type| Function
|------- | --- | ----
| media | `Directory`| Visual informations about the project
| src | `Directory`| Contains all website files
| .project| `File`| File created by IDE


### /src
|Name| Type| Function
|------- | --- | ----
| assets| `Directory`| Contains all application content files
| controllers | `Directory`| Contains all application controller classes
| core | `Directory`| Contains the classes responsable for the MVC operations
| db | `Directory`| Contains [the database of the application](https://github.com/shourya2002-geek/ECommerce_Php/tree/master/src/db)
| models | `Directory`| Contains all application model classes
| vendor| `Directory`| Folder created by [Composer](https://getcomposer.org/) - responsable for classes autoload
| views | `Directory`| Contains all application view classes
| &#46;buildpath| `File`| File created by IDE
| &#46;htaccess| `File`| Responsible for friendly url
| &#46;project | `File`| File created by IDE
| composer&#46;json | `File`| File created by Composer
| config&#46;py | `File`| Website configuration file (Database and website location)
| environment&#46;php | `File`| File responsible for defining which environment is in use
| index&#46;php | `File`| File responsible for starting the website
