<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Griya Karya Amil (GKA) — Filantropi Tenaga & Kerja Nyata</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-stone-50 text-stone-800 antialiased overflow-x-hidden">

    <!-- W6: BANNER STATUS SIMULASI WAJIB DI SETIAP HALAMAN/TAMPILAN -->
    <div class="sticky top-0 z-50 bg-amber-500 text-stone-950 px-4 py-2 text-center text-xs sm:text-sm font-bold shadow-md">
        ⚠️ SIMULASI – TUGAS KULIAH | Seluruh data, transaksi, dokumentasi, dan nomor rekening adalah fiktif untuk keperluan akademik.
    </div>

    <!-- NAVIGASI 7 HALAMAN/BAGIAN WAJIB (W2 & W8) -->
    <header class="bg-emerald-950 text-white sticky top-9 sm:top-9 z-40 shadow-lg border-b border-emerald-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Logo SVG Orisinal & Nama Lembaga -->
                <a href="#beranda" class="flex items-center gap-3 shrink-0">
                    <svg class="w-9 h-9 text-amber-400" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect width="40" height="40" rx="10" fill="#064E3B"/>
                        <path d="M20 8L8 18H12V30H28V18H32L20 8Z" stroke="#FBBF24" stroke-width="2.5" stroke-linejoin="round"/>
                        <path d="M16 23C16 20.7909 17.7909 19 20 19C22.2091 19 24 20.7909 24 23V30H16V23Z" fill="#34D399"/>
                    </svg>
                    <div>
                        <span class="font-extrabold text-base sm:text-lg tracking-tight block leading-none">Griya Karya Amil</span>
                        <span class="text-[11px] text-emerald-300 font-medium">Filantropi Tenaga & Kerja Nyata</span>
                    </div>
                </a>

                <!-- Menu Desktop -->
                <nav class="hidden lg:flex items-center space-x-1 text-sm font-medium">
                    <a href="#beranda" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">1. Beranda</a>
                    <a href="#profil" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">2. Profil & Pengurus</a>
                    <a href="#program" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">3. Program (10 Poin)</a>
                    <a href="#donasi" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">4. Donasi & Relawan</a>
                    <a href="#laporan" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">5. Laporan</a>
                    <a href="#galeri" class="px-3 py-2 rounded-lg hover:bg-emerald-800 transition">6. Galeri Bukti</a>
                    <a href="#kontak" class="px-3 py-2 rounded-lg bg-amber-500 text-stone-950 font-bold hover:bg-amber-400 transition ml-2">7. Kontak</a>
                </nav>

                <!-- Tombol Menu Mobile -->
                <button id="mobile-menu-btn" class="lg:hidden p-2 rounded-lg text-emerald-200 hover:bg-emerald-800 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>

        <!-- Dropdown Menu Mobile -->
        <div id="mobile-menu" class="hidden lg:hidden bg-emerald-900 px-4 pt-2 pb-4 space-y-1 text-sm border-t border-emerald-800">
            <a href="#beranda" class="block px-3 py-2 rounded-md hover:bg-emerald-800">1. Beranda</a>
            <a href="#profil" class="block px-3 py-2 rounded-md hover:bg-emerald-800">2. Profil & Pengurus</a>
            <a href="#program" class="block px-3 py-2 rounded-md hover:bg-emerald-800">3. Program (10 Poin)</a>
            <a href="#donasi" class="block px-3 py-2 rounded-md hover:bg-emerald-800">4. Donasi & Relawan</a>
            <a href="#laporan" class="block px-3 py-2 rounded-md hover:bg-emerald-800">5. Laporan & Transparansi</a>
            <a href="#galeri" class="block px-3 py-2 rounded-md hover:bg-emerald-800">6. Galeri Bukti</a>
            <a href="#kontak" class="block px-3 py-2 rounded-md bg-amber-500 text-stone-950 font-bold mt-2">7. Kontak</a>
        </div>
    </header>

    <!-- BAGIAN 1: BERANDA -->
    <section id="beranda" class="bg-gradient-to-br from-emerald-900 via-emerald-800 to-teal-900 text-white py-16 sm:py-24">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-10 items-center">
                <div>
                    <span class="inline-block bg-emerald-700/80 border border-emerald-500 text-emerald-100 text-xs font-semibold px-3 py-1 rounded-full mb-4">
                        Lembaga Filantropi Berbasis Kerja Nyata
                    </span>
                    <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight mb-5">
                        Merawat Fasilitas Umat dengan <span class="text-amber-400">Dana & Tenaga Nyata.</span>
                    </h1>
                    <p class="text-emerald-100 text-base sm:text-lg leading-relaxed mb-8">
                        Griya Karya Amil (GKA) menghimpun zakat, infaq, sedekah, wakaf material, serta menggerakkan relawan keahlian untuk membenahi musholla dhuafa dan rumah warga prasejahtera secara transparan.
                    </p>
                    <div class="flex flex-wrap gap-3">
                        <a href="#donasi" class="bg-amber-400 text-stone-950 font-bold px-6 py-3 rounded-xl hover:bg-amber-300 transition shadow-lg">
                            Ikut Donasi / Jadi Relawan
                        </a>
                        <a href="#program" class="bg-emerald-950/60 border border-emerald-400 text-white font-semibold px-6 py-3 rounded-xl hover:bg-emerald-900 transition">
                            Lihat 10 Poin Program
                        </a>
                    </div>
                </div>

                <!-- Kartu Visi Misi & Ringkasan Dampak -->
                <div class="bg-white/10 backdrop-blur-md border border-white/20 rounded-2xl p-6 sm:p-8 space-y-6">
                    <div>
                        <h2 class="text-amber-400 font-bold text-sm uppercase tracking-wider mb-1">Visi Lembaga</h2>
                        <p class="text-sm sm:text-base text-white leading-relaxed">
                            Menjadi pelopor pengelolaan filantropi Islam yang memadukan akuntabilitas dana umat dengan gerakan kerelawanan kerja nyata yang berdampak langsung bagi infrastruktur sosial dhuafa.
                        </p>
                    </div>
                    <div>
                        <h2 class="text-amber-400 font-bold text-sm uppercase tracking-wider mb-2">Misi Utama</h2>
                        <ul class="text-sm text-emerald-100 space-y-2 list-disc list-inside">
                            <li>Menghimpun dana ZISWAF dan jam kerja relawan secara terukur dan terpisah per akad.</li>
                            <li>Melaksanakan renovasi ringan, sanitasi tempat ibadah, dan perbaikan hunian mustahik.</li>
                            <li>Menyajikan laporan keuangan dan dampak kerja bakti yang seimbang dan terbuka.</li>
                        </ul>
                    </div>
                    <div class="grid grid-cols-3 gap-3 pt-4 border-t border-white/20 text-center">
                        <div>
                            <p class="text-xl sm:text-2xl font-extrabold text-amber-400">Rp15 Jt</p>
                            <p class="text-xs text-emerald-200">Dana Terhimpun</p>
                        </div>
                        <div>
                            <p class="text-xl sm:text-2xl font-extrabold text-amber-400">40 Orang</p>
                            <p class="text-xs text-emerald-200">Relawan Aktif</p>
                        </div>
                        <div>
                            <p class="text-xl sm:text-2xl font-extrabold text-amber-400">320 Jam</p>
                            <p class="text-xs text-emerald-200">Kerja Nyata</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BAGIAN 2: PROFIL & PENGURUS (W3: FOTO ASLI PENDIRI, NAMA, NIM) -->
    <section id="profil" class="py-16 sm:py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-3xl mx-auto mb-12">
            <span class="text-emerald-700 font-bold text-xs uppercase tracking-wider">Tentang Lembaga & Struktur</span>
            <h2 class="text-2xl sm:text-4xl font-extrabold text-stone-900 mt-1 mb-4">Profil & Pengurus Griya Karya Amil</h2>
            <p class="text-stone-600 text-sm sm:text-base">
                Griya Karya Amil lahir dari kepedulian mahasiswa Ekonomi Syariah untuk menjembatani donatur material dengan relawan lapangan dalam program renovasi dan sanitasi sarana publik dhuafa.
            </p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- W3: PENDIRI / KETUA DENGAN FOTO ASLI, NAMA, NIM -->
            <div class="bg-white rounded-2xl shadow-md border-2 border-emerald-600 overflow-hidden flex flex-col">
                <div class="aspect-[4/3] bg-stone-200 overflow-hidden">
                    <img src="foto-fariha.jpg.jpeg" alt="Fariha Fauziah" class="w-full h-full object-cover object-top">
                </div>
                <div class="p-5 flex-1 flex flex-col justify-between">
                    <div>
                        <span class="inline-block bg-emerald-100 text-emerald-800 text-xs font-bold px-2.5 py-0.5 rounded-full mb-2">
                            Pendiri & Ketua Lembaga
                        </span>
                        <h3 class="font-extrabold text-lg text-stone-900">Fariha Fauziah</h3>
                        <p class="text-sm font-mono font-semibold text-emerald-700 mt-0.5">NIM: 24108010109</p>
                    </div>
                    <p class="text-xs text-stone-500 mt-3 pt-3 border-t border-stone-100">
                        Bertanggung jawab atas tata kelola program, verifikasi mustahik, dan akuntabilitas lembaga.
                    </p>
                </div>
            </div>

            <!-- Relawan / Pengurus Pendukung 1 -->
            <div class="bg-white rounded-2xl shadow-sm border border-stone-200 p-5 flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-emerald-100 text-emerald-800 flex items-center justify-center font-bold text-lg mb-4">MA</div>
                    <span class="inline-block bg-stone-100 text-stone-700 text-xs font-semibold px-2.5 py-0.5 rounded-full mb-2">
                        Koordinator Relawan Lapangan
                    </span>
                    <h3 class="font-bold text-lg text-stone-900">Marvin Alviansyah</h3>
                    <p class="text-xs text-stone-500 mt-1">Relawan Mahasiswa Ekonomi Syariah</p>
                </div>
                <p class="text-xs text-stone-500 mt-4 pt-3 border-t border-stone-100">
                    Mengatur pembagian regu kerja bakti, logistik perkakas, dan pencatatan jam kerja relawan.
                </p>
            </div>

            <!-- Relawan / Pengurus Pendukung 2 -->
            <div class="bg-white rounded-2xl shadow-sm border border-stone-200 p-5 flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-800 flex items-center justify-center font-bold text-lg mb-4">AA</div>
                    <span class="inline-block bg-stone-100 text-stone-700 text-xs font-semibold px-2.5 py-0.5 rounded-full mb-2">
                        Bendahara & Pencatatan Akad
                    </span>
                    <h3 class="font-bold text-lg text-stone-900">Alisya Aura I.</h3>
                    <p class="text-xs text-stone-500 mt-1">Relawan Mahasiswa Ekonomi Syariah</p>
                </div>
                <p class="text-xs text-stone-500 mt-4 pt-3 border-t border-stone-100">
                    Mengelola pemisahan kas Zakat, Infaq/Sedekah, Wakaf, serta audit kuitansi belanja material.
                </p>
            </div>

            <!-- Relawan / Pengurus Pendukung 3 -->
            <div class="bg-white rounded-2xl shadow-sm border border-stone-200 p-5 flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-teal-100 text-teal-800 flex items-center justify-center font-bold text-lg mb-4">TF</div>
                    <span class="inline-block bg-stone-100 text-stone-700 text-xs font-semibold px-2.5 py-0.5 rounded-full mb-2">
                        Pengawas Syariah Internal
                    </span>
                    <h3 class="font-bold text-lg text-stone-900">Taufiq Ferdiansyah</h3>
                    <p class="text-xs text-stone-500 mt-1">Relawan Mahasiswa Ekonomi Syariah</p>
                </div>
                <p class="text-xs text-stone-500 mt-4 pt-3 border-t border-stone-100">
                    Memastikan penyaluran tepat sasaran sesuai asnaf dan menjaga batas hak amil di bawah 12,5%.
                </p>
            </div>
        </div>
    </section>

    <!-- BAGIAN 3: PROGRAM LENGKAP DENGAN 10 POIN PROSES (W4) -->
    <section id="program" class="bg-stone-100 py-16 sm:py-20 border-y border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mb-12">
                <span class="text-emerald-700 font-bold text-xs uppercase tracking-wider">Alur Tata Kelola Program</span>
                <h2 class="text-2xl sm:text-4xl font-extrabold text-stone-900 mt-1 mb-3">
                    10 Poin Proses: Aksi Bedah Sarana & Sanitasi Musholla Dhuafa (ABSSM)
                </h2>
                <p class="text-stone-600 text-sm sm:text-base">
                    Program unggulan kolaborasi donasi material dan kerja nyata relawan untuk memperbaiki tempat wudhu, instalasi air bersih, dan pengecatan Musholla Al-Ikhlas (Dusun Karangjati, DIY - Simulasi).
                </p>
            </div>

            <div class="grid md:grid-cols-2 gap-5">
                <!-- Poin 1 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">1</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Penghimpunan</span>
                            <h3 class="font-bold text-stone-900">Penghimpunan (Fundraising & Rekrutmen Relawan)</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Menetapkan target terukur sebesar <strong>Rp15.000.000</strong> untuk belanja bahan bangunan dan <strong>40 relawan kerja nyata</strong> (target 320 jam kerja). Kampanye dilakukan melalui poster digital kampus, formulir pendaftaran relawan, dan kanal transfer khusus simulasi.
                    </p>
                </div>

                <!-- Poin 2 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">2</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Penghimpunan</span>
                            <h3 class="font-bold text-stone-900">Penerimaan & Pencatatan</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Setiap donasi uang dicatat dengan nomor transaksi unik (contoh: <code>GKA-2026-001</code>), bukti setor, dan rekap donatur. Kontribusi tenaga dicatat melalui lembar daftar hadir relawan bertanda tangan berisi jam datang, jam pulang, dan jenis pekerjaan.
                    </p>
                </div>

                <!-- Poin 3 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">3</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Pengelolaan</span>
                            <h3 class="font-bold text-stone-900">Pemisahan per Akad & Jenis Filantropi</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Dana dipisah dalam buku pembantu berbeda: <strong>Zakat Maal</strong> (khusus mustahik fakir/miskin), <strong>Infaq/Sedekah</strong> (untuk konsumsi relawan & alat kerja), serta <strong>Wakaf Material</strong> (semen, keramik, cat). Filantropi tenaga dicatat terpisah dalam satuan jam kerja.
                    </p>
                </div>

                <!-- Poin 4 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">4</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Pengelolaan</span>
                            <h3 class="font-bold text-stone-900">Pengelolaan & Hak Amil</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Alokasi dana dirancang transparan: <strong>80% (Rp12.000.000)</strong> langsung untuk material renovasi & santunan dhuafa, <strong>10% (Rp1.500.000)</strong> untuk Hak Amil & operasional lapangan (di bawah batas syariah 1/8 atau 12,5%), dan <strong>10% (Rp1.500.000)</strong> sebagai dana cadangan perawatan.
                    </p>
                </div>

                <!-- Poin 5 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">5</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Penyaluran</span>
                            <h3 class="font-bold text-stone-900">Identifikasi & Verifikasi Penerima</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Sasaran mencakup jamaah prasejahtera (asnaf fakir/miskin) dan fasilitas ibadah publik (asnaf fi sabilillah). Verifikasi dilakukan melalui survei fisik kerusakan bangunan, wawancara takmir, dan surat pengantar ketua RT setempat.
                    </p>
                </div>

                <!-- Poin 6 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">6</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Penyaluran</span>
                            <h3 class="font-bold text-stone-900">Perencanaan Program Penyaluran</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Bentuk program berupa renovasi fisik tempat wudhu dan pembersihan lingkungan musholla. Dilaksanakan pada hari Ahad (2 pekan berturut-turut, pukul 07.30–15.30 WIB) di Dusun Karangjati dengan PIC Lapangan Marvin Alviansyah.
                    </p>
                </div>

                <!-- Poin 7 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">7</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Penyaluran</span>
                            <h3 class="font-bold text-stone-900">Pendistribusian / Pendayagunaan</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Relawan dibagi menjadi 3 regu: Regu Sanitasi & Keramik Wudhu, Regu Pengecatan Dinding, dan Regu Kebersihan & Logistik. Seluruh proses didokumentasikan dengan foto berpenanda waktu serta berita acara serah terima kepada takmir.
                    </p>
                </div>

                <!-- Poin 8 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">8</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Akuntabilitas</span>
                            <h3 class="font-bold text-stone-900">Pelaporan kepada Donatur</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Menyajikan tabel neraca seimbang antara dana masuk, dana tersalur, hak amil/biaya operasional, dan sisa dana di halaman Laporan, disertai kabar perkembangan kondisi musholla pasca-renovasi kepada seluruh donatur dan relawan.
                    </p>
                </div>

                <!-- Poin 9 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">9</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Akuntabilitas</span>
                            <h3 class="font-bold text-stone-900">Pengawasan & Audit</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Pemeriksaan dilakukan berlapis oleh Bendahara (Alisya Aura I.) untuk kecocokan nota belanja material dan Pengawas Syariah Internal (Taufiq Ferdiansyah) untuk memastikan kepatuhan akad serta keabsahan surat keterangan mitra takmir.
                    </p>
                </div>

                <!-- Poin 10 -->
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <div class="flex items-center gap-3 mb-3">
                        <span class="w-8 h-8 rounded-full bg-emerald-700 text-white font-bold text-sm flex items-center justify-center shrink-0">10</span>
                        <div>
                            <span class="text-[11px] font-bold uppercase text-amber-600 block">Evaluasi</span>
                            <h3 class="font-bold text-stone-900">Evaluasi Dampak & Tindak Lanjut</h3>
                        </div>
                    </div>
                    <p class="text-sm text-stone-600 leading-relaxed">
                        Mengukur indikator sebelum vs sesudah (kelayakan kran air, kebersihan area wudhu, dan kenyamanan jamaah), mencatat kendala cuaca/keterlambatan material, serta menjadwalkan pemeriksaan berkala 3 bulan pasca-kegiatan.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- BAGIAN 4: DONASI / KAMPANYE & KALKULATOR SIMULASI (W6: REKENING FIKTIF) -->
    <section id="donasi" class="py-16 sm:py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-2 gap-10 items-start">
            <!-- Progres Kampanye & Kanal Pembayaran Fiktif -->
            <div class="bg-white p-6 sm:p-8 rounded-2xl border border-stone-200 shadow-sm space-y-6">
                <div>
                    <span class="bg-amber-100 text-amber-800 text-xs font-bold px-3 py-1 rounded-full">Kampanye Aktif (Simulasi)</span>
                    <h2 class="text-2xl font-extrabold text-stone-900 mt-3">Bedah Sanitasi & Tempat Wudhu Musholla Al-Ikhlas</h2>
                    <p class="text-sm text-stone-600 mt-2">
                        Bantu wujudkan tempat wudhu yang bersih, tidak licin, dan layak bagi jamaah lansia melalui donasi material atau pendaftaran relawan kerja bakti.
                    </p>
                </div>

                <!-- Progress Bar Dana & Relawan -->
                <div class="space-y-4 bg-stone-50 p-4 rounded-xl border border-stone-200">
                    <div>
                        <div class="flex justify-between text-sm font-bold mb-1">
                            <span class="text-emerald-800">Dana Terkumpul: Rp15.000.000</span>
                            <span class="text-stone-500">Target: Rp15.000.000 (100%)</span>
                        </div>
                        <div class="w-full bg-stone-200 rounded-full h-3">
                            <div class="bg-emerald-600 h-3 rounded-full" style="width: 100%"></div>
                        </div>
                    </div>
                    <div>
                        <div class="flex justify-between text-sm font-bold mb-1">
                            <span class="text-amber-700">Relawan Terdaftar: 40 Orang</span>
                            <span class="text-stone-500">Target: 40 Relawan (100%)</span>
                        </div>
                        <div class="w-full bg-stone-200 rounded-full h-3">
                            <div class="bg-amber-500 h-3 rounded-full" style="width: 100%"></div>
                        </div>
                    </div>
                </div>

                <!-- Kanal Pembayaran Fiktif (W6) -->
                <div>
                    <h3 class="font-bold text-sm text-stone-900 mb-3">Kanal Donasi (Nomor Fiktif Khusus Simulasi Tugas)</h3>
                    <div class="space-y-2.5 text-sm">
                        <div class="p-3.5 rounded-xl bg-emerald-50 border border-emerald-200 flex justify-between items-center">
                            <div>
                                <p class="font-bold text-emerald-950">Bank Syariah Simulasi (Kode: 000)</p>
                                <p class="font-mono text-emerald-800">0000-1234-5678-90 (a.n. Simulasi Griya Karya Amil)</p>
                            </div>
                            <span class="text-xs bg-emerald-200 text-emerald-900 font-bold px-2 py-1 rounded">Fiktif</span>
                        </div>
                        <div class="p-3.5 rounded-xl bg-stone-50 border border-stone-200 flex justify-between items-center">
                            <div>
                                <p class="font-bold text-stone-900">E-Wallet Simulasi (Dompet Karya)</p>
                                <p class="font-mono text-stone-700">0800-0000-0000 (a.n. Simulasi GKA)</p>
                            </div>
                            <span class="text-xs bg-stone-200 text-stone-700 font-bold px-2 py-1 rounded">Fiktif</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Kalkulator Zakat Maal & Simulasi Kontribusi -->
            <div class="bg-emerald-950 text-white p-6 sm:p-8 rounded-2xl shadow-lg space-y-5">
                <div>
                    <h3 class="text-xl font-extrabold text-amber-400">Kalkulator Zakat Maal & Simulasi Donasi</h3>
                    <p class="text-xs text-emerald-200 mt-1">Hitung kewajiban zakat penghasilan/harta (2,5%) atau simulasikan dukunganmu.</p>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-emerald-200 mb-1">Pilih Akad Kontribusi</label>
                    <select id="akad-select" class="w-full rounded-xl bg-emerald-900 border border-emerald-700 px-4 py-2.5 text-sm text-white focus:outline-none">
                        <option value="zakat">Zakat Maal (2,5% dari Harta/Penghasilan)</option>
                        <option value="infaq">Infaq / Sedekah Operasional Relawan</option>
                        <option value="wakaf">Wakaf Material Bangunan</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-emerald-200 mb-1">Masukkan Nominal Harta / Donasi (Rp)</label>
                    <input type="number" id="nominal-input" placeholder="Contoh: 4000000" class="w-full rounded-xl bg-emerald-900 border border-emerald-700 px-4 py-2.5 text-sm text-white placeholder-emerald-500 focus:outline-none">
                </div>

                <button onclick="hitungSimulasi()" class="w-full bg-amber-400 text-stone-950 font-bold py-3 rounded-xl hover:bg-amber-300 transition text-sm">
                    Hitung Nominal Simulasi
                </button>

                <div id="hasil-kalkulator" class="hidden p-4 rounded-xl bg-emerald-900/90 border border-emerald-700 text-sm">
                    <p class="text-emerald-200 text-xs">Estimasi Nilai Kontribusi:</p>
                    <p id="nilai-output" class="text-2xl font-extrabold text-amber-400 mt-1">Rp0</p>
                    <p id="keterangan-output" class="text-xs text-emerald-100 mt-1"></p>
                </div>
            </div>
        </div>
    </section>

    <!-- BAGIAN 5: LAPORAN & TRANSPARANSI (W5: NERACA SEIMBANG & HAK AMIL <= 12,5%) -->
    <section id="laporan" class="bg-stone-100 py-16 sm:py-20 border-y border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-12">
            <div>
                <span class="text-emerald-700 font-bold text-xs uppercase tracking-wider">Akuntabilitas Keuangan & Kinerja</span>
                <h2 class="text-2xl sm:text-4xl font-extrabold text-stone-900 mt-1 mb-2">Laporan & Transparansi (Simulasi)</h2>
                <p class="text-stone-600 text-sm sm:text-base">
                    Disusun sesuai prinsip keseimbangan kas: <strong>Dana Masuk = Dana Tersalur + Hak Amil/Biaya + Sisa Dana</strong>.
                </p>
            </div>

            <!-- Ringkasan Neraca Seimbang (W5) -->
            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="bg-white p-5 rounded-2xl border-l-4 border-emerald-600 shadow-sm">
                    <p class="text-xs font-semibold text-stone-500">Total Dana Masuk (A)</p>
                    <p class="text-2xl font-extrabold text-stone-900 mt-1">Rp15.000.000</p>
                    <p class="text-xs text-emerald-700 mt-1">100% Terverifikasi</p>
                </div>
                <div class="bg-white p-5 rounded-2xl border-l-4 border-teal-600 shadow-sm">
                    <p class="text-xs font-semibold text-stone-500">Dana Tersalur Program (B)</p>
                    <p class="text-2xl font-extrabold text-stone-900 mt-1">Rp12.000.000</p>
                    <p class="text-xs text-stone-500 mt-1">80% (Material & Santunan)</p>
                </div>
                <div class="bg-white p-5 rounded-2xl border-l-4 border-amber-500 shadow-sm">
                    <p class="text-xs font-semibold text-stone-500">Hak Amil & Operasional (C)</p>
                    <p class="text-2xl font-extrabold text-stone-900 mt-1">Rp1.500.000</p>
                    <p class="text-xs text-amber-700 mt-1">10% (Aman, ≤ batas 12,5%)</p>
                </div>
                <div class="bg-white p-5 rounded-2xl border-l-4 border-stone-600 shadow-sm">
                    <p class="text-xs font-semibold text-stone-500">Sisa Saldo Kas (D)</p>
                    <p class="text-2xl font-extrabold text-stone-900 mt-1">Rp1.500.000</p>
                    <p class="text-xs text-stone-500 mt-1">10% (Cadangan Perawatan)</p>
                </div>
            </div>

            <!-- Tabel Pemisahan per Akad & Jenis Filantropi (Poin 3 & 4) -->
            <div class="bg-white rounded-2xl border border-stone-200 shadow-sm overflow-hidden">
                <div class="p-5 border-b border-stone-200">
                    <h3 class="font-bold text-lg text-stone-900">1. Laporan Pemisahan Dana per Akad & Filantropi Tenaga</h3>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-sm text-left">
                        <thead class="bg-stone-50 text-stone-700 font-bold border-b border-stone-200">
                            <tr>
                                <th class="px-4 py-3">Jenis Akad / Filantropi</th>
                                <th class="px-4 py-3">Masuk</th>
                                <th class="px-4 py-3">Tersalur</th>
                                <th class="px-4 py-3">Hak Amil / Biaya</th>
                                <th class="px-4 py-3">Sisa Saldo</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-stone-200">
                            <tr>
                                <td class="px-4 py-3 font-semibold">Zakat Maal (Mustahik Fakir/Miskin)</td>
                                <td class="px-4 py-3">Rp5.000.000</td>
                                <td class="px-4 py-3">Rp4.500.000</td>
                                <td class="px-4 py-3">Rp500.000 (10%)</td>
                                <td class="px-4 py-3">Rp0</td>
                            </tr>
                            <tr>
                                <td class="px-4 py-3 font-semibold">Infaq / Sedekah (Logistik & Alat)</td>
                                <td class="px-4 py-3">Rp4.000.000</td>
                                <td class="px-4 py-3">Rp2.500.000</td>
                                <td class="px-4 py-3">Rp1.000.000 (Biaya Ops)</td>
                                <td class="px-4 py-3">Rp500.000</td>
                            </tr>
                            <tr>
                                <td class="px-4 py-3 font-semibold">Wakaf Material (Semen, Cat, Keramik)</td>
                                <td class="px-4 py-3">Rp6.000.000</td>
                                <td class="px-4 py-3">Rp5.000.000</td>
                                <td class="px-4 py-3">Rp0</td>
                                <td class="px-4 py-3">Rp1.000.000</td>
                            </tr>
                            <tr class="bg-emerald-50/70 font-bold">
                                <td class="px-4 py-3">TOTAL KEUANGAN (SEIMBANG)</td>
                                <td class="px-4 py-3">Rp15.000.000</td>
                                <td class="px-4 py-3">Rp12.000.000</td>
                                <td class="px-4 py-3">Rp1.500.000</td>
                                <td class="px-4 py-3">Rp1.500.000</td>
                            </tr>
                            <tr class="bg-amber-50/70">
                                <td class="px-4 py-3 font-semibold">Filantropi Tenaga (Non-Tunai)</td>
                                <td class="px-4 py-3">40 Relawan (320 Jam)</td>
                                <td class="px-4 py-3">320 Jam Kerja Bakti</td>
                                <td class="px-4 py-3">Tercatat Terpisah</td>
                                <td class="px-4 py-3">0 Jam</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Tabel Rekap Penerimaan Donatur (Poin 2) -->
            <div class="bg-white rounded-2xl border border-stone-200 shadow-sm overflow-hidden">
                <div class="p-5 border-b border-stone-200">
                    <h3 class="font-bold text-lg text-stone-900">2. Sampel Rekap Penerimaan & Pencatatan Transaksi (Simulasi)</h3>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-sm text-left">
                        <thead class="bg-stone-50 text-stone-700 font-bold border-b border-stone-200">
                            <tr>
                                <th class="px-4 py-3">No. Transaksi</th>
                                <th class="px-4 py-3">Nama Donatur</th>
                                <th class="px-4 py-3">Akad</th>
                                <th class="px-4 py-3">Nominal / Kontribusi</th>
                                <th class="px-4 py-3">Status Bukti</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-stone-200">
                            <tr>
                                <td class="px-4 py-3 font-mono text-xs">GKA-2026-001</td>
                                <td class="px-4 py-3">Hamba Allah 01 (Disamarkan)</td>
                                <td class="px-4 py-3">Zakat Maal</td>
                                <td class="px-4 py-3 font-semibold">Rp2.500.000</td>
                                <td class="px-4 py-3 text-emerald-700 font-medium">Kuitansi Terbit</td>
                            </tr>
                            <tr>
                                <td class="px-4 py-3 font-mono text-xs">GKA-2026-002</td>
                                <td class="px-4 py-3">Keluarga Bpk. H*** (Disamarkan)</td>
                                <td class="px-4 py-3">Wakaf Material</td>
                                <td class="px-4 py-3 font-semibold">Rp3.000.000</td>
                                <td class="px-4 py-3 text-emerald-700 font-medium">Kuitansi Terbit</td>
                            </tr>
                            <tr>
                                <td class="px-4 py-3 font-mono text-xs">GKA-2026-003</td>
                                <td class="px-4 py-3">Komunitas Mahasiswa ES</td>
                                <td class="px-4 py-3">Infaq & Tenaga</td>
                                <td class="px-4 py-3 font-semibold">Rp1.500.000 + 15 Relawan</td>
                                <td class="px-4 py-3 text-emerald-700 font-medium">Daftar Hadir Sah</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Evaluasi Dampak Sebelum vs Sesudah & Hasil Audit (Poin 9 & 10) -->
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <h3 class="font-bold text-lg text-stone-900 mb-3">3. Evaluasi Dampak (Sebelum vs Sesudah)</h3>
                    <div class="space-y-3 text-sm">
                        <div class="p-3 bg-stone-50 rounded-xl">
                            <p class="font-bold text-stone-800">Area Tempat Wudhu</p>
                            <p class="text-xs text-stone-600 mt-1"><strong>Sebelum:</strong> Keramik pecah, licin, dan 3 dari 6 kran air bocor.<br><strong>Sesudah:</strong> Keramik anti-slip terpasang penuh, 6 kran baru berfungsi lancar.</p>
                        </div>
                        <div class="p-3 bg-stone-50 rounded-xl">
                            <p class="font-bold text-stone-800">Kendala & Rencana Tindak Lanjut</p>
                            <p class="text-xs text-stone-600 mt-1"><strong>Kendala:</strong> Hujan deras pada pekan pertama memperlambat pengecatan luar.<br><strong>Tindak Lanjut:</strong> Pengecekan saluran air berkala bersama takmir setiap 3 bulan.</p>
                        </div>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm">
                    <h3 class="font-bold text-lg text-stone-900 mb-3">4. Ringkasan Pengawasan & Audit Internal</h3>
                    <ul class="text-sm text-stone-600 space-y-2.5 list-disc list-inside">
                        <li><strong>Audit Keuangan:</strong> 100% nota pembelian material toko bangunan cocok dengan kas keluar sebesar Rp12.000.000.</li>
                        <li><strong>Kepatuhan Syariah:</strong> Hak amil zakat ditetapkan 10% (Rp500.000 dari Rp5.000.000 zakat), mematuhi batas maksimal 1/8 (12,5%).</li>
                        <li><strong>Verifikasi Fisik:</strong> Surat keterangan penyelesaian kerja bakti telah ditandatangani dan distempel oleh Ketua Takmir Musholla Al-Ikhlas (Simulasi).</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- BAGIAN 6: GALERI BUKTI & PROFIL PENERIMA MANFAAT (POIN 5 & 7, TANPA DATA SENSITIF) -->
    <section id="galeri" class="py-16 sm:py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="mb-12">
            <span class="text-emerald-700 font-bold text-xs uppercase tracking-wider">Dokumentasi & Verifikasi Lapangan</span>
            <h2 class="text-2xl sm:text-4xl font-extrabold text-stone-900 mt-1 mb-2">Galeri Bukti & Profil Penerima (Simulasi)</h2>
            <p class="text-stone-600 text-sm sm:text-base">
                Sesuai etika privasi, data pribadi sensitif penerima (NIK dan alamat rumah lengkap) tidak dipublikasikan.
            </p>
        </div>

        <div class="grid md:grid-cols-3 gap-6">
            <!-- Kartu 1 -->
            <div class="bg-white rounded-2xl border border-stone-200 overflow-hidden shadow-sm">
                <div class="bg-emerald-900 text-white p-6">
                    <span class="text-xs bg-amber-400 text-stone-950 font-bold px-2.5 py-0.5 rounded">Profil Mitra Penerima</span>
                    <h3 class="font-bold text-lg mt-3">Musholla Al-Ikhlas (Asnaf Fi Sabilillah)</h3>
                    <p class="text-xs text-emerald-200 mt-1">Wilayah Dusun Karangjati, DIY (Simulasi)</p>
                </div>
                <div class="p-5 text-sm text-stone-600 space-y-2">
                    <p><strong>Perwakilan Mitra:</strong> Bpk. S*** (Ketua Takmir)</p>
                    <p><strong>Status Verifikasi:</strong> Terverifikasi melalui survei kerusakan sanitasi & surat pengantar RT.</p>
                    <p class="text-xs text-emerald-700 font-semibold pt-2">✓ Izin dokumentasi tertulis telah ditandatangani mitra.</p>
                </div>
            </div>

            <!-- Kartu 2 -->
            <div class="bg-white rounded-2xl border border-stone-200 overflow-hidden shadow-sm">
                <div class="bg-teal-900 text-white p-6">
                    <span class="text-xs bg-emerald-400 text-stone-950 font-bold px-2.5 py-0.5 rounded">Bukti Filantropi Tenaga</span>
                    <h3 class="font-bold text-lg mt-3">Kerja Bakti Pemasangan Keramik Wudhu</h3>
                    <p class="text-xs text-teal-200 mt-1">Pelaksanaan: Ahad, 15 November 2026 (Simulasi)</p>
                </div>
                <div class="p-5 text-sm text-stone-600 space-y-2">
                    <p><strong>Keterlibatan:</strong> 40 Relawan Mahasiswa (Total 320 Jam Kerja).</p>
                    <p><strong>Kelengkapan Bukti:</strong> Daftar hadir relawan bertanda tangan, foto lapangan bersama ketua lembaga, dan surat keterangan takmir.</p>
                </div>
            </div>

            <!-- Kartu 3 -->
            <div class="bg-white rounded-2xl border border-stone-200 overflow-hidden shadow-sm">
                <div class="bg-stone-800 text-white p-6">
                    <span class="text-xs bg-amber-400 text-stone-950 font-bold px-2.5 py-0.5 rounded">Bukti Serah Terima</span>
                    <h3 class="font-bold text-lg mt-3">Serah Terima Fasilitas & Paket Sembako Lansia</h3>
                    <p class="text-xs text-stone-300 mt-1">Pelaksanaan: Ahad, 22 November 2026 (Simulasi)</p>
                </div>
                <div class="p-5 text-sm text-stone-600 space-y-2">
                    <p><strong>Penerima:</strong> 15 Keluarga Lansia Dhuafa (Asnaf Fakir/Miskin) di sekitar musholla.</p>
                    <p><strong>Kelengkapan Bukti:</strong> Kuitansi serah terima bertanda tangan dan laporan sisa saldo Rp1.500.000.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- BAGIAN 7: KONTAK & FOOTER PERNYATAAN AI (W7) -->
    <footer id="kontak" class="bg-emerald-950 text-emerald-100 pt-16 pb-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 gap-10 pb-12 border-b border-emerald-800">
                <div>
                    <h2 class="text-2xl font-extrabold text-white mb-3">Hubungi Sekretariat Griya Karya Amil</h2>
                    <p class="text-sm text-emerald-200 mb-6">
                        Ingin mengusulkan musholla atau rumah dhuafa yang membutuhkan renovasi kerja bakti, atau mendaftar sebagai relawan? Hubungi kami melalui kanal simulasi berikut:
                    </p>
                    <ul class="space-y-2.5 text-sm">
                        <li><strong>Sekretariat:</strong> Jl. Marsda Adisucipto (Area Kampus FEBI), Yogyakarta (Simulasi)</li>
                        <li><strong>WhatsApp Relawan:</strong> +62 800-0000-1234 (Nomor Fiktif Simulasi)</li>
                        <li><strong>Email Resmi:</strong> halo@griyakaryaamil-simulasi.org</li>
                    </ul>
                </div>

                <!-- Form Simulasi Daftar Relawan -->
                <form onsubmit="kirimPesanSimulasi(event)" class="bg-emerald-900/70 p-6 rounded-2xl border border-emerald-800 space-y-4">
                    <h3 class="font-bold text-white text-base">Formulir Simulasi Pendaftaran Relawan / Saran</h3>
                    <input type="text" required placeholder="Nama Lengkap" class="w-full rounded-xl bg-emerald-950 border border-emerald-700 px-4 py-2.5 text-sm text-white placeholder-emerald-500">
                    <select class="w-full rounded-xl bg-emerald-950 border border-emerald-700 px-4 py-2.5 text-sm text-white">
                        <option>Daftar Relawan Kerja Nyata (Tenaga)</option>
                        <option>Usulan Lokasi Bedah Sarana Dhuafa</option>
                        <option>Konfirmasi Donasi Material (Simulasi)</option>
                    </select>
                    <button type="submit" class="w-full bg-amber-400 text-stone-950 font-bold py-2.5 rounded-xl hover:bg-amber-300 transition text-sm">
                        Kirim Simulasi
                    </button>
                    <p id="status-form" class="hidden text-xs text-amber-300 font-semibold">
                        ✓ Simulasi berhasil dicatat! Terima kasih atas partisipasi Anda.
                    </p>
                </form>
            </div>

            <!-- W7: PERNYATAAN PENGGUNAAN AI DI FOOTER -->
            <div class="pt-8 text-center space-y-2 text-xs text-emerald-300">
                <p class="font-bold text-white text-sm">
                    SIMULASI – TUGAS KULIAH | Griya Karya Amil (GKA)
                </p>
                <p class="max-w-3xl mx-auto leading-relaxed bg-emerald-900/60 border border-emerald-800 rounded-xl p-3 text-emerald-100">
                    <strong>Pernyataan Penggunaan AI:</strong> Website ini dikembangkan dengan bantuan AI (Gemini untuk penyusunan struktur kode HTML/Tailwind CSS dan draf kerangka teks), sedangkan seluruh konsep program filantropi tenaga, penyesuaian akad syariah, dan verifikasi konten dipertanggungjawabkan sepenuhnya oleh <strong>Fariha Fauziah (NIM: 24108010109)</strong>.
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Toggle Menu HP
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');
        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Kalkulator Simulasi Zakat/Donasi
        function hitungSimulasi() {
            const akad = document.getElementById('akad-select').value;
            const nominal = parseFloat(document.getElementById('nominal-input').value) || 0;
            const hasilBox = document.getElementById('hasil-kalkulator');
            const nilaiOutput = document.getElementById('nilai-output');
            const ketOutput = document.getElementById('keterangan-output');

            hasilBox.classList.remove('hidden');
            if (akad === 'zakat') {
                const zakat = nominal * 0.025;
                nilaiOutput.textContent = 'Rp' + zakat.toLocaleString('id-ID');
                ketOutput.textContent = 'Zakat Maal 2,5% — Dialokasikan khusus untuk mustahik fakir & miskin (Hak Amil maks. 10%).';
            } else if (akad === 'infaq') {
                nilaiOutput.textContent = 'Rp' + nominal.toLocaleString('id-ID');
                ketOutput.textContent = 'Infaq/Sedekah — Dialokasikan untuk logistik relawan & alat kerja bakti.';
            } else {
                nilaiOutput.textContent = 'Rp' + nominal.toLocaleString('id-ID');
                ketOutput.textContent = 'Wakaf Material — Dialokasikan 100% untuk pembelian semen, keramik, dan sarana wudhu.';
            }
        }

        // Notifikasi Form Simulasi
        function kirimPesanSimulasi(e) {
            e.preventDefault();
            document.getElementById('status-form').classList.remove('hidden');
        }
    </script>
</body>
</html>
