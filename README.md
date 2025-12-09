# Build Week 3: Cyber Security & Ethical Hacking

Questo repository contiene il lavoro svolto dal **Team GhostProtocol** durante la terza Build Week, incentrata su sfide pratiche e concetti fondamentali di **Cyber Security & Ethical Hacking**.

Il progetto ha richiesto l'applicazione di strumenti di analisi forense, l'esplorazione di sistemi operativi Linux, l'analisi di traffico di rete e l'identificazione di vulnerabilità.

---

## Obiettivi e Sfide del Progetto

Il progetto è stato suddiviso in diverse sfide pratiche, ciascuna mirata a consolidare specifiche competenze di analisi e difesa:

* **Esercizio 1: Malware Analysis**
    * Scarico e analisi completa di un file eseguibile malevolo, pulizia delle tracce e creazione di un report.
* **Esercizio 2: Server Linux & Analisi di Rete**
    * Utilizzo della riga di comando Linux per identificare servizi in esecuzione (`ps`), analizzare le connessioni di rete (`netstat`) e testare servizi TCP con `Telnet`.
* **Esercizio 3: Filesystem Linux e Permessi**
    * Navigazione nel filesystem, identificazione e montaggio di partizioni (`lsblk`, `mount`), e manipolazione dei permessi e della proprietà di file e directory (`chmod`, `chown`).
* **Esercizio 4: Analisi del Traffico (HTTP/HTTPS)**
    * Cattura e analisi del traffico di rete (HTTP e HTTPS) utilizzando `tcpdump` e `Wireshark` per evidenziare la differenza tra comunicazioni in chiaro e crittografate.
* **Esercizio 5: Anyrun Sandbox**
    * Analisi di minacce utilizzando la sandbox online Anyrun e produzione di un report di remediation per un cliente non tecnico.
* **Esercizio 6: Forensics su PCAP**
    * Analisi forense di un file PCAP (cattura pacchetti) per estrarre e identificare un eseguibile malevolo scaricato.
* **Tracce Bonus (Investigazione e Exploitation):**
    * **Bonus 1:** Interpretazione di log HTTP e DNS in Kibana per isolare attori di minaccia (SQL injection e esfiltrazione dati DNS).
    * **Bonus 2:** Isolare un host compromesso in Sguil e Kibana utilizzando la 5-Tupla e investigare l'esfiltrazione di file tramite FTP.
    * **Extra 2:** Analisi e cracking di una vulnerabilità di **Buffer Overflow** (`jmp esp` technique) su un binario `oscp.exe`.

---

## Strumenti Principali Utilizzati

Abbiamo lavorato principalmente in ambienti Linux (VM CyberOps Workstation, Kali Linux, Security Onion) e abbiamo utilizzato i seguenti strumenti:

| Categoria | Strumenti | Descrizione / Ruolo |
| :--- | :--- | :--- |
| **Networking/Forensics** | `tcpdump`, `Wireshark` | Cattura e analisi dettagliata dei pacchetti di rete. |
| **Diagnostica di Rete** | `netstat`, `Telnet` | Identificazione dei servizi in ascolto e test delle connessioni TCP. |
| **Linux Core** | `ps`, `lsblk`, `mount`, `chmod`, `chown` | Gestione di processi, filesystem, permessi e proprietà. |
| **Log Analysis** | Kibana, Sguil | Analisi di eventi, log e alert di sicurezza (SIEM/NIDS). |
| **Malware Sandbox** | Anyrun | Analisi dinamica dei campioni di malware in ambiente isolato. |
| **Exploitation** | Immunity Debugger, Mona, `msfvenom` | Fasi di debug, calcolo offset e generazione di shellcode. |

---

## Team GhostProtocol

Questo progetto è stato realizzato grazie alla collaborazione e all'impegno di:

* **Iris Canole**
* **Federico Giannini**
* **Daniele Castello**
* **Luca Pani**
* **Rosario Papa**
* **Yari Olmi**
* **Alessandro Salerno**
