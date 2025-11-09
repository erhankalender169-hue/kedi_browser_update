# Kedi Browser Güncelleme Sunucusu

Bu depo Kedi Browser tarayıcısı için güncelleme sunucusudur.

## Dosyalar

- `version.json` : Güncel sürüm numarası ve mesaj
- `kedi_browser.py` : Python tarayıcı dosyası

## Kullanım

1. Tarayıcı kodunda `UPDATE_URL` ve `DOWNLOAD_URL` aşağıdaki gibi olmalı:

```python
UPDATE_URL = "https://raw.githubusercontent.com/erhankalender169-hue/kedi_browser_update/main/version.json"
DOWNLOAD_URL = "https://raw.githubusercontent.com/erhankalender169-hue/kedi_browser_update/main/kedi_browser.py"
