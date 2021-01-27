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
   
