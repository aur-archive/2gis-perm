# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-perm
pkgver=53
pkgrel=1
pkgdesc="Map of Perm for 2GIS, May 2012"
arch=('i686' 'x86_64')
url="http://perm.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Perm-${pkgver}.orig.zip")
md5sums=('99cd3f457a89530027e182b1316faedd')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Perm.dgdat "${startdir}/pkg/opt/2gis/perm.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Perm.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Perm.dglf" || return 1
     
}

