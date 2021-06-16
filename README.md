# python-web-flask-mvc-triple-des-encrypted-scrypt-encode

## Description
This is a simple login with
encryption and encoding. A custom error
page will be shown for unauthorized
access.

Passwords are triple des encrypted and encoded scrypt.

## Tech stack
- python
  - flask
  - pyscrypt
  - des

## Docker stack
- python:latest

## To run
`sudo ./install.sh -u`
- Available http://localhost
- Login with id: user and password: pass
- Login with id: admin and password: pass
- Login with id: super and password: pass

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
