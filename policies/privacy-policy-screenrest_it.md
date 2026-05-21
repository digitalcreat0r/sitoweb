---
layout: document
title: Privacy Policy - ScreenRest
permalink: /it/policies/privacy-policy-screenrest.html
back_url: /it/screenrest
back_text: Torna a ScreenRest
---
# Privacy Policy - ScreenRest

*Ultimo aggiornamento: 15 maggio 2026*

**ScreenRest** è un'applicazione sviluppata e gestita da **Oleksandr Bihansky** ("io"), operante come **CleverPocket**. È costruita con un approccio "Privacy by Design": credo che i tuoi dati appartengano a te. Questa applicazione è progettata per funzionare principalmente sul tuo dispositivo, mantenendo elevati standard di stabilità tecnica e privacy.

## 1. Titolare del Trattamento
Il titolare del trattamento per questa applicazione è:
**Oleksandr Bihansky (CleverPocket)**
Email: {{ site.email }}
Sito web: {{ site.url }}

## 2. Raccolta delle Informazioni
**Non** raccolgo, memorizzo o elaboro alcuna informazione personale come nomi, indirizzi email o numeri di telefono.

### Diagnostica e Segnalazione Crash (Opt-In)
Per aiutarmi a migliorare la stabilità dell'app, utilizzo **Firebase Crashlytics**. Per impostazione predefinita, la segnalazione automatica dei crash è disattivata.

Se l'app subisce un crash (chiusura improvvisa), genererà un log locale sul tuo dispositivo. Al successivo avvio dell'app, ti verrà mostrato un messaggio che richiede il tuo consenso esplicito per inviare quello specifico rapporto sul crash.
- **Se scegli "Send":** L'app trasmetterà il rapporto anonimo a Firebase.
- **Se scegli "Don't Send":** Il rapporto locale viene eliminato permanentemente dal tuo dispositivo e nessun dato viene trasmesso.

Il rapporto anonimo, inviato solo se autorizzato esplicitamente da te, include:
- **Crashlytics Installation UUID:** Un identificatore anonimo generato casualmente.
- **Stack traces:** Log tecnici che indicano esattamente in quale punto il codice si è interrotto.
- **Metadati del dispositivo:** Modello hardware, versione del sistema operativo e stato dell'app al momento del crash.

## 3. Archiviazione Locale e Permessi
L'app utilizza **Android Jetpack DataStore** per salvare le tue preferenze localmente. Queste rimangono sul tuo dispositivo e non vengono mai caricate su alcun server esterno.

### Permessi Utilizzati
- **Allarmi esatti (Exact Alarms):** Utilizzato per attivare i timer di benessere con precisione.
- **Notifiche:** Utilizzato per fornire aggiornamenti sullo stato e promemoria.
- **Vibrazione:** Utilizzato per il feedback aptico.

## 4. Conformità e Diritti
In conformità con il GDPR e le leggi internazionali sulla privacy, hai il pieno controllo sui tuoi dati. Poiché tutti i dati operativi sono memorizzati esclusivamente in locale, puoi esercitare il tuo diritto alla cancellazione in qualsiasi momento svuotando i dati dell'app dalle impostazioni di sistema o disinstallando l'applicazione. Inoltre, i log dei crash sono rigorosamente facoltativi (opt-in) e vengono trasmessi solo con il tuo consenso esplicito per ogni singolo evento.

## 5. Informazioni di Contatto
Se hai domande riguardanti la tua privacy, puoi contattarmi all'indirizzo: **{{ site.email }}**