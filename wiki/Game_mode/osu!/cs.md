---
needs_cleanup: true  # https://github.com/ppy/osu-wiki/issues/9918, also, strange descriptions in many places and unhelpful order if you're trying to see what this game mode is all about.
---


# osu! (herní režim)

*Pro jiné použití viz [osu! (význam)](/wiki/Disambiguation/osu!).*

![Gameplay of osu!](/wiki/shared/osu-gameplay.jpg "osu! Interface")

První herní režim, s hratelností [založenou na sérii Ouendan](#inspiration).

## ![](/wiki/shared/mode/osu.png) Hratelnost

*Tutoriál: [nové začátky (součást osu!)](https://osu.ppy.sh/beatmapsets/1011011).*

### Výběr písně

Pro přístup do herního režimu osu! stiskněte současně `Ctrl`+`1`.

Alternativně klikněte na tlačítko `Mode` a vyberte `osu!`.

### Základy hry

#### Hrací pole

![osu! hrací pole](/wiki/shared/osu-gameplay.jpg "osu! hrací pole")

Hore v levém rohu se nachází lišta zdraví, která bude klesat konstantní rychlostí (v závislosti na nastavení obtížnosti beatmapy), ale může být doplněna poklepáním na noty v pravý čas nebo točením spinneru. Dokonale načasovaný zásah (300 nebo Geki) obnoví zdraví více než špatně načasovaný zásah (50). Celkové minuty odstraní značnou část zdraví z lišty.

Vpravo od lišty zdraví je celkové skóre. Pod tím je přesnost. Kruh vedle přesnosti (a pod skóre) je časovač pro trvání beatmapy.

Číslo v levém dolním rohu je počítadlo komba/multiplier skóre.

#### Hit circle

![Hit circles](/wiki/shared/osu_hitcircles.jpg "osu! hit circles")

Barevné kruhy s čísly nahoře, nazývané hit circle, se objeví na hracím poli při hraní. Tenčí, podobně barevný [approach circle](/wiki/Gameplay/Hit_object/Approach_circle) na okraji hit circle se bude zmenšovat v čase. Poklepejte na hit circle v přesně určeném okamžiku, kdy se approach circle dotkne jejich bílých okrajů, v pořadí podle čísel.

Po zásahu hit circle se objeví číslo, které ukazuje [hodnocení](/wiki/Gameplay/Judgement/osu!) na základě přesnosti načasování zásahu.

#### Slidery

![Sliders](/wiki/shared/osu_slider.jpg "osu! sliders")

Nejprve poklepejte na kruh na začátku slideru, nazývaný [slider head](/wiki/Gameplay/Hit_object/Slider/Sliderhead), v pravý okamžik. Po poklepání se koule začne pohybovat po cestě. Oranžový vnější kruh, nazývaný follow circle, se objeví, když držíte kouli slideru, ale zmizí, když je kurzor mimo kruh nebo tlačítko je uvolněno. Držte myš/klávesnici (nebo držte pero na tabletu) a sledujte kouli uvnitř follow circle, jak se pohybuje.

Někdy, jak je vidět na snímku výše, se koule může obrátit a hráč musí následovat kouli zpět na začátek cesty nebo naopak. Vizualní indikátor je zpětná šipka na koncovém/počátečním kruhu cesty.

#### Spinnery

![Spinner](/wiki/shared/osu_spinner.jpg "osu! spinners")

Držte myš/klávesnici (nebo držte pero na tabletu). Poté použijte myš (nebo pero) a točte spinner ve směru hodinových ručiček (nebo proti směru hodinových ručiček), dokud se kruh spinneru úplně nerozroste. Objeví se oznámení *Clear*, které ukáže, že spinner byl dokončen. Pokud byl spinner dokončen brzy, můžete pokračovat v točení a získat bonus skóre a obnovit nějaké zdraví.

Vnější bílý kruh ukazuje, kolik času zbývá na dokončení spinneru. Tento kruh se změní na červený, aby upozornil, že čas téměř vypršel. Starší skiny, které používají [verzi skinu](/wiki/Skinning/skin.ini#versions) 1.0, budou mít měřič/ukazatel, který ukazuje, jak blízko je spinner k dokončení.

Malý box pod spinnerem ukazuje aktuální rychlost točení, měřenou v otáčkách za minutu.

## Herní styly

*Odkaz na [stránku herních stylů v osu!](/wiki/Gameplay/Play_style).*

## Ovládání

Výchozí ovládání pro osu! je:

| Myš | Klávesnice | Tablet/Touchscreen |
| :-- | :-- | :-- |
| Levé kliknutí (M1) / Pravé kliknutí (M2) | `Z` (K1) / `X` (K2) | Dotyk na obrazovce (M1) |

Hit objekty v osu! přijímají jakýkoli vstup z zařízení, pokud je každý hit objekt poklepán včas.

Pokud je použit [Relax](/wiki/Gameplay/Game_modifier/Relax) herní modifikátor, bude fungovat pouze herní kurzor. Použijte herní kurzor k sledování hit objektů s automatickým poklepáním. Spinnery musí být stále dokončeny.

Pokud je použit [Auto Pilot](/wiki/Gameplay/Game_modifier/Autopilot) herní modifikátor, bude fungovat pouze vstup z ovládacího zařízení. Načasujte poklepání na hit objekty s automatickým pohybem kurzoru. Spinnery budou následovat rychlost [Spun Out](/wiki/Gameplay/Game_modifier/Spun_Out) modifikátoru.

## Skórování

[Skóre v osu!](/wiki/Gameplay/Score/ScoreV1/osu!) je vážený součet několika složek hratelnosti. Závisí na následujících faktorech:

- [Hodnocení](/wiki/Gameplay/Judgement/osu!) určuje základní hodnotu skóre pro hit objekt (300, 100, 50 nebo 0 v případě zmeškaného zásahu). Pro [hit circle](/wiki/Gameplay/Hit_object/Hit_circle) jsou správně načasované klávesy cennější, jak z hlediska skóre, tak i přesnosti. [Slidery](/wiki/Gameplay/Hit_object/Slider) a [spinnery](/wiki/Gameplay/Hit_object/Spinner) nemají okna zásahů, ale přeruší combo při chybném zásahu nebo nedokončení. Vyšší hodnocení znamená také větší [zdraví](/wiki/Gameplay/Health) bonus.
- [Přesnost](/wiki/Gameplay/Accuracy#osu!) závisí na hodnocení a ukazuje, jak přesné jsou zásahy. Pozdní nebo příliš brzké stisky kláves, stejně jako zmeškané zásahy, snižují celkovou přesnost.
- [Combo](/wiki/Gameplay/Combo_(score_multiplier)) je multiplikátor skóre: vyčištění hit objektu přispívá více k celkovému skóre, když je combo vysoké a naopak. Combo může být [přerušeno](/wiki/Gameplay/Judgement/Combobreak) zmeškaným zásahem nebo [slider break](/wiki/Gameplay/Judgement/Slider_break).

Pokud je combo udržováno, celkové skóre roste exponenciálně. Objekty blíže ke konci mapy mají hodnotu o několik řádů vyšší než ty na začátku, což znamená, že hráč ztratí mnohem více potenciálního skóre v případě špatně načasovaných zásahů. Výsledkem je, že skóre s nižší přesností může mít více bodů než skóre s vyšší přesností.

Po dokončení beatmapy je skóre přiřazeno [hodnocení](/wiki/Gameplay/Grade#osu!), krátkému hodnocení přesnosti ve formě jednoho písmena. Zlaté nebo stříbrné SS označuje 100% přesnost, a vše ostatní, od S po D, závisí na počtu 300, 50 a zmeškaných zásahů.

## Skinning

*Odkaz na [stránku Skinning v osu!](/wiki/Skinning/osu!) pro úplné informace.*

## Beatmapping

*Odkaz na [stránku Beatmapping](/wiki/Beatmapping) pro úplné informace.*

## Trivia

### Inspirace

Hratelnost osu! je založena na *[Osu! Tatakae! Ouendan](https://en.wikipedia.org/wiki/Osu!_Tatakae!_Ouendan)*, rytmické hře pro Nintendo DS. Stejně jako osu!, hratelnost obsahuje pouze tři prvky: poklepávání na kruhy na dotykovém displeji, tahání koule po pevné cestě a otáčení spinneru velmi rychle. Všechny tyto prvky jsou načasovány na coververze populárních japonských písní. Vypadá to takto na DS:

![Gameplay example of Osu! Tatakae! Ouendan in Nintendo DS](/wiki/shared/Ouendan.jpg "Gameplay example of Osu! Tatakae! Ouendan in Nintendo DS")

Hratelnostní kruhy jsou viditelné na spodní obrazovce a příběh na horní obrazovce. Každá úroveň je v podstatě samostatným příběhem o člověku v nesnázích. Tam přichází *Ouendan* (podporovací tým). Pomocí magické síly mužského cheerleadingu musí hráč pomoci lidem v nouzi.

### Hratelnost

![osu! smoke effect](/wiki/shared/osu_smoke.jpg "Smoke Usage")

![osu! smoke settings](/wiki/shared/osu_smoke_set.jpg "Smoke in key bindings")

- V závislosti na nastavení obtížnosti a toleranci časování, poklepání na hit objekt *příliš brzy* bude silně vibrace hit objektu.
- Uvolnění sliderové koule na prázdné sliderové cestě bez skrytých nebo viditelných slider ticků neznamená přerušení komba ani žádné skóre. Sliderové hodnocení pouze kontroluje, zda byl kliknut začínací kruh, sbírány slider ticke a koncový kruh byl správně dokončen.
- Na *DS* je dokončení spinnerů dobrý způsob, jak poškrábat dotykovou obrazovku (nebo ochranu obrazovky), zejména na vyšších obtížnostech. V osu! byly spinnery upraveny, aby nebyly takovou nepříjemností. Maximální počet otáček za minutu dosažitelný je 477, což je také rychlost, kterou otáčí [Auto](/wiki/Gameplay/Game_modifier/Auto) herní modifikátor, zatímco [Spun Out](/wiki/Gameplay/Game_modifier/Spun_Out) otáčí pomaleji při 287 otáčkách za minutu.
- Změna směru otáčení ve středu otáčení způsobí zpomalení spinneru (počet otáček za minutu klesne na 0 pro resetování směru otáčení), poté se otočí správně. Pokrok při otáčení nebude ztracen při reorientaci (nebude se místo toho zvyšovat), ale bude pokračovat při zpětném otáčení.
- Pokud neotáčíte kolem středu spinneru, nebude to považováno za platné otáčení.
- Kouř vydrží déle než výchozí stopa herního kurzoru. Používejte efekty kouře střídmě, aby staré efekty kouře příliš rychle nezmizely.
- Maskot pro osu! je [pippi](/wiki/Mascots#pippi).
- Když je hra spuštěna s [Auto](/wiki/Gameplay/Game_modifier/Auto), jméno hráče bude osu!.

### Historie

- Starší verze osu! používaly emulaci některých prvků ze série *Ouendan*, než byly odstraněny nebo nahrazeny:
  - [Combo fire](/wiki/Gameplay/Combo_fire) při dosažení nových combo milníků.
  - První verze výchozího skinu používající v1 chování skinu, který byl *osu!default by peppy*, poskytoval téměř identickou kopii rozhraní *Ouendan*.
    - Tento skin byl nahrazen hezčím současným výchozím skinem používajícím v2 chování skinu.
  - Největší rozdíl mezi v1 a v2 chováním skinu je spinner.
    - V chování v1 pro spinner by měřič spinneru rostl od spodního k vrchnímu, dokud nebyl plný podle série *Ouendan*.
      - Časovač je kruh uvnitř spinneru, který se bude sbíhat do středu spinneru. Spinner končí, když kruh časovače dosáhne středu spinneru.
    - V chování v2 pro spinner by se kruh spinneru pomalu rozšiřoval na plnou velikost a zářil, když byl dokončen.
      - Časovač je vnější kruh spinneru, který mění barvu. Spinner končí, když se barva kruhu časovače úplně změní.
- První tři beatmapy, které byly hodnoceny ve stejný den (7. října 2007), když se online leaderboard spustil, byly:
  - [Kenji Ninuma - DISCO PRINCE (peppy)](https://osu.ppy.sh/beatmapsets/1), nebo `discoprince`; což bylo zřejmě mapováno asi za hodinu.
  - [Ni-Ni - 1,2,3,4, 007 \[Wipeout Series\] (MCXD)](https://osu.ppy.sh/beatmapsets/3), nebo `Ni-Ni - 1,2,3,4, 007 [Wipeout Series]`.
  - [Brandy - Love Fighter (FFFanatic)](https://osu.ppy.sh/beatmapsets/16), nebo `Brandy - Love Fighter`.
- Poznámka: Starší složky mají svůj vlastní pojmenovací konvenci (název složky lze najít pouze ve *starých* balíčkách beatmap) a přísně se neřídí aktuálním formátem `{BeatmapSetID} {ArtistName} - {BeatmapName}`.
  - Stahování přímo z beatmapového seznamu na webu osu! sleduje aktuální vynucený pojmenovací formát bez ohledu na to.
