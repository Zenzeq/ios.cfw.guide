---
lang: it_IT
title: doubleH3lix
description: Guida all'installazione di doubleh3lix tramite Sideload
permalink: /it_IT/installing-doubleh3lix-(ipa)
redirect_from:
  - /it_IT/installing-doubleh3lix-ipa
pkgman: cydia
extra_contributors:
  - TheHacker894
---

::: warning

Questa è una guida alternativa progettata in caso riscontrassi problemi con <router-link to="/it_IT/using-tns">TotallyNotSpyware</router-link>. Nella maggior parte dei casi, TotallyNotSpyware è generalmente migliore e più semplice rispetto ad installare manualmente doubleh3lix.

:::

doubleh3lix è in grado di eseguire il jailbreak di tutti dispositivi A7-A9(X) con una versione del firmware 10.0-10.3.3.

Tieni a mente che il jailbreak di doubleh3lix non <router-link to="/it_IT/types-of-jailbreak/#semi-untethered-jailbreaks">è persistente</router-link> (non rimane installato dopo un riavvio). Sarà necessario ri-eseguire l’exploit dopo ogni riavvio. Ti verrà spiegato come fare.

A causa di come le app di terze parti vengono installate sul dispositivo, nella maggior parte dei casi dovrai reinstallare l’app di doubleH3lix sul tuo dispositivo ogni 7 giorni tramite un computer.

Utilizzeremo Sideloadly per installare l'app di doubleH3lix sul tuo dispositivo iOS nello step successivo.

## Download

- L’ultima versione di [doubleH3lix](https://doubleh3lix.tihmstar.net/ipa/doubleH3lix-RC8.ipa)
- L’ultima versione di [Sideloadly](https://sideloadly.io/)
- L’ultima versione di [iTunes](https://www.apple.com/itunes/download/win32) se sei su Windows

![Uno screenshot dell’applicazione di Sideloadly (Windows)](/assets/images/sideloadly_win.png)

## Installazione

1. Apri Sideloadly
1. Connetti il tuo dispositivo iOS al computer
    - Assicurati che il tuo computer sia autorizzato a vedere i contenuti del dispositivo
1. Trascina il file `.ipa` di doubleH3lix su Sideloadly
1. Inserisci il tuo Apple ID
1. Inserisci la tua password
    - Sideloadly deve fare una richiesta al server per funzionare con gli account Apple ID gratuiti. Se non sei d’accordo con ciò, puoi sempre usare un Apple ID alternativo.

L’app verrà adesso installata sul tuo dispositivo iOS.

## Autorizzare l’applicazione

1. Vai su `Impostazioni` -> `Generali` -> `Gestione Dispositivo` -> `<Il tuo Apple ID>`
    - A seconda del tuo utilizzo, `Gestione dispositivo` potrebbe apparire come `Gestione Profili e Dispositivo`
1. Clicca su `Autorizza "<Il tuo Apple ID>"`

L’applicazione di doubleH3lix adesso può essere aperta dalla home screen.

## Eseguire doubleH3lix

1. Apri l'applicazione di doubleH3lix dalla home screen
1. Clicca su “Jailbreak”

::: warning

Se il dispositivo crasha o si riavvia inaspettatamente ed il jailbreak non viene installato, prova a far partire l’exploit di nuovo finché non funziona.

:::

Adesso dovresti essere jailbroken con Cydia installato nella home screen. Puoi utilizzare Cydia per installare <router-link to="/it_IT/faq/#what-are-tweaks">tweak</router-link>, temi e altro.
