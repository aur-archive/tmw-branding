# Maintainer: 謝致邦 <Yeking@Red54.com>

pkgname=tmw-branding
pkgver=20120727
pkgrel=1
pkgdesc="The Mana World - Branding Files"
arch=("any")
url="http://themanaworld.org"
license=('GPL2')
depends=("tmw")
source=(http://downloads.sourceforge.net/themanaworld/$pkgname-$pkgver.tar.gz)
md5sums=('5888db74faa6386456dfae902f93544c')

package() {
	mkdir -p $pkgdir/usr/share/{applications,pixmaps,tmw}
	cd $pkgdir/usr/share/tmw
	cp -r $srcdir/$pkgname-$pkgver/[!packaging,COPYING,README]* .
	cp *.desktop ../applications
	cp data/icons/*.png ../pixmaps
}
