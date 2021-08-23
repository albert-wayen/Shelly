# Shelly

**Automatic tool in `bash` to create `reverse shell` from `CLI`**

![](/001.png)

* Run

Tested Interfaces: `eth0` - `tun0` - `enp0s3`

```cmd
root@kali:~# shelly eth0 443 bash
```

![](/002.png)

* Download / Install

```cmd
root@kali:~# wget "https://raw.githubusercontent.com/d4t4s3c/Shelly/main/shelly.sh" -O /opt/shelly.sh
root@kali:~# chmod +x /opt/shelly.sh
```

* Add Alias

  * Bash --------> `root@kali:~# echo "alias shelly='/opt/shelly.sh'" >> /root/.bashrc`
  * Zsh ---------> `root@kali:~# echo "alias shelly='/opt/shelly.sh'" >> /root/.zshrc`
  * Powerlevel --> `root@kali:~# echo "alias shelly='/opt/shelly.sh'" >> /root/.p10k.zsh`

(Close terminal and reopen again)

* Available Languages

  * Bash
  * Netcat
  * PHP
  * Ncat
  * Python
  * Python3
  * Perl
  * Telnet
  * PowerShell
  * Awk
  * Socat
  * Ruby
  * Xterm
  * Gawk

---
