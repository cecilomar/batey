# Batey

*This project is under development and in a planning status. Please come back later for updates.*

Batey will be a really simple content management system. It will generate a website from files placed in a specific directory and from a specified file extension. The idea is that you can place all the content of your website in the same place with no need for a database.

## `index.php`
This will be the heart of the script and where you can tweak all of the options.

## `template.php`
The template will be named `template.php`. A menu will be generated with links to every single item. To add the menu to the template, simply add `{menu}` anywhere in `template.php`. This will generate a list (`<ul> <li>`) with every single item. To add the content part, which is the content of the loaded document, simply add `{content}` anywhere in `template.php`. The title of the page will be taken from the name of the document but it will not include the file extension. Eg: The title of `Contact Me.php` would be *Contact Me*. To add the title to the template, simply add `{title}` anywhere in `template.php`.

You can use Batey to create a simple website, web application, web administration, etc. The idea is to create a page for every single part you like. This makes editing easy and keeps everything tidy. Everything is enclosed in an optional login interface.

## Directory
...
