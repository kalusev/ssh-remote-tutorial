# Tutorijal za uspostavljanje konekcije sa serverom (SSH Remote) preko Visual Studio Code-a

Potrebno je prvo da instalirate Visual Studio Code odlaskom na link https://code.visualstudio.com/download i da izaberete odgovarajuću verziju, u skladu sa Vašim operativnim sistemom.

![vscode download](https://user-images.githubusercontent.com/97163298/149322222-1ae4f62f-e358-440e-afe5-f9d3780dff6d.png)

Posle, uspešne instalacije, pokrenete Visual Studio Code i odete na dugme Extension Marketplace, kako biste instalirali Remote SSH Plugin. U search polje ukucajte remote ssh, odaberete odgovarajući paket i u desnom prozoru kliknete na install.

![extesion market](https://user-images.githubusercontent.com/97163298/149329451-ee04ebe6-3374-4404-9b4b-09943bbed226.png)

![install ssh](https://user-images.githubusercontent.com/97163298/149329928-f53f269b-55f3-4cd6-8241-5739232d2f45.png)

Zatim, idete na dugme Remote Explorer  i posle idete na dugme **+**, kako biste konfigurisali vezu, otvoriće Vam se novi prozor gde je potrebno da ukucate **ssh username@147.91.175.237 -p 52626** (username zamenite sa Vama dodeljenim username-om).

![ssh remote](https://user-images.githubusercontent.com/97163298/149327937-c341e141-8355-418d-b92a-bbe046043be0.png)

U slučaju da Vam se pojavi novi prozor Select the platform of the remote host izaberite opciju Linux.

![ssh remote](https://user-images.githubusercontent.com/97163298/149331345-bb557ade-3b60-4be3-907b-352bb92967aa.png)

Sada bi trebalo da u gornjem levom uglu ispod **SSH TARGETS** vidite da je konfigurisan remote host **147.91.175.237**.





