pkgname=sosrv
pkgver=1.0.0
pkgrel=0
pkgdesc="Simple Socat Service Manager for Retro Lab"
url="https://github.com/dagui0/sosrv"
arch="noarch"
license="MIT"
depends="socat"
makedepends=""
source="sosrv.init sosrv.conf"
options="!check"

package() {
    install -m 644 -D "$srcdir/sosrv.conf" "$pkgdir/etc/sosrv.conf"
    install -m 755 -D "$srcdir/sosrv.init" "$pkgdir/etc/init.d/sosrv"
}
sha512sums="
ac278be1b8a93d8a7a7c032c36c291eadb10b787d026dbd173522deb84986bfef520daa0accaab00cdab7540deabe909b08b683e7a176b07f7ff6a57086b7e6b  sosrv.init
1e0e7434e59b6aae59aaae33f4c0d5b70f8dbac601f6b3c4de939ff202d0d228ecf4ba8f53bc95bd9a3bed779053d7729967bb7d6c5530d0bf794bdb0502a1ee  sosrv.conf
"
