# CLI File Enkryptor

## How to install
Clone the folder and symlink
```shell
git clone https://github.com/raph6/cli-file-enkryptor.git
cd cli-file-enkryptor
composer install
chmod +x enkryptor
sudo ln -s "$(pwd)/enkryptor" /usr/local/bin/enkryptor
```

## Usage
```
Welcome to CLI Enkryptor by Raphaël BLEUZET

Usage : enkryptor COMMAND INPUT-FILE PASSWORD

Commands:
  encrypt    Encrypt your file
  decrypt    Decrypt your file
  help       This 


https://github.com/raph6/cli-file-enkryptor
```

## Exemple of use
```shell
# encryption
enkryptor encrypt my-file.txt mypassword
# my-file.txt.enc is created

# decryption
enkryptor decrypt my-file.txt.enc mypassword
# my-file.txt is created
```

## Special thanks
[Ismai Aydogmus](https://github.com/isma91) for refactoring the code and improving the features
