<!-- Website Chính Thức: CÔNG TY CỔ PHẦN RỒNG BẠC (rongbac.com) - Giao diện chuẩn Flatsome UX Builder -->
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY CỔ PHẦN RỒNG BẠC - Tổng Kho Gạch Men & Thiết Bị Vệ Sinh Đà Nẵng | rongbac.com</title>
    <meta name="description" content="CÔNG TY CỔ PHẦN RỒNG BẠC (rongbac.com) - Tổng kho phân phối Gạch lát nền, Gạch ốp tường, Gạch khổ lớn, Gạch trang trí và Thiết bị vệ sinh cao cấp tại 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng. Hotline: 0905883738 - 02363731868.">
    <meta name="keywords" content="Công ty cổ phần Rồng Bạc, rongbac.com, gạch men Đà Nẵng, gạch lát nền Đà Nẵng, gạch ốp tường, gạch khổ lớn, thiết bị vệ sinh Đà Nẵng, 230 Bắc Sơn Đà Nẵng">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://rongbac.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY CỔ PHẦN RỒNG BẠC - rongbac.com">
    <meta property="og:url" content="https://rongbac.com/">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN RỒNG BẠC - Tổng Kho Gạch Ốp Lát & Thiết Bị Vệ Sinh Đà Nẵng">
    <meta property="og:description" content="Chuyên phân phối sỉ & lẻ Gạch lát nền 60x60, 80x80, Gạch ốp tường 60x120, Gạch khổ lớn 1200x2400, Gạch trang trí & Thiết bị vệ sinh tại 230 Bắc Sơn, P. An Khê, TP Đà Nẵng. ĐT: 0905883738 - 02363731868.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w1200">
    <meta property="og:image:alt" content="Logo Công Ty Cổ Phần Rồng Bạc - rongbac.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN RỒNG BẠC | rongbac.com">
    <meta name="twitter:description" content="Tổng kho Gạch men & Thiết bị vệ sinh Đà Nẵng - 230 Bắc Sơn, P. An Khê, TP Đà Nẵng. Hotline: 0905883738 - 02363731868.">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w1200">

    <!-- Favicon SVG đồng bộ màu Logo Rồng Bạc -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Cdefs%3E%3ClinearGradient id='g' x1='0%25' y1='0%25' x2='100%25' y2='100%25'%3E%3Cstop offset='0%25' stop-color='%230f2b48'/%3E%3Cstop offset='100%25' stop-color='%231e4976'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='100' height='100' rx='18' fill='url(%23g)'/%3E%3Cpath d='M25 72 L50 22 L75 72 L62 72 L50 46 L38 72 Z' fill='%23e2e8f0'/%3E%3Ccircle cx='50' cy='62' r='8' fill='%23c81e1e'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

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
                        rb: {
                            dark: '#0c233c',     /* Xanh Navy đậm theo màu Logo Rồng Bạc */
                            primary: '#14365d',  /* Xanh chủ đạo thương hiệu */
                            accent: '#1e4e8c',   /* Xanh sáng điểm nhấn */
                            silver: '#cbd5e1',   /* Bạc kim loại Rồng Bạc */
                            light: '#f1f5f9',    /* Nền xám bạc nhạt */
                            sale: '#d92626',     /* Đỏ giảm giá chuẩn Flatsome */
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS chuẩn cấu trúc Flatsome UX Builder & Chống tràn viền tuyệt đối -->
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn 95% chiều ngang màn hình máy tính, căn giữa tuyệt đối, không lệch phải */
        .flatsome-container {
            width: 96%;
            max-width: 96%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                margin-left: auto;
                margin-right: auto;
            }
        }

        /* Quy tắc tên danh mục: viết liền trên 1 hàng, không bao giờ xuống dòng giữa chừng */
        .cat-nowrap {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Thanh tiêu đề Section chuẩn Flatsome (Section Title Normal/Center) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 16px;
            padding-bottom: 8px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .flatsome-section-title h2 {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0c233c;
            margin: 0;
            padding-bottom: 8px;
            margin-bottom: -10px;
            border-bottom: 3px solid #14365d;
        }

        /* Thẻ sản phẩm Flatsome (box-product) */
        .flatsome-product-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            transition: all 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
        }
        .flatsome-product-box:hover {
            box-shadow: 0 10px 25px -5px rgba(12, 35, 60, 0.14);
            border-color: #94a3b8;
            transform: translateY(-2px);
        }

        /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d92626;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 5px 8px;
            border-radius: 4px;
            box-shadow: 0 2px 6px rgba(217, 38, 38, 0.35);
            pointer-events: none;
        }
        @media (min-width: 768px) {
            .flatsome-badge-sale {
                font-size: 12px;
                padding: 6px 9px;
            }
        }

        /* Tên sản phẩm: hiển thị đầy đủ 100%, không bị cắt chữ hay tràn ra ngoài */
        .flatsome-product-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 600;
            color: #1e293b;
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .flatsome-product-title {
                font-size: 14px;
                line-height: 1.45;
            }
        }

        /* Dropdown menu trên máy tính chuẩn Flatsome */
        .nav-item-has-dropdown {
            position: relative;
        }
        .nav-dropdown-panel {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 210px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            box-shadow: 0 12px 28px rgba(12, 35, 60, 0.15);
            border-radius: 0 0 8px 8px;
            z-index: 100;
            padding: 6px 0;
        }
        .nav-item-has-dropdown:hover .nav-dropdown-panel {
            display: block;
        }

        /* Hiệu ứng rung nhẹ cho nút nổi Hotline/Zalo */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(20, 54, 93, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(20, 54, 93, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(20, 54, 93, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }

        /* Ẩn thanh cuộn ngang phụ nếu có */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-rb-primary selection:text-white">

    <!-- ==================== HEADER FLATSOME ==================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        
        <!-- 1. TOP BAR (Thông tin công ty, Địa chỉ, SĐT chuẩn Flatsome) -->
        <div class="bg-rb-dark text-slate-200 text-[11px] sm:text-xs py-1.5 border-b border-slate-700/80">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 font-medium truncate">
                    <span class="inline-block w-2 h-2 rounded-full bg-emerald-400 shrink-0"></span>
                    <span class="truncate"><strong>CÔNG TY CỔ PHẦN RỒNG BẠC</strong> — Tổng Kho Gạch Ốp Lát &amp; Thiết Bị Vệ Sinh Đà Nẵng</span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-slate-300 shrink-0">
                    <span class="flex items-center gap-1">
                        <svg class="w-3.5 h-3.5 text-sky-400 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                        230 Bắc Sơn, Phường An Khê, TP Đà Nẵng
                    </span>
                    <span>|</span>
                    <span class="flex items-center gap-1 font-semibold text-white">
                        <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                        0905883738 - 02363731868
                    </span>
                    <span>|</span>
                    <span class="text-sky-300 font-semibold">rongbac.com</span>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo nhỏ gọn chuyên nghiệp + Thanh tìm kiếm + Báo giá, KHÔNG để nút gọi ngay tránh tràn viền) -->
        <div class="py-2.5 bg-white border-b border-slate-200">
            <div class="flatsome-container flex items-center justify-between gap-2 sm:gap-4">
                
                <!-- Nút mở Menu Danh mục trên Điện thoại -->
                <button type="button" onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md border border-slate-200 text-rb-dark hover:bg-slate-100 shrink-0">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                    </svg>
                </button>

                <!-- LOGO CÔNG TY CỔ PHẦN RỒNG BẠC (Thiết kế gọn nhỏ lại, sang trọng, chuẩn nhận diện) -->
                <a href="#top" class="flex items-center gap-2 sm:gap-2.5 shrink-0 group focus:outline-none">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-gradient-to-br from-rb-dark via-rb-primary to-rb-accent p-0.5 shadow-sm shrink-0 flex items-center justify-center">
                        <!-- Biểu tượng Rồng Bạc Vector (Silver Dragon Crest) -->
                        <svg class="w-8 h-8 sm:w-9 sm:h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="silverGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#ffffff"/>
                                    <stop offset="50%" stop-color="#cbd5e1"/>
                                    <stop offset="100%" stop-color="#94a3b8"/>
                                </linearGradient>
                            </defs>
                            <!-- Khung lục giác gạch đá kim cương -->
                            <polygon points="32,4 56,18 56,46 32,60 8,46 8,18" stroke="url(#silverGrad)" stroke-width="2.5" fill="#0c233c"/>
                            <!-- Hình tượng Rồng Bạc uốn lượn chữ S & RB -->
                            <path d="M20 44 C18 34, 24 24, 34 20 C40 17, 46 20, 46 25 C46 30, 38 32, 30 34 C24 36, 22 42, 28 46 C34 49, 43 46, 46 40" stroke="url(#silverGrad)" stroke-width="4" stroke-linecap="round" fill="none"/>
                            <path d="M32 13 L37 20 L27 20 Z" fill="#e2e8f0"/>
                            <circle cx="32" cy="32" r="3.5" fill="#d92626"/>
                        </svg>
                    </div>
                    <div class="flex flex-col leading-tight">
                        <span class="text-xs sm:text-sm md:text-[15px] font-extrabold tracking-tight text-rb-dark group-hover:text-rb-accent transition">
                            CÔNG TY CP RỒNG BẠC
                        </span>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-500 tracking-wide">
                            RONGBAC.COM • GẠCH MEN &amp; TBVS
                        </span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm ở giữa (Giống gachmendanang.vn) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-2">
                    <div class="relative flex w-full">
                        <input id="desktopSearchInput" type="text" oninput="handleSearchProduct(this.value)" placeholder="Tìm gạch lát nền 60x60, 80x80, gạch 60x120, bồn cầu, lavabo..." class="w-full pl-3.5 pr-24 py-2 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-l-md focus:outline-none focus:border-rb-primary focus:bg-white text-slate-800">
                        <button type="button" onclick="handleSearchProduct(document.getElementById('desktopSearchInput').value)" class="px-4 py-2 bg-rb-primary hover:bg-rb-dark text-white text-xs font-semibold rounded-r-md transition shrink-0">
                            Tìm kiếm
                        </button>
                    </div>
                </div>

                <!-- Khu vực tiện ích bên phải (Không đặt nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
                    <a href="#form-bao-gia" class="px-2.5 py-1.5 sm:px-3 sm:py-2 rounded-md bg-slate-100 hover:bg-rb-primary hover:text-white text-rb-dark text-[11px] sm:text-xs font-semibold transition flex items-center gap-1.5 border border-slate-200">
                        <svg class="w-3.5 h-3.5 text-rb-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
                        <span class="cat-nowrap">Nhận Báo Giá</span>
                    </a>
                    <a href="#ban-do-trang-chu" class="hidden sm:inline-flex px-2.5 py-1.5 sm:px-3 sm:py-2 rounded-md bg-slate-100 hover:bg-rb-primary hover:text-white text-rb-dark text-[11px] sm:text-xs font-semibold transition items-center gap-1 border border-slate-200">
                        <svg class="w-3.5 h-3.5 text-rb-sale shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/></svg>
                        <span class="cat-nowrap">Chỉ Đường</span>
                    </a>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="flatsome-container mt-2 md:hidden">
                <div class="flex w-full">
                    <input id="mobileSearchInput" type="text" oninput="handleSearchProduct(this.value)" placeholder="Tìm mã gạch, kích thước 60x60, 80x80, 60x120, TBVS..." class="w-full px-3 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-l-md focus:outline-none focus:border-rb-primary">
                    <button type="button" onclick="handleSearchProduct(document.getElementById('mobileSearchInput').value)" class="px-3 py-1.5 bg-rb-primary text-white text-xs font-semibold rounded-r-md shrink-0">
                        Tìm
                    </button>
                </div>
            </div>
        </div>

        <!-- 3. HEADER NAVIGATION DANH MỤC TRÊN MÁY TÍNH & ĐIỆN THOẠI -->
        <!-- Tên danh mục viết liền trên 1 hàng chữ nhỏ gọn, nằm trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy dòng tên danh mục -->
        <nav class="bg-rb-primary text-white border-b border-rb-dark">
            <div class="flatsome-container">
                <!-- Danh mục chính trên Máy tính (1 hàng chữ nhỏ gọn + Hàng 2 mã kích thước viết liền) -->
                <ul class="hidden lg:flex flex-wrap items-center justify-start gap-x-1 gap-y-1 py-1.5 text-[12px] font-bold tracking-wide">
                    <li>
                        <a href="#top" onclick="filterByCategory('all')" class="cat-nowrap px-2.5 py-1.5 rounded bg-rb-dark text-white hover:bg-white hover:text-rb-dark transition">
                            TRANG CHỦ
                        </a>
                    </li>
                    <li class="nav-item-has-dropdown">
                        <a href="#sec-gach-lat-nen" onclick="filterByCategory('gach-lat-nen')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition gap-1">
                            <span>GẠCH LÁT NỀN</span>
                            <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown-panel text-slate-800 text-xs font-semibold">
                            <a href="#sec-gach-lat-nen" onclick="filterBySubCat('60x60')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 60X60 (60 Sản phẩm)</a>
                            <a href="#sec-gach-lat-nen" onclick="filterBySubCat('80x80')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 80X80 (82 Sản phẩm)</a>
                            <a href="#sec-gach-lat-nen" onclick="filterBySubCat('100x100')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 100X100 (55 Sản phẩm)</a>
                            <a href="#sec-gach-lat-nen" onclick="filterBySubCat('120x120')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 120X120 (28 Sản phẩm)</a>
                        </div>
                    </li>
                    <li class="nav-item-has-dropdown">
                        <a href="#sec-gach-60x120" onclick="filterByCategory('gach-op-tuong')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition gap-1">
                            <span>GẠCH ỐP TƯỜNG</span>
                            <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown-panel text-slate-800 text-xs font-semibold">
                            <a href="#sec-gach-60x120" onclick="filterBySubCat('30x60')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 30X60</a>
                            <a href="#sec-gach-60x120" onclick="filterBySubCat('60x120')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 60X120 (171 Sản phẩm)</a>
                            <a href="#sec-gach-lat-nen" onclick="filterBySubCat('80x160')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 80X160 (66 Sản phẩm)</a>
                            <a href="#sec-gach-60x120" onclick="filterBySubCat('75x150')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 75X150</a>
                            <a href="#sec-gach-60x120" onclick="filterBySubCat('90x180')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 90X180</a>
                        </div>
                    </li>
                    <li class="nav-item-has-dropdown">
                        <a href="#sec-gach-kho-lon" onclick="filterByCategory('gach-kho-lon')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition gap-1">
                            <span>GẠCH KHỔ LỚN</span>
                            <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown-panel text-slate-800 text-xs font-semibold">
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1600x3200')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 1600X3200 (43 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x2400')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 1200X2400 (20 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x2800')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 1200X2800 (14 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x1800')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH 1200X1800 (14 Sản phẩm)</a>
                        </div>
                    </li>
                    <li class="nav-item-has-dropdown">
                        <a href="#sec-gach-kho-lon" onclick="filterByCategory('gach-trang-tri')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition gap-1">
                            <span>GẠCH TRANG TRÍ</span>
                            <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown-panel text-slate-800 text-xs font-semibold">
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('terrazzo')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH TERRAZZO (44 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('gia-go')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH GIẢ GỖ (48 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('mosaic')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH MOSAIC (126 Sản phẩm)</a>
                            <a href="#sec-gach-kho-lon" onclick="filterBySubCat('gach-bong')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">GẠCH BÔNG (7 Sản phẩm)</a>
                        </div>
                    </li>
                    <li class="nav-item-has-dropdown">
                        <a href="#sec-thiet-bi-ve-sinh" onclick="filterByCategory('thiet-bi-ve-sinh')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition gap-1">
                            <span>THIẾT BỊ VỆ SINH</span>
                            <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                        </a>
                        <div class="nav-dropdown-panel text-slate-800 text-xs font-semibold">
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('bon-cau')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">BỒN CẦU (23 Sản phẩm)</a>
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('tu-lavabo')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">TỦ LAVABO (52 Sản phẩm)</a>
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('lavabo')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">LAVABO (79 Sản phẩm)</a>
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('voi-sen')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">VÒI SEN TẮM (28 Sản phẩm)</a>
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('voi-lavabo')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">VÒI LAVABO (33 Sản phẩm)</a>
                            <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('bon-tam')" class="block px-3.5 py-2 hover:bg-slate-100 cat-nowrap">BỒN TẮM &amp; PHỤ KIỆN</a>
                        </div>
                    </li>
                    <li><a href="#sec-doi-tac" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition">ĐỐI TÁC</a></li>
                    <li><a href="#form-bao-gia" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition">BÁO GIÁ SỈ &amp; LẺ</a></li>
                    <li><a href="#sec-bai-viet" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition">TIN TỨC</a></li>
                    <li><a href="#ban-do-trang-chu" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-rb-dark transition">LIÊN HỆ</a></li>
                </ul>

                <!-- Thanh danh mục trên Điện thoại (Chữ nhỏ gọn, viết liền không xuống dòng) -->
                <div class="flex lg:hidden items-center gap-1.5 overflow-x-auto no-scrollbar py-2 text-[11px] font-bold">
                    <a href="#sec-danh-muc" class="cat-nowrap px-2.5 py-1 rounded bg-rb-dark text-white">DANH MỤC</a>
                    <a href="#sec-gach-lat-nen" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">GẠCH LÁT NỀN</a>
                    <a href="#sec-gach-60x120" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">GẠCH ỐP TƯỜNG</a>
                    <a href="#sec-gach-kho-lon" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">GẠCH KHỔ LỚN</a>
                    <a href="#sec-gach-kho-lon" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">GẠCH TRANG TRÍ</a>
                    <a href="#sec-thiet-bi-ve-sinh" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">THIẾT BỊ VỆ SINH</a>
                    <a href="#sec-doi-tac" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">ĐỐI TÁC</a>
                    <a href="#form-bao-gia" class="cat-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20">BÁO GIÁ</a>
                </div>
            </div>
        </nav>

        <!-- Thanh Sub-Categories (Hàng 2 trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không gãy dòng) -->
        <div class="hidden lg:block bg-slate-100 border-b border-slate-200 py-1.5">
            <div class="flatsome-container flex flex-wrap items-center gap-1.5 text-[11.5px] font-semibold text-slate-700">
                <span class="cat-nowrap text-rb-primary font-bold mr-1">KÍCH THƯỚC &amp; HẠNG MỤC NHANH:</span>
                <a href="#sec-gach-lat-nen" onclick="filterBySubCat('60x60')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 60X60</a>
                <a href="#sec-gach-lat-nen" onclick="filterBySubCat('80x80')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 80X80</a>
                <a href="#sec-gach-lat-nen" onclick="filterBySubCat('100x100')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 100X100</a>
                <a href="#sec-gach-60x120" onclick="filterBySubCat('60x120')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 60X120</a>
                <a href="#sec-gach-lat-nen" onclick="filterBySubCat('80x160')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 80X160</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x2400')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 1200X2400</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x2800')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 1200X2800</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('1600x3200')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH 1600X3200</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('terrazzo')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH TERRAZZO</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('gia-go')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH GIẢ GỖ</a>
                <a href="#sec-gach-kho-lon" onclick="filterBySubCat('mosaic')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">GẠCH MOSAIC</a>
                <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('bon-cau')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">BỒN CẦU</a>
                <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('tu-lavabo')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">TỦ LAVABO</a>
                <a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('voi-sen')" class="cat-nowrap px-2 py-0.5 bg-white border border-slate-200 rounded hover:border-rb-primary hover:text-rb-primary transition">VÒI SEN TẮM</a>
            </div>
        </div>
    </header>

    <!-- MENU DRAWER CHO ĐIỆN THOẠI -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div class="fixed inset-0 bg-black/60" onclick="toggleMobileDrawer()"></div>
        <div class="relative w-72 max-w-[85vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-rb-dark text-white flex items-center justify-between">
                <span class="font-bold text-xs tracking-wide uppercase">DANH MỤC RỒNG BẠC</span>
                <button type="button" onclick="toggleMobileDrawer()" class="p-1 text-slate-300 hover:text-white">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-3 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
                <a href="#sec-gach-lat-nen" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">1. GẠCH LÁT NỀN (60x60, 80x80, 100x100, 120x120)</a>
                <a href="#sec-gach-60x120" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">2. GẠCH ỐP TƯỜNG (30x60, 60x120, 80x160, 75x150)</a>
                <a href="#sec-gach-kho-lon" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">3. GẠCH KHỔ LỚN (1200x2400, 1200x2800, 1600x3200)</a>
                <a href="#sec-gach-kho-lon" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">4. GẠCH TRANG TRÍ (Terrazzo, Giả Gỗ, Mosaic, Bông)</a>
                <a href="#sec-thiet-bi-ve-sinh" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">5. THIẾT BỊ VỆ SINH (Bồn Cầu, Tủ Lavabo, Sen Tắm)</a>
                <a href="#sec-doi-tac" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">6. ĐỐI TÁC THƯƠNG HIỆU</a>
                <a href="#form-bao-gia" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">7. YÊU CẦU &amp; NHẬN BÁO GIÁ</a>
                <a href="#sec-bai-viet" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">8. TIN TỨC &amp; KINH NGHIỆM</a>
                <a href="#ban-do-trang-chu" onclick="toggleMobileDrawer()" class="block py-2.5 hover:text-rb-primary">9. BẢN ĐỒ &amp; FANPAGE</a>
            </div>
            <div class="mt-auto p-3.5 bg-slate-100 text-[11px] text-slate-600 space-y-1">
                <p class="font-bold text-rb-dark">CÔNG TY CỔ PHẦN RỒNG BẠC</p>
                <p>ĐC: 230 Bắc Sơn, P. An Khê, TP Đà Nẵng</p>
                <p>SĐT: 0905883738 - 02363731868</p>
                <p>Web: rongbac.com</p>
            </div>
        </div>
    </div>

    <!-- ==================== SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU ==================== -->
    <!-- Thiết kế bằng SVG viewBox chuẩn tỷ lệ đồng nhất 1400x480: Toàn bộ hình ảnh và chữ nằm gọn trong banner, chữ cách xa viền >= 110px, đảm bảo trên cả điện thoại và máy tính không bao giờ bị thiếu hay cắt chữ -->
    <section id="top" class="py-3">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md bg-rb-dark border border-slate-200" id="bannerSliderContainer">
                
                <!-- Khung trượt 2 slides kích thước bằng nhau 100% -->
                <div id="bannerTrack" class="flex transition-transform duration-700 ease-in-out w-full">
                    
                    <!-- SLIDE 1: TỔNG KHO GẠCH MEN & ĐÁ ỐP LÁT RỒNG BẠC -->
                    <div class="w-full shrink-0">
                        <svg class="w-full h-auto block" viewBox="0 0 1400 480" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="bgSlide1" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#091b30"/>
                                    <stop offset="55%" stop-color="#133357"/>
                                    <stop offset="100%" stop-color="#1d4b7d"/>
                                </linearGradient>
                                <linearGradient id="silverBar1" x1="0%" y1="0%" x2="100%" y2="0%">
                                    <stop offset="0%" stop-color="#f8fafc"/>
                                    <stop offset="50%" stop-color="#cbd5e1"/>
                                    <stop offset="100%" stop-color="#94a3b8"/>
                                </linearGradient>
                                <pattern id="gridPat1" width="60" height="60" patternUnits="userSpaceOnUse">
                                    <path d="M 60 0 L 0 0 0 60" fill="none" stroke="rgba(255,255,255,0.05)" stroke-width="1"/>
                                </pattern>
                            </defs>
                            <!-- Nền Banner 1 -->
                            <rect width="1400" height="480" fill="url(#bgSlide1)"/>
                            <rect width="1400" height="480" fill="url(#gridPat1)"/>
                            <!-- Khung viền an toàn bên trong cách mép ngoài -->
                            <rect x="45" y="32" width="1310" height="416" rx="16" fill="none" stroke="rgba(203,213,225,0.28)" stroke-width="2"/>

                            <!-- Phía bên phải (trong vùng an toàn x: 820 -> 1270): Phối cảnh Gạch Vân Đá Marble & Khổ Lớn -->
                            <g transform="translate(825, 65)">
                                <!-- Tấm gạch khổ lớn 1 -->
                                <rect x="0" y="10" width="210" height="330" rx="10" fill="#f8fafc" stroke="#cbd5e1" stroke-width="4"/>
                                <path d="M15 45 Q90 110 60 190 T180 310" stroke="#94a3b8" stroke-width="3" fill="none"/>
                                <path d="M80 25 Q140 120 120 230" stroke="#cbd5e1" stroke-width="2" fill="none"/>
                                <rect x="18" y="285" width="174" height="36" rx="6" fill="#0c233c"/>
                                <text x="105" y="309" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="15" font-weight="700">GẠCH KHỔ LỚN 60X120</text>

                                <!-- Tấm gạch vân đá vàng kim 2 -->
                                <rect x="225" y="35" width="210" height="305" rx="10" fill="#1e293b" stroke="#94a3b8" stroke-width="4"/>
                                <path d="M245 75 Q320 140 295 220 T415 290" stroke="#fbbf24" stroke-width="2.5" fill="none"/>
                                <path d="M310 55 Q370 150 360 250" stroke="#e2e8f0" stroke-width="1.5" fill="none"/>
                                <rect x="243" y="285" width="174" height="36" rx="6" fill="#d92626"/>
                                <text x="330" y="309" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="15" font-weight="700">ƯU ĐÃI ĐẾN -35%</text>
                            </g>

                            <!-- Phía bên trái (Chữ cách xa viền trái x=115, cách xa viền trên/dưới) -->
                            <g transform="translate(115, 82)">
                                <rect x="0" y="0" width="380" height="36" rx="18" fill="#1e4e8c" stroke="#94a3b8" stroke-width="1.5"/>
                                <text x="190" y="24" text-anchor="middle" fill="#f8fafc" font-family="Inter, sans-serif" font-size="15" font-weight="700" letter-spacing="1">WEBSITE CHÍNH THỨC: RONGBAC.COM</text>

                                <text x="0" y="92" fill="url(#silverBar1)" font-family="Inter, sans-serif" font-size="40" font-weight="800">CÔNG TY CỔ PHẦN RỒNG BẠC</text>
                                <text x="0" y="142" fill="#38bdf8" font-family="Inter, sans-serif" font-size="25" font-weight="700">TỔNG KHO GẠCH MEN &amp; THIẾT BỊ VỆ SINH ĐÀ NẴNG</text>

                                <text x="0" y="190" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Phân phối Gạch Lát Nền 60x60, 80x80, 100x100, Gạch Ốp Tường 60x120</text>
                                <text x="0" y="222" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Gạch Khổ Lớn 1200x2400, 1600x3200, Gạch Trang Trí Terrazzo, Mosaic</text>
                                <text x="0" y="254" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Chiết khấu cao cho Công Trình, Dự Án, Nhà Thầu &amp; Đại Lý Miền Trung</text>

                                <!-- Khung địa chỉ & SĐT cách xa viền dưới -->
                                <rect x="0" y="280" width="675" height="48" rx="8" fill="#09192c" stroke="#38bdf8" stroke-width="1.5"/>
                                <text x="18" y="310" fill="#fbbf24" font-family="Inter, sans-serif" font-size="16" font-weight="700">ĐC: 230 Bắc Sơn, P. An Khê, TP Đà Nẵng  |  ĐT: 0905883738 - 02363731868</text>
                            </g>
                        </svg>
                    </div>

                    <!-- SLIDE 2: THIẾT BỊ VỆ SINH & GẠCH ỐP LÁT CAO CẤP RỒNG BẠC (Kích thước bằng Slide 1: 1400x480) -->
                    <div class="w-full shrink-0">
                        <svg class="w-full h-auto block" viewBox="0 0 1400 480" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="bgSlide2" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#0f243c"/>
                                    <stop offset="50%" stop-color="#193b61"/>
                                    <stop offset="100%" stop-color="#0c233c"/>
                                </linearGradient>
                            </defs>
                            <!-- Nền Banner 2 -->
                            <rect width="1400" height="480" fill="url(#bgSlide2)"/>
                            <rect width="1400" height="480" fill="url(#gridPat1)"/>
                            <!-- Khung viền an toàn bên trong cách mép ngoài -->
                            <rect x="45" y="32" width="1310" height="416" rx="16" fill="none" stroke="rgba(203,213,225,0.28)" stroke-width="2"/>

                            <!-- Phía bên phải (trong vùng an toàn x: 825 -> 1270): Minh họa Thiết Bị Phòng Tắm & Gạch Trang Trí -->
                            <g transform="translate(825, 65)">
                                <rect x="0" y="15" width="435" height="325" rx="14" fill="#132f4c" stroke="#64748b" stroke-width="3"/>
                                <!-- Tủ Lavabo Gương LED Minh Họa -->
                                <circle cx="115" cy="125" r="55" fill="#e0f2fe" stroke="#38bdf8" stroke-width="4"/>
                                <rect x="65" y="195" width="100" height="55" rx="6" fill="#f8fafc" stroke="#94a3b8" stroke-width="2"/>
                                <!-- Bồn cầu nguyên khối thông minh Minh Họa -->
                                <rect x="255" y="85" width="110" height="75" rx="14" fill="#ffffff" stroke="#cbd5e1" stroke-width="3"/>
                                <path d="M245 160 L375 160 L355 250 L265 250 Z" fill="#f8fafc" stroke="#cbd5e1" stroke-width="3"/>
                                <rect x="35" y="278" width="365" height="40" rx="8" fill="#1e4e8c"/>
                                <text x="217" y="304" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="16" font-weight="700">COMBO THIẾT BỊ VỆ SINH &amp; GẠCH ỐP LÁT</text>
                            </g>

                            <!-- Phía bên trái (Chữ cách xa viền trái x=115, cách xa viền trên/dưới) -->
                            <g transform="translate(115, 82)">
                                <rect x="0" y="0" width="410" height="36" rx="18" fill="#d92626"/>
                                <text x="205" y="24" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="15" font-weight="700" letter-spacing="0.8">SIÊU THỊ VẬT LIỆU XÂY DỰNG RỒNG BẠC</text>

                                <text x="0" y="92" fill="#ffffff" font-family="Inter, sans-serif" font-size="38" font-weight="800">THIẾT BỊ VỆ SINH &amp; GẠCH CAO CẤP</text>
                                <text x="0" y="142" fill="#fbbf24" font-family="Inter, sans-serif" font-size="25" font-weight="700">BÁO GIÁ TẬN KHO - GIAO HÀNG NHANH TẠI ĐÀ NẴNG</text>

                                <text x="0" y="190" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Bồn Cầu Thông Minh, Bồn Cầu 1 Khối, Tủ Lavabo Gương LED Hiện Đại</text>
                                <text x="0" y="222" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Sen Tắm Âm Tường, Vòi Lavabo Nóng Lạnh, Bồn Tắm, Phụ Kiện Phòng Tắm</text>
                                <text x="0" y="254" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="18" font-weight="500">• Cam kết hàng chính hãng 100% - Bảo hành dài hạn - Hỗ trợ tư vấn 24/7</text>

                                <!-- Khung địa chỉ & SĐT cách xa viền dưới -->
                                <rect x="0" y="280" width="675" height="48" rx="8" fill="#09192c" stroke="#fbbf24" stroke-width="1.5"/>
                                <text x="18" y="310" fill="#38bdf8" font-family="Inter, sans-serif" font-size="16" font-weight="700">Showroom: 230 Bắc Sơn, P. An Khê, Đà Nẵng | Hotline: 0905883738 - 02363731868</text>
                            </g>
                        </svg>
                    </div>

                </div>

                <!-- Nút điều hướng Trái/Phải nằm gọn trong Banner -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Banner kế tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Chỉ báo chấm tròn 2 Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2">
                    <button type="button" id="dot0" onclick="goToSlide(0)" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-white transition-all"></button>
                    <button type="button" id="dot1" onclick="goToSlide(1)" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy từ web mẫu gachmendanang.vn) ==================== -->
    <!-- Thiết kế chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng, chia 2 cột trên điện thoại và 4-6 cột trên máy tính -->
    <section id="sec-danh-muc" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC SẢN PHẨM RỒNG BẠC</h2>
                <span class="text-xs text-slate-500 font-medium">Chọn nhanh kích thước &amp; dòng sản phẩm chính hãng</span>
            </div>

            <!-- Lưới danh mục: 2 cột trên điện thoại, 4 cột trên tablet, 6 cột trên máy tính -->
            <div id="homepageCategoryGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3.5">
                <!-- Được render tự động bằng JS từ 11 ảnh thực tế trong Google Drive -->
            </div>

            <!-- Hàng danh mục con chữ nhỏ gọn viết liền trên 1 hàng (hoặc xuống hàng 2 trên máy tính, không gãy tên danh mục) -->
            <div class="mt-4 bg-white p-3 rounded-lg border border-slate-200 shadow-sm">
                <div class="flex flex-wrap items-center gap-1.5 sm:gap-2">
                    <button type="button" onclick="filterByCategory('all')" id="btnCat-all" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-bold bg-rb-primary text-white transition">
                        TẤT CẢ SẢN PHẨM
                    </button>
                    <button type="button" onclick="filterBySubCat('60x60')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 60X60 (60)
                    </button>
                    <button type="button" onclick="filterBySubCat('80x80')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 80X80 (82)
                    </button>
                    <button type="button" onclick="filterBySubCat('100x100')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 100X100 (55)
                    </button>
                    <button type="button" onclick="filterBySubCat('120x120')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 120X120 (28)
                    </button>
                    <button type="button" onclick="filterBySubCat('60x120')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 60X120 (171)
                    </button>
                    <button type="button" onclick="filterBySubCat('80x160')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 80X160 (66)
                    </button>
                    <button type="button" onclick="filterBySubCat('1200x2400')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 1200X2400 (20)
                    </button>
                    <button type="button" onclick="filterBySubCat('1600x3200')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH 1600X3200 (43)
                    </button>
                    <button type="button" onclick="filterBySubCat('terrazzo')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH TERRAZZO (44)
                    </button>
                    <button type="button" onclick="filterBySubCat('gia-go')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH GIẢ GỖ (48)
                    </button>
                    <button type="button" onclick="filterBySubCat('mosaic')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        GẠCH MOSAIC (126)
                    </button>
                    <button type="button" onclick="filterBySubCat('bon-cau')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        BỒN CẦU (23)
                    </button>
                    <button type="button" onclick="filterBySubCat('tu-lavabo')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        TỦ LAVABO (52)
                    </button>
                    <button type="button" onclick="filterBySubCat('voi-sen')" class="cat-filter-btn cat-nowrap px-2.5 py-1.5 rounded text-[11px] sm:text-xs font-semibold bg-slate-100 hover:bg-rb-primary hover:text-white text-slate-700 transition">
                        VÒI SEN TẮM (28)
                    </button>
                </div>
            </div>

            <!-- Thông báo kết quả lọc nhanh khi tìm kiếm hoặc bấm bộ lọc -->
            <div id="filterStatusBanner" class="hidden mt-3 p-2.5 rounded-lg bg-sky-50 border border-sky-200 flex items-center justify-between text-xs text-rb-dark">
                <span id="filterStatusText" class="font-semibold">Đang lọc sản phẩm...</span>
                <button type="button" onclick="filterByCategory('all')" class="px-2.5 py-1 bg-rb-primary text-white rounded font-semibold hover:bg-rb-dark">Xem tất cả</button>
            </div>
        </div>
    </section>

    <!-- ==================== SECTION 1: GẠCH ỐP LÁT 60X120 MỚI NHẤT (Giống gachmendanang.vn) ==================== -->
    <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), có % giảm giá góc trên bên trái -->
    <section id="sec-gach-60x120" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">GẠCH ỐP LÁT 60X120 CAO CẤP</h2>
                <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 60X120 VÂN ĐÁ</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 30X60</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH ẤN ĐỘ</span>
                </div>
            </div>
            <div id="grid-60x120" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- ==================== SECTION 2: GẠCH LÁT NỀN 60X60 - 80X80 - 80X160 ==================== -->
    <section id="sec-gach-lat-nen" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">GẠCH LÁT NỀN 60X60 • 80X80 • 80X160</h2>
                <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 60X60</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 80X80</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 100X100</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 80X160</span>
                </div>
            </div>
            <div id="grid-lat-nen" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- ==================== SECTION 3: GẠCH KHỔ LỚN 1200X2400 & GẠCH TRANG TRÍ ==================== -->
    <section id="sec-gach-kho-lon" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">GẠCH KHỔ LỚN 1200X2400 &amp; GẠCH TRANG TRÍ</h2>
                <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 1200X2400</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH 1600X3200</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH TERRAZZO</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH MOSAIC</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">GẠCH GIẢ GỖ</span>
                </div>
            </div>
            <div id="grid-kho-lon" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- ==================== SECTION 4: THIẾT BỊ VỆ SINH ĐÀ NẴNG (Bồn cầu, Tủ Lavabo, Sen tắm) ==================== -->
    <section id="sec-thiet-bi-ve-sinh" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">THIẾT BỊ VỆ SINH CAO CẤP ĐÀ NẴNG</h2>
                <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">BỒN CẦU 1 KHỐI</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">BỒN CẦU THÔNG MINH</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">TỦ LAVABO LED</span>
                    <span class="cat-nowrap text-[11px] font-semibold text-slate-600 bg-slate-200/70 px-2 py-0.5 rounded">VÒI SEN TẮM</span>
                </div>
            </div>
            <div id="grid-tbvs" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU ==================== -->
    <section id="sec-doi-tac" class="py-6 bg-white border-y border-slate-200 mt-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">ĐỐI TÁC &amp; THƯƠNG HIỆU PHÂN PHỐI</h2>
                <span class="text-xs text-slate-500">Đối tác chiến lược cung ứng gạch ốp lát &amp; thiết bị vệ sinh chính hãng</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-dark tracking-wider">VIGLACERA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch &amp; Thiết Bị Vệ Sinh</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-primary tracking-wider">PRIME GROUP</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Ốp Lát Cao Cấp</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-dark tracking-wider">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Men &amp; Granite</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-accent tracking-wider">INAX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Phòng Tắm</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-dark tracking-wider">TOTO</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-primary tracking-wider">TAICERA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Thạch Anh</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-dark tracking-wider">EUROTILE</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Nghệ Thuật</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 hover:border-rb-primary transition flex flex-col items-center justify-center text-center">
                    <span class="text-sm font-extrabold text-rb-sale tracking-wider">CAESAR</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">TBVS Chính Hãng</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU BÁO GIÁ + FANPAGE + GOOGLE MAP NGOÀI TRANG CHỦ ==================== -->
    <section id="form-bao-gia" class="py-6">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">YÊU CẦU BÁO GIÁ • FANPAGE &amp; BẢN ĐỒ CHỈ ĐƯỜNG</h2>
                <span class="text-xs text-slate-500">Hỗ trợ tư vấn mẫu gạch &amp; chiết khấu công trình nhanh chóng</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
                
                <!-- CỘT 1 (5/12): FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-2.5 pb-3 mb-3 border-b border-slate-100">
                            <div class="w-9 h-9 rounded-lg bg-rb-primary text-white flex items-center justify-center shrink-0 font-bold text-sm">
                                BG
                            </div>
                            <div>
                                <h3 class="text-sm sm:text-base font-bold text-rb-dark">FORM ĐĂNG KÝ NHẬN BÁO GIÁ SỈ &amp; LẺ</h3>
                                <p class="text-xs text-slate-500">Nhận bảng giá chiết khấu tốt nhất từ Công Ty Cổ Phần Rồng Bạc</p>
                            </div>
                        </div>

                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs sm:text-sm">
                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Họ và tên quý khách <span class="text-rb-sale">*</span></label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-md border border-slate-300 focus:outline-none focus:border-rb-primary bg-slate-50 focus:bg-white">
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-rb-sale">*</span></label>
                                    <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905883738" class="w-full px-3 py-2 rounded-md border border-slate-300 focus:outline-none focus:border-rb-primary bg-slate-50 focus:bg-white">
                                </div>
                                <div>
                                    <label class="block font-semibold text-slate-700 mb-1">Danh mục quan tâm</label>
                                    <select id="qCat" class="w-full px-3 py-2 rounded-md border border-slate-300 focus:outline-none focus:border-rb-primary bg-slate-50 focus:bg-white">
                                        <option value="Gạch lát nền (60x60, 80x80, 100x100)">Gạch lát nền (60x60, 80x80...)</option>
                                        <option value="Gạch ốp tường (30x60, 60x120, 80x160)">Gạch ốp tường (30x60, 60x120...)</option>
                                        <option value="Gạch khổ lớn (1200x2400, 1600x3200)">Gạch khổ lớn (1200x2400...)</option>
                                        <option value="Gạch trang trí (Terrazzo, Giả gỗ, Mosaic)">Gạch trang trí (Terrazzo, Mosaic...)</option>
                                        <option value="Thiết bị vệ sinh trọn bộ">Thiết bị vệ sinh trọn bộ</option>
                                        <option value="Báo giá tổng thể công trình / đại lý">Báo giá công trình / đại lý</option>
                                    </select>
                                </div>
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Mã sản phẩm hoặc khối lượng dự kiến (m² / số lượng)</label>
                                <textarea id="qNote" rows="3" placeholder="Nhập mã gạch (VD: HG61201, HGMK8001, Bồn cầu KC816...), diện tích m² hoặc địa chỉ giao hàng tại Đà Nẵng..." class="w-full px-3 py-2 rounded-md border border-slate-300 focus:outline-none focus:border-rb-primary bg-slate-50 focus:bg-white"></textarea>
                            </div>
                            <button type="submit" class="w-full py-2.5 px-4 bg-rb-primary hover:bg-rb-dark text-white font-bold rounded-md shadow transition flex items-center justify-center gap-2">
                                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/></svg>
                                <span>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY</span>
                            </button>
                        </form>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 text-[11px] text-slate-500 flex flex-wrap items-center justify-between gap-2">
                        <span>Hotline/Zalo: <strong class="text-rb-dark">0905883738 - 02363731868</strong></span>
                        <span>Phản hồi trong 5 phút</span>
                    </div>
                </div>

                <!-- CỘT 2 (3/12): FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-3 bg-white rounded-xl border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
                    <div>
                        <h3 class="text-sm font-bold text-rb-dark pb-2.5 mb-3 border-b border-slate-100 flex items-center gap-1.5">
                            <svg class="w-4 h-4 text-[#1877F2] shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                            <span>FANPAGE CHÍNH THỨC</span>
                        </h3>

                        <!-- Khung giao diện Fanpage Công Ty Cổ Phần Rồng Bạc -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50">
                            <!-- Ảnh bìa Fanpage -->
                            <div class="h-24 bg-gradient-to-r from-rb-dark via-rb-primary to-rb-accent p-3 flex flex-col justify-between relative">
                                <span class="text-[10px] font-semibold bg-black/40 text-white px-2 py-0.5 rounded self-start">rongbac.com</span>
                                <div class="flex items-center gap-2.5">
                                    <div class="w-11 h-11 rounded-lg bg-white p-1 shadow flex items-center justify-center shrink-0 font-extrabold text-rb-dark text-sm border border-slate-200">
                                        RB
                                    </div>
                                    <div class="text-white leading-tight">
                                        <p class="font-bold text-xs">Công Ty Cổ Phần Rồng Bạc</p>
                                        <p class="text-[10px] text-slate-200">4.850 người theo dõi • Đà Nẵng</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Nút tương tác Fanpage -->
                            <div class="p-3 bg-white space-y-2.5">
                                <div class="grid grid-cols-2 gap-2">
                                    <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="py-1.5 px-2 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-[11px] font-bold text-center transition">
                                        Theo dõi Trang
                                    </a>
                                    <a href="https://zalo.me/0905883738" target="_blank" rel="noopener noreferrer" class="py-1.5 px-2 rounded bg-slate-100 hover:bg-slate-200 text-slate-800 text-[11px] font-bold text-center transition">
                                        Nhắn tin
                                    </a>
                                </div>
                                <div class="p-2.5 rounded bg-slate-50 border border-slate-100 text-[11px] text-slate-600 space-y-1">
                                    <p class="font-semibold text-rb-dark">Tổng Kho Gạch Men &amp; TBVS Rồng Bạc</p>
                                    <p>Chuyên cung cấp gạch lát nền 60x60, 80x80, gạch khổ lớn 60x120, 1200x2400 &amp; thiết bị phòng tắm tại Đà Nẵng.</p>
                                    <p class="text-rb-primary font-semibold">📍 230 Bắc Sơn, P. An Khê, TP Đà Nẵng</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
                        <span>Cập nhật mẫu mới mỗi ngày</span>
                        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="text-rb-primary font-bold hover:underline">Mở Facebook →</a>
                    </div>
                </div>

                <!-- CỘT 3 (4/12): BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ -->
                <div id="ban-do-trang-chu" class="lg:col-span-4 bg-white rounded-xl border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between pb-2.5 mb-3 border-b border-slate-100">
                            <h3 class="text-sm font-bold text-rb-dark flex items-center gap-1.5">
                                <svg class="w-4 h-4 text-rb-sale shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                                <span>BẢN ĐỒ GOOGLE MAPS</span>
                            </h3>
                            <a href="https://share.google/NbIGyVD0NxT3E04rM" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-white bg-rb-primary hover:bg-rb-dark px-2.5 py-1 rounded transition">
                                Mở Google Maps
                            </a>
                        </div>

                        <!-- Iframe Google Maps trực tiếp ngoài trang chủ tại 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng -->
                        <div class="w-full h-56 sm:h-60 rounded-lg overflow-hidden border border-slate-200 bg-slate-100 relative">
                            <iframe 
                                title="Bản đồ Công Ty Cổ Phần Rồng Bạc - 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=230+B%E1%BA%AFc+S%C6%A1n,+An+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs text-slate-600 space-y-1">
                        <p class="font-bold text-rb-dark">ĐỊA CHỈ: 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng</p>
                        <div class="flex flex-wrap items-center justify-between gap-2 text-[11px]">
                            <span>SĐT: <strong>0905883738 - 02363731868</strong></span>
                            <a href="https://share.google/NbIGyVD0NxT3E04rM" target="_blank" rel="noopener noreferrer" class="text-rb-accent font-bold hover:underline">
                                Xem trên Google Maps →
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== -->
    <section id="sec-bai-viet" class="py-6">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">TIN TỨC &amp; KINH NGHIỆM CHỌN GẠCH ỐP LÁT</h2>
                <span class="text-xs text-slate-500">Cẩm nang kiến trúc &amp; báo giá vật liệu xây dựng tại Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w800" 
                             data-fileid="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY"
                             onerror="handleDriveImageError(this)"
                             alt="Xu hướng chọn gạch khổ lớn 60x120 và 1200x2400 tại Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold text-rb-accent uppercase">Tư vấn chọn gạch</span>
                            <h3 class="text-xs sm:text-sm font-bold text-rb-dark mt-1 leading-snug">
                                Xu hướng chọn gạch khổ lớn 60x120 và 1200x2400 cho nhà phố &amp; biệt thự Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Gạch khổ lớn vân đá marble giúp mở rộng không gian, giảm đường ron và tăng vẻ sang trọng vượt thời gian cho phòng khách.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(0)" class="mt-3 text-xs font-bold text-rb-primary hover:text-rb-dark self-start">
                            Đọc chi tiết →
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w800" 
                             data-fileid="1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr"
                             onerror="handleDriveImageError(this)"
                             alt="Bảng báo giá gạch lát nền 60x60, 80x80 mới nhất tại Rồng Bạc" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold text-rb-accent uppercase">Bảng báo giá</span>
                            <h3 class="text-xs sm:text-sm font-bold text-rb-dark mt-1 leading-snug">
                                Bảng báo giá gạch lát nền 60x60, 80x80, 100x100 tại kho Rồng Bạc Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Cập nhật mức chiết khấu ưu đãi đến 35% dành cho khách hàng mua lẻ, chủ thầu xây dựng và các dự án khách sạn, căn hộ.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(1)" class="mt-3 text-xs font-bold text-rb-primary hover:text-rb-dark self-start">
                            Đọc chi tiết →
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w800" 
                             data-fileid="1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4"
                             onerror="handleDriveImageError(this)"
                             alt="Kinh nghiệm chọn thiết bị vệ sinh bồn cầu nguyên khối và tủ lavabo" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold text-rb-accent uppercase">Thiết bị phòng tắm</span>
                            <h3 class="text-xs sm:text-sm font-bold text-rb-dark mt-1 leading-snug">
                                Kinh nghiệm chọn Combo Thiết Bị Vệ Sinh: Bồn cầu 1 khối &amp; Tủ Lavabo Gương LED
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Bí quyết lựa chọn bồn cầu men tuyết phủ nano kháng khuẩn kết hợp tủ lavabo chống nước bền đẹp cho phòng tắm hiện đại.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(2)" class="mt-3 text-xs font-bold text-rb-primary hover:text-rb-dark self-start">
                            Đọc chi tiết →
                        </button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w800" 
                             data-fileid="19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r"
                             onerror="handleDriveImageError(this)"
                             alt="Cách phối gạch Terrazzo và gạch Mosaic trang trí nội ngoại thất" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold text-rb-accent uppercase">Gạch trang trí</span>
                            <h3 class="text-xs sm:text-sm font-bold text-rb-dark mt-1 leading-snug">
                                Phối màu Gạch Terrazzo, Gạch Giả Gỗ &amp; Gạch Mosaic tạo điểm nhấn kiến trúc
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Giải pháp sử dụng gạch trang trí chống trơn trượt, bền màu cho khu vực sân vườn, quán cafe, phòng tắm và mảng tường điểm nhấn.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(3)" class="mt-3 text-xs font-bold text-rb-primary hover:text-rb-dark self-start">
                            Đọc chi tiết →
                        </button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==================== THÔNG TIN GIỚI THIỆU TỔNG KHO (Giống cấu trúc web mẫu gachmendanang.vn) ==================== -->
    <section class="py-6 bg-white border-t border-slate-200">
        <div class="flatsome-container text-xs sm:text-sm text-slate-700 space-y-3 leading-relaxed">
            <h2 class="text-base sm:text-lg font-extrabold text-rb-dark uppercase">
                CÔNG TY CỔ PHẦN RỒNG BẠC – TỔNG KHO PHÂN PHỐI GẠCH MEN &amp; THIẾT BỊ VỆ SINH ĐÀ NẴNG
            </h2>
            <p>
                <strong>CÔNG TY CỔ PHẦN RỒNG BẠC (Website: rongbac.com)</strong> là đơn vị uy tín hàng đầu chuyên cung cấp <strong>gạch lát nền, gạch ốp tường, gạch trang trí, gạch khổ lớn cao cấp</strong> và <strong>thiết bị vệ sinh</strong> tại TP. Đà Nẵng và khu vực miền Trung. Với bề dày hoạt động từ năm 2011 (MST: 0401431074), chúng tôi tự hào là đối tác tin cậy mang đến vật liệu xây dựng chất lượng vượt trội cho nhà ở dân dụng, biệt thự, khách sạn, căn hộ và các dự án quy mô lớn.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-3 pt-2">
                <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                    <h3 class="font-bold text-rb-primary mb-1">1. Mẫu Mã Đa Dạng – Chất Lượng Vượt Trội</h3>
                    <p class="text-xs text-slate-600">Đầy đủ kích thước gạch 60x60, 80x80, 100x100, 60x120, 80x160, gạch khổ lớn 1200x2400, 1600x3200, gạch giả gỗ, terrazzo, mosaic và trọn bộ thiết bị phòng tắm cao cấp.</p>
                </div>
                <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                    <h3 class="font-bold text-rb-primary mb-1">2. Giá Cả Tận Kho – Chiết Khấu Hấp Dẫn</h3>
                    <p class="text-xs text-slate-600">Chính sách giá sỉ &amp; lẻ cạnh tranh trực tiếp từ tổng kho Rồng Bạc, hỗ trợ vận chuyển nhanh chóng tận chân công trình trên toàn địa bàn TP. Đà Nẵng.</p>
                </div>
                <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                    <h3 class="font-bold text-rb-primary mb-1">3. Tư Vấn Chuyên Nghiệp – Tận Tâm</h3>
                    <p class="text-xs text-slate-600">Đội ngũ tư vấn giàu kinh nghiệm hỗ trợ phối màu gạch ốp lát và chọn thiết bị vệ sinh tối ưu ngân sách. Liên hệ ngay: <strong>0905883738 - 02363731868</strong>.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="bg-rb-dark text-slate-300 pt-8 pb-20 md:pb-8 border-t-4 border-rb-primary text-xs">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-700/80">
                
                <!-- Cột 1: Thông tin Công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <div class="w-8 h-8 rounded bg-white text-rb-dark flex items-center justify-center font-extrabold text-sm shrink-0">RB</div>
                        <span class="font-extrabold text-white text-sm">CÔNG TY CỔ PHẦN RỒNG BẠC</span>
                    </div>
                    <p class="text-slate-300 leading-relaxed">
                        Tổng kho phân phối Gạch Ốp Lát, Đá Khổ Lớn &amp; Thiết Bị Vệ Sinh chính hãng tại Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><strong>Mã số thuế:</strong> 0401431074</li>
                        <li><strong>Địa chỉ:</strong> 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng</li>
                        <li><strong>Điện thoại:</strong> <a href="tel:0905883738" class="text-amber-400 font-bold hover:underline">0905883738</a> - <a href="tel:02363731868" class="text-amber-400 font-bold hover:underline">02363731868</a></li>
                        <li><strong>Website:</strong> <a href="https://rongbac.com" class="text-sky-400 font-semibold hover:underline">rongbac.com</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục Gạch Ốp Lát -->
                <div class="space-y-2">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs border-b border-slate-700 pb-2">DANH MỤC GẠCH ỐP LÁT</h4>
                    <ul class="space-y-1.5">
                        <li><a href="#sec-gach-lat-nen" onclick="filterBySubCat('60x60')" class="hover:text-white transition">• Gạch Lát Nền 60x60 Đà Nẵng</a></li>
                        <li><a href="#sec-gach-lat-nen" onclick="filterBySubCat('80x80')" class="hover:text-white transition">• Gạch Lát Nền 80x80 Cao Cấp</a></li>
                        <li><a href="#sec-gach-lat-nen" onclick="filterBySubCat('100x100')" class="hover:text-white transition">• Gạch Lát Nền 100x100 &amp; 120x120</a></li>
                        <li><a href="#sec-gach-60x120" onclick="filterBySubCat('60x120')" class="hover:text-white transition">• Gạch Ốp Lát 60x120 Vân Đá</a></li>
                        <li><a href="#sec-gach-kho-lon" onclick="filterBySubCat('1200x2400')" class="hover:text-white transition">• Gạch Khổ Lớn 1200x2400 &amp; 1600x3200</a></li>
                        <li><a href="#sec-gach-kho-lon" onclick="filterBySubCat('mosaic')" class="hover:text-white transition">• Gạch Trang Trí Terrazzo, Giả Gỗ, Mosaic</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục Thiết bị vệ sinh -->
                <div class="space-y-2">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs border-b border-slate-700 pb-2">THIẾT BỊ VỆ SINH ĐÀ NẴNG</h4>
                    <ul class="space-y-1.5">
                        <li><a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('bon-cau')" class="hover:text-white transition">• Bồn Cầu 1 Khối &amp; Bồn Cầu Thông Minh</a></li>
                        <li><a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('tu-lavabo')" class="hover:text-white transition">• Tủ Lavabo Gương LED Hiện Đại</a></li>
                        <li><a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('lavabo')" class="hover:text-white transition">• Chậu Rửa Lavabo &amp; Bàn Đá Lavabo</a></li>
                        <li><a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('voi-sen')" class="hover:text-white transition">• Vòi Sen Tắm Nóng Lạnh &amp; Âm Tường</a></li>
                        <li><a href="#sec-thiet-bi-ve-sinh" onclick="filterBySubCat('voi-lavabo')" class="hover:text-white transition">• Vòi Lavabo &amp; Phụ Kiện Phòng Tắm</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">• Đăng Ký Nhận Báo Giá Công Trình</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ trợ khách hàng & Google Map Link -->
                <div class="space-y-2.5">
                    <h4 class="font-bold text-white uppercase tracking-wider text-xs border-b border-slate-700 pb-2">KẾT NỐI VỚI RỒNG BẠC</h4>
                    <p class="text-slate-300">Giờ mở cửa: 07:30 – 17:30 (Thứ 2 – Thứ 7). Hỗ trợ tư vấn &amp; báo giá online 24/7.</p>
                    <div class="flex flex-col gap-2 pt-1">
                        <a href="https://share.google/NbIGyVD0NxT3E04rM" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded bg-slate-800 hover:bg-slate-700 text-white font-semibold flex items-center justify-between border border-slate-600 transition">
                            <span>📍 Xem bản đồ Google Maps</span>
                            <span>→</span>
                        </a>
                        <a href="https://zalo.me/0905883738" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded bg-sky-600 hover:bg-sky-500 text-white font-semibold flex items-center justify-between transition">
                            <span>💬 Chat Zalo: 0905.883.738</span>
                            <span>→</span>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
                <p>© Bản quyền thuộc về <strong>CÔNG TY CỔ PHẦN RỒNG BẠC (rongbac.com)</strong>. Địa chỉ: 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng.</p>
                <p>Giao diện tối ưu chuẩn Flatsome UX Builder • Điện thoại &amp; Máy tính</p>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) ==================== -->
    <!-- Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền -->
    <div class="fixed bottom-4 right-3 sm:right-4 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0905883738" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905883738" class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition floating-pulse">
            <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo: 0905.883.738</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook Công Ty Cổ Phần Rồng Bạc" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Fanpage Rồng Bạc</span>
        </a>

        <!-- Nút Hotline Bàn 02363731868 -->
        <a href="tel:02363731868" aria-label="Gọi máy bàn 02363731868" class="group flex items-center gap-2 bg-rb-primary hover:bg-rb-dark text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-rb-primary flex items-center justify-center shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">0236.3731.868</span>
        </a>

        <!-- Nút Hotline Di Động 0905883738 -->
        <a href="tel:0905883738" aria-label="Gọi Hotline 0905883738" class="group flex items-center gap-2 bg-rb-sale hover:bg-red-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition floating-pulse">
            <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-rb-sale flex items-center justify-center shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            </span>
            <span class="text-xs font-extrabold pr-1.5">0905.883.738</span>
        </a>
    </div>

    <!-- ==================== MODAL CHI TIẾT SẢN PHẨM & BÀI VIẾT (Không dùng alert) ==================== -->
    <div id="customModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/60">
        <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
            <div class="p-3.5 bg-rb-dark text-white flex items-center justify-between">
                <h3 id="modalTitle" class="font-bold text-sm">Thông tin chi tiết</h3>
                <button type="button" onclick="closeModal()" class="text-slate-300 hover:text-white p-1">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div id="modalBody" class="p-4 text-xs sm:text-sm text-slate-700 space-y-3 max-h-[75vh] overflow-y-auto"></div>
            <div class="p-3 bg-slate-100 flex items-center justify-end gap-2">
                <a href="tel:0905883738" class="px-3 py-1.5 bg-rb-sale text-white rounded font-bold text-xs">Gọi 0905.883.738</a>
                <button type="button" onclick="closeModal()" class="px-3 py-1.5 bg-slate-300 hover:bg-slate-400 text-slate-800 rounded font-semibold text-xs">Đóng</button>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC ==================== -->
    <script>
        /* Danh sách 11 File ID ảnh sản phẩm thực tế trên Google Drive do người dùng cung cấp */
        const DRIVE_IMAGE_IDS = [
            "1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY", // #0
            "11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP", // #1
            "1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr", // #2
            "1X31hmhpLVVORV-tmMSZYzBO-qtpyusry", // #3
            "171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O", // #4
            "1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg", // #5
            "1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4", // #6
            "1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54", // #7
            "19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r", // #8
            "1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h", // #9
            "1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN"  // #10
        ];

        function getDriveImgUrl(fileId) {
            return `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
        }

        /* Chuỗi dự phòng thông minh cho ảnh Google Drive để luôn hiển thị rõ nét trên mọi trình duyệt */
        function handleDriveImageError(imgEl) {
            const fileId = imgEl.getAttribute('data-fileid');
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            if (step === 0 && fileId) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
            } else if (step === 1 && fileId) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = `https://drive.google.com/uc?export=view&id=${fileId}`;
            } else {
                imgEl.setAttribute('data-fallback-step', '3');
                const svgFallback = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 400"><rect width="400" height="400" fill="#e2e8f0"/><path d="M30 80 Q180 150 140 280 T360 350" stroke="#94a3b8" stroke-width="5" fill="none"/><rect x="40" y="310" width="320" height="50" rx="8" fill="#0c233c"/><text x="200" y="340" text-anchor="middle" fill="#ffffff" font-family="sans-serif" font-size="16" font-weight="bold">CÔNG TY CP RỒNG BẠC</text></svg>`;
                imgEl.src = 'data:image/svg+xml;utf8,' + encodeURIComponent(svgFallback);
            }
        }

        /* 12 Danh mục sản phẩm chính trên trang chủ (Theo chuẩn gachmendanang.vn) */
        const HOMEPAGE_CATEGORIES = [
            { title: "GẠCH 60X60", count: "60 Sản phẩm", sub: "60x60", imgId: DRIVE_IMAGE_IDS[0], target: "#sec-gach-lat-nen" },
            { title: "GẠCH 80X80", count: "82 Sản phẩm", sub: "80x80", imgId: DRIVE_IMAGE_IDS[1], target: "#sec-gach-lat-nen" },
            { title: "GẠCH 100X100", count: "55 Sản phẩm", sub: "100x100", imgId: DRIVE_IMAGE_IDS[2], target: "#sec-gach-lat-nen" },
            { title: "GẠCH 60X120", count: "171 Sản phẩm", sub: "60x120", imgId: DRIVE_IMAGE_IDS[3], target: "#sec-gach-60x120" },
            { title: "GẠCH 80X160", count: "66 Sản phẩm", sub: "80x160", imgId: DRIVE_IMAGE_IDS[4], target: "#sec-gach-lat-nen" },
            { title: "GẠCH 1200X2400", count: "20 Sản phẩm", sub: "1200x2400", imgId: DRIVE_IMAGE_IDS[5], target: "#sec-gach-kho-lon" },
            { title: "GẠCH 1600X3200", count: "43 Sản phẩm", sub: "1600x3200", imgId: DRIVE_IMAGE_IDS[6], target: "#sec-gach-kho-lon" },
            { title: "GẠCH TERRAZZO", count: "44 Sản phẩm", sub: "terrazzo", imgId: DRIVE_IMAGE_IDS[7], target: "#sec-gach-kho-lon" },
            { title: "GẠCH GIẢ GỖ", count: "48 Sản phẩm", sub: "gia-go", imgId: DRIVE_IMAGE_IDS[8], target: "#sec-gach-kho-lon" },
            { title: "GẠCH MOSAIC", count: "126 Sản phẩm", sub: "mosaic", imgId: DRIVE_IMAGE_IDS[9], target: "#sec-gach-kho-lon" },
            { title: "BỒN CẦU CAO CẤP", count: "23 Sản phẩm", sub: "bon-cau", imgId: DRIVE_IMAGE_IDS[10], target: "#sec-thiet-bi-ve-sinh" },
            { title: "TỦ LAVABO & SEN TẮM", count: "80 Sản phẩm", sub: "tu-lavabo", imgId: DRIVE_IMAGE_IDS[0], target: "#sec-thiet-bi-ve-sinh" }
        ];

        /* Danh sách sản phẩm thực tế kết hợp 11 ảnh Google Drive & tên mã chuẩn mẫu gachmendanang.vn */
        const PRODUCTS_DATA = [
            // NHÓM 1: GẠCH 60X120 (8 sản phẩm)
            { id: 1, name: "Gạch 60×120 HG61201 Vân Đá Cẩm Thạch", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 480000, price: 370000, discount: 23, imgId: DRIVE_IMAGE_IDS[0] },
            { id: 2, name: "Gạch 60×120 HG61204 Bóng Kiếng Toàn Phần", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 480000, price: 370000, discount: 23, imgId: DRIVE_IMAGE_IDS[1] },
            { id: 3, name: "Gạch 60×120 HGE61214 Nhập Khẩu Cao Cấp", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 750000, price: 570000, discount: 24, imgId: DRIVE_IMAGE_IDS[2] },
            { id: 4, name: "Gạch 60×120 HGKH61205B Xương Đá Porcelain", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 530000, price: 415000, discount: 22, imgId: DRIVE_IMAGE_IDS[3] },
            { id: 5, name: "Gạch 60×120 HGKH612002M Men Matt Chống Trơn", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 530000, price: 415000, discount: 22, imgId: DRIVE_IMAGE_IDS[4] },
            { id: 6, name: "Gạch 60×120 HGKH612001M Vân Đá Tự Nhiên", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 530000, price: 415000, discount: 22, imgId: DRIVE_IMAGE_IDS[5] },
            { id: 7, name: "Gạch 60×120 HGKH12612 Ốp Lát Phòng Khách", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 430000, price: 350000, discount: 19, imgId: DRIVE_IMAGE_IDS[6] },
            { id: 8, name: "Gạch 60×120 HG61281 Vân Mây Sang Trọng", group: "60x120", cat: "gach-op-tuong", sub: "60x120", oldPrice: 430000, price: 360000, discount: 16, imgId: DRIVE_IMAGE_IDS[7] },

            // NHÓM 2: GẠCH LÁT NỀN 60X60, 80X80, 100X100, 80X160 (8 sản phẩm)
            { id: 9, name: "Gạch Lát Nền 80×80 HGMK8001 Đá Bóng Kiếng", group: "lat-nen", cat: "gach-lat-nen", sub: "80x80", oldPrice: 250000, price: 160000, discount: 36, imgId: DRIVE_IMAGE_IDS[8] },
            { id: 10, name: "Gạch Lát Nền 80×80 HGMK8002 Vân Đá Trắng Khói", group: "lat-nen", cat: "gach-lat-nen", sub: "80x80", oldPrice: 250000, price: 160000, discount: 36, imgId: DRIVE_IMAGE_IDS[9] },
            { id: 11, name: "Gạch Lát Nền 60×60 HG3P601 Porcelain Chống Thấm", group: "lat-nen", cat: "gach-lat-nen", sub: "60x60", oldPrice: 310000, price: 210000, discount: 32, imgId: DRIVE_IMAGE_IDS[10] },
            { id: 12, name: "Gạch Lát Nền 60×60 HG2M601 Vân Đá Hiện Đại", group: "lat-nen", cat: "gach-lat-nen", sub: "60x60", oldPrice: 320000, price: 215000, discount: 33, imgId: DRIVE_IMAGE_IDS[0] },
            { id: 13, name: "Gạch Lát Nền 100×100 HGT11027 Khổ Vuông Lớn", group: "lat-nen", cat: "gach-lat-nen", sub: "100x100", oldPrice: 540000, price: 410000, discount: 24, imgId: DRIVE_IMAGE_IDS[1] },
            { id: 14, name: "Gạch Ốp Lát 80×160 HG81602 Vân Đá Hoàng Gia", group: "lat-nen", cat: "gach-lat-nen", sub: "80x160", oldPrice: 582000, price: 455000, discount: 22, imgId: DRIVE_IMAGE_IDS[2] },
            { id: 15, name: "Gạch Ốp Lát 80×160 HG81605 Bóng Kiếng Cao Cấp", group: "lat-nen", cat: "gach-lat-nen", sub: "80x160", oldPrice: 636000, price: 515000, discount: 19, imgId: DRIVE_IMAGE_IDS[3] },
            { id: 16, name: "Gạch Lát Nền 120×120 HG121201 Đại Sảnh Biệt Thự", group: "lat-nen", cat: "gach-lat-nen", sub: "120x120", oldPrice: 680000, price: 520000, discount: 24, imgId: DRIVE_IMAGE_IDS[4] },

            // NHÓM 3: GẠCH KHỔ LỚN 1200X2400 & GẠCH TRANG TRÍ (8 sản phẩm)
            { id: 17, name: "Gạch Khổ Lớn 1200×2400 HGE122403 Vân Đá Nhập Khẩu", group: "kho-lon", cat: "gach-kho-lon", sub: "1200x2400", oldPrice: 2200000, price: 1500000, discount: 32, imgId: DRIVE_IMAGE_IDS[5] },
            { id: 18, name: "Gạch Khổ Lớn 1200×2400 HG122401 Map Đá Tự Nhiên", group: "kho-lon", cat: "gach-kho-lon", sub: "1200x2400", oldPrice: 830000, price: 610000, discount: 27, imgId: DRIVE_IMAGE_IDS[6] },
            { id: 19, name: "Gạch Khổ Lớn 1200×2800 HGE122412 Ốp Vách Tivi", group: "kho-lon", cat: "gach-kho-lon", sub: "1200x2800", oldPrice: 2200000, price: 1500000, discount: 32, imgId: DRIVE_IMAGE_IDS[7] },
            { id: 20, name: "Gạch Khổ Lớn 1600×3200 HG163201 Đá Nung Kết", group: "kho-lon", cat: "gach-kho-lon", sub: "1600x3200", oldPrice: 2650000, price: 1890000, discount: 29, imgId: DRIVE_IMAGE_IDS[8] },
            { id: 21, name: "Gạch Trang Trí Terrazzo 60×60 HGTZ601 Hạt Đá Mài", group: "kho-lon", cat: "gach-trang-tri", sub: "terrazzo", oldPrice: 350000, price: 245000, discount: 30, imgId: DRIVE_IMAGE_IDS[9] },
            { id: 22, name: "Gạch Thẻ Giả Gỗ 20×100 HGGG2101 Vân Gỗ Sồi Ấm", group: "kho-lon", cat: "gach-trang-tri", sub: "gia-go", oldPrice: 340000, price: 240000, discount: 29, imgId: DRIVE_IMAGE_IDS[10] },
            { id: 23, name: "Gạch Mosaic Gốm Thẻ HG22108 Trang Trí Quán Cafe", group: "kho-lon", cat: "gach-trang-tri", sub: "mosaic", oldPrice: 620000, price: 450000, discount: 27, imgId: DRIVE_IMAGE_IDS[0] },
            { id: 24, name: "Gạch Mosaic Thủy Tinh Ánh Kim Sa HG25006 Hồ Bơi", group: "kho-lon", cat: "gach-trang-tri", sub: "mosaic", oldPrice: 590000, price: 420000, discount: 29, imgId: DRIVE_IMAGE_IDS[1] },

            // NHÓM 4: THIẾT BỊ VỆ SINH ĐÀ NẴNG (8 sản phẩm)
            { id: 25, name: "Bồn Cầu Nguyên Khối Hiện Đại KC816 Men Tuyết Nano", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "bon-cau", oldPrice: 5000000, price: 2450000, discount: 51, imgId: DRIVE_IMAGE_IDS[2] },
            { id: 26, name: "Bồn Cầu Thông Minh Cao Cấp KC945 Tự Động Xả", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "bon-cau", oldPrice: 7900000, price: 6500000, discount: 18, imgId: DRIVE_IMAGE_IDS[3] },
            { id: 27, name: "Bồn Cầu Trứng Cao Cấp KC806T Kiểu Dáng Sang Trọng", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "bon-cau", oldPrice: 4200000, price: 3000000, discount: 29, imgId: DRIVE_IMAGE_IDS[4] },
            { id: 28, name: "Bồn Cầu 1 Khối KC634 Xả Xoáy Siêu Mạnh Tiết Kiệm Nước", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "bon-cau", oldPrice: 3700000, price: 1850000, discount: 50, imgId: DRIVE_IMAGE_IDS[5] },
            { id: 29, name: "Tủ Lavabo 02 Tầng Gương LED Cảm Ứng Hiện Đại KT40", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "tu-lavabo", oldPrice: 4800000, price: 3350000, discount: 30, imgId: DRIVE_IMAGE_IDS[6] },
            { id: 30, name: "Tủ Lavabo Bàn Đá Chống Nước Cao Cấp KT50", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "tu-lavabo", oldPrice: 5500000, price: 3850000, discount: 30, imgId: DRIVE_IMAGE_IDS[7] },
            { id: 31, name: "Bộ Vòi Sen Tắm Nóng Lạnh Phím Đàn Hiện Đại KS70", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "voi-sen", oldPrice: 2800000, price: 1790000, discount: 36, imgId: DRIVE_IMAGE_IDS[8] },
            { id: 32, name: "Vòi Lavabo Nóng Lạnh Thác Nước Mạ PVD Cao Cấp KV01D", group: "tbvs", cat: "thiet-bi-ve-sinh", sub: "voi-lavabo", oldPrice: 1250000, price: 790000, discount: 37, imgId: DRIVE_IMAGE_IDS[9] }
        ];

        function formatVND(num) {
            return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ".") + " ₫";
        }

        /* Render Danh mục sản phẩm ở trang chủ */
        function renderHomepageCategories() {
            const container = document.getElementById('homepageCategoryGrid');
            container.innerHTML = HOMEPAGE_CATEGORIES.map(item => `
                <a href="${item.target}" onclick="filterBySubCat('${item.sub}')" class="group bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-rb-primary transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden relative">
                        <img src="${getDriveImgUrl(item.imgId)}"
                             data-fileid="${item.imgId}"
                             onerror="handleDriveImageError(this)"
                             alt="${item.title} - Công Ty Cổ Phần Rồng Bạc"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2 text-center bg-white">
                        <h3 class="text-[11px] sm:text-xs font-extrabold text-rb-dark group-hover:text-rb-primary cat-nowrap justify-center w-full">${item.title}</h3>
                        <p class="text-[10px] text-slate-500 mt-0.5">${item.count}</p>
                    </div>
                </a>
            `).join('');
        }

        /* Tạo HTML chuẩn Flatsome cho 1 thẻ sản phẩm (Có % giảm giá góc trên bên trái, tên sản phẩm không bị cắt chữ) */
        function createProductCardHTML(p) {
            return `
                <div class="flatsome-product-box" data-cat="${p.cat}" data-sub="${p.sub}" data-name="${p.name.toLowerCase()}">
                    <div class="relative aspect-square w-full bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${p.id})">
                        <span class="flatsome-badge-sale">-${p.discount}%</span>
                        <img src="${getDriveImgUrl(p.imgId)}"
                             data-fileid="${p.imgId}"
                             onerror="handleDriveImageError(this)"
                             alt="${p.name}"
                             loading="lazy"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="flatsome-product-title cursor-pointer hover:text-rb-primary transition" onclick="openProductModal(${p.id})">
                                ${p.name}
                            </h3>
                        </div>
                        <div class="pt-1.5 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <del class="text-[11px] sm:text-xs text-slate-400 font-medium">${formatVND(p.oldPrice)}</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-rb-sale no-underline">${formatVND(p.price)}</ins>
                            </div>
                            <button type="button" onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}')" class="mt-2 w-full py-1.5 px-2 rounded bg-slate-100 hover:bg-rb-primary hover:text-white text-rb-dark text-[11px] font-bold transition text-center">
                                Nhận báo giá sỉ &amp; lẻ
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        /* Render toàn bộ 4 khu vực sản phẩm trên trang chủ */
        function renderAllProducts(filterFn = null) {
            const list = filterFn ? PRODUCTS_DATA.filter(filterFn) : PRODUCTS_DATA;

            const g1 = list.filter(p => p.group === '60x120');
            const g2 = list.filter(p => p.group === 'lat-nen');
            const g3 = list.filter(p => p.group === 'kho-lon');
            const g4 = list.filter(p => p.group === 'tbvs');

            document.getElementById('grid-60x120').innerHTML = g1.map(createProductCardHTML).join('');
            document.getElementById('grid-lat-nen').innerHTML = g2.map(createProductCardHTML).join('');
            document.getElementById('grid-kho-lon').innerHTML = g3.map(createProductCardHTML).join('');
            document.getElementById('grid-tbvs').innerHTML = g4.map(createProductCardHTML).join('');

            document.getElementById('sec-gach-60x120').style.display = g1.length ? 'block' : 'none';
            document.getElementById('sec-gach-lat-nen').style.display = g2.length ? 'block' : 'none';
            document.getElementById('sec-gach-kho-lon').style.display = g3.length ? 'block' : 'none';
            document.getElementById('sec-thiet-bi-ve-sinh').style.display = g4.length ? 'block' : 'none';
        }

        function filterByCategory(catSlug) {
            const statusBanner = document.getElementById('filterStatusBanner');
            const statusText = document.getElementById('filterStatusText');
            if (catSlug === 'all') {
                statusBanner.classList.add('hidden');
                renderAllProducts(null);
            } else {
                statusBanner.classList.remove('hidden');
                statusText.textContent = `Đang hiển thị danh mục: ${catSlug.toUpperCase()}`;
                renderAllProducts(p => p.cat === catSlug);
            }
        }

        function filterBySubCat(subSlug) {
            const statusBanner = document.getElementById('filterStatusBanner');
            const statusText = document.getElementById('filterStatusText');
            statusBanner.classList.remove('hidden');
            statusText.textContent = `Đang lọc theo phân loại: ${subSlug.toUpperCase()}`;
            renderAllProducts(p => p.sub === subSlug);
        }

        function handleSearchProduct(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            const statusBanner = document.getElementById('filterStatusBanner');
            const statusText = document.getElementById('filterStatusText');
            if (!q) {
                statusBanner.classList.add('hidden');
                renderAllProducts(null);
                return;
            }
            statusBanner.classList.remove('hidden');
            statusText.textContent = `Kết quả tìm kiếm cho từ khóa: "${keyword}"`;
            renderAllProducts(p => p.name.toLowerCase().includes(q) || p.sub.toLowerCase().includes(q));
        }

        /* Chọn sản phẩm đưa xuống Form Báo Giá */
        function selectProductForQuote(productName) {
            const noteEl = document.getElementById('qNote');
            noteEl.value = `Tôi cần báo giá sản phẩm: ${productName} (Số lượng / diện tích dự kiến: ... m²)`;
            document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
            document.getElementById('qName').focus();
        }

        /* Xem chi tiết sản phẩm trong Modal */
        function openProductModal(productId) {
            const p = PRODUCTS_DATA.find(item => item.id === productId);
            if (!p) return;
            document.getElementById('modalTitle').textContent = p.name;
            document.getElementById('modalBody').innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 items-center">
                    <div class="aspect-square rounded-lg overflow-hidden border border-slate-200 bg-slate-100 relative">
                        <span class="flatsome-badge-sale">-${p.discount}%</span>
                        <img src="${getDriveImgUrl(p.imgId)}" data-fileid="${p.imgId}" onerror="handleDriveImageError(this)" alt="${p.name}" class="w-full h-full object-cover">
                    </div>
                    <div class="space-y-2">
                        <p class="text-xs font-bold text-rb-primary uppercase">CÔNG TY CỔ PHẦN RỒNG BẠC</p>
                        <h4 class="text-sm font-extrabold text-rb-dark">${p.name}</h4>
                        <div class="flex items-baseline gap-2">
                            <del class="text-xs text-slate-400">${formatVND(p.oldPrice)}</del>
                            <span class="text-base font-extrabold text-rb-sale">${formatVND(p.price)}</span>
                        </div>
                        <ul class="text-xs text-slate-600 space-y-1 pt-1 border-t border-slate-100">
                            <li>• <strong>Phân loại:</strong> ${p.sub.toUpperCase()}</li>
                            <li>• <strong>Tình trạng:</strong> Sẵn kho Đà Nẵng</li>
                            <li>• <strong>Showroom:</strong> 230 Bắc Sơn, P. An Khê, TP Đà Nẵng</li>
                            <li>• <strong>Hotline/Zalo:</strong> 0905883738 - 02363731868</li>
                        </ul>
                        <button type="button" onclick="closeModal(); selectProductForQuote('${p.name.replace(/'/g, "\\'")}');" class="w-full mt-2 py-2 bg-rb-primary hover:bg-rb-dark text-white rounded font-bold text-xs">
                            Đăng ký nhận giá chiết khấu công trình
                        </button>
                    </div>
                </div>
            `;
            const modal = document.getElementById('customModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        /* Nội dung chi tiết 4 bài viết trang chủ */
        const ARTICLES_CONTENT = [
            {
                title: "Xu hướng chọn gạch khổ lớn 60x120 và 1200x2400 tại Đà Nẵng",
                body: "<p>Gạch khổ lớn 60x120, 80x160 và 1200x2400 đang trở thành lựa chọn hàng đầu cho các công trình nhà phố, biệt thự và khách sạn tại Đà Nẵng nhờ bề mặt vân đá liền mạch, sang trọng và dễ vệ sinh.</p><p>Tại Tổng kho <strong>Công Ty Cổ Phần Rồng Bạc (230 Bắc Sơn, Phường An Khê, TP Đà Nẵng)</strong>, quý khách có thể trực tiếp trải nghiệm hàng trăm mẫu gạch khổ lớn bề mặt bóng kiếng, matt mịn và сахар chống trơn với mức chiết khấu ưu đãi lên tới 35%.</p>"
            },
            {
                title: "Bảng báo giá gạch lát nền 60x60, 80x80, 100x100 tại kho Rồng Bạc",
                body: "<p>Công Ty Cổ Phần Rồng Bạc cung cấp đầy đủ các phân khúc gạch lát nền xương đá Porcelain chống thấm, độ cứng cao:</p><ul class='list-disc pl-5 space-y-1'><li>Gạch lát nền 60x60: Giá ưu đãi chỉ từ 160.000 ₫ - 215.000 ₫/m²</li><li>Gạch lát nền 80x80 bóng kiếng: Giá ưu đãi từ 160.000 ₫ - 290.000 ₫/m²</li><li>Gạch 60x120 &amp; 80x160: Giá ưu đãi từ 350.000 ₫ - 570.000 ₫/m²</li></ul><p>Liên hệ ngay Hotline <strong>0905883738 - 02363731868</strong> để nhận báo giá sỉ cho công trình.</p>"
            },
            {
                title: "Kinh nghiệm chọn Combo Thiết Bị Vệ Sinh: Bồn cầu 1 khối & Tủ Lavabo LED",
                body: "<p>Khi chọn thiết bị phòng tắm, gia chủ nên ưu tiên bồn cầu đúc nguyên khối phủ men tuyết Nano chống bám bẩn kết hợp hệ thống xả xoáy siêu êm.</p><p>Bên cạnh đó, các mẫu Tủ Lavabo 2 tầng tích hợp gương LED cảm ứng chống mờ sương tại <strong>rongbac.com</strong> giúp tối ưu diện tích lưu trữ và nâng tầm thẩm mỹ phòng tắm hiện đại.</p>"
            },
            {
                title: "Phối màu Gạch Terrazzo, Gạch Giả Gỗ & Gạch Mosaic tạo điểm nhấn",
                body: "<p>Sự kết hợp giữa gạch Terrazzo hạt đá mài hiện đại cùng gạch thẻ giả gỗ ấm cúng hoặc gạch Mosaic thủy tinh/gốm thẻ giúp không gian phòng tắm, sân vườn, quán cafe trở nên độc đáo và bền bỉ trước thời tiết miền Trung.</p>"
            }
        ];

        function openArticleModal(idx) {
            const art = ARTICLES_CONTENT[idx];
            if (!art) return;
            document.getElementById('modalTitle').textContent = art.title;
            document.getElementById('modalBody').innerHTML = art.body;
            const modal = document.getElementById('customModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('customModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Xử lý gửi Form Yêu cầu & Báo giá trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const cat = document.getElementById('qCat').value;
            const note = document.getElementById('qNote').value.trim();

            document.getElementById('modalTitle').textContent = "Đã Tiếp Nhận Yêu Cầu Báo Giá";
            document.getElementById('modalBody').innerHTML = `
                <div class="p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-900 space-y-1.5">
                    <p class="font-bold text-sm">Cảm ơn quý khách ${name}!</p>
                    <p class="text-xs">Yêu cầu báo giá của quý khách đã được gửi tới bộ phận kinh doanh <strong>CÔNG TY CỔ PHẦN RỒNG BẠC</strong>.</p>
                </div>
                <div class="text-xs space-y-1 text-slate-700 pt-1">
                    <p>• <strong>Số điện thoại nhận báo giá:</strong> ${phone}</p>
                    <p>• <strong>Hạng mục quan tâm:</strong> ${cat}</p>
                    <p>• <strong>Ghi chú:</strong> ${note || 'Tư vấn báo giá tốt nhất'}</p>
                    <p>• <strong>Địa chỉ kho &amp; showroom:</strong> 230 Bắc Sơn, Phường An Khê, TP Đà Nẵng</p>
                </div>
                <div class="pt-2">
                    <a href="https://zalo.me/0905883738" target="_blank" rel="noopener noreferrer" class="block w-full py-2 text-center rounded bg-[#0068ff] text-white font-bold text-xs">
                        Mở Zalo 0905.883.738 nhận bảng giá ngay
                    </a>
                </div>
            `;
            const modal = document.getElementById('customModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.getElementById('quoteForm').reset();
        }

        /* Điều khiển Menu Drawer trên điện thoại */
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileDrawer');
            drawer.classList.toggle('hidden');
        }

        /* Điều khiển 2 Banner Tự Trượt chuyên nghiệp */
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function updateSliderUI() {
            const track = document.getElementById('bannerTrack');
            track.style.transform = `translateX(-${currentSlideIndex * 100}%)`;
            const dot0 = document.getElementById('dot0');
            const dot1 = document.getElementById('dot1');
            if (currentSlideIndex === 0) {
                dot0.className = "w-6 h-2 rounded-full bg-white transition-all";
                dot1.className = "w-2.5 h-2 rounded-full bg-white/50 transition-all";
            } else {
                dot0.className = "w-2.5 h-2 rounded-full bg-white/50 transition-all";
                dot1.className = "w-6 h-2 rounded-full bg-white transition-all";
            }
        }

        function changeSlide(step) {
            currentSlideIndex = (currentSlideIndex + step + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function goToSlide(idx) {
            currentSlideIndex = idx;
            updateSliderUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                currentSlideIndex = (currentSlideIndex + 1) % totalSlides;
                updateSliderUI();
            }, 4500);
        }

        window.addEventListener('DOMContentLoaded', () => {
            renderHomepageCategories();
            renderAllProducts(null);
            resetAutoSlide();
        });
    </script>
</body>
</html>
