## Exercise 4

Install PHP 7.4 on your local linux machine using the ppa:ondrej/php package repo.

To get started with this installation, I started by running the following command to update apt-get itself, which ensures that you have access to the latest versions of anything you want to install:

```
sudo apt-get update
```

Next, i installed software-properties-common, which adds management for additional software sources:
```
sudo apt -y install software-properties-common
```
The -y flag will automatically agree to the installation. Without that, you would receive a prompt in your terminal window for each installation.

Next, install the repository ppa:ondrej/php, which will give you all your versions of PHP:
```
sudo add-apt-repository ppa:ondrej/php
```

Finally, you update apt-get again so your package manager can see the newly listed packages:

```
sudo apt-get update
```
The next step is to install php.
```
sudo apt -y install php7.4
```

To check the version i used the command 
` php -v `


***
![Alt text](<php version.png>)



![Alt text](<2024-01-30 (9).png>)

