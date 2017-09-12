# Maintainer: Michal Kimle <kimle.michal@gmail.com>
pkgname=perun-slave-process-k5login-root
pkgver=3.1.3
pkgrel=1
pkgdesc="Perun slave process k5login root"
arch=('any')
url="https://github.com/CESNET/perun"
license=('unknown')
depends=('bash' 'perun-slave-base')
source=("ftp://depot1.mc.cesnet.cz/pool/main/${pkgname}_${pkgver}_amd64.deb")
md5sums=('c16842822a1d8cc1990305003f426c26')

package() {
        tar xfp ${srcdir}/data.tar.gz -C ${pkgdir}/
        rm -r ${pkgdir}/usr/
        rm -r ${pkgdir}/etc/
        chmod -R 755 ${pkgdir}/opt/perun
}
