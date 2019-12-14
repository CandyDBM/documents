##Základní návody
**UPOZORNĚNÍ** <br/> Styl těchto dokumentů je okopírován z Anglických DBM dokumentů, link **[zde](https://silversunset.net/dbm/)**

#Rozběhnutí bota v konzoli

**Budete potřebovat nainstalovat node.js! [Link zde!](https://nodejs.org/en/download/)**

- Otevřeme složku projektu

![](http://developeri.wz.cz/docs/resources/dbm/images/cmd1.png)

- Klikneme na adresu a přepíšeme ji na `cmd`
  - Následně potvrdíme klávesou Enter

![](http://developeri.wz.cz/docs/resources/dbm/images/cmd2.png)

- Nyní jen napíšeme `node bot.js` a potvrdíme to klávesou Enter
  - Po chvilce by se měl zobrazit nápis "Bot is ready!"

![](http://developeri.wz.cz/docs/resources/dbm/images/cmd3.png)

##Příkazy
V této sekci si ukážeme jak udělat některé příkazy
#Say command
- Vytvoříme novou akci - Store Command Params, to uloží text, který uvedeme s commandem
  - Multiple Parameters
  - Starting Parameter 1
  - Store in Temp Variable
  - Variable name: `params`

![](http://developeri.wz.cz/images/say1.png)

- Nyní jen pošleme zprávu (Send Message) s textem `${tempVars("params")}`

![](http://developeri.wz.cz/images/say2.png)

- Můžeme otestovat příkaz... FUNGUJE!

![](http://developeri.wz.cz/images/say3.png)
