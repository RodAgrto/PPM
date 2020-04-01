## PPM for Strawberry Perl 64 bits 5.30.*

Alien-wxWidget Module is too slow to compile, so is added here.

First install PPM

```shell
cpan -i PPM
cpan -i DBI
cpan -i DBI::DBD
```

to install any of these package in the console use:

```shell
git clone https://github.com/RodAgrto/PPM.git
cd .\PPM\64bit-5.30
ppm install --location=.\ Alien-wxWidget
ppm install --location=.\ DBD::DB2
ppm install --location=.\ ORLite
ppm install --location=.\ Wx
```
 
