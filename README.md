
# Example

## Requirements

### Install build essential

```bash
sudo apt install build-essential
```

### Install texlive-full

```bash
sudo apt-get install texlive-full
```

### Install PCRE

```bash
sudo apt-get install libpcre3 libpcre3-dev
```

### Install Chktex

Download latest tar.gz file from [chktex](http://nongnu.askapache.com/chktex/)

```bash
# Extract to /usr/local
sudo tar --directory=/usr/local -xvf chktex-X.X.X.tar.gz
# Delete archive
rm chktex-X.X.X.tar.gz
# Enter uncompressed directory
cd /usr/local/chktex-X.X.X
sudo ./configure --enable-pcre --enable-lacheck-replace --enable-debug-info
sudo make
sudo make install
sudo make install   # I had to make install once more.
sudo make check     # To test installation, should return OK!
```
