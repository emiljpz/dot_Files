# dot_Files

![Screenshot_20220612_061803](https://user-images.githubusercontent.com/53439706/199979382-7f344aab-6c9e-4d92-97b1-53c12b065204.png)
![Screenshot_20220612_061904](https://user-images.githubusercontent.com/53439706/199979407-751c2503-5e90-4e3a-b1f7-cd05b690b10a.png)
![Screenshot_20220612_063025](https://user-images.githubusercontent.com/53439706/199979417-0f1ba606-2a32-4e98-bb23-c486fbbb3704.png)

Custom modules in polybar for OpenSuse, working in L14 Thinkpad
dependencies:
[module/brightness]
uses light dependency be aware
[module/battery]
use ; $ ls -1 /sys/class/power_supply/ to get battery name, line 178 polybar/config.ini
[module/temperature]
check this path : "hwmon-path = /sys/devices/platform/thinkpad_hwmon/hwmon/hwmon5/temp1_input" to get the temp data.

