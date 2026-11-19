<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN | xaydunglenguyen.com</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói uy tín tại TP Đà Nẵng. Hotline: 0914.725.383.">

    <!-- =====================================================================
         THUMBNAIL CHIA SẺ LINK WEBSITE (OPEN GRAPH / ZALO / FACEBOOK)
         Khi đưa lên WordPress Flatsome, thay đường dẫn logo-le-nguyen.png bằng
         link ảnh logo tải lên Thư viện Media (khuyên dùng kích thước 1200x630px).
         ===================================================================== -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://xaydunglenguyen.com/">
    <meta property="og:site_name" content="Xây Dựng Lê Nguyên">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN">
    <meta property="og:description" content="Chuyên Thiết Kế Kiến Trúc - Thi Công Xây Dựng Trọn Gói - Nội Thất tại Đà Nẵng. Hotline: 0914.725.383.">
    <meta property="og:image" content="https://xaydunglenguyen.com/wp-content/uploads/logo-le-nguyen-share.png">
    <meta property="og:image:alt" content="Logo Công ty TNHH Xây Dựng - Tư Vấn - Thiết Kế Lê Nguyên">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://xaydunglenguyen.com/wp-content/uploads/logo-le-nguyen-share.png">

    <!-- Font Inter & Tailwind CSS CDN -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình màu thương hiệu đồng bộ theo Logo Lê Nguyên (Xanh Navy & Vàng Đồng Kiến Trúc) -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        navy: {
                            950: '#08182C',
                            900: '#0F2A4A',
                            800: '#163B66',
                            700: '#1E4D82',
                            50:  '#F0F5FA',
                        },
                        gold: {
                            600: '#A9771E',
                            500: '#C8922A',
                            400: '#DDA842',
                            100: '#FBF3E2',
                        }
                    }
                }
            }
        };
    </script>

    <style>
        /* Đảm bảo không tràn viền, không lệch phải trên mọi màn hình */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html {
            font-size: 16px;
            scroll-behavior: smooth;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            overflow-x: hidden;
            width: 100%;
            max-width: 100%;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
        .container-95 {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-95 {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu máy tính: chữ gọn đẹp, viết liền trên 1 hàng, không xuống dòng từng mục */
        .desktop-nav-link {
            white-space: nowrap;
            word-break: keep-all;
            font-size: 13px;
            font-weight: 600;
            letter-spacing: 0.01em;
            transition: color 0.2s ease;
        }
        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13.5px;
            }
        }

        /* Dropdown Flatsome mượt mà */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown,
        .nav-item:focus-within .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Đường gạch chân tiêu đề phong cách Flatsome */
        .flatsome-title-bar {
            width: 56px;
            height: 3px;
            background-color: #C8922A;
            border-radius: 999px;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(200, 146, 42, 0); }
            100% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0); }
        }
        .hotline-pulse {
            animation: softPulse 2s infinite;
        }

        /* Thanh cuộn ngang mượt cho danh mục trên mobile nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Banner 2 slide đồng nhất chiều cao tuyệt đối */
        .banner-slide {
            transition: opacity 0.65s ease-in-out;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- =====================================================================
         FLATSOME TOP BAR (THÔNG TIN NHANH)
         ===================================================================== -->
    <div class="bg-navy-900 text-slate-200 text-xs py-2 border-b border-navy-800">
        <div class="container-95 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0914725383" class="inline-flex items-center gap-1.5 hover:text-gold-400 transition-colors font-medium">
                    <svg class="w-3.5 h-3.5 text-gold-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                    </svg>
                    <span>Hotline: 0914.725.383</span>
                </a>
                <span class="hidden sm:inline text-slate-500">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-gold-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                    </svg>
                    <span>Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-3 text-slate-300">
                <span>Website: <strong class="text-white font-semibold">xaydunglenguyen.com</strong></span>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         FLATSOME MAIN HEADER
         - Logo thiết kế chuyên nghiệp, thu gọn nhỏ lại
         - Không có nút gọi ngay trên header để tránh tràn viền
         - Danh mục viết liền trên 1 hàng gọn đẹp, không xuống dòng từng mục
         ===================================================================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="container-95 flex items-center justify-between gap-3 py-2.5">
            <!-- LOGO CÔNG TY LÊ NGUYÊN (Gọn nhỏ, chuyên nghiệp) -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="Xây Dựng Lê Nguyên">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Xây Dựng Lê Nguyên">
                    <!-- Khung nền kiến trúc Xanh Navy -->
                    <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F2A4A"/>
                    <rect x="4" y="4" width="56" height="56" rx="10" stroke="#C8922A" stroke-width="1.5" stroke-opacity="0.6"/>
                    <!-- Mái nhà kiến trúc vàng đồng -->
                    <path d="M12 29L32 13L52 29" stroke="#C8922A" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                    <!-- Chữ L & N cách điệu khối công trình -->
                    <path d="M20 31V48H30" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M35 48V31L45 48V31" stroke="#DDA842" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                    <!-- Đế nền vững chắc -->
                    <line x1="16" y1="53" x2="48" y2="53" stroke="#C8922A" stroke-width="2" stroke-linecap="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy-900 group-hover:text-gold-600 transition-colors">
                        LÊ NGUYÊN
                    </div>
                    <div class="text-[9.5px] sm:text-[10px] font-semibold uppercase tracking-wider text-gold-600">
                        Xây Dựng • Tư Vấn • Thiết Kế
                    </div>
                </div>
            </a>

            <!-- MENU MÁY TÍNH (Viết liền 1 hàng, không xuống dòng tên danh mục) -->
            <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-4 xl:gap-x-6 gap-y-1.5" aria-label="Menu chính">
                <a href="#trang-chu" class="desktop-nav-link text-gold-600 hover:text-gold-500 py-1.5">Trang chủ</a>
                <a href="#gioi-thieu" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5">Giới thiệu</a>

                <!-- Dropdown: Công trình thực tế (Theo web mẫu Tín Trường Thịnh) -->
                <div class="relative nav-item">
                    <a href="#cong-trinh-thuc-te" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5 inline-flex items-center gap-1">
                        <span>Công trình thực tế</span>
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('phan-tho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Thi công phần thô & Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="relative nav-item">
                    <a href="#linh-vuc" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5 inline-flex items-center gap-1">
                        <span>Lĩnh vực hoạt động</span>
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Thi công phần thô</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Thi công hoàn thiện</a>
                            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Mẫu thiết kế -->
                <div class="relative nav-item">
                    <a href="#du-an-da-nang" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5 inline-flex items-center gap-1">
                        <span>Dự án Đà Nẵng</span>
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-52 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Dự án tiêu biểu Đà Nẵng</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Mẫu thiết kế nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('noi-that')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Mẫu thiết kế nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Báo giá -->
                <div class="relative nav-item">
                    <a href="#bao-gia" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5 inline-flex items-center gap-1">
                        <span>Báo giá</span>
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-2">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-navy-50 hover:text-navy-900">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#tin-tuc" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5">Tin tức</a>
                <a href="#doi-tac" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5">Đối tác</a>
                <a href="#lien-he" class="desktop-nav-link text-navy-900 hover:text-gold-600 py-1.5">Liên hệ</a>
            </nav>

            <!-- NÚT MỞ MENU ĐIỆN THOẠI -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden p-2 rounded-lg text-navy-900 hover:bg-slate-100 focus:outline-none" aria-label="Mở menu điều hướng">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>
    </header>

    <!-- =====================================================================
         MOBILE DRAWER MENU (TỐI ƯU HIỂN THỊ DANH MỤC TRÊN ĐIỆN THOẠI)
         ===================================================================== -->
    <div id="mobileMenuBackdrop" class="fixed inset-0 bg-navy-950/60 z-50 hidden opacity-0 transition-opacity duration-300"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 right-0 h-full w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3.5 bg-navy-900 text-white">
            <span class="font-bold text-sm tracking-wide">DANH MỤC LÊ NGUYÊN</span>
            <button id="closeMobileMenuBtn" type="button" class="p-1.5 rounded-lg hover:bg-navy-800 text-slate-200" aria-label="Đóng menu">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
                </svg>
            </button>
        </div>
        <nav class="flex-1 overflow-y-auto p-3 space-y-1 text-sm font-medium text-slate-800">
            <a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50 text-gold-600 font-semibold">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Giới thiệu công ty</a>
            <a href="#linh-vuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Lĩnh vực hoạt động</a>
            <div class="px-3 py-2">
                <div class="text-xs font-bold uppercase text-navy-900 mb-1.5">Công trình thực tế</div>
                <div class="pl-3 space-y-1 border-l-2 border-gold-400 text-xs text-slate-600">
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('all')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Tất cả công trình</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Nhà phố hiện đại</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Biệt thự sang trọng</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Khách sạn – Căn hộ – Phòng trọ</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('phan-tho')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Thi công phần thô</a>
                    <a href="#cong-trinh-thuc-te" onclick="filterProjects('noi-that')" class="mobile-nav-link block py-1.5 hover:text-navy-900">Hoàn thiện & Nội thất</a>
                </div>
            </div>
            <a href="#du-an-da-nang" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Dự án tại Đà Nẵng</a>
            <a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Báo giá & Yêu cầu tư vấn</a>
            <a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Tin tức xây dựng</a>
            <a href="#doi-tac" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Đối tác đồng hành</a>
            <a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-navy-50">Liên hệ & Bản đồ</a>
        </nav>
        <div class="p-4 border-t border-slate-100 bg-slate-50 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-navy-900">Hotline: 0914.725.383</div>
            <div>Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng</div>
        </div>
    </aside>

    <!-- =====================================================================
         SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU)
         - Toàn bộ hình ảnh và chữ nằm gọn trong banner
         - Chữ cách xa viền ảnh banner (padding rộng an toàn)
         - Đảm bảo trên điện thoại và máy tính không bị mất/thiếu chữ
         - Không đặt nhãn dán
         ===================================================================== -->
    <section id="trang-chu" class="w-full bg-navy-950">
        <div id="heroSlider" class="relative w-full overflow-hidden h-[340px] sm:h-[420px] md:h-[490px] lg:h-[540px] select-none">

            <!-- SLIDE 1 -->
            <div class="banner-slide absolute inset-0 w-full h-full opacity-100 z-10" data-slide="0">
                <img
                    src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                    data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                    alt="Công trình thi công xây dựng trọn gói Công ty Lê Nguyên"
                    class="w-full h-full object-cover object-center"
                    onerror="handleDriveImageError(this, 'Xay Dung Le Nguyen - Banner 1')"
                >
                <!-- Lớp phủ gradient giúp chữ nổi bật và hài hòa theo màu thương hiệu -->
                <div class="absolute inset-0 bg-gradient-to-r from-navy-950/90 via-navy-900/75 to-navy-900/45"></div>

                <!-- Khung chữ đặt cách xa viền banner ở cả 4 phía -->
                <div class="absolute inset-0 flex items-center">
                    <div class="container-95">
                        <div class="px-8 sm:px-14 md:px-20 py-6 max-w-3xl">
                            <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-gold-400 mb-2 sm:mb-3">
                                CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN
                            </p>
                            <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                Kiến Tạo Không Gian Sống Bền Vững &amp; Chuẩn Mực Tại Đà Nẵng
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6 max-w-2xl">
                                Chuyên tư vấn thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói. Cam kết chất lượng vững chắc, đúng tiến độ và chi phí minh bạch.
                            </p>
                            <div class="flex flex-wrap items-center gap-3">
                                <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-semibold shadow-md transition-colors">
                                    Nhận Báo Giá Miễn Phí
                                </a>
                                <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/10 hover:bg-white/20 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                    Xem Công Trình Thực Tế
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- SLIDE 2 (Kích thước & bố cục lề an toàn bằng tuyệt đối Slide 1) -->
            <div class="banner-slide absolute inset-0 w-full h-full opacity-0 z-0 pointer-events-none" data-slide="1">
                <img
                    src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                    data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                    alt="Dự án nhà phố biệt thự thi công thực tế tại Đà Nẵng - Lê Nguyên"
                    class="w-full h-full object-cover object-center"
                    onerror="handleDriveImageError(this, 'Du An Da Nang - Le Nguyen')"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-navy-950/90 via-navy-900/75 to-navy-900/45"></div>

                <!-- Khung chữ cách xa viền ảnh banner -->
                <div class="absolute inset-0 flex items-center">
                    <div class="container-95">
                        <div class="px-8 sm:px-14 md:px-20 py-6 max-w-3xl">
                            <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-gold-400 mb-2 sm:mb-3">
                                GIẢI PHÁP XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP
                            </p>
                            <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                Thi Công Thực Tế Biệt Thự, Nhà Phố &amp; Khách Sạn Tại Đà Nẵng
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6 max-w-2xl">
                                Đội ngũ kỹ sư, kiến trúc sư tận tâm trực tiếp giám sát tại công trường. Bảo hành kết cấu dài hạn, đồng hành cùng chủ đầu tư từ bản vẽ đến ngày bàn giao.
                            </p>
                            <div class="flex flex-wrap items-center gap-3">
                                <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-semibold shadow-md transition-colors">
                                    Khám Phá Dự Án Đà Nẵng
                                </a>
                                <a href="tel:0914725383" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/10 hover:bg-white/20 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
                                    Tư Vấn: 0914.725.383
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng Trái / Phải đặt sát mép ngoài, không che chữ -->
            <button id="prevSlideBtn" type="button" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-navy-950/55 hover:bg-gold-500 text-white flex items-center justify-center transition-colors" aria-label="Banner trước">
                <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
            </button>
            <button id="nextSlideBtn" type="button" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-navy-950/55 hover:bg-gold-500 text-white flex items-center justify-center transition-colors" aria-label="Banner tiếp theo">
                <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
            </button>

            <!-- Dấu chấm chỉ báo slide -->
            <div class="absolute bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
                <button type="button" onclick="goToSlide(0)" class="slider-dot w-7 h-2 rounded-full bg-gold-500 transition-all" aria-label="Chọn banner 1"></button>
                <button type="button" onclick="goToSlide(1)" class="slider-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Chọn banner 2"></button>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 2: DỊCH VỤ TIÊU BIỂU (CHUẨN BỐ CỤC WEB MẪU TÍN TRƯỜNG THỊNH)
         ===================================================================== -->
    <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
        <div class="container-95">
            <div class="text-center mb-8">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ tư vấn thiết kế kiến trúc, thi công phần thô đến hoàn thiện nội thất chìa khóa trao tay.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-5">
                <!-- Dịch vụ 1: Thiết kế -->
                <div class="group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900"
                            alt="Thiết kế kiến trúc và nội thất Lê Nguyên"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Thiet Ke Kien Truc')"
                        >
                    </div>
                    <div class="p-5 text-center">
                        <h3 class="text-base sm:text-lg font-bold text-navy-900 uppercase mb-2">Thiết Kế Kiến Trúc</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Thiết kế mặt bằng công năng khoa học, phối cảnh 3D hiện đại cho nhà phố, biệt thự, khách sạn và văn phòng.
                        </p>
                    </div>
                </div>

                <!-- Dịch vụ 2: Thi công -->
                <div class="group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                            alt="Thi công phần thô và trọn gói Lê Nguyên"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Thi Cong Xay Dung')"
                        >
                    </div>
                    <div class="p-5 text-center">
                        <h3 class="text-base sm:text-lg font-bold text-navy-900 uppercase mb-2">Thi Công Xây Dựng</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Thi công phần thô và xây nhà trọn gói đúng quy chuẩn kỹ thuật, vật tư chính hãng, giám sát chặt chẽ từng hạng mục.
                        </p>
                    </div>
                </div>

                <!-- Dịch vụ 3: Nội thất -->
                <div class="group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900"
                            alt="Thi công hoàn thiện nội thất Lê Nguyên"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Thi Cong Noi That')"
                        >
                    </div>
                    <div class="p-5 text-center">
                        <h3 class="text-base sm:text-lg font-bold text-navy-900 uppercase mb-2">Hoàn Thiện &amp; Nội Thất</h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Hoàn thiện không gian sống tinh tế, tối ưu công năng sử dụng và thẩm mỹ bền vững theo ngân sách của gia chủ.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 3: GIỚI THIỆU CÔNG TY LÊ NGUYÊN (2 CỘT FLATSOME)
         ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-navy-50 border-y border-slate-200/70">
        <div class="container-95">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-6 space-y-4">
                    <div class="text-xs font-bold uppercase tracking-widest text-gold-600">
                        Về Chúng Tôi
                    </div>
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 leading-snug">
                        CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN
                    </h2>
                    <div class="flatsome-title-bar"></div>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        <strong>Xây Dựng Lê Nguyên</strong> chuyên hoạt động trong lĩnh vực Thiết kế Kiến trúc – Tư vấn – Thi công xây dựng phần thô, hoàn thiện và nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại khu vực <strong>TP Đà Nẵng</strong> và miền Trung.
                    </p>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        Với phương châm đặt chữ <strong>"TÂM"</strong> và <strong>"CHẤT LƯỢNG"</strong> làm nền tảng cốt lõi, chúng tôi luôn mang đến công trình đạt tiêu chuẩn <strong>An Toàn – Bền Vững – Đúng Tiến Độ – Tối Ưu Chi Phí</strong>, giúp Quý khách hàng an tâm tuyệt đối khi trao gửi tổ ấm.
                    </p>

                    <!-- Thông số nổi bật đơn giản -->
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-navy-900">100+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình bàn giao</div>
                        </div>
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-gold-600">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Vật tư chuẩn cam kết</div>
                        </div>
                        <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-navy-900">5 Năm</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-6">
                    <div class="rounded-2xl overflow-hidden shadow-lg border border-slate-200 bg-white">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w1200"
                            data-fallback="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1200"
                            alt="Hình ảnh thi công thực tế Công ty TNHH Xây Dựng Lê Nguyên"
                            class="w-full h-[260px] sm:h-[340px] md:h-[380px] object-cover"
                            onerror="handleDriveImageError(this, 'Cong Ty Xay Dung Le Nguyen')"
                        >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 4: THẾ MẠNH CỦA CHÚNG TÔI (6 HẠNG MỤC THEO WEB MẪU)
         ===================================================================== -->
    <section class="py-10 sm:py-14 bg-white">
        <div class="container-95">
            <div class="text-center mb-8">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Thế Mạnh Của Xây Dựng Lê Nguyên
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5">
                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp cùng đội ngũ kỹ sư hiện trường dày dạn kinh nghiệm và thợ lành nghề.</p>
                </div>

                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Cập nhật xu hướng thiết kế hiện đại</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Ứng dụng vật liệu bền vững và biện pháp thi công tiên tiến, phù hợp khí hậu miền Trung.</p>
                </div>

                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Giám sát tiến độ chuẩn xác</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Báo cáo tiến độ thi công định kỳ bằng hình ảnh thực tế, đảm bảo bàn giao đúng cam kết hợp đồng.</p>
                </div>

                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Bảo hành công trình lâu dài</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu và bảo trì chống thấm rõ ràng, hỗ trợ khách hàng tận tình sau bàn giao.</p>
                </div>

                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Chi phí hợp lý, không phát sinh</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Dự toán bóc tách khối lượng chi tiết, minh bạch từng chủng loại vật tư để tối ưu ngân sách chủ đầu tư.</p>
                </div>

                <div class="p-5 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:shadow-md transition-all">
                    <div class="w-10 h-10 rounded-lg bg-navy-900 text-gold-400 flex items-center justify-center mb-3.5">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    </div>
                    <h3 class="text-sm sm:text-base font-bold text-navy-900 mb-1.5">Hỗ trợ tư vấn miễn phí 24/7</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế, tư vấn phong thủy và phương án xây dựng tối ưu qua Hotline 0914.725.383.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 5: CÔNG TRÌNH THỰC TẾ THI CÔNG (9 ẢNH THỰC TẾ GOOGLE DRIVE)
         - Danh mục theo web mẫu Tín Trường Thịnh, chữ danh mục nhỏ gọn đẹp
         - Chia thành 2 cột trên điện thoại, 3-4 cột trên máy tính
         - Tên sản phẩm/công trình hiển thị đầy đủ, không tràn ra ngoài, không thiếu chữ
         - Không có nhãn dán trên hình ảnh
         ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200/80">
        <div class="container-95">
            <div class="text-center mb-6">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Công Trình Thực Tế Thi Công
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
            </div>

            <!-- Bộ lọc danh mục nhỏ gọn, dễ bấm trên cả điện thoại và máy tính -->
            <div id="projectCategoryTabs" class="flex flex-wrap items-center justify-center gap-2 mb-7">
                <button type="button" data-filter="all" onclick="filterProjects('all')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-navy-900 text-white transition-colors whitespace-nowrap">
                    Tất cả
                </button>
                <button type="button" data-filter="nha-pho" onclick="filterProjects('nha-pho')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap">
                    Nhà phố
                </button>
                <button type="button" data-filter="biet-thu" onclick="filterProjects('biet-thu')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap">
                    Biệt thự
                </button>
                <button type="button" data-filter="khach-san" onclick="filterProjects('khach-san')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap">
                    Khách sạn – Căn hộ
                </button>
                <button type="button" data-filter="phan-tho" onclick="filterProjects('phan-tho')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap">
                    Thi công phần thô
                </button>
                <button type="button" data-filter="noi-that" onclick="filterProjects('noi-that')" class="cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap">
                    Hoàn thiện &amp; Nội thất
                </button>
            </div>

            <!-- Lưới sản phẩm / công trình: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính -->
            <div id="realProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-4 gap-3 sm:gap-5">
                <!-- Nội dung được render tự động từ dữ liệu 9 ảnh thực tế Google Drive -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 6: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE)
         - Chia thành 2 cột trên điện thoại, 5 cột (2 hàng đều đẹp) trên máy tính lớn
         - Không nhãn dán, tên dự án hiển thị rõ ràng, không tràn chữ
         ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-white border-t border-slate-200/80">
        <div class="container-95">
            <div class="text-center mb-8">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tổng hợp các công trình nhà ở, biệt thự, khách sạn và văn phòng do Xây Dựng Lê Nguyên tư vấn, thiết kế và thi công tại TP Đà Nẵng.
                </p>
            </div>

            <div id="daNangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Nội dung được render tự động từ dữ liệu 10 ảnh dự án Đà Nẵng Google Drive -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 7: BẢNG GIÁ THAM KHẢO & FORM YÊU CẦU TƯ VẤN - BÁO GIÁ
         ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-navy-900 text-white">
        <div class="container-95">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Cột trái: Bảng báo giá tham khảo các gói dịch vụ -->
                <div class="lg:col-span-5 space-y-5">
                    <div>
                        <p class="text-xs font-bold uppercase tracking-widest text-gold-400 mb-1.5">
                            Minh Bạch &amp; Tối Ưu Chi Phí
                        </p>
                        <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug">
                            Bảng Báo Giá Thiết Kế &amp; Thi Công Xây Dựng
                        </h2>
                        <div class="flatsome-title-bar mt-3"></div>
                    </div>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                        Đơn giá tham khảo dành cho các công trình dân dụng tại Đà Nẵng. Liên hệ trực tiếp để kỹ sư Lê Nguyên khảo sát thực tế và lập dự toán chi tiết miễn phí.
                    </p>

                    <div class="space-y-3">
                        <div class="flex items-center justify-between p-3.5 rounded-xl bg-navy-800/80 border border-navy-700">
                            <div>
                                <div class="text-sm font-bold text-white">Thiết kế Kiến trúc – Nội thất</div>
                                <div class="text-xs text-slate-300">Hồ sơ 2D, 3D, kết cấu &amp; điện nước</div>
                            </div>
                            <div class="text-right font-bold text-gold-400 text-sm whitespace-nowrap pl-2">Từ 150.000đ/m²</div>
                        </div>

                        <div class="flex items-center justify-between p-3.5 rounded-xl bg-navy-800/80 border border-navy-700">
                            <div>
                                <div class="text-sm font-bold text-white">Thi công phần thô &amp; nhân công</div>
                                <div class="text-xs text-slate-300">Vật tư thô chính hãng, chuẩn kỹ thuật</div>
                            </div>
                            <div class="text-right font-bold text-gold-400 text-sm whitespace-nowrap pl-2">Từ 3.600.000đ/m²</div>
                        </div>

                        <div class="flex items-center justify-between p-3.5 rounded-xl bg-navy-800/80 border border-navy-700">
                            <div>
                                <div class="text-sm font-bold text-white">Thi công hoàn thiện công trình</div>
                                <div class="text-xs text-slate-300">Ốp lát, sơn nước, trần thạch cao, cửa</div>
                            </div>
                            <div class="text-right font-bold text-gold-400 text-sm whitespace-nowrap pl-2">Từ 2.400.000đ/m²</div>
                        </div>

                        <div class="flex items-center justify-between p-3.5 rounded-xl bg-navy-800/80 border border-gold-500/60">
                            <div>
                                <div class="text-sm font-bold text-white">Xây nhà trọn gói (Chìa khóa trao tay)</div>
                                <div class="text-xs text-slate-300">Miễn phí hồ sơ thiết kế &amp; xin giấy phép</div>
                            </div>
                            <div class="text-right font-bold text-gold-400 text-sm whitespace-nowrap pl-2">Từ 5.800.000đ/m²</div>
                        </div>
                    </div>
                </div>

                <!-- Cột phải: Form yêu cầu tư vấn & báo giá (Theo form web mẫu Tín Trường Thịnh) -->
                <div class="lg:col-span-7">
                    <div class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
                        <h3 class="text-lg sm:text-xl font-extrabold text-navy-900 uppercase mb-1">
                            Đăng Ký Yêu Cầu Tư Vấn &amp; Báo Giá Miễn Phí
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-500 mb-5">
                            Vui lòng để lại thông tin, kiến trúc sư Lê Nguyên sẽ liên hệ tư vấn và gửi báo giá chi tiết trong vòng 30 phút.
                        </p>

                        <form id="quoteForm" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerName" class="block text-xs font-semibold text-navy-900 mb-1.5">Họ và tên *</label>
                                    <input id="customerName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10">
                                </div>
                                <div>
                                    <label for="customerPhone" class="block text-xs font-semibold text-navy-900 mb-1.5">Số điện thoại *</label>
                                    <input id="customerPhone" type="tel" required placeholder="VD: 0914.725.383" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="projectType" class="block text-xs font-semibold text-navy-900 mb-1.5">Loại công trình</label>
                                    <select id="projectType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                        <option value="Chưa xác định">Chưa xác định</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="budgetRange" class="block text-xs font-semibold text-navy-900 mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="budgetRange" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10">
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ" selected>1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                        <option value="Chưa xác định">Chưa xác định</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label for="customerEmail" class="block text-xs font-semibold text-navy-900 mb-1.5">Email (không bắt buộc)</label>
                                <input id="customerEmail" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10">
                            </div>

                            <div>
                                <label for="customerNote" class="block text-xs font-semibold text-navy-900 mb-1.5">Diện tích đất &amp; Yêu cầu chi tiết</label>
                                <textarea id="customerNote" rows="3" placeholder="VD: Đất 5x20m tại Đà Nẵng, nhu cầu xây nhà 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy-900 focus:ring-2 focus:ring-navy-900/10"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3 px-6 rounded-lg bg-gold-500 hover:bg-gold-600 text-white font-bold text-sm uppercase tracking-wide shadow-md transition-colors">
                                Gửi Yêu Cầu Báo Giá Ngay
                            </button>

                            <!-- Hộp thông báo kết quả gửi form (thay thế hoàn toàn alert) -->
                            <div id="quoteFeedback" class="hidden p-3.5 rounded-lg text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 8: TIN TỨC & KIẾN THỨC XÂY DỰNG (TRANG CHỦ)
         ===================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200/80">
        <div class="container-95">
            <div class="text-center mb-8">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Tin Tức &amp; Kinh Nghiệm Xây Dựng
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
            </div>

            <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết được render từ dữ liệu bài viết chuẩn ngành xây dựng -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 9: DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
         ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white border-t border-slate-200/80">
        <div class="container-95">
            <div class="text-center mb-7">
                <h2 class="text-xl sm:text-2xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Đối Tác Vật Tư &amp; Đồng Hành
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
                <p class="text-xs sm:text-sm text-slate-600 mt-2.5">
                    Xây Dựng Lê Nguyên cam kết sử dụng vật liệu chính hãng từ các thương hiệu hàng đầu Việt Nam và quốc tế.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500">Thép xây dựng</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500">Xi măng cao cấp</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">DULUX</span>
                    <span class="text-[10px] text-slate-500">Sơn nội ngoại thất</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">AN CƯỜNG</span>
                    <span class="text-[10px] text-slate-500">Gỗ nội thất</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">XINGFA</span>
                    <span class="text-[10px] text-slate-500">Cửa nhôm kính</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">CADIVI</span>
                    <span class="text-[10px] text-slate-500">Dây cáp điện</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">INAX</span>
                    <span class="text-[10px] text-slate-500">Thiết bị vệ sinh</span>
                </div>
                <div class="h-16 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 text-center hover:border-gold-500 transition-colors">
                    <span class="text-xs sm:text-sm font-extrabold text-navy-900 tracking-tight">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500">Gạch ốp lát</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 10: BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ
         ===================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-navy-50 border-t border-slate-200">
        <div class="container-95">
            <div class="text-center mb-8">
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-navy-900 uppercase tracking-tight">
                    Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
                </h2>
                <div class="flatsome-title-bar mx-auto mt-3"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột trái: Google Maps trụ sở Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng -->
                <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <div>
                            <h3 class="text-sm sm:text-base font-bold text-navy-900">Vị Trí Trụ Sở Công Ty Trên Google Maps</h3>
                            <p class="text-xs text-slate-500">Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng</p>
                        </div>
                        <a href="https://maps.google.com/?q=Thôn+An+Phú,+Quế+Sơn+Trung,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-gold-600 hover:text-gold-500 underline">
                            Mở bản đồ lớn
                        </a>
                    </div>
                    <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty TNHH Xây Dựng Tư Vấn Thiết Kế Lê Nguyên"
                            src="https://maps.google.com/maps?q=Th%C3%B4n%20An%20Ph%C3%BA%2C%20Qu%E1%BA%BF%20S%C6%A1n%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=13&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                </div>

                <!-- Cột phải: Khung Fanpage Facebook đặt trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-100 flex items-center justify-between">
                        <div class="flex items-center gap-2">
                            <svg class="w-5 h-5 text-[#1877F2]" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                            <h3 class="text-sm sm:text-base font-bold text-navy-900">Fanpage Chính Thức</h3>
                        </div>
                        <span class="text-xs text-slate-500">Facebook</span>
                    </div>

                    <!-- Cover & Avatar Fanpage -->
                    <div class="relative h-36 bg-navy-900 overflow-hidden">
                        <img
                            src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                            data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                            alt="Ảnh bìa Fanpage Xây Dựng Lê Nguyên"
                            class="w-full h-full object-cover opacity-80"
                            onerror="handleDriveImageError(this, 'Fanpage Xay Dung Le Nguyen')"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-navy-950/85 via-navy-950/30 to-transparent"></div>
                        <div class="absolute bottom-3 left-4 right-4 flex items-end gap-3">
                            <div class="w-12 h-12 rounded-lg bg-white p-1 shadow-md shrink-0">
                                <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <rect x="2" y="2" width="60" height="60" rx="10" fill="#0F2A4A"/>
                                    <path d="M12 29L32 13L52 29" stroke="#C8922A" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                                    <path d="M20 31V48H30" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                                    <path d="M35 48V31L45 48V31" stroke="#DDA842" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                            </div>
                            <div class="min-w-0">
                                <div class="text-white font-bold text-sm leading-tight truncate">Xây Dựng - Thiết Kế Lê Nguyên</div>
                                <div class="text-slate-200 text-xs mt-0.5">xaydunglenguyen.com • Đà Nẵng</div>
                            </div>
                        </div>
                    </div>

                    <!-- Nội dung cập nhật mới trên Fanpage -->
                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <div class="space-y-2.5 text-xs sm:text-sm text-slate-600">
                            <p class="leading-relaxed">
                                Theo dõi Fanpage <strong>Công Ty TNHH Xây Dựng - Tư Vấn - Thiết Kế Lê Nguyên</strong> để cập nhật hình ảnh thực tế công trình đang thi công mỗi ngày, mẫu nhà phố đẹp và báo giá ưu đãi tại Đà Nẵng.
                            </p>
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-100 text-xs text-slate-700 space-y-1">
                                <div class="font-semibold text-navy-900">Thông tin liên hệ trực tiếp:</div>
                                <div>Hotline / Zalo: <strong>0914.725.383</strong></div>
                                <div>Địa chỉ: Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng</div>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-2.5">
                            <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1565D8] text-white text-xs font-semibold transition-colors">
                                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M14 9V5a3 3 0 00-3-3l-4 9v11h11.28a2 2 0 002-1.7l1.38-9a2 2 0 00-2-2.3H14zM7 22H4a2 2 0 01-2-2v-7a2 2 0 012-2h3"/></svg>
                                <span>Theo Dõi Trang</span>
                            </a>
                            <a href="https://zalo.me/0914725383" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-navy-900 hover:bg-navy-800 text-white text-xs font-semibold transition-colors">
                                <span>Nhắn Tin Tư Vấn</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FLATSOME FOOTER
         ===================================================================== -->
    <footer class="bg-navy-950 text-slate-300 pt-12 pb-6 border-t-4 border-gold-500">
        <div class="container-95">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-navy-800">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect x="2" y="2" width="60" height="60" rx="12" fill="#163B66"/>
                            <rect x="4" y="4" width="56" height="56" rx="10" stroke="#C8922A" stroke-width="1.5"/>
                            <path d="M12 29L32 13L52 29" stroke="#C8922A" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M20 31V48H30" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M35 48V31L45 48V31" stroke="#DDA842" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <div>
                            <div class="text-white font-extrabold text-sm sm:text-base">CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN</div>
                            <div class="text-xs text-gold-400 font-medium">xaydunglenguyen.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 pt-1">
                        <li><strong class="text-white">Địa chỉ:</strong> Thôn An Phú, Xã Quế Sơn Trung, TP Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0914725383" class="text-gold-400 font-semibold hover:underline">0914.725.383</a></li>
                        <li><strong class="text-white">Website:</strong> xaydunglenguyen.com</li>
                        <li><strong class="text-white">Mã số thuế:</strong> 4001186499</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc" class="hover:text-gold-400 transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-400 transition-colors">Thi công phần thô</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-400 transition-colors">Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-400 transition-colors">Xây dựng nhà trọn gói</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-400 transition-colors">Cải tạo &amp; Sửa chữa nhà ở</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-2 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider">Danh Mục</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-gold-400 transition-colors">Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-gold-400 transition-colors">Dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-gold-400 transition-colors">Báo giá xây dựng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-gold-400 transition-colors">Tin tức &amp; Kiến thức</a></li>
                        <li><a href="#doi-tac" class="hover:text-gold-400 transition-colors">Đối tác đồng hành</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Giờ làm việc -->
                <div class="lg:col-span-2 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider">Hỗ Trợ Khách Hàng</h4>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                        Thứ 2 – Thứ 7: 07:30 – 17:30<br>
                        Chủ nhật: Tư vấn qua Hotline &amp; Zalo 24/7.
                    </p>
                    <a href="#bao-gia" class="inline-block mt-1 px-4 py-2 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs font-semibold transition-colors">
                        Yêu Cầu Báo Giá
                    </a>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright 2026 © CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN | xaydunglenguyen.com
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích gọn đẹp trên cả máy tính và điện thoại, không gây tràn viền
         ===================================================================== -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Facebook Xây Dựng Lê Nguyên" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D0] text-white px-3 py-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition-all">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24">
                <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
            </svg>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0914725383" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0914.725.383" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white px-3 py-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition-all">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0914725383" aria-label="Gọi Hotline 0914.725.383" class="hotline-pulse flex items-center gap-2 bg-gold-500 hover:bg-gold-600 text-white px-3.5 py-2.5 sm:px-4 sm:py-3 rounded-full shadow-xl transition-all">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
            </svg>
            <span class="text-xs sm:text-sm font-extrabold tracking-wide">0914.725.383</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT (KHÔNG DÙNG ALERT)
         ===================================================================== -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-navy-950/75 backdrop-blur-sm">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white/95 backdrop-blur px-4 sm:px-5 py-3.5 border-b border-slate-100 flex items-center justify-between gap-3">
                <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-navy-900 leading-snug">Chi tiết</h3>
                <button type="button" onclick="closeDetailModal()" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 shrink-0" aria-label="Đóng cửa sổ">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-4 sm:p-5 space-y-4">
                <div class="rounded-xl overflow-hidden bg-slate-100 border border-slate-200">
                    <img id="modalImage" src="" alt="" class="w-full max-h-[380px] object-cover">
                </div>
                <div id="modalMeta" class="text-xs font-semibold text-gold-600"></div>
                <div id="modalBody" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2"></div>
                <div class="pt-2 flex flex-wrap gap-2.5">
                    <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2.5 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-semibold transition-colors">
                        Nhận Báo Giá Công Trình Tương Tự
                    </a>
                    <a href="tel:0914725383" class="px-4 py-2.5 rounded-lg bg-navy-900 hover:bg-navy-800 text-white text-xs sm:text-sm font-semibold transition-colors">
                        Gọi Tư Vấn: 0914.725.383
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, DANH MỤC, DỰ ÁN GOOGLE DRIVE & FORM
         ===================================================================== -->
    <script>
        /**
         * Xử lý dự phòng tải ảnh Google Drive mượt mà:
         * 1. Thử link lh3.googleusercontent.com độ phân giải cao
         * 2. Nếu lỗi chuyển sang drive.google.com/thumbnail
         * 3. Nếu vẫn bị chặn quyền chia sẻ thì dùng ảnh placeholder đồng bộ màu thương hiệu
         */
        function handleDriveImageError(imgEl, labelText) {
            try {
                const step = imgEl.getAttribute('data-error-step') || '0';
                const fallbackUrl = imgEl.getAttribute('data-fallback');
                if (step === '0' && fallbackUrl) {
                    imgEl.setAttribute('data-error-step', '1');
                    imgEl.src = fallbackUrl;
                } else {
                    imgEl.onerror = null;
                    const encoded = encodeURIComponent(labelText || 'Xay Dung Le Nguyen');
                    imgEl.src = `https://placehold.co/800x600/0F2A4A/DDA842?text=${encoded}`;
                }
            } catch (err) {
                console.error('Image fallback error:', err);
            }
        }

        function getDriveImgPrimary(fileId) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
        }

        function getDriveImgFallback(fileId) {
            return `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
        }

        /* ===================================================================
           DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
           =================================================================== */
        const REAL_CONSTRUCTION_PROJECTS = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Xây Dựng Nhà Phố Hiện Đại Trọn Gói',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'TP Đà Nẵng',
                description: 'Công trình nhà phố hiện đại được Công ty TNHH Xây Dựng - Tư Vấn - Thiết Kế Lê Nguyên đảm nhận trọn gói từ thiết kế kiến trúc, thi công phần thô đến hoàn thiện mặt tiền sắc nét.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Kết Cấu Phần Thô Nhà Phố 3 Tầng',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'Khu vực Đà Nẵng',
                description: 'Hạng mục thi công phần thô móng, cột, dầm sàn bê tông cốt thép chuẩn mác thiết kế, kiểm soát chặt chẽ độ phẳng và kỹ thuật bảo dưỡng bê tông.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thiết Kế & Thi Công Biệt Thự Sân Vườn Hiện Đại',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Quế Sơn Trung, Đà Nẵng',
                description: 'Biệt thự sân vườn không gian mở, kết hợp hài hòa giữa kiến trúc vững chãi và cảnh quan xanh mát, tối ưu ánh sáng tự nhiên cho mọi phòng chức năng.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Sang Trọng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'TP Đà Nẵng',
                description: 'Hoàn thiện ốp lát đá tự nhiên, hệ cửa nhôm kính cao cấp và chống thấm tường ngoài chuyên sâu giúp công trình bền đẹp trước thời tiết miền Trung.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Sàn Dầm Bê Tông Cốt Thép Chuẩn Kỹ Thuật',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'TP Đà Nẵng',
                description: 'Lắp đặt cốp pha, đan thép sàn đúng khoảng cách bản vẽ kết cấu và kiểm tra nghiệm thu nghiêm ngặt trước khi đổ bê tông tươi.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thiết Kế & Thi Công Khách Sạn – Căn Hộ Cho Thuê',
                category: 'khach-san',
                categoryLabel: 'Khách sạn – Căn hộ',
                location: 'TP Đà Nẵng',
                description: 'Giải pháp thiết kế tối ưu số lượng phòng khai thác kinh doanh, đảm bảo đầy đủ tiêu chuẩn kỹ thuật, thông gió và hệ thống điện nước đồng bộ.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Hoàn Thiện Nội Thất Không Gian Sống',
                category: 'noi-that',
                categoryLabel: 'Hoàn thiện & Nội thất',
                location: 'TP Đà Nẵng',
                description: 'Thi công hoàn thiện nội thất phòng khách, bếp và phòng ngủ đồng bộ vật liệu cao cấp, đường nét sắc sảo đúng bản vẽ 3D đã thống nhất.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Xây Dựng Biệt Thự Phố 2 Mặt Tiền',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'TP Đà Nẵng',
                description: 'Công trình biệt thự góc 2 mặt tiền bề thế, xử lý hình khối kiến trúc cân đối, đảm bảo tính riêng tư và giá trị thẩm mỹ lâu dài.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Trọn Gói Nhà Ở Dân Dụng & Hoàn Thiện',
                category: 'noi-that',
                categoryLabel: 'Hoàn thiện & Nội thất',
                location: 'Quế Sơn Trung, Đà Nẵng',
                description: 'Bàn giao chìa khóa trao tay đúng tiến độ, kiểm tra toàn diện hệ thống chống thấm, cấp thoát nước, chiếu sáng và sơn hoàn thiện.'
            }
        ];

        /* ===================================================================
           DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE
           =================================================================== */
        const DA_NANG_PROJECTS = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại Khu Đô Thị Hòa Xuân – Đà Nẵng',
                area: 'Cẩm Lệ, TP Đà Nẵng',
                description: 'Thi công trọn gói nhà phố hiện đại 3 tầng tại Khu đô thị sinh thái Hòa Xuân với công năng thông thoáng và vật tư hoàn thiện cao cấp.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Hiện Đại Khu Đô Thị FPT City – Đà Nẵng',
                area: 'Ngũ Hành Sơn, TP Đà Nẵng',
                description: 'Thiết kế kiến trúc và thi công hoàn thiện biệt thự nghỉ dưỡng hiện đại, chú trọng giếng trời và mảng xanh thư giãn.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Căn Hộ Dịch Vụ Cho Thuê Quận Sơn Trà – Đà Nẵng',
                area: 'Sơn Trà, TP Đà Nẵng',
                description: 'Công trình căn hộ dịch vụ ven biển tối ưu công năng khai thác, kết cấu vững chắc và hệ thống kỹ thuật vận hành ổn định.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố 3 Tầng Trung Tâm Hải Châu – Đà Nẵng',
                area: 'Hải Châu, TP Đà Nẵng',
                description: 'Thiết kế và thi công nhà phố kết hợp ở và kinh doanh tại trung tâm thành phố Đà Nẵng, thi công an toàn và sạch sẽ.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Biệt Thự Phố Sang Trọng Ngũ Hành Sơn – Đà Nẵng',
                area: 'Ngũ Hành Sơn, TP Đà Nẵng',
                description: 'Biệt thự phố phong cách hiện đại tinh giản, vật liệu mặt tiền chống chịu tốt với khí hậu gió biển miền Trung.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Tòa Nhà Văn Phòng & Nhà Ở Thanh Khê – Đà Nẵng',
                area: 'Thanh Khê, TP Đà Nẵng',
                description: 'Thi công trọn gói tòa nhà văn phòng kết hợp không gian sinh hoạt gia đình với mặt kính đón sáng hiện đại.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà Phố Gia Đình Khu Nam Việt Á – Đà Nẵng',
                area: 'Ngũ Hành Sơn, TP Đà Nẵng',
                description: 'Công trình nhà phố 3 tầng hiện đại bàn giao đúng tiến độ, chi phí xây dựng tối ưu và không phát sinh ngoài hợp đồng.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Khách Sạn Mini Gần Biển Mỹ Khê – Đà Nẵng',
                area: 'Sơn Trà, TP Đà Nẵng',
                description: 'Tư vấn thiết kế và thi công trọn gói khách sạn mini phục vụ du lịch, đảm bảo tiêu chuẩn thẩm mỹ và độ bền cao.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Biệt Thự Vườn Mái Nhật Liên Chiểu – Đà Nẵng',
                area: 'Liên Chiểu, TP Đà Nẵng',
                description: 'Thiết kế và thi công biệt thự vườn mái Nhật thanh lịch, tối ưu sân vườn và không gian sinh hoạt chung ấm cúng.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Nhà Ở Trọn Gói Quế Sơn Trung – TP Đà Nẵng',
                area: 'Quế Sơn Trung, TP Đà Nẵng',
                description: 'Công trình nhà ở gia đình tại địa bàn Quế Sơn Trung được Xây Dựng Lê Nguyên trực tiếp thi công và giám sát toàn diện.'
            }
        ];

        /* ===================================================================
           DỮ LIỆU 4 BÀI VIẾT TIN TỨC & KINH NGHIỆM XÂY DỰNG
           =================================================================== */
        const NEWS_ARTICLES = [
            {
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Khi Xây Nhà',
                date: '15/11/2026',
                imageId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                excerpt: 'Bê tông móng quyết định độ bền vững của toàn bộ ngôi nhà. Tìm hiểu quy trình tưới ẩm và che phủ chuẩn kỹ thuật.',
                content: 'Trong 7 ngày đầu sau khi đổ bê tông móng, việc giữ ẩm liên tục là yếu tố then chốt giúp bê tông đạt đủ cường độ thiết kế và hạn chế tối đa tình trạng nứt chân chim do co ngót nhiệt. Đội ngũ kỹ sư Xây Dựng Lê Nguyên luôn thực hiện che phủ bạt/bao tải ướt và phun sương giữ ẩm định kỳ theo đúng tiêu chuẩn TCVN.'
            },
            {
                title: '03 Nỗi Lo Lớn Nhất Khi Xây Nhà Trọn Gói Và Cách Phòng Tránh',
                date: '10/11/2026',
                imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: 'Phát sinh chi phí, chậm tiến độ và sai lệch vật tư là 3 vấn đề chủ nhà thường lo ngại nhất trước khi khởi công.',
                content: 'Để yên tâm khi xây dựng tổ ấm, gia chủ cần chuẩn bị hồ sơ thiết kế chi tiết trước khi thi công, ký hợp đồng với bảng vật tư quy định rõ thương hiệu, quy cách và tiến độ thanh toán theo từng giai đoạn nghiệm thu thực tế. Đây cũng chính là quy trình chuẩn mà Xây Dựng Lê Nguyên áp dụng cho 100% công trình.'
            },
            {
                title: 'Kinh Nghiệm Chọn Vật Liệu Chống Thấm Bền Đẹp Cho Khí Hậu Đà Nẵng',
                date: '04/11/2026',
                imageId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                excerpt: 'Miền Trung có mùa mưa bão kéo dài và nắng nóng gay gắt, vì vậy giải pháp chống thấm sân thượng và tường ngoài rất quan trọng.',
                content: 'Khu vực Đà Nẵng chịu tác động mạnh của mưa tạt và độ ẩm cao. Khi thi công, cần xử lý kỹ cổ ống xuyên sàn, chân tường sân thượng, ban công và sử dụng lớp sơn lót kháng kiềm kết hợp sơn chống thấm chuyên dụng để bảo vệ kết cấu công trình bền vững nhiều năm.'
            },
            {
                title: 'Quy Trình Tư Vấn Thiết Kế & Xin Giấy Phép Xây Dựng Nhà Ở Tại Đà Nẵng',
                date: '28/10/2026',
                imageId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                excerpt: 'Những hồ sơ pháp lý cần chuẩn bị để quá trình cấp phép xây dựng nhà phố, biệt thự diễn ra nhanh chóng, đúng quy định.',
                content: 'Hồ sơ xin giấy phép xây dựng gồm giấy chứng nhận quyền sử dụng đất, bản vẽ thiết kế xin phép theo đúng chỉ giới xây dựng và mật độ quy hoạch của từng tuyến đường. Khi lựa chọn gói xây nhà trọn gói tại Xây Dựng Lê Nguyên, chúng tôi hỗ trợ trọn vẹn thủ tục tư vấn và hoàn thiện hồ sơ xin phép.'
            }
        ];

        /* ===================================================================
           RENDER CÔNG TRÌNH THỰC TẾ (2 CỘT MOBILE, ĐẦY ĐỦ TÊN, KHÔNG NHÃN DÁN)
           =================================================================== */
        function renderRealProjects(filterKey) {
            const grid = document.getElementById('realProjectsGrid');
            if (!grid) return;

            const filtered = filterKey === 'all'
                ? REAL_CONSTRUCTION_PROJECTS
                : REAL_CONSTRUCTION_PROJECTS.filter(item => item.category === filterKey);

            grid.innerHTML = filtered.map((item, idx) => `
                <article
                    onclick="openProjectModal('real', '${item.id}')"
                    class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col"
                >
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgPrimary(item.id)}"
                            data-fallback="${getDriveImgFallback(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Cong Trinh Le Nguyen ${idx + 1}')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-1.5">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-navy-900 group-hover:text-gold-600 transition-colors leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 leading-snug">
                            ${item.categoryLabel} • ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(filterKey) {
            renderRealProjects(filterKey);
            const tabs = document.querySelectorAll('#projectCategoryTabs .cat-tab');
            tabs.forEach(tab => {
                const isActive = tab.getAttribute('data-filter') === filterKey;
                if (isActive) {
                    tab.className = 'cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-navy-900 text-white transition-colors whitespace-nowrap';
                } else {
                    tab.className = 'cat-tab px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-navy-900 border border-slate-200 hover:border-gold-500 transition-colors whitespace-nowrap';
                }
            });
        }

        /* ===================================================================
           RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (2 CỘT MOBILE, 5 CỘT DESKTOP)
           =================================================================== */
        function renderDaNangProjects() {
            const grid = document.getElementById('daNangProjectsGrid');
            if (!grid) return;

            grid.innerHTML = DA_NANG_PROJECTS.map((item, idx) => `
                <article
                    onclick="openProjectModal('danang', '${item.id}')"
                    class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col"
                >
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgPrimary(item.id)}"
                            data-fallback="${getDriveImgFallback(item.id)}"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Du An Da Nang ${idx + 1}')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-1">
                        <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-navy-900 group-hover:text-gold-600 transition-colors leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 leading-snug">
                            ${item.area}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* ===================================================================
           RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
           =================================================================== */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            if (!grid) return;

            grid.innerHTML = NEWS_ARTICLES.map((art, idx) => `
                <article
                    onclick="openArticleModal(${idx})"
                    class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col"
                >
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgPrimary(art.imageId)}"
                            data-fallback="${getDriveImgFallback(art.imageId)}"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            onerror="handleDriveImageError(this, 'Tin Tuc Xay Dung')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div class="space-y-1.5">
                            <div class="text-[11px] text-gold-600 font-semibold">${art.date}</div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-navy-900 group-hover:text-gold-600 transition-colors leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="text-[11px] sm:text-xs font-semibold text-navy-900 group-hover:text-gold-600 inline-flex items-center gap-1">
                            Đọc chi tiết →
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /* ===================================================================
           MODAL XEM CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
           =================================================================== */
        function openProjectModal(source, id) {
            const list = source === 'real' ? REAL_CONSTRUCTION_PROJECTS : DA_NANG_PROJECTS;
            const item = list.find(p => p.id === id);
            if (!item) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalMeta').textContent = source === 'real'
                ? `Hạng mục: ${item.categoryLabel} | Địa điểm: ${item.location}`
                : `Dự án Đà Nẵng | Khu vực: ${item.area}`;
            document.getElementById('modalBody').innerHTML = `
                <p>${item.description}</p>
                <p>Đơn vị thực hiện: <strong>CÔNG TY TNHH XÂY DỰNG - TƯ VẤN - THIẾT KẾ LÊ NGUYÊN</strong> (Hotline: 0914.725.383).</p>
            `;

            img.removeAttribute('data-error-step');
            img.setAttribute('data-fallback', getDriveImgFallback(item.id));
            img.onerror = function() { handleDriveImageError(this, item.title); };
            img.src = getDriveImgPrimary(item.id);
            img.alt = item.title;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function openArticleModal(index) {
            const art = NEWS_ARTICLES[index];
            if (!art) return;

            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = art.title;
            document.getElementById('modalMeta').textContent = `Ngày đăng: ${art.date} | Kiến thức xây dựng Lê Nguyên`;
            document.getElementById('modalBody').innerHTML = `
                <p class="font-medium text-navy-900">${art.excerpt}</p>
                <p>${art.content}</p>
            `;

            img.removeAttribute('data-error-step');
            img.setAttribute('data-fallback', getDriveImgFallback(art.imageId));
            img.onerror = function() { handleDriveImageError(this, art.title); };
            img.src = getDriveImgPrimary(art.imageId);
            img.alt = art.title;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        /* ===================================================================
           SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI
           =================================================================== */
        let currentSlide = 0;
        let sliderTimer = null;
        const totalSlides = 2;

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            const slides = document.querySelectorAll('#heroSlider .banner-slide');
            const dots = document.querySelectorAll('#heroSlider .slider-dot');

            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
                }
            });

            dots.forEach((dot, i) => {
                if (i === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/50');
                    dot.classList.add('w-7', 'bg-gold-500');
                } else {
                    dot.classList.remove('w-7', 'bg-gold-500');
                    dot.classList.add('w-2.5', 'bg-white/50');
                }
            });

            restartSliderAutoplay();
        }

        function restartSliderAutoplay() {
            if (sliderTimer) clearInterval(sliderTimer);
            sliderTimer = setInterval(() => {
                goToSlide(currentSlide + 1);
            }, 5500);
        }

        /* ===================================================================
           KHỞI TẠO SỰ KIỆN KHI TẢI TRANG
           =================================================================== */
        document.addEventListener('DOMContentLoaded', function() {
            // Render danh mục sản phẩm/công trình, dự án Đà Nẵng & bài viết
            renderRealProjects('all');
            renderDaNangProjects();
            renderArticles();

            // Khởi chạy slider tự trượt
            restartSliderAutoplay();

            const prevBtn = document.getElementById('prevSlideBtn');
            const nextBtn = document.getElementById('nextSlideBtn');
            if (prevBtn) prevBtn.addEventListener('click', () => goToSlide(currentSlide - 1));
            if (nextBtn) nextBtn.addEventListener('click', () => goToSlide(currentSlide + 1));

            // Hỗ trợ vuốt ngang banner trên điện thoại
            const heroSlider = document.getElementById('heroSlider');
            let touchStartX = 0;
            if (heroSlider) {
                heroSlider.addEventListener('touchstart', (e) => {
                    touchStartX = e.changedTouches[0].screenX;
                }, { passive: true });
                heroSlider.addEventListener('touchend', (e) => {
                    const diffX = e.changedTouches[0].screenX - touchStartX;
                    if (Math.abs(diffX) > 45) {
                        if (diffX < 0) goToSlide(currentSlide + 1);
                        else goToSlide(currentSlide - 1);
                    }
                }, { passive: true });
            }

            // Menu điện thoại (Drawer)
            const mobileBtn = document.getElementById('mobileMenuBtn');
            const closeBtn = document.getElementById('closeMobileMenuBtn');
            const drawer = document.getElementById('mobileMenuDrawer');
            const backdrop = document.getElementById('mobileMenuBackdrop');

            function openMobileMenu() {
                backdrop.classList.remove('hidden');
                setTimeout(() => backdrop.classList.remove('opacity-0'), 10);
                drawer.classList.remove('translate-x-full');
                document.body.style.overflow = 'hidden';
            }

            function closeMobileMenu() {
                backdrop.classList.add('opacity-0');
                drawer.classList.add('translate-x-full');
                setTimeout(() => backdrop.classList.add('hidden'), 280);
                document.body.style.overflow = '';
            }

            if (mobileBtn) mobileBtn.addEventListener('click', openMobileMenu);
            if (closeBtn) closeBtn.addEventListener('click', closeMobileMenu);
            if (backdrop) backdrop.addEventListener('click', closeMobileMenu);
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', closeMobileMenu);
            });

            // Đóng modal khi bấm ra ngoài hoặc nhấn ESC
            const modal = document.getElementById('detailModal');
            if (modal) {
                modal.addEventListener('click', (e) => {
                    if (e.target === modal) closeDetailModal();
                });
            }
            document.addEventListener('keydown', (e) => {
                if (e.key === 'Escape') closeDetailModal();
            });

            // Xử lý gửi form yêu cầu tư vấn & báo giá
            const quoteForm = document.getElementById('quoteForm');
            const feedback = document.getElementById('quoteFeedback');
            if (quoteForm && feedback) {
                quoteForm.addEventListener('submit', function(e) {
                    e.preventDefault();
                    const name = document.getElementById('customerName').value.trim();
                    const phone = document.getElementById('customerPhone').value.trim();
                    const type = document.getElementById('projectType').value;

                    if (!name || !phone) {
                        feedback.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để được tư vấn.';
                        feedback.className = 'p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                        return;
                    }

                    feedback.innerHTML = `Cảm ơn anh/chị <strong>${name}</strong> đã gửi yêu cầu báo giá hạng mục <strong>${type}</strong>. Kỹ sư Xây Dựng Lê Nguyên sẽ liên hệ số <strong>${phone}</strong> trong thời gian sớm nhất!`;
                    feedback.className = 'p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                    quoteForm.reset();
                });
            }
        });
    </script>
</body>
</html>
