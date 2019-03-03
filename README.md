# Raihana-prototype
Refined version of a prototype License concept for a hackathon we did in 2018


Designed to show what a digital license could look like in the future to cut the cost of printing plastic cards

## To test the QR scanner on your dev machine, do 
This is to create a SSH key because you need https:// to enable the QR scanner
`openssl req -newkey rsa:2048 -new -nodes -keyout key.pem -out csr.pem`

`openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

https://stackoverflow.com/questions/12871565/how-to-create-pem-files-for-https-web-server
#note: this is only for dev, don't use this for production


This is the quick intro tutorial to the qr scanner library
https://gist.github.com/dvergeylen/a256deb3182b8a863238fcc0704aecb9
