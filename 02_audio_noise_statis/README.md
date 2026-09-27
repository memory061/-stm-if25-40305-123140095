# Tugas 2 — Analisis Sinyal Suara & Noise Statis

## Perangkat & Cara Perekaman
- **Perangkat rekam:** [isi merk/tipe HP atau aplikasi voice recorder yang dipakai]
- **Format asli:** direkam dalam container `.mp4` (audio ter-*encode* AAC), kemudian dikonversi ke `.wav`
- **Jarak ke sumber noise:** ±0.5–1 meter

## Sumber Noise Statis
- **Sumber:** Kipas angin
- **Alasan pemilihan:** deru baling-baling kipas berputar konstan, sesuai kriteria noise statis (stasioner) pada soal

## Metadata Rekaman
| Parameter | Nilai |
|---|---|
| Durasi | 20.44 detik |
| Laju sampel asli (fs) | 48000 Hz |
| Jumlah sampel | 980.992 |
| Amplitudo min / maks | -0.3542 / 0.4164 |

## Berkas pada Folder Ini
| Berkas | Keterangan |
|---|---|
| `tugas_audio_noise_statis.ipynb` | Notebook lengkap (akuisisi, visualisasi 4D, eksperimen resampling) |
| `tugas_audio_noise_statis.pdf` | Ekspor PDF hasil eksekusi notebook |
| `audio_original.wav` | Rekaman asli (pembacaan berita + noise kipas) |
| `audio_downsampled_naive.wav` | Hasil downsampling ke 8000 Hz tanpa filter anti-aliasing (naive decimation) |
| `audio_downsampled_clean.wav` | Hasil downsampling ke 8000 Hz dengan filter anti-aliasing |
