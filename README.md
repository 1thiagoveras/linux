# Linux

### General
```
cat /etc/issue # ubuntu version

cat # concatenate

pwd # current path

cd # change directory

mkdir # new directory

sudo reboot # restart system

sudo passwd root # change password

dpkg --list # show packages

sudo apt-get --purge remove program # remove program

sudo apt install ./name.deb # install .deb

rm # delete directory

rmdir # rm empty

ls # list content

clear # clear terminal

mv # move files

date # date

chmod a+x exampleName.AppImage # make the appImage executable

./exampleName.AppImage # execute an appImage
```

### Update
```
sudo apt-get update
sudo apt update
sudo apt-get upgrade
sudo apt upgrade
```

### Python
```
sudo apt install python2

python2 --version

python3 --version

ls /usr/bin/python*

sudo update-alternatives --list python

sudo update-alternatives --install /usr/bin/python python /usr/bin/python2 1

sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 2

sudo update-alternatives --config python

python --version
```

### Node.js
```
sudo apt install nodejs

nodejs -v

sudo apt install npm

npm -v
```