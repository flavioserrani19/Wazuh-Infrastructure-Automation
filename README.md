\# Wazuh-Infrastructure-Automation



Progetto di automazione e configurazione di un'infrastruttura di sicurezza basata su \*\*Wazuh\*\*, gestita tramite \*\*Ansible\*\*. Il progetto documenta la creazione di un ambiente sicuro, la gestione delle criticità di sistema e il monitoraggio proattivo.



\## Obiettivo del Progetto

L'obiettivo è la distribuzione automatizzata di un agente Wazuh su una macchina target (Web), risolvendo le sfide di connettività, autenticazione crittografica (GPG/SSH) e gestione delle risorse di sistema.



\## Tecnologie Utilizzate

\- \*\*Wazuh\*\*: SIEM/XDR per la sicurezza.

\- \*\*Ansible\*\*: Automazione della configurazione.

\- \*\*SSH/GPG\*\*: Gestione della sicurezza e dell'autenticità dei pacchetti.

\- \*\*Linux (Debian/Ubuntu)\*\*: Sistema operativo di riferimento.



\## Workflow e Troubleshooting

La documentazione segue il ciclo di vita del progetto, dalla configurazione iniziale alla risoluzione delle anomalie:



1\. \*\*Configurazione SSH\*\*: Creazione del canale sicuro tra Manager e Agente.

2\. \*\*Automazione\*\*: Distribuzione via Ansible.

3\. \*\*Gestione Criticità\*\*:

&#x20;  - Risoluzione errore GPG (`NO\_PUBKEY`).

&#x20;  - Gestione saturazione storage su `/var`.

4\. \*\*Validazione\*\*: Monitoraggio log di sistema e intercettazione minacce via \*Rootcheck\*.



\## Conclusioni

Il progetto ha dimostrato la capacità di gestire un ambiente di sicurezza reale, trasformando errori bloccanti in opportunità di hardening del sistema. Il sistema è ora in grado di rilevare attivamente anomalie (Rootcheck) e tentativi di manomissione, confermando l'integrità dell'infrastruttura.

