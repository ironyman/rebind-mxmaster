# Maintainer: Me
pkgname=rebind-mxmaster
pkgver=1
pkgrel=1
epoch=1
pkgdesc="Rebind MX Master keys"

url=""
arch=('i686' 'x86_64')
license=('GPL2')
depends=('libdbus' 'glib2' 'perl' 'coreutils')
conflicts=()
provides=()
backup=()
source=(mxmaster.rules
        rebind-mxmaster)
md5sums=('SKIP'
         'SKIP')

pkgver() {
  echo 1
}

prepare() {
  return 0
}

build() {
  return 0
}
  
package() {
  install -Dm644 $startdir/mxmaster.rules "${pkgdir}/etc/udev/rules.d/99-mxmaster.rules"
  install -Dm755 $startdir/rebind-mxmaster "${pkgdir}/usr/bin/rebind-mxmaster"
}
