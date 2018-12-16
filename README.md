# Froxlor-Installer

A simple shell installer for froxlor

## Quick howto

Install requirements:

```
apt-get install apache2 mysql-server php php-mysql php-simplexml php-xml php-mbstring php-curl php-bcmath php-zip
```

If you want to retreive the latest froxlor development version using the ```--git``` parameter, you also need to install git:

```
apt-get install git
```

Acquire froxlor-install PHAR:

```
wget https://files.froxlor.org/froxlor-install.phar
```

Start froxlor-install:

```
php froxlor-install.phar
```

To see all possible parameters pass the ```--help``` parameter to froxlor-install.phar

```
php froxlor-install.phar --help
```
