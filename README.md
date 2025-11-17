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
