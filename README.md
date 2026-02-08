# Jeg er Ghoul (bot), arbejder nu i chats

![Bot i aktion](https://github.com/error1001es/teleghoul/blob/main/screenshots/bot_work.png)

**Du kan takke forfatteren for deres arbejde [her](#donér)**<br>
**Hjælp med installation [her](#hjælp)**

___
## Installation på Android
**Efter installationen skal du gå til afsnittet [*Start*](#Start)**<br>

Download appen [Termux](https://play.google.com/store/apps/details?id=com.termux) fra Play Market<br>
Åbn og skriv kommandoerne nedenfor en efter en<br>

***For at kopiere en kommando skal du klikke til højre for den***

*Opdater*

apt-get update
*Installer git og python*

apt-get install git python
Hvis du bliver spurgt: "Vil du fortsætte?" [J/n], svar "J" og fortsæt.<br>
*Installer pyrogram*

pip install pyrogram
*Klon arkivet*

git clone https://github.com/error1001es/teleghoul.git
**Efter installationen skal du gå til afsnittet [*Kør*](#Kør)**.<br>

___
## Installation på pc
**Efter installationen skal du gå til afsnittet [*Kør*](#Kør)**.<br>

Download [git](https://git-scm.com/downloads) og [python](https://www.python.org/downloads/)<br>
**Når du installerer Python, skal du sørge for at markere feltet "Tilføj til STI".**<br>

*Installer pyrogram*

pip install pyrogram
*Klon arkivet*

git clone https://github.com/error1001es/teleghoul.git
___
## Start
Før hver start skal du [opdatere](#update) bot<br>
*Indtast* og vent på, at botten beder om telefonnummeret, der er knyttet til **DIN** Telegram

python teleghoul/index.py

En kode vil blive sendt til **TELEGRAM**. Indtast den, og botten vil virke.

![Launch](https://github.com/error1001es/teleghoul/blob/main/screenshots/startup.png)<br>

Hvis du har *tofaktorgodkendelse* aktiveret, vil botten bede om en adgangskode<br>

**Efter opstart vil botten give dig besked. *Efterfølgende opstarter udføres uden nogen installation***<br>

<pre>
<kbd>Ctrl</kbd>+<kbd>C</kbd> - Deaktivering af botten
</pre>
___
## Telegram-kommandoer
`Jeg er en Ghoul` - spam<br>
`.ghoul-c` - sign<br>

*Det er bedst kun at køre dette i én chat ad gangen*<br>

***Test det venligst ikke på mig***<br>

___

## Donér
[Min Qiwi](https://donate.qiwi.com/payin/4sadly)<br>
[Donationstjeneste](https://donate.stream/4sadly)
https://www.donationalerts.com/r/ponyal

___
## Hjælp
Hvis du støder på fejl, skal du kontrollere din stavning/kopiering af kommandoerne<br>
Prøv igen, og send mig først derefter en besked [**PM**](https://t.me/ghoul4s) med et skærmbillede!

___
## Opdatering
*Gå til bot-mappen*

cd teleghoul

*Opdatering*

git pull

*Luk mappen for nem opstart senere*

cd ../

___
## Yderligere funktioner og kommandoændringer
Du kan åbne *config.py*-filen med kommandoen `nano teleghoul/config.py`<br>
<pre>
<kbd>Ctrl</kbd>+<kbd>X</kbd> - Afslut redigering
</pre>
