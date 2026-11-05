# 🎲 Dice-cise

Permainan latihan kognitif (ejaan suku kata) + senaman fizikal untuk Unit Fisioterapi.

- **Satu fail sahaja**: `index.html` — buka terus dalam browser (Chrome/Edge/Safari). Tiada backend, tiada login, boleh run **offline**.
- Mesra tablet & skrin TV: butang besar, font besar, kontras tinggi. Butang ⛶ untuk skrin penuh.

## Cara main
1. Pilih **Tahap Kognitif** (1 = eja 1 patah perkataan, 2 = 2 perkataan, 3 = 3 perkataan setiap pusingan) → **Mula**.
2. **Baling Dadu Kategori**: 1 & 4 = Kenderaan 🚗, 2 & 5 = Makanan 🍜, 3 & 6 = Tempat 🏫.
3. Eja perkataan penuh huruf demi huruf (kiri → kanan) guna papan kekunci A–Z. Gambar emoji jadi petunjuk.
4. Salah huruf → **Dadu Hukuman**: 1 Duduk-Berdiri · 2 Angkat Tumit · 3 Angkat Peha · 4 Cangkung · 5 & 6 Baling Semula.
   Ulangan = tahap kognitif (boleh darab ×2/×3/×5 di skrin mula). Tekan **Siap 1 Ulangan** setiap kali, kemudian sambung ejaan.
5. **🏁 Tamat Sesi** untuk ringkasan (perkataan siap, kesilapan, set & ulangan setiap senaman, tempoh).

## Ubah suai
- Senarai perkataan: objek `WORDS` dalam `index.html` (format `'KE-RE-TA'`, emoji). Sempang hanya untuk jarak visual antara suku kata.
- Senaman & arahan: objek `EXERCISES`.
