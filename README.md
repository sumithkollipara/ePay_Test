Hi,

You will find two projects in this repository(ePay_Test) as named below:
 - Denomination_Routine
 - Rest_Server
 
Project execution process:
 - Open solution with Visual Studio IDE
    * Denomination_Routine is a console application
      - Please set as the start-up project
      - Run the project and then follow instructions in the console window
      - Eg. If you want to see the denominations of 50, please enter 50 EUR and you can see the permutations and combinations of denominations with the payout amount
      - In case you like to check different amounts after the above step please press "Y" so that you will be able to enter the next desired payout amount.
    * Rest_Server is a Web API project
      - Please set as the start-up project
      - Choose the browser as your choice and run the project
      - Swagger UI will be opened in the selected browser
      - You will find three methods in the swagger UI
        1. GET: /Customer/{customerCount}: which will return a list of prepared customers.
        2. GET: /Customer: Returns list of all customers from the server.
        3. POST: Multiple (2 or more) customers can be inserted into the server.
