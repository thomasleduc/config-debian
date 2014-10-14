config-debian
=============

A basic configuration for turnkey VM

# Install

**You have to be root**

```bash
wget https://raw.githubusercontent.com/thomasleduc/config-debian/master/config
chmod +x config
./config
```

### Options
```bash
./config [-knb]
```

```-k``` option to change the keymap
*This allow you to choose your keymap*


```-n``` option to install npm
*Please note that also install node*

*If you want to install bower, just add the ```-b``` option, no need to add the ```-n```*


```-b``` option to install bower
*Please note that also install node and npm*
