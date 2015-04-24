# Specification: Car Tracking Device #

In-car-tracking device should provide following functionalities:

  1. Car Status Information Push to Server (for example, every 10 min)
  1. Car Status Information on-demand by Poll-Request from Server

Car Status Information will consist of following data:
  1. GPS Location
  1. Vehicle mileage (start / stop mileage for accounting)
  1. Maintenance status (needs maintenance? etc.)
  1. Engine status (engine running?)
  1. Fuel status (percentage full?)
  1. Vehicle speed
  1. How many people inside? Infra red motion detector or smth
  1. Lock status (which doors open/locked/recent tracelogs)
  1. WebCam snapshots
  1. Theft notification
  1. Out of Fence / Route / Road notifications
  1. Over speeding / harsh driving notifications

Car Control Information
  1. The Server should be able to send commands like: lock/unlock door(s), start/stop engine

Nice-to-have Car Status Information will consist of following data:
  1. Vehicle direction, possible destination address?

[On-board diagnostics](http://en.wikipedia.org/wiki/On-board_diagnostics) can be used to integrate with the car.

[CAN vehicle bus](http://en.wikipedia.org/wiki/CAN_bus) standard can be used to communicate with the vehicle

Example building blocks
  * http://www.alibaba.com/product-detail/GPS-GPRS-Vehicle-Tracker-900E-GPS_1044763325.html?s=p
  * http://www.aliexpress.com/item/Advanced-gps-tracker-with-car-speaker-Central-lock-control-remote-open-close-car-doors-internal-memory/1689949409.html
  * http://www.alibaba.com/product-detail/New-tk103-GSM-GPS-tracker-dual_1838841039.html
  * http://www.engadget.com/2012/01/09/onstar-announces-closed-api-developers-welcome-to-apply/
  * http://www.mobile-devices.com/our-products/c4-obd2-dongle/
  * http://gpsgate.com/devices/gosafe_sniper_g797
  * http://www.obdsol.com/stn1170/
  * http://driverlocate.com/products.html
  * http://trakpro.com.au/fleet-tracking.html
  * http://bostonglobaltracking.com/product-details.php
  * http://www.titangps.ca/fleetreplay-products.htm
  * http://www.exactpointgps.com/commercialtracking.php
  * http://www.duratechusa.com/Products/hightech.html
  * http://opennetwork.verizonwireless.com/deviceModuleDetails.aspx?deviceId=719
  * http://www.navizot.com/en/products01_detail_01.php?id=53

See video:
  * <a href='http://www.youtube.com/watch?feature=player_embedded&v=DZStbfenfAI' target='_blank'><img src='http://img.youtube.com/vi/DZStbfenfAI/0.jpg' width='425' height=344 /></a>