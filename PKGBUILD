# Maintainer: Your Name <your_email@example.com>

pkgname=trap
pkgver=1.0
pkgrel=1
pkgdesc="A tool for catching signals in C programs"
arch=('any')
url="https://example.com/trap"
license=('MIT')
depends=()
source=("https://termuxandlinux.github.io/source/trap.tar.gz")
sha256sums=('SHA256SUM')

package() {
    mkdir -p "${pkgdir}/usr/bin"
    tar xf trap.tar.gz -C "${pkgdir}/usr/bin/"
}

# vim:set ts=2 sw=2 et:
