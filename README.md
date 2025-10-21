Esame intermedio Node.js
#  ShowTracker

ShowTracker è una piattaforma **Node.js** per la gestione personalizzata di film e serie TV.  
Gli utenti possono registrarsi, autenticarsi, cercare contenuti tramite l’API di **TMDb** e creare le proprie liste di visione.

---

##  Funzionalità principali

###  Gestione utenti
- Registrazione, login e logout.  
- Autenticazione tramite **Bearer Token (JWT)** con **Passport.js**.  
- Gli utenti autenticati possono:
  - Cercare film e serie TV.  
  - Salvare contenuti nel proprio profilo.  
  - Lasciare **commenti** e **valutazioni personali**.  

---

### 🎥 Integrazione con TMDb
- Ricerca di **film e serie TV** tramite le **API TMDb**.  
- Visualizzazione dei dettagli:
  - Titolo  
  - Trama  
  - Cast  
  - Valutazioni  
  - Trailer  
  - Immagini  
- Salvataggio dei contenuti preferiti nel database personale dell’utente.  

---

###  Gestione contenuti personali
- Creazione di liste personalizzate:
  - “Da vedere”  
  - “Visti”  
  - Altre liste custom.  
- Modifica o rimozione di contenuti dalle liste.  
- Possibilità di lasciare commenti e valutazioni su ogni titolo salvato.  

---

##  Stack Tecnologico

- **Node.js**  
- **Express.js**  
- **Passport.js + JWT** (autenticazione)  
- **MySQL** (database)  
- **TMDb API** (integrazione esterna)  

---

##  Installazione e Setup

1. Clona il repository:
   ```bash
   git clone https://github.com/giadaperno/Node_esameint.git
    ```

