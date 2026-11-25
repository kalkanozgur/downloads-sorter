---
title: Privacy Policy — Download Sorter
permalink: /privacy/
---

# Privacy Policy — Download Sorter

_Last updated: 2026-11-25_ · Türkçe metin aşağıda.

## Summary
Download Sorter does **not** collect, transmit, sell or share any personal data. It makes **no network requests**. Everything it stores stays in your browser.

## What the extension stores, and where

| Data | Where | Why | How to remove |
|---|---|---|---|
| Your sorting rules (site names, file extensions, folder names) | `chrome.storage.sync` — synced by your browser to your own browser account if you have sync enabled | To apply your rules on every download | Settings → "Restore defaults", or uninstall |
| Recent download history: up to 50 entries of **file name, site host name** (e.g. `files.printables.com`), chosen folder and matching rule. **Full web addresses are never stored.** | `chrome.storage.local` (this device only) | So you can see where a file went and create a rule from it | Settings → "Clear history"; turn off "Keep history" to stop recording; uninstall removes it |

## Permissions
- **downloads** — to suggest a subfolder for a file at the moment it is downloaded (`downloads.onDeterminingFilename`), and to save the rules file when you choose "Export".
- **storage** — to keep your rules and the optional local history described above.

The extension requests no host permissions, injects no scripts into web pages, and cannot read page content.

## Third parties
None. No analytics, no advertising, no remote code, no external servers.

## Changes
Changes to this policy are published at this address with a new "Last updated" date.

## Contact
Questions or requests: open an issue at <https://github.com/kalkanozgur/downloads-sorter/issues>.

---

# Gizlilik Politikası — Download Sorter

_Son güncelleme: 2026-11-25_

## Özet
Download Sorter hiçbir kişisel veriyi **toplamaz, iletmez, satmaz veya paylaşmaz**. **Hiçbir ağ isteği yapmaz.** Sakladığı her şey tarayıcınızda kalır.

## Eklentinin sakladıkları ve yeri

| Veri | Yer | Neden | Nasıl silinir |
|---|---|---|---|
| Sıralama kurallarınız (site adları, dosya uzantıları, klasör adları) | `chrome.storage.sync` — senkronizasyon açıksa tarayıcınız tarafından kendi hesabınıza senkronlanır | Her indirmede kurallarınızı uygulamak | Ayarlar → "Varsayılana dön" veya eklentiyi kaldırma |
| Son indirme geçmişi: en fazla 50 kayıt; **dosya adı, site alan adı** (ör. `files.printables.com`), seçilen klasör ve eşleşen kural. **Tam web adresi asla tutulmaz.** | `chrome.storage.local` (yalnız bu cihaz) | Dosyanın nereye gittiğini görüp ondan kural oluşturabilmeniz için | Ayarlar → "Geçmişi sil"; "Geçmişi tut" kapatılırsa kayıt durur; kaldırma hepsini siler |

## İzinler
- **downloads** — dosya indirilirken alt klasör önermek (`downloads.onDeterminingFilename`) ve "Dışa aktar" seçildiğinde kural dosyasını kaydetmek.
- **storage** — kurallarınızı ve yukarıdaki isteğe bağlı yerel geçmişi tutmak.

Eklenti site (host) izni istemez, sayfalara betik eklemez, sayfa içeriğini okuyamaz.

## Üçüncü taraflar
Yok. Analitik, reklam, uzak kod veya harici sunucu yok.

## Değişiklikler
Bu politikadaki değişiklikler bu adreste yeni "Son güncelleme" tarihiyle yayınlanır.

## İletişim
Soru ve talepler için: <https://github.com/kalkanozgur/downloads-sorter/issues> adresinde issue açın.
