# IBM_Watson_Challenge

**Technical Architecture Diagram**



**Intents in CSV:(also attached along)**

What is my balance?, balance\_enquiry

How much money do I have in my account?. balance\_enquiry

Whats my account balance?, balance\_enquiry

Account balance please., balance\_enquiry

Send my account details to my email., account\_statement

Send my statement for the last one year to my email account., account\_statement

email me my statement for the last month., account\_statement

I want to transfer funds to another account., fund\_transfer

please transfer 5000 rs to my friends account., fund\_transfer

how do i transfer money to another account., fund\_transfer

What is the process to transfer money to another bank account?., fund\_transfer

I want to open an FD., fd\_opening

Whats the process to open an FD?, fd\_opening

Can I open an FD from here?, fd\_opening

How do I open an FD account?, fd\_opening

I want to topup my phone., mobile\_recharge

Please recharge my phone balance, mobile\_recharge

My phone balance is low I want to add money, mobile\_recharge

Make phone recharge of Rs 100, mobile\_recharge

Can I add money to my phone from here?, mobile\_recharge

I want to ask for a loan., byom\_lones

What is the procedure to get a loan from bank?, byom\_loans

What is be your own master loans, byom\_loans

Guide me through getting a loan, byom\_loans

I am requesting for a loan please process it, byom\_loans

**Languages:**

We will be basically using python for the backend. We will us the facebook messenger SDK for python for the user interface. We will use the watson&#39;s RESTful API called via our python backend. Our backend will be in flask which is a BSD licensed microframework for Python based on Werkzeug, Jinja 2. Some of our code will also be in C to perform high performance modelling.

We will be hosting our main code of backend on the IBM bluemix, it will also be the main point of contact for the following IBM services that we will use.

- IBM Watson for the powerful natural language processing APIs
- IBM Cloudant DB to store all the queries and logs
- IBM Watson translation API to integrate more languages like Hindi for users who recently enrolled after Pradhan Mantri Jan Dhan Yojna.
