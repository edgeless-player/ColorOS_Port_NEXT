<div align="center">


# ColorOS/OxygenOS Porting Project

[简体中文](/README.md)&nbsp;&nbsp;|&nbsp;&nbsp;English

</div>

## Intro
- ColorOS/OxygenOS Porting Project

## Supported Devices

- OnePlus 8T

## Tested devices and portroms
- Test Base ROM:  
OnePlus 8T (ColorOS_14.0.0.602), 
- Test Port ROM: 
OnePlus 15 (ColorOS_16.0.7.206), 
OnePlus ACE6T (ColorOS_16.0.5.702)

## Working
- Face unlock
- Fringerprint
- Camera
- Automatic Brightness
- NFC
- etc


## BUG

- AOD is too dim
- Voice trigger is not working
- WiredEarphone without DAC is not working

## How to use
- On ubuntu
```shell
    sudo apt update
    sudo apt upgrade
    sudo apt install git -y
    # Clone project
    git clone https://github.com/edgeless-player/ColorOS_Port_NEXT.git
    cd ColorOS_Port_NEXT
    # Install dependencies
    sudo ./setup.sh
    # Start porting
    sudo ./port.sh <baserom> <portrom>
```
- baserom and portrom can be a direct download link. you can get the ota download link  from third-party websites.

## Credits
> In this project, some or all of the content is derived from the following open-source projects. Special thanks to the developers of these projects.

- [「BypassSignCheck」by Weverses](https://github.com/Weverses/BypassSignCheck)
- [「contextpatch」 by ColdWindScholar](https://github.com/ColdWindScholar/TIK)
- [「fspatch」by affggh](https://github.com/affggh/fspatch)
- [「gettype」by affggh](https://github.com/affggh/gettype)
- [「lpunpack」by unix3dgforce](https://github.com/unix3dgforce/lpunpack)
- [「miui_port」by ljc-fight](https://github.com/ljc-fight/miui_port)
- etc

## Notes：
People with the ability are welcome to send issues to help our project, which is open source permanently.

Here, I would like to express my highest gratitude to all those who have worked hard for this project, as well as to all the contributors.

Since the author of this branch project is a student, his English is poor, and the Readme is translated, if there is any mistake, please send an issue to remind me, and I will modify it immediately.
