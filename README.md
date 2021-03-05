# laot-apartments-m3
Credit : laot7490

Scriptin çalışması için
https://github.com/laot7490/laot-interior https://github.com/laot7490/laot-core
Dosyalarına ihtiyacınız var. 

Ayrıca m3 configine stash açmanız gerekmekte.
Açmak için m3_inventoryhud/config.lua
kısmına stash başlığının altına

    ['Apartman'] = { 
        coords = {vector3(-99.9, -99.9, -99.9)},
        useMarker = false,
        markerType = 2,
        markerSize = vector3(0.2, 0.2, 0.2),
        markerColour = { r = 255, g = 255, b = 255 },
        use3dtext = false,
        msg = 'Depoya erişmek için ~INPUT_CONTEXT~ tuşuna basınız.', --or '[E] - Silahlar',
        job = 'all',
        maxweight = 1000 -- if u use weight, uncomment this line
    },

Bu kodu yapıştırmalısınız. Kendinize göre düzenleyebilirsiniz.
