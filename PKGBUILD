pkgname=craftbukkit-plugin-spout-gunpack
pkgver=1.6
pkgrel=2
pkgdesc="Spout plugin for CraftBukkit that lets you add custom gun items"
arch=(any)
url="http://forums.bukkit.org/threads/mech-fun-gunpack-v1-6-create-your-very-own-guns-spout-1-1-r3.57768/"
license=('unknown')
depends=('craftbukkit-plugin-spout')
source=("http://dl.dropbox.com/u/44243469/GunPack/GunPack.jar")
noextract=("GunPack.jar")
md5sums=('5a0cd0474979b8c4a3544b37db08ead2')

package() {
	mkdir -p "$pkgdir/opt/craftbukkit/plugins"
	install -m 644 "$srcdir/GunPack.jar" "$pkgdir/opt/craftbukkit/plugins"
}
