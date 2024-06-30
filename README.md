# Lid
GUI for setting up the laptop lid closing event  
  
![](https://github.com/AKotov-dev/Lid/blob/main/ScreenShot2.png)  
  
Many times during the process of installing Linux on laptops, I came across the fact that in some DE (for example, in the latest versions of `XFCE`) it is impossible to configure the laptop to turn off after closing the lid. To automate the setup process, `Lid` was created. It allows you to change settings that relate to the "lid close" event in the configuration files `/etc/UPower/UPower.conf` (if the `upower` package is present) and `/etc/systemd/logind.conf`.

+ Optimal (OFF) - setting power off when closing the lid
+ Reset - Cancel and return settings to default
+ Apply - Apply settings set manually

`Lid` is made in the form of two archives, the choice of which depends on the system architecture: unpack and run`StartAsRoot` (so as not to bother going to the console and running with root privileges). The interface is intuitive and does not require additional explanation.

**Note:** Before use `Lid`, make sure your DE may already have the necessary settings.
