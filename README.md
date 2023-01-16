# php-tech-test
PHP Command Line Program for Service Catalogue
This program allows you to query data in a CSV file containing a service catalogue based on country code and produces a summary output showing the total number of services in each country.

Usage:
Save the program to a file (e.g. services.php)
Run the program by typing php services.php countrycode on your command line, where countrycode is the two letter country code you want to query.

Output:
The program will print the ref code, center, service name and country code for the services provided by the country specified by the country code.
The program will print the service count for each country.

Future changes:

i would make the code reusable by putting the logic into reusable classes and writing unit tests to demonstrate that the code works correctly. This would include doc blocking the functions

