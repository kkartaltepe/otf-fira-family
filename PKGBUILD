pkgname=otf-fira-family
pkgver=1.1
pkgrel=1
pkgdesc="Firefox Fira-sans fonts"
arch=(any)
depends=(fontconfig xorg-font-utils unzip)
source=("https://codeload.github.com/mozilla/Fira/zip/master")
install=$pkgname.install

package() {
    install -d "$pkgdir/usr/share/fonts/OTF"
    install -m644 "$srcdir/Fira-master/otf/"*.otf "$pkgdir/usr/share/fonts/OTF/"
    install -d "$pkgdir/usr/share/licenses/$pkgname"
    install -m644 "$srcdir/Fira-master/LICENSE" "$pkgdir/usr/share/licenses/$pkgname/"
}


md5sums=('8f146ff168c5d7d0d97c9f37ac9d109c')
