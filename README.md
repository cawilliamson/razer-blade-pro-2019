# razer-blade-pro-2019

- Add bootarg: button.lid_init_state=open (fix sleep-wake loop when sleeping laptop)
- Disable systemd-udev-settle service (avoids ~90sec boot wait - not 100% sure why - may be LVM2 related.)
- Add modprobe config: options ucvideo quirks=512 (not 100% sure if necessary to enable 720p - read it online - need to confirm.)
