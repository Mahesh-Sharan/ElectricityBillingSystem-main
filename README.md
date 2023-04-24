<h1>ElectricityBillingSystem ⚡️ </h1>
<ul>

<li>Electricity Billing System is a software-based application developed in Java programming language.<br></li>
<li>The project aims at serving the department of electricity by computerizing the billing system.<br></li>
<li>It mainly focuses on the calculation of Units consumed during the specified time and the money to be paid to electricity offices. <br>
</li><li>This computerized system will make the overall billing system easy, accessible, comfortable and effective for consumers.<br></li>
</h4>
<br>

<h2>Tools Used : </h2> <ul>
<li>Languages Used : JAVA<br></li>
<li>Frameworks Used: Swing, AWT<br></li>
<li>Databases Used : MySQL<br></li>
<li>IDE Used : VSCode<br></li>
<br>

<h2>Guide To setup Database<h2>

<h3>1. Open Mysql and create a new database as follow : " create database electricity;" and use it.<br><br>
2. Now we need to add following tables as follow (just copy paste) :<br><br>


>>create table login(meter_no varchar(20), username varchar(30), name varchar(30), password varchar(30), user varchar(30));<br/>
>>
>>create table customer(name varchar(30), meter varchar(20), address varchar(50), city varchar(20), state varchar(30), email varchar(30), phone varchar(20));
>>
>>create table meter_info(meter_number varchar(20), meter_location varchar(20), meter_type varchar(20), phase_code varchar(20), bill_type varchar(20), days varchar(20));
>>
>>create table tax(cost_per_unit varchar(20), meter_rent varchar(20), service_charge varchar(20), service_tax varchar(20), swacch_bharat_cess varchar(20), fixed_tax varchar(20));
>>
>>insert into tax values('9','47','22','57','6','18');
>>
>>create table bill(meter varchar(20), month varchar(20), units varchar(20), total_bill varchar(20), status varchar(20));<br><br>

Now just run the project from vscode.

<br><br>
<h1> That's it !! Enjoy 😍 </h1>
