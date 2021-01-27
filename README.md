# payment_process

### How to run the project
Have `pipenv` installed in your system

run the following command to do so.
    1. clone the project from git on your system 
    
    git clome https://github.com/ThenukaDharmaseelan/payment_process.git
    
   2. cd `filed_payments`
   3. run command `pipenv install`
   4. run to go in virtual environment, inside the project run command `pipenv shell`
   5. run command to run the flask server `flask run`
   6. To exit server run `ctrl+c`
   7. To exit the virtual env run command in terminal `deactivate`
   
 ## How to test the application
 
   1. run the server first using above step
   2. in seperate terminal, run `cd application/test` ie go to test folder
   3. Activate python environment, `pipenv shell`
   4. run comands: `pytest test_external_payment.py`
   
 ### Shortcoming OR consideration 
 
 1. ExpirationDate format is `yyyy/mm/dd` not `mm/dd` as found in the credit card usually.
 2. Testing of external payment gate should be done with there api (i don't know how to test that part without there api, if anyone know i would learn to do that).
 
 ### Note
 
 if you find this project help you to create the assignment in anyway, please fork or click on watch this project
 i will be really happy :D. 
