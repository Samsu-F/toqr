
<h1 align="center">
  toqr
</h1>


## Installation

Install `qrcode` the way you normally install Python packages, e.g.
```
pip install qrcode
```
or
```
pacman -S python-qrcode
```

Then, install toqr where you want it. Assuming `~/.local/bin` is in your `PATH` variable, you can use

```
wget -O ~/.local/bin/toqr https://raw.githubusercontent.com/Samsu-F/toqr/main/toqr && chmod +x ~/.local/bin/toqr
```


## Usage

If any arguments are passed to toqr, it will encode them into the QR code:
```
toqr this is an example
```
The resulting QR code will contain the string `this is an example`.
If no arguments are given, toqr will read from stdin:
```
cat ~/.local/bin/toqr | toqr
```
