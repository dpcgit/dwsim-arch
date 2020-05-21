# Generated by debtap
# Maintainer: dwsim
# Contributor: dwsim
pkgname=dwsim-bin
pkgname=dwsim
pkgver=5.8.11
pkgrel=1
pkgdesc="DWSIM - Open Source Process Simulator. DWSIM is a software for modeling, simulation and optimization of steady-state chemical processes. DISCLAIMER The data and information within DWSIM has been obtained from a wide variety of literature sources. While reasonable care has been exercised in the collection of data and testing of this software, the author of DWSIM disclaims any warranty, expressed or implied, as to the accuracy or reliability of the data or calculations contained therein. The results of calculations obtained from DWSIM yield approximate results, which will not always be suitable for every application. The software is designed for use by trained professional personnel and is not a substitute for sound professional judgment. It is the sole responsibility of the user to validate the data presented by DWSIM and to determine whether the results of this program are accurate and suitable for any specific purpose. No guarantee of accuracy or fitness for any purpose is expressed or implied. The author strongly recommends that the data be checked against other sources and/or methods before use and application. The author shall not be held liable for any direct, indirect, consequential or incidental damages incurred through use of the data or calculations. LICENSE DWSIM is licensed under the GNU General Public License (GPL) Version 3. VERSION HISTORY / CHANGELOG"
arch=('i686' 'x86_64')
url="http://dwsim.inforside.com.br"
license=('GNU')
groups=('')
depends=('crossover' 'desktop-file-utils' 'fontconfig' 'glu' 'gtk>=2.12' 'hicolor-icon-theme' 'mono>=5.14')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_i686=("PUT_FULL_URL_FOR_DOWNLOADING_i386_DEB_PACKAGE_HERE")
source_x86_64=("PUT_FULL_URL_FOR_DOWNLOADING_amd64_DEB_PACKAGE_HERE")
sha512sums_i686=('PUT_SHA512SUM_OF_i386_DEB_PACKAGE_HERE')
sha512sums_x86_64=('d422f54a5cebbf5cce7cad92a7c1cd49402d55bc5a6e33ff764dfd538a5d22a7637df2845f705caea8cbafef873f66afc02dc7a1e2bffb5a2cf0d6a6b028ff16')

package(){

	# Extract package data
	tar xf data.tar.xz -C "${pkgdir}"

	# Fix directory structure differences
	cd "${pkgdir}"

	install -D -m644 "/usr/local/lib/dwsim/license.txt" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
	mkdir usr/bin 2> /dev/null; mv usr/local/bin/* usr/bin; rm -rf usr/local/bin

	cd ..

}
