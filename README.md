# mktcapsule
mktcapsule is a tool for disabling to open specific file until given time.

### Requirements
* Linux
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

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

### License
MIT License
