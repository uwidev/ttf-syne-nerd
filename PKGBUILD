pkgname=ttf-syne-nerd
pkgver=1.0.0
pkgrel=1
pkgdesc="Syne sans-serif, monospace, and tactile patched with nerd"
arch=('any')
license=('OFL')
source=("https://github.com/uwidev/$pkgname/raw/refs/heads/main/ttf-syne-nerd.zip")
sha256sums=("8465e051f9210bae57d4644ecdc89a265f81cb6d5477258b0425dc20c52c6e37")

package() {
	install -dm 755 "$pkgdir"/usr/share/fonts/TTF
	install -Dm644 ./*.ttf "$pkgdir"/usr/share/fonts/TTF
}
