# IPTV Shol ⚽📺

Playlist IPTV sport — dikurasi & di-test otomatis dengan **ffprobe** (verifikasi segmen video asli, bukan cuma HTTP 200).

**Terakhir diuji: 22 November 2026**

## File

| File | Isi |
|---|---|
| `sports.m3u` | 118 channel sport publik terverifikasi live |
| `epl.m3u` | 61 channel fokus bola (beIN, TNT, Sky, ESPN, dll) |
| `subscription-bola.m3u` | **136 channel bola dari langganan** (Sky Sport Calcio, DAZN, beIN, Blue Sport, MySports) |
| `subscription-sport-all.m3u` | **199 channel sport lengkap dari langganan** |
| `sky-premiere-league.m3u` | 4 channel Sky Sport Premiere League 1-4 ⚠️ **MATI (HTTP 407)** |

## Cara pakai di VLC

**Laptop:** `Media → Open Network Stream (Ctrl+N)` → paste raw URL.

**HP Android:** VLC → tab Browse → kotak `Stream` → paste raw URL.

**iPhone:** VLC → Network → Open Network Stream → paste URL.

### Raw URL

```
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/sports.m3u
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/epl.m3u
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/subscription-bola.m3u
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/subscription-sport-all.m3u
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/sky-premiere-league.m3u
```

## Statistik langganan (22 Nov 2026)

- Total channel: **1.119**
- Kategori: 29 (dominan Italia & Swiss)
- Channel sport-related: 383
- Channel sport LIVE (ffprobe): **199**
- Channel bola LIVE: **136**
- Kualitas tertinggi: **3840x2160 (4K)** — CH: Blue Sport 1/2 UHD

### Catatan langganan

- ⚠️ Header playlist berisi pesan **"Your subscription is almost expired"**
- Channel UK berlabel `LQ` tapi kenyataannya 1080p — label tidak akurat
- **Sky Sport Premiere League 1-4 MATI** (HTTP 407 Proxy Auth Required). Channel Swiss yang hidup: `CH: Sky Sport Ligue1 1` (303573) dan `Sky Sport 16/17/18` (303570-303572)
- Sky Sports Main Event UK pakai feed berbeda dari Sky UK asli (jadwal EPL bisa tidak sesuai)
- Sky Sport 1/2/3/5/6/8/9 hidup tapi sedang tayang **holding screen** ("Auf diesem Sender wird zurzeit nicht gesendet")

## Disclaimer

Channel publik bersumber dari playlist terbuka (iptv-org, all_sport, InstaTechHD, tamjid, dll). Link IPTV publik sering mati dalam hitungan hari/minggu — re-test & update kalau ada yang mati.

Channel langganan (`subscription-*.m3u`) berasal dari akun pribadi; kalau langganan expired, semua link di file itu akan mati.
