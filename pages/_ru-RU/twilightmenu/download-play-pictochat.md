---
lang: ru-RU
layout: wiki
section: twilightmenu
category: other
title: Download Play/PictoChat в DS Classic Menu
description: Как получить DS Download Play и PictoChat в TWiLight Menu++'s DS Classic Menu
---

Если вы используете консоль DSi, вы уже можете запускать эти приложения. Getting dumps of them for your flashcard or 3DS requires accessing the DS Classic Menu on a DSi. В противном случае, если у вас 3DS без существующих дампа(ов), следуйте шагам ниже.

В GodMode9:
1. Press the HOME/Power button
1. Select `Title Manager`, then select `[1:] NAND / TWL`
1. Find and select `DS Download Play (NTR-HDNA)`
1. Select `Open title folder`
1. Select `00000000.tmd`, then select `TMD file options...`
1. Select `Dump CXI/NDS file`
   - The file will be in `0:/gm9/out/`
1. Copy `DS Download Play (NTR-HDNA).nds` to `0:/_nds/`, and rename it to `dlplay.nds`

The above steps will increase DLP boot speed.

To run PictoChat on 3DS (DSi required), copy `pictochat.nds` from `sd:/_nds/` on the DSi's SD card to the same location on the 3DS's SD card.

To run both on flashcard, copy both `pictochat.nds` and `dlplay.nds` from `sd:/_nds/` on the DSi or 3DS SD card to the same location on the flashcard's SD card.
