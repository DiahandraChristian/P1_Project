# RoSA
# RoSA or Robotic Shopping Assistant, is a UiPath automation that shops for a vendor utilizing the Pega Training Website.
Rosa is your robotic shopping assistant, here to help your shopping business. RoSA helps you shop for all your customers from online vendor, create customer individual expense reports sent via email.
## Technologies Used
UiPath Studio 2020.10.7 <br>
Azure Data Studio/Microsoft Azure Portal<br>
Pega Training Website <https://training.openspan.com/login>
## Features 
### Current Features
- Take customer shopping list from your excel files
- Shop for customers in the Pega Training Website
- Record their expense in a receipt and store it in the database
- Use customer information that is created in SQLserver database for the client
- Record expense report, add service base fee, and commission fee in a reciept as .xlsx file and email that to the client 
- Email receipt, along with commission fee and service base fee to the customer 
- Email reciepts to the shopper for a profit report
- Send customers order number that should be stored in the SQLserver database

### To-Do List
- Simplified way to get customers data and be able to pull a profit report to email to the shopper. 
- Being able to store customers individual shopping list in the database

## Getting Started
- git clone https://github.com/DiahandraChristian/P1_Project.git
- Open file Connect2DB.xaml
- edit "Connect to Database" and "Run Query" in UiPath activities to connect to customers SQLserver Database
- Check SQLserver Database for customers information stored in tables with columns with the following: ([first_name], [last_name], [st_address], [zip_code], [email], [customers_id], [card_type], [card_number], [expiration_mo], [expiration_yr], [cvc])

## Usage
- Open P1PegaProject on main project folder to start consumer automation.
![image](https://user-images.githubusercontent.com/104388361/174124553-a5eb6a1a-ab2d-4831-8778-cec3c56ed492.png)

## License
- https://github.com/DiahandraChristian/P1_Project/blob/main/License
