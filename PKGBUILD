pkgname=elgeneral-icon-theme
pkgver=1.4a5
pkgrel=1
pkgdesc='Because El Capitan is eating Apples. Is a OS X inspired theme upon the base of Breeze.'
arch=('x86_64')
url='http://kde-look.org/content/show.php/El+General?content=173973'
license=('LGPL')
makedepends=()
optdepends=()
source=('https://github.com/fabianalexisinostroza/El-General/archive/master.zip')
md5sums=('SKIP')



package() {
  install -d -m 755 "$pkgdir"/usr/share/icons/ElGeneralDark
  cd $srcdir/El-General-master/ElGeneralDark/
  cp -r . "$pkgdir"/usr/share/icons/ElGeneralDark/


  install -d -m 755 "$pkgdir"/usr/share/icons/ElGeneral
  cd $srcdir/El-General-master/ElGeneral/
  cp -r . "$pkgdir"/usr/share/icons/ElGeneral/
}
