pkgname=2gis-perm
pkgver=67
pkgrel=1
pkgdesc="Map of Perm for 2GIS, July 2013"
arch=('i686' 'x86_64')
url="http://perm.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.5.1')
source=("http://download.2gis.ru/arhives/2GISData_Perm-67.orig.zip")
md5sums=('d4509179a9ab28eb6157853bd2b83b49')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Perm.dgdat" "${pkgdir}/opt/2gis/perm.dgdat" || return 1
  install -D -m 644 "${srcdir}/2gis/3.0/Plugins/DGisLan/Perm.dglf" "${pkgdir}/opt/2gis/Plugins/DGisLan/perm.dglf" || return 1
}
