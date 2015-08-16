# Maintainer: yetist <yetist@gmail.com>
pkgname=ios-sdk5
pkgver=5.0
pkgrel=4
pkgdesc="iPhone 5.0 sdk with ARC support"
arch=('i686' 'x86_64')
url="http://code.google.com/p/ios-toolchain-based-on-clang-for-linux"
license=('GPL')
optdepends=('iphonesdk-utils')
provides=('ios-sdk')
source=(http://ios-toolchain-based-on-clang-for-linux.googlecode.com/files/iPhoneOS${pkgver}.sdk.tar.xz)
md5sums=('3a52d151c27d2447ab308bb1d600fec9')

build() {
  echo "Building..."
}

package() {
  [ -d $pkgdir/usr/share ] || mkdir -p $pkgdir/usr/share
  mv $srcdir/iPhoneOS${pkgver}.sdk $pkgdir/usr/share
  #ln -sf crt1.o $pkgdir/usr/share/iPhoneOS5.0.sdk/usr/lib/crt1.3.1.o
}

# vim:set ts=2 sw=2 et:
