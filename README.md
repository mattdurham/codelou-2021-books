# Project to Book Library

I want uses to be able to keep track of books that own. They should be able to view, delete, and add books. Book information will be pulled from openlibrary.org and will record the name, author, edition, and isbn. This information will be persisted to the disk in the json format.

# Basic Requirements

* Create at least one class: 
  * Create a class to hold the results of the openlibrary.org request. 
* Create 3 functions
  * Create an add function
  * Create a remove function
  * Create a view function

# Feature Requirements

* Implement a master loop
  * UI will ask the user if they want to view, add, remove or exit
* Create a dictionary or list
  * Books will be held in the a list in memory
* Connect to a 3rd party
  * Calling openlibrary.org
* Read data from external file
  * Current collection will be stored on disk in a json file
