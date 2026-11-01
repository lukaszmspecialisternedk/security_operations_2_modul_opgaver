# Module 2: DNS

## 1\. Skriv et script der konstruere og sender en DNS forspørgsel over UDP

Screencaps af indholdet i "simple_dns_resolver_client.py" scriptet (uden importerede pre-made DNS resolver libraries):

Del. 1:

<img width="799" height="625" alt="Skærmbillede 2026-10-26 122610" src="https://github.com/user-attachments/assets/cdf86d53-a7c9-4394-80c4-151ef74d003e" />

Del. 2:

<img width="802" height="592" alt="Skærmbillede 2026-10-26 122850" src="https://github.com/user-attachments/assets/76194274-cda2-4f72-9321-46770b0b9ed1" />

Del. 3:

<img width="804" height="553" alt="Skærmbillede 2026-10-26 124144" src="https://github.com/user-attachments/assets/a1a2ea98-06a7-4e40-af2b-ac67afaa034e" />

Del. 4:

<img width="790" height="544" alt="Skærmbillede 2026-10-26 124426" src="https://github.com/user-attachments/assets/91c9914a-738a-4ee5-ab9e-9cce9cfb284b" />

Del. 5:

<img width="790" height="559" alt="Skærmbillede 2026-10-26 124635" src="https://github.com/user-attachments/assets/662057cd-53b2-430e-9fd7-e7cbef06d2cc" />

Del. 6:

<img width="796" height="550" alt="Skærmbillede 2026-10-26 130209" src="https://github.com/user-attachments/assets/879454a1-3d0d-43b7-afe5-23c7db19aa37" />

Del. 7:

<img width="799" height="553" alt="Skærmbillede 2026-10-26 130345" src="https://github.com/user-attachments/assets/07037c51-16fe-45a9-a6c2-983c12e6a36c" />

Del. 8:

<img width="804" height="786" alt="Skærmbillede 2026-10-26 131041" src="https://github.com/user-attachments/assets/ebd481b7-e7d4-4867-a99d-4dd0cfb8d43b" />

Del. 9:

<img width="805" height="786" alt="Skærmbillede 2026-10-26 131342" src="https://github.com/user-attachments/assets/a14c0d35-710e-4ce3-848d-9a60c4488c6c" />

Del. 10:

<img width="801" height="786" alt="Skærmbillede 2026-10-26 131804" src="https://github.com/user-attachments/assets/1cc4b7e1-09d1-4ffc-8fdf-4cfa6e4e95cb" />

## 2\. Konfigurere en lokal navnopløsning i VM, så den peger på localhost:

Opretter en entre og peger 127.0.0.1 på "network.test":

<img width="341" height="279" alt="Skærmbillede 2026-11-01 230711" src="https://github.com/user-attachments/assets/d402e17f-d574-42fb-8623-62d274673bba" />

Tjekker indholdet af /etc/hosts er i orden:

<img width="348" height="282" alt="Skærmbillede 2026-11-01 230741" src="https://github.com/user-attachments/assets/6ca0e46f-edd3-486a-92ce-f2c374536ada" />

Genstarter systemd-hostnamed med den entre for at sikre navnopløsningen er aktiv og kører:

<img width="335" height="275" alt="Skærmbillede 2026-11-01 231321" src="https://github.com/user-attachments/assets/03ac098b-aa50-47bf-8b7f-cb5df20e09f0" />

<img width="340" height="280" alt="Skærmbillede 2026-11-01 231347" src="https://github.com/user-attachments/assets/ec71a7de-7f18-4930-afaa-449c74607e87" />

## 3\. Undersøg recodtyperne A, CNAME, MX, TXT og NS - forklar deres formål:

Beskrivelse af recordtyperne:

A: Denne recordtype vedrøre domænet's IPv4 addresse (i kontrast til AAAA, som gælder for dens IPv6 adresse). 

CNAME: Betyder "canonical name". Det er det læselige "alias" (domæne) for IP adressen.

MX: Er en forkortelse for "Mail exchange". Det kan henvise til at domænet/serveren anvendes til afsende og modtage emails.

TXT: Er synonymt for "text". Det er forskelligt information omkring domænet der ofte benyttes til verificering (SPF,DKIM m.m). Kan også være en kilde til andet menneskeligt læsebart information.

NS: Henviser til "Name server". Denne recordtype peger på de name servers der er autorative for domænet.

## 4\. Opfang et DNS opslag i WireShark og identificere query, response, transaktion-ID og TTL: 

## 5\. Bilag

Projektstyring:

