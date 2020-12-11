### Description
Here is a project which should enable a small business to easily install and run a webshop (based on wordpress).


                 +- Privat -------+     |  +- RPi -----------------+
                 | Store Network  |     |  | 192.168.100.2         |          +- smart devices ----+
(Internet)---WAN-+ DHCP server    +-LAN-+--+ DHCP Server + WLAN AP +-)))  (((-+ WLAN Client        |
                 | 192.168.1.0/24 |     |  | 192.168.100.0/24      |          | 192.168.100.x      |
                 +----------------+     |  +-----------------------+          +--------------------+


The following software is used:
- Raspberry PI OS 64bit
- docker
  - nginx
  - Mariadb
  - ...

### Use case
## First step
The customer enters the store and scans a QR code which automatically connects him to the dedicated WLAN network.
## second step
WIP
