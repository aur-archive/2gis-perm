# Contributor: stanislaw <i@archuser.pp.ru>
# Contributor: wido <widomaker2k7@gmail.com>

pkgname=2gis-perm
pkgver=38
pkgrel=1
pkgdesc="Map of Perm for 2GIS"
arch=('any')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Perm-${pkgver}.orig.zip")
md5sums=('b3800aa9eaa7af538e83188ff6a3afdb')

build() {

  cd ${startdir}

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Perm.dgdat "${startdir}/pkg/opt/2gis/perm.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Perm.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Perm.dglf" || return 1

}
