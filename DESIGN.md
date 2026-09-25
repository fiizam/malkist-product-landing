# DESIGN.md — Roma Malkist Belgian Style Chocolate Landing Page

## Goal
Buat landing page produk yang terasa premium, energetic, crunchy, appetizing, dan modern.

Desain harus fokus pada produk dan visual makanan, bukan template UI generik.

Gunakan anti-slop skills selama proses desain dan audit hasil akhir.

---

## Brand Direction

### Mood
- premium food advertising
- bold
- crunchy
- chocolate-rich
- warm
- playful tapi tetap rapi
- modern editorial

### Hindari
- AI slop
- SaaS-style landing page
- glassmorphism berlebihan
- gradient random
- terlalu banyak rounded card
- shadow besar di semua elemen
- icon dekoratif tanpa fungsi
- feature card grid generik
- fake statistics
- testimonial palsu
- badge berlebihan
- copywriting klise
- section terlalu simetris

---

## Color Palette

Gunakan warna yang terinspirasi langsung dari kemasan produk.

### Primary
- Dark Chocolate: `#3B1B12`
- Deep Cocoa: `#5A2A18`
- Biscuit Gold: `#D89A35`
- Warm Cream: `#F4E7CF`

### Accent
- Roma Red: `#B91818`
- Package Blue: `#54BFE8`

### Neutral
- Near Black: `#17120F`
- Soft White: `#FFF9F1`

Jangan pakai semua warna sekaligus.
Dominan tetap chocolate + cream + biscuit gold.

---

## Typography

Gunakan kombinasi:
- display font bold / condensed untuk headline
- sans-serif bersih untuk body

Karakter headline:
- besar
- editorial
- pendek
- kuat
- tidak generik

Contoh gaya copy:
- CRUNCH INTO CHOCOLATE
- 7 LAYERS. ONE SERIOUS CRUNCH.
- CRISP. CHOCOLATE. DONE RIGHT.
- BUILT FOR THE CRUNCH.

Hindari:
- “Experience the best”
- “Discover excellence”
- “Why choose us”
- “Premium quality for everyone”
- “Crafted with passion”

---

## Layout Principles

### Hero
- fullscreen atau near-fullscreen
- produk menjadi visual utama
- packaging besar
- copy pendek
- whitespace cukup
- jangan terlalu banyak tombol
- satu CTA utama

### Section Rhythm
Jangan bikin semua section dengan pola:
text kiri + image kanan.

Variasikan:
- centered hero
- oversized typography
- pinned section
- asymmetric layout
- full-width image
- horizontal marquee
- dark immersive section
- large product close-up

Gunakan pacing visual yang berbeda antar section.

---

## Required Sections

1. Navbar minimal
2. Hero fullscreen
3. Product reveal
4. “7 Crunchy Layers”
5. Chocolate-focused immersive section
6. Product highlights
7. Marquee
8. Final product CTA
9. Footer minimal

---

## Assets

Gunakan aset yang sudah tersedia di project:

- packaging transparent PNG
- hero composition
- floating biscuit stack
- chocolate / crumb splash

Jangan gunakan placeholder setelah aset asli tersedia.

Produk harus terlihat tajam, besar, dan tidak tenggelam oleh dekorasi.

---

## Animation Direction

Gunakan:
- GSAP
- ScrollTrigger
- Lenis

### Allowed animations
- text reveal
- mask reveal
- parallax ringan
- pinned scroll
- image scale
- subtle rotation
- biscuit floating
- chocolate / crumb motion
- marquee
- section transition
- product depth movement

### Rules
- animasi harus punya tujuan
- jangan animasikan semua elemen
- hindari bounce berlebihan
- hindari looping random
- hindari easing terlalu “game-like”
- jaga durasi tetap smooth
- hormati `prefers-reduced-motion`

---

## Hero Direction

Produk menjadi focal point utama.

Gunakan:
- package transparent PNG atau hero composition
- floating biscuit stack sebagai depth layer
- crumb / chocolate splash sebagai decorative motion layer

Copy hero harus maksimal 1–2 baris besar.

Jangan buat hero seperti SaaS:
headline + paragraph + 2 CTA + 3 badge + dashboard mockup.

---

## 7 Crunchy Layers Section

Buat section ini sebagai storytelling visual.

Bisa:
- pinned section
- biscuit image membesar saat scroll
- teks “7 Crunchy Layers”
- layer text muncul bertahap
- crumbs ikut bergerak ringan

Jangan pakai 7 cards.

---

## Chocolate Section

Gunakan background dark chocolate.

Buat section terasa immersive:
- large typography
- close-up product
- chocolate splash
- subtle parallax

Jangan pakai card.

---

## Product Highlights

Batasi 3–4 highlight saja.

Contoh:
- 7 Crunchy Layers
- Belgian Style Chocolate
- Crispy Texture
- Halal Certified

Presentasi jangan berupa grid card generik.

Gunakan:
- large text blocks
- editorial layout
- stacked sections
- visual-number treatment

---

## Marquee

Gunakan teks pendek seperti:

CRUNCHY • CHOCOLATE • MALKIST • CRUNCHY • CHOCOLATE •

Marquee harus subtle dan tidak terlalu cepat.

---

## Mobile

Mobile layout harus didesain khusus, bukan sekadar desktop yang diperkecil.

Pastikan:
- headline tidak terlalu tinggi
- gambar tidak overflow
- animasi lebih ringan
- pinned section tidak mengganggu scroll
- tap target cukup besar
- layout tetap punya hierarchy

---

## Performance

- optimalkan PNG/WebP
- lazy load image non-critical
- preload hero image bila perlu
- batasi animasi GPU berat
- hindari blur besar
- hindari canvas/WebGL bila tidak perlu
- jangan install library berlebihan

---

## Accessibility

- semantic HTML
- alt text
- contrast cukup
- keyboard accessible
- focus state jelas
- reduced motion support

---

## Anti-Slop Checklist

Sebelum dianggap selesai, cek:

- Apakah tampilannya terasa seperti template AI?
- Apakah terlalu banyak rounded card?
- Apakah semua section terlalu simetris?
- Apakah terlalu banyak gradient?
- Apakah typography terlalu generik?
- Apakah copywriting terdengar klise?
- Apakah animasi terlalu ramai?
- Apakah produk masih menjadi fokus utama?
- Apakah setiap section punya alasan visual?
- Apakah layout punya variasi dan rhythm?
- Apakah mobile terasa didesain, bukan dipaksa?

Kalau jawabannya iya pada poin negatif di atas, revisi.

---

## Final Quality Bar

Hasil akhir harus terasa seperti:
- branded product landing page
- modern food campaign
- strong visual direction
- custom-designed
- editorial
- motion-driven
- premium

Bukan:
- AI-generated template
- generic Tailwind landing page
- SaaS website
- component showcase