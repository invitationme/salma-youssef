<!DOCTYPE html>
<html lang="ar" dir="rtl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دعوة حفل عقيقة الأمير الصغير فيصل | 16/11/2026</title>
    
    <!-- استدعاء خطوط عربية فاخرة من Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Aref+Ruqaa:wght@400;700&family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    
    <!-- استدعاء مكتبة Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        skyPastel: '#EBF5FF',
                        skyLight: '#D6EBFF',
                        powderBlue: '#B8DCFF',
                        royalBlue: '#3B82F6',
                        navyDeep: '#1E3A5F',
                        goldChampagne: '#C5A059',
                        goldLight: '#E5C98B',
                        ivorySoft: '#F8FBFF'
                    },
                    fontFamily: {
                        ruqaa: ['"Aref Ruqaa"', 'serif'],
                        amiri: ['"Amiri"', 'serif'],
                        cairo: ['"Cairo"', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <!-- تنسيقات مخصصة للرسوم المتحركة والزخارف الملكية -->
    <style>
        body {
            background: linear-gradient(180deg, #EBF5FF 0%, #F8FBFF 40%, #E1F0FF 80%, #D6EBFF 100%);
            color: #1E3A5F;
            font-family: 'Cairo', sans-serif;
            overflow-x: hidden;
        }

        /* خلفية نقش مغربي وهندسي خفيف جداً */
        .moroccan-pattern {
            background-image: radial-gradient(#C5A059 0.75px, transparent 0.75px), radial-gradient(#93C5FD 0.75px, #F8FBFF 0.75px);
            background-size: 32px 32px;
            background-position: 0 0, 16px 16px;
        }

        /* بطاقات زجاجية فاخرة */
        .glass-card {
            background: rgba(255, 255, 255, 0.78);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 1px solid rgba(197, 160, 89, 0.35);
            box-shadow: 0 15px 35px -5px rgba(30, 58, 95, 0.08), 0 0 15px rgba(184, 220, 255, 0.4);
        }

        /* إطار ذهبي مزدوج */
        .royal-border {
            position: relative;
        }
        .royal-border::after {
            content: '';
            position: absolute;
            inset: 6px;
            border: 1px solid rgba(197, 160, 89, 0.45);
            border-radius: inherit;
            pointer-events: none;
        }

        /* حركات الطفو واللمعان */
        @keyframes floatSlow {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-12px) rotate(2deg); }
        }
        @keyframes floatReverse {
            0%, 100% { transform: translateY(0px) translateX(0px); }
            50% { transform: translateY(-8px) translateX(8px); }
        }
        @keyframes twinkle {
            0%, 100% { opacity: 0.35; transform: scale(0.9); }
            50% { opacity: 1; transform: scale(1.15); }
        }
        @keyframes pulseGold {
            0%, 100% { box-shadow: 0 0 0 0 rgba(197, 160, 89, 0.45); }
            50% { box-shadow: 0 0 0 14px rgba(197, 160, 89, 0); }
        }
        @keyframes shimmer {
            0% { background-position: -200% center; }
            100% { background-position: 200% center; }
        }

        .animate-float { animation: floatSlow 6s ease-in-out infinite; }
        .animate-float-rev { animation: floatReverse 7s ease-in-out infinite; }
        .animate-twinkle { animation: twinkle 3.5s ease-in-out infinite; }
        .animate-pulse-gold { animation: pulseGold 2.5s infinite; }

        .gold-text-shimmer {
            background: linear-gradient(90deg, #9E7B36 0%, #DFC07B 35%, #9E7B36 70%, #DFC07B 100%);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 4s linear infinite;
        }

        /* ظهور تدريجي عند التمرير */
        .reveal-section {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.85s cubic-bezier(0.22, 1, 0.36, 1);
        }
        .reveal-section.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* شاشة الغلاف الملكي */
        #envelope-screen {
            transition: opacity 0.9s ease, transform 0.9s cubic-bezier(0.22, 1, 0.36, 1);
        }
        #envelope-screen.opened {
            opacity: 0;
            transform: scale(1.06);
            pointer-events: none;
        }

        /* جزيئات الاحتفال */
        .sparkle-particle {
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            animation: fallParticle 2.8s ease-out forwards;
        }
        @keyframes fallParticle {
            0% { transform: translateY(0) scale(1) rotate(0deg); opacity: 1; }
            100% { transform: translateY(160px) scale(0.3) rotate(360deg); opacity: 0; }
        }
    </style>
</head>
<body class="antialiased selection:bg-skyLight selection:text-navyDeep">

    <!-- ==================== 1. شاشة الترحيب وفتح الدعوة الملكية ==================== -->
    <div id="envelope-screen" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-gradient-to-br from-[#D6EBFF] via-[#EBF5FF] to-[#CBE4FF]">
        <!-- زخارف خلفية متحركة -->
        <div class="absolute inset-0 overflow-hidden pointer-events-none">
            <!-- سحابة علوية -->
            <svg class="absolute top-8 right-6 w-36 h-20 text-white/70 animate-float" viewBox="0 0 200 100" fill="currentColor">
                <path d="M45,80 L155,80 C175,80 185,65 180,50 C175,35 160,30 148,35 C142,15 120,5 100,12 C82,5 62,15 56,33 C40,28 22,38 20,55 C18,70 30,80 45,80 Z"/>
            </svg>
            <!-- هلال ونجوم -->
            <svg class="absolute top-14 left-10 w-16 h-16 text-goldChampagne/60 animate-float-rev" viewBox="0 0 64 64" fill="currentColor">
                <path d="M36 6C21.6 6 10 17.6 10 32s11.6 26 26 26c4.8 0 9.3-1.3 13.2-3.6-10.3-2.5-18-11.8-18-22.9s7.7-20.4 18-22.9C45.3 7.3 40.8 6 36 6z"/>
            </svg>
            <svg class="absolute bottom-16 right-12 w-8 h-8 text-goldChampagne/70 animate-twinkle" viewBox="0 0 24 24" fill="currentColor">
                <path d="M12 2l2.9 6.2L22 9.2l-5 4.8 1.2 6.8L12 17.5l-6.2 3.3L7 14 2 9.2l7.1-1z"/>
            </svg>
        </div>

        <!-- بطاقة الظرف الملكي -->
        <div class="relative w-full max-w-md glass-card royal-border rounded-3xl p-8 sm:p-10 text-center shadow-2xl">
            <!-- تاج ملكي ذهبي -->
            <div class="mx-auto mb-5 w-20 h-20 rounded-full bg-gradient-to-b from-skyPastel to-skyLight border-2 border-goldChampagne/60 flex items-center justify-center shadow-inner animate-float">
                <svg class="w-11 h-11 text-goldChampagne" viewBox="0 0 64 64" fill="currentColor">
                    <path d="M8 46h48v6H8v-6zm4-4L6 18l16 11 10-17 10 17 16-11-6 24H12zm20-34a3 3 0 100 6 3 3 0 000-6zM6 12a3 3 0 100 6 3 3 0 000-6zm52 0a3 3 0 100 6 3 3 0 000-6z"/>
                </svg>
            </div>

            <p class="font-amiri text-lg text-goldChampagne font-bold tracking-wide mb-1">دعوة خاصة وتشريف</p>
            <h1 class="font-ruqaa text-3xl sm:text-4xl text-navyDeep mb-3 leading-relaxed">
                حفل عقيقة الأمير الصغير
                <span class="block text-4xl sm:text-5xl gold-text-shimmer mt-2">فيصـل</span>
            </h1>

            <div class="flex items-center justify-center gap-3 my-4">
                <span class="h-[1px] w-12 bg-gradient-to-l from-goldChampagne to-transparent"></span>
                <span class="text-goldChampagne text-sm">✦ 16 / 11 / 2026 ✦</span>
                <span class="h-[1px] w-12 bg-gradient-to-r from-goldChampagne to-transparent"></span>
            </div>

            <p class="text-sm sm:text-base text-navyDeep/80 mb-7 leading-relaxed">
                بكل حب وفرح، يسرّنا دعوتكم لمشاركتنا فرحة قدوم مولودنا الغالي
            </p>

            <!-- زر فتح الدعوة -->
            <button id="open-invitation-btn" type="button" class="group relative inline-flex items-center justify-center gap-3 px-8 py-4 rounded-full bg-gradient-to-r from-[#2B588C] via-[#1E3A5F] to-[#2B588C] text-white font-bold text-base sm:text-lg shadow-lg border border-goldChampagne/70 hover:scale-105 active:scale-95 transition-all duration-300 animate-pulse-gold cursor-pointer">
                <span>افتح الدعوة</span>
                <svg class="w-5 h-5 text-goldLight group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 19v-8.93a2 2 0 01.89-1.664l7-4.666a2 2 0 012.22 0l7 4.666A2 2 0 0121 10.07V19M3 19a2 2 0 002 2h14a2 2 0 002-2M3 19l6.75-4.5M21 19l-6.75-4.5M3 10l6.75 4.5M21 10l-6.75 4.5m0 0l-1.14.76a2 2 0 01-2.22 0l-1.14-.76"/>
                </svg>
            </button>
        </div>
    </div>

    <!-- ==================== شريط علوي عائم للموسيقى والتنقل السريع ==================== -->
    <header class="fixed top-3 inset-x-0 z-40 px-4 pointer-events-none">
        <div class="max-w-4xl mx-auto flex items-center justify-between">
            <!-- زر تشغيل/إيقاف المعزوفة الهادئة -->
            <button id="music-toggle-btn" type="button" aria-label="تشغيل أو إيقاف الموسيقى الهادئة" class="pointer-events-auto glass-card px-3.5 py-2 rounded-full flex items-center gap-2 text-xs sm:text-sm font-semibold text-navyDeep hover:bg-white transition shadow-md cursor-pointer">
                <span id="music-icon-wave" class="flex items-end gap-0.5 h-3.5">
                    <span class="w-0.5 h-2 bg-goldChampagne rounded-full transition-all"></span>
                    <span class="w-0.5 h-3.5 bg-goldChampagne rounded-full transition-all"></span>
                    <span class="w-0.5 h-1.5 bg-goldChampagne rounded-full transition-all"></span>
                </span>
                <span id="music-label">نغمة هادئة</span>
            </button>

            <!-- اختصارات سريعة -->
            <nav class="pointer-events-auto hidden sm:flex items-center gap-1 glass-card px-3 py-1.5 rounded-full text-xs font-semibold text-navyDeep shadow-md">
                <a href="#details" class="px-3 py-1 rounded-full hover:bg-skyLight/60 transition">التفاصيل</a>
                <a href="#location" class="px-3 py-1 rounded-full hover:bg-skyLight/60 transition">الموقع</a>
                <a href="#rsvp" class="px-3 py-1 rounded-full bg-navyDeep text-white hover:bg-navyDeep/90 transition">تأكيد الحضور</a>
            </nav>
        </div>
    </header>

    <!-- ==================== المحتوى الرئيسي للدعوة ==================== -->
    <main id="main-content" class="relative overflow-hidden pb-16">
        
        <!-- عناصر سماوية عائمة في الخلفية -->
        <div class="fixed inset-0 pointer-events-none z-0 overflow-hidden">
            <svg class="absolute top-20 -right-10 w-56 h-28 text-white/60 animate-float" viewBox="0 0 200 100" fill="currentColor">
                <path d="M45,80 L155,80 C175,80 185,65 180,50 C175,35 160,30 148,35 C142,15 120,5 100,12 C82,5 62,15 56,33 C40,28 22,38 20,55 C18,70 30,80 45,80 Z"/>
            </svg>
            <svg class="absolute top-1/3 -left-12 w-64 h-32 text-white/50 animate-float-rev" viewBox="0 0 200 100" fill="currentColor">
                <path d="M45,80 L155,80 C175,80 185,65 180,50 C175,35 160,30 148,35 C142,15 120,5 100,12 C82,5 62,15 56,33 C40,28 22,38 20,55 C18,70 30,80 45,80 Z"/>
            </svg>
            <!-- نجوم ذهبية متلألئة -->
            <svg class="absolute top-28 left-12 w-5 h-5 text-goldChampagne/60 animate-twinkle" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l2.4 7.2H22l-6 4.8 2.3 7.2L12 16.8l-6.3 4.4 2.3-7.2-6-4.8h7.6z"/></svg>
            <svg class="absolute top-96 right-10 w-6 h-6 text-goldChampagne/50 animate-twinkle" style="animation-delay: 1.2s;" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l2.4 7.2H22l-6 4.8 2.3 7.2L12 16.8l-6.3 4.4 2.3-7.2-6-4.8h7.6z"/></svg>
            <svg class="absolute bottom-40 left-8 w-5 h-5 text-royalBlue/30 animate-twinkle" style="animation-delay: 2s;" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l2.4 7.2H22l-6 4.8 2.3 7.2L12 16.8l-6.3 4.4 2.3-7.2-6-4.8h7.6z"/></svg>
        </div>

        <!-- ==================== 2. القسم الافتتاحي (Hero Section) ==================== -->
        <section class="relative z-10 pt-20 pb-10 px-4 sm:px-6">
            <div class="max-w-3xl mx-auto">
                <div class="glass-card royal-border rounded-[2.2rem] p-7 sm:p-12 text-center relative overflow-hidden">
                    
                    <!-- قوس علوي مزخرف -->
                    <div class="w-48 h-6 mx-auto mb-4 text-goldChampagne/80">
                        <svg viewBox="0 0 200 30" fill="none" stroke="currentColor" stroke-width="1.5">
                            <path d="M10 25 Q100 -5 190 25" />
                            <circle cx="100" cy="8" r="3" fill="#C5A059"/>
                            <circle cx="60" cy="14" r="1.5" fill="#C5A059"/>
                            <circle cx="140" cy="14" r="1.5" fill="#C5A059"/>
                        </svg>
                    </div>

                    <!-- البسملة -->
                    <p class="font-amiri text-2xl sm:text-3xl text-navyDeep font-bold mb-6">
                        بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ
                    </p>

                    <!-- آية قرآنية / دعاء -->
                    <div class="bg-skyPastel/80 border border-powderBlue rounded-2xl py-3 px-5 mb-7 inline-block max-w-xl">
                        <p class="font-amiri text-lg sm:text-xl text-navyDeep/90 leading-relaxed">
                            "الْمَالُ وَالْبَنُونَ زِينَةُ الْحَيَاةِ الدُّنْيَا"
                        </p>
                    </div>

                    <!-- نص الترحيب المغربي الراقي -->
                    <p class="text-base sm:text-lg text-navyDeep/85 leading-loose max-w-2xl mx-auto mb-6 font-medium">
                        الحمد لله الذي بنعمته تتم الصالحات، وبفضله تتنزل البركات.
                        <br>
                        بقلوب يملؤها الفرح والسرور، نتشرف بدعوتكم لحضور حفل عقيقة مولودنا الغالي
                    </p>

                    <!-- اسم المولود بتصميم ملكي بارز -->
                    <div class="relative my-6 py-6 px-4 rounded-3xl bg-gradient-to-b from-white/90 to-skyPastel/90 border border-goldChampagne/40 shadow-inner">
                        <!-- هلال صغير يزين الاسم -->
                        <div class="flex justify-center items-center gap-2 mb-1 text-goldChampagne">
                            <span class="text-xs">✦</span>
                            <span class="font-amiri text-base font-bold tracking-wider">الأمير الصغير</span>
                            <span class="text-xs">✦</span>
                        </div>
                        <h2 class="font-ruqaa text-5xl sm:text-7xl gold-text-shimmer py-2 drop-shadow-sm">
                            فيصـل
                        </h2>
                        <p class="font-amiri text-base sm:text-lg text-navyDeep/75 mt-2">
                            أنبته الله نباتاً حسناً، وجعله قرة عين لوالديه ومن حفظة كتابه الكريم
                        </p>
                    </div>

                    <!-- شارة التاريخ البارزة -->
                    <div class="mt-8 inline-flex flex-wrap items-center justify-center gap-3 sm:gap-5 bg-navyDeep text-white px-6 py-3.5 rounded-2xl shadow-lg border border-goldChampagne/60">
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-goldLight" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/>
                            </svg>
                            <span class="font-bold text-sm sm:text-base">الإثنين 16 نونبر 2026</span>
                        </div>
                        <span class="hidden sm:inline text-goldChampagne">|</span>
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-goldLight" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                            <span class="font-bold text-sm sm:text-base">الساعة 19:00 مساءً</span>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- ==================== 3. العداد التنازلي المباشر للحفل ==================== -->
        <section class="relative z-10 py-6 px-4 sm:px-6 reveal-section">
            <div class="max-w-3xl mx-auto text-center">
                <h3 class="font-amiri text-2xl sm:text-3xl font-bold text-navyDeep mb-2">
                    العد التنازلي لليلة الفرح
                </h3>
                <p class="text-xs sm:text-sm text-navyDeep/70 mb-6">نترقب لقاءكم بكل شوق ومحبة</p>

                <div class="grid grid-cols-4 gap-2.5 sm:gap-5 max-w-xl mx-auto" id="countdown-container">
                    <!-- الثواني -->
                    <div class="glass-card rounded-2xl p-3 sm:p-5 transform hover:-translate-y-1 transition duration-300">
                        <span id="cd-seconds" class="block font-cairo text-2xl sm:text-4xl font-extrabold text-royalBlue">00</span>
                        <span class="text-xs sm:text-sm font-semibold text-navyDeep/80 mt-1 block">ثانية</span>
                    </div>
                    <!-- الدقائق -->
                    <div class="glass-card rounded-2xl p-3 sm:p-5 transform hover:-translate-y-1 transition duration-300">
                        <span id="cd-minutes" class="block font-cairo text-2xl sm:text-4xl font-extrabold text-navyDeep">00</span>
                        <span class="text-xs sm:text-sm font-semibold text-navyDeep/80 mt-1 block">دقيقة</span>
                    </div>
                    <!-- الساعات -->
                    <div class="glass-card rounded-2xl p-3 sm:p-5 transform hover:-translate-y-1 transition duration-300">
                        <span id="cd-hours" class="block font-cairo text-2xl sm:text-4xl font-extrabold text-navyDeep">00</span>
                        <span class="text-xs sm:text-sm font-semibold text-navyDeep/80 mt-1 block">ساعة</span>
                    </div>
                    <!-- الأيام -->
                    <div class="glass-card rounded-2xl p-3 sm:p-5 border-goldChampagne/60 transform hover:-translate-y-1 transition duration-300">
                        <span id="cd-days" class="block font-cairo text-2xl sm:text-4xl font-extrabold text-goldChampagne">00</span>
                        <span class="text-xs sm:text-sm font-semibold text-navyDeep/80 mt-1 block">يوم</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 4. تفاصيل الحفل والبرنامج الاحتفالي ==================== -->
        <section id="details" class="relative z-10 py-8 px-4 sm:px-6 reveal-section">
            <div class="max-w-3xl mx-auto">
                <div class="glass-card royal-border rounded-3xl p-6 sm:p-10">
                    <div class="text-center mb-8">
                        <span class="inline-block px-3.5 py-1 rounded-full bg-skyLight text-navyDeep text-xs font-bold mb-2">تفاصيل المناسبة</span>
                        <h3 class="font-amiri text-3xl font-bold text-navyDeep">برنامج حفل العقيقة</h3>
                        <div class="w-20 h-0.5 bg-goldChampagne mx-auto mt-3 rounded-full"></div>
                    </div>

                    <!-- بطاقات التوقيت والبرنامج -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-8">
                        <div class="bg-white/80 rounded-2xl p-5 border border-powderBlue flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-skyPastel text-royalBlue flex items-center justify-center shrink-0">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"/></svg>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-goldChampagne">19:00 مساءً</span>
                                <h4 class="font-bold text-navyDeep text-base">استقبال الضيوف الكرام</h4>
                                <p class="text-xs text-navyDeep/75 mt-1 leading-relaxed">الترحيب بالأهل والأحباب على أنغام الدقة المراكشية والشاي المغربي الأصيل.</p>
                            </div>
                        </div>

                        <div class="bg-white/80 rounded-2xl p-5 border border-powderBlue flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-skyPastel text-royalBlue flex items-center justify-center shrink-0">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/></svg>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-goldChampagne">20:00 مساءً</span>
                                <h4 class="font-bold text-navyDeep text-base">تلاوة قرآنية وأمداح نبوية</h4>
                                <p class="text-xs text-navyDeep/75 mt-1 leading-relaxed">آيات بينات من الذكر الحكيم ودعاء مبارك للمولود فيصل بالصلاح والبركة.</p>
                            </div>
                        </div>

                        <div class="bg-white/80 rounded-2xl p-5 border border-powderBlue flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-skyPastel text-royalBlue flex items-center justify-center shrink-0">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z"/></svg>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-goldChampagne">21:30 مساءً</span>
                                <h4 class="font-bold text-navyDeep text-base">مأدبة العشاء الملكية</h4>
                                <p class="text-xs text-navyDeep/75 mt-1 leading-relaxed">تقديم أطباق العقيقة المغربية التقليدية الفاخرة في أجواء عائلية دافئة.</p>
                            </div>
                        </div>

                        <div class="bg-white/80 rounded-2xl p-5 border border-powderBlue flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-skyPastel text-royalBlue flex items-center justify-center shrink-0">
                                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                            </div>
                            <div>
                                <span class="text-xs font-bold text-goldChampagne">23:00 مساءً</span>
                                <h4 class="font-bold text-navyDeep text-base">حفل الحلويات والتقاط الصور</h4>
                                <p class="text-xs text-navyDeep/75 mt-1 leading-relaxed">توزيع تذكارات الأمير فيصل مع الحلويات المغربية والصور التذكارية.</p>
                            </div>
                        </div>
                    </div>

                    <!-- زر فتح نافذة الملاحظات والزي المقترح -->
                    <div class="text-center">
                        <button id="open-notes-modal" type="button" class="inline-flex items-center gap-2 px-6 py-3 rounded-full bg-skyLight hover:bg-powderBlue text-navyDeep font-bold text-sm transition cursor-pointer border border-royalBlue/20">
                            <svg class="w-4 h-4 text-goldChampagne" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"/></svg>
                            <span>ملاحظات تهم ضيوفنا الكرام</span>
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 5. قسم الموقع الجغرافي (Localisation) ==================== -->
        <section id="location" class="relative z-10 py-8 px-4 sm:px-6 reveal-section">
            <div class="max-w-3xl mx-auto">
                <div class="glass-card royal-border rounded-3xl p-6 sm:p-10">
                    <div class="text-center mb-6">
                        <span class="inline-block px-3.5 py-1 rounded-full bg-skyLight text-navyDeep text-xs font-bold mb-2">الموقع الجغرافي (Localisation)</span>
                        <h3 class="font-amiri text-3xl font-bold text-navyDeep">مكان إقامة الحفل</h3>
                        <p class="text-sm sm:text-base font-semibold text-navyDeep/85 mt-2">
                            قاعة الأفراح الملكية - طنجة (شارع محمد السادس)
                        </p>
                        <p class="text-xs text-navyDeep/65 mt-1">موقف السيارات مجاني ومتوفر أمام القاعة مباشرة</p>
                    </div>

                    <!-- خريطة تفاعلية مدمجة -->
                    <div class="w-full h-64 sm:h-72 rounded-2xl overflow-hidden border-2 border-powderBlue shadow-inner mb-6 relative bg-skyPastel">
                        <iframe 
                            title="موقع حفل عقيقة فيصل"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d51799.26629431234!2d-5.8453482!3d35.7642466!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd0b875cf04c132d%3A0x76bfc571bfb4e17a!2sTangier%2C%20Morocco!5e0!3m2!1sar!2sma!4v1700000000000!5m2!1sar!2sma">
                        </iframe>
                    </div>

                    <!-- أزرار التفاعل مع الموقع -->
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-3">
                        <a href="https://maps.google.com/?q=35.7595,-5.8340" target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 px-6 py-3.5 rounded-full bg-navyDeep hover:bg-[#274b7a] text-white font-bold text-sm shadow-md transition">
                            <svg class="w-5 h-5 text-goldLight" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                            </svg>
                            <span>فتح الموقع في Google Maps</span>
                        </a>

                        <button id="copy-location-btn" type="button" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 px-6 py-3.5 rounded-full bg-white hover:bg-skyPastel text-navyDeep font-bold text-sm border border-goldChampagne/60 shadow-sm transition cursor-pointer">
                            <svg class="w-4 h-4 text-goldChampagne" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"/>
                            </svg>
                            <span>نسخ رابط الموقع</span>
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 6. تأكيد الحضور وسجل التهاني لفيصل ==================== -->
        <section id="rsvp" class="relative z-10 py-8 px-4 sm:px-6 reveal-section">
            <div class="max-w-3xl mx-auto">
                <div class="glass-card royal-border rounded-3xl p-6 sm:p-10">
                    <div class="text-center mb-7">
                        <span class="inline-block px-3.5 py-1 rounded-full bg-skyLight text-navyDeep text-xs font-bold mb-2">تشريفكم يسعدنا</span>
                        <h3 class="font-amiri text-3xl font-bold text-navyDeep">تأكيد الحضور وتهنئة لفيصل</h3>
                        <p class="text-xs sm:text-sm text-navyDeep/75 mt-1">يرجى تأكيد حضوركم وترك دعوة جميلة للأمير الصغير فيصل</p>
                    </div>

                    <form id="rsvp-form" class="space-y-4 max-w-xl mx-auto">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="guest-name" class="block text-xs font-bold text-navyDeep mb-1.5">الاسم الكامل أو اسم العائلة *</label>
                                <input type="text" id="guest-name" required placeholder="مثال: عائلة العلمي" class="w-full px-4 py-3 rounded-xl bg-white/90 border border-powderBlue focus:border-royalBlue focus:ring-2 focus:ring-skyLight outline-none text-sm text-navyDeep transition">
                            </div>
                            <div>
                                <label for="guest-count" class="block text-xs font-bold text-navyDeep mb-1.5">عدد الحضور</label>
                                <select id="guest-count" class="w-full px-4 py-3 rounded-xl bg-white/90 border border-powderBlue focus:border-royalBlue focus:ring-2 focus:ring-skyLight outline-none text-sm text-navyDeep transition">
                                    <option value="1">شخص واحد (1)</option>
                                    <option value="2" selected>شخصان (2)</option>
                                    <option value="3">3 أشخاص</option>
                                    <option value="4">4 أشخاص</option>
                                    <option value="5+">عائلة (5 أشخاص أو أكثر)</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-navyDeep mb-1.5">حالة الحضور</label>
                            <div class="grid grid-cols-2 gap-3">
                                <label class="cursor-pointer">
                                    <input type="radio" name="attendance" value="yes" checked class="peer sr-only">
                                    <div class="p-3 rounded-xl border border-powderBlue bg-white/80 text-center text-xs sm:text-sm font-bold text-navyDeep peer-checked:bg-navyDeep peer-checked:text-white peer-checked:border-goldChampagne transition">
                                        ✨ سأحضر بكل سرور
                                    </div>
                                </label>
                                <label class="cursor-pointer">
                                    <input type="radio" name="attendance" value="no" class="peer sr-only">
                                    <div class="p-3 rounded-xl border border-powderBlue bg-white/80 text-center text-xs sm:text-sm font-bold text-navyDeep peer-checked:bg-slate-600 peer-checked:text-white transition">
                                        💐 أعتذر مع خالص التهاني
                                    </div>
                                </label>
                            </div>
                        </div>

                        <div>
                            <label for="guest-wish" class="block text-xs font-bold text-navyDeep mb-1.5">كلمة أو دعاء للأمير الصغير فيصل *</label>
                            <textarea id="guest-wish" rows="3" required placeholder="مبارك المولود فيصل، جعله الله من الصالحين البارين..." class="w-full px-4 py-3 rounded-xl bg-white/90 border border-powderBlue focus:border-royalBlue focus:ring-2 focus:ring-skyLight outline-none text-sm text-navyDeep transition resize-none"></textarea>
                        </div>

                        <button type="submit" class="w-full py-3.5 rounded-full bg-gradient-to-r from-[#2B588C] via-[#1E3A5F] to-[#2B588C] text-white font-bold text-sm sm:text-base shadow-lg border border-goldChampagne/60 hover:opacity-95 active:scale-[0.99] transition cursor-pointer">
                            إرسال التأكيد والتهنئة 🤍
                        </button>
                    </form>

                    <!-- دفتر التهاني التفاعلي -->
                    <div class="mt-10 pt-8 border-t border-powderBlue">
                        <div class="flex items-center justify-between mb-4">
                            <h4 class="font-amiri text-2xl font-bold text-navyDeep">دفتر تهاني الأحباب لفيصل</h4>
                            <span id="wishes-counter" class="text-xs font-bold px-3 py-1 rounded-full bg-skyLight text-navyDeep">3 تهاني</span>
                        </div>

                        <div id="wishes-wall" class="space-y-3 max-h-80 overflow-y-auto pl-1">
                            <!-- بطاقات تهنئة افتراضية راقية -->
                            <div class="bg-white/85 p-4 rounded-2xl border border-powderBlue/80 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <span class="font-bold text-sm text-navyDeep">الجد والجدة 👑</span>
                                    <span class="text-[11px] px-2 py-0.5 rounded-full bg-skyPastel text-royalBlue font-semibold">حاضرون بكل حب</span>
                                </div>
                                <p class="text-xs sm:text-sm text-navyDeep/80 leading-relaxed">ألف مبروك قدوم حفيدنا الغالي فيصل، جعله الله قرة عين لنا ولكم وألبسه ثوب الصحة والعافية.</p>
                            </div>

                            <div class="bg-white/85 p-4 rounded-2xl border border-powderBlue/80 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <span class="font-bold text-sm text-navyDeep">عائلة بنجلون</span>
                                    <span class="text-[11px] px-2 py-0.5 rounded-full bg-skyPastel text-royalBlue font-semibold">تأكيد الحضور</span>
                                </div>
                                <p class="text-xs sm:text-sm text-navyDeep/80 leading-relaxed">بورك لكم في الموهوب وشكرتم الواهب، نسأل الله أن ينبته نباتاً حسناً. نراكم يوم الإثنين إن شاء الله!</p>
                            </div>

                            <div class="bg-white/85 p-4 rounded-2xl border border-powderBlue/80 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <span class="font-bold text-sm text-navyDeep">سلمى ويوسف</span>
                                    <span class="text-[11px] px-2 py-0.5 rounded-full bg-skyPastel text-royalBlue font-semibold">تأكيد الحضور</span>
                                </div>
                                <p class="text-xs sm:text-sm text-navyDeep/80 leading-relaxed">ما شاء الله تبارك الرحمن، اللهم اجعل فيصل من السعداء في الدنيا والآخرة.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- تذييل الدعوة -->
        <footer class="relative z-10 text-center pt-6 pb-8 px-4">
            <p class="font-amiri text-xl text-navyDeep font-bold">بحضوركم تكتمل فرحتنا</p>
            <p class="text-xs text-navyDeep/60 mt-1">حفل عقيقة فيصل • 16 نونبر 2026</p>
        </footer>
    </main>

    <!-- ==================== نافذة منبثقة (Modal) لملاحظات الضيوف ==================== -->
    <div id="notes-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-4 bg-navyDeep/40 backdrop-blur-sm">
        <div class="glass-card royal-border rounded-3xl max-w-md w-full p-6 sm:p-8 text-center relative transform transition-all">
            <button id="close-notes-modal" type="button" class="absolute top-4 left-4 w-8 h-8 rounded-full bg-skyPastel text-navyDeep hover:bg-powderBlue flex items-center justify-center font-bold cursor-pointer">✕</button>
            <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-skyLight text-goldChampagne flex items-center justify-center">
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
            </div>
            <h4 class="font-amiri text-2xl font-bold text-navyDeep mb-3">ملاحظات الحفل</h4>
            <ul class="text-right space-y-2.5 text-xs sm:text-sm text-navyDeep/85 mb-6">
                <li class="flex items-center gap-2"><span class="text-goldChampagne">✦</span> يُرجى الحضور في الوقت المحدد للاستمتاع بفقرات الاستقبال.</li>
                <li class="flex items-center gap-2"><span class="text-goldChampagne">✦</span> اللباس التقليدي المغربي يضفي رونقاً خاصاً على الأمسية.</li>
                <li class="flex items-center gap-2"><span class="text-goldChampagne">✦</span> نتمنى لأطفالنا الصغار نوماً هنيئاً، كما نرحب بالعائلات الكريمة.</li>
            </ul>
            <button id="confirm-notes-btn" type="button" class="w-full py-2.5 rounded-full bg-navyDeep text-white font-bold text-sm cursor-pointer">حسناً، شكراً لكم</button>
        </div>
    </div>

    <!-- ==================== إشعار منبثق (Toast) للرسائل التأكيدية ==================== -->
    <div id="toast-notification" class="fixed bottom-5 left-1/2 -translate-x-1/2 z-50 px-5 py-3 rounded-full bg-navyDeep text-white text-xs sm:text-sm font-bold shadow-xl border border-goldChampagne/70 opacity-0 pointer-events-none transition-all duration-300 flex items-center gap-2">
        <span class="text-goldLight">✦</span>
        <span id="toast-message">تم بنجاح</span>
    </div>

    <!-- ==================== البرمجة التفاعلية (JavaScript) ==================== -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // 1. فتح شاشة الدعوة الملكية وإطلاق النجوم المتلألئة
            const envelopeScreen = document.getElementById('envelope-screen');
            const openBtn = document.getElementById('open-invitation-btn');

            openBtn.addEventListener('click', () => {
                triggerCelebrationSparkles();
                envelopeScreen.classList.add('opened');
                startGentleLullaby(); // تشغيل نغمة ترحيبية لطيفة عند الفتح
                setTimeout(() => {
                    envelopeScreen.style.display = 'none';
                }, 900);
            });

            // دالة إنشاء نجوم وقلوب زرقاء وذهبية متطايرة
            function triggerCelebrationSparkles() {
                const symbols = ['✦', '★', '✨', '💙', '👑'];
                for (let i = 0; i < 28; i++) {
                    const el = document.createElement('span');
                    el.className = 'sparkle-particle text-lg sm:text-xl';
                    el.textContent = symbols[Math.floor(Math.random() * symbols.length)];
                    el.style.left = Math.random() * 100 + 'vw';
                    el.style.top = (Math.random() * 40 + 10) + 'vh';
                    el.style.color = i % 2 === 0 ? '#C5A059' : '#3B82F6';
                    el.style.animationDuration = (Math.random() * 1.5 + 1.8) + 's';
                    document.body.appendChild(el);
                    setTimeout(() => el.remove(), 3200);
                }
            }

            // 2. نظام الموسيقى الهادئة المدمج عبر Web Audio API (بدون روابط خارجية)
            let audioCtx = null;
            let isPlaying = false;
            let melodyInterval = null;
            const musicBtn = document.getElementById('music-toggle-btn');
            const musicLabel = document.getElementById('music-label');

            function playSoftNote(freq, duration = 1.2) {
                try {
                    if (!audioCtx) {
                        audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                    }
                    if (audioCtx.state === 'suspended') {
                        audioCtx.resume();
                    }
                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(freq, audioCtx.currentTime);

                    gain.gain.setValueAtTime(0.001, audioCtx.currentTime);
                    gain.gain.exponentialRampToValueAtTime(0.04, audioCtx.currentTime + 0.15);
                    gain.gain.exponentialRampToValueAtTime(0.0001, audioCtx.currentTime + duration);

                    osc.connect(gain);
                    gain.connect(audioCtx.destination);
                    osc.start();
                    osc.stop(audioCtx.currentTime + duration);
                } catch (e) {
                    // تجاهل في حال حظر المتصفح للصوت التلقائي
                }
            }

            function startGentleLullaby() {
                if (isPlaying) return;
                isPlaying = true;
                musicLabel.textContent = 'إيقاف النغمة';
                // نوتات تهويدة هادئة وناعمة
                const notes = [523.25, 659.25, 783.99, 659.25, 587.33, 698.46, 880.00, 783.99];
                let step = 0;
                playSoftNote(notes[0]);
                melodyInterval = setInterval(() => {
                    step = (step + 1) % notes.length;
                    playSoftNote(notes[step], 1.4);
                }, 950);
            }

            function stopGentleLullaby() {
                isPlaying = false;
                musicLabel.textContent = 'نغمة هادئة';
                clearInterval(melodyInterval);
            }

            musicBtn.addEventListener('click', () => {
                if (isPlaying) {
                    stopGentleLullaby();
                } else {
                    startGentleLullaby();
                }
            });

            // 3. العداد التنازلي المباشر ليوم 16 نونبر 2026 الساعة 19:00
            const eventDate = new Date('2026-11-16T19:00:00').getTime();
            const daysEl = document.getElementById('cd-days');
            const hoursEl = document.getElementById('cd-hours');
            const minutesEl = document.getElementById('cd-minutes');
            const secondsEl = document.getElementById('cd-seconds');

            function updateCountdown() {
                const now = new Date().getTime();
                const distance = eventDate - now;

                if (distance <= 0) {
                    daysEl.textContent = '00';
                    hoursEl.textContent = '00';
                    minutesEl.textContent = '00';
                    secondsEl.textContent = '00';
                    return;
                }

                const days = Math.floor(distance / (1000 * 60 * 60 * 24));
                const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((distance % (1000 * 60)) / 1000);

                daysEl.textContent = String(days).padStart(2, '0');
                hoursEl.textContent = String(hours).padStart(2, '0');
                minutesEl.textContent = String(minutes).padStart(2, '0');
                secondsEl.textContent = String(seconds).padStart(2, '0');
            }
            updateCountdown();
            setInterval(updateCountdown, 1000);

            // 4. إظهار الأقسام بانسيابية عند التمرير (IntersectionObserver)
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.12 });

            document.querySelectorAll('.reveal-section').forEach(sec => observer.observe(sec));

            // 5. نافذة الملاحظات المنبثقة (Modal)
            const notesModal = document.getElementById('notes-modal');
            const openNotesBtn = document.getElementById('open-notes-modal');
            const closeNotesBtn = document.getElementById('close-notes-modal');
            const confirmNotesBtn = document.getElementById('confirm-notes-btn');

            function toggleModal(show) {
                if (show) {
                    notesModal.classList.remove('hidden');
                    notesModal.classList.add('flex');
                } else {
                    notesModal.classList.add('hidden');
                    notesModal.classList.remove('flex');
                }
            }
            openNotesBtn.addEventListener('click', () => toggleModal(true));
            closeNotesBtn.addEventListener('click', () => toggleModal(false));
            confirmNotesBtn.addEventListener('click', () => toggleModal(false));
            notesModal.addEventListener('click', (e) => {
                if (e.target === notesModal) toggleModal(false);
            });

            // 6. نسخ رابط الموقع الجغرافي مع إشعار أنيق
            const copyLocationBtn = document.getElementById('copy-location-btn');
            copyLocationBtn.addEventListener('click', () => {
                const mapUrl = 'https://maps.google.com/?q=35.7595,-5.8340';
                const tempInput = document.createElement('input');
                tempInput.value = mapUrl;
                document.body.appendChild(tempInput);
                tempInput.select();
                try {
                    document.execCommand('copy');
                    showToast('تم نسخ رابط موقع الحفل بنجاح');
                } catch (err) {
                    showToast('تعذر النسخ، يرجى استخدام زر الفتح المباشر');
                }
                document.body.removeChild(tempInput);
            });

            // 7. معالجة نموذج تأكيد الحضور وإضافة التهنئة إلى دفتر التهاني
            const rsvpForm = document.getElementById('rsvp-form');
            const wishesWall = document.getElementById('wishes-wall');
            const wishesCounter = document.getElementById('wishes-counter');
            let wishesCount = 3;

            rsvpForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const nameInput = document.getElementById('guest-name');
                const wishInput = document.getElementById('guest-wish');
                const countSelect = document.getElementById('guest-count');
                const attendanceVal = document.querySelector('input[name="attendance"]:checked').value;

                const guestName = nameInput.value.trim();
                const guestWish = wishInput.value.trim();

                if (!guestName || !guestWish) return;

                const badgeText = attendanceVal === 'yes' 
                    ? `تأكيد الحضور (${countSelect.value})` 
                    : 'تهنئة عن بُعد';
                const badgeClass = attendanceVal === 'yes'
                    ? 'bg-skyPastel text-royalBlue'
                    : 'bg-amber-50 text-goldChampagne';

                // إنشاء بطاقة التهنئة الجديدة وإضافتها في أعلى القائمة
                const card = document.createElement('div');
                card.className = 'bg-white p-4 rounded-2xl border border-goldChampagne/60 shadow-md transition-all duration-500';
                
                const headerDiv = document.createElement('div');
                headerDiv.className = 'flex items-center justify-between mb-1';
                
                const nameSpan = document.createElement('span');
                nameSpan.className = 'font-bold text-sm text-navyDeep';
                nameSpan.textContent = guestName;

                const statusSpan = document.createElement('span');
                statusSpan.className = `text-[11px] px-2.5 py-0.5 rounded-full font-semibold ${badgeClass}`;
                statusSpan.textContent = badgeText;

                const msgP = document.createElement('p');
                msgP.className = 'text-xs sm:text-sm text-navyDeep/85 leading-relaxed';
                msgP.textContent = guestWish;

                headerDiv.appendChild(nameSpan);
                headerDiv.appendChild(statusSpan);
                card.appendChild(headerDiv);
                card.appendChild(msgP);

                wishesWall.prepend(card);
                wishesCount++;
                wishesCounter.textContent = `${wishesCount} تهاني`;

                rsvpForm.reset();
                triggerCelebrationSparkles();
                showToast('شكراً لك! تم تسجيل ردك وتهنئتك للأمير فيصل');
            });

            // دالة عرض الإشعارات السفلية
            let toastTimeout;
            function showToast(message) {
                const toast = document.getElementById('toast-notification');
                const toastMsg = document.getElementById('toast-message');
                toastMsg.textContent = message;
                toast.classList.remove('opacity-0', 'translate-y-2');
                toast.classList.add('opacity-100', 'translate-y-0');
                clearTimeout(toastTimeout);
                toastTimeout = setTimeout(() => {
                    toast.classList.add('opacity-0', 'translate-y-2');
                    toast.classList.remove('opacity-100', 'translate-y-0');
                }, 3200);
            }
        });
    </script>
</body>
</html>
