# 🏗 Checklist Cantiere — Audit di Qualità ISO 9001

Strumento web per creare check-list ed eseguire **audit di qualità** in cantiere e in azienda,
con gestione di non conformità, segnalazioni, anomalie, statistiche (KPI) e report in Word.

👉 **Applicazione online:** https://giovanni-sicimontaggi.github.io/checklist-cantiere/

> È un'unica pagina web che funziona nel browser, **senza installare nulla**.
> I dati restano salvati **sul tuo dispositivo** (nel browser); niente viene inviato su internet.

---

## A cosa serve

- 📋 **Modelli (check-list)** — crea modelli di controllo con argomenti e punti, e pianifica date inizio/fine
- ✅ **Esegui audit** — per ogni punto: esito (Conforme / Non conforme / N.A.), Note Auditor, note, allegati
- 📌 **Gestione** di Non Conformità (con scadenze), Segnalazioni e Anomalie (con tempi)
- 👥 **Personale audit** — persone intervistate, assegnabili per argomento o per singolo punto
- 📊 **KPI e grafici** — conformità, NC aperte/chiuse, tempo perso, istogrammi
- 📄 **Report in Word (.docx)** — con logo aziendale, grafici, e spazio per timbro e firma Auditor
- 💾 **Backup / Ripristino** — salva tutto in un file e ricaricalo su un altro dispositivo

## Come si usa

1. Apri il link dell'applicazione (qui sopra).
2. Dalla **Dashboard** scegli: **Vai alla Check**, **Crea Modulo** oppure **KPI**.
3. Crea un modello, poi lancia una check-list e compila i punti.
4. A fine audit: **Report → Scarica Word** per il documento da stampare/firmare.

## Dati e backup

- I dati sono salvati nel **browser** del dispositivo che usi (localStorage).
- Versione **locale** (file sul PC) e versione **online** hanno dati separati.
- Per spostare i dati: **Home → Salva backup** su un dispositivo, poi **Ripristina** sull'altro.
- Consiglio: fai un backup periodico e conservalo su OneDrive / chiavetta.

## Aspetti tecnici

- Singolo file `index.html` (HTML + CSS + JavaScript), nessuna dipendenza esterna.
- Pubblicato con **GitHub Pages**. Non indicizzato dai motori di ricerca (`robots.txt` + meta `noindex`).
- Il report Word viene generato direttamente nel browser (formato OOXML).

## Autore

**Giovanni Fiorenza** — Sicimontaggi
