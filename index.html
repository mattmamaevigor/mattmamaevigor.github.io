<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>СППНЛ - Служба по поимке нежелательных личностей</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
            color: #fff;
            overflow-x: hidden;
        }

        .header {
            background: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(10px);
            padding: 20px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }

        .nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 15px;
            flex-wrap: wrap;
        }

        .nav a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
            padding: 10px 20px;
            border-radius: 25px;
            transition: background 0.3s ease, color 0.3s ease;
        }

        .nav a:hover, .nav a.active {
            background: #ffd700;
            color: #000;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .logo {
            font-size: 32px;
            font-weight: bold;
            text-align: center;
            letter-spacing: 3px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .hero {
            padding: 150px 20px 80px;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            animation: fadeInUp 1s ease;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 40px;
            opacity: 0.9;
            animation: fadeInUp 1s ease 0.2s backwards;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(10px);
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeIn 1s ease;
            border: 2px solid rgba(255, 215, 0, 0.3);
        }

        .stat-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);
            border-color: #ffd700;
        }

        .stat-number {
            font-size: 48px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #ffd700;
        }

        .stat-label {
            font-size: 18px;
            opacity: 0.9;
        }

        .section-title {
            text-align: center;
            font-size: 40px;
            margin-bottom: 60px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        /* RANKS SECTION */
        .ranks-section {
            padding: 80px 20px;
            background: rgba(0, 0, 0, 0.3);
        }

        .ranks-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
            margin-top: 40px;
        }

        .rank-card {
            background: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            padding: 40px;
            position: relative;
            overflow: hidden;
            transition: all 0.4s ease;
            border: 3px solid transparent;
        }

        .rank-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, var(--rank-color), transparent);
        }

        .rank-card:hover {
            transform: translateY(-10px) scale(1.02);
            border-color: var(--rank-color);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
        }

        .rank-card.agent { --rank-color: #ff4444; }
        .rank-card.scout { --rank-color: #ffaa00; }
        .rank-card.reporter { --rank-color: #44ff44; }
        .rank-card.coordinator { --rank-color: #4488ff; }
        .rank-card.specialist { --rank-color: #aa44ff; }
        .rank-card.instructor { --rank-color: #888888; }
        .rank-card.pursuer { --rank-color: #ff6600; }
        .rank-card.patrol { --rank-color: #cc0000; }
        .rank-card.observer { --rank-color: #996633; }
        .rank-card.liquidator { --rank-color: #dddddd; }

        .rank-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 20px;
            background: var(--rank-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            font-weight: bold;
            color: #000;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .rank-title {
            font-size: 28px;
            font-weight: bold;
            text-align: center;
            margin-bottom: 10px;
            color: var(--rank-color);
        }

        .rank-subtitle {
            text-align: center;
            font-size: 16px;
            opacity: 0.7;
            margin-bottom: 25px;
            font-style: italic;
        }

        .rank-description {
            font-size: 16px;
            line-height: 1.8;
            margin-bottom: 25px;
            opacity: 0.9;
        }

        .rank-duties {
            list-style: none;
            padding: 0;
        }

        .rank-duties li {
            padding: 12px 0;
            padding-left: 30px;
            position: relative;
            font-size: 15px;
            opacity: 0.85;
            border-left: 3px solid var(--rank-color);
            margin-bottom: 10px;
            padding-left: 15px;
        }

        .rank-duties li::before {
            content: "▸";
            position: absolute;
            left: 0;
            color: var(--rank-color);
            font-weight: bold;
        }

        .rank-requirements {
            margin-top: 25px;
            padding: 20px;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 10px;
            border-left: 4px solid var(--rank-color);
        }

        .rank-requirements h4 {
            color: var(--rank-color);
            margin-bottom: 10px;
            font-size: 16px;
        }

        .rank-requirements ul {
            list-style: none;
            padding: 0;
        }

        .rank-requirements li {
            padding: 5px 0;
            font-size: 14px;
            opacity: 0.8;
        }

        .rank-requirements li::before {
            content: "✓ ";
            color: var(--rank-color);
            font-weight: bold;
        }

        /* Career Path */
        .career-path {
            margin-top: 80px;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.4);
            border-radius: 20px;
        }

        .career-path h3 {
            text-align: center;
            font-size: 32px;
            margin-bottom: 50px;
            color: #ffd700;
        }

        .path-flow {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .path-step {
            background: rgba(255, 255, 255, 0.05);
            padding: 20px 30px;
            border-radius: 15px;
            border: 2px solid var(--rank-color);
            position: relative;
        }

        .path-arrow {
            font-size: 30px;
            color: #ffd700;
        }

        .cta {
            text-align: center;
            padding: 80px 20px;
        }

        .cta-button {
            display: inline-block;
            padding: 20px 50px;
            background: linear-gradient(135deg, #ffd700, #ffed4e);
            color: #333;
            font-size: 20px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 5px 20px rgba(255, 215, 0, 0.3);
        }

        .cta-button:hover {
            transform: scale(1.1);
            box-shadow: 0 10px 40px rgba(255, 215, 0, 0.5);
        }

        .footer {
            background: rgba(0, 0, 0, 0.3);
            padding: 30px 20px;
            text-align: center;
            margin-top: 80px;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 32px; }
            .ranks-grid { grid-template-columns: 1fr; }
            .path-flow { flex-direction: column; }
            .path-arrow { transform: rotate(90deg); }
        }

        /* Discord Section */
        .discord-section {
            min-height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 100px 20px;
        }

        .discord-content {
            text-align: center;
            max-width: 600px;
        }

        .discord-icon {
            font-size: 120px;
            margin-bottom: 30px;
        }

        .discord-content h2 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #ffd700;
        }

        .discord-content p {
            font-size: 24px;
            line-height: 1.6;
            opacity: 0.9;
        }

        .dev-badge {
            margin-top: 40px;
            padding: 20px;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 15px;
            border: 2px solid rgba(255, 215, 0, 0.3);
        }

        .dev-badge p {
            font-size: 16px;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="container">
            <div class="logo">🛡️ СППНЛ</div>
            <div class="nav">
                <a href="#home" class="active" onclick="showSection('home'); return false;">Главная</a>
                <a href="#ranks" onclick="showSection('ranks'); return false;">Ранги</a>
                <a href="#agent" onclick="showSection('agent'); return false;">Стать агентом</a>
                <a href="#discord" onclick="showSection('discord'); return false;">Discord</a>
            </div>
        </div>
    </div>

    <div class="hero">
        <div class="container">
            <h1>Служба по поимке нежелательных личностей</h1>
            <p>Обеспечиваем порядок и безопасность в ваших Telegram-чатах</p>
        </div>
    </div>

    <!-- HOME SECTION -->
    <div id="home-section">
        <div class="stats">
                            <div class="container">
            <div class="stat-card">
                <div class="stat-number" id="banned">0</div>
                <div class="stat-label">Нарушителей забанено</div>
            </div>
            <div class="stat-card">
                <div class="stat-number" id="chats">2</div>
                <div class="stat-label">Чатов под защитой</div>
            </div>
            <div class="stat-card">
                <div class="stat-number" id="agents">10</div>
                <div class="stat-label">Активных агентов</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">24/7</div>
                <div class="stat-label">Круглосуточный мониторинг</div>
            </div>
        </div>
        </div>

        <div class="cta">
            <div class="container">
                <h2 class="section-title">Присоединяйтесь к СППНЛ</h2>
                <p style="font-size: 18px; margin-bottom: 40px; opacity: 0.9;">Станьте частью элитной службы безопасности</p>
                <a href="#ranks" onclick="showSection('ranks'); return false;" class="cta-button">Узнать о рангах</a>
            </div>
        </div>
    </div>

    <!-- RANKS SECTION -->
    <div id="ranks-section" style="display: none;">
        <div class="ranks-section">
            <div class="container">
                <h2 class="section-title">🎖️ Система рангов СППНЛ</h2>
                <p style="text-align: center; font-size: 18px; opacity: 0.8; margin-bottom: 60px;">
                    Каждый агент начинает свой путь и может вырасти до любого ранга
                </p>

                <div class="ranks-grid">
                    <!-- АГЕНТЫ -->
                    <div class="rank-card agent">
                        <div class="rank-icon">А</div>
                        <h3 class="rank-title">АГЕНТЫ</h3>
                        <p class="rank-subtitle">Основная сила службы</p>
                        <p class="rank-description">
                            Агенты - это фундамент СППНЛ. Они находятся на передовой борьбы с нарушениями, 
                            ежедневно обеспечивая порядок в чатах.
                        </p>
                        <ul class="rank-duties">
                            <li>Круглосуточный мониторинг чатов</li>
                            <li>Сбор доказательств нарушений</li>
                            <li>Прямая работа с нарушителями</li>
                            <li>Быстрое реагирование на инциденты</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Активность в Telegram</li>
                                <li>Внимательность</li>
                                <li>Знание правил чатов</li>
                            </ul>
                        </div>
                    </div>

                    <!-- РАЗВЕДЧИКИ -->
                    <div class="rank-card scout">
                        <div class="rank-icon">Р</div>
                        <h3 class="rank-title">РАЗВЕДЧИКИ</h3>
                        <p class="rank-subtitle">Тайная служба</p>
                        <p class="rank-description">
                            Разведчики работают под прикрытием, проникая в потенциально опасные сообщества 
                            для предотвращения угроз до их возникновения.
                        </p>
                        <ul class="rank-duties">
                            <li>Внедрение в подозрительные чаты</li>
                            <li>Сбор разведданных</li>
                            <li>Работа под прикрытием</li>
                            <li>Предотвращение массовых нарушений</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Опыт работы Агентом (1+ месяц)</li>
                                <li>Осторожность и конспирация</li>
                                <li>Аналитическое мышление</li>
                            </ul>
                        </div>
                    </div>

                    <!-- ДОКЛАДЧИКИ -->
                    <div class="rank-card reporter">
                        <div class="rank-icon">Д</div>
                        <h3 class="rank-title">ДОКЛАДЧИКИ</h3>
                        <p class="rank-subtitle">Аналитики</p>
                        <p class="rank-description">
                            Докладчики систематизируют всю информацию, анализируют тренды нарушений 
                            и готовят детальные отчёты для руководства.
                        </p>
                        <ul class="rank-duties">
                            <li>Составление отчётов</li>
                            <li>Анализ статистики нарушений</li>
                            <li>Ведение базы данных</li>
                            <li>Подготовка аналитики</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Грамотная письменная речь</li>
                                <li>Внимание к деталям</li>
                                <li>Навыки работы с данными</li>
                            </ul>
                        </div>
                    </div>

                    <!-- КООРДИНАТОРЫ -->
                    <div class="rank-card coordinator">
                        <div class="rank-icon">К</div>
                        <h3 class="rank-title">КООРДИНАТОРЫ</h3>
                        <p class="rank-subtitle">Управление операциями</p>
                        <p class="rank-description">
                            Координаторы управляют командами агентов, распределяют задачи 
                            и обеспечивают слаженную работу всей службы.
                        </p>
                        <ul class="rank-duties">
                            <li>Распределение задач</li>
                            <li>Координация операций</li>
                            <li>Связь с администрацией чатов</li>
                            <li>Управление командой</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Опыт работы (2+ месяца)</li>
                                <li>Лидерские качества</li>
                                <li>Организаторские способности</li>
                            </ul>
                        </div>
                    </div>

                    <!-- СПЕЦИАЛИСТЫ -->
                    <div class="rank-card specialist">
                        <div class="rank-icon">С</div>
                        <h3 class="rank-title">СПЕЦИАЛИСТЫ</h3>
                        <p class="rank-subtitle">Техническая поддержка</p>
                        <p class="rank-description">
                            Специалисты разрабатывают инструменты для автоматизации работы, 
                            создают ботов и поддерживают техническую инфраструктуру.
                        </p>
                        <ul class="rank-duties">
                            <li>Разработка ботов</li>
                            <li>Техническая поддержка</li>
                            <li>Создание автоматизаций</li>
                            <li>Улучшение процессов</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Навыки программирования</li>
                                <li>Знание Python/JS</li>
                                <li>Опыт с Telegram Bot API</li>
                            </ul>
                        </div>
                    </div>

                    <!-- ИНСТРУКТОРЫ -->
                    <div class="rank-card instructor">
                        <div class="rank-icon">И</div>
                        <h3 class="rank-title">ИНСТРУКТОРЫ</h3>
                        <p class="rank-subtitle">Обучение кадров</p>
                        <p class="rank-description">
                            Инструкторы готовят новых агентов, проводят тренинги 
                            и разрабатывают обучающие материалы для службы.
                        </p>
                        <ul class="rank-duties">
                            <li>Обучение новичков</li>
                            <li>Проведение тренингов</li>
                            <li>Разработка методичек</li>
                            <li>Аттестация агентов</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Большой опыт (3+ месяца)</li>
                                <li>Педагогические навыки</li>
                                <li>Терпение и коммуникабельность</li>
                            </ul>
                        </div>
                    </div>

                    <!-- ПРЕСЛЕДОВАТЕЛИ -->
                    <div class="rank-card pursuer">
                        <div class="rank-icon">П</div>
                        <h3 class="rank-title">ПРЕСЛЕДОВАТЕЛИ</h3>
                        <p class="rank-subtitle">Охотники за нарушителями</p>
                        <p class="rank-description">
                            Преследователи - элитное подразделение, специализирующееся на выслеживании 
                            и поимке злостных нарушителей, действующих в нескольких чатах.
                        </p>
                        <ul class="rank-duties">
                            <li>Выслеживание нарушителей</li>
                            <li>Создание досье на токсиков</li>
                            <li>Работа со сложными случаями</li>
                            <li>Координация банов между чатами</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Опыт Агента (2+ месяца)</li>
                                <li>Настойчивость и терпение</li>
                                <li>Навыки расследования</li>
                            </ul>
                        </div>
                    </div>

                    <!-- ПАТРУЛЬНЫЕ -->
                    <div class="rank-card patrol">
                        <div class="rank-icon">П</div>
                        <h3 class="rank-title">ПАТРУЛЬНЫЕ</h3>
                        <p class="rank-subtitle">Стражи порядка</p>
                        <p class="rank-description">
                            Патрульные регулярно обходят закреплённые за ними территории, 
                            предотвращая нарушения своим присутствием и быстро реагируя на инциденты.
                        </p>
                        <ul class="rank-duties">
                            <li>Патрулирование чатов по графику</li>
                            <li>Профилактика нарушений</li>
                            <li>Быстрое реагирование</li>
                            <li>Видимое присутствие</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Стабильная активность онлайн</li>
                                <li>Дисциплинированность</li>
                                <li>Соблюдение графика</li>
                            </ul>
                        </div>
                    </div>

                    <!-- НАБЛЮДАТЕЛИ -->
                    <div class="rank-card observer">
                        <div class="rank-icon">Н</div>
                        <h3 class="rank-title">НАБЛЮДАТЕЛИ</h3>
                        <p class="rank-subtitle">Тихая стража</p>
                        <p class="rank-description">
                            Наблюдатели незаметно мониторят чаты, собирая долгосрочную статистику 
                            и выявляя скрытые паттерны нарушений.
                        </p>
                        <ul class="rank-duties">
                            <li>Скрытое наблюдение</li>
                            <li>Фиксация подозрительной активности</li>
                            <li>Сбор долгосрочной статистики</li>
                            <li>Выявление паттернов</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Незаметность и терпение</li>
                                <li>Аналитическое мышление</li>
                                <li>Внимание к деталям</li>
                            </ul>
                        </div>
                    </div>

                    <!-- ЛИКВИДАТОРЫ -->
                    <div class="rank-card liquidator">
                        <div class="rank-icon">Л</div>
                        <h3 class="rank-title">ЛИКВИДАТОРЫ</h3>
                        <p class="rank-subtitle">Спецподразделение</p>
                        <p class="rank-description">
                            Ликвидаторы - элитное спецподразделение для работы с критическими угрозами: 
                            рейдами, массовым спамом и другими серьёзными атаками на чаты.
                        </p>
                        <ul class="rank-duties">
                            <li>Устранение массовых атак</li>
                            <li>Борьба с ботами и флудом</li>
                            <li>Экстренное реагирование</li>
                            <li>Зачистка после инцидентов</li>
                        </ul>
                        <div class="rank-requirements">
                            <h4>📋 Требования:</h4>
                            <ul>
                                <li>Большой опыт (2+ месяца)</li>
                                <li>Стрессоустойчивость</li>
                                <li>Быстрая реакция</li>
                                <li>Навыки работы в кризисе</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Career Path -->
                <div class="career-path">
                    <h3>🚀 Структура подразделений</h3>
                    
                    <div style="margin: 40px 0; padding: 30px; background: rgba(255, 215, 0, 0.05); border-radius: 15px;">
                        <h4 style="color: #ffd700; text-align: center; font-size: 24px; margin-bottom: 30px;">
                            📊 Основные группы
                        </h4>
                        <div class="path-flow">
                            <div class="path-step agent" style="--rank-color: #ff4444;">
                                <strong>АГЕНТЫ</strong><br>
                                <small>Основа службы</small>
                            </div>
                            <div class="path-step scout" style="--rank-color: #ffaa00;">
                                <strong>РАЗВЕДЧИКИ</strong><br>
                                <small>Тайная служба</small>
                            </div>
                            <div class="path-step reporter" style="--rank-color: #44ff44;">
                                <strong>ДОКЛАДЧИКИ</strong><br>
                                <small>Аналитика</small>
                            </div>
                        </div>
                    </div>

                    <div style="margin: 40px 0; padding: 30px; background: rgba(255, 100, 0, 0.05); border-radius: 15px;">
                        <h4 style="color: #ff6600; text-align: center; font-size: 24px; margin-bottom: 30px;">
                            ⚔️ Боевые подразделения
                        </h4>
                        <div class="path-flow">
                            <div class="path-step pursuer" style="--rank-color: #ff6600;">
                                <strong>ПРЕСЛЕДОВАТЕЛИ</strong><br>
                                <small>Охотники</small>
                            </div>
                            <div class="path-step patrol" style="--rank-color: #cc0000;">
                                <strong>ПАТРУЛЬНЫЕ</strong><br>
                                <small>Стражи</small>
                            </div>
                            <div class="path-step observer" style="--rank-color: #996633;">
                                <strong>НАБЛЮДАТЕЛИ</strong><br>
                                <small>Тихая стража</small>
                            </div>
                            <div class="path-step liquidator" style="--rank-color: #dddddd; color: #000;">
                                <strong>ЛИКВИДАТОРЫ</strong><br>
                                <small>Спецназ</small>
                            </div>
                        </div>
                    </div>

                    <div style="margin: 40px 0; padding: 30px; background: rgba(100, 100, 255, 0.05); border-radius: 15px;">
                        <h4 style="color: #4488ff; text-align: center; font-size: 24px; margin-bottom: 30px;">
                            🎓 Управление и специалисты
                        </h4>
                        <div class="path-flow">
                            <div class="path-step coordinator" style="--rank-color: #4488ff;">
                                <strong>КООРДИНАТОРЫ</strong><br>
                                <small>Управление</small>
                            </div>
                            <div class="path-step specialist" style="--rank-color: #aa44ff;">
                                <strong>СПЕЦИАЛИСТЫ</strong><br>
                                <small>Техподдержка</small>
                            </div>
                            <div class="path-step instructor" style="--rank-color: #888888;">
                                <strong>ИНСТРУКТОРЫ</strong><br>
                                <small>Обучение</small>
                            </div>
                        </div>
                    </div>

                    <p style="text-align: center; margin-top: 40px; opacity: 0.8; font-size: 16px; line-height: 1.8;">
                        <strong style="color: #ffd700;">💡 Система гибкая:</strong><br>
                        Вы можете совмещать несколько ролей (например, быть Агентом и Патрульным)<br>
                        или специализироваться на одном направлении для достижения мастерства
                    </p>
                </div>

                <div class="cta" style="margin-top: 60px;">
                    <h3 style="font-size: 32px; margin-bottom: 20px;">Готовы начать карьеру?</h3>
                    <a href="https://t.me/sppnl_bot" target="_blank" class="cta-button">Подать заявку</a>
                </div>
            </div>
        </div>
    </div>

    <!-- AGENT SECTION -->
    <div id="agent-section" style="display: none;">
        <div style="padding: 120px 20px 80px;">
            <div class="container">
                <h2 class="section-title">Стать агентом СППНЛ</h2>
                
                <div style="max-width: 800px; margin: 0 auto;">
                    <div style="background: rgba(255, 215, 0, 0.1); border: 2px solid rgba(255, 215, 0, 0.3); border-radius: 15px; padding: 30px; margin-bottom: 40px;">
                        <h4 style="color: #ffd700; margin-bottom: 15px; font-size: 24px;">🎯 Начните с ранга АГЕНТ</h4>
                        <p style="opacity: 0.9; line-height: 1.8; font-size: 16px;">
                            Каждый начинает свой путь в СППНЛ с ранга <strong style="color: #ff4444;">АГЕНТА</strong>. 
                            После успешной работы вы сможете получить повышение и перейти на другие ранги 
                            в зависимости от ваших навыков и предпочтений.
                        </p>
                    </div>

                    <div style="text-align: center; margin: 60px 0;">
                        <a href="https://t.me/sppnl_bot" target="_blank" class="cta-button">
                            📱 Подать заявку через бота
                        </a>
                        <p style="margin-top: 20px; opacity: 0.7; font-size: 14px;">
                            Бот: @sppnl_bot
                        </p>
                    </div>

                    <div style="background: rgba(0, 0, 0, 0.4); border-radius: 20px; padding: 40px;">
                        <h3 style="text-align: center; font-size: 28px; margin-bottom: 30px; color: #ffd700;">
                            📝 Процесс подачи заявки
                        </h3>
                        <div style="display: grid; gap: 20px;">
                            <div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 10px; border-left: 4px solid #ffd700;">
                                <strong style="color: #ffd700; font-size: 18px;">Шаг 2:</strong>
                                <p style="margin-top: 10px; opacity: 0.9;">Заполните короткую анкету (возраст, опыт, мотивация)</p>
                            </div>
                            <div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 10px; border-left: 4px solid #ffd700;">
                                <strong style="color: #ffd700; font-size: 18px;">Шаг 3:</strong>
                                <p style="margin-top: 10px; opacity: 0.9;">Ожидайте ответа администрации (24-48 часов)</p>
                            </div>
                            <div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 10px; border-left: 4px solid #ffd700;">
                                <strong style="color: #ffd700; font-size: 18px;">Шаг 4:</strong>
                                <p style="margin-top: 10px; opacity: 0.9;">Получите инструкции и начните работу!</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- DISCORD SECTION -->
    <div id="discord-section" style="display: none;">
        <div class="discord-section">
            <div class="discord-content">
                <div class="discord-icon">🎮</div>
                <h2>Discord</h2>
                <p style="font-size: 24px; line-height: 1.6; opacity: 0.9;">СППНЛ скоро войдёт в земли Discord!</p>
                <p style="font-size: 20px; margin-top: 20px; color: #ffd700;">В разработке...</p>
                <div class="dev-badge">
                    <p style="font-size: 16px; opacity: 0.8;">Следите за обновлениями в нашем Telegram канале!</p>
                </div>
            </div>
        </div>
    </div>

    <div class="footer">
        <div class="container">
            <p>&copy; 2025 СППНЛ - Служба по поимке нежелательных личностей</p>
            <p style="margin-top: 10px; opacity: 0.7;">Порядок • Безопасность • Контроль</p>
            <p style="margin-top: 15px; font-size: 14px;">
                <a href="https://t.me/sppnltgk" target="_blank" style="color: #ffd700; text-decoration: none;">📱 Telegram канал</a>
            </p>
        </div>
    </div>

    <script>
        // Переключение секций
        function showSection(section) {
            const sections = {
                'home': document.getElementById('home-section'),
                'ranks': document.getElementById('ranks-section'),
                'agent': document.getElementById('agent-section'),
                'discord': document.getElementById('discord-section')
            };
            
            const navLinks = document.querySelectorAll('.nav a');
            
            // Скрыть все секции
            Object.values(sections).forEach(s => s.style.display = 'none');
            
            // Убрать активный класс
            navLinks.forEach(link => link.classList.remove('active'));
            
            // Показать нужную секцию
            if (sections[section]) {
                sections[section].style.display = 'block';
            }
            
            // Активировать нужную ссылку
            const linkIndex = {
                'home': 0,
                'ranks': 1,
                'agent': 2,
                'discord': 3
            };
            
            if (linkIndex[section] !== undefined) {
                navLinks[linkIndex[section]].classList.add('active');
            }
            
            // Прокрутка наверх
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Анимация счётчиков
        function animateCounter(id, target, duration) {
            const element = document.getElementById(id);
            if (!element) return;
            
            if (target === 0) {
                element.textContent = '0';
                return;
            }
            
            const start = 0;
            const increment = target / (duration / 16);
            let current = start;

            const timer = setInterval(() => {
                current += increment;
                if (current >= target) {
                    element.textContent = target;
                    clearInterval(timer);
                } else {
                    element.textContent = Math.floor(current);
                }
            }, 16);
        }

        // Запуск анимации при загрузке
        window.addEventListener('load', () => {
            animateCounter('banned', 0, 2000);
            animateCounter('chats', 2, 2000);
            animateCounter('agents', 10, 2000);
        });

        // Плавная прокрутка
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
                if (href.startsWith('#') && href.length > 1) {
                    e.preventDefault();
                    const target = document.querySelector(href);
                    if (target) {
                        target.scrollIntoView({ behavior: 'smooth' });
                    }
                }
            });
        });

        // Параллакс эффект для карточек рангов
        document.addEventListener('mousemove', (e) => {
            const cards = document.querySelectorAll('.rank-card');
            cards.forEach(card => {
                const rect = card.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                
                if (x > 0 && x < rect.width && y > 0 && y < rect.height) {
                    const moveX = (x - rect.width / 2) / 20;
                    const moveY = (y - rect.height / 2) / 20;
                    card.style.transform = `translateY(-10px) scale(1.02) rotateX(${-moveY}deg) rotateY(${moveX}deg)`;
                }
            });
        });

        // Сброс трансформации при уходе мыши
        document.querySelectorAll('.rank-card').forEach(card => {
            card.addEventListener('mouseleave', () => {
                card.style.transform = '';
            });
        });

        // Появление элементов при прокрутке
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Применяем наблюдатель к карточкам рангов
        document.addEventListener('DOMContentLoaded', () => {
            const rankCards = document.querySelectorAll('.rank-card');
            rankCards.forEach((card, index) => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(50px)';
                card.style.transition = `all 0.6s ease ${index * 0.1}s`;
                observer.observe(card);
            });
        });

        // Эффект печати для заголовков
        function typeWriter(element, text, speed = 50) {
            let i = 0;
            element.textContent = '';
            
            function type() {
                if (i < text.length) {
                    element.textContent += text.charAt(i);
                    i++;
                    setTimeout(type, speed);
                }
            }
            
            type();
        }

        // Добавляем эффект свечения при наведении на иконки рангов
        document.querySelectorAll('.rank-icon').forEach(icon => {
            icon.addEventListener('mouseenter', function() {
                this.style.boxShadow = `0 0 30px ${getComputedStyle(this).backgroundColor}`;
            });
            
            icon.addEventListener('mouseleave', function() {
                this.style.boxShadow = '0 5px 20px rgba(0, 0, 0, 0.3)';
            });
        });
    </script>
</body>
</html>fd700;">
                                <strong style="color: #ffd700; font-size: 18px;">Шаг 1:</strong>
                                <p style="margin-top: 10px; opacity: 0.9;">Напишите боту @sppnl_bot команду /start</p>
                            </div>
                            <div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 10px; border-left: 4px solid #f
