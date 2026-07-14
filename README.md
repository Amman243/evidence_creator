# Evidence Marker

Tool sederhana untuk menandai gambar/screenshot sebagai evidence — 100% satu file HTML, tanpa dependency, tanpa build step.

## Cara pakai

**Paling gampang:** double-click `index.html` (atau buka lewat browser). Selesai — tidak butuh server sama sekali.

**Kalau mau lewat localhost** (port sengaja dipilih yang jarang dipakai):

```powershell
python -m http.server 47313
# lalu buka http://localhost:47313
```

## Fitur

- **Input gambar**: paste dari clipboard (`Ctrl+V`), drag & drop, atau pilih file
- **Shape**: rectangle, ellipse, arrow
- **Mode fill**: outline saja (transparan), semi-transparan (35%), atau solid — stroke selalu ada
- **Warna**: 6 preset + color picker custom, tebal stroke bisa diatur
- **Edit**: select, pindah (drag), resize (drag handle), hapus (`Delete`), undo/redo
- **Output**: export PNG (resolusi asli gambar) & copy ke clipboard

## Shortcut

| Tombol | Fungsi |
|---|---|
| `V` / `R` / `E` / `A` | Tool: select / rect / ellipse / arrow |
| `Shift` (saat drag) | Kotak/lingkaran proporsional, arrow snap 45° |
| `Ctrl+Z` / `Ctrl+Y` | Undo / redo |
| `Delete` | Hapus shape terpilih |
| `Ctrl+C` | Copy hasil ke clipboard |
| `Ctrl+S` | Export PNG |
| `Esc` | Batal / deselect |
