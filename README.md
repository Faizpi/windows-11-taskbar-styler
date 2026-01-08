# Centered Floating Taskbar (Windows 11 XAML Override via Windhawk)

Eksperimen visual taskbar Windows 11 menggunakan **XAML style overrides melalui Windhawk** untuk mengubah layout default menjadi **centered floating taskbar** dengan **rounded geometry** dan **spacing minimal**.

Repository ini berfokus pada eksplorasi UI system-level tanpa memodifikasi logic Windows Explorer.

---

## Preview

> Tampilan taskbar terpusat, floating, ikon rata tengah, dengan bentuk membulat dan layout lebih bersih dibanding default Windows 11.
<br>

![Centered Floating Taskbar](assets/preview.png)

---

## Key Features

- Centered floating taskbar dengan width otomatis
- Rounded geometry untuk tampilan modern dan minimal
- Background taskbar bawaan disembunyikan
- Spacing dan padding taskbar icons disederhanakan
- Penyesuaian system tray agar tetap selaras dengan layout floating
- Non-intrusive: hanya override visual, tanpa patch Explorer logic

---

## Implementation Details

- Menggunakan **XAML style override**
- Diterapkan melalui **Windhawk**
- Target: Windows 11 taskbar visual tree
- Tidak menggunakan registry tweak
- Tidak mengubah behavior atau event handling taskbar

Pendekatan ini cocok untuk eksperimen UI/UX dan observasi perilaku Windows Shell terhadap override berbasis XAML.

---

## Requirements

- Windows 11
- Windhawk (latest stable version)
- Taskbar berbasis XAML (default Windows 11 shell)

---

## Notes

- Struktur visual taskbar dapat berubah pada update Windows tertentu
- Selector XAML mungkin perlu disesuaikan di masa depan
- Project ini ditujukan sebagai **UI engineering experiment**, bukan solusi production-grade

---

## Use Cases

- Windows shell customization
- UI/UX engineering experiment
- Studi internal XAML override behavior
- Personal desktop setup

---

## Disclaimer

This project is provided as-is for educational and experimental purposes.  
Windows updates may affect compatibility.

---

## License

MIT License
