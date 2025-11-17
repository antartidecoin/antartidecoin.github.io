# AntartideCoin (ANTR) – The ice coin

> **EN** – AntartideCoin (ANTR) is a Scrypt-based cryptocurrency created as an independent,  
> experimental project. It focuses on mining, transparency and a real ecosystem  
> (online shop, services, games), not only on short-term speculation.

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

## Official links / Link ufficiali

- **Website / Sito ufficiale:** https://antartidecoin.com
- **Explorer:** https://explorer.antartidecoin.org
- **Official mining pool / Pool ufficiale:** https://pool.antartidecoin.org
- **Contact / Contatti:** info@antartidecoin.com

---

## Mining ANTR (EN)

AntartideCoin (ANTR) uses the **Scrypt** algorithm. Mining is open: anyone with
compatible hardware (ASIC / GPU) can participate using the official pool.

### 1. Requirements

- An **ANTR address** (created with the official wallet).
- A Scrypt miner:
  - `cpuminer` / GPU miner, or
  - ASIC miner (e.g. Antminer L3+ and similar).

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


---

## Creator premine & ethical rules (riassunto)

- **Premine:** 1,500,000,000 ANTR to creator-controlled wallets, for:
  development, infrastructure, security, future marketing and treasury.
- **No hidden premine:** this is the **only** premine; no secret extra allocations.
- **No ICO / no private sale:** the creator will not run ICO or private pre-sales.
- **10× rule for selling creator funds:**
  - Reference starting price (P0): `0.0001 EUR` per ANTR (indicative listing price).
  - At each new **10×** price level (0.001, 0.01, 0.1, …) the creator may sell at most  
    **10% of the initial premine** (150,000,000 ANTR per level).
  - Between two 10× levels, the creator does **not** sell on the market.
  - Major sales should be announced publicly with motivation
    (development, infrastructure, listings, marketing, ecc.).

Dettagli completi e versioni ufficiali sono nei PDF di regole e nel sito.

---

## Official links

- 🌐 **Website:** https://antartidecoin.github.io  
- 🔎 **Explorer:** https://explorer.antartidecoin.org  
- ⛏️ **Official pool:** https://pool.antartidecoin.org  
- ✉️ **Contact:** `info@antartidecoin.com`

(Quando il dominio `antartidecoin.com` sarà collegato a GitHub Pages, aggiungeremo anche quello.)

---

## Documentation (PDF, EN/IT)

Tutti i documenti ufficiali sono nella cartella [`docs/`](docs/):

- `ANTR_Whitepaper_EN_IT.pdf` – Technical and economic overview / panoramica tecnica ed economica  
- `ANTR_Emission_and_Supply_Rules_EN_IT.pdf` – Block rewards, supply, premine rules  
- `ANTR_Official_Pool_Rules_EN_IT.pdf` – Official ANTR mining pool regulation  
- `ANTR_Rewards_and_Supply_Report_01_EN_IT.pdf` – First rewards & supply transparency report  

Updated versions will keep the same filenames.  
Le versioni aggiornate manterranno gli stessi nomi file.

---

## Status & roadmap (short)

- **2026:** mainnet, nodes, official explorer & pool, first desktop wallet.  
- **2027:** improved wallet, first integrations with Antartide services / shop, public docs.  
- **2028:** ecosystem expansion (services, games, merchant tools, first exchange listings to be evaluated).  
- **Future:** planned hard fork on supply/rewards at defined milestones (e.g. around 1B ANTR),
  deeper integration with AntartideShop.com and possible shared governance for treasury.

See the website for the full roadmap (EN/IT).  
Vedi il sito per la roadmap completa (EN/IT).

---

## Legal / risk notice

> **EN** – AntartideCoin is an experimental project. Holding or using ANTR involves risks  
> (volatility, technical issues, regulatory uncertainty). Nothing in this repository, website  
> or PDFs is financial, legal or tax advice. Always do your own research.

> **IT** – AntartideCoin è un progetto sperimentale. Detenere o utilizzare ANTR comporta rischi  
> (volatilità, problemi tecnici, incertezza normativa). Nulla in questa repo, nel sito o nei PDF  
> costituisce consulenza finanziaria, legale o fiscale. Informati sempre in autonomia.
