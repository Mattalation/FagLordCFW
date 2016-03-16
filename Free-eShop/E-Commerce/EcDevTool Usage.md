Programming Manual: ECDK
The content of this document is highly confidential and should be handled accordingly.

The content of this document cannot be duplicated, copied, reprinted, transferred, distributed, or loaned in whole or in part without the prior approval of Nintendo.

This document contains confidential and proprietary information of Nintendo and is also protected under the copyright laws of the United States and foreign countries. No part of this document may be released, distributed, transmitted or reproduced in any form or by any electronic or mechanical means, including information storage and retrieval systems, without permission in writing from Nintendo.

Version 1.3 © 2016 Nintendo. All rights reserved.
All company and product names in this document are the trademarks or registered trademarks of their respective companies.
CTR-03-0112-002-A

6.1. Development Tool

The ECDK development tool provides the features necessary for debugging.
The development tool currently has the following features.
Add funds to the account balance.
Delete rights.
Delete the eShop account.
Manage downloads.
Downgrade data titles.
Change settings.
The development tool is available in the following directory.
There is also an installation image in this directory.

Note: The development tool requires network configuration to be completed before it starts.
Some of the development tool features are not available if the current account is not a network account.

# Usage 

Code 4-6. Account Balance Management
In the development environment, you can add funds to the account balance using the following credit card information.
Card type	Credit card number - VISA	4444 4444 4444 4448	
Period of validity	- 12 / 2030
Security code	- 123
Address (U.S. only) - 12345
Note:
To redisplay the catalog after managing the account balance, synchronize the license information. (Only for applications that support item redemption.)
Allows items to be redeemed when a download code is entered during the account balance management process.

# Usage (Dev Units)
3.3. Network Settings
Configure DNS to connect to the development server.
Specify 205.166.76.187 for the DNS address.
Note:
The DNS address may change in the future.
If you cannot connect to the development server, refer to Nintendo's support page and update to the latest DNS address.

