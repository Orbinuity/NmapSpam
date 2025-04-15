# NmapSpam

[<img alt="Status" src="https://raw.githubusercontent.com/Orbinuity/.github/main/status/stable.png" width="100" height="25">](https://orbinuity.github.io/Orbinuity/statusIcons.html)

A bash script that spams nmap commands

## License

Before copying any part of this project, please read the [LICENSE](./LICENSE) file to understand the terms and conditions.

## How to use

### Usage:
```bash
./ns <option> <times> <ip>
```


### Options:

-d a dot for evry time it nmaps.

-n the number of the current nmap.

-e nothing.

### Times:

the times it runs

### Example:
```bash
./ns -e 1000 "10.10.1.1"
```

### Warning

Forthis you need to have the ns file in you working directory.

Follow the install instructions to make it work even if you dont have that file.

## Install

you can move the file to /usr/bin/

```bash
sudo mv ns /usr/bin/
```

now you can use it like this:
```bash
ns -e 1000 "10.10.1.1"
```