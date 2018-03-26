# Maintainer: semo <semox78@gmail.com>
pkgname=europlate.ttf
pkgver=1.0
pkgrel=1
pkgdesc="EuroPlate - TrueType Font for european number plates."
arch=('any')
url="http://www.autokennzeichen.info/kennzeichen-schriftart.htm"
license=('MIT')

source=("http://www.autokennzeichen.info/files/EuroPlate.ttf")

md5sums=('97a834894e9186114b53cb801f73c18b')


package() {
	cd "/usr/share/fonts/"
	make DESTDIR="EuroPlate/ttf/" install
}
