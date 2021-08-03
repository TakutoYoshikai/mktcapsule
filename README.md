# mktcapsule
mktcapsule is a tool for disabling to open specific file until given time.

### Requirements
* Rust
* Cargo

### Usage
**install**
```bash
git clone https://github.com/TakutoYoshikai/mktcapsule.git
cd mktcapsule
./install.sh
# if you want to register the bin directory to $PATH
echo "export PATH=\$PATH:/path/to/mktcapsule/bin" >> ~/.bashrc
```
**make time capsule**
```bash
mktcapsule /path/to/file "2021-01-02-12-13-00-+0900"
```

**open time capsule**
```bash
./file.tcapsule
```

### License
MIT License
