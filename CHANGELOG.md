Changelog
3.5.0 (2021-03-02)
Features

    add restart time for leaking Chromium in Ubuntu (#1880) (1009ce6)
    add terraform infra as code for AWS fargate (#1987) (d341ef7)
    clean up proxy logging with n/N in each lookup (#1839) (8df4339)
    notification: add simple SmartThings switch activation (#1902) (c22c960)
    notification: add Streamlabs support (#1872) (edb39f8)
    nvidia: updated store for europe (#1732) (2143b15)
    sms: add US Cellular (#1874) (4455e4e)
    store: add globaldata (#2004) (5effbae)
    store: add ldlc (FR) (#2037) (a7be09d)
    store: add netonnet-no (#1989) (e6803d4)
    store: add Norwegian stores (#1985) (5a5927b)
    store: add novoatalho (PT) (#2043) (a3c726b)
    store: add PCDiga.com (#1990) (2501f6b)
    store: corsair-uk (#1733) (c81282e)
    use node 15, use package version (#2066) (eee669b)

Bug Fixes

    alternate: update URLs (#1814) (d63685f)
    amazon-ca: out of stock check was missing (#1885) (0e65f33)
    amazon-ca: update selector (#1851) (3293184)
    amazon-uk: add label for ps5 (8ee6815), closes #2036
    discord: ensure first group in list is notified (#1788) (9791568)
    docs: nvidia store changes (#1797) (de1427c)
    galaxus: update selector (#1730) (1015358)
    microcenter: properly flag in stock items (#1754) (ce609fb)
    nvidia: update inStock text (#1850) (4f57df0)
    remove package-lock.json (e3d0980)
    vuugo: add out of stock check (#1731) (9695e29)
    web: 404 Error / page not visible (#1825) (95b4a15)
    wipoid: corrected 3070 / 3080 links (#1879) (2572c8a)

3.4.1 (2021-01-17)
Bug Fixes

    proxy: build proxyList correctly (c177aed)

3.4.0 (2021-01-17)
Features

    add browser opening to test:notification (f87053c)
    add c8 and mocha for testing (f87053c)
    add command parameter to set custom dotenv conf (#1590) (b03d242)
    add redis (#1390) (fb82526)
    asus: add outOfStock label (#1653) (d0a4667), closes #368
    azerty: add ryzen 5000 series (#878) (ca59777)
    caseking: add 3060ti/3070 cards / add missing 3080/3090 cards (#1715) (b2ebac3)
    galaxus: update selector, add out of stock check (#1607) (c9cda1e)
    lookup: add max price for xbox (f34a808), closes #1436
    lookup: add protection against infinite recursion for Cloudflare (#1505) (1cf618c), closes #1459 #1490
    lookup: handle Cloudflare DDoS protection (#1434) (f86a825), closes #1297
    proshop-de: add proshop-de inStock selector (#1633) (9c2ea8d)
    proxy: fallback to a global proxy list (#1388) (be1953b)
    pushover: add screenshot to push notification if available (#1552) (f9a3d03)
    remove stale user agents, use top 50 (6e2a162)
    store: add johnlewis store, add shopto store (#1481) (ec8d357)
    store: add equippr & futurex for DE region (#1501) (5b70ff1)
    store: add GPU and CPU support for Vuugo (#1555) (8ab6e1f)
    store: add more italian sites (#1701) (cb898c7)
    store: add pcking and acompc (#1470) (beee355)
    store: add SG Location for Amazon and Newegg (#1600) (ef926d2)
    store: addition of several australian sites (#1651) (2fa8937)
    store: specify links to navigate to between product searches (#1542) (0982774)
    twilio: add support to have multiple numbers (#1450) (83508bc)
    update Docker and ci (f87053c)
    vsgamers: add maxPrice selector(#1682) (84382de)
    web: properly set for attribute for labels (#1626) (c0638d2)

Bug Fixes

    acompc: false positives (#1699) (0a1198b)
    amazon-de-warehouse: update wrong maxPrice selector (#1514) (90fb430)
    bandh: asus cards / out of stock check added (#1670) (b821eab)
    bestbuy: shorter pageview urls and missing carturl links (#1613) (8faf320), closes #1610
    computeruniverse: false positives (#1698) (e0849c4)
    disable redis if not configured (6bc7737), closes #1516
    galaxus: maxPrice selector (#1469) (7a5bc22)
    galaxus: update selector ( 14.01.2020 07:00 ) (#1664) (a768eb4)
    galaxus: update selector (#1578) (ad5bd55)
    galaxus: update selector (#1599) (445a007)
    galaxus: update selector (#1705) (2120d29)
    lookup: check out of stock before price (#1422) (02d29c3)
    lookup: remove mobile versions of user agent (96ae818)
    newegg: false positives (all stores) (#1714) (3f191bb)
    properly pass array entries as separate indices (#1502) (0c6e2d5)
    proxy: fix requests with proxies (#1408) (f65df4c)
    proxy: update proxy module (#1451) (ab03702), closes #1437
    store: link builder in UK stores (#1486) (eb59dc3)
    store: Update 30 series links and models for store.asus.com (#1645) (20bea85), closes #1637
    store: update missing/mislabeled cards for Canadian retailers (#1574) (082776c)
    store: update out of stock detection for MediaMarkt and Saturn (#1549) (4f86d24), closes #1545
    webui: handling of file serving (#1383) (445689e)
    wipoid: added 3090/3080/3070/3060ti/ryzen store items (#1683) (be54171)

3.3.0 (2020-12-13)
Features

    discord: dynamic currency symbol (#1328) (cccfde2)
    docs: add mkdocs (243109a)
    docs: add table sorting (#1258) (5955d10)
    lookup: use random user agents (#1335) (b599c23)
    notification: add discord groups (#1211) (2632386)
    notification: add sound player executable option (#1301) (8d19231)
    playstation: add queuing selector (#1173) (67b19a7)
    store: add darkhero motherboard to asus and microcenter (#1336) (29175c7)
    store: add EBGames (#1281) (27cfb94)
    store: add Irish store variants (#1373) (f70998f)
    store: add Megekko (#1216) (30bed2a)
    store: add several Australian stores, add some 3080 brands/models (#1367) (579cb97)
    store: add Toys R Us (#1257) (ac0bd2a)
    store: add Walmart (CA) (#1253) (b535b47)

Bug Fixes

    adblock: proxy another function to produce less errors (#1379) (eb70076)
    amazon-it: maxPrice selector and links (#1239) (84f2cb7)
    amazon-nl: inStock selector (b6964b0), closes #1366
    bestbuy-ca: add outOfStock text (58f0a9c), closes #1269
    bestbuy-ca: update selectors to help false positives (#1278) (0525119), closes #895
    ci: mkdocs deps (1f63e99)
    config: disable docker by default (dca916b)
    config: remove quotes (ef452d8)
    discord: notification groupings (ad0b2fe)
    docker: run in docker, and build scripts for docker (#1291) (c74ea28)
    eprice: inStock selector (5e1dfc3), closes #1067
    newegg: dedupe nitro+ models (#1300) (7329c6e), closes #1230
    newegg: price selector and mobile inStock (c3beedc), closes #1356
    pushover: add expire and retry (0072dda), closes #983
    store: update UK stores (#1372) (02825d0)
    .env backwards compatibility (9b7c7e2)
    add setRequestInterception (#1312) (a44621f), closes #826
    store: italian store checks (#1212) (e3eb386)

Reverts

    allow users to still use USER_AGENT (3386e8f)

3.2.0 (2020-12-06)
Features

    bestbuy: add 3060 series (#1074) (e9a39c4)
    bestbuy-ca: add 3060ti cards (29478bf)
    notification: add price to links (#1209) (15ec12b), closes #1188 #673 #1187
    proxy: socks5 support (#933) (364c6c2)
    store: add 3060ti to newegg-ca, canadacomputer, memoryexpress (#1172) (09f0236)
    store: add amazon-de-warehouse (#1102) (6de8c4a)
    store: add antonline store (#1042) (19eece1)
    store: add argos with ps5 (b2f5c1a)
    store: add awd(uk), add 3060ti link builders (#1114) (36e3806)
    store: add custom labels for links (#1183) (f7b32e8), closes #1132 #1163
    store: add el corte ingles (#1107) (75ee95b)
    store: add ePrice store (#1016) (30a51a3)
    store: add Euronics DE (#1045) (1774afc)
    store: add expert (#1105) (202698f)
    store: add Gamestop DE (#1046) (79a3f33)
    store: add Medimax (#1057) (7d29ef8)
    store: add Otto (#1096) (af96c5f)
    store: add smythstoys (1ed0593)
    store: add some italian stores with ps5 links (#976) (f663579)
    store: add spielegrotte (#1056) (cf70f1f)
    store: add wipoid store (#1018) (feae978)
    store: update the italian store links (#1002) (de7036c)
    topachat: add maxPrice (d7f2427), closes #1097
    add proxy rotation (settable per store) (#1026) (490d44e)

Bug Fixes

    amazon: price and cart buttons (6fd023e), closes #1125
    amazon-de: inStock selector (14cbd5a), closes #1178
    amazon-de: remove xbox cart links (cbc4330), closes #1095
    bestbuy-ca: model always indicating in stock (#1145) (06f3aaf)
    bestbuy-ca: replace old evga xc3 ultra (#1058) (65df944)
    canadacomputers: add inStock selector, use english links (#889) (06214eb)
    memoryexpress: add backorder to outOfStock selector (#890) (67605a6)
    newegg: maxPrice selector using used price (feddac7), closes #1052
    newegg: typo in 5800x url(#903) (a99eecb)
    scan: links builder (#1161) (ca5553c)
    smythstoys: add out of stock label (5bbdfa2)
    store: add backoffStatusCodes and new captcha container (#1110) (0b11238)
    store: removes unnecessary newegg links from bestbuy (#1126) (f2ae423), closes #1119
    store: update euroFormat for expert and otto (#1108) (e198e44)
    walmart: instock container and add test:series (21e74cf), closes #1106
    related products being picked up on scan (#954) (db18157)

3.1.0 (2020-11-22)
Features

    asus: add backoff codes (#790) (501ea34)
    canadacomputers: add ryzen 5000 series (#842) (6f27330)
    coolmod: add maxPrice (#862) (4b689cb)
    newegg-ca: add big navi links (#843) (6d292a1)
    notification: add product link to email and telegram (#816) (777c31b)
    playstation: add outOfStock label (#812) (eb314af)
    store: add PlayStation store (#806) (7c28c7f)
    store: add 3070 models to pccomponentes & coolmod (#820) (d0ebffd)
    store: add amd rx 6000 series model (#832) (89a762e)
    store: add captcha check to saturn and mediamarkt (#876) (2d01cfd)
    store: add corsair sfx PSUs (#881) (e552c91)
    store: add topachat (#776) (c38bebb)
    store: add vsgamers (#767) (53739e0)
    add amazon-fr to stores. (#766) (02d7c47)
    store: support for canadacomputers (#772) (bd69e47)

Bug Fixes

    amazon: add 5800x and 5600x (#802) (167713b)
    bestbuy-ca: use proper selector (#801) (63d550c)
    config: correcting newline split for multiple user agents (#824) (f16a9fb)
    store: generate links only for selected stores (292e360), closes #694

Reverts

    correcting newline split for multiple user agents (af631c8), closes #824
    pipeline changes (efe0d64)

3.0.0 (2020-11-12)
⚠ BREAKING CHANGES

    removed duplicated Model

Features

    amazon: add more 3070s (#719) (dde9837)
    coolmod: add zen 3 (#754) (3270292)
    discord: add cart link to embed (#762) (ccb207a)
    store: support for kabum (amd and rtx 30 series) (#727) (23d061b)
    add option to disable auto add to cart (#759) (a5249ec)
    fix metadata in logging, lint prettier, typed Models (#747) (318e626)
    amazon-ca: add ps5 (#713) (2570056)
    amd: add 5950 config (#685) (31a3d8f)
    amd: add env vars and series filtering (#696) (df3b10b)
    galaxus: add zen 3 (#729) (4e086e9)
    mindfactory: add ryzen 5900x, 5950x (#720) (0362bf8)
    notification: add philips hue (#681) (c8a9b0b)
    notification: support for multiple phone numbers (#738) (9f28fe5)
    ps5: add console and digital edition (#709) (42ef7cf)
    store: add arlt and amd-de (#721) (38937f6)
    store: add game store, add ps5 for uk stores (#736) (0128718)
    store: add ps5 to german stores (#715) (2291b8e)
    store: add xbox series x and s (#732) (314f533)
    store: add zen 3 to german stores (#702) (71d5cb4)
    store: add zen 3 to more stores (#698) (760ddf5)
    store: Adds AM3 to microcenter (#707) (8a45905)
    target: add additional selector for 'ship it' (#737) (ab1fddf)
    add production scripts and better Dockerfile (0d14500), closes #710
    bring back ascii banner, but make it configurable (#703) (0a680e9)
    memoryexpress website support (#717) (c02241c)

Bug Fixes

    docker: copy web directory (#745) (0754fec)
    walmart: ps5 digital url (#763) (841647c)
    environment variables to match ryzen cpus (5db8348)
    revert to 14.15.0 until 15 is stable for tsc (2955ea7), closes #691

Code Refactoring

    removed duplicated Model (d19dd5a)

2.0.0 (2020-11-05)
⚠ BREAKING CHANGES

    update naming to streetmerchant

Features

    asus: realtime api (#675) (018784e)
    newegg-ca: realtime api (#674) (3c5407f)

Bug Fixes

    filterBrandsSeriesModels: always loop all stores (#680) (6ced13e)

Miscellaneous Chores

    update naming to streetmerchant (3f9b3c6)

1.7.0 (2020-11-03)
Features

    add deprecation notices (601742c)
    newegg realtime api (#664) (5b3e95a)

Bug Fixes

    banner: add version to docker image (#649) (1d2a33b)

1.6.0 (2020-10-29)
Features

    add series to Discord webhook (#618) (273d058)
    api: add rudimentary web control panel (#183) (373d1a9)
    store: add founders editions to notebooksbilliger.de (#593) (2e5db7a)
    store: add max price containers to multiple stores (#579) (f9c4c25)
    store: add new cards to german web shops (#597) (699de57)
    store: Add PCComponentes and Amazon-ES Stores. (#558) (062201f)
    store: support for azerty (#557) (58416e1)
    store: support for coolmod (#605) (c1dda4f)
    add meta to logger (#437) (ae6bc86)
    add alternate.nl support (#552) (aca6523)
    add asus-de store and asus 3080 tuf/oc to amazon-de (#436) (b4d8733)
    add caseking and proshop-de store (#521) (1aaa102)
    add coolblue store (#482) (5c61333)
    add german stores (#462) (85a07dc)
    add incognito mode (#534) (2b6457e)
    add link series to error message for better context (#265) (332b4a8)
    Add PagerDuty Integration (#565) (11ee0bf)
    add proshop-dk (#524) (dc2fcf5)
    add support for multiple browser user agents (#547) (10a81dc)
    add uk stores (#455) (b9b6b55)
    allow filtering per model by a specific series (#595) (a42418f)
    optional per store min and max page sleep time (#576) (503d76f)
    notification: add to field for email (#327) (8828dd1)
    store: add ttl for scan (#555) (4847725)
    add rog strix oc to amazon-de (#471) (e5909c5)
    add support for specifying smtp server (#458) (160ae37)
    allow multiple microcenter locations (#487) (2b0eab6)
    clear cookies and cache (#515) (1f89945), closes #417
    max price per series (#451) (8adc07a)
    mqtt alerts (#538) (68ff5bf)
    twitch chat notification, multiple telegram chat ids and german web shop overhaul (#528) (675f13a)
    docker: add docker and publish images to ghcr (#411) (c857985)
    notification: add at&t prepaid carrier (#425) (eb9d082)
    notification: add pushover priority setting (#186) (f277172)
    notification: add Twillio notification provider (#344) (f2f8d81)
    store: add pny (#295) (f6760d3)
    store: add 3090s to amazon-ca (#274) (e992cf4)
    store: add additional cards to all stores (#286) (d25a643)
    store: add amazon cards and cartUrls (#284) (d69189f)
    store: add asus strix oc to asus store (#385) (e55398e)
    store: add evga 3090 to newegg canada (#396) (313d176)
    store: add ftw3 ultra to microcenter (#448) (5109227)
    store: add gamestop (#390) (7148451)
    store: add models to bestbuy (#421) (4085136)
    store: add rog-strix-3080 to newegg-ca (#489) (207bc41)
    add norway to nvidia-api (#304) (eda6c85)
    configurable status code behaviours (#340) (3b7487e)
    enhanced lookup behaviour (#270) (b868d1a)
    in stock wait time per link now (c7a716f)
    low bandwidth mode (#294) (0aa7ab5)
    max price filtering (#383) (fd294d2)
    store: adds aorus master 3080 to newegg (#402) (fddc002)
    retry logic for nvidia session token and adding to cart (#347) (1bac1b9)
    support for proxy server (#352) (fdcd787)
    store: nvidia debug card for "product details" page (#337) (5b8d774)

Bug Fixes

    amazon.{nl,de} test urls (#345) (589fbbc)
    envOrNumber behavior (#364) (7d8897c)
    nvidia-api (#314) (8d8e5b5)
    add amazon-nl, captcha amazon-de, add ftw3 newegg (#293) (a2983eb)
    add status code 429 to bandh backOffStatusCodes (#404) (7a981e7)
    add support for stores label text to have uppercase letters (#526) (5ea7cc4)
    asus store links (#573) (f6db348)
    bestbuy label container selector precision (#491) (cbc3b0b)
    corrected norway locales (#356) (d2476dd)
    cyclical dependencies (ed970fc), closes #468
    denver microcenter name (#296) (349f55d)
    dutch stores components (#513) (586029c)
    gamestop false positives (#395) (d3bb507)
    in stock wait time (#325) (07bd246), closes #315
    max price getter updated to match .env (#516) (32f114b), closes #514 #510
    page sleep (#586) (a2af30b), closes #594 #576
    remove 3090 drid for DK/FI regions (#361) (f1d22d1)
    trim strings from comma-separated values (#472) (f7ed865)
    typo in maxPrice for 3090 (#496) (e073590)
    update gigabyte model vision oc (#550) (4fefe22)
    update new additions with web panel and sleep operations (#606) (61a23fe)
    update pushbullet import to match package (#637) (d7360f7)
    env: default LOG_LEVEL (9636572)
    notification: discord false triggers (#346) (3b90bbb)
    notification: sms subject output (#298) (03755d5)
    notifications: twilio client creation (#349) (5414b24)
    store: gamestop label.inStock (9e7976d)
    store: pccomponents model normalization (#563) (699e77d)
    updating amazon test model card to an in stock product (#492) (81daa7c)
    config: MAX_PRICE quotations (#426) (b7e5941)
    store: container names on nvidia (#333) (772de90)
    store: update inStock and maxPrice for newegg, newegg-ca (#433) (628cab1), closes #400

Reverts

    reduce false-positive during ci/cd (79b9bfe)

1.5.0 (2020-09-24)
Features

    filter models (#261) (e1b34a9)
    log: colors for console logs (#207) (0ad67fe)
    notification: add desktop notifications (#140) (722eaf3)
    notification: add pushbullet, add url with notifications (#226) (74490ea)
    notification: twitter integration (#224) (908ed35)
    store: add bannedSeller label for stores (#173) (71c6774)
    store: add amazon-de (#167) (8a70f14)
    store: add bestbuy.ca (#229) (22fd22f)
    store: add evga eu (#172) (605bdd7)
    store: add evga model (#220) (190388c)
    store: add microcenter store location config (#215) (d6a27c9)
    stores: add 3090 for bestbuy, newegg (#249) (dd45dba)
    stores: add 3090s for amazon-ca, bestbuy-ca, newegg-ca (#258) (482fb58)
    add chromium sandbox skipping (#209) (2065680)
    deprecate nvidia (api), add 3080 add 3090 (9f470f0)
    invert logic (#141) (6608a79)
    multiple discord roles and webhooks, qol for envs (#260) (8913879)
    store: add newegg.ca (#160) (76f5849), closes #159
    store: add office depot (#157) (0df2dcf)
    store: add zotac store (#214) (7875855)
    add delay on captcha to try and evade faster (#119) (4f83b3b)
    bestbuy bypass international splash, newegg add to cart (#153) (133a54f)
    card series filter, fix: newegg oosLabels (#120) (252459d)
    custom user agent (#121) (d9be3fe)
    include screenshot for emails + sms notifications (#144) (7191e03)
    load puppeteer faster, run stores in parallel (#83) (d1a5aa1)
    set country in config, login to nvidia when starting (#162) (ebd6091)
    temporarily pause requests if store has stock (#147) (6413144)
    update for complex add to cart, fix nvidia (#108) (3ea146d)
    notification: discord integration (#82) (a3fc07d)
    scraping: change lookup impl, add randomize sleep (#110) (dc0f710)
    store: add adorama (#104) (5b91065)
    store: add asus (#102) (a501cf7)

Bug Fixes

    store: adorama captcha config (#234) (9a53917)
    color logs and notification (76b28a6)
    notification: change discord ping visibility (#168) (9675c5b)
    store: bandh removed cards (#201) (6409646)
    rateLimitTimeout not being defaulted (#106) (28947be)
    check response for rate limiting (#58) (#98) (b7d9462)
    keep single Store from draining (e819e46)
    memory leak due to adblocker (#139) (0f6e570)
    nvidia: false positives (#132) (a75d214)
    newegg out-of-stock (#124) (770a13a)
    newegg out-of-stock labels (#134) (19c8f18)
    notification: wrong condition for sounds playing (#91) (103d96d)
    store: false positives for nvidia. (#85) (c65fa04)

1.4.0 (2020-09-19)
Features

    notification: add mint mobile carrier (#70) (8aba7ec)
    notification: add pushover (#55) (c85658b)
    notification: add telegram (#71) (393d5f6)
    notification: add telus sms (6be74a1)
    store: add amazon.ca, fix timeout (#75) (d4de1a4)
    webpage toggle, sound notification, fix evga links (#52) (a217409)

Performance Improvements

    browser abstraction (#68) (#81) (ebbdfe3)

1.3.0 (2020-09-19)
Features

    logging: add timestamp (#48) (6c3cd01)

Bug Fixes

    store: amazon captcha false-positives (#54) (5c9e0b6)
    evga xc3 ultra link (#56) (d907092)
    screenshot size, add screenshot config setting (#53) (7cfc7c7)
    sms carrier config, add google carrier (#44) (971fec2)

1.2.0 (2020-09-19)
Features

    ci: add npm run build (faad3e6)
    store: microcenter (#39) (edf17e9)
    add Amazon links (#26) (f0560ce)
    add email test, fix memory leak (#24) (a2fb973)
    more Best Buy AIBs (#41) (7d7bd18)
    page timeout (#22) (643045c)
    slack integration (#34) (c0a881a)
    sms notification for usa carriers (#40) (5a3636b)
    update to check if FE in-stock via Digital River (#29) (00ede13)

Bug Fixes

    small error in isOutOfStock logic (#33) (c2a210c)

1.1.0 (2020-09-18)
Features

    add conventional commits (#14) (eb4f5e0)
    add evga (#17) (#18) (6c65032)

Bug Fixes

    exception handling TimeoutError (#20) (#21) (00a0687)

1.0.0 (2020-09-18)
Features

    use ts, update cd, update README (#12) (e9fc0bf)
