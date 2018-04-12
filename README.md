# REST-api-with-PHP
This repository contains an api for CURD operation.
Designed with PHP slim framework it's easy to understand and modify

# How to call the api?
Basically I have performed operations using this api on a customer information table.

*GET - yourdomain.com/api/customers*
      this will give information about all customers in JSON format
      
      -yourdomain.com/api/customers/{id}
      this will give the information about customer having id={id}.
*POST - yourdomain.com/api/customers/add*
      this will add new entry to the table the JSON file should be like this
      {
        "name":"Sachin",
        "surname":"Sapkal",
        "phone":"9876543210",
        "email":"a@b.com",
        "address":"asvd agsd ahsvd ahsvd ahsvd ahsvd",
        "city":"Pune",
        "state":"Maharashtra"
      }
      
*DELETE - yourdomain.com/api/customers/delete/{id}*
      this will delete the record of the given id
      
*PUT - yourdomain.com/api/customers/update/{id}*
       this will update a row in table the JSON file should be like this
      {
        "name":"Sachin",
        "surname":"Sapkal",
        "phone":"9876543210",
        "email":"a@b.com",
        "address":"asvd agsd ahsvd ahsvd ahsvd ahsvd",
        "city":"Pune",
        "state":"Maharashtra"
      }
      
