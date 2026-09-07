<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aries Triandi Kurniawan, S.H. - Portfolio</title>
    
    <!-- Google Fonts: Inter for clean, modern look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#1d4ed8', // blue-700
                            red: '#dc2626',  // red-600
                            black: '#0f172a' // slate-900 (softer black)
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom base styles for smooth transitions */
        body { font-family: 'Inter', sans-serif; }
        .glass-nav { background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); }
        .hover-card { transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .hover-card:hover { transform: translateY(-5px); box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04); }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-red selection:text-white">

    <nav class="fixed w-full z-50 glass-nav border-b border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center">
                    <a href="#home" class="text-lg sm:text-xl md:text-2xl font-bold text-brand-black tracking-tight whitespace-nowrap">
                        Aries Triandi Kurniawan
                    </a>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-sm font-medium text-slate-600 hover:text-brand-red transition-colors">About</a>
                    <a href="#experience" class="text-sm font-medium text-slate-600 hover:text-brand-blue transition-colors">Experience</a>
                    <a href="#projects" class="text-sm font-medium text-slate-600 hover:text-brand-red transition-colors">Projects</a>
                </div>
                <div class="hidden md:flex">
                    <a href="#contact" class="inline-flex items-center justify-center px-5 py-2.5 border border-transparent text-sm font-medium rounded-full text-white bg-brand-black hover:bg-gray-800 transition-all shadow-md">
                        Let's Talk
                    </a>
                </div>
                <!-- Mobile menu button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-600 hover:text-brand-black focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-gray-200 absolute w-full">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-slate-700 hover:text-brand-red hover:bg-slate-50">About</a>
                <a href="#experience" class="block px-3 py-2 rounded-md text-base font-medium text-slate-700 hover:text-brand-blue hover:bg-slate-50">Experience</a>
                <a href="#projects" class="block px-3 py-2 rounded-md text-base font-medium text-slate-700 hover:text-brand-red hover:bg-slate-50">Projects</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-brand-blue hover:text-brand-red">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Slide 1: Hero Section -->
    <section id="home" class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden flex items-center min-h-screen bg-gradient-to-br from-slate-800 via-slate-900 to-black">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 w-full text-center">
            <h1 class="text-5xl md:text-6xl lg:text-7xl font-extrabold text-white tracking-widest mb-4 uppercase drop-shadow-lg">
                PORTFOLIO
            </h1>
            <h2 class="text-xl md:text-2xl text-gray-300 font-light tracking-wide mb-12 drop-shadow-md">
                Aries Triandi Kurniawan, S.H.
            </h2>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#contact" class="inline-flex items-center justify-center px-8 py-3.5 border border-transparent text-base font-medium rounded-full text-white bg-brand-red hover:bg-red-700 transition-colors shadow-lg">
                    Hubungi Saya
                </a>
                <a href="https://drive.google.com/file/d/1DdCdOT_DYQ4dhCPps3yMVFWi-ii6ZMX9/view?usp=drivesdk" target="_blank" class="inline-flex items-center justify-center px-8 py-3.5 border-2 border-white text-base font-medium rounded-full text-white hover:bg-white hover:text-brand-black transition-colors shadow-lg">
                    <i class="fas fa-download mr-2"></i> Download CV
                </a>
            </div>
            
            <div class="mt-12 flex items-center justify-center space-x-8">
                <a href="https://linkedin.com/in/aries-triandi-kurniawan-5481562aa@ariestk" target="_blank" class="text-gray-300 hover:text-white transition-colors text-3xl hover:scale-110 transform">
                    <span class="sr-only">LinkedIn</span>
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="mailto:ariestk123@gmail.com" class="text-gray-300 hover:text-white transition-colors text-3xl hover:scale-110 transform">
                    <span class="sr-only">Email</span>
                    <i class="fas fa-envelope"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Slide 2: About Me & Skills -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-brand-black tracking-tight sm:text-4xl">Tentang Saya & Keahlian</h2>
                <div class="mt-2 w-24 h-1 bg-brand-red mx-auto rounded-full"></div>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-12">
                <div class="lg:col-span-1 p-8 bg-slate-50 rounded-3xl border border-gray-100 shadow-sm h-max">
                    <h3 class="text-xl font-bold text-brand-black mb-4"><i class="fas fa-graduation-cap text-brand-blue mr-2"></i>Pendidikan</h3>
                    <div class="space-y-6">
                        <div>
                            <p class="font-bold text-slate-800">Universitas Bengkulu</p>
                            <p class="text-sm text-brand-red font-medium">Agt 2022 - Jul 2026</p>
                            <p class="text-sm text-slate-600 mt-1">S1 Hukum | IPK 3.73 (Pujian)</p>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">Universitas Padjadjaran</p>
                            <p class="text-sm text-brand-red font-medium">Feb 2024 - Jul 2024</p>
                            <p class="text-sm text-slate-600 mt-1">S1 Hukum | IPK 3.74<br/>(Pertukaran Mahasiswa Merdeka)</p>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">SMAN 5 Bengkulu Utara</p>
                            <p class="text-sm text-brand-red font-medium">2019 - 2022</p>
                            <p class="text-sm text-slate-600 mt-1">MIPA | Nilai Rata-rata 88.93/100</p>
                        </div>
                    </div>
                </div>
                
                <div class="lg:col-span-2 flex flex-col justify-start">
                    <p class="text-lg text-slate-600 leading-relaxed mb-10 text-justify">
                        Lulusan Sarjana Hukum (S.H.) Predikat Pujian dengan IPK 3,73 Universitas Bengkulu. Memiliki pengalaman langsung sebagai Mitra Statistik di Badan Pusat Statistik (BPS) Bengkulu Utara. Terampil dalam pendataan, verifikasi, dan pemetaan sektor usaha untuk Sensus Ekonomi 2026. Mampu melakukan wawancara terstruktur kepada pelaku usaha, menganalisis akurasi data finansial, serta memastikan validitas data pada sistem digital BPS. Memiliki kemampuan administrasi, komunikasi, dan komitmen untuk aktif pengembangan diri.
                    </p>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-8">
                        <div>
                            <h3 class="text-lg font-bold text-brand-black mb-4 flex items-center border-b border-gray-200 pb-2">
                                <i class="fas fa-laptop-code text-brand-blue mr-2"></i> Technical Skills
                            </h3>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Microsoft Office</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Sistem Digital BPS</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Google Sheets</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Analisis Hukum</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Legal Drafting</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Analisis Kebijakan</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Administrasi Organisasi</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Data Entry & Verifikasi</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Wawancara Terstruktur</span>
                                <span class="px-3 py-1.5 bg-blue-50 border border-blue-200 text-brand-blue text-sm rounded-full font-medium shadow-sm">Pemetaan Usaha</span>
                            </div>
                        </div>

                        <div>
                            <h3 class="text-lg font-bold text-brand-black mb-4 flex items-center border-b border-gray-200 pb-2">
                                <i class="fas fa-users text-brand-red mr-2"></i> Soft Skills
                            </h3>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Komunikasi Indonesia (Aktif)</span>
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Komunikasi Inggris (Pasif)</span>
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Problem Solving</span>
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Kerja Sama Tim</span>
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Ketelitian & Akurasi</span>
                                <span class="px-3 py-1.5 bg-red-50 border border-red-200 text-brand-red text-sm rounded-full font-medium shadow-sm">Manajemen Waktu</span>
                            </div>
                        </div>
                    </div>

                    <div>
                        <h3 class="text-lg font-bold text-brand-black mb-4 flex items-center border-b border-gray-200 pb-2">
                            <i class="fas fa-certificate text-yellow-500 mr-2"></i> Sertifikasi Profesional
                        </h3>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Certified Legal Tax Specialist (CLTS)</span>
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Pendidikan Khusus Profesi Advokat (PKPA)</span>
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Certified Professional Mediator (CPM)</span>
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Certified Business Analysis Professional (CBAP)</span>
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Legal Contracts and Agreements</span>
                            <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 text-slate-700 text-sm rounded-full font-medium shadow-sm">Intro to Computers & AI</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section: Experience -->
    <section id="experience" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-brand-black tracking-tight sm:text-4xl">Pengalaman Profesional</h2>
                <div class="mt-2 w-24 h-1 bg-brand-blue mx-auto rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Exp Card 1 (Mitra Statistik BPS with Photo) -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100 hover-card flex flex-col group">
                    <div class="h-48 w-full overflow-hidden bg-slate-200 relative">
                        <img src="WhatsApp Image 2026-08-31 at 18.52.31.jpeg" alt="Pelatihan Petugas Sensus Ekonomi 2026 BPS" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://placehold.co/600x400/1d4ed8/ffffff?text=Pelatihan+BPS+2026'">
                        <span class="absolute top-3 right-3 text-xs font-bold text-white bg-brand-blue px-3 py-1 rounded-full shadow-md">Jun - Agt 2026</span>
                    </div>
                    <div class="p-6 flex-grow flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-brand-black mb-1">Mitra Statistik</h3>
                            <h4 class="text-sm font-semibold text-slate-500 mb-4">BPS Bengkulu Utara</h4>
                            <ul class="text-sm text-slate-600 space-y-2 list-disc list-inside">
                                <li>Pendataan, verifikasi, dan pemetaan sektor usaha untuk Sensus Ekonomi 2026.</li>
                                <li>Wawancara terstruktur dan analisis data finansial pelaku usaha.</li>
                                <li>Validasi data bisnis ke sistem digital BPS.</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Exp Card 2 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-gray-100 hover-card relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-16 h-16 bg-red-50 rounded-bl-full -mr-8 -mt-8 transition-transform group-hover:scale-150"></div>
                    <span class="text-xs font-bold text-brand-red bg-red-100 px-3 py-1 rounded-full mb-4 inline-block">Jul 2025</span>
                    <h3 class="text-xl font-bold text-brand-black mb-1">Fasilitator Freelance</h3>
                    <h4 class="text-sm font-semibold text-slate-500 mb-4">Yale Communication</h4>
                    <ul class="text-sm text-slate-600 space-y-2 list-disc list-inside">
                        <li>Fasilitator Pelatihan Koding dan AI Tingkat SD-SMA.</li>
                        <li>Bekerjasama dengan Kemendikdasmen di Kabupaten Bengkulu Utara.</li>
                    </ul>
                </div>

                <!-- Exp Card 3 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-gray-100 hover-card relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-16 h-16 bg-blue-50 rounded-bl-full -mr-8 -mt-8 transition-transform group-hover:scale-150"></div>
                    <span class="text-xs font-bold text-brand-blue bg-blue-100 px-3 py-1 rounded-full mb-4 inline-block">Agt 2025</span>
                    <h3 class="text-xl font-bold text-brand-black mb-1">Peserta Magang Internship</h3>
                    <h4 class="text-sm font-semibold text-slate-500 mb-4">Magang Institusional - Jakarta</h4>
                    <ul class="text-sm text-slate-600 space-y-2 list-disc list-inside">
                        <li>Audiensi di 8 instansi pemerintah pusat (Kemendes, Kemenkumham, MK, dll).</li>
                        <li>Mengumpulkan informasi kebijakan dan layanan publik.</li>
                    </ul>
                </div>

                <!-- Exp Card 4 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-gray-100 hover-card relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-16 h-16 bg-red-50 rounded-bl-full -mr-8 -mt-8 transition-transform group-hover:scale-150"></div>
                    <span class="text-xs font-bold text-brand-red bg-red-100 px-3 py-1 rounded-full mb-4 inline-block">Des 2024 - Mei 2026</span>
                    <h3 class="text-xl font-bold text-brand-black mb-1">Sekretaris Umum</h3>
                    <h4 class="text-sm font-semibold text-slate-500 mb-4">HIMABU Bengkulu Utara</h4>
                    <ul class="text-sm text-slate-600 space-y-2 list-disc list-inside">
                        <li>Mengelola administrasi, pengarsipan, dan surat-menyurat organisasi.</li>
                        <li>Mengoordinasikan data/informasi internal.</li>
                    </ul>
                </div>

                <!-- Exp Card 5 -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-gray-100 hover-card relative overflow-hidden group lg:col-span-2">
                    <div class="absolute top-0 right-0 w-16 h-16 bg-blue-50 rounded-bl-full -mr-8 -mt-8 transition-transform group-hover:scale-150"></div>
                    <span class="text-xs font-bold text-brand-blue bg-blue-100 px-3 py-1 rounded-full mb-4 inline-block">Agt 2023 - Jan 2025</span>
                    <h3 class="text-xl font-bold text-brand-black mb-1">Staf Divisi Kajian dan Penelitian Hukum</h3>
                    <h4 class="text-sm font-semibold text-slate-500 mb-4">Paralegal FH Universitas Bengkulu</h4>
                    <ul class="text-sm text-slate-600 space-y-2 list-disc list-inside">
                        <li>Melakukan kajian dan penelitian terhadap isu-isu hukum dengan analisis mendalam.</li>
                        <li>Berkolaborasi menyelenggarakan sosialisasi hukum kepada masyarakat.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Section: Projects -->
    <section id="projects" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-brand-black tracking-tight sm:text-4xl">Project Sosial</h2>
                <div class="mt-2 w-24 h-1 bg-brand-red mx-auto rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Proj Card 1 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden hover-card border border-gray-100 flex flex-col h-full">
                    <div class="h-2 bg-brand-red"></div>
                    <div class="p-6 flex-grow">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-xs font-bold text-white bg-brand-black px-2 py-1 rounded">2026</span>
                        </div>
                        <h3 class="text-lg font-bold text-brand-black mb-2 leading-tight">Kenal Kampus, Kenal Masa Depan</h3>
                        <p class="text-sm font-semibold text-brand-red mb-4">Edukasi Pendidikan</p>
                        <p class="text-sm text-slate-600 line-clamp-4 hover:line-clamp-none transition-all duration-300">
                            Roadshow HIMABU di SMAN 15 Bengkulu Utara untuk memotivasi siswa ke perguruan tinggi melalui sosialisasi jalur masuk dan sharing experience.
                        </p>
                    </div>
                    <div class="p-6 pt-0 mt-auto">
                        <a href="#" class="text-sm font-bold text-brand-blue hover:text-brand-red inline-flex items-center">Lihat Detail <i class="fas fa-arrow-right ml-1"></i></a>
                    </div>
                </div>

                <!-- Proj Card 2 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden hover-card border border-gray-100 flex flex-col h-full">
                    <div class="h-2 bg-brand-blue"></div>
                    <div class="p-6 flex-grow">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-xs font-bold text-white bg-brand-black px-2 py-1 rounded">2025</span>
                        </div>
                        <h3 class="text-lg font-bold text-brand-black mb-2 leading-tight">Pondok Meaningful Literacy Digital</h3>
                        <p class="text-sm font-semibold text-brand-blue mb-4">Proposal Pengabdian Masyarakat</p>
                        <p class="text-sm text-slate-600">
                            Menyusun proposal PKM untuk meningkatkan minat baca dan kreativitas siswa SMPN 17 Bengkulu Utara di Kec. Enggano melalui literasi digital berdasarkan observasi lapangan.
                        </p>
                    </div>
                    <div class="p-6 pt-0 mt-auto">
                        <a href="#" class="text-sm font-bold text-brand-blue hover:text-brand-red inline-flex items-center">Lihat Detail <i class="fas fa-arrow-right ml-1"></i></a>
                    </div>
                </div>

                <!-- Proj Card 3 -->
                <div class="bg-slate-50 rounded-2xl overflow-hidden hover-card border border-gray-100 flex flex-col h-full">
                    <div class="h-2 bg-brand-black"></div>
                    <div class="p-6 flex-grow">
                        <div class="flex justify-between items-center mb-4">
                            <span class="text-xs font-bold text-white bg-brand-black px-2 py-1 rounded">2024</span>
                        </div>
                        <h3 class="text-lg font-bold text-brand-black mb-2 leading-tight">Awareness Pertanian Perkotaan Berbasis Heritage</h3>
                        <p class="text-sm font-semibold text-brand-black mb-4">Project Sosial PMM Bandung</p>
                        <p class="text-sm text-slate-600">
                            Mengelola kegiatan, verifikasi data peserta, serta memberikan pelatihan pembibitan cabai dan pengendalian hama lalat buah di Bandung.
                        </p>
                    </div>
                    <div class="p-6 pt-0 mt-auto">
                        <a href="#" class="text-sm font-bold text-brand-blue hover:text-brand-red inline-flex items-center">Lihat Detail <i class="fas fa-arrow-right ml-1"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section: Contact -->
    <section id="contact" class="py-20 bg-slate-50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold text-brand-black tracking-tight sm:text-4xl mb-4">Mari Berkolaborasi</h2>
            <p class="text-lg text-slate-600 mb-10 max-w-2xl mx-auto">
                Saya terbuka untuk diskusi terkait peluang karier, proyek riset hukum, atau kerja sama profesional lainnya. Silakan hubungi saya melalui platform di bawah ini.
            </p>

            <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
                <!-- Email -->
                <a href="mailto:ariestk123@gmail.com" class="flex items-center w-full sm:w-auto px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border border-gray-100 transition-all group">
                    <div class="w-12 h-12 bg-red-100 text-brand-red rounded-full flex items-center justify-center text-xl group-hover:bg-brand-red group-hover:text-white transition-colors">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <div class="ml-4 text-left">
                        <p class="text-sm text-slate-500 font-medium">Email</p>
                        <p class="text-brand-black font-semibold">ariestk123@gmail.com</p>
                    </div>
                </a>

                <!-- LinkedIn -->
                <a href="https://linkedin.com/in/aries-triandi-kurniawan-5481562aa@ariestk" target="_blank" class="flex items-center w-full sm:w-auto px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border border-gray-100 transition-all group">
                    <div class="w-12 h-12 bg-blue-100 text-brand-blue rounded-full flex items-center justify-center text-xl group-hover:bg-blue-600 group-hover:text-white transition-colors">
                        <i class="fab fa-linkedin-in"></i>
                    </div>
                    <div class="ml-4 text-left">
                        <p class="text-sm text-slate-500 font-medium">LinkedIn</p>
                        <p class="text-brand-black font-semibold">Aries Triandi K.</p>
                    </div>
                </a>

                <!-- WhatsApp / Phone -->
                <a href="https://wa.me/6285783495330" target="_blank" class="flex items-center w-full sm:w-auto px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border border-gray-100 transition-all group">
                    <div class="w-12 h-12 bg-green-100 text-green-600 rounded-full flex items-center justify-center text-xl group-hover:bg-green-600 group-hover:text-white transition-colors">
                        <i class="fab fa-whatsapp"></i>
                    </div>
                    <div class="ml-4 text-left">
                        <p class="text-sm text-slate-500 font-medium">WhatsApp / Phone</p>
                        <p class="text-brand-black font-semibold">+62 857 8349 5330</p>
                    </div>
                </a>
            </div>
            
            <div class="mt-12 text-slate-500 flex items-center justify-center gap-2">
                <i class="fas fa-map-marker-alt text-brand-red"></i> 
                <span>Bengkulu, Indonesia</span>
            </div>
        </div>
    </section>

    <footer class="bg-brand-black text-white py-8 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center">
            <p class="text-gray-400 text-sm">
                &copy; <span id="year"></span> Aries Triandi Kurniawan. All rights reserved.
            </p>
        </div>
    </footer>

    <!-- AI Chatbot Widget -->
    <div id="chatbot-container" class="fixed bottom-6 right-6 z-50">
        <button id="chat-toggle" class="bg-brand-blue hover:bg-blue-800 text-white w-14 h-14 rounded-full shadow-2xl flex items-center justify-center transition-transform hover:scale-110 focus:outline-none">
            <i class="fas fa-robot text-2xl"></i>
        </button>

        <div id="chat-window" class="hidden absolute bottom-16 right-0 w-80 sm:w-96 bg-white rounded-2xl shadow-2xl border border-gray-200 overflow-hidden flex-col transition-all duration-300 transform origin-bottom-right">
            <div class="bg-brand-black text-white p-4 flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <div class="w-8 h-8 bg-brand-red rounded-full flex items-center justify-center">
                        <i class="fas fa-robot text-sm"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-sm">Aries AI Assistant</h3>
                        <p class="text-xs text-gray-300">Tanya seputar profil saya</p>
                    </div>
                </div>
                <button id="close-chat" class="text-gray-400 hover:text-white focus:outline-none">
                    <i class="fas fa-times"></i>
                </button>
            </div>

            <div id="chat-messages" class="p-4 h-80 overflow-y-auto bg-slate-50 flex flex-col space-y-3 text-sm">
                <div class="flex justify-start">
                    <div class="bg-white border border-gray-200 text-slate-700 p-3 rounded-2xl rounded-tl-none max-w-[85%] shadow-sm">
                        Halo! Saya asisten AI virtual Aries. Ada yang ingin ditanyakan tentang pendidikan, pengalaman, atau keahlian Aries?
                    </div>
                </div>
            </div>

            <div class="p-3 bg-white border-t border-gray-200 flex items-center space-x-2">
                <input type="text" id="chat-input" class="flex-1 bg-slate-100 text-slate-800 rounded-full px-4 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-brand-blue/50" placeholder="Ketik pertanyaan di sini...">
                <button id="send-btn" class="bg-brand-red hover:bg-red-700 text-white w-9 h-9 rounded-full flex items-center justify-center transition-colors focus:outline-none">
                    <i class="fas fa-paper-plane text-xs"></i>
                </button>
            </div>
        </div>
    </div>

    <script>
        document.getElementById('year').textContent = new Date().getFullYear();

        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        const chatToggle = document.getElementById('chat-toggle');
        const chatWindow = document.getElementById('chat-window');
        const closeChat = document.getElementById('close-chat');
        const chatMessages = document.getElementById('chat-messages');
        const chatInput = document.getElementById('chat-input');
        const sendBtn = document.getElementById('send-btn');

        let chatHistory = [];
        const systemInstruction = `Kamu adalah Asisten AI virtual untuk Aries Triandi Kurniawan, S.H. Tugasmu adalah menjawab pertanyaan pengunjung website seputar profil, pengalaman, pendidikan, dan proyek Aries dengan ramah, profesional, singkat, dan menggunakan bahasa Indonesia.`;

        chatToggle.addEventListener('click', () => {
            chatWindow.classList.toggle('hidden');
            chatWindow.classList.toggle('flex');
            if(!chatWindow.classList.contains('hidden')) {
                chatInput.focus();
            }
        });

        closeChat.addEventListener('click', () => {
            chatWindow.classList.add('hidden');
            chatWindow.classList.remove('flex');
        });

        function appendMessage(text, sender, isTyping = false) {
            const msgDiv = document.createElement('div');
            msgDiv.className = `flex ${sender === 'user' ? 'justify-end' : 'justify-start'}`;
            
            const bubble = document.createElement('div');
            bubble.className = sender === 'user' 
                ? 'bg-brand-blue text-white p-3 rounded-2xl rounded-tr-none max-w-[85%] shadow-sm'
                : 'bg-white border border-gray-200 text-slate-700 p-3 rounded-2xl rounded-tl-none max-w-[85%] shadow-sm';
            
            if (isTyping) {
                bubble.id = 'typing-indicator';
                bubble.innerHTML = '<div class="flex space-x-1"><div class="w-2 h-2 bg-gray-400 rounded-full animate-bounce"></div><div class="w-2 h-2 bg-gray-400 rounded-full animate-bounce" style="animation-delay: 0.1s"></div><div class="w-2 h-2 bg-gray-400 rounded-full animate-bounce" style="animation-delay: 0.2s"></div></div>';
            } else {
                bubble.textContent = text;
            }

            msgDiv.appendChild(bubble);
            chatMessages.appendChild(msgDiv);
            chatMessages.scrollTop = chatMessages.scrollHeight;
            return msgDiv;
        }

        async function handleSendMessage() {
            const text = chatInput.value.trim();
            if (!text) return;

            appendMessage(text, 'user');
            chatInput.value = '';
            const loadingNode = appendMessage('', 'ai', true);

            try {
                chatHistory.push({ role: 'user', parts: [{ text: text }] });
                const payload = {
                    contents: chatHistory,
                    systemInstruction: { parts: [{ text: systemInstruction }] }
                };

                const apiKey = ""; 
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-3-flash-preview:generateContent?key=${apiKey}`;

                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) throw new Error('API Error');

                const result = await response.json();
                
                if (result.candidates && result.candidates.length > 0) {
                    const aiResponseText = result.candidates[0].content.parts[0].text;
                    chatHistory.push({ role: 'model', parts: [{ text: aiResponseText }] });
                    loadingNode.remove();
                    appendMessage(aiResponseText, 'ai');
                }
            } catch (error) {
                console.error("Error connecting to Gemini AI:", error);
                loadingNode.remove();
                appendMessage("Maaf, layanan AI sedang mengalami gangguan. Silakan coba lagi nanti.", 'ai');
                chatHistory.pop();
            }
        }

        sendBtn.addEventListener('click', handleSendMessage);
        chatInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') handleSendMessage();
        });
    </script>
</body>
</html>
