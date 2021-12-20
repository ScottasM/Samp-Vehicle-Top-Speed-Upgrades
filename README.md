# Samp-Vehicle-Top-Speed-Upgrades

This simple filterscript allows the modification of vehicle max speed. Call SetVehicleMaxSpeed(vehicleid, percentage (integrer, must be more than 0)) to set how much you want to increase the max speed in %. If you want to get rid of the upgrade, just set it to 0

This is the best way i found to do this, but keep in mind that it keeps increasing the vehicle velocity even though the game is limiting it, so making the top speed double what it already is might cause the car to be uncontrollable at high speeds - i would recommend to not exceed 50%, especially on cars with high top speeds like infernus.

<h3 align="left">Installation:</h3>
Add VehicleMaxSpeed.pwn to your filterscripts folder and VehicleMaxSpeed to your server.cfg line
Make sure you have sscanf plugin, zcmd (or any command library that supports CMD:), y_iterate and y_vehicledata (Huge thanks to YSI, you can find what you need in here https://github.com/pawn-lang/YSI-Includes#libraries). 
<p align="left">

<h3 align="left">Usage:</h3>
Just use SetVehicleMaxSpeed(vehicleid,percentage) to set the new max speed. The percentage is added to current max speed, so using 0 will remove the upgrade.
<p align="left">

Fell free to edit this filterscript in any way you want and do pull requests to update it.
