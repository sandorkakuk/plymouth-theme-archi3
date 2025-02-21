# Maintainer: Onur BÜBER <onurbuber@engineer.com>
# Maintainer: Sándor Kakuk

pkgname=plymouth-theme-archi3
pkgver=1.0
pkgrel=1
pkgdesc="Plymouth Theme for Archi3 (Similar to Manjaro)"
arch=('any')
url="https://github.com/sandorkakuk/plymouth-theme-archi3"
license=('GPL')
depends=('plymouth')
install='plymouth-theme-archi3.install'
makedepends=('git')
source=("git+$url.git")
md5sums=('SKIP')

package() {
	cd $srcdir/$repo
	install -dm755 "$pkgdir/usr/share/plymouth/themes/archi3"
	cp -r ./plymouth-theme-archi3/archi3/* "$pkgdir/usr/share/plymouth/themes/archi3"
}
