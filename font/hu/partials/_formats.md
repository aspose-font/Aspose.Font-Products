---
translation: true
deploy: false
---


{{<section TTF>}}

A TrueType betűtípus vagy TTF jelenleg a legnépszerűbb. Ezt a formátumot először az Apple fejlesztette ki, és manapság a Microsoft és az Apple operációs rendszerek használják. A TTF font speciális technikákat használ a betűtípus kiváló minőségű megjelenítéséhez az alacsony képernyőfelbontású eszközökön. A kifejlesztett utasításokat használja, amelyek lehetővé teszik, hogy a betűtípusok hasonló minőségűek legyenek, mint a bittérképes betűtípusok.

{{<section WOFF>}}

"A Web Open Font Format vagy WOFF 2009-ben lett kifejlesztve a webalkalmazások piacának igényeinek kielégítésére a TrueType és OpenType betűtípusok formátum-specifikus tömörítésével. Zlib tömörítést használ, amely körülbelül 40%-os tömörítést biztosít a betűtípusoknak. A WOFF formátum másik sajátossága, hogy hogy a formátum betűtípusa tartalmazhat csatolt további metaadatokat. Ezek a metaadatok nem befolyásolják a betűtípus megjelenítését, de szükség esetén megjelenhetnek a felhasználó számára."

{{<section WOFF2>}}

A Web Open Font Format 2 vagy WOFF2 a WOFF formátum következő verziója jobb tömörítéssel. Pontosabban 30%-os előnyt biztosít a tömörítésben a WOFF formátumhoz képest. A Brotli bájtszintű tömörítési algoritmust használja, amely egy könyvtár az adatok nyílt forráskódú tömörítésére. A weboldalak betöltésének felgyorsítására szolgál. WOFF formátumként a WOFF2-t a legtöbb böngésző is támogatja.

{{<section TYPE1>}}

Az 1-es típusú formátum a PostScript programozási nyelvvel együtt 1984-ben került piacra, így a formátumot Postscript Type 1-nek is nevezik. Ez a Postscript program és a fájlformátum egy speciális formája, amely a betűtípus leírására irányul. Az 1-es típusú formátumot a nyomtatók és a számítógépek felismerik a beépített tolmácsok vagy további segédprogramok, például az Adobe Type Manager segítségével. A betűtípusok nem támogatják a Unicode kódolási szabványokat.

{{<section EOT>}}

Beágyazott OpenType vagy EOT formátum. Ez a weboldalakba ágyazott OpenType betűtípusok kompakt formátuma. LZ-tömörítést használva, és csak a szükséges karaktereket tartalmazza a betűtípusban, az OpenType-fájlok kompaktak. A betűtípus lehetővé teszi a font szerzői jogok megsértésének megakadályozását, és mindig olvasható, mivel tartalék betűtípusokat használ.

{{<section CFF>}}

A Compact Font Format vagy CFF Type 2 font formátumként vagy CFF/Type 2 betűformátumként is ismert. Azt mondják, hogy a CFF nem pontosan a betűtípus formátuma, hanem más betűformátumok tömörítésének módja, mint például a Type 1. Az 1-es típushoz és a TrueType formátumokhoz hasonlóan a CFF is használ utalásokat. Ugyanazokat a módszereket használja a tippek megjelenítésére, mint az 1. típus, de egyszerűbb és tisztább kódba írni, és jelentős helymegtakarítást tesz lehetővé.

{{<section OTF>}}

Az OpenType betűtípust vagy OTF-et ennek alapján hozták létre, és alapstruktúráját a TrueType-tól vette át. Ehhez további adatkonstrukciókat adtak a tipográfiai viselkedés rendezésére. A formátum a TrueType és a Postscript betűtípusok összekapcsolásaként ismert. Mivel valóban rugalmas, a legtöbb operációs rendszer és eszköz támogatja. TTF-ként az OTF is teljesen méretezhető anélkül, hogy a minőség romlana.