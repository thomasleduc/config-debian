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

You can add ```-k``` option to change the keymap
```bash
./config -k
```

You can add ```-n``` option to install npm
```bash
./config -n
```
*Please note that also install node*
*If you want to install bower, just add the ```-b``` option, no need to add the ```-n```*

You can add ```-b``` option to install bower
```bash
./config -b
```
*Please note that also install node and npm*
