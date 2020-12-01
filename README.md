# README

# Contents

- Introduction
- Prerequisites
- Installing and configuring the module
- License

# Introduction

This Opencart module provides an easy method to integrate with the payment gateway.
 - Supports Open versions: **3.X**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php
    - SSL **NB: HTTPS is expected to be in place as the payment gateway will respond over SSL when redirecting the user's browser. Failure to provide an environment where HTTPS traffic is possible, will result in the 3DSv2 payment flow failing***

> Please note that we can only offer support for the Module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarentee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Copy the contents of the httpdocs directory into the root OpenCart directory.
2. Navigate to the Extentsions dropdown -> Extensions -> Payment methods -> Cardstream and hit 'Activate'
3. Navigate to the Extentsions dropdown -> Extensions -> Payment methods -> Cardstream and hit the 'Edit' button
4. Enter your MerchantID / Secretkey and update the customer/country code.
5. Selects what type of integration you would like to use.
6. Set what status you would like to update an order to once paid
7. Set the Enabled option to true.
8. Click 'Save Changes'.

License
----
MIT