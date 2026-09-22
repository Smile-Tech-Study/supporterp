---
description: >-
  Система управления и контроля предприятием в области дополнительного
  образования.
order: 0.3
---

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
    box-sizing: border-box;
}

html, body {
    margin: 0;
    padding: 0;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    background: #ffffff;
    color: #172033;
}

.erp-home {
    max-width: 1180px;
    margin: 0 auto;
    padding: 18px 16px 40px;
}

/* HERO */

.hero {
    position: relative;
    overflow: hidden;
    padding: 52px 48px;
    border-radius: 28px;
    background:
        radial-gradient(circle at 90% 10%, rgba(255,255,255,.18), transparent 25%),
        linear-gradient(135deg, #1378d4 0%, #075aa8 100%);
    color: white;
    box-shadow: 0 18px 45px rgba(14, 105, 190, .18);
}

.hero::after {
    content: "";
    position: absolute;
    width: 280px;
    height: 280px;
    right: -100px;
    bottom: -150px;
    border-radius: 50%;
    background: rgba(255,255,255,.08);
}

.badge {
    display: inline-block;
    padding: 7px 12px;
    margin-bottom: 18px;
    border: 1px solid rgba(255,255,255,.25);
    border-radius: 999px;
    background: rgba(255,255,255,.12);
    font-size: 13px;
    font-weight: 600;
}

.hero h1 {
    margin: 0 0 14px;
    font-size: 42px;
    line-height: 1.1;
    letter-spacing: -1px;
}

.hero p {
    max-width: 680px;
    margin: 0;
    font-size: 18px;
    line-height: 1.6;
    color: rgba(255,255,255,.88);
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 28px;
}

.hero-btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 12px 18px;
    border-radius: 12px;
    background: white;
    color: #0968bd;
    text-decoration: none;
    font-weight: 700;
    font-size: 14px;
    transition: .2s ease;
}

.hero-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0,0,0,.14);
}

.hero-btn.secondary {
    color: white;
    background: rgba(255,255,255,.12);
    border: 1px solid rgba(255,255,255,.28);
}

/* SECTIONS */

.section {
    margin-top: 42px;
}

.section-title {
    margin-bottom: 8px;
    font-size: 25px;
    font-weight: 750;
    letter-spacing: -.4px;
}

.section-subtitle {
    margin: 0 0 22px;
    color: #667085;
    font-size: 15px;
    line-height: 1.5;
}

/* CARDS */

.cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
}

.card {
    position: relative;
    display: block;
    min-height: 190px;
    padding: 24px;
    border: 1px solid #e6ebf1;
    border-radius: 18px;
    background: #ffffff;
    text-decoration: none;
    color: inherit;
    transition: all .22s ease;
}

.card:hover {
    transform: translateY(-4px);
    border-color: #b8d8f5;
    box-shadow: 0 14px 34px rgba(20, 70, 120, .10);
}

.icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 46px;
    height: 46px;
    margin-bottom: 18px;
    border-radius: 13px;
    background: #edf7ff;
    font-size: 23px;
}

.card h3 {
    margin: 0 0 9px;
    font-size: 18px;
    color: #172033;
}

.card p {
    margin: 0 0 22px;
    color: #667085;
    font-size: 14px;
    line-height: 1.5;
}

.more {
    position: absolute;
    bottom: 20px;
    color: #0874cf;
    font-size: 13px;
    font-weight: 700;
}

/* POPULAR */

.popular {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
}

.popular-link {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 14px;
    padding: 17px 19px;
    border: 1px solid #e6ebf1;
    border-radius: 14px;
    background: #fafcff;
    color: #273142;
    text-decoration: none;
    font-size: 14px;
    font-weight: 600;
    transition: .2s ease;
}

.popular-link:hover {
    border-color: #a9d2f5;
    background: #f2f9ff;
    color: #0874cf;
}

.arrow {
    color: #0874cf;
    font-size: 18px;
}

/* HELP */

.help {
    margin-top: 42px;
    padding: 28px 30px;
    border-radius: 20px;
    background: #f3f8fd;
    border: 1px solid #dcecf9;
}

.help h3 {
    margin: 0 0 8px;
    font-size: 20px;
}

.help p {
    margin: 0;
    color: #667085;
    font-size: 14px;
    line-height: 1.6;
}

/* MOBILE */

