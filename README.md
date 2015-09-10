# dockerswitch

script to switch Docker client versions locally

```
$ sudo ./dockerswitch 1.7.1
```

or compose versions:

```
$ ./dockercomposeswitch 1.3.1
```

To see list of versions run with a dummy argument:

```
» ./dockercomposeswitch dummy
Wrong version: dummy
use as: ./dockercomposeswitch <VERSION>
VERSION can be one of: 1.4.0 1.3.3 1.3.2 1.3.1 1.3.0 1.2.0
```


## Install 
```
sudo cp ./dockerswitch /usr/local/bin/dockerswitch
sudo ln -s /usr/local/bin/dockerswitch /usr/local/bin/dockercomposeswitch
```

Works on reasonable Linux and OS X.
