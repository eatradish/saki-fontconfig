# sakiily-fonts-config

My Arch Linux /etc/fonts

# config

```
# pacaur -S adobe-source-code-pro-fonts  adobe-source-han-sans-cn-fonts adobe-source-han-serif-tw-fonts  noto-fonts-cjk noto-fonts-emoji noto-fonts-extra font-bh-ttf
$ git clone https://github.com/eatradish/sakiily-fonts-config.git
$ cd /$path/sakiily-fonts-config
# cp conf.avail/* /etc/fonts/conf.avail
$ cd /etc/fonts/conf.d
# sudo ln -sf /etc/fonts/conf.avail/* /etc/fonts/conf.d/
# cp ../fonts.conf /etc/fonts/fonts.conf

$ ls -l /etc/fonts/conf.d
total 56
lrwxrwxrwx 1 root root 38 Nov 14 01:18 10-autohint.conf -> /etc/fonts/conf.avail/10-autohint.conf
lrwxrwxrwx 1 root root 42 Nov 14 01:18 10-hinting-full.conf -> /etc/fonts/conf.avail/10-hinting-full.conf
lrwxrwxrwx 1 root root 44 Nov 14 01:18 10-hinting-medium.conf -> /etc/fonts/conf.avail/10-hinting-medium.conf
lrwxrwxrwx 1 root root 42 Nov 14 01:18 10-hinting-none.conf -> /etc/fonts/conf.avail/10-hinting-none.conf
lrwxrwxrwx 1 root root 44 Nov 14 01:18 10-hinting-slight.conf -> /etc/fonts/conf.avail/10-hinting-slight.conf
lrwxrwxrwx 1 root root 42 Nov 14 01:18 10-no-sub-pixel.conf -> /etc/fonts/conf.avail/10-no-sub-pixel.conf
lrwxrwxrwx 1 root root 48 Nov 14 01:18 10-scale-bitmap-fonts.conf -> /etc/fonts/conf.avail/10-scale-bitmap-fonts.conf
lrwxrwxrwx 1 root root 43 Nov 14 01:18 10-sub-pixel-bgr.conf -> /etc/fonts/conf.avail/10-sub-pixel-bgr.conf
lrwxrwxrwx 1 root root 43 Nov 14 01:18 10-sub-pixel-rgb.conf -> /etc/fonts/conf.avail/10-sub-pixel-rgb.conf
lrwxrwxrwx 1 root root 44 Nov 14 01:18 10-sub-pixel-vbgr.conf -> /etc/fonts/conf.avail/10-sub-pixel-vbgr.conf
lrwxrwxrwx 1 root root 44 Nov 14 01:18 10-sub-pixel-vrgb.conf -> /etc/fonts/conf.avail/10-sub-pixel-vrgb.conf
lrwxrwxrwx 1 root root 38 Nov 14 01:18 10-unhinted.conf -> /etc/fonts/conf.avail/10-unhinted.conf
lrwxrwxrwx 1 root root 47 Nov 14 01:18 11-lcdfilter-default.conf -> /etc/fonts/conf.avail/11-lcdfilter-default.conf
lrwxrwxrwx 1 root root 46 Nov 14 01:18 11-lcdfilter-legacy.conf -> /etc/fonts/conf.avail/11-lcdfilter-legacy.conf
lrwxrwxrwx 1 root root 45 Nov 14 01:18 11-lcdfilter-light.conf -> /etc/fonts/conf.avail/11-lcdfilter-light.conf
lrwxrwxrwx 1 root root 51 Nov 14 01:18 20-adobe-source-code-pro.conf -> /etc/fonts/conf.avail/20-adobe-source-code-pro.conf
lrwxrwxrwx 1 root root 47 Nov 14 01:18 20-unhint-small-vera.conf -> /etc/fonts/conf.avail/20-unhint-small-vera.conf
lrwxrwxrwx 1 root root 45 Nov 14 01:18 25-unhint-nonlatin.conf -> /etc/fonts/conf.avail/25-unhint-nonlatin.conf
lrwxrwxrwx 1 root root 44 Nov 14 01:18 30-metric-aliases.conf -> /etc/fonts/conf.avail/30-metric-aliases.conf
lrwxrwxrwx 1 root root 41 Nov 14 01:18 30-urw-aliases.conf -> /etc/fonts/conf.avail/30-urw-aliases.conf
lrwxrwxrwx 1 root root 38 Nov 14 01:18 40-nonlatin.conf -> /etc/fonts/conf.avail/40-nonlatin.conf
lrwxrwxrwx 1 root root 40 Apr 24  2017 44-source-han-sans-cn.conf -> ../conf.avail/44-source-han-sans-cn.conf
lrwxrwxrwx 1 root root 35 Nov 14 01:18 45-latin.conf -> /etc/fonts/conf.avail/45-latin.conf
lrwxrwxrwx 1 root root 39 Nov 14 01:18 49-sansserif.conf -> /etc/fonts/conf.avail/49-sansserif.conf
lrwxrwxrwx 1 root root 34 Nov 14 01:18 50-user.conf -> /etc/fonts/conf.avail/50-user.conf
lrwxrwxrwx 1 root root 35 Nov 14 01:18 51-local.conf -> /etc/fonts/conf.avail/51-local.conf
lrwxrwxrwx 1 root root 35 Nov 14 01:18 60-latin.conf -> /etc/fonts/conf.avail/60-latin.conf
lrwxrwxrwx 1 root root 43 Nov 14 01:18 65-fonts-persian.conf -> /etc/fonts/conf.avail/65-fonts-persian.conf
lrwxrwxrwx 1 root root 35 Nov 14 01:18 65-khmer.conf -> /etc/fonts/conf.avail/65-khmer.conf
lrwxrwxrwx 1 root root 38 Nov 14 01:18 65-nonlatin.conf -> /etc/fonts/conf.avail/65-nonlatin.conf
lrwxrwxrwx 1 root root 42 Nov 14 01:18 66-aa-rendering.conf -> /etc/fonts/conf.avail/66-aa-rendering.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-kufi-arabic.conf -> /etc/fonts/conf.avail/66-google-noto-kufi-arabic.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-naskh-arabic.conf -> /etc/fonts/conf.avail/66-google-noto-naskh-arabic.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-naskh-arabic-ui.conf -> /etc/fonts/conf.avail/66-google-noto-naskh-arabic-ui.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-armenian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-armenian.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-avestan.conf -> /etc/fonts/conf.avail/66-google-noto-sans-avestan.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-balinese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-balinese.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-bamum.conf -> /etc/fonts/conf.avail/66-google-noto-sans-bamum.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-batak.conf -> /etc/fonts/conf.avail/66-google-noto-sans-batak.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-bengali.conf -> /etc/fonts/conf.avail/66-google-noto-sans-bengali.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-bengali-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-bengali-ui.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-brahmi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-brahmi.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-buginese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-buginese.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-buhid.conf -> /etc/fonts/conf.avail/66-google-noto-sans-buhid.conf
lrwxrwxrwx 1 root root 66 Nov 14 01:18 66-google-noto-sans-canadian-aboriginal.conf -> /etc/fonts/conf.avail/66-google-noto-sans-canadian-aboriginal.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-carian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-carian.conf
lrwxrwxrwx 1 root root 51 Nov 14 01:18 66-google-noto-sans-cham.conf -> /etc/fonts/conf.avail/66-google-noto-sans-cham.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-cherokee.conf -> /etc/fonts/conf.avail/66-google-noto-sans-cherokee.conf
lrwxrwxrwx 1 root root 46 Nov 14 01:18 66-google-noto-sans.conf -> /etc/fonts/conf.avail/66-google-noto-sans.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-coptic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-coptic.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-cuneiform.conf -> /etc/fonts/conf.avail/66-google-noto-sans-cuneiform.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-cypriot.conf -> /etc/fonts/conf.avail/66-google-noto-sans-cypriot.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-deseret.conf -> /etc/fonts/conf.avail/66-google-noto-sans-deseret.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-devanagari.conf -> /etc/fonts/conf.avail/66-google-noto-sans-devanagari.conf
lrwxrwxrwx 1 root root 60 Nov 14 01:18 66-google-noto-sans-devanagari-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-devanagari-ui.conf
lrwxrwxrwx 1 root root 67 Nov 14 01:18 66-google-noto-sans-egyptian-hieroglyphs.conf -> /etc/fonts/conf.avail/66-google-noto-sans-egyptian-hieroglyphs.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-ethiopic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-ethiopic.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-georgian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-georgian.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-glagolitic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-glagolitic.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-gothic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-gothic.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-gujarati.conf -> /etc/fonts/conf.avail/66-google-noto-sans-gujarati.conf
lrwxrwxrwx 1 root root 58 Nov 14 01:18 66-google-noto-sans-gujarati-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-gujarati-ui.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-gurmukhi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-gurmukhi.conf
lrwxrwxrwx 1 root root 58 Nov 14 01:18 66-google-noto-sans-gurmukhi-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-gurmukhi-ui.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-hanunoo.conf -> /etc/fonts/conf.avail/66-google-noto-sans-hanunoo.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-hebrew.conf -> /etc/fonts/conf.avail/66-google-noto-sans-hebrew.conf
lrwxrwxrwx 1 root root 63 Nov 14 01:18 66-google-noto-sans-imperial-aramaic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-imperial-aramaic.conf
lrwxrwxrwx 1 root root 68 Nov 14 01:18 66-google-noto-sans-inscriptional-pahlavi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-inscriptional-pahlavi.conf
lrwxrwxrwx 1 root root 69 Nov 14 01:18 66-google-noto-sans-inscriptional-parthian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-inscriptional-parthian.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-japanese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-japanese.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-javanese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-javanese.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-kaithi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-kaithi.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-kannada.conf -> /etc/fonts/conf.avail/66-google-noto-sans-kannada.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-kannada-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-kannada-ui.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-kayah-li.conf -> /etc/fonts/conf.avail/66-google-noto-sans-kayah-li.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-kharoshthi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-kharoshthi.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-khmer.conf -> /etc/fonts/conf.avail/66-google-noto-sans-khmer.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-khmer-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-khmer-ui.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-korean.conf -> /etc/fonts/conf.avail/66-google-noto-sans-korean.conf
lrwxrwxrwx 1 root root 50 Nov 14 01:18 66-google-noto-sans-lao.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lao.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-lao-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lao-ui.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-lepcha.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lepcha.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-limbu.conf -> /etc/fonts/conf.avail/66-google-noto-sans-limbu.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-linear-b.conf -> /etc/fonts/conf.avail/66-google-noto-sans-linear-b.conf
lrwxrwxrwx 1 root root 51 Nov 14 01:18 66-google-noto-sans-lisu.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lisu.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-lycian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lycian.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-lydian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-lydian.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-malayalam.conf -> /etc/fonts/conf.avail/66-google-noto-sans-malayalam.conf
lrwxrwxrwx 1 root root 59 Nov 14 01:18 66-google-noto-sans-malayalam-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-malayalam-ui.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-mandaic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-mandaic.conf
lrwxrwxrwx 1 root root 59 Nov 14 01:18 66-google-noto-sans-meetei-mayek.conf -> /etc/fonts/conf.avail/66-google-noto-sans-meetei-mayek.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-mongolian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-mongolian.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-myanmar.conf -> /etc/fonts/conf.avail/66-google-noto-sans-myanmar.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-myanmar-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-myanmar-ui.conf
lrwxrwxrwx 1 root root 58 Nov 14 01:18 66-google-noto-sans-new-tai-lue.conf -> /etc/fonts/conf.avail/66-google-noto-sans-new-tai-lue.conf
lrwxrwxrwx 1 root root 50 Nov 14 01:18 66-google-noto-sans-nko.conf -> /etc/fonts/conf.avail/66-google-noto-sans-nko.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-ogham.conf -> /etc/fonts/conf.avail/66-google-noto-sans-ogham.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-ol-chiki.conf -> /etc/fonts/conf.avail/66-google-noto-sans-ol-chiki.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-old-italic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-old-italic.conf
lrwxrwxrwx 1 root root 58 Nov 14 01:18 66-google-noto-sans-old-persian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-old-persian.conf
lrwxrwxrwx 1 root root 64 Nov 14 01:18 66-google-noto-sans-old-south-arabian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-old-south-arabian.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-old-turkic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-old-turkic.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-oriya.conf -> /etc/fonts/conf.avail/66-google-noto-sans-oriya.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-oriya-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-oriya-ui.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-osmanya.conf -> /etc/fonts/conf.avail/66-google-noto-sans-osmanya.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-phags-pa.conf -> /etc/fonts/conf.avail/66-google-noto-sans-phags-pa.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-phoenician.conf -> /etc/fonts/conf.avail/66-google-noto-sans-phoenician.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-rejang.conf -> /etc/fonts/conf.avail/66-google-noto-sans-rejang.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-runic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-runic.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-samaritan.conf -> /etc/fonts/conf.avail/66-google-noto-sans-samaritan.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 66-google-noto-sans-saurashtra.conf -> /etc/fonts/conf.avail/66-google-noto-sans-saurashtra.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-shavian.conf -> /etc/fonts/conf.avail/66-google-noto-sans-shavian.conf
lrwxrwxrwx 1 root root 65 Nov 14 01:18 66-google-noto-sans-simplified-chinese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-simplified-chinese.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-sinhala.conf -> /etc/fonts/conf.avail/66-google-noto-sans-sinhala.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-sundanese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-sundanese.conf
lrwxrwxrwx 1 root root 59 Nov 14 01:18 66-google-noto-sans-syloti-nagri.conf -> /etc/fonts/conf.avail/66-google-noto-sans-syloti-nagri.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-symbols.conf -> /etc/fonts/conf.avail/66-google-noto-sans-symbols.conf
lrwxrwxrwx 1 root root 61 Nov 14 01:18 66-google-noto-sans-syriac-eastern.conf -> /etc/fonts/conf.avail/66-google-noto-sans-syriac-eastern.conf
lrwxrwxrwx 1 root root 64 Nov 14 01:18 66-google-noto-sans-syriac-estrangela.conf -> /etc/fonts/conf.avail/66-google-noto-sans-syriac-estrangela.conf
lrwxrwxrwx 1 root root 61 Nov 14 01:18 66-google-noto-sans-syriac-western.conf -> /etc/fonts/conf.avail/66-google-noto-sans-syriac-western.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-tagalog.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tagalog.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-tagbanwa.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tagbanwa.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-tai-le.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tai-le.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-tai-tham.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tai-tham.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-tai-viet.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tai-viet.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-sans-tamil.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tamil.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-tamil-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tamil-ui.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-telugu.conf -> /etc/fonts/conf.avail/66-google-noto-sans-telugu.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-sans-telugu-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-telugu-ui.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-sans-thaana.conf -> /etc/fonts/conf.avail/66-google-noto-sans-thaana.conf
lrwxrwxrwx 1 root root 51 Nov 14 01:18 66-google-noto-sans-thai.conf -> /etc/fonts/conf.avail/66-google-noto-sans-thai.conf
lrwxrwxrwx 1 root root 54 Nov 14 01:18 66-google-noto-sans-thai-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-thai-ui.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-tifinagh.conf -> /etc/fonts/conf.avail/66-google-noto-sans-tifinagh.conf
lrwxrwxrwx 1 root root 66 Nov 14 01:18 66-google-noto-sans-traditional-chinese.conf -> /etc/fonts/conf.avail/66-google-noto-sans-traditional-chinese.conf
lrwxrwxrwx 1 root root 55 Nov 14 01:18 66-google-noto-sans-ugaritic.conf -> /etc/fonts/conf.avail/66-google-noto-sans-ugaritic.conf
lrwxrwxrwx 1 root root 49 Nov 14 01:18 66-google-noto-sans-ui.conf -> /etc/fonts/conf.avail/66-google-noto-sans-ui.conf
lrwxrwxrwx 1 root root 50 Nov 14 01:18 66-google-noto-sans-vai.conf -> /etc/fonts/conf.avail/66-google-noto-sans-vai.conf
lrwxrwxrwx 1 root root 49 Nov 14 01:18 66-google-noto-sans-yi.conf -> /etc/fonts/conf.avail/66-google-noto-sans-yi.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-serif-armenian.conf -> /etc/fonts/conf.avail/66-google-noto-serif-armenian.conf
lrwxrwxrwx 1 root root 47 Nov 14 01:18 66-google-noto-serif.conf -> /etc/fonts/conf.avail/66-google-noto-serif.conf
lrwxrwxrwx 1 root root 56 Nov 14 01:18 66-google-noto-serif-georgian.conf -> /etc/fonts/conf.avail/66-google-noto-serif-georgian.conf
lrwxrwxrwx 1 root root 53 Nov 14 01:18 66-google-noto-serif-khmer.conf -> /etc/fonts/conf.avail/66-google-noto-serif-khmer.conf
lrwxrwxrwx 1 root root 51 Nov 14 01:18 66-google-noto-serif-lao.conf -> /etc/fonts/conf.avail/66-google-noto-serif-lao.conf
lrwxrwxrwx 1 root root 52 Nov 14 01:18 66-google-noto-serif-thai.conf -> /etc/fonts/conf.avail/66-google-noto-serif-thai.conf
lrwxrwxrwx 1 root root 59 Nov 14 01:18 67-google-noto-cjk-sans-japanese.conf -> /etc/fonts/conf.avail/67-google-noto-cjk-sans-japanese.conf
lrwxrwxrwx 1 root root 57 Nov 14 01:18 67-google-noto-cjk-sans-korean.conf -> /etc/fonts/conf.avail/67-google-noto-cjk-sans-korean.conf
lrwxrwxrwx 1 root root 69 Nov 14 01:18 67-google-noto-cjk-sans-simplified-chinese.conf -> /etc/fonts/conf.avail/67-google-noto-cjk-sans-simplified-chinese.conf
lrwxrwxrwx 1 root root 70 Nov 14 01:18 67-google-noto-cjk-sans-traditional-chinese.conf -> /etc/fonts/conf.avail/67-google-noto-cjk-sans-traditional-chinese.conf
lrwxrwxrwx 1 root root 37 Nov 14 01:18 69-unifont.conf -> /etc/fonts/conf.avail/69-unifont.conf
lrwxrwxrwx 1 root root 40 Nov 14 01:18 70-no-bitmaps.conf -> /etc/fonts/conf.avail/70-no-bitmaps.conf
lrwxrwxrwx 1 root root 41 Nov 14 01:18 70-yes-bitmaps.conf -> /etc/fonts/conf.avail/70-yes-bitmaps.conf
lrwxrwxrwx 1 root root 39 Nov 14 01:18 80-delicious.conf -> /etc/fonts/conf.avail/80-delicious.conf
lrwxrwxrwx 1 root root 39 Nov 14 01:18 90-synthetic.conf -> /etc/fonts/conf.avail/90-synthetic.conf

```

# EOF
