<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Garage Đại Việt - Trung Tâm Bảo Dưỡng, Sửa Chữa & Cứu Hộ Ô Tô Uy Tín Đà Nẵng - Hội An</title>
    <meta name="description" content="Garage Đại Việt (garagedaiviet.com) - Chuyên sửa chữa máy gầm điện, đồng sơn ô tô, bảo dưỡng định kỳ, chăm sóc xe và cứu hộ 24/7 tại 416 Nguyễn Tất Thành, Phường Hội An Tây, Đà Nẵng. Hotline: 0798.187.689">
    
    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://garagedaiviet.com/">
    <meta property="og:title" content="Garage Đại Việt - Sửa Chữa, Đồng Sơn & Cứu Hộ Ô Tô Uy Tín">
    <meta property="og:description" content="Địa chỉ: 416 Nguyễn Tất Thành, Phường Hội An Tây, Đà Nẵng. Hotline cứu hộ & đặt lịch 24/7: 0798.187.689">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            navy: '#0d2b56',
                            blue: '#15407a',
                            light: '#eef4fb',
                            red: '#d62828',
                            darkred: '#b01e1e',
                            gold: '#f59e0b'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối và không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Container chuẩn 1500px cho máy tính */
        .fs-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .fs-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section kiểu Flatsome Divider */
        .fs-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 18px;
            padding-bottom: 8px;
        }
        .fs-section-title h2 {
            position: relative;
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
            color: #0d2b56;
        }
        .fs-section-title h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #d62828;
        }

        /* Đảm bảo tên danh mục viết liền trên 1 hàng, không bao giờ bị gãy dòng */
        .cat-nowrap {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) và không tràn khung */
        .product-title-full {
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(214, 40, 40, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(214, 40, 40, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(214, 40, 40, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }

        /* Custom Scrollbar gọn gàng */
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #0d2b56;
            border-radius: 3px;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- ==========================================
         1. TOP BAR (FLATSOME TOPBAR)
         ========================================== -->
    <div class="bg-brand-navy text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="fs-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 overflow-hidden">
                <span class="flex items-center gap-1.5 truncate">
                    <i class="fa-solid fa-location-dot text-brand-red shrink-0"></i>
                    <span class="truncate">416 Nguyễn Tất Thành, Phường Hội An Tây, Đà Nẵng</span>
                </span>
                <span class="hidden md:flex items-center gap-1.5 shrink-0">
                    <i class="fa-regular fa-clock text-amber-400"></i>
                    <span>Mở cửa: 24/7 (Cứu hộ & Sửa chữa ngày đêm)</span>
                </span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 shrink-0 ml-auto">
                <a href="https://garagedaiviet.com" class="hover:text-amber-300 transition hidden sm:inline">
                    <i class="fa-solid fa-globe mr-1"></i>garagedaiviet.com
                </a>
                <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="hover:text-amber-300 transition flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i>
                    <span>Fanpage Đại Việt</span>
                </a>
                <a href="https://maps.app.goo.gl/QiMq7fnBbLMVqb4J6" target="_blank" rel="noopener" class="hover:text-amber-300 transition flex items-center gap-1">
                    <i class="fa-solid fa-map-location-dot text-amber-400"></i>
                    <span>Chỉ đường</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2. HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
        <div class="fs-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shadow-xs shrink-0">
                    <img src="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y" 
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y&sz=w300';" 
                         alt="Logo Garage Đại Việt" 
                         class="w-full h-full object-contain">
                </div>
                <div class="leading-tight">
                    <span class="block font-heading font-extrabold text-sm sm:text-base lg:text-lg text-brand-navy tracking-tight">
                        GARAGE ĐẠI VIỆT
                    </span>
                    <span class="block text-[10px] sm:text-[11px] text-brand-red font-semibold">
                        SỬA CHỮA & CỨU HỘ Ô TÔ
                    </span>
                </div>
            </a>

            <!-- Ô tìm kiếm dịch vụ / sản phẩm trên máy tính -->
            <div class="hidden md:flex flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input type="text" id="searchInput" oninput="filterProductsBySearch(this.value)"
                           placeholder="Tìm dịch vụ: đồng sơn, bảo dưỡng, máy gầm, cứu hộ..." 
                           class="w-full pl-3.5 pr-10 py-2 text-xs lg:text-sm bg-slate-100 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy focus:bg-white transition">
                    <button type="button" aria-label="Tìm kiếm" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-brand-navy">
                        <i class="fa-solid fa-magnifying-glass text-sm"></i>
                    </button>
                </div>
            </div>

            <!-- Thông tin địa chỉ & giờ làm việc dạng chữ gọn (Không có nút Gọi Ngay để không tràn viền) -->
            <div class="hidden xl:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-shield-halved text-brand-navy text-base"></i>
                    <div>
                        <strong class="block text-slate-800">Phụ Tùng Chính Hãng</strong>
                        <span>Bảo hành dài hạn uy tín</span>
                    </div>
                </div>
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-screwdriver-wrench text-brand-red text-base"></i>
                    <div>
                        <strong class="block text-slate-800">Kỹ Thuật Viên Giàu Kinh Nghiệm</strong>
                        <span>Chẩn đoán lỗi chuyên sâu</span>
                    </div>
                </div>
            </div>

            <!-- Nút mở Menu trên điện thoại -->
            <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg bg-slate-100 text-brand-navy hover:bg-slate-200 transition shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH (VIẾT LIỀN TRÊN 1 HÀNG HOẶC HÀNG 2, KHÔNG XUỐNG DÒNG TÊN DANH MỤC)
             ========================================== -->
        <nav class="hidden lg:block bg-brand-navy text-white border-t border-brand-blue">
            <div class="fs-container">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1 gap-y-1 py-1.5 text-[11.5px] xl:text-[12.5px] font-semibold">
                    <li>
                        <a href="#trang-chu" class="cat-nowrap px-2.5 py-1.5 rounded bg-brand-red text-white hover:bg-brand-darkred transition">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#dm-dong-son" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-spray-can-sparkles mr-1.5 text-amber-400 text-[11px]"></i>ĐỒNG SƠN Ô TÔ
                        </a>
                    </li>
                    <li>
                        <a href="#dm-may-gam-dien" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-gears mr-1.5 text-amber-400 text-[11px]"></i>SỬA CHỮA MÁY - GẦM - ĐIỆN
                        </a>
                    </li>
                    <li>
                        <a href="#dm-bao-duong" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-oil-can mr-1.5 text-amber-400 text-[11px]"></i>BẢO DƯỠNG ĐỊNH KỲ
                        </a>
                    </li>
                    <li>
                        <a href="#dm-cham-soc" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-car-on mr-1.5 text-amber-400 text-[11px]"></i>CHĂM SÓC & LÀM ĐẸP XE
                        </a>
                    </li>
                    <li>
                        <a href="#dm-phu-tung" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-car-battery mr-1.5 text-amber-400 text-[11px]"></i>PHỤ TÙNG & LỐP Ô TÔ
                        </a>
                    </li>
                    <li>
                        <a href="#dm-cuu-ho" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-truck-pickup mr-1.5 text-amber-400 text-[11px]"></i>CỨU HỘ Ô TÔ 24/7
                        </a>
                    </li>
                    <li>
                        <a href="#hinh-anh-garage" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-images mr-1.5 text-amber-400 text-[11px]"></i>XƯỞNG THỰC TẾ
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-newspaper mr-1.5 text-amber-400 text-[11px]"></i>BÀI VIẾT
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/10 transition">
                            <i class="fa-solid fa-file-signature mr-1.5 text-amber-400 text-[11px]"></i>BÁO GIÁ & LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh Mục xổ xuống trên Điện Thoại -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 shadow-lg">
            <div class="mb-2.5">
                <input type="text" oninput="filterProductsBySearch(this.value)"
                       placeholder="Tìm nhanh dịch vụ, phụ tùng..." 
                       class="w-full px-3 py-2 text-xs bg-slate-100 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy">
            </div>
            <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-brand-navy">
                <a href="#dm-dong-son" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-spray-can-sparkles text-brand-red mr-1.5"></i>Đồng Sơn Ô Tô
                </a>
                <a href="#dm-may-gam-dien" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-gears text-brand-red mr-1.5"></i>Máy - Gầm - Điện
                </a>
                <a href="#dm-bao-duong" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-oil-can text-brand-red mr-1.5"></i>Bảo Dưỡng Định Kỳ
                </a>
                <a href="#dm-cham-soc" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-car-on text-brand-red mr-1.5"></i>Chăm Sóc Làm Đẹp
                </a>
                <a href="#dm-phu-tung" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-car-battery text-brand-red mr-1.5"></i>Phụ Tùng Chính Hãng
                </a>
                <a href="#dm-cuu-ho" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-truck-pickup text-brand-red mr-1.5"></i>Cứu Hộ 24/7
                </a>
                <a href="#hinh-anh-garage" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 border border-slate-200 truncate">
                    <i class="fa-solid fa-warehouse text-brand-red mr-1.5"></i>Ảnh Thực Tế Xưởng
                </a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-brand-red text-white truncate">
                    <i class="fa-solid fa-paper-plane mr-1.5"></i>Nhận Báo Giá Nhanh
                </a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         3. BANNER TỰ TRƯỢT 2 SLIDE KÍCH THƯỚC BẰNG NHAU
            - Thiết kế riêng Banner Máy Tính & Banner Điện Thoại khác nhau
            - Chữ nhỏ gọn nằm hết bên trong ảnh, không tràn viền
         ========================================== -->
    <section id="trang-chu" class="py-3 sm:py-4 bg-white border-b border-slate-200">
        <div class="fs-container">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-navy">

                <!-- ==========================================
                     A. BANNER DÀNH RIÊNG CHO MÁY TÍNH (Desktop >= 768px)
                        2 Slide kích thước bằng nhau tuyệt đối (h-[390px] lg:h-[430px])
                     ========================================== -->
                <div class="hidden md:block relative w-full h-[390px] lg:h-[430px]">
                    
                    <!-- Desktop Slide 1 -->
                    <div data-desktop-slide="0" class="desktop-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img src="https://lh3.googleusercontent.com/d/1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS&sz=w1600';"
                             alt="Xưởng dịch vụ Garage Đại Việt" 
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-r from-[#081d3d]/95 via-[#0d2b56]/85 to-transparent flex items-center">
                            <div class="px-10 lg:px-14 max-w-2xl text-white">
                                <p class="text-amber-400 font-bold text-xs lg:text-sm uppercase tracking-wider mb-2">
                                    TRUNG TÂM KỸ THUẬT & DỊCH VỤ Ô TÔ GARAGE ĐẠI VIỆT
                                </p>
                                <h1 class="font-heading font-extrabold text-xl lg:text-3xl leading-snug mb-3 text-white">
                                    CHUYÊN SỬA CHỮA MÁY GẦM ĐIỆN, ĐỒNG SƠN & BẢO DƯỠNG Ô TÔ
                                </h1>
                                <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4">
                                    Trang thiết bị chẩn đoán hiện đại, phòng sơn tiêu chuẩn, đội ngũ kỹ thuật viên tay nghề cao phục vụ tận tâm tại Đà Nẵng - Hội An.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-5 bg-white/10 p-3 rounded-lg border border-white/15">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-circle-check text-amber-400"></i>
                                        <span>Địa chỉ: 416 Nguyễn Tất Thành, Hội An Tây</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-circle-check text-amber-400"></i>
                                        <span>Hotline / Zalo: 0798.187.689</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-circle-check text-amber-400"></i>
                                        <span>Phụ tùng chính hãng - Báo giá minh bạch</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-circle-check text-amber-400"></i>
                                        <span>Hỗ trợ bảo hiểm thân vỏ các hãng</span>
                                    </div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#form-bao-gia" class="px-5 py-2.5 rounded-lg bg-brand-red hover:bg-brand-darkred text-white font-bold text-xs lg:text-sm transition">
                                        <i class="fa-solid fa-calendar-check mr-1.5"></i>ĐẶT LỊCH & NHẬN BÁO GIÁ
                                    </a>
                                    <a href="#danh-muc-dich-vu" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs lg:text-sm border border-white/30 transition">
                                        XEM DỊCH VỤ CHI TIẾT
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 -->
                    <div data-desktop-slide="1" class="desktop-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img src="https://lh3.googleusercontent.com/d/1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR&sz=w1600';"
                             alt="Dịch vụ Đồng Sơn và Cứu Hộ 24/7 Garage Đại Việt" 
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-r from-[#081d3d]/95 via-[#0d2b56]/85 to-transparent flex items-center">
                            <div class="px-10 lg:px-14 max-w-2xl text-white">
                                <p class="text-amber-400 font-bold text-xs lg:text-sm uppercase tracking-wider mb-2">
                                    DỊCH VỤ CỨU HỘ GIAO THÔNG & ĐỒNG SƠN CÔNG NGHỆ CAO
                                </p>
                                <h2 class="font-heading font-extrabold text-xl lg:text-3xl leading-snug mb-3 text-white">
                                    CỨU HỘ Ô TÔ 24/7 ĐÀ NẴNG - HỘI AN & PHỤC HỒI ĐỒNG SƠN
                                </h2>
                                <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4">
                                    Có mặt nhanh chóng khi xe gặp sự cố trên đường: kích bình ắc quy, thay lốp lưu động, kéo xe về xưởng an toàn bất kể ngày đêm.
                                </p>
                                <div class="grid grid-cols-2 gap-2 text-xs text-slate-100 mb-5 bg-white/10 p-3 rounded-lg border border-white/15">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-truck-fast text-amber-400"></i>
                                        <span>Cứu hộ lưu động 24/24 nhanh chóng</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-spray-can text-amber-400"></i>
                                        <span>Sơn hấp công nghệ chuẩn màu 100%</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-snowflake text-amber-400"></i>
                                        <span>Vệ sinh nội thất, đánh bóng Ceramic</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-phone-volume text-amber-400"></i>
                                        <span>Gọi ngay: 0798.187.689</span>
                                    </div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="tel:0798187689" class="px-5 py-2.5 rounded-lg bg-brand-red hover:bg-brand-darkred text-white font-bold text-xs lg:text-sm transition">
                                        <i class="fa-solid fa-phone-volume mr-1.5"></i>GỌI CỨU HỘ: 0798.187.689
                                    </a>
                                    <a href="https://maps.app.goo.gl/QiMq7fnBbLMVqb4J6" target="_blank" rel="noopener" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs lg:text-sm border border-white/30 transition">
                                        XEM BẢN ĐỒ GARAGE
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ==========================================
                     B. BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Mobile < 768px)
                        2 Slide kích thước bằng nhau (h-[250px] sm:h-[280px]), chữ nhỏ gọn nằm hết trong khung
                     ========================================== -->
                <div class="block md:hidden relative w-full h-[250px] sm:h-[280px]">
                    
                    <!-- Mobile Slide 1 -->
                    <div data-mobile-slide="0" class="mobile-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img src="https://lh3.googleusercontent.com/d/1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E&sz=w800';"
                             alt="Garage Đại Việt Mobile Banner 1" 
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-t from-[#071936]/95 via-[#0d2b56]/85 to-[#0d2b56]/60 p-4 flex flex-col justify-center">
                            <div class="max-w-full">
                                <span class="inline-block text-[10px] font-bold text-amber-300 uppercase tracking-wide mb-1">
                                    GARAGE ĐẠI VIỆT - GARAGEDAIVIET.COM
                                </span>
                                <h2 class="font-heading font-extrabold text-[14px] sm:text-base text-white leading-snug mb-1.5">
                                    SỬA CHỮA MÁY GẦM ĐIỆN - ĐỒNG SƠN - BẢO DƯỠNG Ô TÔ
                                </h2>
                                <p class="text-[11px] text-slate-200 leading-normal mb-2.5">
                                    Chẩn đoán lỗi chính xác, phụ tùng chính hãng, báo giá rõ ràng. Đ/c: 416 Nguyễn Tất Thành, P. Hội An Tây, Đà Nẵng.
                                </p>
                                <div class="flex flex-wrap items-center gap-2">
                                    <a href="#form-bao-gia" class="px-3 py-1.5 rounded bg-brand-red text-white font-bold text-[11px]">
                                        Nhận Báo Giá Nhanh
                                    </a>
                                    <a href="tel:0798187689" class="px-3 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                        SĐT: 0798.187.689
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 -->
                    <div data-mobile-slide="1" class="mobile-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img src="https://lh3.googleusercontent.com/d/1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak&sz=w800';"
                             alt="Garage Đại Việt Mobile Banner 2" 
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-t from-[#071936]/95 via-[#0d2b56]/85 to-[#0d2b56]/60 p-4 flex flex-col justify-center">
                            <div class="max-w-full">
                                <span class="inline-block text-[10px] font-bold text-amber-300 uppercase tracking-wide mb-1">
                                    HỖ TRỢ KHẨN CẤP NGÀY ĐÊM 24/7
                                </span>
                                <h2 class="font-heading font-extrabold text-[14px] sm:text-base text-white leading-snug mb-1.5">
                                    CỨU HỘ Ô TÔ ĐÀ NẴNG - HỘI AN & CHĂM SÓC LÀM ĐẸP XE
                                </h2>
                                <p class="text-[11px] text-slate-200 leading-normal mb-2.5">
                                    Kích bình ắc quy, thay lốp lưu động, kéo xe cứu hộ 24/24, phục hồi xe tai nạn và làm bảo hiểm thân vỏ uy tín.
                                </p>
                                <div class="flex flex-wrap items-center gap-2">
                                    <a href="tel:0798187689" class="px-3 py-1.5 rounded bg-brand-red text-white font-bold text-[11px]">
                                        Gọi Cứu Hộ: 0798.187.689
                                    </a>
                                    <a href="https://maps.app.goo.gl/QiMq7fnBbLMVqb4J6" target="_blank" rel="noopener" class="px-3 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                        Mở Google Map
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide (Trái / Phải & Chấm chỉ báo) -->
                <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToBannerSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         4. DANH MỤC DỊCH VỤ & SẢN PHẨM TRANG CHỦ
            - Chữ danh mục ở trang chủ nhỏ gọn
            - Trên máy tính nằm gọn trên 1 hàng (hoặc hàng 2), tên từng danh mục viết liền trên 1 hàng không xuống dòng
         ========================================== -->
    <section id="danh-muc-dich-vu" class="py-5 bg-white border-b border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">DANH MỤC DỊCH VỤ & SẢN PHẨM</h2>
                <span class="text-[11px] sm:text-xs text-slate-500 hidden sm:inline">Chọn danh mục để xem nhanh</span>
            </div>

            <!-- Danh mục thiết kế tối ưu cho cả máy tính & điện thoại -->
            <div class="flex flex-wrap items-center justify-center lg:justify-between gap-2">
                <a href="#dm-dong-son" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-spray-can-sparkles text-brand-red mr-1.5"></i>
                    <span>Đồng Sơn Ô Tô</span>
                </a>
                <a href="#dm-may-gam-dien" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-gears text-brand-red mr-1.5"></i>
                    <span>Sửa Chữa Máy Gầm Điện</span>
                </a>
                <a href="#dm-bao-duong" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-oil-can text-brand-red mr-1.5"></i>
                    <span>Bảo Dưỡng Định Kỳ</span>
                </a>
                <a href="#dm-cham-soc" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-car-on text-brand-red mr-1.5"></i>
                    <span>Chăm Sóc & Làm Đẹp Xe</span>
                </a>
                <a href="#dm-phu-tung" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-car-battery text-brand-red mr-1.5"></i>
                    <span>Phụ Tùng & Phụ Kiện</span>
                </a>
                <a href="#dm-cuu-ho" class="cat-nowrap flex-1 min-w-[140px] sm:min-w-[165px] justify-center px-3 py-2.5 rounded-lg bg-slate-50 hover:bg-brand-navy text-brand-navy hover:text-white border border-slate-200 transition text-[11.5px] xl:text-[12.5px] font-bold">
                    <i class="fa-solid fa-truck-pickup text-brand-red mr-1.5"></i>
                    <span>Cứu Hộ Giao Thông 24/7</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         5. CÁC SECTION SẢN PHẨM / DỊCH VỤ THEO WEB MẪU (GARAGEOTODANANG.COM.VN)
            - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
            - Không để các nhãn dán (badge) ở trang chủ
            - Tên sản phẩm hiển thị trọn vẹn, không tràn ra ngoài hoặc thiếu chữ
            - Lồng ghép chuẩn 7 ảnh thực tế sản phẩm/dịch vụ từ Google Drive
         ========================================== -->

    <!-- DANH MỤC 1: ĐỒNG SƠN & PHỤC HỒI THÂN VỎ Ô TÔ -->
    <section id="dm-dong-son" class="py-6">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">1. ĐỒNG SƠN & PHỤC HỒI THÂN VỎ Ô TÔ</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand-red hover:underline cat-nowrap">
                    Nhận báo giá đồng sơn <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- SP 1 (Ảnh thực tế Drive #1) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1jExzF72wBtUtRnMLuPbChR_xIO2amiqy" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jExzF72wBtUtRnMLuPbChR_xIO2amiqy&sz=w800';"
                                 alt="Dịch vụ sơn dặm, sơn quây nguyên xe ô tô" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Sơn Dặm & Sơn Quây Nguyên Xe Ô Tô Công Nghệ Phòng Sơn Hấp
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Pha màu vi tính chuẩn 100% theo mã màu gốc của hãng, bề mặt sơn bóng đẹp, bền màu.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Sơn Dặm & Sơn Quây Nguyên Xe Ô Tô')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 2 (Ảnh thực tế Drive #2) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1RyKTw2bLOOM1PRi1lpLvlPdfRtk1Jiuu" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1RyKTw2bLOOM1PRi1lpLvlPdfRtk1Jiuu&sz=w800';"
                                 alt="Gò hàn phục hồi thân vỏ xe ô tô va quệt" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Gò Hàn Phục Hồi Thân Vỏ Xe Ô Tô Bị Móp Méo, Trầy Xước, Va Quệt
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Nắn kéo khung sườn bằng máy chuyên dụng, lấy lại form dáng nguyên bản của nhà sản xuất.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Gò Hàn Phục Hồi Thân Vỏ Xe Ô Tô')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 3 (Ảnh thực tế Drive #3) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/19FKSSFk_7mhto7FhTzZSajWCLP2X7oby" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=19FKSSFk_7mhto7FhTzZSajWCLP2X7oby&sz=w800';"
                                 alt="Đánh bóng hiệu chỉnh bề mặt sơn và phủ Ceramic" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Đánh Bóng Hiệu Chỉnh Bề Mặt Sơn & Phủ Bảo Vệ Ceramic Ô Tô
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Xóa vết xước dăm, vết ố mờ, tạo hiệu ứng lá sen chống bám nước và tăng độ bóng sâu.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Đánh Bóng Hiệu Chỉnh Sơn & Phủ Ceramic')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 4 (Ảnh thực tế Xưởng Drive) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS&sz=w800';"
                                 alt="Sơn phủ gầm chống rỉ sét và cách âm hốc lốp" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Sơn Phủ Gầm Chống Rỉ Sét, Chống Đá Văng & Hỗ Trợ Bảo Hiểm Thân Vỏ
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Bảo vệ khung gầm khỏi oxy hóa vùng biển Đà Nẵng - Hội An, hỗ trợ hồ sơ bảo hiểm nhanh.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Sơn Phủ Gầm Chống Rỉ & Bảo Hiểm Thân Vỏ')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- DANH MỤC 2: SỬA CHỮA MÁY - GẦM - ĐIỆN Ô TÔ -->
    <section id="dm-may-gam-dien" class="py-6 bg-white border-y border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">2. SỬA CHỮA MÁY - GẦM - ĐIỆN - ĐIỀU HÒA Ô TÔ</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand-red hover:underline cat-nowrap">
                    Tư vấn kỹ thuật <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- SP 5 (Ảnh thực tế Drive #4) -->
                <div class="product-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1YtTIphRGiKQBwQyQYWfxv1FnMr4lZgqJ" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YtTIphRGiKQBwQyQYWfxv1FnMr4lZgqJ&sz=w800';"
                                 alt="Chẩn đoán và đại tu động cơ, hộp số ô tô" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Kiểm Tra, Chẩn Đoán & Đại Tu Động Cơ - Hộp Số Tự Động Ô Tô
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Xử lý triệt để hiện tượng hao nhớt, sôi nước, rung giật động cơ và lỗi chuyển số.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-200 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Đại Tu Động Cơ & Hộp Số Ô Tô')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 6 (Ảnh thực tế Drive #5) -->
                <div class="product-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1SjGfDH-v0IXOcqtUZmiOgF1A3neJyzUB" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1SjGfDH-v0IXOcqtUZmiOgF1A3neJyzUB&sz=w800';"
                                 alt="Sửa chữa hệ thống khung gầm, phuộc nhún, thước lái" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Sửa Chữa Hệ Thống Gầm Bệ, Thước Lái, Giảm Xóc & Hệ Thống Phanh ABS
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Khắc phục tiếng kêu lục cục dưới gầm, lệch lái, bảo dưỡng rotuyn, cao su càng A, phanh đĩa.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-200 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Sửa Chữa Gầm Bệ, Thước Lái & Phanh')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 7 (Ảnh thực tế Drive #6) -->
                <div class="product-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1wp3WJ9iO4ufpA6A22OrlsJ5NgkX3elAr" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wp3WJ9iO4ufpA6A22OrlsJ5NgkX3elAr&sz=w800';"
                                 alt="Sửa chữa điện điều hòa máy lạnh ô tô" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Sửa Chữa Điện - Điện Lạnh Ô Tô, Vệ Sinh Giàn Lạnh & Nạp Gas Điều Hòa
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Kiểm tra lốc lạnh, dàn nóng, rò rỉ gas, nạp gas lạnh chính hãng giúp điều hòa mát sâu.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-200 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Sửa Chữa Điện Lạnh & Nạp Gas Điều Hòa')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 8 (Ảnh thực tế Drive #7) -->
                <div class="product-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1L8VAGXP8N-TW-sUwo0WxzjH6D6GUFXSU" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1L8VAGXP8N-TW-sUwo0WxzjH6D6GUFXSU&sz=w800';"
                                 alt="Đọc xóa lỗi ECU bằng máy chẩn đoán chuyên hãng" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Đọc Xóa Lỗi Hệ Thống Điện Tử ECU, Cảm Biến, Túi Khí & Máy Phát Điện
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Sử dụng máy test lỗi OBD chuyên sâu cho các dòng xe Nhật, Hàn, Đức, Mỹ đời mới.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-200 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                        <button type="button" onclick="selectServiceForQuote('Đọc Xóa Lỗi Điện Tử ECU & Cảm Biến')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- DANH MỤC 3 & 4: BẢO DƯỠNG ĐỊNH KỲ & CHĂM SÓC XE + PHỤ TÙNG + CỨU HỘ 24/7 -->
    <section id="dm-bao-duong" class="py-6">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">3. BẢO DƯỠNG ĐỊNH KỲ, CHĂM SÓC XE, PHỤ TÙNG & CỨU HỘ 24/7</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand-red hover:underline cat-nowrap">
                    Đặt lịch bảo dưỡng <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- SP 9 -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR&sz=w800';"
                                 alt="Bảo dưỡng ô tô định kỳ các cấp" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Bảo Dưỡng Ô Tô Định Kỳ Đủ Các Cấp 5.000Km - 40.000Km - 100.000Km
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Thay dầu nhớt máy, lọc nhớt, lọc gió động cơ, lọc điều hòa, vệ sinh kim phun buồng đốt.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Từ 450.000đ</span>
                        <button type="button" onclick="selectServiceForQuote('Bảo Dưỡng Ô Tô Định Kỳ')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 10: Chăm sóc xe -->
                <div id="dm-cham-soc" class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E&sz=w800';"
                                 alt="Vệ sinh khoang máy và dọn nội thất ô tô" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Vệ Sinh Khoang Máy Hơi Nước Nóng & Dọn Nội Thất Khử Mùi Toàn Diện
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Làm sạch sâu ghế da, trần sàn, taplo và khoang động cơ bằng dung dịch chuyên dụng an toàn.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Từ 500.000đ</span>
                        <button type="button" onclick="selectServiceForQuote('Vệ Sinh Khoang Máy & Dọn Nội Thất')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 11: Phụ tùng & Ắc quy -->
                <div id="dm-phu-tung" class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak&sz=w800';"
                                 alt="Thay bình ắc quy, lốp xe và phụ tùng ô tô chính hãng" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Cung Cấp & Thay Thế Bình Ắc Quy, Lốp Ô Tô, Má Phanh, Phụ Tùng Chính Hãng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Sẵn có phụ tùng chính hãng Toyota, Hyundai, Kia, Mazda, Ford, Mitsubishi, Honda, VinFast.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">Giá chính hãng</span>
                        <button type="button" onclick="selectServiceForQuote('Thay Bình Ắc Quy, Lốp & Phụ Tùng Chính Hãng')" class="px-2.5 py-1.5 rounded bg-brand-navy hover:bg-brand-blue text-white text-[11px] font-semibold transition shrink-0">
                            Đặt lịch
                        </button>
                    </div>
                </div>

                <!-- SP 12: Cứu hộ ô tô 24/7 -->
                <div id="dm-cuu-ho" class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1jExzF72wBtUtRnMLuPbChR_xIO2amiqy" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jExzF72wBtUtRnMLuPbChR_xIO2amiqy&sz=w800';"
                                 alt="Cứu hộ giao thông ô tô 24/7 Đà Nẵng Hội An" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Cứu Hộ Giao Thông Ô Tô 24/7 Đà Nẵng - Hội An, Kích Bình & Vá Lốp Lưu Động
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal">
                                Hỗ trợ khẩn cấp 24/24 khi xe chết máy, hết bình, nổ lốp hoặc tai nạn trên mọi tuyến đường.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold text-brand-red">0798.187.689</span>
                        <a href="tel:0798187689" class="px-2.5 py-1.5 rounded bg-brand-red hover:bg-brand-darkred text-white text-[11px] font-semibold transition shrink-0">
                            Gọi ngay
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         6. HÌNH ẢNH THỰC TẾ XƯỞNG GARAGE ĐẠI VIỆT (4 ẢNH GARAGE + ẢNH DỊCH VỤ THỰC TẾ)
         ========================================== -->
    <section id="hinh-anh-garage" class="py-6 bg-white border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">HÌNH ẢNH THỰC TẾ TẠI XƯỞNG GARAGE ĐẠI VIỆT</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">416 Nguyễn Tất Thành, P. Hội An Tây, Đà Nẵng</span>
            </div>

            <!-- 4 Ảnh thực tế Garage -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 mb-4">
                <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS&sz=w800';"
                             alt="Không gian xưởng Garage Đại Việt 1" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <p class="p-2 text-center text-xs font-semibold text-brand-navy">Khu vực tiếp nhận & sửa chữa chung</p>
                </div>

                <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1D5UIm4NtzIDUiAPJJQMqCKxlcln9CvnR&sz=w800';"
                             alt="Không gian xưởng Garage Đại Việt 2" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <p class="p-2 text-center text-xs font-semibold text-brand-navy">Cầu nâng kiểm tra máy gầm chuyên dụng</p>
                </div>

                <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1oBxsnz2rpav9anq3wnNFOfI_ll3d8x7E&sz=w800';"
                             alt="Không gian xưởng Garage Đại Việt 3" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <p class="p-2 text-center text-xs font-semibold text-brand-navy">Khu vực đồng sơn & phục hồi thân vỏ</p>
                </div>

                <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1gkwl7bHdQDjvc9MgIrI8AjCiJlK4U6Ak&sz=w800';"
                             alt="Không gian xưởng Garage Đại Việt 4" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <p class="p-2 text-center text-xs font-semibold text-brand-navy">Đội ngũ kỹ thuật viên làm việc thực tế</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         7. FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAP TRANG CHỦ
            (3 Cột trực quan kiểu Flatsome Row)
         ========================================== -->
    <section id="form-bao-gia" class="py-7 bg-slate-100 border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">YÊU CẦU BÁO GIÁ - KẾT NỐI FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI</h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-5">
                
                <!-- CỘT 1: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-xs">
                    <div class="flex items-center gap-2.5 mb-3 pb-2.5 border-b border-slate-100">
                        <div class="w-9 h-9 rounded-lg bg-brand-red text-white flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-file-invoice-dollar"></i>
                        </div>
                        <div>
                            <h3 class="font-heading font-bold text-sm sm:text-base text-brand-navy">FORM YÊU CẦU & BÁO GIÁ</h3>
                            <p class="text-[11px] text-slate-500">Phản hồi nhanh qua điện thoại / Zalo trong 5 phút</p>
                        </div>
                    </div>

                    <form id="quoteForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3 text-xs sm:text-sm">
                        <div>
                            <label class="block font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                            <input type="text" id="qName" required placeholder="Nhập họ tên của bạn" 
                                   class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5">
                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="VD: 0905xxxxxx" 
                                       class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-700 mb-1">Dòng xe & Đời xe</label>
                                <input type="text" id="qCar" placeholder="VD: Mazda 3, Vios, CX5..." 
                                       class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy">
                            </div>
                        </div>
                        <div>
                            <label class="block font-semibold text-slate-700 mb-1">Danh mục cần tư vấn / báo giá *</label>
                            <select id="qService" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy bg-white">
                                <option value="Đồng Sơn & Phục Hồi Thân Vỏ">Đồng Sơn & Phục Hồi Thân Vỏ</option>
                                <option value="Sửa Chữa Máy - Gầm - Điện">Sửa Chữa Máy - Gầm - Điện</option>
                                <option value="Bảo Dưỡng Ô Tô Định Kỳ">Bảo Dưỡng Ô Tô Định Kỳ</option>
                                <option value="Sửa Chữa Điện Lạnh Điều Hòa">Sửa Chữa Điện Lạnh Điều Hòa</option>
                                <option value="Chăm Sóc Xe & Đánh Bóng Ceramic">Chăm Sóc Xe & Đánh Bóng Ceramic</option>
                                <option value="Thay Bình Ắc Quy, Lốp & Phụ Tùng">Thay Bình Ắc Quy, Lốp & Phụ Tùng</option>
                                <option value="Cứu Hộ Giao Thông 24/7">Cứu Hộ Giao Thông 24/7</option>
                            </select>
                        </div>
                        <div>
                            <label class="block font-semibold text-slate-700 mb-1">Mô tả tình trạng xe / Yêu cầu chi tiết</label>
                            <textarea id="qNote" rows="2" placeholder="Nhập tình trạng xe hoặc phụ tùng cần báo giá..." 
                                      class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:outline-none focus:border-brand-navy"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 rounded-lg bg-brand-red hover:bg-brand-darkred text-white font-bold transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i>
                            <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                        </button>
                    </form>

                    <!-- Hộp thông báo gửi thành công -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs">
                        <p class="font-bold mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá!</p>
                        <p id="quoteSummaryText" class="mb-2"></p>
                        <a href="https://zalo.me/0798187689" target="_blank" rel="noopener" class="inline-block px-3 py-1.5 rounded bg-emerald-600 text-white font-semibold">
                            Chat Zalo 0798.187.689 ngay
                        </a>
                    </div>
                </div>

                <!-- CỘT 2: ĐƯA FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ -->
                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-2.5 mb-3 pb-2.5 border-b border-slate-100">
                            <div class="w-9 h-9 rounded-lg bg-[#1877F2] text-white flex items-center justify-center shrink-0">
                                <i class="fa-brands fa-facebook-f text-lg"></i>
                            </div>
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand-navy">FANPAGE FACEBOOK CHÍNH THỨC</h3>
                                <p class="text-[11px] text-slate-500">Cập nhật hoạt động sửa chữa hằng ngày</p>
                            </div>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan + Nhúng Facebook -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 mb-3">
                            <div class="relative h-36 w-full overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_l_8GOd37VPsNYzMPyCf1w9zS_FioCRS&sz=w800';"
                                     alt="Ảnh bìa Fanpage Garage Đại Việt" 
                                     class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent p-3 flex items-end gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y" 
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y&sz=w200';"
                                         alt="Avatar Fanpage" 
                                         class="w-12 h-12 rounded-lg border-2 border-white bg-white object-contain shrink-0">
                                    <div class="text-white overflow-hidden">
                                        <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="font-bold text-sm hover:underline block truncate">
                                            Garage Đại Việt - Sửa Chữa & Cứu Hộ Ô Tô
                                        </a>
                                        <span class="text-[11px] text-slate-200 block">facebook.com/vonguyenthanhhue1906</span>
                                    </div>
                                </div>
                            </div>

                            <div class="p-3 text-xs text-slate-600 space-y-2">
                                <p class="font-medium text-slate-800">
                                    <i class="fa-solid fa-circle-check text-[#1877F2] mr-1"></i>
                                    Chuyên Đồng Sơn - Máy Gầm Điện - Bảo Dưỡng - Cứu Hộ 24/7 tại 416 Nguyễn Tất Thành, Hội An Tây, Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-3 gap-1.5 pt-1">
                                    <img src="https://lh3.googleusercontent.com/d/1jExzF72wBtUtRnMLuPbChR_xIO2amiqy" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jExzF72wBtUtRnMLuPbChR_xIO2amiqy&sz=w300';" alt="Ảnh bài đăng 1" class="h-16 w-full object-cover rounded">
                                    <img src="https://lh3.googleusercontent.com/d/1RyKTw2bLOOM1PRi1lpLvlPdfRtk1Jiuu" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1RyKTw2bLOOM1PRi1lpLvlPdfRtk1Jiuu&sz=w300';" alt="Ảnh bài đăng 2" class="h-16 w-full object-cover rounded">
                                    <img src="https://lh3.googleusercontent.com/d/19FKSSFk_7mhto7FhTzZSajWCLP2X7oby" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=19FKSSFk_7mhto7FhTzZSajWCLP2X7oby&sz=w300';" alt="Ảnh bài đăng 3" class="h-16 w-full object-cover rounded">
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 gap-2.5">
                        <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs text-center transition flex items-center justify-center gap-1.5">
                            <i class="fa-brands fa-facebook"></i>
                            <span>Truy Cập Fanpage</span>
                        </a>
                        <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="py-2.5 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-brand-navy font-bold text-xs text-center border border-slate-300 transition flex items-center justify-center gap-1.5">
                            <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i>
                            <span>Nhắn Tin Ngay</span>
                        </a>
                    </div>
                </div>

                <!-- CỘT 3: ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-2.5 mb-3 pb-2.5 border-b border-slate-100">
                            <div class="w-9 h-9 rounded-lg bg-emerald-600 text-white flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-map-location-dot text-lg"></i>
                            </div>
                            <div>
                                <h3 class="font-heading font-bold text-sm sm:text-base text-brand-navy">BẢN ĐỒ GOOGLE MAPS GARAGE</h3>
                                <p class="text-[11px] text-slate-500">416 Nguyễn Tất Thành, P. Hội An Tây, Đà Nẵng</p>
                            </div>
                        </div>

                        <!-- Bản đồ Google Map trực tiếp + Thẻ địa chỉ -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 mb-3 bg-slate-100">
                            <iframe 
                                title="Bản đồ Garage Đại Việt 416 Nguyễn Tất Thành"
                                src="https://maps.google.com/maps?q=416%20Nguy%E1%BB%85n%20T%E1%BA%A5t%20Th%C3%A0nh,%20H%E1%BB%99i%20An,%20Qu%E1%BA%A3ng%20Nam&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-52 border-0" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                            <div class="p-2.5 bg-slate-50 border-t border-slate-200 text-xs text-slate-700 flex items-start gap-2">
                                <i class="fa-solid fa-location-dot text-brand-red mt-0.5 shrink-0"></i>
                                <div>
                                    <strong class="block text-brand-navy">Cứu Hộ Ô Tô Garage Đại Việt</strong>
                                    <span>416 Nguyễn Tất Thành, Phường Hội An Tây, Đà Nẵng (Mở cửa 24/24)</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <a href="https://maps.app.goo.gl/QiMq7fnBbLMVqb4J6" target="_blank" rel="noopener" class="w-full py-2.5 px-4 rounded-lg bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs sm:text-sm text-center transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-diamond-turn-right"></i>
                        <span>MỞ CHỈ ĐƯỜNG TRÊN GOOGLE MAPS</span>
                    </a>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         8. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM Ô TÔ)
         ========================================== -->
    <section id="tin-tuc" class="py-6 bg-white border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">DANH MỤC BÀI VIẾT & KINH NGHIỆM CHĂM SÓC Ô TÔ</h2>
                <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="text-xs font-semibold text-brand-red hover:underline cat-nowrap">
                    Xem thêm bài viết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <!-- Thanh danh mục bài viết nhỏ gọn, không xuống dòng tên danh mục -->
            <div class="flex flex-wrap items-center gap-2 mb-4">
                <button type="button" onclick="filterBlog('all', this)" class="blog-tab cat-nowrap px-3 py-1.5 rounded-lg bg-brand-navy text-white text-xs font-semibold transition">
                    Tất cả bài viết
                </button>
                <button type="button" onclick="filterBlog('bao-duong', this)" class="blog-tab cat-nowrap px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold transition">
                    Kinh nghiệm bảo dưỡng
                </button>
                <button type="button" onclick="filterBlog('dong-son', this)" class="blog-tab cat-nowrap px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold transition">
                    Kỹ thuật đồng sơn
                </button>
                <button type="button" onclick="filterBlog('cuu-ho', this)" class="blog-tab cat-nowrap px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold transition">
                    Cứu hộ & Xử lý sự cố
                </button>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article data-blog-cat="bao-duong" class="blog-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1YtTIphRGiKQBwQyQYWfxv1FnMr4lZgqJ" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YtTIphRGiKQBwQyQYWfxv1FnMr4lZgqJ&sz=w600';"
                                 alt="Các mốc bảo dưỡng ô tô định kỳ quan trọng" 
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <span class="text-[11px] font-semibold text-brand-red block mb-1">Kinh nghiệm bảo dưỡng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Các Mốc Bảo Dưỡng Ô Tô Định Kỳ Quan Trọng Chủ Xe Cần Nhớ Để Máy Bền Bỉ
                            </h3>
                            <p class="text-xs text-slate-600 leading-normal">
                                Hướng dẫn chi tiết lịch thay dầu máy, lọc nhớt, lọc gió, nước làm mát và dầu hộp số theo từng cấp số km.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-2 border-t border-slate-200/70 flex items-center justify-between text-[11px] text-slate-500">
                        <span>Garage Đại Việt</span>
                        <a href="#form-bao-gia" class="font-semibold text-brand-navy hover:text-brand-red">Tư vấn ngay →</a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article data-blog-cat="dong-son" class="blog-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1jExzF72wBtUtRnMLuPbChR_xIO2amiqy" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jExzF72wBtUtRnMLuPbChR_xIO2amiqy&sz=w600';"
                                 alt="Quy trình đồng sơn ô tô chuẩn màu" 
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <span class="text-[11px] font-semibold text-brand-red block mb-1">Kỹ thuật đồng sơn</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Quy Trình Sơn Dặm & Sơn Quây Ô Tô Chuẩn Màu Hãng Tại Garage Đại Việt
                            </h3>
                            <p class="text-xs text-slate-600 leading-normal">
                                Từ khâu làm nền, bả matit, pha sơn vi tính đến phun sơn phòng hấp giúp bề mặt sơn bóng sâu và không lệch màu.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-2 border-t border-slate-200/70 flex items-center justify-between text-[11px] text-slate-500">
                        <span>Garage Đại Việt</span>
                        <a href="#form-bao-gia" class="font-semibold text-brand-navy hover:text-brand-red">Tư vấn ngay →</a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article data-blog-cat="bao-duong" class="blog-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1wp3WJ9iO4ufpA6A22OrlsJ5NgkX3elAr" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wp3WJ9iO4ufpA6A22OrlsJ5NgkX3elAr&sz=w600';"
                                 alt="Dấu hiệu điều hòa ô tô cần bảo dưỡng" 
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <span class="text-[11px] font-semibold text-brand-red block mb-1">Kinh nghiệm bảo dưỡng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                5 Dấu Hiệu Cho Thấy Hệ Thống Điều Hòa Ô Tô Đang Thiếu Gas Hoặc Nghẹt Lọc
                            </h3>
                            <p class="text-xs text-slate-600 leading-normal">
                                Cách nhận biết sớm điều hòa làm lạnh yếu, có mùi hôi để vệ sinh giàn lạnh và bảo vệ lốc điều hòa kịp thời.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-2 border-t border-slate-200/70 flex items-center justify-between text-[11px] text-slate-500">
                        <span>Garage Đại Việt</span>
                        <a href="#form-bao-gia" class="font-semibold text-brand-navy hover:text-brand-red">Tư vấn ngay →</a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article data-blog-cat="cuu-ho" class="blog-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                            <img src="https://lh3.googleusercontent.com/d/1L8VAGXP8N-TW-sUwo0WxzjH6D6GUFXSU" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1L8VAGXP8N-TW-sUwo0WxzjH6D6GUFXSU&sz=w600';"
                                 alt="Kinh nghiệm xử lý khi xe chết máy giữa đường" 
                                 class="w-full h-full object-cover">
                        </div>
                        <div class="p-3.5">
                            <span class="text-[11px] font-semibold text-brand-red block mb-1">Cứu hộ & Xử lý sự cố</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-brand-navy mb-1.5">
                                Lưu Ngay Số Cứu Hộ Ô Tô 24/7 Đà Nẵng - Hội An (0798.187.689) Khi Xe Gặp Sự Cố
                            </h3>
                            <p class="text-xs text-slate-600 leading-normal">
                                Những việc cần làm ngay để đảm bảo an toàn khi xe hết bình ắc quy, thủng lốp hoặc báo đèn cảnh báo đỏ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-2 border-t border-slate-200/70 flex items-center justify-between text-[11px] text-slate-500">
                        <span>Garage Đại Việt</span>
                        <a href="tel:0798187689" class="font-semibold text-brand-red hover:underline">Gọi 0798.187.689</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         9. DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
         ========================================== -->
    <section id="doi-tac" class="py-6 bg-slate-50 border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <h2 class="text-sm sm:text-base lg:text-lg">ĐỐI TÁC PHỤ TÙNG & BẢO HIỂM LIÊN KẾT</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Cam kết sản phẩm & dịch vụ chính hãng</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-navy">CASTROL</span>
                    <span class="text-[10px] text-slate-500">Dầu nhớt động cơ</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-red">MOBIL 1</span>
                    <span class="text-[10px] text-slate-500">Dầu nhớt cao cấp</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-navy">BOSCH</span>
                    <span class="text-[10px] text-slate-500">Phụ tùng & Ắc quy</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-red">DENSO</span>
                    <span class="text-[10px] text-slate-500">Điện lạnh & Bugi</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-navy">MICHELIN</span>
                    <span class="text-[10px] text-slate-500">Lốp xe chính hãng</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-red">3M AUTO</span>
                    <span class="text-[10px] text-slate-500">Vật tư chăm sóc xe</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-navy">BẢO VIỆT</span>
                    <span class="text-[10px] text-slate-500">Bảo hiểm liên kết</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center hover:border-brand-navy transition">
                    <span class="font-heading font-extrabold text-sm text-brand-red">PVI / PTI</span>
                    <span class="text-[10px] text-slate-500">Bảo hiểm thân vỏ</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         10. FOOTER CHUẨN FLATSOME
         ========================================== -->
    <footer class="bg-brand-navy text-slate-200 pt-8 pb-20 lg:pb-8 border-t-4 border-brand-red">
        <div class="fs-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10 text-xs sm:text-sm">
                
                <!-- Cột 1: Thông tin Garage Đại Việt -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uWUxfe4Kn-aztdjrSeP2q3gxFsyrIV9y&sz=w200';"
                             alt="Logo Garage Đại Việt" 
                             class="w-10 h-10 rounded-lg bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <h3 class="font-heading font-extrabold text-white text-base">GARAGE ĐẠI VIỆT</h3>
                            <span class="text-[11px] text-amber-400">garagedaiviet.com</span>
                        </div>
                    </div>
                    <p class="text-slate-300 text-xs leading-relaxed mb-3">
                        Trung tâm sửa chữa, đồng sơn, bảo dưỡng, chăm sóc ô tô và cứu hộ giao thông 24/7 uy tín hàng đầu tại khu vực Đà Nẵng - Hội An.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
                            <span>Địa chỉ: 416 Nguyễn Tất Thành, Phường Hội An Tây, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-amber-400 shrink-0"></i>
                            <span>Hotline / Zalo: <a href="tel:0798187689" class="font-bold text-white hover:text-amber-300">0798.187.689</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400 shrink-0"></i>
                            <span>Website: <a href="https://garagedaiviet.com" class="hover:text-amber-300">garagedaiviet.com</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục dịch vụ -->
                <div>
                    <h4 class="font-heading font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-white/15">
                        DANH MỤC DỊCH VỤ
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#dm-dong-son" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Đồng Sơn & Phục Hồi Thân Vỏ Ô Tô</a></li>
                        <li><a href="#dm-may-gam-dien" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Sửa Chữa Máy - Gầm - Hộp Số</a></li>
                        <li><a href="#dm-bao-duong" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Bảo Dưỡng Ô Tô Định Kỳ Các Cấp</a></li>
                        <li><a href="#dm-may-gam-dien" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Sửa Chữa Điện - Điện Lạnh Điều Hòa</a></li>
                        <li><a href="#dm-cham-soc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Chăm Sóc Xe, Đánh Bóng & Phủ Ceramic</a></li>
                        <li><a href="#dm-cuu-ho" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cứu Hộ Giao Thông 24/7 Đà Nẵng - Hội An</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Cam kết khách hàng -->
                <div>
                    <h4 class="font-heading font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-white/15">
                        CAM KẾT CỦA GARAGE ĐẠI VIỆT
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400"></i> Kiểm tra, chẩn đoán bệnh chính xác</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400"></i> Báo giá minh bạch trước khi sửa chữa</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400"></i> Phụ tùng chính hãng, nguồn gốc rõ ràng</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400"></i> Bảo hành dịch vụ & phụ tùng chu đáo</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-emerald-400"></i> Giao xe đúng tiến độ cam kết</li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h4 class="font-heading font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-white/15">
                        KẾT NỐI VỚI CHÚNG TÔI
                    </h4>
                    <p class="text-xs text-slate-300 mb-3">
                        Liên hệ trực tiếp qua Hotline, Zalo hoặc Fanpage để được tư vấn kỹ thuật và cứu hộ nhanh nhất:
                    </p>
                    <div class="space-y-2 text-xs">
                        <a href="tel:0798187689" class="flex items-center gap-2.5 p-2.5 rounded-lg bg-brand-red text-white font-bold hover:bg-brand-darkred transition">
                            <i class="fa-solid fa-phone-volume"></i>
                            <span>Hotline 24/7: 0798.187.689</span>
                        </a>
                        <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener" class="flex items-center gap-2.5 p-2.5 rounded-lg bg-[#1877F2] text-white font-bold hover:bg-blue-700 transition">
                            <i class="fa-brands fa-facebook"></i>
                            <span>Fanpage Garage Đại Việt</span>
                        </a>
                        <a href="https://maps.app.goo.gl/QiMq7fnBbLMVqb4J6" target="_blank" rel="noopener" class="flex items-center gap-2.5 p-2.5 rounded-lg bg-white/10 text-white font-semibold hover:bg-white/20 transition">
                            <i class="fa-solid fa-location-arrow text-amber-400"></i>
                            <span>Bản đồ: 416 Nguyễn Tất Thành</span>
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2 text-center">
                <p>© Bản quyền thuộc về <strong class="text-white">Garage Đại Việt (garagedaiviet.com)</strong> - 416 Nguyễn Tất Thành, P. Hội An Tây, Đà Nẵng.</p>
                <p>Hotline hỗ trợ 24/7: <strong class="text-amber-400">0798.187.689</strong></p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         11. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
         ========================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/vonguyenthanhhue1906" target="_blank" rel="noopener"
           aria-label="Facebook Fanpage Garage Đại Việt"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-sm sm:text-base w-4 text-center"></i>
            <span class="text-xs font-bold hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0798187689" target="_blank" rel="noopener"
           aria-label="Chat Zalo 0798.187.689"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#0068ff] hover:bg-blue-600 text-white shadow-lg transition">
            <span class="font-extrabold text-xs bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">0798.187.689</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0798187689"
           aria-label="Gọi Hotline 0798.187.689"
           class="pulse-btn flex items-center gap-2 px-3.5 py-2.5 rounded-full bg-brand-red hover:bg-brand-darkred text-white shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold">0798.187.689</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, TÌM KIẾM & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // 1. Điều khiển Banner Tự Trượt 2 Slide (Đồng bộ cả Desktop và Mobile)
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function renderBannerSlide(index) {
            const desktopSlides = document.querySelectorAll('.desktop-slide');
            const mobileSlides = document.querySelectorAll('.mobile-slide');
            const dot0 = document.getElementById('dot-0');
            const dot1 = document.getElementById('dot-1');

            desktopSlides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            mobileSlides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            if (index === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            } else {
                dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
            }
        }

        function changeBannerSlide(step) {
            currentSlide = (currentSlide + step + totalSlides) % totalSlides;
            renderBannerSlide(currentSlide);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            currentSlide = index;
            renderBannerSlide(currentSlide);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                renderBannerSlide(currentSlide);
            }, 5000);
        }

        // 2. Đóng/Mở Menu trên điện thoại
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            menu.classList.toggle('hidden');
        }

        // 3. Chọn dịch vụ từ thẻ sản phẩm chuyển xuống Form Báo Giá
        function selectServiceForQuote(serviceName) {
            const selectEl = document.getElementById('qService');
            const noteEl = document.getElementById('qNote');
            if (selectEl) {
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (serviceName.toLowerCase().includes(selectEl.options[i].value.toLowerCase().split(' ')[0])) {
                        selectEl.selectedIndex = i;
                        break;
                    }
                }
            }
            if (noteEl) {
                noteEl.value = 'Tôi cần tư vấn & báo giá dịch vụ: ' + serviceName;
            }
            const formSection = document.getElementById('form-bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
                setTimeout(() => {
                    document.getElementById('qName')?.focus();
                }, 500);
            }
        }

        // 4. Xử lý gửi Form Yêu Cầu Báo Giá
        function handleQuoteSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const car = document.getElementById('qCar').value.trim() || 'Chưa rõ dòng xe';
            const service = document.getElementById('qService').value;

            const summary = `Cảm ơn anh/chị ${name} (${phone})! Yêu cầu báo giá "${service}" cho xe (${car}) đã được ghi nhận. Kỹ thuật viên Garage Đại Việt sẽ liên hệ ngay qua số 0798.187.689.`;
            document.getElementById('quoteSummaryText').textContent = summary;
            document.getElementById('quoteSuccessBox').classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        // 5. Lọc bài viết theo danh mục ở Trang Chủ
        function filterBlog(category, btnElement) {
            const cards = document.querySelectorAll('.blog-card');
            const buttons = document.querySelectorAll('.blog-tab');

            buttons.forEach(btn => {
                btn.classList.remove('bg-brand-navy', 'text-white');
                btn.classList.add('bg-slate-100', 'text-slate-700');
            });
            btnElement.classList.remove('bg-slate-100', 'text-slate-700');
            btnElement.classList.add('bg-brand-navy', 'text-white');

            cards.forEach(card => {
                if (category === 'all' || card.getAttribute('data-blog-cat') === category) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 6. Tìm kiếm nhanh sản phẩm / dịch vụ
        function filterProductsBySearch(keyword) {
            const query = keyword.trim().toLowerCase();
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!query || text.includes(query)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        window.onload = function () {
            resetBannerTimer();
        };
    </script>
</body>
</html>
