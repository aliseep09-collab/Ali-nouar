# Ali-nouar
 Boutique Ali Nouar Your platform for managing your online store with ease. Track orders in real-time. Monthly subscription + 10 free days. Smart solutions for e-commerce merchants.
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Shop - ابدأ تجارتك الإلكترونية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }
        
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700&display=swap');
        
        * {
            font-family: 'Cairo', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #374151 0%, #1f2937 100%);
        }
        
        .hero-pattern {
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.05'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .animate-float {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .feature-icon {
            background: linear-gradient(135deg, #8b5cf6, #7c3aed);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-3 space-x-reverse">
                    <div class="w-10 h-10 gradient-bg rounded-lg flex items-center justify-center">
                        <span class="text-white font-bold text-xl">A</span>
                    </div>
                    <h1 class="text-2xl font-bold text-gray-800">Ali Shop</h1>
                </div>
                
                <nav class="hidden md:flex space-x-8 space-x-reverse items-center">
                    <a href="#features" class="text-gray-600 hover:text-gray-900 transition-colors nav-link" data-ar="المميزات" data-en="Features">المميزات</a>
                    <a href="#testimonials" class="text-gray-600 hover:text-gray-900 transition-colors nav-link" data-ar="آراء العملاء" data-en="Testimonials">آراء العملاء</a>
                    <a href="#faq" class="text-gray-600 hover:text-gray-900 transition-colors nav-link" data-ar="الأسئلة الشائعة" data-en="FAQ">الأسئلة الشائعة</a>
                    <a href="#pricing" class="text-gray-600 hover:text-gray-900 transition-colors nav-link" data-ar="الأسعار" data-en="Pricing">الأسعار</a>
                    
                    <!-- Language Toggle -->
                    <div class="flex items-center bg-gray-100 rounded-lg p-1">
                        <button onclick="switchLanguage('ar')" class="lang-btn px-3 py-1 rounded-md text-sm font-medium transition-all bg-gray-800 text-white" id="ar-btn">
                            العربية
                        </button>
                        <button onclick="switchLanguage('en')" class="lang-btn px-3 py-1 rounded-md text-sm font-medium transition-all text-gray-600 hover:text-gray-900" id="en-btn">
                            English
                        </button>
                    </div>
                </nav>
                
                <button class="gradient-bg text-white px-6 py-2 rounded-lg font-semibold hover:shadow-lg transition-all translatable" data-ar="ابدأ الآن مجاناً" data-en="Start Free Now">
                    ابدأ الآن مجاناً
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="gradient-bg hero-pattern text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <div class="animate-float mb-8">
                <div class="w-20 h-20 bg-white bg-opacity-20 rounded-full flex items-center justify-center mx-auto mb-6">
                    <svg class="w-10 h-10 text-white" fill="currentColor" viewBox="0 0 20 20">
                        <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"/>
                    </svg>
                </div>
            </div>
            
            <h2 class="text-5xl font-bold mb-6 leading-tight translatable" data-ar="ابدأ تجارتك بثقة مع Ali Shop" data-en="Start Your Business Confidently with Ali Shop">
                ابدأ تجارتك بثقة مع Ali Shop
            </h2>
            <p class="text-xl mb-8 opacity-90 max-w-2xl mx-auto translatable" data-ar="حيث يبدأ النجاح بخطوة واحدة! منصة جزائرية حديثة للتجارة الإلكترونية - أبسط وأرخص من أي مكان آخر" data-en="Where success begins with one step! A modern Algerian e-commerce platform - simpler and cheaper than anywhere else">
                حيث يبدأ النجاح بخطوة واحدة! منصة جزائرية حديثة للتجارة الإلكترونية - أبسط وأرخص من أي مكان آخر
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                <button class="bg-white text-gray-800 px-8 py-4 rounded-lg font-bold text-lg hover:bg-gray-100 transition-all translatable" data-ar="ابدأ متجرك مجاناً" data-en="Start Your Store Free">
                    ابدأ متجرك مجاناً
                </button>
                <button class="border-2 border-white text-white px-8 py-4 rounded-lg font-semibold hover:bg-white hover:text-gray-800 transition-all translatable" data-ar="شاهد العرض التوضيحي" data-en="Watch Demo">
                    شاهد العرض التوضيحي
                </button>
            </div>
            
            <div class="mt-12 text-sm opacity-75">
                ✨ تجربة مجانية لمدة 14 يوم - بدون بطاقة ائتمان
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-bold text-gray-800 mb-4">لماذا Ali Shop؟</h3>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    نوفر لك كل ما تحتاجه لبناء متجر إلكتروني ناجح بأسهل الطرق وأقل التكاليف
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="card-hover bg-gray-50 p-8 rounded-xl text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <h4 class="text-xl font-bold text-gray-800 mb-3">إنشاء في دقائق</h4>
                    <p class="text-gray-600">أنشئ متجرك الإلكتروني في أقل من 5 دقائق بدون أي خبرة تقنية</p>
                </div>
                
                <div class="card-hover bg-gray-50 p-8 rounded-xl text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4zM18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm5-1a1 1 0 100 2h1a1 1 0 100-2H9z"/>
                        </svg>
                    </div>
                    <h4 class="text-xl font-bold text-gray-800 mb-3">دفع إلكتروني آمن</h4>
                    <p class="text-gray-600">قبول المدفوعات عبر بطاقات الائتمان وبريدي موب للجزائريين</p>
                </div>
                
                <div class="card-hover bg-gray-50 p-8 rounded-xl text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 20 20">
                            <path d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"/>
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <h4 class="text-xl font-bold text-gray-800 mb-3">أسعار منخفضة</h4>
                    <p class="text-gray-600">اشتراكات شهرية وسنوية بأسعار تنافسية تناسب جميع الميزانيات</p>
                </div>
                
                <div class="card-hover bg-gray-50 p-8 rounded-xl text-center">
                    <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-6">
                        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 20 20">
                            <path fill-rule="evenodd" d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z" clip-rule="evenodd"/>
                        </svg>
                    </div>
                    <h4 class="text-xl font-bold text-gray-800 mb-3">خصم للمشتركين الجدد</h4>
                    <p class="text-gray-600">احصل على خصم 50% على أول 3 أشهر عند الاشتراك الآن</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-bold text-gray-800 mb-4">خطط الأسعار</h3>
                <p class="text-xl text-gray-600">اختر الخطة التي تناسب احتياجاتك</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <div class="bg-white p-8 rounded-xl shadow-lg">
                    <h4 class="text-2xl font-bold text-gray-800 mb-4">الخطة الأساسية</h4>
                    <div class="text-4xl font-bold text-gray-800 mb-6">2,500 دج<span class="text-lg text-gray-500">/شهر</span></div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> متجر إلكتروني كامل</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> حتى 100 منتج</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> دعم فني 24/7</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> شهادة SSL مجانية</li>
                    </ul>
                    <button class="w-full border-2 border-gray-800 text-gray-800 py-3 rounded-lg font-semibold hover:bg-gray-800 hover:text-white transition-all">
                        اختر هذه الخطة
                    </button>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg border-4 border-gray-800 relative">
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-gray-800 text-white px-4 py-1 rounded-full text-sm font-semibold">
                        الأكثر شعبية
                    </div>
                    <h4 class="text-2xl font-bold text-gray-800 mb-4">الخطة المتقدمة</h4>
                    <div class="text-4xl font-bold text-gray-800 mb-6">4,500 دج<span class="text-lg text-gray-500">/شهر</span></div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> كل مميزات الخطة الأساسية</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> منتجات غير محدودة</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> تحليلات متقدمة</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> تخصيص كامل للتصميم</li>
                    </ul>
                    <button class="w-full gradient-bg text-white py-3 rounded-lg font-semibold hover:shadow-lg transition-all">
                        اختر هذه الخطة
                    </button>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg">
                    <h4 class="text-2xl font-bold text-gray-800 mb-4">الخطة الاحترافية</h4>
                    <div class="text-4xl font-bold text-gray-800 mb-6">7,500 دج<span class="text-lg text-gray-500">/شهر</span></div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> كل مميزات الخطة المتقدمة</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> متاجر متعددة</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> API متقدم</li>
                        <li class="flex items-center"><span class="text-gray-600 ml-2">✓</span> دعم مخصص</li>
                    </ul>
                    <button class="w-full border-2 border-gray-800 text-gray-800 py-3 rounded-lg font-semibold hover:bg-gray-800 hover:text-white transition-all">
                        اختر هذه الخطة
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-bold text-gray-800 mb-4">آراء عملائنا</h3>
                <p class="text-xl text-gray-600">ماذا يقول التجار عن تجربتهم مع Ali Shop</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-gray-600 rounded-full flex items-center justify-center text-white font-bold">
                            أ
                        </div>
                        <div class="mr-4">
                            <h5 class="font-bold text-gray-800">أحمد بن علي</h5>
                            <p class="text-gray-600 text-sm">متجر الإلكترونيات</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">"Ali Shop غيّر حياتي التجارية! أنشأت متجري في دقائق وبدأت البيع فوراً. الدعم الفني ممتاز والأسعار معقولة جداً."</p>
                    <div class="flex text-yellow-400">
                        ⭐⭐⭐⭐⭐
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-gray-600 rounded-full flex items-center justify-center text-white font-bold">
                            ف
                        </div>
                        <div class="mr-4">
                            <h5 class="font-bold text-gray-800">فاطمة الزهراء</h5>
                            <p class="text-gray-600 text-sm">متجر الأزياء</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">"كوني امرأة عاملة، كنت أحتاج حلاً سريعاً وبسيطاً. Ali Shop وفر لي كل ما أحتاجه لبدء مشروعي الخاص بنجاح."</p>
                    <div class="flex text-yellow-400">
                        ⭐⭐⭐⭐⭐
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-gray-600 rounded-full flex items-center justify-center text-white font-bold">
                            م
                        </div>
                        <div class="mr-4">
                            <h5 class="font-bold text-gray-800">محمد الأمين</h5>
                            <p class="text-gray-600 text-sm">متجر المواد الغذائية</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">"بعد تجربة عدة منصات، Ali Shop هو الأفضل للسوق الجزائري. سهولة الاستخدام ودعم بريدي موب ميزة رائعة."</p>
                    <div class="flex text-yellow-400">
                        ⭐⭐⭐⭐⭐
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-bold text-gray-800 mb-4">الأسئلة الشائعة</h3>
                <p class="text-xl text-gray-600">إجابات على أكثر الأسئلة شيوعاً</p>
            </div>
            
            <div class="max-w-3xl mx-auto space-y-4">
                <div class="bg-white rounded-lg shadow-sm">
                    <button class="w-full text-right p-6 font-semibold text-gray-800 hover:text-gray-900 transition-colors faq-toggle" onclick="toggleFAQ(this)">
                        كيف يمكنني إنشاء متجري الإلكتروني؟
                        <span class="float-left">+</span>
                    </button>
                    <div class="faq-content hidden p-6 pt-0 text-gray-600">
                        ببساطة! اضغط على "ابدأ الآن مجاناً"، أدخل بياناتك الأساسية، اختر تصميم متجرك، وأضف منتجاتك. ستكون جاهزاً للبيع في أقل من 5 دقائق.
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-sm">
                    <button class="w-full text-right p-6 font-semibold text-gray-800 hover:text-gray-900 transition-colors faq-toggle" onclick="toggleFAQ(this)">
                        ما هي طرق الدفع المتاحة؟
                        <span class="float-left">+</span>
                    </button>
                    <div class="faq-content hidden p-6 pt-0 text-gray-600">
                        نوفر دعماً كاملاً لبطاقات الائتمان العالمية، وللعملاء الجزائريين نوفر دعم بريدي موب وبطاقات الدفع المحلية الأخرى.
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-sm">
                    <button class="w-full text-right p-6 font-semibold text-gray-800 hover:text-gray-900 transition-colors faq-toggle" onclick="toggleFAQ(this)">
                        هل يمكنني تجربة الخدمة مجاناً؟
                        <span class="float-left">+</span>
                    </button>
                    <div class="faq-content hidden p-6 pt-0 text-gray-600">
                        نعم! نوفر تجربة مجانية لمدة 14 يوماً بدون الحاجة لبطاقة ائتمان. يمكنك تجربة جميع المميزات والتأكد من ملاءمة الخدمة لاحتياجاتك.
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-sm">
                    <button class="w-full text-right p-6 font-semibold text-gray-800 hover:text-gray-900 transition-colors faq-toggle" onclick="toggleFAQ(this)">
                        هل أحتاج خبرة تقنية لاستخدام المنصة؟
                        <span class="float-left">+</span>
                    </button>
                    <div class="faq-content hidden p-6 pt-0 text-gray-600">
                        إطلاقاً! Ali Shop مصمم ليكون بسيطاً وسهل الاستخدام. واجهة المستخدم باللغة العربية وجميع العمليات تتم بالسحب والإفلات.
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-sm">
                    <button class="w-full text-right p-6 font-semibold text-gray-800 hover:text-gray-900 transition-colors faq-toggle" onclick="toggleFAQ(this)">
                        كيف يمكنني الحصول على الدعم الفني؟
                        <span class="float-left">+</span>
                    </button>
                    <div class="faq-content hidden p-6 pt-0 text-gray-600">
                        فريق الدعم الفني متاح 24/7 عبر الدردشة المباشرة، البريد الإلكتروني، والهاتف. نحن هنا لمساعدتك في أي وقت تحتاج فيه للمساعدة.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="gradient-bg hero-pattern text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-4xl font-bold mb-6">جاهز لبدء رحلتك التجارية؟</h3>
            <p class="text-xl mb-8 opacity-90 max-w-2xl mx-auto">
                انضم إلى آلاف التجار الذين اختاروا Ali Shop لبناء متاجرهم الإلكترونية
            </p>
            <button class="bg-white text-gray-800 px-8 py-4 rounded-lg font-bold text-lg hover:bg-gray-100 transition-all">
                ابدأ تجربتك المجانية الآن
            </button>
            <div class="mt-6 text-sm opacity-75">
                ✨ بدون التزام - يمكنك الإلغاء في أي وقت
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-3 space-x-reverse mb-4">
                        <div class="w-8 h-8 gradient-bg rounded-lg flex items-center justify-center">
                            <span class="text-white font-bold">A</span>
                        </div>
                        <h4 class="text-xl font-bold">Ali Shop</h4>
                    </div>
                    <p class="text-gray-400">منصة جزائرية حديثة للتجارة الإلكترونية تمكنك من إنشاء متجرك بسهولة وبأسعار منافسة.</p>
                </div>
                
                <div>
                    <h5 class="font-bold mb-4">الخدمات</h5>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">إنشاء المتاجر</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">الدفع الإلكتروني</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">التحليلات</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">الدعم الفني</a></li>
                    </ul>
                </div>
                
                <div>
                    <h5 class="font-bold mb-4">الشركة</h5>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">من نحن</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">اتصل بنا</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">الوظائف</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">الأخبار</a></li>
                    </ul>
                </div>
                
                <div>
                    <h5 class="font-bold mb-4">تابعنا</h5>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-gray-600 transition-colors">
                            <span>📘</span>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-gray-600 transition-colors">
                            <span>📷</span>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-gray-600 transition-colors">
                            <span>🐦</span>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2024 Ali Shop. جميع الحقوق محفوظة.</p>
            </div>
        </div>
    </footer>

    <script>
        let currentLanguage = 'ar';

        function switchLanguage(lang) {
            currentLanguage = lang;
            const html = document.documentElement;
            
            // Update language buttons
            document.querySelectorAll('.lang-btn').forEach(btn => {
                btn.classList.remove('bg-gray-800', 'text-white');
                btn.classList.add('text-gray-600');
            });
            
            const activeBtn = document.getElementById(lang + '-btn');
            activeBtn.classList.add('bg-gray-800', 'text-white');
            activeBtn.classList.remove('text-gray-600');
            
            // Update text direction and language
            if (lang === 'ar') {
                html.setAttribute('dir', 'rtl');
                html.setAttribute('lang', 'ar');
            } else {
                html.setAttribute('dir', 'ltr');
                html.setAttribute('lang', 'en');
            }
            
            // Update all translatable elements
            document.querySelectorAll('.translatable, .nav-link').forEach(element => {
                const text = element.getAttribute('data-' + lang);
                if (text) {
                    element.textContent = text;
                }
            });
            
            // Update specific sections that need special handling
            updateSectionTitles(lang);
            updateFeatures(lang);
            updateTestimonials(lang);
            updateFAQ(lang);
        }

        function updateSectionTitles(lang) {
            const titles = {
                ar: {
                    features: 'لماذا Ali Shop؟',
                    featuresDesc: 'نوفر لك كل ما تحتاجه لبناء متجر إلكتروني ناجح بأسهل الطرق وأقل التكاليف',
                    pricing: 'خطط الأسعار',
                    pricingDesc: 'اختر الخطة التي تناسب احتياجاتك',
                    testimonials: 'آراء عملائنا',
                    testimonialsDesc: 'ماذا يقول التجار عن تجربتهم مع Ali Shop',
                    faq: 'الأسئلة الشائعة',
                    faqDesc: 'إجابات على أكثر الأسئلة شيوعاً'
                },
                en: {
                    features: 'Why Ali Shop?',
                    featuresDesc: 'We provide everything you need to build a successful online store in the easiest ways and lowest costs',
                    pricing: 'Pricing Plans',
                    pricingDesc: 'Choose the plan that suits your needs',
                    testimonials: 'Customer Reviews',
                    testimonialsDesc: 'What merchants say about their experience with Ali Shop',
                    faq: 'Frequently Asked Questions',
                    faqDesc: 'Answers to the most common questions'
                }
            };
            
            // Update section titles
            const sections = ['features', 'pricing', 'testimonials', 'faq'];
            sections.forEach(section => {
                const titleEl = document.querySelector(`#${section} h3`);
                const descEl = document.querySelector(`#${section} p`);
                if (titleEl) titleEl.textContent = titles[lang][section];
                if (descEl) descEl.textContent = titles[lang][section + 'Desc'];
            });
        }

        function updateFeatures(lang) {
            const features = {
                ar: [
                    { title: 'إنشاء في دقائق', desc: 'أنشئ متجرك الإلكتروني في أقل من 5 دقائق بدون أي خبرة تقنية' },
                    { title: 'دفع إلكتروني آمن', desc: 'قبول المدفوعات عبر بطاقات الائتمان وبريدي موب للجزائريين' },
                    { title: 'أسعار منخفضة', desc: 'اشتراكات شهرية وسنوية بأسعار تنافسية تناسب جميع الميزانيات' },
                    { title: 'خصم للمشتركين الجدد', desc: 'احصل على خصم 50% على أول 3 أشهر عند الاشتراك الآن' }
                ],
                en: [
                    { title: 'Create in Minutes', desc: 'Create your online store in less than 5 minutes without any technical experience' },
                    { title: 'Secure Electronic Payment', desc: 'Accept payments via credit cards and Baridimob for Algerians' },
                    { title: 'Low Prices', desc: 'Monthly and annual subscriptions at competitive prices suitable for all budgets' },
                    { title: 'New Subscriber Discount', desc: 'Get 50% discount on the first 3 months when you subscribe now' }
                ]
            };
            
            const featureCards = document.querySelectorAll('#features .card-hover');
            featureCards.forEach((card, index) => {
                const title = card.querySelector('h4');
                const desc = card.querySelector('p');
                if (title && desc && features[lang][index]) {
                    title.textContent = features[lang][index].title;
                    desc.textContent = features[lang][index].desc;
                }
            });
        }

        function updateTestimonials(lang) {
            const testimonials = {
                ar: [
                    { name: 'أحمد بن علي', store: 'متجر الإلكترونيات', text: '"Ali Shop غيّر حياتي التجارية! أنشأت متجري في دقائق وبدأت البيع فوراً. الدعم الفني ممتاز والأسعار معقولة جداً."' },
                    { name: 'فاطمة الزهراء', store: 'متجر الأزياء', text: '"كوني امرأة عاملة، كنت أحتاج حلاً سريعاً وبسيطاً. Ali Shop وفر لي كل ما أحتاجه لبدء مشروعي الخاص بنجاح."' },
                    { name: 'محمد الأمين', store: 'متجر المواد الغذائية', text: '"بعد تجربة عدة منصات، Ali Shop هو الأفضل للسوق الجزائري. سهولة الاستخدام ودعم بريدي موب ميزة رائعة."' }
                ],
                en: [
                    { name: 'Ahmed Ben Ali', store: 'Electronics Store', text: '"Ali Shop changed my business life! I created my store in minutes and started selling immediately. Technical support is excellent and prices are very reasonable."' },
                    { name: 'Fatima Zahra', store: 'Fashion Store', text: '"As a working woman, I needed a quick and simple solution. Ali Shop provided me with everything I need to start my own project successfully."' },
                    { name: 'Mohamed Amine', store: 'Grocery Store', text: '"After trying several platforms, Ali Shop is the best for the Algerian market. Ease of use and Baridimob support is a great feature."' }
                ]
            };
            
            const testimonialCards = document.querySelectorAll('#testimonials .bg-gray-50');
            testimonialCards.forEach((card, index) => {
                const name = card.querySelector('h5');
                const store = card.querySelector('.text-sm');
                const text = card.querySelector('p.text-gray-700');
                if (name && store && text && testimonials[lang][index]) {
                    name.textContent = testimonials[lang][index].name;
                    store.textContent = testimonials[lang][index].store;
                    text.textContent = testimonials[lang][index].text;
                }
            });
        }

        function updateFAQ(lang) {
            const faqs = {
                ar: [
                    { q: 'كيف يمكنني إنشاء متجري الإلكتروني؟', a: 'ببساطة! اضغط على "ابدأ الآن مجاناً"، أدخل بياناتك الأساسية، اختر تصميم متجرك، وأضف منتجاتك. ستكون جاهزاً للبيع في أقل من 5 دقائق.' },
                    { q: 'ما هي طرق الدفع المتاحة؟', a: 'نوفر دعماً كاملاً لبطاقات الائتمان العالمية، وللعملاء الجزائريين نوفر دعم بريدي موب وبطاقات الدفع المحلية الأخرى.' },
                    { q: 'هل يمكنني تجربة الخدمة مجاناً؟', a: 'نعم! نوفر تجربة مجانية لمدة 14 يوماً بدون الحاجة لبطاقة ائتمان. يمكنك تجربة جميع المميزات والتأكد من ملاءمة الخدمة لاحتياجاتك.' },
                    { q: 'هل أحتاج خبرة تقنية لاستخدام المنصة؟', a: 'إطلاقاً! Ali Shop مصمم ليكون بسيطاً وسهل الاستخدام. واجهة المستخدم باللغة العربية وجميع العمليات تتم بالسحب والإفلات.' },
                    { q: 'كيف يمكنني الحصول على الدعم الفني؟', a: 'فريق الدعم الفني متاح 24/7 عبر الدردشة المباشرة، البريد الإلكتروني، والهاتف. نحن هنا لمساعدتك في أي وقت تحتاج فيه للمساعدة.' }
                ],
                en: [
                    { q: 'How can I create my online store?', a: 'Simply! Click "Start Free Now", enter your basic information, choose your store design, and add your products. You\'ll be ready to sell in less than 5 minutes.' },
                    { q: 'What payment methods are available?', a: 'We provide full support for international credit cards, and for Algerian customers we provide Baridimob support and other local payment cards.' },
                    { q: 'Can I try the service for free?', a: 'Yes! We provide a 14-day free trial without the need for a credit card. You can try all features and make sure the service fits your needs.' },
                    { q: 'Do I need technical experience to use the platform?', a: 'Not at all! Ali Shop is designed to be simple and easy to use. The user interface is in Arabic and all operations are done by drag and drop.' },
                    { q: 'How can I get technical support?', a: 'Technical support team is available 24/7 via live chat, email, and phone. We are here to help you whenever you need assistance.' }
                ]
            };
            
            const faqItems = document.querySelectorAll('#faq .bg-white');
            faqItems.forEach((item, index) => {
                const question = item.querySelector('.faq-toggle');
                const answer = item.querySelector('.faq-content');
                if (question && answer && faqs[lang][index]) {
                    const questionText = question.childNodes[0];
                    questionText.textContent = faqs[lang][index].q + ' ';
                    answer.textContent = faqs[lang][index].a;
                }
            });
        }

        function toggleFAQ(button) {
            const content = button.nextElementSibling;
            const icon = button.querySelector('span');
            
            if (content.classList.contains('hidden')) {
                content.classList.remove('hidden');
                icon.textContent = '-';
            } else {
                content.classList.add('hidden');
                icon.textContent = '+';
            }
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll effect to header
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.classList.add('shadow-xl');
            } else {
                header.classList.remove('shadow-xl');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9907fa8020cc2133',t:'MTc2MDc4OTkwOC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
