pkgname=2gis-volgograd
pkgver=46
pkgrel=1
pkgdesc="Map of Volgograd for 2GIS, July 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/volgograd/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Volgograd-46.orig.zip")
md5sums=('19d8ac819123dafcdf72de07c9fe4edb')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Volgograd.dgdat" "${pkgdir}/opt/2gis/2gis-volgograd.dgdat" || return 1
  
}
