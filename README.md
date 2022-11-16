# Bankist--Main---Bank-App
Bank app with clean UI having necessary banking features like sending, receiving, getting Loan.  as of now crud is implemented locally so limited to 4 users
{will soon add features like creating a new user and store all details like transactions, id pass for verfication and all CRUD into a database}

Features :

1. User can send money to other user .
2. User can get loan from the bank , which cant exceed above 9 times their available balance (900%)  of their total available balance .
(eg: you have 100 in your account then loan amt cant exceed above 1000 )
4. Used world time API to fetch current time based on current region of user .

USE THESE IDS TO LOGIN 
USER : 
const account1 = {
  owner: 'js',
  pin: 1111,
};

const account2 = {
  owner: 'jd',
  pin: 2222,
};

const account3 = {
  owner: 'stw',
  pin: 3333,
};

const account4 = {
  owner: 'ss',
  pin: 4444,
};
