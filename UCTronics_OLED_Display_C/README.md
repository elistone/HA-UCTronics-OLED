# UCTRONICS OLED Display

### NB This is my first HomeAssistant Add-on so use at own risk

Enables the OLED display for UCTRONICS Pi 4 Rack Module.

This addon will utilise code from Adam Outler, [GitHub adamoutler](https://github.com/adamoutler/HassOSConfigurator/tree/main/Pi4EnableI2C) to first enable the I2C interface, you will need to reboot twice as per his documentation. After I2C is enabled then the display will finally show.

Special thanks to [DC Walter](https://github.com/dcwalter) for fixing the code to support C unit for temperature, and also fixing CPU usage, and adding the HA Logo.

## Install Guide

### Phase 1: Setup I2C Interface
1. Install the addon from the Home Assistant Add-on Store
2. Disable "Protection mode" in the addon configuration
3. Start the addon to initialize the I2C interface configuration
4. Restart your Home Assistant system completely
5. Wait for the system to fully boot, then verify the addon has started automatically (if not, start it manually)
6. Restart your Home Assistant system again (this second reboot is required to complete I2C initialization)
7. After the second reboot completes, stop the addon

### Phase 2: Normal Operation
1. Re-enable "Protection mode" in the addon configuration for improved security
2. Start the addon
3. Check the "Logs" tab for any error messages
4. If no errors appear, your UCTRONICS OLED display should now be functioning
