# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>

pkgname=2gis-perm
pkgver=41
pkgrel=1
pkgdesc="Map of Perm for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Perm-${pkgver}.orig.zip")
md5sums=('f8dff33156f10214b25cf40ad8917495')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Perm.dgdat "${startdir}/pkg/opt/2gis/perm.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Perm.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Perm.dglf" || return 1

}
