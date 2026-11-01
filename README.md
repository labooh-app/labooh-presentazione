# Labooh 👻

**L'app che uso per organizzare le affissioni pubblicitarie.**
Progetto personale: l'ho ideata e costruita io, con l'aiuto di un'intelligenza artificiale (Claude).

👉 **Presentazione:** [labooh-app.github.io/labooh-presentazione](https://labooh-app.github.io/labooh-presentazione/)

L'app è ad accesso riservato: il codice e i dati di lavoro non sono pubblici.
Vuoi usarla quando apre? Lascia la tua richiesta su [labooh-app.onrender.com](https://labooh-app.onrender.com/) (può metterci un minuto ad aprirsi).

> 🚧 **Cantiere aperto.** La uso ogni giorno e ogni settimana migliora qualcosa.

![Labooh](sito/anteprima-link.png)

## Il problema

Lavoro con i cartelloni pubblicitari. Molte ore se ne andavano a ricopiare Excel, preparare i fogli per le squadre, decidere i giri e fare mappe e presentazioni per i clienti. Labooh fa questo lavoro in pochi minuti.

## Cosa fa

**🗓️ Squadre**
Dal file della campagna ai fogli per ogni squadra, in PDF ed Excel. Promemoria salvati online e condivisi con i colleghi.

![Squadre](sito/pianificazione.webp)

**🚚 Giri di affissione**
Organizzo e pianifico i giri di affissione, per ottimizzare l'espletamento e garantire puntualità su tutti i comuni. Scelgo in che giorno andare in ogni comune, le campagne si dividono da sole e posso ritoccarle a mano. Escono i tabulati per ogni giro e il riepilogo di poster e manifesti.

![Giri di affissione](sito/giri.webp)

**📍 Posizioni**
Elenco degli impianti con la mappa, in PDF. Trova da sola i punti sbagliati: in mare, fuori dal comune o doppi.

![Posizioni](sito/mappe.webp)

**🧪 Clienti**
Il testo del progetto scritto con l'AI, da rileggere, e la brochure: da stampare (A4, A3, pieghevole) o in PDF da mandare per mail, con mappa interattiva ed Excel.

![Clienti](sito/progetto.webp)

**✉️ Mail**
Due righe scritte o dettate diventano una mail curata, nel tono giusto, senza inventare fatti.

## Come l'ho fatta

- Ho deciso cosa serviva e come doveva funzionare.
- Il codice l'ho scritto insieme a Claude, un'intelligenza artificiale.
- Ho provato ogni versione sul lavoro vero e corretto quello che non andava.

| | |
|---|---|
| App | React e TypeScript, per PC e telefono, tema chiaro e scuro |
| Server | Node.js con Express |
| Database | PostgreSQL su Supabase (server nell'Unione europea) |
| AI | modelli Google Gemini |
| Mappe | MapLibre, OpenFreeMap e OpenStreetMap |
| Documenti | PDF ed Excel creati nel browser |
| Online | Render, con una versione di prova e una vera |
| Automazioni | GitHub Actions: sveglia del server e copia di sicurezza del database |
| Account | accesso con approvazione, permessi, privacy e termini d'uso (GDPR) |

Tutto gira su servizi gratuiti. Il codice resta privato.

## Cosa arriva

- giri di affissione salvati online, da condividere con i colleghi
- storico delle mail scritte
- note personali che seguono l'account

---

Contatti: **Filippo Gulisano** · labooh.ai@gmail.com

<sub>Gli esempi nelle immagini (campagne, vie, numeri) sono inventati.</sub>
