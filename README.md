# .cfg for DotFiles Maintenance

## Initialization
To start your dot files installation you need to:

1) Create bootstrap file.
vi bootstrap_dotfiles

2) Copy the files content

3) Make the file executable
sudo chmod +x bootstrap_dotfiles

4) Execute the file to clone this repository
./bootstrap_dotfiles


## Commands

config add <file_name>
config commit -m '<your commend>'
config push origin master
