### URL
`https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/clive-news-20ZZXXYY_AABBCC.json`

### Method
`GET`

### Sample request
`https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/clive-news-20200922_111138.json`

### Sample response

```json
[
  {
    "template_text": "<!DOCTYPE html>\n<html lang=\"en\">\n<head>\n  <meta charset=\"UTF-8\">\n  <title>Game Update</title>\n</head>\n<body>\n\n    <style> \n    @font-face {\n  font-family: Trajan;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 300;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Semibold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-ExtraLight.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-ExtraLight.otf\") format(\"opentype\"); }\n\nh1, h2, h3, h4, h5 {\n  font-family: \"Trajan\", sans-serif;\n  color: #a3a3a3;\n  font-weight: 200; }\n\np, label, ul, ol {\n  font-family: \"Hypatia\", serif;\n  color: #a3a3a3; }\n\nbody {\n  width: 900px;\n  background-color: #000;\n  padding: 0;\n  margin: 0; }\n\nheader {\n  width: 100%;\n  background-size: cover;\n  background-repeat: no-repeat; }\n\n.content-container {\n  position: fixed;\n  top: 0;\n  left: 0;\n  right: 0;\n  bottom: 0;\n  display: flex;\n  flex-direction: column; }\n\n.vertical-padding > * {\n  margin-top: 0;\n  margin-bottom: 20px;\n  padding: 0; }\n  .vertical-padding > *:last-child {\n    margin-bottom: 0; }\n\n.side-padding {\n  margin-left: 20px;\n  margin-right: 20px;\n  padding: 0; }\n\n.footer-logos {\n  margin: 20px 0;\n  width: 100%;\n  display: flex;\n  justify-content: center;\n  flex-wrap: wrap;\n  flex-shrink: 0; }\n  .footer-logos img {\n    padding: 0 10px; }\n\nheader {\n  width: 100%;\n  height: auto;\n  background-size: cover;\n  background-repeat: no-repeat;\n  flex-shrink: 0; }\nheader img {\n  width: 100%;\n}\n\n.body-content-container {\n  flex-grow: 1;\n  position: relative;\n  margin-top: 20px;\n  display: flex; }\n  .body-content-container:after {\n    content: '';\n    height: 20px;\n    background: linear-gradient(transparent, #000);\n    position: absolute;\n    bottom: 0;\n    left: 0;\n    width: 100%;\n    margin-bottom: -2px; }\n  .body-content-container:before {\n    content: '';\n    height: 20px;\n    background: linear-gradient(#000, transparent);\n    position: absolute;\n    top: 0;\n    left: 0;\n    width: 100%;\n    margin-top: -2px; }\n  .body-content-container h1 {\n    font-size: 35px;\n    text-align: center;\n    padding: 0;\n    margin: 0 0 20px 0; }\n  .body-content-container .scrollable-area {\n    padding-top: 10px;\n    padding-bottom: 20px;\n    overflow-y: auto;\n    flex-shrink: 1;\n    width: 100%; }\n    .body-content-container .scrollable-area p, ul, ol {\n      text-align: center; }\n\n </style>\n\n    <div class=\"content-container\">\n\n      <header>\n        <img src=\"$$header_image$$\">\n      </header>\n\n        <div class=\"body-content-container side-padding\">\n            <div class=\"scrollable-area vertical-padding\">\n                \n    <h1>$$heading$$</h1>\n\n    <p>$$p1$$</p>\n\n    <p>$$p2$$</p>\n\n    <p>$$p3$$</p>\n\n    <p>$$p4$$</p>\n\n    <p>$$p5$$</p>\n\n    <p>$$p6$$</p>\n    \n    <p>$$p7$$</p>\n    \n    <p>$$p8$$</p>\n\n    <p>$$p9$$</p>\n\n    <p>$$p10$$</p>\n\n            </div>\n        </div>\n    </div>\n</body>\n</html>\n",
    "id": "20200305_090505",
    "target": "client",
    "category": "general",
    "template_id": "game_update",
    "template_fields": {
      "en": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/Helmets-Shortened.png",
        "heading": "Total War: Arena - Technical Alpha #1",
        "p1": "Welcome to Total War: Arena, Commander!",
        "p2": "The first round of Pioneer testing is officially open! Let's transform ourselves into the greatest legendary commander in history, join the epic battle, and conquer the mighty battlefield of all-out war!",
        "p3": "Test time: March 5th to March 8th, daily 18: 00 ~ 22: 00",
        "p4": "Pioneer Test only opens some game content, including:",
        "p5": "1) Unlock the four main camps of Rome / Greece / Barbarian / Carthage to become legendary commanders.",
        "p6": "2) Open Tier 1 ~ Tier 6, which are the base units of all forces, and create your own team.",
        "p7": "3) The new 10v10 stronghold mode, captures the flag to make the battle rhythm closer and smoother.",
        "p8": "4) Built-in battlefield voice, and develop meticulous battle plans alongside comrades-in-arms.",
        "p9": "5) The premium account is unlocked by default, and the double bonus is unobstructed.",
        "p10": ""
      },
      "cn": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/Helmets-Shortened.png",
        "heading": "「全面战争：竞技场」首轮先锋测试",
        "p1": "欢迎来到「全面战争：竞技场」，指挥官！",
        "p2": "首轮先锋测试正式开启！让我们一起化身史上最伟大的传奇指挥官，加入名垂千古的史诗战役，征服全面战争的万人恢弘战场！",
        "p3": "测试时间：3月5日~3月8日，每日18:00~22:00",
        "p4": "您在测试过程中如果遇到任何问题或BUG，请及时通过启动器中的「问题反馈」提交或在游戏中按ESC点击「联系客服」。\n在竞技场体验过程中，有任何关于游戏内容和玩法的意见及建议，都可以通过客服反馈或加入官方Q群（630717459）进行讨论交流。\n同时希望每名指挥官都能积极填写本次测试问卷（启动器-玩家反馈收集），我们将与开发商共同努力，为大家打造更优秀的「全面战争：竞技场」！",
        "p5": "先锋测试仅开放部分游戏内容，包括：",
        "p6": "1)     解锁罗马/希腊/蛮族/迦太基四大阵营，化身传奇指挥官。",
        "p7": "2)     开放所有势力基础兵种Tier1~Tier6，创建属于你的队伍。",
        "p8": "3)     全新10v10据点模式，夺旗玩法让战斗节奏更加紧密畅快。",
        "p9": "4)     内置战场语音，与战友并肩制定缜密的作战计划",
        "p10": "5)     默认解锁高级账户，双倍加成畅通无阻。"
      }
    },
    "languages": [
      "en",
      "cn"
    ],
    "start_time": "2020-03-05T08:00:16.000Z",
    "end_time": "2020-03-08T13:00:23.000Z",
    "preview_language": "cz",
    "start_time_unix": "1583395216",
    "end_time_unix": "1583672423"
  },
  {
    "template_text": "<!DOCTYPE html>\n<html lang=\"en\">\n<head>\n  <meta charset=\"UTF-8\">\n  <title>Game Update</title>\n</head>\n<body>\n\n    <style> \n    @font-face {\n  font-family: Trajan;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 300;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Semibold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-ExtraLight.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-ExtraLight.otf\") format(\"opentype\"); }\n\nh1, h2, h3, h4, h5 {\n  font-family: \"Trajan\", sans-serif;\n  color: #a3a3a3;\n  font-weight: 200; }\n\np, label, ul, ol {\n  font-family: \"Hypatia\", serif;\n  color: #a3a3a3; }\n\nbody {\n  width: 900px;\n  background-color: #000;\n  padding: 0;\n  margin: 0; }\n\nheader {\n  width: 100%;\n  background-size: cover;\n  background-repeat: no-repeat; }\n\n.content-container {\n  position: fixed;\n  top: 0;\n  left: 0;\n  right: 0;\n  bottom: 0;\n  display: flex;\n  flex-direction: column; }\n\n.vertical-padding > * {\n  margin-top: 0;\n  margin-bottom: 20px;\n  padding: 0; }\n  .vertical-padding > *:last-child {\n    margin-bottom: 0; }\n\n.side-padding {\n  margin-left: 20px;\n  margin-right: 20px;\n  padding: 0; }\n\n.footer-logos {\n  margin: 20px 0;\n  width: 100%;\n  display: flex;\n  justify-content: center;\n  flex-wrap: wrap;\n  flex-shrink: 0; }\n  .footer-logos img {\n    padding: 0 10px; }\n\nheader {\n  width: 100%;\n  height: auto;\n  background-size: cover;\n  background-repeat: no-repeat;\n  flex-shrink: 0; }\nheader img {\n  width: 100%;\n}\n\n.body-content-container {\n  flex-grow: 1;\n  position: relative;\n  margin-top: 20px;\n  display: flex; }\n  .body-content-container:after {\n    content: '';\n    height: 20px;\n    background: linear-gradient(transparent, #000);\n    position: absolute;\n    bottom: 0;\n    left: 0;\n    width: 100%;\n    margin-bottom: -2px; }\n  .body-content-container:before {\n    content: '';\n    height: 20px;\n    background: linear-gradient(#000, transparent);\n    position: absolute;\n    top: 0;\n    left: 0;\n    width: 100%;\n    margin-top: -2px; }\n  .body-content-container h1 {\n    font-size: 35px;\n    text-align: center;\n    padding: 0;\n    margin: 0 0 20px 0; }\n  .body-content-container .scrollable-area {\n    padding-top: 10px;\n    padding-bottom: 20px;\n    overflow-y: auto;\n    flex-shrink: 1;\n    width: 100%; }\n    .body-content-container .scrollable-area p, ul, ol {\n      text-align: center; }\n\n </style>\n\n    <div class=\"content-container\">\n\n      <header>\n        <img src=\"$$header_image$$\">\n      </header>\n\n        <div class=\"body-content-container side-padding\">\n            <div class=\"scrollable-area vertical-padding\">\n                \n    <h1>$$heading$$</h1>\n\n    <p>$$p1$$</p>\n\n    <p>$$p2$$</p>\n\n    <p>$$p3$$</p>\n\n    <p>$$p4$$</p>\n\n    <p>$$p5$$</p>\n\n    <p>$$p6$$</p>\n    \n    <p>$$p7$$</p>\n    \n    <p>$$p8$$</p>\n\n    <p>$$p9$$</p>\n\n    <p>$$p10$$</p>\n\n            </div>\n        </div>\n    </div>\n</body>\n</html>\n",
    "id": "20200421_083740",
    "target": "client",
    "category": "general",
    "template_id": "game_update",
    "template_fields": {
      "en": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/in-game%20news900x255.png",
        "heading": "Total War: Arena - Technical Alpha #2",
        "p1": "Welcome to Total War: Arena, Commander!",
        "p2": "The second Technical Alpha is officially open! Let's transform ourselves into the greatest legendary commander in history, join the epic battle, and conquer the mighty battlefield of all-out war!",
        "p3": "Dates/times: April 29th to May 5th, Daily 09:00 ~ 14:00 (BST).",
        "p4": "Additions include:",
        "p5": "1)\tRemoval of tier restrictions, enabling tiers 1 to 10 for all available factions.",
        "p6": "2)\tAdditional game mode (territory mode) hints and tips while matchmaking.",
        "p7": "3)\tGame mode, unit and map balancing alterations",
        "p8": "4)\tA number of bug fixes and minor improvements",
        "p9": "For additional details regarding this patch, please see our Patch Notes.",
        "p10": ""
      },
      "cn": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/in-game%20news900x255.png",
        "heading": "「全面战争：竞技场」先锋测试2/2",
        "p1": "欢迎加入竞技场，指挥官们！",
        "p2": "第二轮先锋测试正式开场！让我们一起化身史上最伟大的传奇指挥官，加入名垂千古的史诗战役，征服全面战争的万人恢弘战场！",
        "p3": "测试时间：4月29日-5月5日，每天17: 00 ~ 22: 00",
        "p4": "测试内容：",
        "p5": "1)\t全阵营1-10级单位开放，组建军事力量更自由。",
        "p6": "2)\t罗马/希腊/蛮族/迦太基四大阵营，化身传奇指挥官。",
        "p7": "3)\t改善10v10据点模式，玩法优化酣畅战斗。",
        "p8": "4)\t战斗细节优化，兵种平衡性调整。",
        "p9": "5)\t内置战场语音，与战友并肩。",
        "p10": "您在测试过程中如果遇到任何问题或BUG，请及时通过启动器中的「问题反馈」提交或在游戏中按ESC点击「联系客服」。\n在竞技场体验过程中，有任何关于游戏内容和玩法的意见及建议，都可以通过客服反馈或加入官方Q群（630717459）进行讨论交流。\n\n版本内容详情请见官网【版本更新说明】"
      }
    },
    "languages": [
      "en",
      "cn"
    ],
    "start_time": "2020-04-20T08:00:00.000Z",
    "end_time": "2020-05-05T22:00:00.000Z",
    "preview_language": "cz",
    "start_time_unix": "1587369600",
    "end_time_unix": "1588716000"
  },
  {
    "template_text": "<!DOCTYPE html>\n<html lang=\"en\">\n<head>\n  <meta charset=\"UTF-8\">\n  <title>Game Update</title>\n</head>\n<body>\n\n    <style> \n    @font-face {\n  font-family: Trajan;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 300;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Semibold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-ExtraLight.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-ExtraLight.otf\") format(\"opentype\"); }\n\nh1, h2, h3, h4, h5 {\n  font-family: \"Trajan\", sans-serif;\n  color: #a3a3a3;\n  font-weight: 200; }\n\np, label, ul, ol {\n  font-family: \"Hypatia\", serif;\n  color: #a3a3a3; }\n\nbody {\n  width: 900px;\n  background-color: #000;\n  padding: 0;\n  margin: 0; }\n\nheader {\n  width: 100%;\n  background-size: cover;\n  background-repeat: no-repeat; }\n\n.content-container {\n  position: fixed;\n  top: 0;\n  left: 0;\n  right: 0;\n  bottom: 0;\n  display: flex;\n  flex-direction: column; }\n\n.vertical-padding > * {\n  margin-top: 0;\n  margin-bottom: 20px;\n  padding: 0; }\n  .vertical-padding > *:last-child {\n    margin-bottom: 0; }\n\n.side-padding {\n  margin-left: 20px;\n  margin-right: 20px;\n  padding: 0; }\n\n.footer-logos {\n  margin: 20px 0;\n  width: 100%;\n  display: flex;\n  justify-content: center;\n  flex-wrap: wrap;\n  flex-shrink: 0; }\n  .footer-logos img {\n    padding: 0 10px; }\n\nheader {\n  width: 100%;\n  height: auto;\n  background-size: cover;\n  background-repeat: no-repeat;\n  flex-shrink: 0; }\nheader img {\n  width: 100%;\n}\n\n.body-content-container {\n  flex-grow: 1;\n  position: relative;\n  margin-top: 20px;\n  display: flex; }\n  .body-content-container:after {\n    content: '';\n    height: 20px;\n    background: linear-gradient(transparent, #000);\n    position: absolute;\n    bottom: 0;\n    left: 0;\n    width: 100%;\n    margin-bottom: -2px; }\n  .body-content-container:before {\n    content: '';\n    height: 20px;\n    background: linear-gradient(#000, transparent);\n    position: absolute;\n    top: 0;\n    left: 0;\n    width: 100%;\n    margin-top: -2px; }\n  .body-content-container h1 {\n    font-size: 35px;\n    text-align: center;\n    padding: 0;\n    margin: 0 0 20px 0; }\n  .body-content-container .scrollable-area {\n    padding-top: 10px;\n    padding-bottom: 20px;\n    overflow-y: auto;\n    flex-shrink: 1;\n    width: 100%; }\n    .body-content-container .scrollable-area p, ul, ol {\n      text-align: center; }\n\n </style>\n\n    <div class=\"content-container\">\n\n      <header>\n        <img src=\"$$header_image$$\">\n      </header>\n\n        <div class=\"body-content-container side-padding\">\n            <div class=\"scrollable-area vertical-padding\">\n                \n    <h1>$$heading$$</h1>\n\n    <p>$$p1$$</p>\n\n    <p>$$p2$$</p>\n\n    <p>$$p3$$</p>\n\n    <p>$$p4$$</p>\n\n    <p>$$p5$$</p>\n\n    <p>$$p6$$</p>\n    \n    <p>$$p7$$</p>\n    \n    <p>$$p8$$</p>\n\n    <p>$$p9$$</p>\n\n    <p>$$p10$$</p>\n\n            </div>\n        </div>\n    </div>\n</body>\n</html>\n",
    "id": "20200430_095826",
    "target": "client",
    "category": "general",
    "template_id": "game_update",
    "template_fields": {
      "en": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/Helmets-Shortened.png",
        "heading": "Announcement on Issues and Rewards",
        "p1": "Dear Commanders,",
        "p2": "We would like to thank you for participating in our Technical Alpha #2. We appreciate your valuable feedback during the test. As a thank you, all players who log into the game between 17:00 to 22:00 on 30th of April (Beijing Time) will receive an additional 1 day premium account bonus.",
        "p3": "\nKnown issues:",
        "p4": "\nError messages caused by missing files\n\nSome players have manually deleted the launcher and/or game folder of the first Technical Alpha #1 test, which leaves old files which is preventing the game from being updated correctly.\n\nSolution: The NetEase launcher team is trying to fix the issue ASAP. Unfortunately until a fix is rolled out the only temporary solution is to apply a manually workaround (delete local game client files and reinstall the game client).\n\n \n",
        "p5": "\nArbitration Failures / Delayed Battle Results / Matchmaking Failures\n\nSolution: We've pushed a server update which should fix these issues. Our developers are continuously monitoring this situation closely.\n\n \n",
        "p6": "\nDisplay error in 4K resolution\n\nSolution: Change the resolution scaling to 100% and restart the game client. The launcher will continue to be updated as well.\n\n ",
        "p7": "Party Rewards\n\nSolution: The developers are aware of the issue and have temporarily removed the bonus party experience as this was the cause of the issue while a fix is investigated.\n\n ",
        "p8": "\nMatchmaking Times\n\nAs users progress through the game our player tier distribution will change. If you do experience matchmaking times longer than a few minutes, we would advise you to select PvE and a lower tier to ensure a fast battle.\n\n ",
        "p9": "Once again we appreciate your patience and support, we will continue monitoring the test closely and all your valuable feedback is appreciated. Official Arena QQ Group Number: 630717459; NetEase CS Number: NEBCKF",
        "p10": "\nWe wish you a happy Arena experience!"
      },
      "cn": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/Helmets-Shortened.png",
        "heading": "4月30日全员高级账号奖励公告",
        "p1": "尊敬的指挥官们",
        "p2": "感谢所有人加入本轮先锋二测！感谢大家积极反馈体验中的各类问题，帮助我们持续修缮竞技场。\n\n4月30日 17:00~22:00测试期间，所有登录玩家将获得高级账户权限，解锁双倍战斗加成。",
        "p3": "目前已知问题做如下汇总：",
        "p4": "缺失文件导致的各类客户端错误提示\n\n由于部分玩家手动删除了首测版本的启动器或游戏安装目录，存在旧版本文件残留，从而影响游戏版本更新。\n\n解决方案：启动器团队正在努力进行修复（当检测到旧版本残留文件时，进行重复校验及文件修复）未修复前需要玩家以手动方式处理解决。",
        "p5": "对局结算延迟/仲裁失败/匹配失败\n\n解决方案：开发商积极排查并确定问题来源，目前已完成服务端设置调整，将在后续测试期间持续观察竞技场内的战斗情况。",
        "p6": "4K分辨率屏幕下出现的显示错误\n\n解决方案：建议在PC显示设置中，将布局缩放暂时调整为100%，并重启客户端。同时启动器将会针对此类显示问题进行持续优化。",
        "p7": "组队收益功能错误\n\n解决方案：我们已了解目前组队战斗收益存在的BUG，在修复完成前，我们暂时将组队战斗收益恢复为100%。",
        "p8": "匹配时间问题\n\n解决方案：随着玩家在游戏中等级的提升，各个等级玩家的分布将会不断变化。如果你的匹配时间过长，我们建议你使用低等级的兵种或者进行PVE战斗来提升匹配速度。",
        "p9": "再次感谢所有指挥官的付出与支持，欢迎大家继续积极反馈在竞技场中的任何疑问或体验反馈，我们都将倾力解决。\n\n官方Q群：630717459  宝船客服服务号：NEBCKF",
        "p10": "祝，竞技场战斗愉快！"
      }
    },
    "languages": [
      "en",
      "cn"
    ],
    "start_time": "2020-04-30T09:00:00.000Z",
    "end_time": "2020-05-01T22:00:00.000Z",
    "preview_language": "cz",
    "start_time_unix": "1588237200",
    "end_time_unix": "1588370400"
  },
  {
    "template_text": "<!DOCTYPE html>\n<html lang=\"en\">\n<head>\n  <meta charset=\"UTF-8\">\n  <title>Game Update</title>\n</head>\n<body>\n\n    <style> \n    @font-face {\n  font-family: Trajan;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 300;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Semibold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Trajan;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/TrajanPro3-ExtraLight.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Regular.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: bold;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Bold.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 200;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-Light.otf\") format(\"opentype\"); }\n\n@font-face {\n  font-family: Hypatia;\n  font-weight: 100;\n  src: url(\"$$template_asset_url$$/fonts/HypatiaSansPro-ExtraLight.otf\") format(\"opentype\"); }\n\nh1, h2, h3, h4, h5 {\n  font-family: \"Trajan\", sans-serif;\n  color: #a3a3a3;\n  font-weight: 200; }\n\np, label, ul, ol {\n  font-family: \"Hypatia\", serif;\n  color: #a3a3a3; }\n\nbody {\n  width: 900px;\n  background-color: #000;\n  padding: 0;\n  margin: 0; }\n\nheader {\n  width: 100%;\n  background-size: cover;\n  background-repeat: no-repeat; }\n\n.content-container {\n  position: fixed;\n  top: 0;\n  left: 0;\n  right: 0;\n  bottom: 0;\n  display: flex;\n  flex-direction: column; }\n\n.vertical-padding > * {\n  margin-top: 0;\n  margin-bottom: 20px;\n  padding: 0; }\n  .vertical-padding > *:last-child {\n    margin-bottom: 0; }\n\n.side-padding {\n  margin-left: 20px;\n  margin-right: 20px;\n  padding: 0; }\n\n.footer-logos {\n  margin: 20px 0;\n  width: 100%;\n  display: flex;\n  justify-content: center;\n  flex-wrap: wrap;\n  flex-shrink: 0; }\n  .footer-logos img {\n    padding: 0 10px; }\n\nheader {\n  width: 100%;\n  height: auto;\n  background-size: cover;\n  background-repeat: no-repeat;\n  flex-shrink: 0; }\nheader img {\n  width: 100%;\n}\n\n.body-content-container {\n  flex-grow: 1;\n  position: relative;\n  margin-top: 20px;\n  display: flex; }\n  .body-content-container:after {\n    content: '';\n    height: 20px;\n    background: linear-gradient(transparent, #000);\n    position: absolute;\n    bottom: 0;\n    left: 0;\n    width: 100%;\n    margin-bottom: -2px; }\n  .body-content-container:before {\n    content: '';\n    height: 20px;\n    background: linear-gradient(#000, transparent);\n    position: absolute;\n    top: 0;\n    left: 0;\n    width: 100%;\n    margin-top: -2px; }\n  .body-content-container h1 {\n    font-size: 35px;\n    text-align: center;\n    padding: 0;\n    margin: 0 0 20px 0; }\n  .body-content-container .scrollable-area {\n    padding-top: 10px;\n    padding-bottom: 20px;\n    overflow-y: auto;\n    flex-shrink: 1;\n    width: 100%; }\n    .body-content-container .scrollable-area p, ul, ol {\n      text-align: center; }\n\n </style>\n\n    <div class=\"content-container\">\n\n      <header>\n        <img src=\"$$header_image$$\">\n      </header>\n\n        <div class=\"body-content-container side-padding\">\n            <div class=\"scrollable-area vertical-padding\">\n                \n    <h1>$$heading$$</h1>\n\n    <p>$$p1$$</p>\n\n    <p>$$p2$$</p>\n\n    <p>$$p3$$</p>\n\n    <p>$$p4$$</p>\n\n    <p>$$p5$$</p>\n\n    <p>$$p6$$</p>\n    \n    <p>$$p7$$</p>\n    \n    <p>$$p8$$</p>\n\n    <p>$$p9$$</p>\n\n    <p>$$p10$$</p>\n\n            </div>\n        </div>\n    </div>\n</body>\n</html>\n",
    "id": "20200921_161543",
    "target": "client",
    "category": "general",
    "template_id": "game_update",
    "template_fields": {
      "en": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/900x255.png",
        "heading": "Six major player benefits to celebrate Commercial Launch",
        "p1": "Commanders! Let us become the greatest legendary generals in history, form a team to command thousands of troops, and experience the grand battlefield of tens of thousands of people on the same screen unique to Total War!",
        "p2": "【EVENT : Welcome to ARENA】",
        "p3": "Log in to the arena for the first time, and you can get the \"Arena Recruitment Package: Silver Coins x 50000, Exclusive Portrait x1\"!",
        "p4": "【EVENT : War supplies for battle 】",
        "p5": "Players who login in the game every day and are online for more than 30 mins a day, will get each day’s check in rewards, during National Day holiday there will be double bonus!",
        "p6": "【EVENT : Lead a grand army and achieve victory 】",
        "p7": "Accumulate sign-in rewards for specified number of days, and receive extra gifts such as gold and free experience!",
        "p8": "【EVENT : Army equipment discount 】",
        "p9": "Two discounted packages will be available, plus six levels of rewards based on first payment.",
        "p10": ""
      },
      "cn": {
        "template_asset_url": "https://s3-eu-west-1.amazonaws.com/public.arenatw.co.uk/news/assets",
        "header_image": "https://s3.cn-north-1.amazonaws.com.cn/twa-game-data.arena.neshgameservers.com/news/images/Arena%20NE%20clive/900x255.png",
        "heading": "六大庆典福利 喜迎不删档！",
        "p1": "史诗级战争策略大作「全面战争：竞技场」9月23日正式不删档上线！指挥官们！让我们一起化身史上最伟大的传奇将领，组建队伍统率千军，感受全面战争独有的万人同屏恢弘战场！",
        "p2": "【EVENT 欢迎加入竞技场】",
        "p3": "首次登录竞技场，即可获得「竞技场招募礼包：银币x50000、专属头像x1」！",
        "p4": "【EVENT 粮草补给 时刻助战】",
        "p5": "每日登入游戏并累计在线满30分钟，即可获得签到奖励，国庆期间更有超额翻倍奖励！",
        "p6": "【EVENT 统帅千军 凯旋嘉奖】",
        "p7": "累计签到达成指定天数，赠送金币、自由经验值等额外好礼！",
        "p8": "【EVENT 战备资源 折扣钜惠】",
        "p9": "两大特惠资源礼包上架，金币商城开启六档首充返利！",
        "p10": ""
      }
    },
    "languages": [
      "en",
      "cn"
    ],
    "start_time": "2020-09-21T08:15:47.000Z",
    "end_time": "2020-10-21T16:00:00.000Z",
    "preview_language": "cz",
    "start_time_unix": "1600676147",
    "end_time_unix": "1603296000"
  }
]
```
