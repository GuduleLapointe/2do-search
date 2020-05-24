2DO Hypergrid Events search
===========================
Version 0.0.17

In-world Search engine for 2DO Hypegrid Events.

Based on [Outworldz OpensimEvents](https://github.com/Outworldz/OpensimEvents)

Installation
------------
* Clone this project in "search" folder, inside your web directory to make it
available by http://example.com/search
    * Make sure your server handles perl cgi. For apache:
    ```
    sudo apt install libapache2-mod-perl2
    sudo a2enmod perl
    ```
    * Make sure your server accepts .htaccess rules, otherwise copy .htaccess
      content in your website configuration
* If needed, create ossearch database and database user
  (follow instructions in README-sql-tables.txt)
* Create a copy of lib/MySQL.txt.example as lib/MySQL.txt and update it with
  the right database credentials
