# APRIRE UN PACCHETTO DI FIGURINE

> #### VARIABILI:
>
> - Lista_Doppioni
> - Lista_Bustina
> - Lista_Album

> #### CLASSI:
>
> - **CARTA:**
>   - _**RARITA'**_

> #### OGGETTI:
>
> - **Carta_Rara:**
>   - **RARITA'**: Rara

## LISTA DI AZIONI:

- Prendo il pacchetto
- Apro il pacchetto
- Sfilo le carte
- **FINCHE' (_While_)** _Lista_Bustina_ è **diverso da** **(_!=_)** 0
  - Controllo la carta
    - **SE** la carta è uguale a _Carta_Rara_
      - Esulto
    - **SE _NOT_** è nella _Lista_Album_
      - Attaco la carta nella _Lista_Album_
    - **ALTRIMENTI**
      - Inserisco la carta nella _Lista_Doppioni_
  - Tolgo la carta dalla _Lista_Bustina_
- **FINE CICLO**
