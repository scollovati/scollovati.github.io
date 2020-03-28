---
layout: page
title: MinecraftEDU
permalink: /minecraftedu/
---

>_Istruzioni per sostituire le traduzione aggiornate nei jar originali._
>
Eseguire da terminale il comando di sostituzione senza scompattamento, dopo aver messo dentro il path `mcedu/global/localization/translations/minecraft/` il corretto file `it_IT`:
```
$ jar uf minecraftedu_server.jar mcedu/global/localization/translations/minecraft/it_IT
$ jar uf Launcher.jar mcedu/global/localization/translations/minecraft/it_IT  
$ jar uf ServerWizard.jar mcedu/global/localization/translations/minecraft/it_IT
$ jar uf mceduforge-0.jar mcedu/global/localization/translations/minecraft/it_IT
```
I nuovi jar vanno sostituiti ai vecchi, il più difficile da trovare è `mceduforge-0`, che si trova dentro `minecraftedu/minecraft/libraries/minecraftedu/mceduforge/0`.
