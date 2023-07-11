# Bank-Simulator
The “Bank Account Management System” project is a model Internet Banking Site. This site enables the customers to perform the basic banking transactions by sitting at their office or at homes through PC or laptop.
                                                                


## Tech Stack -

[![My Skills](https://skillicons.dev/icons?i=java,mysql,eclipse,git,github)]()                   

## File Structure -
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/9c2a5d0b-71d3-43d9-84ea-dd94a57bf9df)

## ScreenShots -                                           
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/7463452a-8d11-4dd3-aeb7-9fbe75f94ff9)

![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/48aba518-0586-432e-a513-a6034d79a4cb)

![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/5197a487-8fbb-4764-b45f-528d76318632)

![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/f48c2f70-bb67-4d92-8ac1-152ea9f627c9)      
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/85e85ff9-39a8-479e-ab34-3cfcac9ab930)
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/450cdff3-0f04-451e-8cf7-0710edf91ca3)





### Methods :                                                                                

∙ We need to be able to generate an account number                                                             
∙ Account types: Savings or Current Account                                                                                         
∙ Maintain/update Balance                                                                                               
∙ Open/Close Account                                                                                       
∙ Withdraw/Deposit              

### Admin Module :                                                                                                                      

Admin can access this project there is an authorization process. If you login as an Admin then you will be redirected to the Admin Home Page and if you are a simple user you will be redirected to your Account Home Page. This performs the following functions: Create 
Individual Accounts, manage existing accounts, View all transactions, Balance enquiry, 
Delete/close account etc. 

1- Admin login                                                                             
2- Add/delete/update account                                                                   
3- Withdrawal/deposit/statements transaction                                                                       
4- Account Information                                                                     
5- User details list                                                                                       
6- Active/Inactive account                                                                                         
7- View transaction histories                                                                                                           

### User Module:                                                                                

A simple user can access their account and can deposit/withdraw money from their account. 
User can also transfer money from their account to any other bank account. User can see their transaction report and balance enquiry too. 

1- User login, use PIN system                                                                                                   
2- Creating/open new account registration                                                                                       
3- Funds transfer (local/international/domestic)                                                                               
4- View statements transaction                                                                                           
5- User account details                                                                                             
6- Change Password and Pin                                                                                                                                            


### Banks terms: 

1. All requests received from customers are logged for backend fulfillment and are effective from the time they are recorded at the branch. 
2. Rules and regulations applicable to normal banking transactions in India will be applicable mutatis mutandis for the transactions executed through this site. 
3. The Bank service cannot be claimed as a right. The bank may also convert this into a discretionary service anytime. 
4. Dispute between the customer and the Bank in this service is subject to the jurisdiction of the courts in the Republic of India and governed by the laws prevailing in India. 
5. The Bank reserves the right to modify the services offered or the Terms of service of 
   Bank. The changes will be notified to the customers through a notification on the Site. 


### Customer’s obligations :

1. The customer has an obligation to maintain secrecy in regard to Username & 
Password registered with the Bank. The bank presupposes that login using valid 
Username and Password is a valid session initiated by none other than the customer. 
2. Transaction executed through a valid session will be construed by RR to have emanated from the registered customer and will be binding on him/her. 
3. The customer will not attempt or permit others to attempt accessing the Bank through any unlawful means.                             



# FLOWCHART                                                                        
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/17264afc-3f67-4857-9dcd-9cc5bc159fd2)                                          



# UML USE CASE DIAGRAM                                                                                                  
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/b92516cb-4269-4258-a0c4-533927b775a6)                                                                    


# ER DIAGRAM                                                                                              
![image](https://github.com/HiteshSharma-github/Bank-Simulator/assets/85629794/4dfcb4a2-bd52-4f12-925a-389e8cde4d89)                                

# Database Queries -
---------------------------------------------------
Database Queries for BANK MANAGEMENT SYSTEM Project
---------------------------------------------------

1 - Create database with name bankmanagementsystem in mysql

create database bankmanagementsystem;

2 - Select the database you just created

use bankmanagementsystem;

3 - Create our first Table in the selected database with name signup

create table signup(formno varchar(20), name varchar(20), father_name varchar(20), dob varchar(20), gender varchar(20),email varchar(30), marital_status varchar(20), address varchar(40), city varchar(25), pincode varchar(20), state varchar(25));

4 - Create the second table to store more information of user

create table signuptwo(formno varchar(20), religion varchar(20), category varchar(20), income varchar(20), education varchar(20), occupation varchar(20), pan varchar(20), aadhar varchar(20), seniorcitizen varchar(20), existingaccount varchar(20));

5 - Create the third table to store the account information of user

create table signupthree(formno varchar(20), accountType varchar(40), cardnumber varchar(25), pin varchar(10), facility varchar(100)); 

6 - Create the Login table to store login information

create table login(formno varchar(20), cardnumber varchar(25), pin varchar(10));

7 - Now create bank table to store transactions related information 

create table bank(pin varchar(10), date varchar(50), type varchar(20), amount varchar(20));                                                                        


<p align="center">
   Made with Java, JDBC, Java Swing, Java AWT and MySQL technology.
  <br/>
<p align="center">
  :star: Star me on this repo — it means a lot to me!
</p>
                 
