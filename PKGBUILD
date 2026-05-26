pkgname=swaypaper
pkgver=1.3.4
pkgrel=2
pkgdesc="Simple TUI wallpaper selector for swaybg"
arch=('any')
url="https://github.com/Kibblix/swaypaper"
license=('MIT')

depends=('bash' 'swaybg')

source=("swaypaper")

sha256sums=('SKIP')

package() {
    install -Dm755 swaypaper "$pkgdir/usr/bin/swaypaper"
}
