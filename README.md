# AntartideCoin (ANTR) – The ice coin

> **EN** – AntartideCoin (ANTR) is a Scrypt-based cryptocurrency created as an independent,  
> experimental project. It focuses on mining, transparency and a real ecosystem  
> (online shop, services, games), not only on short-term speculation.  
>
> **IT** – AntartideCoin (ANTR) è una criptovaluta basata su algoritmo Scrypt, nata come  
> progetto indipendente e sperimentale. Il focus è su mining, trasparenza ed ecosistema reale  
> (shop online, servizi, giochi), non solo sulla speculazione di breve periodo.

---

## Project overview

- **Algorithm / Algoritmo:** Scrypt  
- **Ticker:** ANTR  
- **Target max supply / Supply massima target:** ~36.5 billion ANTR  
- **Premine / Creator allocation:** 1,500,000,000 ANTR (about 4% of target supply, creator wallets)  
- **Network:** mainnet (experimental / sperimentale)  

The project does **not** run an ICO, IDO or private presale.  
Il progetto **non** prevede ICO, IDO o prevendita privata.

---

## Official links / Link ufficiali

- 🌐 **Website / Sito ufficiale:** https://antartidecoin.com  
  (mirror GitHub Pages: https://antartidecoin.github.io)  
- 🔎 **Explorer:** https://explorer.antartidecoin.org  
- ⛏️ **Official mining pool / Pool ufficiale:** https://pool.antartidecoin.org  
- ✉️ **Contact / Contatti:** `info@antartidecoin.com`

---

## Mining ANTR (EN)

AntartideCoin (ANTR) uses the **Scrypt** algorithm. Mining is open: anyone with
compatible hardware (ASIC / GPU) can participate using the official pool.

### 1. Requirements

- An **ANTR address** (created with the official wallet).
- A Scrypt miner:
  - `cpuminer` / GPU miner, or
  - ASIC miner (e.g. Antminer L3+, Goldshell and similar Scrypt devices).

### 2. Official pool (Stratum)

- URL: `pool.antartidecoin.org`
- Ports (example configuration):
  - `3333` – VarDiff, standard port for most miners (GPU / small ASIC).
  - `3433` – Light VarDiff / low difficulty (when enabled).
  - `3533` – High-diff port for powerful ASICs.

### 3. Example configuration

**cpuminer / GPU miner – standard port**

```bash
./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3333 \
  -u YOUR_ANTR_ADDRESS \
  -p c=ANTR
cpuminer – high-diff port (powerful ASICs)

./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3533 \
  -u YOUR_ANTR_ADDRESS \
  -p c=ANTR

4. ASIC example (Antminer L3+)

URL: stratum+tcp://pool.antartidecoin.org:3333

Worker: YOUR_ANTR_ADDRESS.L3

Password: c=ANTR (or simply x if required)

Exact parameters of the official pool (dev fee, minimum payout, confirmations)
are always visible on the pool website and in the “ANTR Pool Rules” document.

Mining ANTR (IT)

AntartideCoin (ANTR) utilizza l’algoritmo Scrypt. Il mining è aperto:
chiunque abbia hardware compatibile (ASIC / GPU) può partecipare utilizzando la
pool ufficiale.

1. Requisiti

Un indirizzo ANTR (creato con il wallet ufficiale).

Un miner Scrypt:

cpuminer / miner GPU, oppure

ASIC (es. Antminer L3+, Goldshell e altri dispositivi Scrypt).

2. Pool ufficiale (Stratum)

URL: pool.antartidecoin.org

Porte (configurazione di esempio):

3333 – VarDiff, porta standard per la maggior parte dei miner (GPU / ASIC piccoli).

3433 – VarDiff leggera / bassa difficoltà (quando attiva).

3533 – Porta ad alta difficoltà per ASIC potenti.

3. Esempi di configurazione

cpuminer / miner GPU – porta standard

./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3333 \
  -u TUO_INDIRIZZO_ANTR \
  -p c=ANTR


cpuminer – porta ad alta difficoltà (ASIC potenti)

./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3533 \
  -u TUO_INDIRIZZO_ANTR \
  -p c=ANTR


ASIC (es. Antminer L3+)

URL: stratum+tcp://pool.antartidecoin.org:3333

Worker: TUO_INDIRIZZO_ANTR.L3

Password: c=ANTR (oppure x se richiesto)

I parametri esatti della pool ufficiale (dev fee, payout minimo, conferme) sono
sempre visibili sul sito della pool e nel documento “Regolamento pool ANTR”.

Creator premine & ethical rules (riassunto)

Premine: 1,500,000,000 ANTR to creator-controlled wallets, for:
development, infrastructure, security, future marketing and treasury.

No hidden premine: this is the only premine; no secret extra allocations.

No ICO / no private sale: the creator will not run ICO or private pre-sales.

10× rule for selling creator funds:

Reference starting price (P0): 0.0001 EUR per ANTR (indicative listing price).

At each new 10× price level (0.001, 0.01, 0.1, …) the creator may sell at most
10% of the initial premine (150,000,000 ANTR per level).

Between two 10× levels, the creator does not sell on the market.

Major sales should be announced publicly with motivation
(development, infrastructure, listings, marketing, ecc.).

Dettagli completi e versioni ufficiali sono nei PDF di regole e nel sito.

Documentation (PDF, EN/IT)

All official documents are in the docs/
 folder:

ANTR_Whitepaper_EN_IT.pdf – Technical and economic overview / panoramica tecnica ed economica

ANTR_Emission_and_Supply_Rules_EN_IT.pdf – Block rewards, supply, premine rules

ANTR_Official_Pool_Rules_EN_IT.pdf – Official ANTR mining pool regulation

ANTR_Rewards_and_Supply_Report_01_EN_IT.pdf – First rewards & supply transparency report

Updated versions will keep the same filenames.
Le versioni aggiornate manterranno gli stessi nomi file.

Status & roadmap (short)

2026: mainnet, stable nodes, official explorer & pool, first desktop wallet.

2027: improved wallet (UI + features), first integrations with Antartide services / shop, public technical docs.

2028: ecosystem expansion (services, games, merchant tools, evaluation of first exchange listings).

Future: planned hard fork on supply/rewards at defined milestones (e.g. around 1B ANTR),
deeper integration with AntartideShop.com and possible shared governance for treasury.

See the website for the full roadmap (EN/IT).
Vedi il sito per la roadmap completa (EN/IT).

Legal / risk notice

EN – AntartideCoin is an experimental project. Holding or using ANTR involves risks
(volatility, technical issues, regulatory uncertainty). Nothing in this repository, website
or PDFs is financial, legal or tax advice. Always do your own research.

IT – AntartideCoin è un progetto sperimentale. Detenere o utilizzare ANTR comporta rischi
(volatilità, problemi tecnici, incertezza normativa). Nulla in questa repo, nel sito o nei PDF
costituisce consulenza finanziaria, legale o fiscale. Informati sempre in autonomia.







