# visitorTracking
A simple PHP class to gather visitor information, and store it in a database using MYSQLi

## LICENSE
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.
http://creativecommons.org/licenses/by-sa/4.0/

THIS SOFTWARE IS BEING PROVIDED "AS IS", WITHOUT ANY EXPRESS OR IMPLIED WARRANTY.  
IN PARTICULAR, THE AUTHOR DOES NOT MAKE ANY REPRESENTATION OR WARRANTY OF ANY KIND 
CONCERNING THE MERCHANTABILITY OF THIS SOFTWARE OR ITS FITNESS FOR ANY PARTICULAR PURPOSE.


## INSTALLATION


1. Upload the files to your server. 

1. Edit the database configuration ( `/includes/db.php` ) 

1. Create the `visitors` table in your database. (`/includes/visitors.sql` )

1. Instance the class in your code.

Demo: http://tyrexi.us/demo/visitorTracking


## EXAMPLE INITIALIZATION:

```php
//define database
`define( 'DB_HOST', 'localhost' );`			// set database host
`define( 'DB_USER', 'root' );` 				// set database user
`define( 'DB_PASS', 'root' );` 				// set database password
`define( 'DB_NAME', 'yourdatabasename' );`	// set database name

//include the class
include( 'class.visitorTracking.php' );

//instance the class
$visitors = new visitorTracking();
```
