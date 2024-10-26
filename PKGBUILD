pkgname=mymind-electron-app
pkgver=1.0.0
pkgrel=1
pkgdesc="MyMind Electron App"
arch=('x86_64')
url="https://github.com/AndreaKinder/mymind-electron-app"
license=('MIT')
depends=('electron' 'nodejs')
source=("https://github.com/AndreaKinder/mymind-electron-app/archive/v1.0.0.tar.gz")
sha256sums=('YOUR_SHA256SUM')

build() {
  cd "$srcdir/mymind-electron-app-1.0.0"
  makepkg -s
}

package() {
  cd "$srcdir/mymind-electron-app-1.0.0/dist"
  cp -r mymind-electron-app-* "$pkgdir/usr"
}