<Prosekov>
<html lang="ru" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Натяжные потолки PROsekov | Новомосковск и Тульская область</title>
    <base target="_self">
    <script src="https://cdn.tailwindcss.com "></script>
    <script src="https://cdn.jsdelivr.net/npm/ @preline/preline@2.0.0/dist/preline.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css ">

    <!-- Настройка Tailwind -->
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        graphite: {
                            500: '#A9A9A9',
                            600: '#7D7F82',
                            700: '#2E3135'
                        },
                        silver: {
                            400: '#C0C0C0',
                            500: '#B0B0B0',
                            600: '#9A9A9A'
                        },
                        yellowAccent: {
                            400: '#FBBF24',
                            500: '#FACC15',
                            600: '#D9A010'
                        }
                    },
                    fontFamily: {
                        'sans': ['Inter', 'sans-serif'],
                        'heading': ['Montserrat', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <!-- Стили -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700&display=swap');

        .bg-local-pattern {
            background-image: url('image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI2MCIgaGVpZ2h0PSI2MCIgdmlld0JveD0iMCAwIDYwIDYwIj48cGF0aCBkPSJNNDAgMEMxNy45IDAgMCAxNy45IDAgNDBzMTcuOSA0MCA0MCA0MCA0MC0xNy45IDQwLTQwUzYyLjEgMCA0MCAwem0wIDVjMTkuMyAwIDM1IDE1LjcgMzUgMzVzLTE1LjcgMzUtMzUgMzVTNSA1OS4zIDUgNDAgMjAuNyA1IDQwIDV6IiBmaWxsPSJ1cmwoI2EpIi8+PHBhdGggZD0iTTQwIDE1YzEzLjggMCAyNSAxMS4yIDI1IDI1UzUzLjggNjUgNDAgNjVTMjUgNTMuOCAyNSA0MCAzNi4yIDE1IDQwIDE1em0wIDVjMTEgMCAyMCA5IDIwIDIwcy05IDIwLTIwIDIwLTIwLTktMjAtMjAgOS0yMCAyMC0yMHoiIGZpbGw9InVybCgjYikiLz48ZGVmcz48cmFkaWFsR3JhZGllbnQgaWQ9ImEiIGN4PSIwIiBjeT0iMCIgcj0iNjAiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIj48c3RvcCBvZmZzZXQ9Ii41IiBzdG9wLWNvbG9yPSIjZjVlOGQxIi8+PHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjZjVlOGQxIiBzdG9wLW9wYWNpdHk9IjAiLz48L3JhZGlhbEdyYWRpZW50PjxyYWRpYWxHcmFkaWVudCBpZD0iYiIgY3g9IjAiIGN5PSIwIiByPSI2MCIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPjxzdG9wIG9mZnNldD0iLjUiIHN0b3AtY29sb3I9IiNmY2JmODkiLz48c3RvcCBvZmZzZXQ9IjEiIHN0b3AtY29sb3I9IiNmY2JmODkiIHN0b3Atb3BhY2l0eT0iMCIvPjwvcmFkaWFsR3JhZGllbnQ+PC9kZWZzPjwvc3ZnPg==');
            background-size: 100px;
            opacity: 0.1;
        }

        .btn-primary {
            background: linear-gradient(135deg, #7D7F82 0%, #2E3135 100%);
            transition: all 0.3s ease;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(46, 49, 53, 0.4);
        }

        .btn-accent {
            background: linear-gradient(135deg, #C0C0C0 0%, #9A9A9A 100%);
            transition: all 0.3s ease;
        }

        .btn-accent:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(192, 192, 192, 0.4);
        }

        .btn-yellow {
            background-color: #FACC15;
            color: #fff;
            border-radius: 0.5rem;
            transition: all 0.3s ease;
        }

        .btn-yellow:hover {
            background-color: #FBBF24;
            box-shadow: 0 4px 15px rgba(250, 204, 21, 0.4);
        }

        .feature-card {
            transition: all 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .testimonial-card {
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }

        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 25px rgba(0, 0, 0, 0.1);
        }

        .pulse {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(250, 204, 21, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(250, 204, 21, 0); }
            100% { box-shadow: 0 0 0 0 rgba(250, 204, 21, 0); }
        }

        .floating {
            animation: floating 3s ease-in-out infinite;
        }

        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        /* Цвета для классов */
        .bg-primary-100 { background-color: #f5f5f5; }
        .text-primary-600,
        .hover\:text-primary-600:hover,
        .bg-primary-600 { color: #7D7F82; }
        .bg-accent-500 { background-color: #C0C0C0; }
        .text-accent-600,
        .hover\:text-accent-600:hover,
        .bg-accent-600 { color: #9A9A9A; }
        .bg-accent-100 { background-color: #E0E0E0; }
    </style>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

<!-- Header -->
<header class="sticky top-0 z-50 bg-white shadow-sm">
    <div class="container mx-auto px-4 py-3">
        <div class="flex justify-between items-center">
            <div class="flex items-center">
                <a href="#" class="text-2xl font-heading font-bold">
                    <span class="text-graphite-600">PRO</span><span class="text-yellowAccent-500">sekov</span>
                </a>
            </div>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#advantages" class="font-medium hover:text-graphite-600 transition-colors">Преимущества</a>
                <a href="#portfolio" class="font-medium hover:text-graphite-600 transition-colors">Портфолио</a>
                <a href="#reviews" class="font-medium hover:text-graphite-600 transition-colors">Отзывы</a>
                <a href="#contact" class="font-medium hover:text-graphite-600 transition-colors">Контакты</a>
            </div>
            <div class="flex items-center">
                <a href="tel:+78001234567" class="hidden md:flex items-center bg-graphite-100 text-graphite-600 px-4 py-2 rounded-lg mr-4 hover:bg-graphite-200 transition-colors">
                    <i class="fas fa-phone-alt mr-2"></i>
                    <span class="font-medium">+7 (___) ___-__-__</span>
                </a>
                <button class="md:hidden text-gray-600 hover:text-graphite-600">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </div>
</header>

<!-- Hero Section -->
<section class="relative py-12 md:py-20 bg-white overflow-hidden">
    <div class="absolute inset-0 bg-local-pattern"></div>
    <div class="container mx-auto px-4 relative">
        <div class="flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-3xl md:text-4xl lg:text-5xl font-heading font-bold mb-6">
                    Натяжные потолки в <span class="text-graphite-600">Новомосковске</span> и Тульской области
                </h1>
                <p class="text-xl text-gray-600 mb-8">
                    Потолки за <span class="font-bold text-yellowAccent-500">1 день</span> с гарантией <span class="font-bold text-yellowAccent-500">10 лет</span>
                </p>
                <div class="flex flex-col sm:flex-row gap-4 mb-8">
                    <a href="#calculator" class="btn-accent bg-silver-500 text-white font-medium py-3 px-6 rounded-lg text-center hover:bg-silver-600 transition-colors">
                        Рассчитать стоимость
                    </a>
                    <a href="#contact" class="btn-yellow bg-yellowAccent-500 text-white font-medium py-3 px-6 rounded-lg text-center">
                        Заказать замер
                    </a>
                </div>
                <div class="bg-white rounded-lg shadow-md p-4 inline-block">
                    <div class="flex items-center">
                        <div class="flex-shrink-0 bg-green-100 text-green-600 rounded-full p-2 mr-3">
                            <i class="fas fa-check"></i>
                        </div>
                        <div>
                            <p class="font-medium">Бесплатный замер уже сегодня</p>
                            <p class="text-sm text-gray-500">Оставьте заявку до 18:00</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="md:w-1/2 relative">
                <div class="relative rounded-xl overflow-hidden shadow-xl">
                    <img src=" https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80"
                         alt="Натяжной потолок" class="w-full h-auto">
                    <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/70 to-transparent p-6">
                        <div class="flex items-center">
                            <div class="bg-yellowAccent-500 text-white rounded-full p-2 mr-3">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <p class="text-white font-medium">г. Новомосковск</p>
                                <p class="text-white/80 text-sm">Жилой комплекс "Престиж"</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="absolute -top-6 -right-6 bg-white rounded-lg shadow-lg p-4 w-32 rotate-3">
                    <div class="flex items-center">
                        <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-2">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <div>
                            <p class="text-xs font-bold">Монтаж</p>
                            <p class="text-xs">за 1 день</p>
                        </div>
                    </div>
                </div>
                <div class="absolute -bottom-6 -left-6 bg-white rounded-lg shadow-lg p-4 w-32 -rotate-3">
                    <div class="flex items-center">
                        <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-2">
                            <i class="fas fa-shield-alt"></i>
                        </div>
                        <div>
                            <p class="text-xs font-bold">Гарантия</p>
                            <p class="text-xs">10 лет</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Features Section -->
<section class="py-12 bg-gray-50">
    <div class="container mx-auto px-4">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-12">
            <div class="bg-white rounded-lg p-4 text-center feature-card">
                <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-3 inline-block mb-3">
                    <i class="fas fa-home text-xl"></i>
                </div>
                <h3 class="font-bold mb-1">Местные мастера</h3>
                <p class="text-sm text-gray-600">Работаем в регионе 5+ лет</p>
            </div>
            <div class="bg-white rounded-lg p-4 text-center feature-card">
                <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-3 inline-block mb-3">
                    <i class="fas fa-tag text-xl"></i>
                </div>
                <h3 class="font-bold mb-1">От 399 ₽/м²</h3>
                <p class="text-sm text-gray-600">Честные цены без накруток</p>
            </div>
            <div class="bg-white rounded-lg p-4 text-center feature-card">
                <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-3 inline-block mb-3">
                    <i class="fas fa-ruler-combined text-xl"></i>
                </div>
                <h3 class="font-bold mb-1">Бесплатный замер</h3>
                <p class="text-sm text-gray-600">Уже сегодня</p>
            </div>
            <div class="bg-white rounded-lg p-4 text-center feature-card">
                <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-3 inline-block mb-3">
                    <i class="fas fa-users text-xl"></i>
                </div>
                <h3 class="font-bold mb-1">120+ клиентов</h3>
                <p class="text-sm text-gray-600">Довольны работой</p>
            </div>
        </div>
    </div>
</section>

<!-- Advantages Section -->
<section id="advantages" class="py-12 bg-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Почему выбирают нас</h2>
            <div class="w-20 h-1 bg-yellowAccent-500 mx-auto mb-6"></div>
        </div>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Работа без посредников</h3>
                        <p class="text-gray-600">Мы производители и монтажники в одном лице. Никаких переплат!</p>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-lock"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Фиксированная цена</h3>
                        <p class="text-gray-600">Цена после замера не изменится. Никаких скрытых платежей!</p>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-broom"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Чистый монтаж</h3>
                        <p class="text-gray-600">После нас не нужно делать уборку. Работаем аккуратно!</p>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-file-contract"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Гарантия по договору</h3>
                        <p class="text-gray-600">10 лет официальной гарантии. Все прописано в договоре!</p>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-map-marked-alt"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Портфолио в вашем городе</h3>
                        <p class="text-gray-600">Покажем выполненные работы в вашем районе!</p>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 rounded-lg p-6">
                <div class="flex items-start">
                    <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Личная ответственность</h3>
                        <p class="text-gray-600">Это наш бренд и наша фамилия. Дорожим репутацией!</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- How It Works Section -->
<section class="py-12 bg-graphite-600 text-white">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Как заказать потолок</h2>
        <div class="w-20 h-1 bg-white mx-auto opacity-50 mb-8"></div>
        <div class="grid md:grid-cols-4 gap-6">
            <div class="text-center">
                <div class="bg-white text-graphite-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">1</div>
                <h3 class="font-bold mb-2">Заявка</h3>
                <p class="opacity-80">На сайте или по телефону</p>
            </div>
            <div class="text-center">
                <div class="bg-white text-graphite-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">2</div>
                <h3 class="font-bold mb-2">Бесплатный замер</h3>
                <p class="opacity-80">С образцами материалов</p>
            </div>
            <div class="text-center">
                <div class="bg-white text-graphite-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">3</div>
                <h3 class="font-bold mb-2">Согласование</h3>
                <p class="opacity-80">Цены и сроков</p>
            </div>
            <div class="text-center">
                <div class="bg-white text-graphite-600 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">4</div>
                <h3 class="font-bold mb-2">Монтаж</h3>
                <p class="opacity-80">За 1 день</p>
            </div>
        </div>
    </div>
</section>

<!-- Portfolio Section -->
<section id="portfolio" class="py-12 bg-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Наши работы в Новомосковске</h2>
            <div class="w-20 h-1 bg-yellowAccent-500 mx-auto mb-6"></div>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="rounded-lg overflow-hidden shadow-md">
                <img src=" https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Гостиная" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-bold mb-1">Гостиная</h3>
                    <p class="text-gray-600 text-sm">ЖК «Престиж», ул. Московская</p>
                </div>
            </div>
            <div class="rounded-lg overflow-hidden shadow-md">
                <img src=" https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Кухня" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-bold mb-1">Кухня</h3>
                    <p class="text-gray-600 text-sm">ул. Ленина, д. 45</p>
                </div>
            </div>
            <div class="rounded-lg overflow-hidden shadow-md">
                <img src=" https://images.unsplash.com/photo-1600607687644-c7171b42498f?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Спальня" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h3 class="font-bold mb-1">Спальня</h3>
                    <p class="text-gray-600 text-sm">мкр. Сокольники</p>
                </div>
            </div>
        </div>
        <div class="text-center mt-8">
            <a href="#" class="inline-block bg-gray-100 hover:bg-gray-200 text-gray-800 font-medium py-2 px-6 rounded-lg transition-colors">
                Смотреть все работы
            </a>
        </div>
    </div>
</section>

<!-- Reviews Section -->
<section id="reviews" class="py-12 bg-gray-50">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Отзывы клиентов</h2>
            <div class="w-20 h-1 bg-yellowAccent-500 mx-auto mb-6"></div>
        </div>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-white rounded-lg p-6 testimonial-card">
                <div class="flex items-center mb-4">
                    <div class="flex-shrink-0 bg-gray-200 rounded-full w-12 h-12"></div>
                    <div class="ml-4">
                        <h3 class="font-bold">Ирина К.</h3>
                        <div class="flex text-yellowAccent-500">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                </div>
                <p class="text-gray-600">"Сделали быстро и аккуратно! Приехали точно в срок, установили за несколько часов. Потолок выглядит идеально."</p>
            </div>
            <div class="bg-white rounded-lg p-6 testimonial-card">
                <div class="flex items-center mb-4">
                    <div class="flex-shrink-0 bg-gray-200 rounded-full w-12 h-12"></div>
                    <div class="ml-4">
                        <h3 class="font-bold">Александр В.</h3>
                        <div class="flex text-yellowAccent-500">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                </div>
                <p class="text-gray-600">"Цена как обещали. Рекомендую! После замера другие компании начали предлагать дешевле, но в итоге выходило дороже. Эти ребята работают честно."</p>
            </div>
            <div class="bg-white rounded-lg p-6 testimonial-card">
                <div class="flex items-center mb-4">
                    <div class="flex-shrink-0 bg-gray-200 rounded-full w-12 h-12"></div>
                    <div class="ml-4">
                        <h3 class="font-bold">Ольга С.</h3>
                        <div class="flex text-yellowAccent-500">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                </div>
                <p class="text-gray-600">"Хорошие мастера, без лишних слов. Сделали всё качественно, убрали за собой. Через год никаких проблем с потолком."</p>
            </div>
        </div>
    </div>
</section>

<!-- About Section -->
<section class="py-12 bg-white">
    <div class="container mx-auto px-4">
        <div class="flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">История PROsekov</h2>
                <div class="w-20 h-1 bg-yellowAccent-500 mb-6"></div>
                <p class="text-gray-600 mb-4">
                    Это не просто бренд. Это наша фамилия. Мы местные, работаем честно и под своим именем.
                </p>
                <p class="text-gray-600">
                    Наша компания начала работу в 2015 году с небольшой бригады монтажников. Сегодня мы устанавливаем более 200 потолков в год по всей Тульской области, но по-прежнему остаемся семейным бизнесом с индивидуальным подходом.
                </p>
            </div>
            <div class="md:w-1/2">
                <div class="bg-gray-100 rounded-lg overflow-hidden p-4">
                    <img src=" https://images.unsplash.com/photo-1600880292207-644b95cd2dfe5569db47bd5d6ceee9d69f54ae67d6d25153beeb6e1efedf7265e9d2 ">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <div>
                        <h3 class="font-bold mb-2">Личная ответственность</h3>
                        <p class="text-gray-600">Это наш бренд и наша фамилия. Дорожим репутацией!</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Promotion Section -->
<section class="py-12 bg-yellowAccent-500 text-white">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Акция месяца!</h2>
        <p class="text-xl mb-6">Скидка <span class="font-bold">10%</span> или <span class="font-bold">LED-подсветка</span> в подарок</p>
        <p class="mb-8 opacity-90">Успейте до <span class="promotion-date">__.__.__.____</span></p>
        <a href="#contact" class="inline-block bg-white text-yellowAccent-600 font-bold py-3 px-8 rounded-lg hover:bg-gray-100 transition-colors pulse">
            Получить подарок
        </a>
    </div>
</section>

<!-- Calculator Section -->
<section id="calculator" class="py-12 bg-gray-50">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Рассчитать стоимость</h2>
            <div class="w-20 h-1 bg-yellowAccent-500 mx-auto"></div>
        </div>
        <div class="max-w-lg mx-auto bg-white rounded-xl shadow-lg overflow-hidden">
            <div class="p-6">
                <div class="mb-6">
                    <label class="block text-gray-700 font-medium mb-2">Площадь помещения (м²)</label>
                    <input type="range" min="10" max="100" value="20" class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                    <div class="flex justify-between mt-2">
                        <span>10 м²</span>
                        <span class="font-bold">20 м²</span>
                        <span>100 м²</span>
                    </div>
                </div>
                <div class="mb-6">
                    <label class="block text-gray-700 font-medium mb-2">Тип потолка</label>
                    <div class="grid grid-cols-3 gap-2">
                        <button class="bg-yellowAccent-100 text-yellowAccent-600 py-2 px-3 rounded-lg font-medium">Матовый</button>
                        <button class="bg-gray-100 text-gray-600 py-2 px-3 rounded-lg font-medium">Глянцевый</button>
                        <button class="bg-gray-100 text-gray-600 py-2 px-3 rounded-lg font-medium">Сатиновый</button>
                    </div>
                </div>
                <div class="mb-6">
                    <label class="block text-gray-700 font-medium mb-2">Дополнительно</label>
                    <div class="space-y-2">
                        <label class="flex items-center">
                            <input type="checkbox" class="rounded text-yellowAccent-600">
                            <span class="ml-2 text-gray-600">Многоуровневый потолок</span>
                        </label>
                        <label class="flex items-center">
                            <input type="checkbox" class="rounded text-yellowAccent-600">
                            <span class="ml-2 text-gray-600">LED-подсветка</span>
                        </label>
                        <label class="flex items-center">
                            <input type="checkbox" class="rounded text-yellowAccent-600">
                            <span class="ml-2 text-gray-600">Установка светильников</span>
                        </label>
                    </div>
                </div>
                <div class="bg-gray-50 rounded-lg p-4 mb-6">
                    <div class="flex justify-between items-center mb-2">
                        <span class="text-gray-600">Примерная стоимость:</span>
                        <span class="text-2xl font-bold text-yellowAccent-600">8 450 ₽</span>
                    </div>
                    <div class="text-sm text-gray-500">* Точную стоимость уточнит мастер при замере</div>
                </div>
                <button class="w-full btn-primary bg-graphite-600 text-white font-medium py-3 px-6 rounded-lg">
                    Заказать точный расчет
                </button>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-12 bg-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-2xl md:text-3xl font-heading font-bold mb-4">Контакты</h2>
            <div class="w-20 h-1 bg-yellowAccent-500 mx-auto"></div>
        </div>
        <div class="flex flex-col md:flex-row">
            <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                <div class="bg-gray-50 rounded-xl p-6">
                    <h3 class="font-bold text-xl mb-4">Наши контакты</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Телефон</h4>
                                <p class="text-gray-600">+7 (___) ___-__-__</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                                <i class="fab fa-whatsapp"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">WhatsApp</h4>
                                <a href="#" class="text-yellowAccent-600 hover:underline">Написать сообщение</a>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Адрес</h4>
                                <p class="text-gray-600">Новомосковск, ул. ___</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-yellowAccent-100 text-yellowAccent-600 rounded-full p-2 mr-4 flex-shrink-0">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-1">Режим работы</h4>
                                <p class="text-gray-600">Пн–Вс: 9:00–20:00</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="bg-gray-50 rounded-xl p-6">
                    <h3 class="font-bold text-xl mb-4">Заказать замер</h3>
                    <form id="contact-form" class="space-y-4">
                        <div>
                            <label class="block text-gray-700 font-medium mb-1">Ваше имя</label>
                            <input type="text" name="name" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-yellowAccent-500 focus:border-yellowAccent-500">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-medium mb-1">Телефон</label>
                            <input type="tel" name="phone" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-yellowAccent-500 focus:border-yellowAccent-500">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-medium mb-1">Адрес</label>
                            <input type="text" name="address" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-yellowAccent-500 focus:border-yellowAccent-500">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-medium mb-1">Желаемая дата замера</label>
                            <input type="date" name="date" required class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-yellowAccent-500 focus:border-yellowAccent-500">
                        </div>
                        <button type="submit" class="w-full btn-yellow bg-yellowAccent-500 text-white font-medium py-3 px-6 rounded-lg">
                            Отправить заявку
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Map Section -->
<div class="h-64 bg-gray-200 flex items-center justify-center">
    <p class="text-gray-500">Карта Новомосковска</p>
</div>

<!-- Footer -->
<footer class="bg-gray-900 text-white py-8">
    <div class="container mx-auto px-4">
        <div class="flex flex-col md:flex-row justify-between items-center">
            <div class="mb-6 md:mb-0">
                <a href="#" class="text-2xl font-heading font-bold">
                    <span class="text-graphite-400">PRO</span><span class="text-yellowAccent-400">sekov</span>
                </a>
                <p class="mt-2 text-gray-400">Натяжные потолки в Новомосковске и Тульской области</p>
            </div>
            <div class="flex space-x-6">
                <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-instagram text-xl"></i></a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-vk text-xl"></i></a>
                <a href="#" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-whatsapp text-xl"></i></a>
            </div>
        </div>
        <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400 text-sm">
            <p>© PROsekov, 2025. Все права защищены.</p>
        </div>
    </div>
</footer>

<!-- WhatsApp Floating Button -->
<a href="https://wa.me/79001234567?text=Здравствуйте!%20Хочу%20узнать%20стоимость%20натяжного%20потолка." 
   target="_blank" 
   class="fixed bottom-6 right-6 bg-yellowAccent-500 text-white rounded-full p-4 shadow-lg hover:bg-yellowAccent-600 transition-colors floating">
    <i class="fab fa-whatsapp text-2xl"></i>
</a>

<script>
    // Mobile menu toggle
    document.querySelector('header button').addEventListener('click', function () {
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenu.classList.toggle('hidden');
    });

    // Smooth scrolling
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            const targetId = this.getAttribute('href');
            if (targetId === '#') return;
            const targetElement = document.querySelector(targetId);
            if (targetElement) {
                targetElement.scrollIntoView({ behavior: 'smooth' });
            }
        });
    });

    // Range input display
    const rangeInput = document.querySelector('input[type="range"]');
    const priceDisplay = document.querySelector('.text-2xl.font-bold');
    if (rangeInput && priceDisplay) {
        rangeInput.addEventListener('input', function () {
            const area = this.value;
            const price = Math.round(area * 399 * 1.1);
            priceDisplay.textContent = `${price.toLocaleString('ru-RU')} ₽`;
        });
    }

    // Date effect
    const promotionDate = new Date();
    promotionDate.setMonth(promotionDate.getMonth() + 1);
    const options = { day: 'numeric', month: 'long', year: 'numeric' };
    const formattedDate = promotionDate.toLocaleDateString('ru-RU', options);
    const dateEl = document.querySelector('.promotion-date');
    if (dateEl) dateEl.textContent = formattedDate;

    // Telegram Bot Integration
    document.getElementById('contact-form').addEventListener('submit', function(e) {
        e.preventDefault();

        const form = e.target;
        const data = new FormData(form);

        const telegramToken = '7630978316:AAFfgcio_t6dgFvogv6u2S4EQtz12PTDwB4';
        const chatId = '975913881';

        let message = '<b>НОВАЯ ЗАЯВКА С САЙТА PROsekov</b>\n\n';
        for (const [key, value] of data.entries()) {
            message += `<b>${key}:</b> ${value}\n`;
        }

        fetch(` https://api.telegram.org/bot ${telegramToken}/sendMessage`, {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify({
                chat_id: chatId,
                text: message,
                parse_mode: 'HTML'
            })
        })
        .then(() => {
            alert('Заявка успешно отправлена!');
            form.reset();
        })
        .catch(err => {
            alert('Ошибка при отправке заявки.');
            console.error(err);
        });
    });
</script>

</body>
</html>
