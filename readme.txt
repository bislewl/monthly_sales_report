Name
====
Monthly Sales and Tax Summary mod for Zen Cart

Version / Date
===============
v 1.5.0 2014/10/12

Zen Cart versions supported
============================
Tested on ZenCart 1.5.0, 1.5.1, 1.3.9h

Author(s)
=========
Orginal OSC contributed by Fritz Clapp <fritz@sonnybarger.com>
Ported to ZenCart 1.3.8a SkipWater <skip@ccssinc.net>
Ported to ZenCart 1.50.RC1/2 SkipWater <skip@ccssinc.net>
Modifed to filter by state/zone by Pro-Webs.net

Support Thread
==============
http://www.zen-cart.com/forum/showthread.php?t=104544

Community Add-Ons
=================
http://www.zen-cart.com/index.php?main_page=product_contrib_info&cPath=40_41&products_id=1043

DESCRIPTION
============
This report displays a summary of monthly or daily totals:
	gross income (order totals)
	subtotals of all orders in the selected period
	nontaxed sales subtotals
	taxed sales subtotals
	tax collected
	shipping/handling charges
	low order fees (if present)
	gift vouchers (or other addl order total component, if present)

The data comes from the orders and orders_total tables.

Data is reported as of order purchase date.

If an order status is chosen, the report summarizes orders with that status.
If an state is chosen, the report summarizes orders with those states.

The capability to "drill down" on any month to report the daily summary for that month.  

Report rows are initially shown in newest to oldest, top to bottom, 
but this order may be inverted by clicking the "Invert" control button.

A popup display that lists the various types (and their
subtotals) comprising the tax values in the report rows.

Columns that summarize nontaxed and taxed order subtotals.
The taxed column summarizes subtotals for orders in which tax was charged.
The nontaxed column is the subtotal for the row less the taxed column value.

A popup help display window on how to use.


AFFECTED FILES
==============
No files overwritten. 

AFFECTS DB
==========
No DB affects

DISCLAIMER
==========
Installation of this contribution is done at your own risk.
Backup any and all applicable files before proceeding.
This script is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

INSTALL PROCESS
===============
Straight forward installation. 

1. Unzip to a temp directory and upload all files to your admin store directory.
   (The files are already arranged and there are *no* overwrites) 

TO RUN
===============
2. Go to Admin->Reports>Monthly Sales.

eof readme.txt