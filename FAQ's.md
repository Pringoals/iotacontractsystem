
# Frequently asked questions

To get started quickly it is reccomended to read the FAQ's prior to installing the software.

## How do I create a seed in Linux?
To create a unique IOTA seed the prefered method is using the following script, However online seed generators can be used but are not reccomended.

Open Terminal and type or paste the following then press enter:

```
cat /dev/urandom |tr -dc A-Z9|head -c${1:-81}
```
Code from: [iota Guide](https://iota.guide/seed/how-to-generate-iota-wallet-seed/)

## How do I generate an Address?

To get an address first login via the seed and open the account tab. From here you will see a unique address. 

## What Document formats are currently supported?

At the moment the following document types are:
- .XML
- .PDF
- .DOC
- .JPG

