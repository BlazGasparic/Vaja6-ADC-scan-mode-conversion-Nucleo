# Vaja6-ADC-scan-mode-conversion-Nucleo

Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. To bodo pini PC0, PC1  in PC2. zbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? C.

Na Pinout configuration se vam morajo usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? ADC1_IN1, ADC1_IN2  in ADC1_IN3.

V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4MHz. Koliko bo izbrana vrednost parametra? 4.

Koliko je privzeta vrednost parametra Number of Conversion? 1. Ker bomo pretvarjali na treh kanalih hrati, spremenite vrednost na 3.

Čas vzorčenja Sampling Time (glejte Rank) izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah? 34,8. Enačba za izračun: tvz = (tvz_cik + 12) / ftakta_pretvorbe

V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC1. Dolžina podatka pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width: Byte (tako za Peripheral in Memory).

Kaj pomeni kratica DMA? Direct Memory Access.
