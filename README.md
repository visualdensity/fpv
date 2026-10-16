# FPV Notes and Configurations

Collection of various important notes and configurations related to FPV (First Person View) drone
flying. Personal reference use only. Use at your own risk!

# Important Details
 * Core temp must be BELOW  70C

# Setup Notes
This is for brand new setup. Some useful references:

 * https://www.youtube.com/watch?v=r8WMn2OeP4Q
 * https://oscarliang.com/setup-radiomaster-pocket/

## General Setup Steps:

 1. Setup radio transmitter - esp the buttons assingments
 2. Setup drone profile in Betaflight
 3. Bind the radio to the drone to the controller
 4. Bind the drone to the FPV goggles

 Additional notes below.

## RadioMaster Pocket

You must ensure you setup these basics up correctly!

 1. Setup a new **Model**
 2. **Setup** page - set the Internal RF to CSRF
 3. **Mixed** page - set throttle, yaw, pitch, and roll AND buttons like SB, SA, 
    SD, etc. for arming, flight modes, etc in Betaflight. Refer to the drone's manual for
    the buttons. RadioMaster Pocket reference manual `docs/RadioMaster-Pocket_A1.8.pdf`.
 4. **Special Functions** - Set SA or arm button to play track called `armed`

## Bind Drone with Controller

 1. Bind using the SYS -> ExpressLRS -> BIND
 2. If you get stuck in "Loading..." after choosing ExpressLRS, set Internal RF to CRSF in the
    **Setup** page and try again.
 3. Once bound, you can test by restarting the drone. It should say "Telemetry lost" and then
    "Telemetry restored" when you power on the controller.

## Bind FPV with Goggle

 1. Use the Auto Search function

## Betaflight Configuration

 1. Connect using the web Betaflight app
 2. BACKUP your presets first!
 3. **Modes** - check your mode settings
