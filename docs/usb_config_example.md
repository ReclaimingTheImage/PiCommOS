# Encrypted USB Config File Example

This file shows how to set up a USB config file for PiCommOS.

## Steps

1. Decrypt the included `usb_config_template.cfg.gpg`:

    gpg -d usb_config_template.cfg.gpg > config.cfg

2. Edit `config.cfg` with your actual information:

    username = geostone  
    vpn_type = wireguard  
    wireguard_private_key = <your-private-key>  
    messaging_keypair = <your-post-quantum-key>  
    enable_dashboard = true  

3. Re-encrypt the config:

    gpg -c config.cfg

4. Save it to your USB stick as `usb_config.gpg`
