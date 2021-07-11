Hi,

You will find two projects in this project ePay_Test repositiory as named below 
 - Denomination_Routine
 - Rest_Server
 
Project execution process:
 - Open solution with Visual stuido IDE as administrator and rebuild solution
    * Denomination_Routine is a console application
      - Please set as start up project
      - Run the project and then follow the instructions in the console
      - Eg. If you want to see the denominations of 50, please enter 50 EUR and you can see the permutations and combinations of denominations with payout amount
      - In case you like to check different amount after the above step please press "Y" so that you will be able to enter next desired payout amount.
    * Rest_Server is a Web API project
      - Please set as start up project
      - Choose the broswer as your choice and run the project
      - Swagger UI will be opened in the selected browser
      - You will find three methods in the swagger UI
        1. GET: /Customer/{customerCount}: which will returns list of preprared customers.
        2. GET: /Customer: Returns list of all customers from the server.
        3. POST: Multiple (2 or more) customers can be inserted into server.
