# Contributor: Ben Morgan <uv.sound@gmail.com>
pkgname=moped
pkgver=2.15
pkgrel=2
pkgdesc="Moped is an advanced and flexible tool to manipulate MPD playlists"
arch=('any') # I haven't tested x86_64
url="https://github.com/cassava/Moped"
license=('GPL')
groups=()
depends=("python>=3.1.2" zenity mpd)
makedepends=()
provides=()
conflicts=()
replaces=()
backup=()
install=
source=(https://github.com/downloads/cassava/Moped/$pkgname-$pkgver.tar.gz)
noextract=()

build() {
  cd $srcdir/$pkgname-$pkgver
  
  mv install.sh.example install.sh
  chmod +x install.sh
  ./install.sh $pkgdir
  
  #ln -s /usr/lib/moped/moped.py $pkgdir/usr/bin/moped
}
md5sums=('26276245b667fa66311b5186e30165b8')
