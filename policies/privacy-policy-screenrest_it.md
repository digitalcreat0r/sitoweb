---
layout: document
title: Privacy Policy - ScreenRest
permalink: /it/policies/privacy-policy-screenrest.html
back_url: /it/screenrest
back_text: Torna a ScreenRest
---
# Privacy Policy - ScreenRest

*Ultimo aggiornamento: 15 maggio 2026*

**ScreenRest** è un'applicazione sviluppata e gestita da **{{ site.author }}** ("lo sviluppatore"), operante come **{{ site.brand }}**. L'applicazione è stata progettata seguendo il principio di "Privacy by Design" (Privacy fin dalla progettazione): è strutturata per funzionare principalmente sul tuo dispositivo, garantendo al contempo elevati standard di stabilità tecnica e riservatezza.

## 1. Titolare del Trattamento dei Dati
Il titolare del trattamento dei dati per questa applicazione è:

**{{ site.author }} ({{ site.brand }})**

Email: {{ site.email }}<br>
Sito web: {{ site.url }}

## 2. Raccolta delle Informazioni
Lo sviluppatore **non** raccoglie, memorizza o tratta in alcun modo dati personali quali nomi, indirizzi email o numeri di telefono.

### Diagnostica e Segnalazione Errori (Su Consenso)
Per contribuire al miglioramento della stabilità dell'app, viene utilizzato il servizio **Firebase Crashlytics**. Di default, l'invio automatico delle segnalazioni di errore è disattivato.

In caso di crash (chiusura inaspettata), sul tuo dispositivo viene generato un registro locale. Al riavvio successivo dell'applicazione, ti verrà mostrato un messaggio per richiedere il tuo consenso esplicito all'invio di quello specifico rapporto di errore.
- **Se selezioni "Invia":** L'app trasmetterà il rapporto anonimo a Firebase.
- **Se selezioni "Non inviare":** Il rapporto locale verrà eliminato definitivamente dal tuo dispositivo e non verrà trasmesso alcun dato.

Il rapporto anonimo, inviato solo a seguito del tuo consenso esplicito, include:
- **UUID di installazione di Crashlytics:** Un identificatore anonimo generato casualmente.
- **Tracce dello stack (Stack traces):** Registri tecnici che indicano l'esatto punto in cui si è verificato l'errore nel codice.
- **Metadati del dispositivo:** Modello dell'hardware, versione del sistema operativo e stato dell'app al momento del crash.

### Servizi di Terze Parti
- **Google Play Services:** Utilizzato per i segnali di verifica dell'età e per le funzionalità di base dell'applicazione. Google potrebbe trattare i dati in conformità con la propria Informativa sulla Privacy.

## 3. Verifica dell'Età e Tutela dei Minori
Per conformarsi alle normative locali (come il Texas SCOPE Act), ScreenRest implementa misure di verifica dell'età:
- **Verifica Automatica:** L'app utilizza Google Play Age Signals per determinare se l'utente è un minore o un adulto in base allo stato del suo account Google. Questo processo è gestito da Google Play Services; lo sviluppatore riceve solo un segnale di stato anonimo (ad esempio, "Verified Adult" o "Supervised Minor") e non ha accesso alla data di nascita o ai documenti di identità.
- **Dichiarazione Manuale:** Se la verifica automatica non è disponibile, gli utenti devono dichiarare manualmente la propria fascia d'età.
- **Sicurezza dei Minori:** Per gli utenti identificati come minori, l'app richiede una conferma manuale di supervisione genitoriale. Poiché ScreenRest non raccoglie dati personali e funziona interamente offline, non crea profili di "fornitore di servizi digitali" per i minori.

## 4. Archiviazione Locale e Autorizzazioni
L'app utilizza **Android Jetpack DataStore** per salvare le tue preferenze localmente. Tali informazioni rimangono sul tuo dispositivo e non vengono mai caricate su server esterni.
- **Stato di Verifica dell'Età:** La tua fascia d'età (Adulto/Minore) viene memorizzata localmente utilizzando Android Jetpack DataStore per ricordare la tua scelta ed evitare richieste ripetute. Questi dati non lasciano mai il tuo dispositivo.

### Autorizzazioni Utilizzate
- **Sveglie di precisione (Exact Alarms):** Utilizzata per attivare i timer del benessere in modo preciso.
- **Notifiche:** Utilizzata per fornire aggiornamenti sullo stato e promemoria.
- **Vibrazione:** Utilizzata per il feedback aptico (tattile).

## 5. Conformità e Diritti dell'Utente
In conformità con il GDPR e le leggi internazionali sulla privacy, mantieni il pieno controllo sui tuoi dati. Poiché tutti i dati operativi sono archiviati localmente, puoi esercitare il tuo diritto alla cancellazione in qualsiasi momento svuotando i dati dell'app o disinstallando l'applicazione. Inoltre, i registri dei crash sono rigorosamente facoltativi e vengono trasmessi solo con il tuo consenso esplicito, richiesto singolarmente per ogni evento.

## 6. Contatti
Per qualsiasi domanda riguardante la tua privacy, puoi contattare lo sviluppatore all'indirizzo:<br>
**{{ site.email }}**