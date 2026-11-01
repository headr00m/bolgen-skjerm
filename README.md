# Bølgen skjerm

Ferdig oppsett for en Raspberry Pi som skal vise skjermene til Bølgen kulturhus. Filen ligger under Releases og skrives til et minnekort med Raspberry Pi Imager, normalt via knappen i Bølgen Produksjonshub.

- En ny Pi viser en kode på skjermen. Ingenting skjer før en administrator har fullført oppsettet i huben.
- Kopien inneholder ingen passord, nøkler eller innlogginger. Bruker, passord og Wi-Fi velges i Imager for hvert kort.
- Pi-en oppdaterer ikke systemet av seg selv.

Bygget på Raspberry Pi OS (Debian Trixie, 64-bit) med tillegg av Bølgens oppsettfiler, for Raspberry Pi 3, 4 og 5. Pakkene og lisensene er uendret, og kildekoden finnes i arkivene til Debian og Raspberry Pi (`apt-get source <pakke>`). Dette er ikke et offisielt produkt fra Raspberry Pi.

## Sjekksummer for `bolgen-skjerm.img.xz`

- SHA-256 pakket: `a9bece42f7c58eca830e6fee0582faf8e72a8dd95c473a88a9acb9b5adae9f9c` (1406835028 byte)
- SHA-256 utpakket: `6a435b9d39f0470f24b285f3b9f08f73d4705b7e2066d84a0481f840fdf6956e` (8922705920 byte)
