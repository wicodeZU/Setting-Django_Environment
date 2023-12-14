# Step by step instructions on how to setup Django environment

The instructions are based on the `shell` files in this repository.
Each sub-section is based on one file from the shell files and some additional info if needed.

This is for making it easy to copy the instructions provided in the shell files.

## Create a directory

```bash
mkdir Foldername
```

## Change directory

```bash
cd Foldername
```

## Install Virtualenvironemt

```bash
pip install virtualenv
```
If you are in a externally managed environment like in Arch Linux then you can try

```bash
pacman -S python-virtualenv
```
If it fails you can try

```bash
pip install virtualenv --break-system-packages
```

If it fails again, then you are using Linux, we trust in you.

## Create virtualenv

```bash
python -m virtualenv name
```

## Activate virtualenv

```bash
name/scripts/activate
```

If the script is not there, then look it maybe in `bin` or somewhere, you know what you are doing right?

## Install Django

```bash
pip install django
```

## Start Django Project

```bash
django-admin startproject (Projectname)
```

## Change Directory

```bash
cd (Projectname)
```

## Run Server

```bash
python manage.py runserver
```

## Aftermath

Edit your files and enjoy the development process. Good Luck!
