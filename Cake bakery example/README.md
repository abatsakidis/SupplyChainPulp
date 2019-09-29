# Bakery Resource Scheduling Example #

## Description ##

Consultant for boutique cake bakery that sell 2 types of cakes

* 30 day month
* There is:
  * 1 oven
  * 2 bakers
  * 1 packaging packer - only works 22 days

* Different resource needs for the 2 types of cakes:

|       | Cake A  | Cake B  |
|-------| --------| --------|
|Oven   | 0.5 days| 1 day   |
|Bakers | 1 day   | 2.5 days|
|Packers| 1 day   | 2 days  |

|       | Cake A  | Cake B |
|-------| --------| -------|
|Profit | $20.00  | $40.00 |

Objective is to Maximize Pro
* Profit = 20 * A + 40 * B

Subject to:
* A >= 0
* B >= 0
* 0.5A + 1B <=30
* 1A + 2.5B <= 60
* 1A + 2B <= 22

