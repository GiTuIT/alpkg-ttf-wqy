# Contributor: T-Wind
# Maintainer: T-Wind

pkgname=ttf-wqy-microhei
_pkgname=WQY_MicroHei
pkgver=0.2.NB
pkgrel=0
pkgdesc="WenQuanYi MicroHei"
url="http://wenq.org/wqy2/index.cgi?FontGuide"
arch="noarch"
license="Apache2.0 or GPLv3"
options="!check"
depends="fontconfig mkfontdir mkfontscale"
makedepends="font-util-dev"
source="https://nchc.dl.sourceforge.net/project/wqy/wqy-microhei/0.2.0-beta/wqy-microhei-0.2.0-beta.tar.gz"
builddir="$srcdir/$_pkgname-$pkgver"

package() {
	install -d "$pkgdir/usr/share/fonts/TTC"
	install -m644 fonts/*.ttc "$pkgdir/usr/share/fonts/TTC/"
}

sha512sums="c1e09c83f6427f637b3c93c7f89e427bde7fb22cedcfbb806fb036f13a553551f28d985516c7ab4c2602b4159502de36b52e6cc9b41c9b6d6e36778a6de74037
