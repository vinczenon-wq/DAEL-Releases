# DAEL v0.9.2 — Note di rilascio

**Versione:** v0.9.2 · **Codice versione:** 42 · **Pacchetto Android:** `com.dael.reader`

DAEL è un lettore digitale Android gratuito, in fase beta. Questa build è stata verificata nell'aggiornamento da DAEL 0.9.1 a 0.9.2 mantenendo libreria, preferiti, progressi di lettura e funzione «Riprendi».

## Download
- `DAEL-v0.9.2-arm64-v8a.apk` — APK per dispositivi Android ARM64 (27.666.756 byte)
- `DAEL-v0.9.2.apk` — APK universale per più architetture (68.107.090 byte)
- `SHA256SUMS.txt` — checksum SHA-256 ufficiali per verificare gli APK

## Integrità SHA-256
```text
53965ee6c118f389c33452301bc98b5139ecb64175714518538f67550f13b47f  DAEL-v0.9.2-arm64-v8a.apk
7fd2c1eb0c4fee1290aadb66bb208c333cdd029700bf285f0e7f942f6818c045  DAEL-v0.9.2.apk
```

I checksum sono stati verificati confrontando i due APK originali con `SHA256SUMS.txt` estratto dall'artifact firmato del run CI `45440433180`.

**Installazione:** eseguire il backup dei dati prima dell'aggiornamento. Installare l'APK ufficiale sopra la versione precedente; non disinstallare la vecchia app. Android può chiedere il permesso per installare APK esterni.

**Nota sul sistema di aggiornamenti:** 0.9.2 è configurata per leggere le versioni pubbliche di questo repository. L'aggiornamento interno verso una versione successiva non è ancora stato testato end-to-end e non va presentato come collaudato.

**Contenuti:** DAEL non fornisce libri, fumetti, opere o fonti editoriali preconfigurate. Usa contenuti e servizi autorizzati.

## Lista di controllo per pubblicazione
- [x] Compilation release riuscita, con firma APK verificata nel workflow GitHub Actions.
- [x] APK ARM64 e universale originali recuperati senza ricompilarli.
- [x] Checksum SHA-256 verificati localmente per entrambi i file.
- [x] Installazione 0.9.2 sopra 0.9.1, libreria e progressi confermati da test dell'utente.
- [ ] Pubblicare una Release con tag esatto `v0.9.2` e allegare tutti e tre i file.
- [ ] Verificare gli URL pubblici e la lettura da parte dell'updater DAEL.
