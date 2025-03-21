# Maintainer: Stefan Zipproth <s.zipproth@ditana.org>

pkgname=ditana-config-kitty
pkgver=1.09
pkgrel=1
pkgdesc="Ditana kitty configuration"
arch=(any)
url="https://ditana.org"
license=('GPL-3.0-only.txt')
conflicts=()
depends=(kitty imagemagick python-pygments libcanberra) # terminal kitty including optional dependencies
makedepends=()
source=(
    "file://${PWD}/kitty.conf"
    "file://${PWD}/ditana-logo-tiny.png"
)
sha256sums=('SKIP' 'SKIP')

package() {
    mkdir -p "$pkgdir/etc/skel/.shell.d"
    install -D -m644 $srcdir/kitty.conf $pkgdir/etc/skel/.config/kitty/kitty.conf
    install -D -m644 $srcdir/ditana-logo-tiny.png $pkgdir/usr/share/pixmaps/ditana-logo-tiny.png
}
