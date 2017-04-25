
<!-- README.md is generated from README.Rmd. Please edit that file -->
emo(ji)
=======

The goal of emo(ji) is to make it very easy to insert emoji into RMarkdown documents.

Emoji data from <https://github.com/muan/emojilib/>.

Installation
------------

You can install emo from github with:

``` r
# install.packages("devtools")
devtools::install_github("hadley/emo")
```

Example
-------

You can either refer to emoji by their name (which is unique):

``` r
emo::ji("poop")
```

💩

Or by a keyword. Keywords are not unique so emo::ji will pick one for you at random.

``` r
emo::ji("face")
```

😄

``` r
emo::ji("face")
```

😲

``` r
emo::ji("face")
```

😣

Often you'll use inline like `r emo::ji("smile")`

Keywords
--------

These are all keywords with more than one emoji associated with them.

    #> :( :  😞😟
    #> :) :  😃😄
    #> :D :  😀😃😄
    #> 3 :  😗3️⃣
    #> 80s :  💾📼
    #> 90s :  💽💾💿📼📟
    #> 911 :  👮‍♀️👮🚑🚨🚔🆘
    #> accessories :  👒👝👛👜👓🕶⌚
    #> affection :  😍😘😙😚😻👫💑👩‍❤️‍👩👨‍❤️‍👨💋🏩💒💌💛💚💙💜💕💞💓💗💖💘
    #> agree :  👍🉑✅🆗☑️
    #> air :  🌬💨
    #> airport :  🛫🛬🛄
    #> alcohol :  🍺🍻🥂🍷🥃🍸🍹🍶
    #> alert :  🚨⚠️
    #> alphabet :  🅰️🅱️🆎🆑🅾️Ⓜ️🅿️ℹ️🔤🔡🔠®️
    #> american :  🗽🇦🇸
    #> angry :  😡👿👊💢NANANANA
    #> animal :  😺😸😹😻😼😽🙀😿😾🐶🐱🐭🐹🐰🦊🐻🐼🐨🐯🦁🐮🐷🐽🐸🦑🐙🦐🐵🦍🙈🙉🙊🐒🐔🐧🐦🐤🐣🐥🦆🦅🦉🦇🐺🐗🐴🦄🐝🐛🦋🐌🐞🐜🕷🦂🦀🐍🦎🐢🐠🐟🐡🐬🦈🐳🐋🐊🐆🐅🐃🐂🐄🦌🐪🐫🐘🦏🐐🐏🐑🐎🐖🐀🐁🐓🦃🕊🐕🐩🐈🐇🐿🐾🐉🐲🕸🍤🏇NANA
    #> answer :  ✅✔️
    #> arab :  🇸🇾🇦🇪
    #> arabs :  👳‍♀️👳
    #> arachnid :  🕷🦂🕸
    #> architect :  📐📏
    #> arrest :  👮‍♀️👮⛓
    #> arrow :  ♻️🔚🔙🔛🔜
    #> art :  🏛🖌
    #> asia :  🎑🗾
    #> assembly :  👩‍🏭👨‍🏭
    #> astrology :  ⛎♈♉♊♋♌♍♎♏♐♑♒♓
    #> athlete :  🏊‍♀️🏊
    #> aviator :  👩‍✈️👨‍✈️
    #> aw :  😦🇦🇼
    #> award :  🏆🏅🎖🥇🥈🥉
    #> awesome :  👍🌟✨❇️
    #> baby :  🤰🐣🐥
    #> back :  ⬅️↩️
    #> bad :  📉⛔〽️
    #> bag :  🎒👝
    #> balance :  🤹‍♀️🤹‍♂️☯
    #> balls :  🏀🏈⚾🎾🏐
    #> banner :  🎏🇦🇫🇦🇽🇦🇱🇩🇿🇦🇸🇦🇩🇦🇴🇦🇮🇦🇶🇦🇬🇦🇷🇦🇲🇦🇼🇦🇺🇦🇹🇦🇿🇧🇸🇧🇭🇧🇩🇧🇧🇧🇾🇧🇪🇧🇿🇧🇯🇧🇲🇧🇹🇧🇴🇧🇶🇧🇦🇧🇼🇧🇷🇮🇴🇻🇬🇧🇳🇧🇬🇧🇫🇧🇮🇨🇻🇰🇭🇨🇲🇨🇦🇮🇨🇰🇾🇨🇫🇹🇩🇨🇱🇨🇳🇨🇽🇨🇨🇨🇴🇰🇲🇨🇬🇨🇩🇨🇰🇨🇷🇭🇷🇨🇺🇨🇼🇨🇾🇨🇿🇩🇰🇩🇯🇩🇲🇩🇴🇪🇨🇪🇬🇸🇻🇬🇶🇪🇷🇪🇪🇪🇹🇪🇺🇫🇰🇫🇴🇫🇯🇫🇮🇫🇷🇬🇫🇵🇫🇹🇫🇬🇦🇬🇲🇬🇪🇩🇪🇬🇭🇬🇮🇬🇷🇬🇱🇬🇩🇬🇵🇬🇺🇬🇹🇬🇬🇬🇳🇬🇼🇬🇾🇭🇹🇭🇳🇭🇰🇭🇺🇮🇸🇮🇳🇮🇩🇮🇷🇮🇶🇮🇪🇮🇲🇮🇱🇮🇹🇨🇮🇯🇲🇯🇵🇯🇪🇯🇴🇰🇿🇰🇪🇰🇮🇽🇰🇰🇼🇰🇬🇱🇦🇱🇻🇱🇧🇱🇸🇱🇷🇱🇾🇱🇮🇱🇹🇱🇺🇲🇴🇲🇰🇲🇬🇲🇼🇲🇾🇲🇻🇲🇱🇲🇹🇲🇭🇲🇶🇲🇷🇲🇺🇾🇹🇲🇽🇫🇲🇲🇩🇲🇨🇲🇳🇲🇪🇲🇸🇲🇦🇲🇿🇲🇲🇳🇦🇳🇷🇳🇵🇳🇱🇳🇨🇳🇿🇳🇮🇳🇪🇳🇬🇳🇺🇳🇫🇲🇵🇰🇵🇳🇴🇴🇲🇵🇰🇵🇼🇵🇸🇵🇦🇵🇬🇵🇾🇵🇪🇵🇭🇵🇳🇵🇱🇵🇹🇵🇷🇶🇦🇷🇪🇷🇴🇷🇺🇷🇼🇧🇱🇸🇭🇰🇳🇱🇨🇵🇲🇻🇨🇼🇸🇸🇲🇸🇹🇸🇦🇸🇳🇷🇸🇸🇨🇸🇱🇸🇬🇸🇽🇸🇰🇸🇮🇸🇧🇸🇴🇿🇦🇬🇸🇰🇷🇸🇸🇪🇸🇱🇰🇸🇩🇸🇷🇸🇿🇸🇪🇨🇭🇸🇾🇹🇼🇹🇯🇹🇿🇹🇭🇹🇱🇹🇬🇹🇰🇹🇴🇹🇹🇹🇳🇹🇷🇹🇲🇹🇨🇹🇻🇺🇬🇺🇦🇦🇪🇬🇧🇺🇸🇻🇮🇺🇾🇺🇿🇻🇺🇻🇦🇻🇪🇻🇳🇼🇫🇪🇭🇾🇪🇿🇲🇿🇼
    #> bathroom :  🛀🚽🚿🛁
    #> beach :  😎👙👣🐙🐠🐬🦈🌴🌺🐚☀️🍥🍹🏄‍♀️🏄
    #> beef :  🐮🐂🐄🍔
    #> beverage :  🥛🍺🍻🥂🍷🥃🍸🍹🍶☕
    #> bike :  🚴‍♀️🚴🚵‍♀️🚵
    #> bill :  💵💳
    #> bills :  💸💷
    #> bin :  🗑🚯
    #> biologist :  👩‍🔬👨‍🔬
    #> bird :  🐔🐤🐣🐥🦆🦅🦉🦃🕊🍗
    #> birthday :  🎈🎁🎊🎉
    #> blonde :  👱‍♀️👱
    #> blue :  🙆‍♂️💎💠🌀
    #> blue-square :  🚇🈳🏧🈂️🛂🛃🛄🛅♿🚭🚾🅿️🚰🚹🚻🚮🎦📶🈁🆖🆗🆙🆒🆕🆓0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟🔢▶️⏸⏭⏹⏺⏯⏩⏪🔀🔂◀️🔼🔽⏫⏬➡️⬅️⬆️⬇️↗️↘️↙️↖️↕️🔄↪️↩️⤴️⤵️#️⃣ℹ️🔤🔡🔠🔣🔝
    #> blush :  ☺️😳
    #> boat :  ⛴🛶⚓
    #> booze :  🍺🍻🍷🥃🍸🍹🍶
    #> border :  🎌🛃
    #> bottom :  🔽⏬⬇️⤵️🔻
    #> box :  🍱📦
    #> boy :  👶👱👲🤴🕺🙇🤦🤷‍♂️💁‍♂️🙅‍♂️🙆‍♂️🙋‍♂️🙎‍♂️🙍‍♂️💇‍♂️💆‍♂️
    #> bread :  🥐🥖
    #> breakfast :  🍞🥚🥓🥞🍳🍵
    #> bride :  👰💒
    #> british :  💂‍♀️💂🍵💷🇮🇴🇻🇬🇬🇧
    #> broadcast :  🔈🔉🔊
    #> bubble :  💭💬
    #> buddhism :  🕉☸
    #> bug :  🐝🐜
    #> build :  👷‍♀️👷⛑🔨⚒🛠
    #> building :  🏭🏰🏯🏠🏚🏢🏬🏣🏤🏥🏦🏨🏪🏫⛪
    #> buildings :  🌆🏘
    #> bunny :  👯👯‍♂️🐰
    #> business :  👩‍💼👨‍💼👔💼⛳🏌️‍♀️🏌🕴🏦📈📉📇🗃📁🗂〽️
    #> button :  ⚫🔵⬛⬜◼️◾◽
    #> ca :  🍁🇨🇦
    #> calculation :  ➕➖➗✖️
    #> camping :  ⛺🔦
    #> car :  🚌🚐🚜🚘
    #> cards :  🃏♠️♣️♥️♦️
    #> carnival :  🎪🎡🎢🎠🎆
    #> cars :  🚕🚓🚒🚚🚛🚖🅿️
    #> cash :  🏦🏧
    #> cat :  🐯🐾
    #> cats :  😺😸😹😻😼😽🙀😿😾🐈
    #> celebration :  🙌🎄🍾🎈🎉
    #> chatting :  💬🗨
    #> chef :  👩‍🍳👨‍🍳
    #> chemist :  👩‍🔬👨‍🔬
    #> chicken :  🐤🐣🐥🐓🥚🍗
    #> child :  👶👪👨‍👩‍👧👩‍👦👩‍👧👨‍👦👨‍👧🚼
    #> childish :  😜😛
    #> children :  👨‍👩‍👧‍👦👨‍👩‍👦‍👦👨‍👩‍👧‍👧👩‍👩‍👦👩‍👩‍👧👩‍👩‍👧‍👦👩‍👩‍👦‍👦👩‍👩‍👧‍👧👨‍👨‍👦👨‍👨‍👧👨‍👨‍👧‍👦👨‍👨‍👦‍👦👨‍👨‍👧‍👧👩‍👧‍👦👩‍👦‍👦👩‍👧‍👧👨‍👧‍👦👨‍👦‍👦👨‍👧‍👧
    #> china :  🍚🇨🇳
    #> chinese :  👲🐉🐲🈳🈹🈶🈚🈸🈷️🉑🉐㊙️㊗️🈴🈵🈲🈯🀄🇨🇳
    #> christmas :  ❄️⛄☃🎁🔔🇨🇽
    #> cigarette :  🚬🚭
    #> circle :  🉐⛔🚫⭕🚷🚯🚳🚱🔞📵©️®️🔘
    #> circus :  🎩🐵🦍🐒🐘🔮🎈🎊🎉NA
    #> city :  🌃🇻🇦
    #> classy :  👨🎩NA
    #> clean :  🛀🚿🛁
    #> cloth :  👕👔
    #> cloud :  🌀💭
    #> coder :  👩‍💻👨‍💻
    #> cold :  🤒❄️⛄☃🎿🏔🌡
    #> communication :  🛰🏣📞☎️📠📻📡✉️📩📧📪📫📬
    #> computer :  🤖⌨
    #> concert :  🎫🎟🏟
    #> confused :  😖🤷🤷‍♂️❓❔
    #> congo :  🇨🇬🇨🇩
    #> congratulations :  🎆🎉
    #> construction :  👷‍♀️👷⛑
    #> contest :  🏆🏁
    #> continue :  ⏩⬆️
    #> cook :  🔥🇨🇰
    #> cool :  😎👍🕶✨
    #> country :  🗾🎌🇦🇫🇦🇽🇦🇱🇩🇿🇦🇸🇦🇩🇦🇴🇦🇮🇦🇶🇦🇬🇦🇷🇦🇲🇦🇼🇦🇺🇦🇹🇦🇿🇧🇸🇧🇭🇧🇩🇧🇧🇧🇾🇧🇪🇧🇿🇧🇯🇧🇲🇧🇹🇧🇴🇧🇶🇧🇦🇧🇼🇧🇷🇮🇴🇻🇬🇧🇳🇧🇬🇧🇫🇧🇮🇨🇻🇰🇭🇨🇲🇨🇦🇮🇨🇰🇾🇨🇫🇹🇩🇨🇱🇨🇳🇨🇽🇨🇨🇨🇴🇰🇲🇨🇬🇨🇩🇨🇰🇨🇷🇭🇷🇨🇺🇨🇼🇨🇾🇨🇿🇩🇰🇩🇯🇩🇲🇩🇴🇪🇨🇪🇬🇸🇻🇬🇶🇪🇷🇪🇪🇪🇹🇫🇰🇫🇴🇫🇯🇫🇮🇫🇷🇬🇫🇵🇫🇹🇫🇬🇦🇬🇲🇬🇪🇩🇪🇬🇭🇬🇮🇬🇷🇬🇱🇬🇩🇬🇵🇬🇺🇬🇹🇬🇬🇬🇳🇬🇼🇬🇾🇭🇹🇭🇳🇭🇰🇭🇺🇮🇸🇮🇳🇮🇩🇮🇷🇮🇶🇮🇪🇮🇲🇮🇱🇮🇹🇨🇮🇯🇲🇯🇵🇯🇪🇯🇴🇰🇿🇰🇪🇰🇮🇽🇰🇰🇼🇰🇬🇱🇦🇱🇻🇱🇧🇱🇸🇱🇷🇱🇾🇱🇮🇱🇹🇱🇺🇲🇴🇲🇰🇲🇬🇲🇼🇲🇾🇲🇻🇲🇱🇲🇹🇲🇭🇲🇶🇲🇷🇲🇺🇾🇹🇲🇽🇫🇲🇲🇩🇲🇨🇲🇳🇲🇪🇲🇸🇲🇦🇲🇿🇲🇲🇳🇦🇳🇷🇳🇵🇳🇱🇳🇨🇳🇿🇳🇮🇳🇪🇳🇬🇳🇺🇳🇫🇲🇵🇰🇵🇳🇴🇴🇲🇵🇰🇵🇼🇵🇸🇵🇦🇵🇬🇵🇾🇵🇪🇵🇭🇵🇳🇵🇱🇵🇹🇵🇷🇶🇦🇷🇪🇷🇴🇷🇺🇷🇼🇧🇱🇸🇭🇰🇳🇱🇨🇵🇲🇻🇨🇼🇸🇸🇲🇸🇹🇸🇦🇸🇳🇷🇸🇸🇨🇸🇱🇸🇬🇸🇽🇸🇰🇸🇮🇸🇧🇸🇴🇿🇦🇬🇸🇰🇷🇸🇸🇪🇸🇱🇰🇸🇩🇸🇷🇸🇿🇸🇪🇨🇭🇸🇾🇹🇼🇹🇯🇹🇿🇹🇭🇹🇱🇹🇬🇹🇰🇹🇴🇹🇹🇹🇳🇹🇷🇹🇲🇹🇨🇹🇻🇺🇬🇺🇦🇦🇪🇬🇧🇺🇸🇻🇮🇺🇾🇺🇿🇻🇺🇻🇦🇻🇪🇻🇳🇼🇫🇪🇭🇾🇪🇿🇲🇿🇼
    #> couple :  👰🤵👬👭💒
    #> court :  👩‍⚖️👨‍⚖️
    #> cow :  🐃🐂🥛
    #> create :  🔨⚒🛠
    #> creativity :  🖍🖌
    #> creepy :  👹👺💀🎃
    #> crown :  👸🤴
    #> crush :  😊😍
    #> cry :  😂😭😿
    #> currency :  💵💴💶💷💲
    #> custom_ :  NANANANANANA
    #> cut :  ✂️🈹
    #> cutlery :  🥄🍴🔪
    #> cycle :  🔄🔃
    #> dad :  👨👪
    #> danger :  🐯☠☢☣❗🚸🔴
    #> date :  👫📆🗓
    #> dating :  👫💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨🏩
    #> dawn :  🌇🕕
    #> dead :  💀⚰⚱
    #> death :  ⚰⚱
    #> decoration :  🏵🎀❣
    #> democratic :  🇨🇩🇱🇦
    #> denied :  ⛔🚫
    #> depressed :  😞😔😢😭🙍🙍‍♂️
    #> desert :  🐪🐫
    #> despise :  😡NANANANA
    #> dessert :  🍡🍧🍨🍦🍰🎂🍮🍬🍫🍩🍪
    #> detective :  🕵️‍♀️🕵🔍🔎NA
    #> developer :  👩‍💻👨‍💻
    #> devil :  😈👿👹
    #> diagonal :  ↗️↘️↙️↖️
    #> dial :  📱📞☎️🎛
    #> diamond :  💍💎
    #> die :  ⚰⚱
    #> direction :  ☝👆👇👈👉🗺▶️◀️🔼🔽⏫⏬⬆️⬇️↗️↘️↙️↖️↕️↔️↪️⤴️⤵️🔺🔻
    #> disaster :  🌊🌋
    #> disbelief :  🤦🤦‍♀️
    #> disc :  💿📀
    #> discouraged :  🙍🙍‍♂️
    #> disk :  💽💿📀
    #> divide :  🈹➗
    #> doctor :  👩‍⚕️👨‍⚕️🏥💊💉
    #> documents :  💼📥📜📃📄📋📁📂📎🖇📝
    #> dog :  🐩🐾
    #> dollar :  🤑💸💴💶💰💳💱
    #> doom :  NANANANANA
    #> door :  🔑🗝
    #> dork :  🤓👓
    #> doubt :  🤷🤷‍♂️❓
    #> draw :  🎨〰️➰
    #> drawing :  📏🖍🖌
    #> drink :  🥛🍺🍻🥂🍷🥃🍸🍾🍶🍵🚱🔞
    #> drip :  💧💦
    #> driving :  🚦🚸
    #> drumstick :  🍗🍖
    #> drunk :  🍺🍻🍷🥃🍸🍶
    #> early :  🕐🕑🕒🕓🕔🕕🕖🕗🕘🕙🕚🕛🕜🕝🕞🕟🕠🕡🕢🕣🕤🕥🕦🕧
    #> economics :  📈📉〽️
    #> education :  🎓🎒🏫
    #> egg :  🐣🍳
    #> elder :  👴👵
    #> election :  🗳✅☑️
    #> email :  🏤📩📨💌📮📪📫📬📭📥📤
    #> emergency :  🚨🆘
    #> enforcement :  👮‍♀️👮🚓🚔
    #> engineer :  👩‍💻👨‍💻👩‍🔬👨‍🔬
    #> england :  💷🇬🇧
    #> entertainer :  👩‍🎤👨‍🎤
    #> envelope :  🏣💌📮
    #> environment :  ⛰🏔🏞♻️
    #> error :  🚨⚠️🔴
    #> evening :  🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜🌙🌆🌃
    #> evil :  👺🐍🖤
    #> exam :  ⌛📝💯
    #> exclamation :  ‼️⚠️
    #> exercise :  😓🏃‍♀️🏃🏊‍♀️🏊🏋️‍♀️🏋🚴‍♀️🚴🚲
    #> experiment :  ⚗🔬
    #> explode :  💥💣
    #> explosion :  💥💣
    #> face :  😀😬😁😂🤣😃😄😅😆😇😉😊🙂🙃☺️😋😌😍😘😗😙😚😜😝😛🤑🤓😎🤡🤠🤗😏😶😑🙄🤔🤥😳😞😟😠😔😕🙁☹😣😖😩😤😮😱😨😰😯😦😧😢😥🤤😪😓😭😲🤐🤢🤧😷😴👂👁💋🕶🦊NANA
    #> fail :  💩🏳
    #> faithful :  🐶🐕
    #> fall :  🍁🌻🎃⛅
    #> fashion :  💅👚👕👖👔👗👙👘💄👠👡👢👞👒👛👜👓💍NA
    #> fast :  ⚡💨🏎🏍🚅
    #> fast food :  🍔🍟
    #> father :  👨👪
    #> faucet :  💧🚱🚰
    #> favorite :  🔖📑
    #> feet :  🚶‍♀️🚶👣🐾
    #> female :  👧👩👱‍♀️👵👳‍♀️👮‍♀️👷‍♀️💂‍♀️🕵️‍♀️🤶👸🏃‍♀️🚶‍♀️💃👯👭🙇‍♀️🤦‍♀️🤷💁🙅🙆🙋🙎🙍💇💆👚👙👘💄👠👒🏌️‍♀️🚣‍♀️🏊‍♀️🏄‍♀️⛹️‍♀️🏋️‍♀️🚴‍♀️🚵‍♀️🚺
    #> ferry :  🛳⚓
    #> festival :  🎅🎄🎪🎆🎊
    #> film :  🎬📹🎥🎦
    #> find :  🔍🔎
    #> fingers :  ✊✌👌✋🤚👐☝👆👇👈👉🖕🖐🤘🖖
    #> fins :  🐬🦈
    #> fire :  🕯📛
    #> fireman :  👩‍🚒👨‍🚒
    #> fish :  🐬🦈🍣🎏
    #> fistbump :  🤛🤜
    #> fix :  🔧🔩
    #> flag :  ⛳🏳️‍🌈🇦🇫🇦🇽🇦🇱🇩🇿🇦🇸🇦🇩🇦🇴🇦🇮🇦🇶🇦🇬🇦🇷🇦🇲🇦🇼🇦🇺🇦🇹🇦🇿🇧🇸🇧🇭🇧🇩🇧🇧🇧🇾🇧🇪🇧🇿🇧🇯🇧🇲🇧🇹🇧🇴🇧🇶🇧🇦🇧🇼🇧🇷🇮🇴🇻🇬🇧🇳🇧🇬🇧🇫🇧🇮🇨🇻🇰🇭🇨🇲🇨🇦🇮🇨🇰🇾🇨🇫🇹🇩🇨🇱🇨🇳🇨🇽🇨🇨🇨🇴🇰🇲🇨🇬🇨🇩🇨🇰🇨🇷🇭🇷🇨🇺🇨🇼🇨🇾🇨🇿🇩🇰🇩🇯🇩🇲🇩🇴🇪🇨🇪🇬🇸🇻🇬🇶🇪🇷🇪🇪🇪🇹🇪🇺🇫🇰🇫🇴🇫🇯🇫🇮🇫🇷🇬🇫🇵🇫🇹🇫🇬🇦🇬🇲🇬🇪🇩🇪🇬🇭🇬🇮🇬🇷🇬🇱🇬🇩🇬🇵🇬🇺🇬🇹🇬🇬🇬🇳🇬🇼🇬🇾🇭🇹🇭🇳🇭🇰🇭🇺🇮🇸🇮🇳🇮🇩🇮🇷🇮🇶🇮🇪🇮🇲🇮🇱🇮🇹🇨🇮🇯🇲🇯🇵🇯🇪🇯🇴🇰🇿🇰🇪🇰🇮🇽🇰🇰🇼🇰🇬🇱🇦🇱🇻🇱🇧🇱🇸🇱🇷🇱🇾🇱🇮🇱🇹🇱🇺🇲🇴🇲🇰🇲🇬🇲🇼🇲🇾🇲🇻🇲🇱🇲🇹🇲🇭🇲🇶🇲🇷🇲🇺🇾🇹🇲🇽🇫🇲🇲🇩🇲🇨🇲🇳🇲🇪🇲🇸🇲🇦🇲🇿🇲🇲🇳🇦🇳🇷🇳🇵🇳🇱🇳🇨🇳🇿🇳🇮🇳🇪🇳🇬🇳🇺🇳🇫🇲🇵🇰🇵🇳🇴🇴🇲🇵🇰🇵🇼🇵🇸🇵🇦🇵🇬🇵🇾🇵🇪🇵🇭🇵🇳🇵🇱🇵🇹🇵🇷🇶🇦🇷🇪🇷🇴🇷🇺🇷🇼🇧🇱🇸🇭🇰🇳🇱🇨🇵🇲🇻🇨🇼🇸🇸🇲🇸🇹🇸🇦🇸🇳🇷🇸🇸🇨🇸🇱🇸🇬🇸🇽🇸🇰🇸🇮🇸🇧🇸🇴🇿🇦🇬🇸🇰🇷🇸🇸🇪🇸🇱🇰🇸🇩🇸🇷🇸🇿🇸🇪🇨🇭🇸🇾🇹🇼🇹🇯🇹🇿🇹🇭🇹🇱🇹🇬🇹🇰🇹🇴🇹🇹🇹🇳🇹🇷🇹🇲🇹🇨🇹🇻🇺🇬🇺🇦🇦🇪🇬🇧🇺🇸🇻🇮🇺🇾🇺🇿🇻🇺🇻🇦🇻🇪🇻🇳🇼🇫🇪🇭🇾🇪🇿🇲🇿🇼
    #> flight :  🛩✈️🛫🛬💺
    #> flower :  🥀🌸🏵
    #> flowers :  🌺🌹🌷🌼💐
    #> fly :  🐦🚁🛩✈️🚀💺
    #> food :  🐟🐡🌰🍐🍊🍌🍉🍇🍓🍈🍒🍑🍍🥝🥑🍅🍆🥒🥕🌶🥔🌽🍠🥜🥐🍞🥖🧀🥚🥓🥞🍗🍖🍤🍳🥙🌭🍕🍝🌮🌯🥗🥘🍜🍲🍥🍣🍱🍛🍙🍚🍘🍢🍡🍨🍦🍰🎂🍮🍭🍫🍿🍩🍪🍼🍽🎣
    #> forbid :  📛🚫
    #> formal :  👔NA
    #> forward :  ⏭🔼
    #> french :  🥐🥖🇫🇷🇬🇫🇵🇫🇹🇫
    #> friend :  🐶🐕
    #> friendship :  👬👭
    #> frozen :  ⛄☃
    #> fruit :  🍏🍎🍐🍊🍋🍌🍉🍇🍓🍈🍒🍑🍍🥝🥑🍅🥒
    #> frustrated :  🙄😠😫😩
    #> fun :  💃🕺🎳🎢
    #> funny :  😃😄
    #> gadgets :  🎧📱📷📸
    #> gamble :  🐎🎰
    #> game :  🎱👾🎯🕹🃏🀄🎴
    #> garbage :  🗑🚯♻️
    #> gardener :  👩‍🌾👨‍🌾
    #> gb :  💂‍♀️💂
    #> geek :  🤓👓
    #> gem :  💍💠🔸🔹🔶🔷
    #> gender :  🚹🚺🚻
    #> gesture :  🙌👋🤙
    #> girl :  👶👱‍♀️👸💃🙇‍♀️🤦‍♀️🤷💁🙅🙆🙋🙎🙍💇💆👙💄🎀
    #> girls :  👩👯
    #> globe :  🌎🌍🌏
    #> gn :  🇬🇶🇬🇳
    #> good :  👍🤞🌟✨🍖📈🉑❇️🆗
    #> graduate :  👩‍🎓👨‍🎓
    #> graph :  📊📈📉〽️💹
    #> grass :  🌱🌿🍃
    #> gray :  🌔❕❔
    #> green :  🤢🐉🐲🍵🎾
    #> green-square :  🈯💹❇️✳️❎✅
    #> groom :  🤵💒
    #> guy :  👦👨👱👷💂
    #> gymnastics :  🤸‍♀️🤸‍♂️
    #> haha :  😂🤣😃😄😆😹🙈
    #> halloween :  👹👻🎃🏮
    #> halo :  😇👼
    #> hand :  👍👎👊✊🤛🤜✌💪☝👆👇👈👉🖕🖐🤘🖖
    #> hands :  🙌👏👋🤙👐
    #> happiness :  ☺️😌
    #> happy :  😀😁😂😃😄😅😆😉😊😋😺😹🌈
    #> hat :  🤠🎓
    #> hate :  😡NANANANA
    #> head :  💆💆‍♂️
    #> headline :  🗞📰
    #> health :  🚑🏥💊💉
    #> healthcare :  👩‍⚕️👨‍⚕️
    #> heart :  😍😻💔💕💓💘
    #> heaven :  😇👼
    #> here :  📌📍🈁
    #> highfive :  ✋🙏
    #> hinduism :  👳‍♀️👳🕉☸
    #> hipster :  🚴‍♀️🚴🚲
    #> history :  🏰🏛📜
    #> hmmm :  🤔😕
    #> hobby :  🎱🎣🚣‍♀️🚣
    #> home :  👪👨‍👩‍👧👨‍👩‍👧‍👦👨‍👩‍👦‍👦👨‍👩‍👧‍👧👩‍👩‍👦👩‍👩‍👧👩‍👩‍👧‍👦👩‍👩‍👦‍👦👩‍👩‍👧‍👧👨‍👨‍👦👨‍👨‍👧👨‍👨‍👧‍👦👨‍👨‍👦‍👦👨‍👨‍👧‍👧👩‍👦👩‍👧👩‍👧‍👦👩‍👦‍👦👩‍👧‍👧👨‍👦👨‍👧👨‍👧‍👦👨‍👦‍👦👨‍👧‍👧🏠🏡
    #> horns :  😈👿🦌
    #> hospital :  🚑💉
    #> hot :  😅😓🐪🐫🔥🍛🍧🍨🍦🌡
    #> huh :  😕😨❔
    #> human :  👤👥🗣👴👵👷‍♀️👷🕵️‍♀️🕵👩‍⚕️👨‍⚕️👩‍🌾👨‍🌾👩‍🍳👨‍🍳👩‍🎓👨‍🎓👩‍🎤👨‍🎤👩‍🏫👨‍🏫👩‍🏭👨‍🏭👩‍💻👨‍💻👩‍💼👨‍💼👩‍🔧👨‍🔧👩‍🔬👨‍🔬👩‍🎨👨‍🎨👩‍🚒👨‍🚒👩‍✈️👨‍✈️👩‍🚀👨‍🚀👩‍⚖️👨‍⚖️🚶‍♀️🚶👫👬👭💁💁‍♂️🙆🙆‍♂️💑👩‍❤️‍👩👨‍❤️‍👨👪👨‍👩‍👧👨‍👩‍👧‍👦👨‍👩‍👦‍👦👨‍👩‍👧‍👧👩‍👩‍👦👩‍👩‍👧👩‍👩‍👧‍👦👩‍👩‍👦‍👦👩‍👩‍👧‍👧👨‍👨‍👦👨‍👨‍👧👨‍👨‍👧‍👦👨‍👨‍👦‍👦👨‍👨‍👧‍👧👩‍👦👩‍👧👩‍👧‍👦👩‍👦‍👦👩‍👧‍👧👨‍👦👨‍👧👨‍👧‍👦👨‍👦‍👦👨‍👧‍👧🏊‍♀️🏊⛹️‍♀️⛹🚵‍♀️🚵🚮
    #> hump :  🐪🐫
    #> hurt :  🤕NA
    #> icon :  🆖🔵▪️▫️⬛⬜◼️◻️◾◽
    #> ill :  🤢😷
    #> inbox :  ✉️📨📧📪📫📬📭📤
    #> indian :  👳‍♀️👳🍛🇮🇴
    #> indifference :  😐😒😕
    #> indifferent :  😑🤷🤷‍♂️
    #> industrial :  👩‍🏭👨‍🏭
    #> infatuation :  😍😘😗😙😚
    #> information :  💁💁‍♂️📄
    #> injured :  🤕NA
    #> input :  ⌨🔘🔲🔳
    #> insect :  🐝🐛🦋🐞🐜🕸
    #> instructor :  👩‍🏫👨‍🏫
    #> instrument :  🎹🥁🎷🎸🎻📯
    #> international :  🌎🌍🌏🌐
    #> internet :  🌐📶NA
    #> iphone :  📲📵
    #> irish :  ☘🍀
    #> islam :  🕌🕋☪
    #> island :  🇨🇽🇳🇫
    #> islands :  🇦🇽🇻🇬🇮🇨🇰🇾🇨🇨🇨🇰🇫🇰🇫🇴🇲🇭🇲🇵🇸🇧🇬🇸🇹🇨🇻🇮
    #> jainism :  🕉☸
    #> japan :  🍥🎑⛩
    #> japanese :  👹👺👘🍜🍣🍱🍙🍘🍢🍡🍶🗼🗻🗾💴🎏🎎🎌🈳🈚🈸🈺🈷️💮㊗️🈴🈵🈲🈂️🈁🇯🇵
    #> jewel :  💠🔸🔹🔶🔷
    #> jewelry :  💍💎
    #> jewish :  🕍🔯🕎
    #> joy :  😀😁😃😄😆😊😋
    #> judaism :  🕍✡
    #> juggle :  🤹‍♀️🤹‍♂️
    #> justice :  👩‍⚖️👨‍⚖️
    #> kanji :  🈳🈹🈶🈚🈸🈷️🉑🉐㊙️㊗️🈴🈵🈲🈯🀄
    #> katakana :  🈂️🈁
    #> king :  🤴👑
    #> kiss :  😘😗😙😚😽👄
    #> kitchen :  🍯🍳🥄🍴🔪
    #> knowledge :  📕📗📘📙📖
    #> korea :  🇰🇵🇰🇷
    #> labor :  👷‍♀️👷
    #> lady :  👩👵👒
    #> late :  🕐🕑🕒🕓🕔🕕🕖🕗🕘🕙🕚🕛🕜🕝🕞🕟🕠🕡🕢🕣🕤🕥🕦🕧
    #> laugh :  😄😅😆
    #> law :  👮‍♀️👮💼🚓🚨🚔⚖©️™️
    #> lawn :  🌱🌿🍃
    #> learn :  🎓🏫📕📘📖
    #> left :  👈◀️
    #> legal :  👮‍♀️👮🎓💼🚓🚨🚔📝©️™️
    #> letter :  ✉️📮🅰️🅱️🅾️Ⓜ️🅿️ℹ️
    #> library :  📕📗📘📙📚📖
    #> light :  🎃💡🏮🔆
    #> like :  😄😍😘😗😚😻👍👫👬👭💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨💋🏩💒💌❤️💛💚💙💜💕💞💓💗💖💘💟
    #> limit :  ⌛🈲⛔🚫
    #> literature :  📚📖
    #> location :  🗺📍
    #> lock :  ⛓🔑🗝
    #> lol :  🤣😆
    #> look :  👁👀
    #> loop :  🔁🔂
    #> love :  😍😘😗😚😻👫👬👭💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨💋🌹💒❤️💛💚💙💜❣💕💞💓💗💖💘💝💟
    #> luck :  🐎🎱🏇🎲🎰
    #> lucky :  🤞🍀
    #> mad :  😠😡💢🗯NANANANANANA
    #> magic :  🎩🐰🐇🌙🌟💫✨🎱🔮🎉🃏♠️♣️♥️♦️NA
    #> male :  👦👱👴👲👳👷💂🎅🤴🕺👯‍♂️🙇🤦🤷‍♂️💁‍♂️🙅‍♂️🙆‍♂️🙋‍♂️🙎‍♂️🙍‍♂️💇‍♂️💆‍♂️👞🚹
    #> mall :  🏬🛍
    #> man :  👦👱👮👨‍⚕️👨‍🌾👨‍🍳👨‍🎓👨‍🎤👨‍🏫👨‍🏭👨‍💻👨‍💼👨‍🔧👨‍🔬👨‍🎨👨‍🚒👨‍✈️👨‍🚀👨‍⚖️🎅🤴🏃🙇🤦🤷‍♂️💁‍♂️🙅‍♂️🙆‍♂️🙋‍♂️🙎‍♂️🙍‍♂️💇‍♂️💆‍♂️🇮🇲
    #> manager :  👩‍💼👨‍💼
    #> mark :  📌🚩
    #> marriage :  👰🤵👫💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨💍💒
    #> mask :  👹👺
    #> massage :  ☺️😌
    #> math :  📐📏➕➖➗✖️
    #> meat :  🥓🍗🍔🍲🍡
    #> medicine :  🌿💊💉
    #> meh :  😐😑
    #> men :  👴👯‍♂️🙆‍♂️
    #> meow :  🐱🐈
    #> message :  💬🗨
    #> mexican :  🌮🌯
    #> milk :  🐮🐄🍼
    #> mischievous :  😉😜😝😛
    #> mojito :  🌴🍸🍹🏖🏝
    #> money :  🤑👛🏦💵💴💶💷💳📈📉🏧💲💱
    #> monkey :  🙈🙉🙊🍌
    #> monster :  👹👺
    #> moo :  🐮🐄
    #> morning :  🌞⛅🌅
    #> mountain :  🌁🗻
    #> moustache :  👨〰️
    #> mouth :  👄👅
    #> movie :  🎬📽🎞🎦
    #> multitask :  🤹‍♀️🤹‍♂️
    #> munch :  😱🙀
    #> music :  🎤🎧🥁🎷🎺🎸🎻📻📯🔀🔣🎶🔘
    #> mustache :  👨〰️
    #> mute :  📴📵🔕
    #> myth :  🐉🐲
    #> NASA :  🚀🛰
    #> nation :  🗾🎌🇦🇫🇦🇽🇦🇱🇩🇿🇦🇸🇦🇩🇦🇴🇦🇮🇦🇶🇦🇬🇦🇷🇦🇲🇦🇼🇦🇺🇦🇹🇦🇿🇧🇸🇧🇭🇧🇩🇧🇧🇧🇾🇧🇪🇧🇿🇧🇯🇧🇲🇧🇹🇧🇴🇧🇶🇧🇦🇧🇼🇧🇷🇮🇴🇻🇬🇧🇳🇧🇬🇧🇫🇧🇮🇨🇻🇰🇭🇨🇲🇨🇦🇮🇨🇰🇾🇨🇫🇹🇩🇨🇱🇨🇳🇨🇽🇨🇨🇨🇴🇰🇲🇨🇬🇨🇩🇨🇰🇨🇷🇭🇷🇨🇺🇨🇼🇨🇾🇨🇿🇩🇰🇩🇯🇩🇲🇩🇴🇪🇨🇪🇬🇸🇻🇬🇶🇪🇷🇪🇪🇪🇹🇫🇰🇫🇴🇫🇯🇫🇮🇫🇷🇬🇫🇵🇫🇹🇫🇬🇦🇬🇲🇬🇪🇩🇪🇬🇭🇬🇮🇬🇷🇬🇱🇬🇩🇬🇵🇬🇺🇬🇹🇬🇬🇬🇳🇬🇼🇬🇾🇭🇹🇭🇳🇭🇰🇭🇺🇮🇸🇮🇳🇮🇩🇮🇷🇮🇶🇮🇪🇮🇲🇮🇱🇮🇹🇨🇮🇯🇲🇯🇵🇯🇪🇯🇴🇰🇿🇰🇪🇰🇮🇽🇰🇰🇼🇰🇬🇱🇦🇱🇻🇱🇧🇱🇸🇱🇷🇱🇾🇱🇮🇱🇹🇱🇺🇲🇴🇲🇰🇲🇬🇲🇼🇲🇾🇲🇻🇲🇱🇲🇹🇲🇭🇲🇶🇲🇷🇲🇺🇾🇹🇲🇽🇫🇲🇲🇩🇲🇨🇲🇳🇲🇪🇲🇸🇲🇦🇲🇿🇲🇲🇳🇦🇳🇷🇳🇵🇳🇱🇳🇨🇳🇿🇳🇮🇳🇪🇳🇬🇳🇺🇳🇫🇲🇵🇰🇵🇳🇴🇴🇲🇵🇰🇵🇼🇵🇸🇵🇦🇵🇬🇵🇾🇵🇪🇵🇭🇵🇳🇵🇱🇵🇹🇵🇷🇶🇦🇷🇪🇷🇴🇷🇺🇷🇼🇧🇱🇸🇭🇰🇳🇱🇨🇵🇲🇻🇨🇼🇸🇸🇲🇸🇹🇸🇦🇸🇳🇷🇸🇸🇨🇸🇱🇸🇬🇸🇽🇸🇰🇸🇮🇸🇧🇸🇴🇿🇦🇬🇸🇰🇷🇸🇸🇪🇸🇱🇰🇸🇩🇸🇷🇸🇿🇸🇪🇨🇭🇸🇾🇹🇼🇹🇯🇹🇿🇹🇭🇹🇱🇹🇬🇹🇰🇹🇴🇹🇹🇹🇳🇹🇷🇹🇲🇹🇨🇹🇻🇺🇬🇺🇦🇦🇪🇬🇧🇺🇸🇻🇮🇺🇾🇺🇿🇻🇺🇻🇦🇻🇪🇻🇳🇼🇫🇪🇭🇾🇪🇿🇲🇿🇼
    #> nature :  🐶🐱🐭🐹🐰🦊🐻🐼🐨🐯🦁🐮🐷🐸🦑🐙🦐🐵🦍🙈🙉🙊🐒🐔🐧🐦🦆🦅🦉🦇🐺🐗🐴🦄🐝🐛🦋🐞🐜🐍🦎🐢🐟🐡🐬🦈🐳🐋🐊🐆🐅🐃🐄🦌🐫🐘🦏🐐🐏🐑🐖🐁🐓🐕🐩🐇🐿🐉🐲🌵🌲🌳🌴🌱☘🍀🎍🎋🍃🍂🍁🌾🌻🥀🌷🌼🌸💐🐚🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜🌞☀️⛅🌊🍏🍐🍊🍋🍓🍈🍑🍍🍅🍆🍠⛰🏔🗻🌋🏞🌈🏡🎐
    #> nerdy :  🤓👓NA
    #> nervous :  😟😨😰😧😥
    #> new :  🇳🇨🇳🇿🇵🇬
    #> next :  ⏭➡️
    #> night :  😴🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜🌙⭐🌟🌠🎇🔦🔞
    #> no :  😣👎❌❎🇳🇴
    #> noodle :  🍝🍜
    #> nope :  🙅🙅‍♂️
    #> northern :  🇲🇵🇬🇧
    #> notes :  📓📔📒
    #> numbers :  💯0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟🔢
    #> nurse :  👩‍⚕️👨‍⚕️💉
    #> ocean :  🦑🐙🦐🐠🐡🐬🦈🐳🐋🏄‍♀️🏄🇮🇴
    #> office :  📃📄📁
    #> oink :  🐷🐽
    #> ok :  👌🉑✅✔️☑️
    #> old :  👴👵🔘
    #> oldschool :  💾📼📟📺⏳⌛NANANANA
    #> omg :  😱🙊
    #> oops :  😣😖😨💦
    #> orange :  🍊🥕
    #> orange-square :  📴📳🈶🈚🈸🈺🈷️✴️🆚🚼
    #> organizing :  🗄🗂
    #> outdoors :  🏕⛺
    #> outer_space :  👽🚀
    #> ox :  🐮🐃🐄
    #> painter :  👩‍🎨👨‍🎨
    #> pair :  👫👬👭💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨
    #> palm :  👋✋🖐
    #> panda :  🐼🎍
    #> paper :  🖨🏮📜📃📄📓📔📒📝✏️
    #> parent :  👩‍👦👩‍👧👩‍👧‍👦👩‍👦‍👦👩‍👧‍👧👨‍👦👨‍👧👨‍👧‍👦👨‍👦‍👦👨‍👧‍👧
    #> parents :  👪👨‍👩‍👧👨‍👩‍👧‍👦👨‍👩‍👦‍👦👨‍👩‍👧‍👧👩‍👩‍👦👩‍👩‍👧👩‍👩‍👧‍👦👩‍👩‍👦‍👦👩‍👩‍👧‍👧👨‍👨‍👦👨‍👨‍👧👨‍👨‍👧‍👦👨‍👨‍👦‍👦👨‍👨‍👧‍👧
    #> party :  🍕🍺🍻🥂🎪🔮🎈🎊🎉
    #> pass :  🎫💯
    #> password :  🔑🗝🔒
    #> pause :  ⏸⏯
    #> payment :  💸💰💳🏧💲
    #> people :  👫👬👭👪👨‍👩‍👧👨‍👩‍👧‍👦👨‍👩‍👦‍👦👨‍👩‍👧‍👧👩‍👩‍👦👩‍👩‍👧👩‍👩‍👧‍👦👩‍👩‍👦‍👦👩‍👩‍👧‍👧👨‍👨‍👦👨‍👨‍👧👨‍👨‍👧‍👦👨‍👨‍👦‍👦👨‍👨‍👧‍👧👩‍👦👩‍👧👩‍👧‍👦👩‍👦‍👦👩‍👧‍👧👨‍👦👨‍👧👨‍👧‍👦👨‍👦‍👦👨‍👧‍👧
    #> perfect :  👌💯
    #> person :  👤👥🗣👱‍♀️👱
    #> pet :  🐶🐱🐰🐕🐩🐈🐇🐾
    #> phew :  😌😤😥
    #> phone :  🤳📳📶
    #> photo :  🎡🎢🎠🌁🗼⛲🎑⛰🏔🗻🌋🏕⛺🏞🌅🌄🏜🏝🌇🌆🏙🌉🌌🌠🎆🌈🏘🏯🏟
    #> photography :  📷📸🖼
    #> physicist :  👩‍🔬👨‍🔬
    #> pink :  🙆🎀💓💗
    #> place :  🏆🏟🚩
    #> plane :  👩‍✈️👨‍✈️
    #> planet :  🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜
    #> planning :  📆🗓
    #> plant :  🌵🌲🌳🌴🌱🌿☘🍀🎍🎋🍃🍂🍁🌾🌺🌻🥀🌷🌸🍄🌽🏡
    #> play :  🎽🎮👾🎯🎲🎳🕹▶️⏯⏩⏪🃏🀄
    #> playful :  😜😝😛👅
    #> plumber :  👩‍🔧👨‍🔧
    #> point :  🈯🔼↗️↖️
    #> poker :  🃏♠️♣️♥️♦️
    #> police :  👮‍♀️👮🚨
    #> pool :  🎱🤽‍♀️🤽‍♂️
    #> power :  🔋🔌
    #> prank :  😜😝😛😏
    #> presentation :  📊📈📉〽️💹
    #> press :  🗞📰
    #> prime :  2️⃣3️⃣5️⃣7️⃣
    #> privacy :  🔐🔓㊙️⛔
    #> professor :  👩‍🏫👨‍🏫
    #> program :  📺📻
    #> programmer :  👩‍💻👨‍💻
    #> progress :  🚧🏗
    #> pub :  🍺🍻🔞
    #> public :  🚋🚅🚉
    #> punctuation :  ❗❕⁉️
    #> purple-square :  💟🔯⛎♈♉♊♋♌♍♎♏♐♑♒♓🆔🚺
    #> quiet :  📴🔇🔕
    #> quiz :  ⌛📝💯
    #> race :  🏃‍♀️🏃🚵‍♀️🚵🏎🏍🏁
    #> rancher :  👩‍🌾👨‍🌾
    #> random :  🎲🔀
    #> read :  🛋📕📗📘📙📖
    #> record :  🎬💽📼📹🎥📽📓📔🎦🔁
    #> red :  👹👺🚗🎴
    #> red-circle :  ㊙️㊗️
    #> red-square :  🈴🈵🈲🅰️🅱️🆎🆑🅾️🆘
    #> relax :  🍺🍻♨️
    #> religion :  ⛪🔯☦🛐
    #> reptile :  🦎🐊
    #> republic :  🇨🇫🇨🇩🇩🇴🇮🇷🇱🇦🇲🇩🇸🇾🇹🇿🇻🇪
    #> rest :  😪🛌🛏
    #> restroom :  🚽🚾🚰🚹🚺
    #> return :  ↪️↩️🔙
    #> right :  👉▶️
    #> rip :  ⚰⚱
    #> roar :  🐯🐅
    #> rocket :  👩‍🚀👨‍🚀
    #> rockstar :  👩‍🎤👨‍🎤
    #> rodent :  🐭🐀🐁🐿
    #> round :  ⭕🔃⚪⚫
    #> royal :  💂‍♀️💂👸🤴
    #> royalty :  👑🏰
    #> running :  🏃‍♀️🏃
    #> sad :  😞😔🙁☹😩😢😓😭😿🙍🙍‍♂️💔
    #> saint :  🇧🇱🇸🇭🇰🇳🇱🇨🇵🇲🇻🇨
    #> sale :  💸💰🏷
    #> sales :  👛🏦💵💴💶💷💳📈📉🏧💲💱
    #> sarcasm :  😏😒
    #> save :  💾🔖📑
    #> scared :  😱😨🙀
    #> scary :  👹👺👻☠
    #> schedule :  📅📆🗓🕐🕑🕒🕓🕔🕕🕖🕗🕘🕙🕚🕛🕜🕝🕞🕟🕠🕡🕢🕣🕤🕥🕦🕧
    #> school :  🎓🍎📏✏️🚸
    #> science :  ⚗🔬⚛
    #> score :  🎧💯🎵🎶
    #> screen :  💻🖥
    #> scribble :  〰️➰
    #> sd :  🇸🇸🇸🇩
    #> sea :  🦑🐙🐡🐬🦈🐳🐋🐚🌊🍥🏄‍♀️🏄⚓
    #> search :  🔍🔎
    #> season :  ❄️⛄☃
    #> secret :  😉🤐🔏
    #> security :  🛡🔐🔒🔓🔏⛔
    #> see :  👁👀
    #> senior :  👴👵
    #> shape :  ✴️🆖↔️➰⚪⚫🔴🔵🔸🔹🔶🔷🔺▪️▫️⬛⬜🔻◼️◻️◾◽🔲🔳
    #> shine :  ✨🎇
    #> ship :  🚣‍♀️🚣⛵🛥🚤⛴🚀🛶⚓
    #> shirt :  👕👔
    #> shoes :  👠👡👢👟
    #> shopping :  👖👗👝👛👜🏬🏪💳
    #> shower :  🛀🛁
    #> shy :  😊😳
    #> sick :  😣😖😫🤢🤧😷🤒
    #> sign :  ⛎♈♉♊♋♌♍♎♏♐♑♒♓🚸🚮
    #> sikhism :  🕉☸
    #> silence :  📴🔈🔇
    #> silly :  🙃😋
    #> sketch :  📐📏
    #> ski :  🚡🚠
    #> skill :  🤹‍♀️🤹‍♂️
    #> sky :  🌔🌞🌙☁️🌆🌈🈳
    #> sleep :  🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜🌙🛏
    #> sleepy :  😩😴💤
    #> slow :  🐌🐢
    #> smell :  👃🚭
    #> smile :  😀😁😃😅😉😊🙂🙃😋😜😝😛😎🤗😏😺😸
    #> smoke :  💨🏭🚬🚭
    #> snack :  🍟🍬🍭🍫🍿🍩🍪
    #> snow :  🎿⛷
    #> software :  👩‍💻👨‍💻
    #> sound :  👂🎤🎵🔈🔇📣📢🔔🔕
    #> south :  🇿🇦🇬🇸🇰🇷🇸🇸
    #> space :  👩‍🚀👨‍🚀🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜☄🌌📡🔭
    #> sparkle :  🌟💫✳️
    #> speaker :  🔉🔊📣
    #> speech :  💭🗯
    #> speed :  🚅⏩
    #> spicy :  🌶🍛
    #> spooky :  👻🏮
    #> sports :  👟⚽🏀🏈⚾🎾🏐🏉⛳🏌️‍♀️🏌🏓🏸🥅🏒🏑🏏🎿⛷🏂🤺🤼‍♀️🤼‍♂️🤾‍♀️🤾‍♂️⛸🏹🥊🚣‍♀️🚣🏊‍♀️🏊🤽‍♀️🤽‍♂️🏄‍♀️🏄⛹️‍♀️⛹🏋️‍♀️🏋🚴‍♀️🚴🚵‍♀️🚵🎗🎟🎳🏎🏍🚲🏟
    #> spring :  👒🐰🐦🐝🐇🌱🍃🌹🌷🌸💐☀️⛅☂☔💧🌈🎐💮
    #> spy :  🕵️‍♀️🕵
    #> squiggle :  〰️➰
    #> squirrel :  🐿🌰NA
    #> star :  💫✳️*⃣
    #> stars :  ✨🌌🎇🔭❇️
    #> states :  🇫🇲🇺🇸
    #> stationery :  ✍📇🗃📋🗒🗂📓📎🖇✂️📐📏📌📍🖊🖋✒️📝✏️
    #> stats :  📊📈📉〽️💹
    #> steps :  🚶‍♀️🚶
    #> stone :  ⬜◻️◽
    #> stop :  ✋⛔🚫🛑
    #> student :  🎒🏫
    #> study :  🔬📓📗📘📙📔📚📖📝✏️
    #> suit :  🕴NA
    #> suits :  ♠️♣️♥️♦️
    #> summer :  😎💪👙🌴🎋🌷☀️🍉🍤🍧🍦🍺🍻🍹⛳🎣🏊‍♀️🏊🏄‍♀️🏄⛵🚤⛲🏖⛱🔅
    #> sun :  🔅🔆
    #> surprise :  😮❗❕‼️⁉️
    #> sweat :  😅😰😥
    #> sweet :  🍯🍡🍬🍭🍫🍩🍪
    #> sync :  🔄🔃
    #> talk :  💬🗨
    #> tape :  📽➿
    #> team :  👥🏉
    #> tears :  😂😢😭😹😿
    #> technology :  📱💻⌨🖥🖲💽💾💿📞☎️📠📺
    #> teenager :  👦👧
    #> temperature :  🤒🌡
    #> temple :  🕍⛩🛐
    #> territories :  🇹🇫🇵🇸
    #> test :  ⌛📝💯
    #> textbook :  📕📙
    #> th :  🐘🇹🇭
    #> theater :  🎭🎦
    #> therapist :  👩‍⚕️👨‍⚕️
    #> thinking :  💭🗯
    #> thunder :  🌩⚡
    #> time :  ⌚⏱⏰🕰⏳⌛🕐🕑🕒🕓🕔🕕🕖🕗🕘🕙🕚🕛🕜🕝🕞🕟🕠🕡🕢🕣🕤🕥🕦🕧
    #> tired :  😩😪😓😴💤
    #> toilet :  🚾🚹🚺🚻
    #> tongue :  😋😜😝😛
    #> tools :  🔧🔨⚒🛠⛏🔩
    #> top :  🔼⏫⬆️⤴️🔺
    #> tracking :  👣🐾
    #> train :  🚂🛤
    #> training :  🏋️‍♀️🏋
    #> transport :  💺🛄
    #> transportation :  🚵‍♀️🚵🚗🚕🚙🚌🚎🚓🚒🚐🚚🚛🚍🚘🚡🚠🚟🚃🚋🚝🚄🚅🚈🚞🚂🚆🚇🚊🚉🚁🛩✈️⛵🚤🚏🚦🚥🚢🛤
    #> trash :  🗑🚯♻️
    #> travel :  🚋🚅🛅💱
    #> tropical :  🌴🏝
    #> turkey :  🍗🇹🇷
    #> twilight :  🌕🌖🌗🌘🌑🌒🌓🌔🌚🌝🌛🌜
    #> uber :  🚕🚖
    #> uk :  💂‍♀️💂💷
    #> unhappy :  🙍🙍‍♂️
    #> united :  🇹🇿🇦🇪🇬🇧🇺🇸
    #> up :  ☝👆🔺
    #> upset :  😞😔🙁☹😣😫😩😢😭😿
    #> user :  👤👥🗣
    #> vacation :  🎄🌅🌄
    #> valentines :  😍😘😗😙😚😻👫💑👩‍❤️‍👩👨‍❤️‍👨💏👩‍❤️‍💋‍👩👨‍❤️‍💋‍👨💋💍🌹💌❤️💛💚💙💜💕💞💓💗💖💘💝
    #> vampire :  🦇⚰
    #> vegetable :  🌵🌴🌿☘🍀🎍🍃🍂🍁🌺🍄🍅🍆🥕🌽
    #> vehicle :  🚗🚕🚙🚌🚎🚓🚒🚐🚛🚜🛴🛵🚔🚍🚘🚖🚡🚠🚟🚃🚋🚝🚄🚅🚈🚞🚂🚆🚊🚉🚁🛩✈️🚤
    #> video :  📼📽
    #> view :  🌅🌄
    #> violence :  👊🔫
    #> virgin :  🇻🇬🇻🇮
    #> volume :  🔈🔉🔊🔇📣📢🔕
    #> vote :  🗳✅☑️
    #> walking :  🏃‍♀️🏃👣🚷
    #> warm :  🏜♨️🔅
    #> warning :  🚧❗❕🚸
    #> watch :  👁👀
    #> water :  💧💦🌊🚣‍♀️🚣🏊‍♀️🏊⛵🛶⛲🚿
    #> wc :  🚽🚹🚻
    #> weapon :  🔫🔪🗡⚔🔱
    #> weather :  🌂☀️🌤⛅🌥🌦☁️🌧⛈🌩⚡❄️🌨⛄☃🌪🌫☂☔🏖🌡⛱🌀
    #> wedding :  👰🤵💍
    #> weep :  😂😿
    #> weird :  😕👽
    #> wild :  🐻🐯🐺
    #> wine :  🍇🍾🍶
    #> winning :  🏅🎖🥇
    #> winter :  ❄️⛄☃🎿⛷🏂🏔
    #> wip :  👷‍♀️👷🚧🏗⚠️
    #> woman :  👧👱‍♀️👳‍♀️👮‍♀️👷‍♀️💂‍♀️🕵️‍♀️👩‍⚕️👩‍🌾👩‍🍳👩‍🎓👩‍🎤👩‍🏫👩‍🏭👩‍💻👩‍💼👩‍🔧👩‍🔬👩‍🎨👩‍🚒👩‍✈️👩‍🚀👩‍⚖️🤶👸👰🏃‍♀️🚶‍♀️💃🙇‍♀️🤦‍♀️🤷💁🙅🙆🙋🙎🙍💇💆👙💄🏌️‍♀️🚣‍♀️🏊‍♀️🏄‍♀️⛹️‍♀️🏋️‍♀️🚴‍♀️🚵‍♀️🚺
    #> women :  👵👯🙆👘
    #> words :  🆔🆚🆑🆘🆖🆒🆕🆓🔠🔚🔙🔛🔝🔜💬🗨
    #> work :  💼🏢
    #> worker :  👷‍♀️👷
    #> world :  🌎🌍🌏🌐
    #> worship :  🕌🕍
    #> wow :  😮❗❕
    #> wrestlers :  🤼‍♀️🤼‍♂️
    #> write :  ✍🖊🖋✒️📝✏️
    #> writing :  🖊🖋✒️📝✏️
    #> ws :  🇦🇸🇼🇸
    #> xmas :  🤶🎅🎄❄️⛄☃🎁🔔
    #> xox :  😵😲
    #> yacht :  ⛴🛳
    #> yellow :  🌼🌕⭐
    #> yes :  👍🉑🆗✔️☑️
    #> zodiac :  ♈♉♊♋♌♍♎♏♐♑♒♓
    #> zoom :  🔭🔍🔎
