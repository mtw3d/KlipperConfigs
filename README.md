# KlipperConfigs
Klipper configurations for MTW printers.

To load the config files onto your printer, SSH to your printer and execute the following two commands:

```
git clone https://github.com/mtw3d/mtw_klipper_config
bash ~/klipper_config/mtw_klipper_config/setup.klipper
```

After installing, you will need to edit the file ~/klipper_configs/printer.cfg to point to the correct sample config file. In addition, you can set any necessary settings in this file. 

To update your configs to the latest version, execute:
```
~/update_mtw_configs
```

Updating your config automatically backs up your current config to the directory `~/config_backups`. It keeps the last ten backups, and automatically deletes any older than that.
