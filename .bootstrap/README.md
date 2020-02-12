# .cfg for DotFiles Maintenance

## Initialization
To start your dot files installation you need to:

1) Create bootstrap file.
vi bootstrap

2) Copy the files content

3) Make the file executable
sudo chmod +x bootstrap

4) Execute the file to clone this repository
sudo ~/bootstrap <Operational System> <Installation methos>
sudo ~/bootstrap Ubuntu Minimal


## Commands

- config add <file_name>
- config commit -m '<your commend>'
- config push origin master
