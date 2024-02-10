pkgname="phosphorus"

pkgver="1.1"

pkgrel="1"

pkgdesc="Phosphorus - A Physics Engine for Movement Analysis"

arch=("x86_64")

depends=("python")

license=("GPL-3.0-or-later")

source=('phosphorus')

sha512sums=("SKIP")

package() {
    mkdir -p "${pkgdir}/usr/bin"
    cp "${srcdir}/phosphorus" "${pkgdir}/usr/bin/phosphorus"
    chmod +x "${pkgdir}/usr/bin/phosphorus"
}

