## v5.0.0 - 2016-03-16
- **NEW META-102** Support for PHP 7.0 - *Joakim.L & Christer.G*

## v4.0.0 - 2015-05-27
- **NEW MINT-2176** Make SDK available on composer - *Joakim.L*
- **FIX MINT-2089** Fix URI for BETA mode with checkoutService - *Joakim.L*
- **NEW MINT-2193** Remove checkoutHTML method - *Joakim.L*
- **NEW MINT-2133** Add function extendExpiryDate - *Joakim.L*
- **FIX MINT-2178** Fix static invocation - *Joakim.L*

## v3.2.0 - 2014-11-11
- **NEW MINT-1894** Add setter for client IP - *Christer.G*

## v3.1.2 - 2014-11-06
- **FIX MINT-1930** Fix notice and warnings in PHP 5.3 & 5.4 - *Christer.G*

## v3.1.1 - 2014-08-22
- **NEW MINT-1664** Reformat changelog - *Christer.G*

## v3.1.0 - 2014-08-22
- **NEW MINT-1716** PHP library support for Checkout Service - *Christer.G*

## v3.0.0 - 2014-06-10
- **NEW MINT-1682** Remove functions updateNotes & reserveOcrEmail - *Christer.G*

## v2.6.0 - 2014-05-15
- **NEW MINT-1528** Remove Candice - *Christer.G*

## v2.5.0 - 2014-02-13
- **NEW MINT-1139** Code examples structure and comments - *Joakim.L*
- **FIX MINT-1238** Support read only databases - *Christer.G*

## v2.4.2 - 2013-07-02
- **NEW MINT-816** Update lowest_monthly_payment_for_account - *Rickard.D*

## v2.4.1 - 2013-06-05
- **FIX MINT-751** Update call filters out falsy values for digest - *Christer.G*

## v2.4.0 - 2013-05-08
- **NEW MINT-674** Add goods list to credit calls for restocking fees - *Rickard.D*

## v2.3.4 - 2013-05-03
- **NEW MINT-672** Change BETA host from beta-test to testdrive - *Joakim.L*

## v2.3.3 - 2013-03-28
- **FIX MINT-661** Creating reservation with amount 0 gets a error 9114 - *Rickard.D*

## v2.3.2 - 2013-03-25
- **FIX MINT-636** Remove restrictions on creating reservation with amount 0 - *Rickard.D*

## v2.3.1 - 2012-12-07
- **FIX MINT-91** Use "HTTP_X_FORWARDED_FOR" if it exists - *Christer.G*
- **FIX MINT-97** Update function uses internal validation in PHP - *Majid.G*
- **NEW MINT-28** Prepare the example files for the API reference guide - *Rickard.D*

## v2.3.0 - 2012-09-12
- **FIX MSDEV-3177** Returns error code 9114 when send empty value to SetActivateInfo - *David.K*
- **NEW MSDEV-3137** Support custom url in config - *Rickard.D*
- **NEW MSDEV-2932** Adding support for Austria - *Christer.G*
- **NEW MSDEV-2660** Add description in return_amount to PHP - *Majid.G*
- **NEW MSEDV-2396** Preparing for Austria - *Rickard.D*
- **NEW MSDEV-2600** Add partial activation to activate - *Rickard.D*
- **NEW MSDEV-2399** Add update call - *Rickard.D*
- **NEW MSDEV-2352** Add country / currency / language constants and remove validation - *Rickard.D*
- **FIX MSDEV-2516** Amount -1 / ignoring VAT - *David.K*
- **NEW MSDEV-2400** Add activate call - *Rickard.D*
- **NEW MSDEV-2481** Make it possible to send an empty pno string in activate_reservation - *Rickard.D*

## v2.2.2 - 2012-04-09
- **NEW MSDEV-2403** Remove ILT specifics - *Rickard.D*
- **NEW MSDEV-2400** Add activate call - *Rickard.D*
- **NEW MSDEV-2027** Clean example files - *Rickard.D*
- **NEW MSDEV-2321** If no gender is selected for DE/NL, send in NULL - *Rickard.D*
- **NEW MSDEV-807** Custom pclass storage - *Rickard.D*
- **NEW MSDEV-1766** Minimise address validation in php library - *Rickard.D*
- **NEW MSDEV-2136** PEAR-ify php-api - *Rickard.D*
- **FIX MSDEV-2006** Update activatePart example - *Rickard.D*
- **FIX MSDEV-2074** Update splitReservation example - *Rickard.D*
- **NEW MSDEV-1879** Update examples - *David.K*
- **NEW MSDEV-2065** Remove update_email - *Rickard.D*
- **NEW MSDEV-2130** Set client-ip to 0.0.0.0 in activateReservation - *Rickard.D*
- **NEW MSDEV-2164** Remove Calc APR from Fixed and Special pclasses - *Rickard.D*
- **FIX MSDEV-1728** fetchPClasses interrupted when no country is defined - *David.K*
- **FIX MSDEV-561** Validation of input is rejecting calls to KO when it shouldn't - *David.K*
- **NEW MSDEV-1718** Change Candice URL - *David.K*
- **NEW MSDEV-1683** Add ILT method - *David.K*


## v2.1.3 - 2011-10-24
- **FIX MSDEV-1490** KlarnaPClass setMinAmount converts to int, when it should be float - *Joakim.L*

## v2.1.2 - 2011-09-13
- **NEW MSDEV-1321** Support for 3 letter country code in getCountryForCode - *Joakim.L*
- **FIX MSDEV-1302** Add backticks to create database statement - *Joakim.L*
- **FIX MSDEV-1312** Using xmlrpcDebug or debug in e.g. JSON disregards value and sets it to true if the field exists - *Joakim.L*
- **FIX MSDEV-1305** Datatype is wrong for interest rate for MySQL storage - *Joakim.L*
- **NEW MSDEV-1004** Make localisation methods accessible from static - *David.K*

## v2.1.1 - 2011-09-06
- **NEW MSDEV-1188** Add language constant for English - *David.K*
- **FIX MSDEV-1142** Fix copy/paste related dirty code - *Joakim.L*

## v2.1.0 - 2011-08-25
- **NEW MSDEV-981** Update api for module release - *David.K*
- **NEW MSDEV-767** Implement the SHA-2 functionality - *Joakim.L*
- **NEW MSDEV-758** Add ILT method to the API - *Joakim.L*

## v2.0.0 - 2011-07-01
- Initial release of 2.0 API
