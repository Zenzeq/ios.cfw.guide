---
lang: it_IT
title: Bloccare gli aggiornamenti
description: Come bloccare gli aggiornamenti sul tuo dispositivo iOS o iPadOS.
permalink: /it_IT/blocking-updates
extra_contributors:
  - Tanbeer191
  - Jack LaFond
---

Ciò ti guiderà nell'installazione del "profilo tvOS" di iOS 15 per bloccare gli aggiornamenti sul dispositivo. È facile da installare e ti assicura di rimanere sul firmware attualmente installato. Ciò è utile se stai aspettando un jailbreak per una versione inferiore e non vuoi aggiornare nel caso in cui venga patchato.

## Installazione del profilo tvOS

1. Apri [cydia.ichitaso.com/no-ota15.mobileconfig](https://cydia.ichitaso.com/no-ota15.mobileconfig) nel browser del tuo dispositivo
1. Seleziona "Consenti" se richiesto
1. Apri l'app delle Impostazioni
1. Vai su `Generali` -> `Profili`
    - Questo può anche essere chiamato `Gestione Profili e Dispositivo`
1. Tocca il profilo tvOS Beta che hai appena installato
1. Premi su "Installa"
1. Conferma premendo nuovamente "Installa"
    - Inserisci il tuo codice se ne hai uno
1. Tocca "Installa" una terza volta
1. Riavvia il dispositivo quando ti viene richiesto

Il tuo dispositivo non dovrebbe più ricevere aggiornamenti software. Puoi controllare andando su `Impostazioni > Generali > Aggiornamento Software`, e se viene mostrato che "iOS è aggiornato", starai bloccando con successo gli aggiornamenti.

## Disinstallazione del profilo tvOS

Se si desidera aggiornare di nuovo il sistema, è necessario seguire i seguenti passaggi per rimuovere il blocco degli aggiornamenti.

::: danger

Rimuovendo il blocco degli aggiornamenti, si può involontariamente aggiornare a un firmware superiore, e non essere in grado di eseguire il jailbreak.

:::

1. Apri l'app delle Impostazioni
1. Vai su `Generali` -> `Profili`
  - Questo può anche essere chiamato `Gestione Profili e Dispositivo`
3. Clicca sull profilo tvOS Beta
1. Premi "Rimuovi Profilo Scaricato"

Il tuo dispositivo dovrebbe ora essere in grado di ricevere nuovamente gli aggiornamenti.
