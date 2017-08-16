# JNEBENZ
A JNE Module for Prestashop
This module will calculate the JNE Shipping cost based on weight and kecamatan/district to where the package is sent. Hence make it highly accurate.
Warning!! This module will override other shipping module in prestashop.
Please read the installation guide below:

Installation Guide:
1.  Install module
2.	Run JNEBENZ.sql in MySQL query console
3.	Copy 
    ….\\\jnebenz\views\templates\front\js\tools\statesManagement.js
    to
    ….\\\ \themes\default-bootstrap\js\tools\statesManagement.js
4.	Copy ….\\\jnebenz\4.jpg to shiping image folder (\img\s\)
5.	Copy ….\\\jnebenz\5.jpg to shiping image folder (\img\s\)
6.	Copy ….\\\jnebenz\6.jpg to shiping image folder (\img\s\)
7.	Add field district
    Login admin -> Localization -> Countries -> Edit -> Add field District:district dan City:name
8.	Change the fields address sequence:
    Login admin -> Localization -> Countries -> Indonesia -> Edit -> Change address format 
        firstname 
        lastname
        address1
        address2
        Country:name
        State:name
        City:name
        District:district
        postcode 
        phone
        phone_mobile
        company
        vat_number

9.	Activate the module by purchasing a subscription for JNE shipping cost data: 
    a. Register your data and email address to www.sartono-media.com/jnebenzsubscribe
    b. You'll get an email with the instruction to activate your subsription
    c. Upon receiving your subscription payment, we will activate your subscription and your module is active
    d. Your subscription is subjected to monthly payment

Note: 
1.	This installation guide is assumed to have your prestashop installed with  _DB_PREFIX_  as “ps_”. You can either adjust your      
    _DB_PREFIX_ to “ps_” or, if you can, adjust some script in the module accordingly.
