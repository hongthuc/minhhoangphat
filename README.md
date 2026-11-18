<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ & XÂY DỰNG MINH HOÀNG PHÁT - minhhoangphat.com</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ & XÂY DỰNG MINH HOÀNG PHÁT chuyên Thiết kế Kiến trúc - Nội thất, Thi công phần thô, Thi công hoàn thiện, Xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0935.330.198">
    
    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link minhhoangphat.com -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://minhhoangphat.com/">
    <meta property="og:title" content="CÔNG TY TNHH TM DV & XD MINH HOÀNG PHÁT - Thiết Kế & Xây Dựng Trọn Gói Đà Nẵng">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc, Thi công phần thô, Thi công hoàn thiện, Thi công nội thất Biệt thự, Nhà phố, Khách sạn, Căn hộ tại Đà Nẵng. Đ/c: 26 Cồn Dầu 23, P. Hòa Xuân, TP Đà Nẵng. SĐT: 0935.330.198">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1200">
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='16' fill='%230b3558'/%3E%3Cpath d='M18 76V38L50 16L82 38V76H66V50H34V76H18Z' fill='%23f59e0b'/%3E%3Cpath d='M38 76V44L50 35L62 44V76H38Z' fill='%23ffffff'/%3E%3C/svg%3E">

    <!-- Tailwind CSS & Font Awesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <style>
        /* Cấu hình chuẩn Flatsome UX Builder & Chống tràn viền tuyệt đối */
        :root {
            --mhp-primary: #0b3558;      /* Xanh Navy đậm theo màu Logo */
            --mhp-secondary: #154c79;    /* Xanh thương hiệu phụ */
            --mhp-accent: #e68a00;       /* Vàng cam xây dựng theo màu Logo */
            --mhp-accent-light: #f59e0b;
            --mhp-bg-light: #f8fafc;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            color: #1e293b;
            background-color: #ffffff;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn 95% màn hình máy tính, cân giữa không lệch phải */
        .ux-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }

        @media (min-width: 1024px) {
            .ux-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
                margin-left: auto !important;
                margin-right: auto !important;
            }
        }

        /* Tối ưu thanh danh mục trên máy tính: chữ nhỏ gọn, viết liền không bị gãy dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px;
        }

        @media (min-width: 1200px) {
            .desktop-nav-list {
                flex-wrap: nowrap;
                gap: 4px;
            }
        }

        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 600;
            letter-spacing: -0.01em;
            padding: 8px 9px;
            color: #0b3558;
            border-radius: 6px;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        .desktop-nav-item:hover, .desktop-nav-item.active {
            background-color: #0b3558;
            color: #ffffff;
        }

        /* Dropdown menu chuẩn Flatsome */
        .ux-dropdown {
            position: relative;
        }
        .ux-dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            border-top: 3px solid var(--mhp-accent);
            box-shadow: 0 10px 25px rgba(11, 53, 88, 0.15);
            border-radius: 0 0 8px 8px;
            z-index: 100;
            padding: 6px 0;
        }
        .ux-dropdown:hover .ux-dropdown-menu {
            display: block;
        }
        .ux-dropdown-menu a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #1e293b;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .ux-dropdown-menu a:last-child {
            border-bottom: none;
        }
        .ux-dropdown-menu a:hover {
            background-color: #f8fafc;
            color: var(--mhp-accent);
            padding-left: 18px;
        }

        /* Banner Slider 2 ảnh bằng nhau tuyệt đối, chữ cách xa viền */
        .ux-banner-wrapper {
            position: relative;
            width: 100%;
            height: 290px;
            overflow: hidden;
            border-radius: 10px;
            background-color: var(--mhp-primary);
        }

        @media (min-width: 640px) {
            .ux-banner-wrapper {
                height: 360px;
            }
        }

        @media (min-width: 1024px) {
            .ux-banner-wrapper {
                height: 450px;
                border-radius: 12px;
            }
        }

        .ux-banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }

        .ux-banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Tiêu đề section kiểu Flatsome */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 8px;
        }
        .section-title-line {
            flex: 1;
            height: 2px;
            background: linear-gradient(90deg, transparent, #cbd5e1, transparent);
            max-width: 180px;
        }

        /* Tên sản phẩm / dự án hiển thị đầy đủ, không bị cắt chữ hay tràn khung */
        .product-card-title {
            white-space: normal !important;
            word-wrap: break-word !important;
            overflow-wrap: break-word !important;
            line-height: 1.38;
        }

        /* Nút liên hệ nổi bật cố định gọn gàng */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 138, 0, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(230, 138, 0, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 138, 0, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==================== TOP BAR (CHUẨN FLATSOME) ==================== -->
    <div class="bg-[#0b3558] text-white text-xs py-2 border-b border-[#154c79]">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 overflow-hidden">
                <span class="inline-flex items-center gap-1.5 font-medium truncate">
                    <i class="fa-solid fa-building-shield text-[#f59e0b]"></i>
                    <span>CÔNG TY TNHH TM DV & XD MINH HOÀNG PHÁT</span>
                </span>
                <span class="hidden md:inline-block text-slate-400">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-[#f59e0b]"></i>
                    <span>26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="tel:0935330198" class="inline-flex items-center gap-1 hover:text-[#f59e0b] transition">
                    <i class="fa-solid fa-phone-volume text-[#f59e0b]"></i>
                    <span class="font-semibold">0935.330.198</span>
                </a>
                <span class="text-slate-400">|</span>
                <a href="https://minhhoangphat.com" class="inline-flex items-center gap-1 hover:text-[#f59e0b] transition">
                    <i class="fa-solid fa-globe text-[#f59e0b]"></i>
                    <span>minhhoangphat.com</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==================== HEADER & NAVIGATION (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
        <div class="ux-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- LOGO CÔNG TY CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg bg-[#0b3558] flex items-center justify-center shadow-sm border border-[#f59e0b]/40 shrink-0">
                    <svg class="w-7 h-7" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Biểu tượng Mái nhà & Tòa nhà kiến trúc chữ MHP -->
                        <path d="M12 44L50 14L88 44L82 51L50 26L18 51L12 44Z" fill="#f59e0b"/>
                        <path d="M22 48L50 27L78 48V84H64V56H36V84H22V48Z" fill="#ffffff"/>
                        <rect x="44" y="60" width="12" height="24" fill="#f59e0b"/>
                        <rect x="14" y="83" width="72" height="5" rx="2.5" fill="#f59e0b"/>
                    </svg>
                </div>
                <div class="leading-tight">
                    <div class="text-[13px] md:text-[15px] font-extrabold tracking-tight text-[#0b3558] group-hover:text-[#e68a00] transition">
                        MINH HOÀNG PHÁT
                    </div>
                    <div class="text-[10px] font-semibold text-[#e68a00] uppercase tracking-wider">
                        Xây Dựng & Thương Mại Dịch Vụ
                    </div>
                </div>
            </a>

            <!-- MENU DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG HOẶC XUỐNG HÀNG 2 NGUYÊN CỤM, KHÔNG GÃY DÒNG TÊN DANH MỤC) -->
            <nav class="hidden lg:block flex-1">
                <ul class="desktop-nav-list">
                    <li>
                        <a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a>
                    </li>
                    <li class="ux-dropdown">
                        <a href="#linh-vuc-hoat-dong" class="desktop-nav-item">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="ux-dropdown-menu">
                            <a href="#linh-vuc-hoat-dong" onclick="filterConstruction('all')">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')">Thi công phần thô</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')">Thi công hoàn thiện</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')">Thi công nội thất</a>
                        </div>
                    </li>
                    <li class="ux-dropdown">
                        <a href="#thi-cong-thuc-te" class="desktop-nav-item">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="ux-dropdown-menu">
                            <a href="#du-an-da-nang" onclick="filterProjects('khach-san')">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('biet-thu')">Biệt thự</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')">Nhà phố</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('van-phong')">Văn phòng</a>
                        </div>
                    </li>
                    <li class="ux-dropdown">
                        <a href="#thi-cong-thuc-te" class="desktop-nav-item">
                            <span>Mẫu thiết kế</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="ux-dropdown-menu">
                            <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')">Mẫu thiết kế nhà phố</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')">Mẫu thiết kế nội thất</a>
                        </div>
                    </li>
                    <li>
                        <a href="#du-an-da-nang" class="desktop-nav-item">Dự án Đà Nẵng</a>
                    </li>
                    <li class="ux-dropdown">
                        <a href="#bang-bao-gia" class="desktop-nav-item">
                            <span>Báo giá</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="ux-dropdown-menu">
                            <a href="#bang-bao-gia">Báo giá thiết kế kiến trúc</a>
                            <a href="#bang-bao-gia">Báo giá thi công phần thô</a>
                            <a href="#bang-bao-gia">Báo giá thi công hoàn thiện</a>
                            <a href="#bang-bao-gia">Báo giá thi công trọn gói</a>
                        </div>
                    </li>
                    <li>
                        <a href="#doi-tac" class="desktop-nav-item">Đối tác</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="desktop-nav-item">Tin tức</a>
                    </li>
                    <li>
                        <a href="#lien-he-map" class="desktop-nav-item">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- NÚT MỞ MENU TRÊN ĐIỆN THOẠI (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#0b3558] text-white text-xs font-semibold shrink-0">
                <i id="mobileMenuIcon" class="fa-solid fa-bars text-sm"></i>
                <span>Danh mục</span>
            </button>
        </div>

        <!-- MENU ĐIỆN THOẠI XỔ XUỐNG GỌN ĐẸP -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="ux-container py-3">
                <div class="grid grid-cols-2 gap-2 text-xs font-semibold">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-house text-[#e68a00]"></i> Trang chủ
                    </a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-building text-[#e68a00]"></i> Giới thiệu
                    </a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-compass-drafting text-[#e68a00]"></i> Lĩnh vực hoạt động
                    </a>
                    <a href="#thi-cong-thuc-te" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-helmet-safety text-[#e68a00]"></i> Công trình thực tế
                    </a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-city text-[#e68a00]"></i> Dự án Đà Nẵng
                    </a>
                    <a href="#bang-bao-gia" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-file-invoice-dollar text-[#e68a00]"></i> Báo giá xây dựng
                    </a>
                    <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-handshake text-[#e68a00]"></i> Đối tác
                    </a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-slate-100 text-[#0b3558] flex items-center gap-2">
                        <i class="fa-solid fa-newspaper text-[#e68a00]"></i> Tin tức
                    </a>
                    <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-[#e68a00] text-white flex items-center gap-2">
                        <i class="fa-solid fa-pen-to-square"></i> Yêu cầu báo giá
                    </a>
                    <a href="#lien-he-map" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-[#0b3558] text-white flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot"></i> Bản đồ & Liên hệ
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== BANNER SLIDER (2 ẢNH TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM TRONG HẾT BANNER & CÁCH XA VIỀN) ==================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="ux-container">
            <div class="ux-banner-wrapper shadow-md">
                
                <!-- SLIDE 1 -->
                <div class="ux-banner-slide active" data-slide="0">
                    <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600';"
                         alt="Thiết kế và Thi công Xây dựng Minh Hoàng Phát Đà Nẵng"
                         class="w-full h-full object-cover object-center">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0b3558]/95 via-[#0b3558]/80 to-[#0b3558]/40"></div>
                    
                    <!-- Nội dung chữ cách xa viền ảnh banner trên cả điện thoại và máy tính -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 py-8 sm:px-16 md:px-24 lg:px-28">
                        <div class="w-full max-w-3xl text-left text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-[#f59e0b] mb-1.5">
                                CÔNG TY TNHH TM DV & XD MINH HOÀNG PHÁT
                            </p>
                            <h1 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2 md:mb-3">
                                Chuyên Thiết Kế – Thi Công Xây Dựng Trọn Gói Tại Đà Nẵng
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-3 md:mb-5 max-w-2xl">
                                Kiến tạo công trình Biệt thự, Nhà phố, Khách sạn, Căn hộ, Văn phòng đạt chuẩn “An Toàn – Chất Lượng – Đúng Tiến Độ – Tối Ưu Chi Phí”.
                            </p>
                            <div class="flex flex-wrap items-center gap-2.5">
                                <a href="#form-bao-gia" class="px-4 py-2 md:px-5 md:py-2.5 rounded-lg bg-[#e68a00] hover:bg-[#d97706] text-white font-bold text-xs md:text-sm transition shadow">
                                    Nhận Báo Giá Ngay
                                </a>
                                <a href="#du-an-da-nang" class="px-4 py-2 md:px-5 md:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs md:text-sm transition">
                                    Xem Dự Án Đà Nẵng
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (KÍCH THƯỚC BẰNG SLIDE 1 TUYỆT ĐỐI) -->
                <div class="ux-banner-slide" data-slide="1">
                    <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600';"
                         alt="Thi Công Phần Thô và Hoàn Thiện Minh Hoàng Phát"
                         class="w-full h-full object-cover object-center">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0b3558]/95 via-[#0b3558]/80 to-[#0b3558]/40"></div>
                    
                    <!-- Nội dung chữ cách xa viền ảnh banner trên cả điện thoại và máy tính -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 py-8 sm:px-16 md:px-24 lg:px-28">
                        <div class="w-full max-w-3xl text-left text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-[#f59e0b] mb-1.5">
                                TIÊU CHUẨN KỸ THUẬT – VẬT TƯ CHÍNH HÃNG 100%
                            </p>
                            <h2 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-2 md:mb-3">
                                Thi Công Phần Thô – Hoàn Thiện – Nội Thất Chuyên Nghiệp
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-3 md:mb-5 max-w-2xl">
                                Trụ sở: 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng. Giám sát chặt chẽ từng hạng mục, bảo hành kết cấu công trình dài hạn.
                            </p>
                            <div class="flex flex-wrap items-center gap-2.5">
                                <a href="#thi-cong-thuc-te" class="px-4 py-2 md:px-5 md:py-2.5 rounded-lg bg-[#e68a00] hover:bg-[#d97706] text-white font-bold text-xs md:text-sm transition shadow">
                                    Hạng Mục Thi Công
                                </a>
                                <a href="tel:0935330198" class="px-4 py-2 md:px-5 md:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs md:text-sm transition">
                                    Hotline: 0935.330.198
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng trái phải nhỏ gọn -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-[#e68a00] text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-[#e68a00] text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chuyển slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-[#f59e0b] transition-all"></button>
                    <button onclick="goToSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC LĨNH VỰC HOẠT ĐỘNG (GIỐNG WEB MẪU TINTRUONGTHINH.COM, CHỮ NHỎ GỌN, 2 CỘT TRÊN ĐIỆN THOẠI) ==================== -->
    <section id="linh-vuc-hoat-dong" class="py-6 md:py-8 bg-white">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Lĩnh Vực Hoạt Động & Danh Mục Dịch Vụ
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Giải pháp toàn diện từ Thiết kế Kiến trúc – Thi công Phần thô – Thi công Hoàn thiện – Thi công Nội thất
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Danh mục 1 -->
                <a href="#thi-cong-thuc-te" onclick="filterConstruction('kien-truc')" class="group bg-slate-50 hover:bg-[#0b3558] border border-slate-200 rounded-xl p-3.5 md:p-5 transition duration-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg bg-[#0b3558] group-hover:bg-[#e68a00] text-white flex items-center justify-center mb-3 transition">
                            <i class="fa-solid fa-compass-drafting text-base md:text-lg"></i>
                        </div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] group-hover:text-white mb-1.5">
                            Thiết Kế Kiến Trúc – Nội Thất
                        </h3>
                        <p class="text-[11px] md:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
                            Thiết kế mặt bằng công năng, phối cảnh 3D nhà phố, biệt thự, căn hộ, văn phòng tối ưu diện tích và phong thủy.
                        </p>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/70 group-hover:border-white/20 text-[11px] font-semibold text-[#e68a00] group-hover:text-[#f59e0b] flex items-center justify-between">
                        <span>Xem hạng mục</span>
                        <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </div>
                </a>

                <!-- Danh mục 2 -->
                <a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')" class="group bg-slate-50 hover:bg-[#0b3558] border border-slate-200 rounded-xl p-3.5 md:p-5 transition duration-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg bg-[#0b3558] group-hover:bg-[#e68a00] text-white flex items-center justify-center mb-3 transition">
                            <i class="fa-solid fa-trowel-bricks text-base md:text-lg"></i>
                        </div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] group-hover:text-white mb-1.5">
                            Thi Công Phần Thô
                        </h3>
                        <p class="text-[11px] md:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
                            Thi công móng, kết cấu bê tông cốt thép, xây tô tường, hệ thống điện nước âm tường chuẩn kỹ thuật xây dựng.
                        </p>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/70 group-hover:border-white/20 text-[11px] font-semibold text-[#e68a00] group-hover:text-[#f59e0b] flex items-center justify-between">
                        <span>Xem hạng mục</span>
                        <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </div>
                </a>

                <!-- Danh mục 3 -->
                <a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')" class="group bg-slate-50 hover:bg-[#0b3558] border border-slate-200 rounded-xl p-3.5 md:p-5 transition duration-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg bg-[#0b3558] group-hover:bg-[#e68a00] text-white flex items-center justify-center mb-3 transition">
                            <i class="fa-solid fa-paint-roller text-base md:text-lg"></i>
                        </div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] group-hover:text-white mb-1.5">
                            Thi Công Hoàn Thiện
                        </h3>
                        <p class="text-[11px] md:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
                            Ốp lát gạch đá, sơn nước nội ngoại thất, đóng trần thạch cao, lắp đặt cửa nhôm kính, lan can và thiết bị vệ sinh.
                        </p>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/70 group-hover:border-white/20 text-[11px] font-semibold text-[#e68a00] group-hover:text-[#f59e0b] flex items-center justify-between">
                        <span>Xem hạng mục</span>
                        <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </div>
                </a>

                <!-- Danh mục 4 -->
                <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="group bg-slate-50 hover:bg-[#0b3558] border border-slate-200 rounded-xl p-3.5 md:p-5 transition duration-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 md:w-12 md:h-12 rounded-lg bg-[#0b3558] group-hover:bg-[#e68a00] text-white flex items-center justify-center mb-3 transition">
                            <i class="fa-solid fa-couch text-base md:text-lg"></i>
                        </div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] group-hover:text-white mb-1.5">
                            Thi Công Nội Thất & Trọn Gói
                        </h3>
                        <p class="text-[11px] md:text-xs text-slate-600 group-hover:text-slate-200 leading-relaxed">
                            Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ, văn phòng, chìa khóa trao tay đồng bộ chuẩn bản vẽ.
                        </p>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/70 group-hover:border-white/20 text-[11px] font-semibold text-[#e68a00] group-hover:text-[#f59e0b] flex items-center justify-between">
                        <span>Xem hạng mục</span>
                        <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU & THẾ MẠNH CỦA CHÚNG TÔI (THEO MẪU TINTRUONGTHINH.COM) ==================== -->
    <section id="gioi-thieu" class="py-7 md:py-10 bg-slate-100/80 border-y border-slate-200">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <!-- Cột thông tin giới thiệu -->
                <div class="lg:col-span-6 bg-white p-5 md:p-7 rounded-xl border border-slate-200 shadow-sm">
                    <p class="text-xs font-bold uppercase tracking-wider text-[#e68a00] mb-1">
                        VỀ CHÚNG TÔI – MINHHOANGPHAT.COM
                    </p>
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0b3558] mb-3 leading-snug">
                        CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ & XÂY DỰNG MINH HOÀNG PHÁT
                    </h2>
                    <p class="text-xs md:text-sm text-slate-600 leading-relaxed mb-3">
                        <strong>MINH HOÀNG PHÁT</strong> chuyên Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất các công trình <strong>Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố</strong> tại Thành phố Đà Nẵng và khu vực miền Trung.
                    </p>
                    <p class="text-xs md:text-sm text-slate-600 leading-relaxed mb-4">
                        Với phương châm <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi dự án bàn giao luôn đạt chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – CHI PHÍ HỢP LÝ</strong>.
                    </p>

                    <div class="grid grid-cols-2 gap-2.5 text-xs mb-4">
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="font-bold text-[#0b3558]">Mã số thuế: 0402086021</div>
                            <div class="text-slate-500 text-[11px] mt-0.5">Pháp lý minh bạch, rõ ràng</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="font-bold text-[#0b3558]">Hotline: 0935.330.198</div>
                            <div class="text-slate-500 text-[11px] mt-0.5">Tư vấn & khảo sát miễn phí 24/7</div>
                        </div>
                    </div>

                    <div class="text-xs text-slate-700 flex items-start gap-2 bg-[#0b3558]/5 p-3 rounded-lg border border-[#0b3558]/15">
                        <i class="fa-solid fa-location-dot text-[#e68a00] mt-0.5"></i>
                        <span><strong>Trụ sở chính:</strong> 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</span>
                    </div>
                </div>

                <!-- Cột 6 thế mạnh chuẩn Tín Trường Thịnh -->
                <div class="lg:col-span-6 grid grid-cols-2 gap-3">
                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-user-tie"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Đội ngũ KTS, Kỹ sư giàu kinh nghiệm
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư chỉ huy công trường và thợ lành nghề lâu năm.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-cubes"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Vật tư chính hãng, công nghệ mới
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Cam kết sử dụng đúng chủng loại vật tư thỏa thuận trong hợp đồng, không phát sinh chi phí.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-clipboard-check"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Giám sát tiến độ chuẩn xác
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Báo cáo hình ảnh nhật ký công trình hàng ngày để Chủ đầu tư dễ dàng theo dõi từ xa.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Bảo hành công trình lâu dài
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Bảo hành kết cấu lên đến 5–10 năm, hỗ trợ bảo trì nhanh chóng với tiêu chí “Gọi đâu có đó”.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-scale-balanced"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Giá cả hợp lý, dự toán chi tiết
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Bóc tách khối lượng minh bạch từng hạng mục, tối ưu ngân sách cho Chủ đầu tư.
                        </p>
                    </div>

                    <div class="bg-white p-3.5 md:p-4 rounded-xl border border-slate-200 shadow-sm">
                        <div class="w-8 h-8 rounded-lg bg-[#0b3558] text-[#f59e0b] flex items-center justify-center mb-2 text-xs">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h3 class="product-card-title text-xs md:text-sm font-bold text-[#0b3558] mb-1">
                            Tư vấn & xin phép xây dựng
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Hỗ trợ trọn gói hồ sơ xin phép xây dựng, bản vẽ thiết kế và thủ tục hoàn công tại Đà Nẵng.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM & HẠNG MỤC THI CÔNG THỰC TẾ (9 ẢNH GOOGLE DRIVE ĐẦU TIÊN - KHÔNG NHÃN DÁN, 2 CỘT TRÊN ĐIỆN THOẠI) ==================== -->
    <section id="thi-cong-thuc-te" class="py-7 md:py-10 bg-white">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Hạng Mục Sản Phẩm & Hình Ảnh Thi Công Thực Tế
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Hình ảnh thực tế thi công xây dựng phần thô, hoàn thiện và nội thất của Minh Hoàng Phát
                </p>
            </div>

            <!-- Bộ lọc danh mục nhỏ gọn, viết liền không xuống dòng -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-6">
                <button onclick="filterConstruction('all')" data-cfilter="all" class="cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-[#0b3558] text-white whitespace-nowrap transition">
                    Tất cả hạng mục
                </button>
                <button onclick="filterConstruction('phan-tho')" data-cfilter="phan-tho" class="cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
                    Thi công phần thô
                </button>
                <button onclick="filterConstruction('hoan-thien')" data-cfilter="hoan-thien" class="cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
                    Thi công hoàn thiện
                </button>
                <button onclick="filterConstruction('kien-truc')" data-cfilter="kien-truc" class="cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
                    Thiết kế Kiến trúc
                </button>
                <button onclick="filterConstruction('noi-that')" data-cfilter="noi-that" class="cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition">
                    Thi công nội thất
                </button>
            </div>

            <!-- Grid sản phẩm/hạng mục thi công: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) - KHÔNG NHÃN DÁN -->
            <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 md:gap-5">
                
                <!-- 1. File: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="phan-tho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w900';"
                             alt="Thi công phần thô nhà phố hiện đại tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công phần thô</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thi Công Phần Thô Nhà Phố Hiện Đại Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Thi công khung kết cấu bê tông cốt thép và xây tường bao chuẩn kỹ thuật xây dựng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 2. File: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="phan-tho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900';"
                             alt="Thi công móng băng và lắp đặt cốt thép dầm sàn"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công phần thô</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thi Công Kết Cấu Móng & Cốt Thép Dầm Sàn
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Gia công lắp dựng cốt thép Hòa Phát/Việt Nhật đúng bản vẽ kết cấu, nghiệm thu chặt chẽ.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 3. File: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="phan-tho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900';"
                             alt="Thi công cốp pha và đổ bê tông sàn công trình"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công phần thô</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thi Công Cốp Pha & Đổ Bê Tông Thương Phẩm
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Đảm bảo độ phẳng, độ sụt bê tông tiêu chuẩn và quy trình bảo dưỡng bê tông đúng kỹ thuật.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 4. File: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="phan-tho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w900';"
                             alt="Thi công xây tô tường và hệ thống điện nước ME"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công phần thô</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Xây Tô Tường & Lắp Đặt Điện Nước Âm Tường
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Xây tường gạch tuynel thẳng đứng, đóng lưới mắt cáo chống nứt và đi ống điện nước chuẩn.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 5. File: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="hoan-thien">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w900';"
                             alt="Thi công hoàn thiện mặt tiền nhà phố và biệt thự"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công hoàn thiện</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thi Công Hoàn Thiện Mặt Tiền Nhà Phố & Biệt Thự
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Sơn bả ngoại thất chống thấm, ốp đá trang trí mặt tiền, lắp đặt hệ cửa nhôm Xingfa và lan can kính.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 6. File: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="hoan-thien">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w900';"
                             alt="Thi công hoàn thiện ốp lát gạch và trần thạch cao"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công hoàn thiện</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Hoàn Thiện Sơn Nước, Ốp Lát & Trần Thạch Cao
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Ốp lát gạch nền chuẩn mạch, đóng trần thạch cao khung xương Vĩnh Tường và hệ đèn LED chiếu sáng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 7. File: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="kien-truc">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900';"
                             alt="Thiết kế kiến trúc nhà phố và căn hộ hiện đại"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thiết kế Kiến trúc – Nội thất</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thiết Kế Kiến Trúc Nhà Phố & Căn Hộ Cho Thuê
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Giải pháp kiến trúc thông tầng, giếng trời đón gió tự nhiên phù hợp khí hậu ven biển Đà Nẵng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 8. File: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="noi-that">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w900';"
                             alt="Thi công nội thất phòng khách và tủ bếp hiện đại"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Thi công nội thất</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Thi Công Nội Thất Phòng Khách, Phòng Bếp & Phòng Ngủ
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Sản xuất và lắp đặt nội thất gỗ MDF chống ẩm An Cường, đá bếp kim sa và phụ kiện cao cấp.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

                <!-- 9. File: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                <div class="construction-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="hoan-thien">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w900"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w900';"
                             alt="Xây nhà trọn gói chìa khóa trao tay tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-[#e68a00] mb-1">Xây nhà trọn gói</div>
                            <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1.5">
                                Xây Nhà Trọn Gói Chìa Khóa Trao Tay Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] md:text-xs text-slate-600 leading-relaxed">
                                Quy trình khép kín từ xin phép xây dựng, thiết kế, thi công phần thô đến hoàn thiện bàn giao.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-flex items-center justify-center w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-[#0b3558] text-[#0b3558] hover:text-white text-xs font-semibold transition">
                            Nhận báo giá hạng mục
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE TIẾP THEO - 2 CỘT TRÊN ĐIỆN THOẠI, KHÔNG NHÃN DÁN) ==================== -->
    <section id="du-an-da-nang" class="py-7 md:py-10 bg-slate-100/80 border-t border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Tổng hợp các công trình Khách sạn, Căn hộ, Biệt thự, Nhà phố, Văn phòng thực tế tại TP. Đà Nẵng
                </p>
            </div>

            <!-- Danh mục lọc Công trình thực tế theo chuẩn tintruongthinh.com -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 md:gap-2 mb-6">
                <button onclick="filterProjects('all')" data-pfilter="all" class="pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-[#0b3558] text-white whitespace-nowrap transition">
                    Tất cả
                </button>
                <button onclick="filterProjects('khach-san')" data-pfilter="khach-san" class="pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 hover:bg-slate-200 border border-slate-200 whitespace-nowrap transition">
                    Khách sạn – Căn hộ – Phòng trọ
                </button>
                <button onclick="filterProjects('biet-thu')" data-pfilter="biet-thu" class="pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 hover:bg-slate-200 border border-slate-200 whitespace-nowrap transition">
                    Biệt thự
                </button>
                <button onclick="filterProjects('nha-pho')" data-pfilter="nha-pho" class="pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 hover:bg-slate-200 border border-slate-200 whitespace-nowrap transition">
                    Nhà phố
                </button>
                <button onclick="filterProjects('van-phong')" data-pfilter="van-phong" class="pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 hover:bg-slate-200 border border-slate-200 whitespace-nowrap transition">
                    Văn phòng
                </button>
            </div>

            <!-- Lưới 10 Dự Án tại Đà Nẵng: 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính (lg:grid-cols-5) -->
            <div id="projectsGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 md:gap-4">
                
                <!-- Dự án 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800';"
                             alt="Nhà Phố Hiện Đại 3 Tầng Khu Đô Thị Hòa Xuân Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Nhà phố Đà Nẵng</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Nhà Phố Hiện Đại 3 Tầng Khu Đô Thị Hòa Xuân – Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Cẩm Lệ, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="khach-san">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800';"
                             alt="Tòa Nhà Căn Hộ Cho Thuê Cao Cấp Sơn Trà Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Khách sạn – Căn hộ</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Tòa Nhà Căn Hộ Cho Thuê Cao Cấp – Sơn Trà, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Sơn Trà, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800';"
                             alt="Biệt Thự Nghỉ Dưỡng 2 Mặt Tiền Ngũ Hành Sơn Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Biệt thự</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Biệt Thự Nghỉ Dưỡng 2 Mặt Tiền – Ngũ Hành Sơn, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Ngũ Hành Sơn, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="khach-san">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                             alt="Khách Sạn & Apartment 6 Tầng Khu Phố Biển Mỹ Khê Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Khách sạn – Căn hộ</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Khách Sạn & Apartment 6 Tầng – Mỹ Khê, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Phước Mỹ, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800';"
                             alt="Nhà Phố Gia Đình Đường Cồn Dầu Hòa Xuân Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Nhà phố Đà Nẵng</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Nhà Phố Gia Đình Đường Cồn Dầu – Hòa Xuân, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Hòa Xuân, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="van-phong">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800';"
                             alt="Thiết Kế Và Thi Công Tòa Nhà Văn Phòng Hải Châu Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Văn phòng</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Thiết Kế & Thi Công Tòa Nhà Văn Phòng – Hải Châu, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Hải Châu, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800';"
                             alt="Nhà Phố Lệch Tầng Khu Đô Thị Nam Việt Á Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Nhà phố Đà Nẵng</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Nhà Phố Lệch Tầng Khu Đô Thị Nam Việt Á – Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Khuê Mỹ, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="khach-san">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800';"
                             alt="Khu Căn Hộ Studio Và Phòng Trọ Cao Cấp Liên Chiểu Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Khách sạn – Căn hộ</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Căn Hộ Studio & Phòng Trọ Cao Cấp – Liên Chiểu, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Liên Chiểu, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800';"
                             alt="Biệt Thự Phố Hiện Đại Khu Đảo VIP Hòa Xuân Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Biệt thự</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Biệt Thự Phố Hiện Đại Khu Đảo VIP Hòa Xuân – Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Hòa Xuân, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                <div class="project-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-pcat="van-phong">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4=w800"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800';"
                             alt="Nhà Phố Kết Hợp Văn Phòng Kinh Doanh Thanh Khê Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-semibold text-[#e68a00] mb-0.5">Nhà phố – Văn phòng</div>
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1">
                                Nhà Phố Kết Hợp Văn Phòng Kinh Doanh – Thanh Khê, Đà Nẵng
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-1.5 border-t border-slate-100">
                            Thanh Khê, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC BẢNG BÁO GIÁ THAM KHẢO (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH) ==================== -->
    <section id="bang-bao-gia" class="py-7 md:py-10 bg-white border-t border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Các Gói Báo Giá Xây Dựng Tại Minh Hoàng Phát
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Đơn giá minh bạch, cam kết vật tư chính hãng và không phát sinh chi phí ngoài hợp đồng
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <div class="bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1">
                            Báo Giá Thiết Kế Kiến Trúc
                        </h3>
                        <div class="text-sm md:text-lg font-extrabold text-[#e68a00] mb-2">
                            120.000đ – 180.000đ/m²
                        </div>
                        <ul class="text-[11px] md:text-xs text-slate-600 space-y-1.5">
                            <li>• Hồ sơ bản vẽ kiến trúc 2D & 3D</li>
                            <li>• Hồ sơ kết cấu & điện nước M&E</li>
                            <li>• Miễn phí 100% khi ký HĐ thi công</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-[#0b3558] hover:bg-[#e68a00] text-white text-xs font-semibold transition">
                        Yêu cầu tư vấn
                    </a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1">
                            Báo Giá Thi Công Phần Thô
                        </h3>
                        <div class="text-sm md:text-lg font-extrabold text-[#e68a00] mb-2">
                            3.600.000đ – 3.900.000đ/m²
                        </div>
                        <ul class="text-[11px] md:text-xs text-slate-600 space-y-1.5">
                            <li>• Vật tư phần thô chuẩn chính hãng</li>
                            <li>• Nhân công hoàn thiện toàn bộ</li>
                            <li>• Bảo hành kết cấu công trình 5 năm</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-[#0b3558] hover:bg-[#e68a00] text-white text-xs font-semibold transition">
                        Yêu cầu tư vấn
                    </a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1">
                            Báo Giá Thi Công Hoàn Thiện
                        </h3>
                        <div class="text-sm md:text-lg font-extrabold text-[#e68a00] mb-2">
                            2.200.000đ – 3.200.000đ/m²
                        </div>
                        <ul class="text-[11px] md:text-xs text-slate-600 space-y-1.5">
                            <li>• Gạch ốp lát, sơn nước Dulux/Jotun</li>
                            <li>• Trần thạch cao, cửa nhôm Xingfa</li>
                            <li>• Thiết bị điện & vệ sinh đồng bộ</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-[#0b3558] hover:bg-[#e68a00] text-white text-xs font-semibold transition">
                        Yêu cầu tư vấn
                    </a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between">
                    <div>
                        <h3 class="product-card-title text-xs sm:text-sm md:text-base font-bold text-[#0b3558] mb-1">
                            Báo Giá Thi Công Trọn Gói
                        </h3>
                        <div class="text-sm md:text-lg font-extrabold text-[#e68a00] mb-2">
                            5.800.000đ – 7.200.000đ/m²
                        </div>
                        <ul class="text-[11px] md:text-xs text-slate-600 space-y-1.5">
                            <li>• Chìa khóa trao tay từ A đến Z</li>
                            <li>• Hỗ trợ xin giấy phép xây dựng</li>
                            <li>• Tặng gói thiết kế kiến trúc & 3D</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-[#0b3558] hover:bg-[#e68a00] text-white text-xs font-semibold transition">
                        Yêu cầu tư vấn
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (THEO MẪU TINTRUONGTHINH.COM) ==================== -->
    <section id="form-bao-gia" class="py-8 md:py-10 bg-[#0b3558] text-white">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Thông tin hỗ trợ báo giá -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-[#f59e0b] mb-1">
                        MIỄN PHÍ TƯ VẤN & KHẢO SÁT TẠI ĐÀ NẴNG
                    </p>
                    <h2 class="text-lg md:text-2xl font-extrabold mb-3 leading-snug">
                        Đăng Ký Yêu Cầu Tư Vấn & Nhận Báo Giá Chi Tiết
                    </h2>
                    <p class="text-xs md:text-sm text-slate-200 leading-relaxed mb-4">
                        Quý khách hàng vui lòng để lại thông tin nhu cầu xây dựng. Kỹ sư trưởng của <strong>Minh Hoàng Phát</strong> sẽ liên hệ tư vấn phương án thiết kế và gửi bảng dự toán chi tiết trong vòng 15 phút.
                    </p>
                    <div class="space-y-2.5 text-xs md:text-sm">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-[#f59e0b] w-5 text-center"></i>
                            <span><strong>Hotline/Zalo:</strong> 0935.330.198</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-location-dot text-[#f59e0b] w-5 text-center"></i>
                            <span><strong>Địa chỉ:</strong> 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-[#f59e0b] w-5 text-center"></i>
                            <span><strong>Website:</strong> minhhoangphat.com</span>
                        </div>
                    </div>
                </div>

                <!-- Form nhập thông tin chuẩn Tín Trường Thịnh -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-5 md:p-6 shadow-lg">
                    <form id="quoteForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3.5">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Họ và tên Quý khách *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm focus:outline-none focus:border-[#0b3558]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Số điện thoại liên hệ *</label>
                                <input type="tel" id="custPhone" required placeholder="Nhập số điện thoại..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm focus:outline-none focus:border-[#0b3558]">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Loại công trình</label>
                                <select id="custType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm bg-white focus:outline-none focus:border-[#0b3558]">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Mức đầu tư dự kiến</label>
                                <select id="custBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm bg-white focus:outline-none focus:border-[#0b3558]">
                                    <option value="Từ 1 - 2 tỷ">Từ 1 - 2 tỷ</option>
                                    <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                                    <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    <option value="Cần tư vấn dự toán">Cần tư vấn dự toán</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Dịch vụ yêu cầu</label>
                                <select id="custService" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm bg-white focus:outline-none focus:border-[#0b3558]">
                                    <option value="Xây nhà trọn gói">Xây nhà trọn gói (Chìa khóa trao tay)</option>
                                    <option value="Thi công phần thô">Thi công phần thô & nhân công hoàn thiện</option>
                                    <option value="Thiết kế Kiến trúc - Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                                    <option value="Thi công hoàn thiện - Nội thất">Thi công hoàn thiện – Nội thất</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0b3558] mb-1">Diện tích & Khu vực xây dựng</label>
                                <input type="text" id="custArea" placeholder="VD: 5x20m, Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-xs md:text-sm focus:outline-none focus:border-[#0b3558]">
                            </div>
                        </div>

                        <button type="submit" class="w-full py-3 px-5 rounded-lg bg-[#e68a00] hover:bg-[#d97706] text-white font-bold text-xs md:text-sm uppercase tracking-wider transition shadow">
                            Gửi Yêu Cầu Báo Giá Ngay
                        </button>

                        <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG - 2 CỘT TRÊN ĐIỆN THOẠI) ==================== -->
    <section id="tin-tuc" class="py-7 md:py-10 bg-white">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Tin Tức & Cẩm Nang Xây Dựng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm xây nhà trọn gói và thiết kế nội thất tại Đà Nẵng
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w700"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w700';"
                                 alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng cách"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1.5">
                                Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Dầm Sàn Đúng Kỹ Thuật
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-relaxed">
                                Quy trình giữ ẩm và bảo dưỡng bê tông sau khi đổ giúp kết cấu đạt cường độ chịu lực tối đa và chống nứt sàn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 text-[11px] font-semibold text-[#e68a00]">
                        Kinh nghiệm thi công
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w700"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w700';"
                                 alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần biết"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1.5">
                                03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Đều Gặp Phải
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-relaxed">
                                Giải pháp kiểm soát ngân sách không phát sinh, lựa chọn vật tư chuẩn và giám sát tiến độ thi công tại Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 text-[11px] font-semibold text-[#e68a00]">
                        Cẩm nang xây nhà
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w700"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w700';"
                                 alt="Thiết kế nội thất là gì Khái niệm và tầm quan trọng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1.5">
                                Thiết Kế Nội Thất Là Gì? Khái Niệm Và Tầm Quan Trọng Cho Tổ Ấm
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-relaxed">
                                Tối ưu hóa không gian sống, ánh sáng tự nhiên và vật liệu nội thất hiện đại giúp nâng tầm giá trị ngôi nhà.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 text-[11px] font-semibold text-[#e68a00]">
                        Kiến trúc & Nội thất
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w700"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w700';"
                                 alt="Thủ tục xin giấy phép xây dựng nhà ở tại Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-card-title text-xs sm:text-sm font-bold text-[#0b3558] mb-1.5">
                                Thủ Tục Xin Cấp Phép Xây Dựng Nhà Phố Tại Đà Nẵng Mới Nhất
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-relaxed">
                                Tổng hợp hồ sơ pháp lý, mật độ xây dựng, chiều cao tầng và thời gian cấp phép xây dựng tại các quận Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 text-[11px] font-semibold text-[#e68a00]">
                        Pháp lý xây dựng
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC & VẬT TƯ CHÍNH HÃNG ==================== -->
    <section id="doi-tac" class="py-6 md:py-8 bg-slate-100 border-t border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Đối Tác & Thương Hiệu Vật Tư Đồng Hành
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Minh Hoàng Phát hợp tác cùng các thương hiệu vật liệu xây dựng và nội thất uy tín hàng đầu Việt Nam
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 5 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center flex flex-col items-center justify-center">
                    <div class="text-sm md:text-base font-extrabold text-[#0b3558]">THÉP HÒA PHÁT</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng tiêu chuẩn</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center flex flex-col items-center justify-center">
                    <div class="text-sm md:text-base font-extrabold text-[#0b3558]">XI MĂNG KIM ĐỈNH</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Bê tông & Xây tô bền vững</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center flex flex-col items-center justify-center">
                    <div class="text-sm md:text-base font-extrabold text-[#0b3558]">SƠN DULUX & JOTUN</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất cao cấp</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center flex flex-col items-center justify-center">
                    <div class="text-sm md:text-base font-extrabold text-[#0b3558]">GỖ AN CƯỜNG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất chính hãng</div>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center flex flex-col items-center justify-center col-span-2 sm:col-span-1">
                    <div class="text-sm md:text-base font-extrabold text-[#0b3558]">PANASONIC & INAX</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện & Vệ sinh</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section id="lien-he-map" class="py-7 md:py-10 bg-white border-t border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base md:text-xl font-extrabold text-[#0b3558] uppercase tracking-wide">
                        Bản Đồ Google Map & Fanpage Minh Hoàng Phát
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs md:text-sm text-slate-500">
                    Địa chỉ trụ sở: 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng – Hotline: 0935.330.198
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- Cột Google Map ngoài trang chủ -->
                <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="p-3.5 bg-[#0b3558] text-white flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs md:text-sm font-bold">
                            <i class="fa-solid fa-map-location-dot text-[#f59e0b]"></i>
                            <span>Bản đồ chỉ đường: 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=26+Con+Dau+23+Hoa+Xuan+Da+Nang" target="_blank" rel="noopener" class="px-2.5 py-1 rounded bg-[#e68a00] text-white text-[11px] font-semibold hover:bg-[#d97706] transition">
                            Mở Google Maps
                        </a>
                    </div>
                    <div class="w-full h-[280px] sm:h-[330px] relative bg-slate-200">
                        <iframe
                            title="Bản đồ Công ty TNHH TM DV & XD Minh Hoàng Phát - 26 Cồn Dầu 23, Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=26%20C%E1%BB%93n%20D%E1%BA%A7u%2023,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage chính thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="p-3.5 bg-[#1877F2] text-white flex items-center justify-between">
                            <div class="flex items-center gap-2 text-xs md:text-sm font-bold">
                                <i class="fa-brands fa-facebook text-base"></i>
                                <span>Fanpage Chính Thức Minh Hoàng Phát</span>
                            </div>
                            <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded">Đang hoạt động</span>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan trên trang chủ -->
                        <div class="p-4">
                            <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm">
                                <div class="h-28 relative overflow-hidden">
                                    <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w900"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w900';"
                                         alt="Ảnh bìa Fanpage Xây Dựng Minh Hoàng Phát"
                                         class="w-full h-full object-cover">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                    <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5 text-white">
                                        <div class="w-11 h-11 rounded-lg bg-[#0b3558] border-2 border-white flex items-center justify-center shrink-0">
                                            <span class="font-extrabold text-xs text-[#f59e0b]">MHP</span>
                                        </div>
                                        <div class="overflow-hidden">
                                            <div class="font-bold text-xs sm:text-sm truncate">Xây Dựng Minh Hoàng Phát Đà Nẵng</div>
                                            <div class="text-[11px] text-slate-200">Thiết kế & Thi công Xây dựng trọn gói</div>
                                        </div>
                                    </div>
                                </div>

                                <div class="p-3.5 space-y-2.5 text-xs text-slate-600">
                                    <p class="leading-relaxed">
                                        Cập nhật hình ảnh công trường thực tế hàng ngày, mẫu nhà phố – biệt thự đẹp tại Đà Nẵng và bảng báo giá xây dựng mới nhất.
                                    </p>
                                    <div class="flex items-center gap-2 text-slate-700 font-medium">
                                        <i class="fa-solid fa-location-dot text-[#e68a00]"></i>
                                        <span>26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</span>
                                    </div>
                                    <div class="flex items-center gap-2 text-slate-700 font-medium">
                                        <i class="fa-solid fa-phone text-[#e68a00]"></i>
                                        <span>Hotline / Zalo: 0935.330.198</span>
                                    </div>
                                    <div class="grid grid-cols-2 gap-2 pt-2">
                                        <a href="https://www.facebook.com" target="_blank" rel="noopener" class="py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-semibold text-center flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-brands fa-facebook-f"></i> Theo dõi Trang
                                        </a>
                                        <a href="https://zalo.me/0935330198" target="_blank" rel="noopener" class="py-2 px-3 rounded-lg bg-[#0b3558] hover:bg-[#154c79] text-white font-semibold text-center flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-solid fa-comment-dots"></i> Nhắn tin tư vấn
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="px-4 pb-4">
                        <div class="p-3 rounded-lg bg-[#0b3558]/5 border border-[#0b3558]/15 text-xs text-[#0b3558] flex items-center justify-between">
                            <span><strong>Website:</strong> minhhoangphat.com</span>
                            <a href="tel:0935330198" class="font-bold text-[#e68a00] hover:underline">Gọi: 0935.330.198</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== FOOTER (CHUẨN FLATSOME / TINTRUONGTHINH.COM) ==================== -->
    <footer class="bg-[#0b3558] text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-[#e68a00]">
        <div class="ux-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/15">
                
                <!-- Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded-lg bg-white flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" viewBox="0 0 100 100" fill="none">
                                <path d="M12 44L50 14L88 44L82 51L50 26L18 51L12 44Z" fill="#e68a00"/>
                                <path d="M22 48L50 27L78 48V84H64V56H36V84H22V48Z" fill="#0b3558"/>
                            </svg>
                        </div>
                        <span class="font-extrabold text-sm md:text-base text-white">
                            CÔNG TY TNHH TM DV & XD MINH HOÀNG PHÁT
                        </span>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Đơn vị uy tín chuyên Thiết kế Kiến trúc – Thi công Phần thô – Thi công Hoàn thiện – Xây nhà trọn gói các công trình Nhà phố, Biệt thự, Căn hộ, Khách sạn, Văn phòng tại Đà Nẵng.
                    </p>
                    <ul class="text-xs space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-[#f59e0b] w-5"></i> <strong>Trụ sở:</strong> 26 Cồn Dầu 23, Phường Hòa Xuân, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-[#f59e0b] w-5"></i> <strong>Hotline:</strong> <a href="tel:0935330198" class="hover:text-[#f59e0b]">0935.330.198</a></li>
                        <li><i class="fa-solid fa-globe text-[#f59e0b] w-5"></i> <strong>Website:</strong> <a href="https://minhhoangphat.com" class="hover:text-[#f59e0b]">minhhoangphat.com</a></li>
                        <li><i class="fa-solid fa-hashtag text-[#f59e0b] w-5"></i> <strong>Mã số thuế:</strong> 0402086021</li>
                    </ul>
                </div>

                <!-- Lĩnh vực hoạt động -->
                <div class="lg:col-span-4 space-y-2">
                    <h3 class="text-xs md:text-sm font-bold uppercase tracking-wider text-[#f59e0b]">
                        Lĩnh Vực Hoạt Động & Dịch Vụ
                    </h3>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-white transition">• Thiết kế Kiến trúc – Nội thất nhà phố, biệt thự</a></li>
                        <li><a href="#thi-cong-thuc-te" class="hover:text-white transition">• Thi công xây dựng phần thô & nhân công hoàn thiện</a></li>
                        <li><a href="#thi-cong-thuc-te" class="hover:text-white transition">• Thi công hoàn thiện công trình dân dụng & thương mại</a></li>
                        <li><a href="#thi-cong-thuc-te" class="hover:text-white transition">• Thi công nội thất trọn gói gỗ công nghiệp & tự nhiên</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-white transition">• Xây dựng Khách sạn – Căn hộ cho thuê – Văn phòng</a></li>
                    </ul>
                </div>

                <!-- Danh mục nhanh -->
                <div class="lg:col-span-3 space-y-2">
                    <h3 class="text-xs md:text-sm font-bold uppercase tracking-wider text-[#f59e0b]">
                        Báo Giá & Hỗ Trợ Khách Hàng
                    </h3>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><a href="#bang-bao-gia" class="hover:text-white transition">• Báo giá thiết kế kiến trúc</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-white transition">• Báo giá thi công phần thô</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-white transition">• Báo giá thi công hoàn thiện</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-white transition">• Báo giá xây nhà trọn gói Đà Nẵng</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">• Đăng ký tư vấn & khảo sát miễn phí</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2">
                <div>Copyright © 2026 CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ & XÂY DỰNG MINH HOÀNG PHÁT (minhhoangphat.com)</div>
                <div>Thiết kế chuẩn giao diện UX Builder Flatsome</div>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
    <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="#lien-he-map" title="Fanpage Facebook Minh Hoàng Phát" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs font-bold">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0935330198" target="_blank" rel="noopener" title="Chat Zalo 0935.330.198" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] flex items-center justify-center text-[10px] font-extrabold">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1">Zalo: 0935.330.198</span>
        </a>

        <!-- Nút Hotline Gọi Ngay -->
        <a href="tel:0935330198" title="Gọi Hotline 0935.330.198" class="pulse-btn flex items-center gap-2 bg-[#e68a00] hover:bg-[#d97706] text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#e68a00] flex items-center justify-center text-xs">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0935.330.198</span>
        </a>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, BỘ LỌC DANH MỤC & FORM BÁO GIÁ ==================== -->
    <script>
        // 1. Điều khiển menu trên điện thoại
        function toggleMobileMenu() {
            const panel = document.getElementById('mobileMenuPanel');
            const icon = document.getElementById('mobileMenuIcon');
            panel.classList.toggle('hidden');
            if (panel.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars text-sm';
            } else {
                icon.className = 'fa-solid fa-xmark text-sm';
            }
        }

        // 2. Điều khiển 2 ảnh Banner tự trượt chuyên nghiệp
        let currentSlide = 0;
        const slides = document.querySelectorAll('.ux-banner-slide');
        const dots = document.querySelectorAll('.banner-dot');
        let slideInterval;

        function showSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            dots.forEach((dot, i) => {
                if (i === currentSlide) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-[#f59e0b] transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeSlide(direction) {
            showSlide(currentSlide + direction);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5000);
        }

        // 3. Bộ lọc Hạng mục thi công thực tế (9 ảnh Google Drive)
        function filterConstruction(category) {
            const items = document.querySelectorAll('.construction-item');
            const buttons = document.querySelectorAll('.cfilter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cfilter') === category) {
                    btn.className = 'cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-[#0b3558] text-white whitespace-nowrap transition';
                } else {
                    btn.className = 'cfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 whitespace-nowrap transition';
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        // 4. Bộ lọc Dự án tại Đà Nẵng (10 ảnh Google Drive)
        function filterProjects(category) {
            const items = document.querySelectorAll('.project-item');
            const buttons = document.querySelectorAll('.pfilter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-pfilter') === category) {
                    btn.className = 'pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-[#0b3558] text-white whitespace-nowrap transition';
                } else {
                    btn.className = 'pfilter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 hover:bg-slate-200 border border-slate-200 whitespace-nowrap transition';
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-pcat');
                if (category === 'all' || itemCat === category) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        // 5. Xử lý gửi Form yêu cầu báo giá trang chủ
        function handleQuoteSubmit(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const type = document.getElementById('custType').value;
            const service = document.getElementById('custService').value;
            const budget = document.getElementById('custBudget').value;
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.innerHTML = 'Cảm ơn Quý khách <strong>' + name + '</strong> (' + phone + ')! Yêu cầu báo giá <strong>' + service + ' - ' + type + '</strong> (' + budget + ') đã được gửi tới <strong>CÔNG TY TNHH TM DV & XD MINH HOÀNG PHÁT</strong>. Kỹ sư của chúng tôi sẽ liên hệ lại ngay qua số <strong>0935.330.198</strong>.';
            msgBox.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        window.onload = function () {
            resetSlideTimer();
        };
    </script>
</body>
</html>
