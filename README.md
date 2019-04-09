npm install -g ionic cordova

ionic start ProgRendszer

ionic cordova platform add android

ionic cordova build android

ionic cordova run android


Otthoni feladat: automatikus +5 pont minden beküldőnek
- buildelj le egy .apk fájlt az otthoni gépen a projektből (ionic cordova build android    után meg kell jelennie a build/outputs mappában)
- vond be a DB Meter plugint https://ionicframework.com/docs/native/db-meter
- fontos infó: az app.module.ts-be is importáld be DBMeter-t a mintában látott módon és tedd bele a providers tömbbe különben nem fog működni
- egy {{volume}} változóval a home.page.html-en jelenítsd meg az épp detektált hangerősséget
- a feltöltött .apk mellé helyezz egy linket is a github/bitbucket repóra, amely tartalmazza a forrást