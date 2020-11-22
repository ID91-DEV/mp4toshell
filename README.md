# mp4toshell
Create mp4 payload to reverse shell on linux

This exploit work using vulnerability code execution on file manager,
when a user extract the payload using affected file manager, the *.deskop file will converted as *.mp4 and using an video thumbnail.
the file manager will make a reverse bind shell on background using netcat,most common
build utility on linux..

Affected Systems:

- Linux Mint 19.2/Cinnamon/Nemo
- Xubuntu 18.04/XFCE4/Thunar
- Fedora 30/MATE/Caja
- MX Linux/XFCE4/Thunar

