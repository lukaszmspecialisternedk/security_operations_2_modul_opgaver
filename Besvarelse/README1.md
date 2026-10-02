# Module 1

## 1. Byg en simpel TCP echo-server og client der sender der modtager tekst over 127.0.0.1 (localhost):

Eksekvering af echo_server script:

<img width="809" height="503" alt="Skærmbillede 2026-09-30 140607" src="https://github.com/user-attachments/assets/37d8a5fd-e2b7-4935-a487-94b748e8b572" />

Test af serveren med en client (netcat - nc):

<img width="808" height="507" alt="Skærmbillede 2026-09-30 140419" src="https://github.com/user-attachments/assets/c1d880eb-ad0a-424e-93a3-cd97d74b029f" />

Klientens response opfanges i echo serveren over localhost:

<img width="808" height="503" alt="Skærmbillede 2026-09-30 140442" src="https://github.com/user-attachments/assets/5169fd04-2b0b-48e3-95c0-9df84361c7b3" />

## 2. Fang en forbindelse i Wireshark og identificér SYN, SYN-ACK, ACK, FIN og RST i capture:

Installation af Wireshark:

<img width="349" height="275" alt="Skærmbillede 2026-09-30 141241" src="https://github.com/user-attachments/assets/4abc8bbe-e092-4434-a98c-51ad3b5e4c73" />

Packet capture med Wireshark:


## 3. Beskriv kort forskellen på TCP og UDP, og hvorfor HTTP er bygget oven på TCP og ikke UDP:

TCP i forhold til UDP er mere robust i dens kommunikation. Derfor anvendes det underlæggende til protokoller, som f.eks. HTTP. UDP er mindre robust og kan ikke garantere pakkerne når sin destination. 

## 4. Brug netstat eller ss til at vise din servers aktive forbindelse på loopback, mens en klient er tilsluttet:

## 5. Bilag
Projektstyring
