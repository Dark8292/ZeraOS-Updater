# Maintainer: Dark <https://github.com/Dark8292>

pkgname=zeraos-updater
pkgver=1.0.1
pkgrel=1
pkgdesc="ZeraOS Updater"
arch=('x86_64')
url="https://github.com/Dark8292"
license=('GPL-3.0')
depends=('python'
        'python-pyqt6')

package() {
    install -dm755 "$pkgdir/usr/bin"

    install -m755 \
        "$srcdir/usr/bin/zeraos-updater" \
        "$pkgdir/usr/bin/zeraos-updater"

    install -Dm644 \
       "$srcdir/usr/share/icons/zeraos-updater.svg" \
       "$pkgdir/usr/share/icons/zeraos-updater.svg"


    install -dm755 "$pkgdir/usr/share/applications"

    install -m755 \
        "$srcdir/usr/share/applications/ZeraOS-Updater.desktop" \
        "$pkgdir/usr/share/applications/ZeraOS-Updater.desktop"
}
