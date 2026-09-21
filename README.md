# CIMDNS

Turkiye icin ozgur ve hizli DNS araci.

CIMDNS.bat cift tikla acilir. Ilk acilista sorar:

```
Kurulum yapilsin mi (E/H):
```

E dersen %APPDATA%\CIMDNS altina kopyalanir, her Windows acilisinda arkada calisir.
H dersen yeni bir CMD acilir ve DNS orada baglanir. O pencereyi kapatirsan baglanti kesilir.

Komutlar:

```
CIMDNS.bat --run-server
CIMDNS.bat --background
CIMDNS.bat --uninstall
```

Calisma mantigi: Aktif ag bagdastiricilarinin DNS adresini 1.1.1.1 ve 8.8.8.8 yapar, cikista otomatige geri alir.

MIT Lisansi.
Rahatlikla forklanabilir ve sadece Windows icin calisir.
