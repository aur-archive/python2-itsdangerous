# Maintainter: warddr <aur@warddr.eu>
# Submitter: ushi <martin.kalcher@gmail.com>
pkgname=python2-itsdangerous
pkgver=0.17
pkgrel=1
pkgdesc="Various helpers to pass trusted data to untrusted environments."
arch=('any')
url="http://pypi.python.org/pypi/itsdangerous"
license=('BSD')
depends=('python2')
source=("http://pypi.python.org/packages/source/i/itsdangerous/itsdangerous-${pkgver}.tar.gz")
md5sums=('f40c7dc39beb859988b0a801d13672aa')

package() {
  cd "$srcdir/${pkgname:8}-$pkgver"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
