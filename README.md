# Droid TV — Releases

Repositório público que hospeda binários e o `manifest.json` de OTA do Droid TV.

- `manifest.json` — descreve a versão mais recente (versionCode, versionName, URL do APK, notas).
- APKs publicados via GitHub Releases (`v0.X.Y`) e referenciados pelo manifest.

O app polla este `manifest.json` ao abrir Home e oferece atualização quando `versionCode` é maior que o instalado.
