# apinet
A simple command line tool to get your basic network information like public IP address, remote host.

## Install
The installation is very simple. Run the following commands.

```bash
$ git clone https://github.com/noraworld/apinet.git
$ cd apinet
$ chmod 755 apinet
$ sudo cp apinet /usr/local/bin
```

Not work? Try this:

```bash
$ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bashrc
```

I assume you are using bash shell. Change the filename to exact one if you are not using bash.

## Usage
Get your IP address

```bash
$ apinet ip
```

Get your remote host

```
$ apinet host
```
Commands will be added in the future...

## License
All codes of this repository are available under the MIT license. See the [LICENSE](https://github.com/noraworld/apinet/blob/master/LICENSE) for more information.
