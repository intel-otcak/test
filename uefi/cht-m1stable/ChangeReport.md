## cht-m1stable: Weekly release 2016_WW20

### New patches

Please see the individual patch files for commit text.  

Touch:  
[input-touchscreen-silead-deactive-debug-logs-set-man.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/input-touchscreen-silead-deactive-debug-logs-set-man.patch)  
[Input-touch-silead-Solve-touch-reading-to-detect-10-.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/Input-touch-silead-Solve-touch-reading-to-detect-10-.patch)  
[input-touch-silead-Initialize-array-before-use-it.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/input-touch-silead-Initialize-array-before-use-it.patch)  

USB:  
[usb-xhci-W-A-for-internal-connected-and-self-powered.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/usb-xhci-W-A-for-internal-connected-and-self-powered.patch)  
[Revert-SSIC-Disable-D3-entry-on-every-SSIC-disconnec.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/Revert-SSIC-Disable-D3-entry-on-every-SSIC-disconnec.patch)  
[SSIC-Disable-D3-entry-on-every-SSIC-disconnect-V2.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/SSIC-Disable-D3-entry-on-every-SSIC-disconnect-V2.patch)  
[0001-Revert-SSIC-Disable-D3-entry-on-every-SSIC-disconnec.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/0001-Revert-SSIC-Disable-D3-entry-on-every-SSIC-disconnec.patch)  

Media:  
[UVC-Make-UVC_URB-a-module-paramater.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/UVC-Make-UVC_URB-a-module-paramater.patch)  

Camera:  
[Camera-ov8858-Update-BLC.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww20/uefi/cht-m1stable/patches/Camera-ov8858-Update-BLC.patch)  

### Obsoleted patch

[0001-Revert-drm-i915-patches.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/0001-Revert-drm-i915-patches.patch)  


## cht-m1stable: Weekly release 2016_WW19

### New patches

Please see the individual patch files for commit text.  

Magnetometer:  
[iio-magn-ak0911-optimizing-hrtimer-trigger-handler.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/iio-magn-ak0911-optimizing-hrtimer-trigger-handler.patch)  

Graphics:  
[SQUASHME-VPG-drm-i915-Fix-IPANIC-of-intel_get_crtc_s.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/SQUASHME-VPG-drm-i915-Fix-IPANIC-of-intel_get_crtc_s.patch)  
[FOR_UPSTREAM-VPG-drm-i915-CHT_CR-Fix-drrs-connector-.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/FOR_UPSTREAM-VPG-drm-i915-CHT_CR-Fix-drrs-connector-.patch)  

Extcon:  
[EM-3gpio_otg-Adding-thermal-cooling-device-in-3gpio-.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/EM-3gpio_otg-Adding-thermal-cooling-device-in-3gpio-.patch)  
[EM-extcon-dc-pwrsrc-Register-extcon-notifier-on-all-.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/EM-extcon-dc-pwrsrc-Register-extcon-notifier-on-all-.patch)  

Power:  
[EM-dc_xpwr_charger-Conditionally-register-vbus-contr.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/EM-dc_xpwr_charger-Conditionally-register-vbus-contr.patch)  

Camera:  
[Camera-ov8858-Fix-purple-stripes.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/Camera-ov8858-Fix-purple-stripes.patch)  
[ov8858-improve-W-A-to-sync-exposure-settings.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/ov8858-improve-W-A-to-sync-exposure-settings.patch)  

Touch:  
[input-silead-touch-add-touch-pressure-and-size-suppo.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/input-silead-touch-add-touch-pressure-and-size-suppo.patch)  


### Renamed patches

These patches have been renamed. There is no change in content.  

FROM:  
0001-Camera-ov8858-Improve-DFC.patch  
0002-Revert-drm-i915-patches.patch  

TO:  
[Camera-ov8858-Improve-DFC.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/Camera-ov8858-Improve-DFC.patch)  
[0001-Revert-drm-i915-patches.patch](https://github.com/intel-otcak/test/blob/cht-m1stable-2016_ww19/uefi/cht-m1stable/patches/0001-Revert-drm-i915-patches.patch)  


## cht-m1stable: Weekly release 2016_WW18

### New Patches:

Please see the individual patch files for commit text.  

Graphics:  
FOR_UPSTREAM-VPG-drm-i915-Avoid-enabling-dithering-f.patch  
FOR_UPSTREAM-VPG-drm-i915-Modify-Link-BW-warn-to-deb.patch  
FOR_UPSTREAM-VPG-drm-i915-Avoid-lane-optimization-fo.patch  
Revert-FOR_UPSTREAM-VPG-drm-i915-Avoid-optimizing-la.patch  
FOR_UPSTREAM-VPG-drm-i915-Fix-audio-checks-during-mo.patch  
FOR_UPSTREAM-VPG-drm-i915-Disable-MaxFifo-during-mod.patch  
SQUASHME-VPG-drm-i915-Fix-upfront-link-training-if-M.patch  
FOR_UPSTREAM-VPG-drm-i915-Optimize-CD-clock-change-f.patch  
FOR_UPSTREAM-VPG-drm-i915-Use-Max-CD-clock-for-DP-in.patch  
FOR_UPSTREAM-VPG-drm-i915-Always-perform-link-traini.patch  
FOR_UPSTREAM-VPG-drm-i915-Change-sleep-to-delays-for.patch  
FOR_UPSTREAM-VPG-drm-i915-use-correct-pipe-for-get-p.patch  
Revert-FOR_UPSTREAM-VPG-drm-i915-Calculate-multiplie.patch  
FOR_UPSTREAM-VPG-drm-i915-move-pm_qos_update_request.patch  
SQUASHME-VPG-drm-i915-fix-boundry-condition-for-allo.patch  
SQUASHME-VPG-drm-i915-Always-do-fake-detach-attach-f.patch  
SQUASHME-VPG-drm-i915-Avoid-clearing-test-request-ti.patch  
FOR_UPSTREAM-VPG-drm-i915-Perform-upfront-before-edi.patch  
0002-Revert-drm-i915-patches.patch  

Audio:  
Displayport-infoframe-support-in-Audio-driver.patch  
ASoC-rt5645-Increase-micbias-output-voltage.patch  

Camera:  
0001-Camera-ov8858-Improve-DFC.patch  

Touch:  
input-touch-Firmware-Memory-should-be-free-after-hav.patch  
input-silead-touch-reset-before-suspending.patch  

Debug:  
sched-dont-ouput-cpu-sched-info-by-default.patch  

### Renamed patches

These patches have been renamed. There is no change in content.  

FROM:  
0001-Camera-ov8858-Apply-OTP.patch  
0002-ov2680-CHT_MRD-WA-to-Fix-ov2680-FOV.patch  
0003-CHT-CR-MRD-Camera-Fix-ov2680-AE-oscillation-issue.patch  
0004-ov8858-W-A-to-sync-exposure-settings.patch  

TO:  
Camera-ov8858-Apply-OTP.patch  
ov2680-CHT_MRD-WA-to-Fix-ov2680-FOV.patch  
CHT-CR-MRD-Camera-Fix-ov2680-AE-oscillation-issue.patch  
ov8858-W-A-to-sync-exposure-settings.patch  


