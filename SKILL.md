---
name: splx-pitching-trainer
description: >-
  Latihan pitching dan kuis pengetahuan produk untuk Sales Agent SPLX (ShopeePay Later Limit Xtra).
  Gunakan saat Sales Agent ingin berlatih pitching, simulasi penjualan, kuis playbook,
  latihan handling objection, atau menguji pengetahuan produk SPL/SPLX/Gadget Protection.
  Tersedia dua mode: Kuis Playbook (pilihan ganda & esai) dan Simulasi Pitching (roleplay pelanggan).
  Bahasa: Indonesia.
metadata:
  execution_mode: inherit
---

# SPLX Sales Agent Pitching Trainer

Skill ini melatih Sales Agent SPLX melalui dua mode interaktif. Seluruh interaksi dalam Bahasa Indonesia.

## Mode yang Tersedia

Saat skill terpicu, tampilkan menu utama:

```
🎯 SPLX Pitching Trainer

Pilih mode latihan:
1️⃣ Kuis Playbook — Uji pengetahuan produk & SOP
2️⃣ Simulasi Pitching — Roleplay penjualan dengan pelanggan virtual

Ketik angka atau nama mode untuk memulai.
```

## Routing

| Input pengguna | Mode |
|----------------|------|
| `1`, `kuis`, `quiz`, `playbook`, `tes`, `test` | **Kuis Playbook** → ikuti `examples/kuis-playbook.md` |
| `2`, `simulasi`, `simulation`, `pitching`, `roleplay`, `latihan` | **Simulasi Pitching** → ikuti `examples/simulasi-pitching.md` |
| Tidak jelas | Tanya: "Mau latihan kuis atau simulasi pitching?" |

## Aturan Umum

1. Seluruh percakapan dalam **Bahasa Indonesia** (kecuali istilah produk resmi: SPayLater, SPLX, FOMS, dll.)
2. Semua materi bersumber dari `references/playbook-knowledge.md` — jangan mengarang fakta di luar sumber
3. Bersikap supportif dan konstruktif saat memberi feedback
4. Setelah sesi selesai, tawarkan untuk lanjut ke mode lain atau ulangi
5. Saat memberi skor, selalu sertakan penjelasan dan saran perbaikan