@media (max-width: 900px) {
    .cards {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 620px) {
    .erp-home {
        padding: 8px 8px 28px;
    }

    .hero {
        padding: 34px 25px;
        border-radius: 22px;
    }

    .hero h1 {
        font-size: 32px;
    }

    .hero p {
        font-size: 16px;
    }

    .cards,
    .popular {
        grid-template-columns: 1fr;
    }
}
</style>
</head>

<body>

<div class="erp-home">

    <!-- HERO -->
    <section class="hero">
        <div class="badge">База знаний Education ERP</div>

        <h1>Как можем помочь?</h1>

        <p>
            Здесь собраны инструкции по работе с Education ERP:
            от добавления первого клиента до управления группами,
            абонементами, сотрудниками и статистикой школы.
        </p>

        <div class="hero-actions">
            <a class="hero-btn"
               href="https://education-erp.com/supporterp/EducationERP/nachalo-raboty/roli-v-sisteme-education-erp">
                🚀 Начать работу
            </a>

            <a class="hero-btn secondary"
               href="https://education-erp.com/supporterp/ucheniki-2">
                👥 Работа с учениками
            </a>
        </div>
    </section>


    <!-- MAIN -->
    <section class="section">

        <div class="section-title">Выберите, с чем хотите разобраться</div>
        <p class="section-subtitle">
            Основные разделы для ежедневной работы в Education ERP
        </p>

        <div class="cards">

            <a class="card"
               href="https://education-erp.com/supporterp/klienty/istochniki-zayavok">
                <div class="icon">👤</div>
                <h3>Клиенты</h3>
                <p>
                    Заявки, работа с клиентской базой,
                    источники обращений и этапы работы с клиентами.
                </p>
                <span class="more">Перейти →</span>
            </a>


            <a class="card"
               href="https://education-erp.com/supporterp/ucheniki-2">
                <div class="icon">🎓</div>
                <h3>Ученики и группы</h3>
                <p>
                    Добавление учеников, запись в учебные группы
                    и работа с информацией об ученике.
                </p>
                <span class="more">Перейти →</span>
            </a>


            <a class="card"
               href="https://education-erp.com/supporterp/EducationERP/nachalo-raboty/shkola/gruppa/poseshaemost-uchenikov">
                <div class="icon">📅</div>
                <h3>Занятия и посещаемость</h3>
                <p>
                    Работа с занятиями, отметки посещений,
                    расписание учеников и информация о занятии.
                </p>
                <span class="more">Перейти →</span>
            </a>


            <a class="card"
               href="https://education-erp.com/supporterp/abonementy/sposoby-oplaty">
                <div class="icon">🎫</div>
                <h3>Абонементы и оплаты</h3>
                <p>
                    Оплата абонементов, заморозка,
                    отчёты и другие операции с абонементами.
                </p>
                <span class="more">Перейти →</span>
            </a>


            <a class="card"
               href="https://education-erp.com/supporterp/EducationERP/nachalo-raboty/roli-v-sisteme-education-erp">
                <div class="icon">👨‍🏫</div>
                <h3>Сотрудники</h3>
                <p>
                    Роли в системе, добавление сотрудников
                    и организация их работы.
                </p>
                <span class="more">Перейти →</span>
            </a>


            <a class="card"
               href="https://education-erp.com/supporterp/upravlenie-shkoloi/statistika-po-gruppam">
                <div class="icon">📊</div>
                <h3>Статистика</h3>
                <p>
                    Анализ групп, посещаемости,
                    состава учеников и основных показателей.
                </p>
                <span class="more">Перейти →</span>
            </a>

        </div>
    </section>


    <!-- POPULAR -->
    <section class="section">

        <div class="section-title">Часто используемые инструкции</div>
        <p class="section-subtitle">
            Быстрый переход к популярным действиям
        </p>

        <div class="popular">

            <a class="popular-link"
               href="https://education-erp.com/supporterp/ucheniki-2">
                <span>👤 Добавить ученика и записать его в группу</span>
                <span class="arrow">→</span>
            </a>

            <a class="popular-link"
               href="https://education-erp.com/supporterp/EducationERP/nachalo-raboty/shkola/gruppa/poseshaemost-uchenikov">
                <span>✓ Отметить посещение ученика</span>
                <span class="arrow">→</span>
            </a>

            <a class="popular-link"
               href="https://education-erp.com/supporterp/instrukcii-po-rabote/domashnie-zadaniya-na-gruppu">
                <span>📝 Выдать домашнее задание группе</span>
                <span class="arrow">→</span>
            </a>

            <a class="popular-link"
               href="https://education-erp.com/supporterp/EducationERP/nachalo-raboty/roli-v-sisteme-education-erp/dobavlenie-sotrudnikov">
                <span>👨‍🏫 Добавить сотрудника</span>
                <span class="arrow">→</span>
            </a>

            <a class="popular-link"
               href="https://education-erp.com/supporterp/abonementy/zamorozka-abonementov">
                <span>❄️ Заморозить абонемент</span>
                <span class="arrow">→</span>
            </a>

            <a class="popular-link"
               href="https://education-erp.com/supporterp/upravlenie-shkoloi/statistika-po-gruppam">
                <span>📊 Посмотреть статистику по группам</span>
                <span class="arrow">→</span>
            </a>

        </div>

    </section>


    <!-- HELP -->
    <section class="help">
        <h3>🔎 Не нашли нужную инструкцию?</h3>
        <p>
            Воспользуйтесь поиском по базе знаний в верхней части страницы
            или откройте нужный раздел в меню слева.
        </p>
    </section>

</div>

</body>
</html>

[/html]