# FeedwireKroger
Repository for useful information about Feedwire Kroger


# LOTTERY CHEATSHEET

### SALES

| ROW                                      | CODE         | OPERATION | ACTION | DESCRIPTION                               |
| ---------------------------------------- | ------------ | --------- | ------ | ----------------------------------------- |
| Vending Online Sales                     | 6585         | X         | X      | Vending - Total Online                    |
| Office Online Sales                      | 6585         | PLUS      | X      | Office - Online - Gross Sales             |
| Fuel Online Sales (DO NOT RING)          | X            | PLUS      | X      | Fuel - Online - Gross Sales               |
| Total Online Sales (line 804)            | X            | EQUALS    | X      | SUM                                       |
| Vending Online Sales CASHLESS (line 308) | 40201        | X         | X      | Cashless - Online - Cashless Online Sales |
| Vending Instant Cashed                   | 6588         | PLUS         | X      | Vending - Instant Tick Cashed             |
| Office Instant Cashed                    | 6588         | PLUS      | X      | Office - Instant - Cashes                 |
| Fuel Instant Cashed (DO NOT RING)        | X            | X         |        | Fuel - Instant - Cashes                   |
| Total Instant Cashed (line 937)          | X            | EQUALS    | X      | SUM                                       |
| Vending Online Cashed                    | 6586         | X         | X      | Vending - Online Tick Cashed              |
| Office Online Cashed                     | 6586         | PLUS      | X      | Office - Online - Cashes                  |
| Fuel Online Cashed  (DO NOT RING)        | X            | PLUS      | X      | Fuel - Online - Cashes                    |
| Online Winners Cashed                    | X (line 936) | EQUALS         | X | SUM                                       |
| MY Lotto Adjustments (line 925)          | X            | X         | X      | Adjustments                               |

### VENDING INSTANT INVENTORY

| ROW                                              | CODE  | OPERATION | ACTION | DESCRIPTION                                 |
| ------------------------------------------------ | ----- | --------- | ------ | ------------------------------------------- |
| Beginning Inventory                              | X     | X         | X      | Previous Ending Inventory                   |
| Activations (line 807)                           | X     | PLUS      | X      | Today's Activations                         |
| Total Instant Sold                               | 6587  | MINUS     | Loan to 31      |  Vending - Total Instant        |
| Subtotal (Should match instant ending inventory) | X     | EQUALS    | X      | SUM                                         |
| Torn Tickets (Activated Tickets in Safe)         | X     | PLUS      | X      | Activated Tickets in Safe                   |
| Credit Issued for Torn Tickets (line 938)        | X     | MINUS     | X      | Credit Issued for Torn Tickets              |
| Total Ending Inventory                           | X     | EQUALS    | X      | SUM                                         |
| Total Instant Sold Cashless                      | 40200 | X         | X      | Cashless - Instant - Cashless Instant Sales |

### FUEL INSTANT INVENTORY

| ROW                                       | CODE | OPERATION | ACTION | DESCRIPTION                        |
| ----------------------------------------- | ---- | --------- | ------ | ---------------------------------- |
| Beginning Inventory                       | X    | X         | X      | Previous Ending Inventory          |
| Activations (line 807)                    | X    | PLUS      | X      | Activations                        |
| Total Instant Sold (DO NOT RING)          | X    | MINUS     |        | Loan to 100 - Number Fuel Told You |
| Subtotal                                  | X    | EQUALS    | X      | Subtotal                           |
| Torn Tickets (Activated Tickets in Safe)  | X    | PLUS      | X      | Torn Tickets                       |
| Credit Issued for Torn Tickets (line 938) | X    | MINUS     | X      | Credit Issued                      |
| Total Ending Inventory                    | X    | EQUALS    | X      | SUM                                |

### SERVICE DESK INSTANT INVENTORY

| ROW                                                                                               | CODE | OPERATION | ACTION                       | DESCRIPTION               |
| ------------------------------------------------------------------------------------------------- | ---- | --------- | ---------------------------- | ------------------------- |
| Beginning Inventory                                                                               | X    | X         | X                            | Previous Ending Inventory |
| Activations (line 807)                                                                            | X    | PLUS      | X                            | Activations               |
| Total Instant Sold (DO NOT RING)                                                  | X    | MINUS     | Loan to 31 |  Office Instant Lotto Tablet - Shift total                         |
| Subtotal                                                                                          | X    | EQUALS    | X                            | Subtotal                  |
| Torn Tickets (Activated Tickets in Safe)                                                          | X    | PLUS      | X                            | Torn Tickets              |
| Credit Issued for Torn Tickets (line 938)                                                         | X    | MINUS     | X                            | Credit Issued             |
| Total Ending Inventory                                                                            | X    | EQUALS    | X                            | SUM                       |
| Total Instant Sold                                                | X    | EQUALS         | X                            | (VENDING + FUEL + SERVICE DESK)                       |
| Total Ending Inventory for Safe Management  | X    | EQUALS         | X                            |   (VENDING + FUEL + SERVICE DESK + TORN TICKETS IN SAFE)                        |



# CLOSING CHECKLIST

### Vending Lotto

- Grab green and orange keys from safe
- Open outer shell of vending using orange key (while pushing up the latch on the grip)
- Sign on using credentials
- End/Close Shift
- Remove money from box using green key when asked
- Save one of the shift close receipts. This will be your 'Vending' receipt

### Online Lotto Tablet

- Utilities -> Store Manager Sign On -> Financial Reports
- Repeat following steps for terminal 1 (Office),2 (Cashless), and 11 (Fuel)
- Sales Summary -> By Terminal
- Hit 'print' in bottom left below receipt preview

### Instant Lotto Tablet:
- Shift -> Record 'Shift Total' to 'Service Desk Instant Inventory - Total Instant Sold'
- Shift -> End Shift

### Money Order Tablet (Western Union):
- Money Order Services -> End Shift
- Insert paper folded in half
- Don't bother printing duplicate

### Sports Bettings Tablet:
- IDK

### Miscellaneous:
- Take bill pays, western unions, and refund receipts from drawer and archive them.

### Close All Tills:
- Registers, SCOs, floral, bar, etc.

### Coupons (Saturday only)
- Pull coupons from desk drawer (unlocked), SCO registers (unlocked), belted SCOs (thin silver key), registers (small short gold key).
- Place all coupons in bag, date it, and place in shipment box

### Lockup:
- Lock pharmacy side completely
- Lock one-way entrance on main side, turn off power of other doors
- Lock safe once all till bags have been collected
- Place safe key back into key locker and close key locker (must be on the correct combination to let you lock it)