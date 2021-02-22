# Beginers Project - Banking System 

### Description - 

#### Let's take a look at the anatomy of a credit card:

[Credit-Card](https://github.com/dcs-soni/python-banking-system/blob/main/img/Credit-Card.png)



#### In our banking system, credit cards should begin with 4.

#### The first six digits are the Issuer Identification Number (IIN). These can be used to look up where the card originated from. If you have access to a list that provides detail on who owns each IIN, you can see who issued the card just by reading the card number.

#### Here are a few you might recognize:

#### Visa: 4*****
#### American Express (AMEX): 34**** or 37****
#### Mastercard: 51**** to 55****

#### In our banking system, the IIN must be 400000


#### The seventh digit to the second-to-last digit is the customer account number. Most companies use just 9 digits for the account numbers, but it’s possible to use up to 12. This means that using the current algorithm for credit cards, the world can issue about a trillion cards before it has to change the system.

#### We often see 16-digit credit card numbers today, but it’s possible to issue a card with up to 19 digits using the current system. In the future, we may see longer numbers becoming more common.

#### In our banking system, the customer account number can be any, but it should be unique. And the whole card number should be 16-digit length.

#### The very last digit of a credit card is the check digit or checksum. It is used to validate the credit card number using the Luhn algorithm, which we will explain in the next stage of this project. For now, the checksum can be any digit you like.


## Objectives

#### You should allow customers to create a new account in our banking system.

#### Once the program starts, you should print the menu: 