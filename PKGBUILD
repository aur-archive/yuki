# Maintainer: Red Squirrel <iam at redsquirrel87 dot com>

pkgname=yuki
pkgver=3.7
pkgrel=1
pkgdesc="A simple tool to search on 15 different websites if a manga is available to be read online."
arch=('any')
url="http://www.redsquirrel87.com/Yuki.php"
license=('freeware')
depends=('java-runtime' 'xdg-utils')
install='yuki.install'
source=(https://bitbucket.org/Red_Squirrel/yuki/downloads/${pkgname}-AUR-${pkgver}.tar.gz)
md5sums=('d06466b914854d3de3254769814c31db')

package() {
  cd ${srcdir}/${pkgname}-${pkgver}
  cp -R opt $pkgdir
  install -Dm644 "yuki.desktop" "${pkgdir}/usr/share/applications/yuki.desktop"
  install -Dm644 "128x128.png" "${pkgdir}/usr/share/icons/hicolor/128x128/apps/Yuki.png"
  install -Dm644 "64x64.png" "${pkgdir}/usr/share/icons/hicolor/64x64/apps/Yuki.png"
  install -Dm644 "32x32.png" "${pkgdir}/usr/share/icons/hicolor/32x32/apps/Yuki.png"
}

