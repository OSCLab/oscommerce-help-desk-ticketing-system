# Help Desk Ticketing System - osCommerce add-on

Customer service is the most important part of each online store. You have to receive message from customers, answer them and solve their problem. It can be confusing and chaotic. As a solution coming our add-on. Perfect customer support ticket system.

* Administrator workflow organized to minimize time waste 
* Customer-friendly: easy to create, track, and manage tickets 
* Built-in content includes a number of automation rules and email templates 
* No third party storage used for saving and processing tickets 
* Knowledge Base - find answers and help fast

Compatible With:

* Community Edition version: All 
* Official version: 2.3++ (catalog design is not supported)
* Minimum PHP Version: 7.0

## Installation

1. Backup all files and database!

2. Unzip the archive and upload the files on server.

3. Manually make changes.

In admin/includes/application_top.php and includes/application_top.php

At the end of the file add

```php
  require DIR_FS_CATALOG . 'includes/functions/help_desk.php'; // help desk ticketing system add-on
```
