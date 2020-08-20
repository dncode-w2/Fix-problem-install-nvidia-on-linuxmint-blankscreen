# Fix-problem-install-nvidia-on-linuxmint-blankscreen

This tutorial how to fix problem blankscreen after install nvidia if you have problem install nvidia on linux mint v20,
i dont know if im use ubuntu install nvidia without problem, but for linux mint you need install nvidia-prime 

My laptop has spec nvidia geforce 610m/710m/810m if you have problem blankscreen on lightdm just install :

```bash
sudo apt install nvidia-prime && prime-select nvidia
```

And then reboot 

Or you can use script nvidia.sh just typing 

```bash
./nvidia.sh
```

Done i hope this help :)
