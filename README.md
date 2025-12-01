AntartideCoin (ANTR) – The ice coin

EN – AntartideCoin (ANTR) is a Scrypt-based cryptocurrency created as an independent,
experimental project. It focuses on mining, transparency and a real ecosystem
(online shop, services, games), not only on short-term speculation.

IT – AntartideCoin (ANTR) è una criptovaluta basata su algoritmo Scrypt, nata come
progetto indipendente e sperimentale. Il focus è su mining, trasparenza ed ecosistema reale
(shop online, servizi, giochi), non solo sulla speculazione di breve periodo.

Project overview / Panoramica

Algorithm / Algoritmo: Scrypt

Ticker: ANTR

Target max supply / Supply massima target: ~36.5 billion ANTR

Premine / Creator allocation: 1,500,000,000 ANTR (circa 4% della supply target)

Network: mainnet (experimental / sperimentale)

No ICO, no IDO, no private presale.
Nessuna ICO, nessuna prevendita privata.

Official links / Link ufficiali

🌐 Website / Sito ufficiale: https://antartidecoin.com

(mirror GitHub Pages: https://antartidecoin.github.io
)

🔎 Explorer: https://explorer.antartidecoin.org

⛏️ Official mining pool / Pool ufficiale: https://pool.antartidecoin.org

✉️ Contact / Contatti: info@antartidecoin.com

Wallet & download (EN/IT)
EN

The official desktop wallet for AntartideCoin is currently available for Windows as a
portable build. Downloads are provided only via official channels:

Official website – Download / Wallet section: https://antartidecoin.com

Official GitHub Releases page:
https://github.com/antartidecoin/antartidecoin.github.io/releases

The installer is currently distributed inside a password-protected archive.
The password is provided directly by the creator / team on request, in order to keep
full control during the early experimental phase.

For security reasons, a public download without password will be enabled only after
the creator reaches the milestone of 1,500,000,000 ANTR, as defined in the official
transparency rules.

⚠️ AntartideCoin Wallet is a non-custodial wallet: your private keys and the file
wallet.dat are under your sole responsibility.

IT

Il wallet desktop ufficiale di AntartideCoin è attualmente disponibile per Windows come
versione portabile. I download sono forniti solo tramite i canali ufficiali:

Sito ufficiale – sezione Download / Wallet: https://antartidecoin.com

Pagina Releases ufficiale GitHub:
https://github.com/antartidecoin/antartidecoin.github.io/releases

Al momento l’installer è distribuito all’interno di un archivio protetto da password.
La password viene fornita direttamente dal creatore / team su richiesta, per mantenere
il pieno controllo durante la prima fase sperimentale.

Per motivi di sicurezza, il download pubblico senza password verrà abilitato solo dopo
che il creatore avrà raggiunto la soglia di 1.500.000.000 ANTR, come definito nelle
regole ufficiali di trasparenza.

⚠️ AntartideCoin Wallet è un wallet non-custodial: le chiavi private e il file
wallet.dat restano sempre sotto la responsabilità dell’utente.

Mining ANTR (EN)

AntartideCoin (ANTR) uses the Scrypt algorithm. Mining is open: anyone with
compatible hardware (ASIC / GPU / Goldshell) can participate using the official pool.

1. Requirements

An ANTR address (created with the official wallet).

A Scrypt miner:

cpuminer / GPU miner, or

ASIC miner (e.g. Antminer L3+, Goldshell and similar Scrypt devices).

2. Official pool (Stratum)

URL: pool.antartidecoin.org

Ports (example configuration):

3333 – VarDiff, standard port for most miners (GPU / small ASIC).

3433 – Light VarDiff / low difficulty (when enabled).

3533 – High-diff port for powerful ASICs.

Exact parameters of the official pool (dev fee, minimum payout, confirmations)
are always visible on the pool website and in the “ANTR Pool Rules” document
in the docs/ folder.

3. Example configuration

cpuminer / GPU miner – standard port

./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3333 \
  -u YOUR_ANTR_ADDRESS \
  -p c=ANTR


cpuminer – high-diff port (powerful ASICs)

./cpuminer -a scrypt \
  -o stratum+tcp://pool.antartidecoin.org:3533 \
  -u YOUR_ANTR_ADDRESS \
  -p c=ANTR


ASIC (e.g. Antminer L3+ / Goldshell)

URL: stratum+tcp://pool.antartidecoin.org:3333

Worker: YOUR_ANTR_ADDRESS.L3 (or similar)

Password: c=ANTR (or simply x if required)

Mining ANTR (IT)

AntartideCoin (ANTR) utilizza l’algoritmo Scrypt. Il mining è aperto:
chiunque abbia hardware compatibile (ASIC / GPU / Goldshell) può partecipare
utilizzando la pool ufficiale.

1. Requisiti

Un indirizzo ANTR (creato con il wallet ufficiale).

Un miner Scrypt:

cpuminer / miner GPU, oppure

ASIC (es. Antminer L3+, Goldshell e modelli Scrypt simili).

2. Pool ufficiale (Stratum)

URL: pool.antartidecoin.org

Porte (configurazione di esempio):

3333 – VarDiff, porta standard per la maggior parte dei miner (GPU / ASIC piccoli).

3433 – VarDiff leggera / bassa difficoltà (quando attiva).

3533 – Porta ad alta difficoltà per ASIC potenti.

I parametri esatti della pool ufficiale (dev fee, payout minimo, conferme) sono
sempre visibili sul sito della pool e nel documento “Regolamento pool ANTR”
presente nella cartella docs/.

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


ASIC (es. Antminer L3+ / Goldshell)

URL: stratum+tcp://pool.antartidecoin.org:3333

Worker: TUO_INDIRIZZO_ANTR.L3

Password: c=ANTR (oppure x se richiesto)

Documentation (PDF, EN/IT)

Official documents are stored in the docs/ folder, for example:

ANTR_Whitepaper_EN_IT.pdf – technical & economic overview / panoramica tecnica ed economica

ANTR_Emission_and_Supply_Rules_EN_IT.pdf – block rewards, supply, premine rules

ANTR_Official_Pool_Rules_EN_IT.pdf – official ANTR mining pool regulation

ANTR_Rewards_and_Supply_Report_01_EN_IT.pdf – first rewards & supply transparency report

Updated versions will keep the same filenames.
Le versioni aggiornate manterranno gli stessi nomi file.

Legal / risk notice

EN – AntartideCoin is an experimental project. Holding or using ANTR involves risks
(volatility, technical issues, regulatory uncertainty). Nothing in this repository, on the
website or in the PDFs is financial, legal or tax advice. Always do your own research.

IT – AntartideCoin è un progetto sperimentale. Detenere o utilizzare ANTR comporta rischi
(volatilità, problemi tecnici, incertezza normativa). Nulla in questa repo, nel sito o nei PDF
costituisce consulenza finanziaria, legale o fiscale. Informati sempre in autonomia.
