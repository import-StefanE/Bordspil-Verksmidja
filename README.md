# Bordspil-Verksmidja

**Þetta er verkefni í áfanganum - VESM1KT05AK Verksmiðja K2 Vorið 2024**

Höfundar: Ella Sigurðardóttir, Kristófer Birgisson og Stefan Erlendur.

Verkefnið var að búa til rafrænt borðspil.

Við ákvaðum að búa til fjárhættuspilið rúllettu (Roulette á ensku).

Við gerðum það rafrænt með því að nota neopixel til að líkja eftir kúlu að snúast á rúlettuborðið. Þessu fylgir hljóði sem líkist ljóðinu sem kemur frá kúlunni. Þegar "kúlann" hættir að snúast birtist handahófskennd tala milli 1-30 + tölurnar 0 og 00. Á sama tíma lýsist neohringurinn í þeim lit sem talan er. Þegar tala birtist á skjánnum þá lýsast allar litlu led perurnar sem þessi tala á við. T.d. ef talann 11 birtist, þá lýsast 1-15, svartur, odda og seinni 9 ljósin. Þetta helst svona þangað til að einhver ýtir aftur á takkann til að byrja leikinn upp á nýtt.

Leikreglur:
  Markmið spilsins er að áætla hvar ljósið birtist til að fá stig.
  
  Veðmálin: Það eru ýmsar leiðir sem hægt er að veðja
    Ein tala: Veðja á eina tölu
    Klofning: Veðja á tvær aðliggjandi tölur
    Gata: Veðja á þrjár tölur í láréttri línu (*götu*)
    Horn: Veðja á fjórum tölum sem eiga sameiginlegt horn
    Tvígata: Veðja á tvær aðliggjandi götur
    Karfa: Veðja á 0, 00, 1, 2 og 3
    Rauður/Svartur: Veðja á lit tölunnar
    Oddatala/Slétt tala: Veðja á hvort talan sé slétt eða ekki
    Há/Lá tala: Veðja á hvort tala sé 1-16 eða 17-32

  Stigatalning
    Þegar öll veðmál hafa verið sett þá er kveikt á ljósinu, svo er fundið stigin út frá þessari töflu:
      Rauður/Svartur/Oddatala/Slétt tala/Há tala/Lá tala: 1:1
      Tvígata: 5:1
      Karfa: 6:1
      Horn: 8:1
      Gata: 11:1
      Klofning: 17:1
      Ein tala: 35:1


      
      
      
      
