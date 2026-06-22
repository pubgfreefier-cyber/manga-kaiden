<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مانغا كايدن | الرئيسية</title>
    <!-- استدعاء مكتبة التنسيق Tailwind CSS -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- استدعاء أيقونات FontAwesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* تخصيص الألوان الافتراضية متوافقة مع طلبك */
        :root {
            --bg-main: #0F172A;
            --bg-card: #1E293B;
            --primary: #8B5CF6; /* البنفسجي */
            --primary-hover: #7C3AED;
        }
        body {
            background-color: var(--bg-main);
            color: #F8FAFC;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
    </style>
</head>
<body>

    <!-- شريط التنقل العلوي (Navbar) -->
    <nav class="bg-[#1E293B] border-b border-gray-700 shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- الشعار والقائمة -->
                <div class="flex items-center gap-6">
                    <div class="text-2xl font-bold text-[#8B5CF6] tracking-wider">
                        <i class="fa-solid fa-book-open shadow-sm"></i> مانغا كايدن
                    </div>
                    <div class="hidden md:flex items-center gap-4 text-gray-300">
                        <a href="#" class="hover:text-[#8B5CF6] px-3 py-2 rounded-md font-medium transition"><i class="fa-solid fa-house ml-1"></i> الرئيسية</a>
                        <a href="#" class="hover:text-[#8B5CF6] px-3 py-2 rounded-md font-medium transition"><i class="fa-solid fa-list ml-1"></i> قائمة المانغا</a>
                        <a href="#" class="hover:text-[#8B5CF6] px-3 py-2 rounded-md font-medium transition"><i class="fa-solid fa-users ml-1"></i> الفرق</a>
                    </div>
                </div>
                <!-- أزرار الحساب والبحث -->
                <div class="flex items-center gap-4">
                    <div class="relative hidden sm:block">
                        <input type="text" placeholder="ابحث عن مانغا..." class="bg-[#0F172A] text-sm text-white px-4 py-2 pr-10 rounded-full border border-gray-700 focus:outline-none focus:border-[#8B5CF6] w-64 transition">
                        <i class="fa-solid fa-magnifying-glass absolute left-3 top-3 text-gray-500"></i>
                    </div>
                    <a href="#" class="bg-[#8B5CF6] hover:bg-[#7C3AED] text-white px-4 py-2 rounded-md font-medium transition shadow-md">
                        <i class="fa-solid fa-user-plus ml-1"></i> إنشاء حساب
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- محتوى الصفحة الرئيسية -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <!-- قسم ترحيبي وقسم الفرق المميزة -->
        <div class="bg-gradient-to-r from-[#1E293B] to-[#2D3748] p-6 rounded-2xl border border-gray-700 shadow-md mb-8 flex flex-col md:flex-row justify-between items-center gap-4">
            <div>
                <h1 class="text-2xl md:text-3xl font-bold mb-2 text-white">مرحباً بك في منصة <span class="text-[#8B5CF6]">مانغا كايدن</span></h1>
                <p class="text-gray-400 text-sm md:text-base">المنصة الأولى لدعم المترجمين المستقلين وتشكيل فرق المانغا الاحترافية.</p>
            </div>
            <div class="flex gap-3">
                <a href="#" class="bg-transparent border border-[#8B5CF6] text-[#8B5CF6] hover:bg-[#8B5CF6] hover:text-white px-4 py-2 rounded-lg font-medium transition">
                    <i class="fa-solid fa-people-group ml-1"></i> إنشاء فريقك الخاص
                </a>
            </div>
        </div>

        <!-- عنوان القسم الرئيسي (أحدث التحديثات) -->
        <div class="flex items-center justify-between mb-6 border-r-4 border-[#8B5CF6] pr-3">
            <h2 class="text-xl font-bold">أحدث الفصول المضافة</h2>
            <a href="#" class="text-sm text-[#8B5CF6] hover:underline">عرض الكل <i class="fa-solid fa-chevron-left mr-1 text-xs"></i></a>
        </div>

        <!-- شبكة المانغا (Manga Grid Layout) -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-6">
            
            <!-- كرت مانغا تجريبي (سيتم تكراره برمجياً لاحقاً) -->
            <div class="bg-[#1E293B] rounded-xl overflow-hidden shadow-lg border border-gray-800 hover:border-[#8B5CF6] transition transform hover:-translate-y-1 duration-200 group">
                <div class="relative aspect-[3/4] bg-gray-700">
                    <!-- صورة مؤقتة للغلاف -->
                    <div class="absolute inset-0 flex items-center justify-center text-gray-500">
                        <i class="fa-regular fa-image text-4xl"></i>
                    </div>
                    <span class="absolute top-2 right-2 bg-red-600 text-white text-xs font-bold px-2 py-1 rounded">HOT</span>
                </div>
                <div class="p-3">
                    <h3 class="font-bold text-sm truncate group-hover:text-[#8B5CF6] transition">اسم المانغا يكتب هنا</h3>
                    <p class="text-xs text-gray-400 mt-1"><i class="fa-solid fa-users text-[#8B5CF6] text-[10px] ml-1"></i> فريق الصقور</p>
                    <div class="mt-2 flex flex-col gap-1">
                        <a href="#" class="flex justify-between items-center bg-[#0F172A] p-1.5 rounded text-xs hover:bg-[#8B5CF6] hover:text-white transition">
                            <span>الفصل 105</span>
                            <span class="text-[10px] text-gray-500 group-hover:text-white">منذ ساعة</span>
                        </a>
                        <a href="#" class="flex justify-between items-center bg-[#0F172A] p-1.5 rounded text-xs hover:bg-[#8B5CF6] hover:text-white transition">
                            <span>الفصل 104</span>
                            <span class="text-[10px] text-gray-500 group-hover:text-white">أمس</span>
                        </a>
                    </div>
                </div>
            </div>

            <!-- كرت مانغا آخر لتوضيح الشكل العام -->
            <div class="bg-[#1E293B] rounded-xl overflow-hidden shadow-lg border border-gray-800 hover:border-[#8B5CF6] transition transform hover:-translate-y-1 duration-200 group">
                <div class="relative aspect-[3/4] bg-gray-700">
                    <div class="absolute inset-0 flex items-center justify-center text-gray-500">
                        <i class="fa-regular fa-image text-4xl"></i>
                    </div>
                </div>
                <div class="p-3">
                    <h3 class="font-bold text-sm truncate group-hover:text-[#8B5CF6] transition">مانغا مغامرات خيالية</h3>
                    <p class="text-xs text-gray-400 mt-1"><i class="fa-solid fa-user text-[#8B5CF6] text-[10px] ml-1"></i> مدون مستقل</p>
                    <div class="mt-2 flex flex-col gap-1">
                        <a href="#" class="flex justify-between items-center bg-[#0F172A] p-1.5 rounded text-xs hover:bg-[#8B5CF6] hover:text-white transition">
                            <span>الفصل 02</span>
                            <span class="text-[10px] text-gray-500">يومين</span>
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </main>

</body>
</html>
