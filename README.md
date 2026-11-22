# IPTV Shol ⚽📺

Playlist IPTV sport — dikurasi & di-test otomatis (cek segmen video asli, bukan cuma HTTP 200).

## File

| File | Isi |
|---|---|
| `sports.m3u` | 53 channel sport terverifikasi live |
| `epl.m3u` | 25 channel fokus bola (beIN, TNT Sports, Sky Sport, Eleven, Setanta, dll) |

## Cara pakai di VLC

**Laptop:** `Media → Open File` → pilih `.m3u` → klik channel di playlist.

**HP Android:** Buka VLC → tab Browse → kotak `Stream` → paste raw URL (untuk auto-update) atau download file-nya dulu lalu buka via Files.

**iPhone:** VLC → Network → Open Network Stream → paste raw URL.

### Raw URL (auto-update dari repo)

```
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/sports.m3u
https://raw.githubusercontent.com/sholud09114-code/iptv-shol/main/epl.m3u
```

> Catatan: repo ini private. Kalau VLC di HP minta login saat akses raw URL, buka `Settings → Repo → Change visibility → Public` di GitHub, atau buat token fine-grained dengan akses baca repo ini.

## Disclaimer

Semua stream bersumber dari playlist publik (iptv-org, tamjid-200, 0215liyou, InstaTechHD, dll). Link IPTV publik sering mati dalam hitungan hari/minggu — kalau ada yang mati, re-test & update file di repo ini.
