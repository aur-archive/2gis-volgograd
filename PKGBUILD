# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-volgograd
pkgver=28
pkgrel=1
pkgdesc="Map of Volgograd for 2GIS, January 2013"
arch=('i686' 'x86_64')
url="http://volgograd.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Volgograd-28.orig.zip")
md5sums=('4fea0cd82540bc6eb6fea7ed9322b689')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Volgograd.dgdat "${startdir}/pkg/opt/2gis/volgograd.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Volgograd.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Volgograd.dglf" || return 1
     
}

