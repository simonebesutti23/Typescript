# 🎯 Bonny — Sistema di Gestione Incentivi Statali

> Progetto TypeScript che modella la struttura operativa di una startup che favorisce l'accesso dei cittadini ai bonus statali.

---

## 📌 Descrizione

**Bonny** è una startup marchigiana attiva da tre anni, impegnata nella semplificazione della burocrazia per i cittadini italiani. Collabora con istituzioni e professionisti del settore fiscale per rendere più accessibili e comprensibili i bonus e le agevolazioni statali disponibili.

Questo progetto modella in TypeScript le interazioni tra:
- 🏢 **Startup** — le aziende innovative nel settore
- 💰 **Incentivi** — i bonus statali disponibili
- 👤 **Cittadini** — gli utenti che partecipano alle iniziative

---

## 🛠️ Tecnologie utilizzate

- **TypeScript** — linguaggio principale
- **CodePen** — ambiente di sviluppo e testing

---

## 🏗️ Struttura del codice

### Interfacce

| Interfaccia | Descrizione |
|-------------|-------------|
| `IStartup` | Rappresenta una startup innovativa nel settore sportivo |
| `IIncentivo` | Rappresenta un incentivo statale disponibile |
| `ICittadino` | Rappresenta un cittadino che partecipa alle iniziative |

### Classi

| Classe | Implementa | Descrizione |
|--------|------------|-------------|
| `Startup` | `IStartup` | Gestisce le informazioni della startup e la ricezione di incentivi |
| `Incentivo` | `IIncentivo` | Gestisce i dettagli degli incentivi e la loro assegnazione |
| `Cittadino` | `ICittadino` | Rappresenta il cittadino e la sua partecipazione alle attività |

### Metodi principali

- `riceviIncentivo(incentivo: IIncentivo): void` — permette a una startup di ricevere un incentivo statale
- `assegnaAStartup(startup: IStartup): void` — assegna un incentivo a una startup qualificata
- `partecipaAttivita(startup: IStartup): void` — consente a un cittadino di partecipare alle attività di una startup

---

## 🔗 Link utili

- 🖥️ **CodePen** — [Visualizza il codice](https://codepen.io/simonebesutti23/pen/019d91eb-0da1-7dfe-978e-61dad8d739f4))

---

## 👨‍💻 Autore

**Simone** — Studente del corso TypeScript @ Start2Impact
