# Maintainer: Jeremy Sands cto@jeremysands.com

pkgname=opera-adblock
pkgver=2011.02.23
pkgrel=1
pkgdesc="Fanboy's AdBlock Filterset for Opera"
arch=('i686' 'x86_64')
url="http://www.fanboy.co.nz/adblock/opera/"
license=('cc-by-3.0')
depends=('opera')
source=(urlfilter.ini)
md5sums=('840be7df43dbbab766c7ae2024433def')

build() {
  cd "$startdir"/src
  mkdir -p "$startdir"/pkg/usr/share/"$pkgname"/
  install -m644 urlfilter.ini "$startdir"/pkg/usr/share/"$pkgname"/urlfilter.ini
}
install=${pkgname}.install

# vim:set ts=2 sw=2 et:
