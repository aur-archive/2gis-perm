pkgname=2gis-perm
pkgver=79
pkgrel=1
pkgdesc="Map of Perm for 2GIS, July 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/perm/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Perm-79.orig.zip")
md5sums=('9c990d52a1025a8c3e58254ab384988d')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Perm.dgdat" "${pkgdir}/opt/2gis/2gis-perm.dgdat" || return 1
  
}
