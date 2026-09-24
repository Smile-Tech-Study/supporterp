---
order: 1.5
title: Быстрый старт
---

[html]

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  color: #1d2939;
  background: transparent;
}

.quick-start {
  max-width: 1000px;
  margin: 0 auto;
  padding: 8px 4px 36px;
}

/* INTRO */

.intro {
  margin-bottom: 30px;
  padding: 24px 26px;
  border: 1px solid #d9eaf8;
  border-radius: 18px;
  background: linear-gradient(135deg, #f4faff 0%, #edf7ff 100%);
}

.intro-label {
  display: inline-block;
  margin-bottom: 9px;
  color: #0874cf;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: .6px;
  text-transform: uppercase;
}

.intro h2 {
  margin: 0 0 8px;
  color: #172033;
  font-size: 23px;
  line-height: 1.3;
}

.intro p {
  max-width: 760px;
  margin: 0;
  color: #5f6c7b;
  font-size: 15px;
  line-height: 1.6;
}


/* PROGRESS */

.progress {
  display: flex;
  align-items: center;
  margin-bottom: 30px;
}

.progress-line {
  flex: 1;
  height: 3px;
  border-radius: 5px;
  background: #d9eaf8;
}

.progress-dot {
  width: 11px;
  height: 11px;
  margin: 0 4px;
  border-radius: 50%;
  background: #0874cf;
}


/* STEPS */

.steps {
  display: grid;
  gap: 14px;
}

.step {
  display: grid;
  grid-template-columns: 54px 1fr;
  gap: 18px;
  align-items: start;
  padding: 21px 22px;
  border: 1px solid #e4e9ef;
  border-radius: 16px;
  background: #ffffff;
  transition: .2s ease;
}

.step:hover {
  transform: translateY(-2px);
  border-color: #b9d9f4;
  box-shadow: 0 9px 24px rgba(30, 80, 130, .08);
}

.number {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 46px;
  height: 46px;
  border-radius: 13px;
  background: #eaf6ff;
  color: #0874cf;
  font-size: 18px;
  font-weight: 750;
}

.step h3 {
  margin: 1px 0 6px;
  color: #172033;
  font-size: 17px;
}

.step p {
  margin: 0;
  color: #667085;
  font-size: 14px;
  line-height: 1.55;
}

.links {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 12px;
}

.link {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  padding: 7px 11px;
  border-radius: 8px;
  background: #f1f8fe;
  color: #0874cf;
  font-size: 12px;
  font-weight: 650;
}


/* FINISH */

.finish {
  display: flex;
  gap: 17px;
  align-items: flex-start;
  margin-top: 27px;
  padding: 23px 25px;
  border-radius: 17px;
  background: linear-gradient(135deg, #0874cf 0%, #075aa8 100%);
  color: #ffffff;
}

.finish-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 44px;
  width: 44px;
  height: 44px;
  border-radius: 12px;
  background: rgba(255,255,255,.15);
  font-size: 22px;
}

.finish h3 {
  margin: 1px 0 5px;
  font-size: 18px;
}

.finish p {
  margin: 0;
  color: rgba(255,255,255,.84);
  font-size: 14px;
  line-height: 1.55;
}


/* NOTE */

.note {
  margin-top: 18px;
  padding: 16px 18px;
  border-left: 4px solid #0874cf;
  border-radius: 10px;
  background: #f5faff;
  color: #536174;
  font-size: 13px;
  line-height: 1.55;
}

.note strong {
  color: #27364a;
}


/* MOBILE */

@media (max-width: 600px) {
  .quick-start {
    padding: 5px 2px 25px;
  }

  .intro {
    padding: 20px;
  }

  .intro h2 {
    font-size: 20px;
  }

  .step {
    grid-template-columns: 42px 1fr;
    gap: 13px;
    padding: 17px;
  }

  .number {
    width: 40px;
    height: 40px;
    border-radius: 11px;
    font-size: 16px;
  }

  .finish {
    padding: 20px;
  }
}
</style>
</head>

<body>

<div class="quick-start">

  <section class="intro">
    <div class="intro-label">Первые шаги</div>

    <h2>Подготовьте Education ERP к работе</h2>

    <p>
      Если вы впервые работаете в системе, пройдите основные этапы
      последовательно. Это поможет подготовить школу, сотрудников,
      группы и основные настройки для начала работы.
    </p>
  </section>


  <div class="progress">
    <span class="progress-dot"></span>
    <span class="progress-line"></span>
    <span class="progress-dot"></span>
    <span class="progress-line"></span>
    <span class="progress-dot"></span>
    <span class="progress-line"></span>
    <span class="progress-dot"></span>
    <span class="progress-line"></span>
    <span class="progress-dot"></span>
  </div>


  <div class="steps">

    <!-- 1 -->

    <div class="step">
      <div class="number">01</div>

      <div>
        <h3>🏫 Добавьте школу</h3>

        <p>
          Создайте школу и заполните основную информацию о ней.
          Это первый шаг перед настройкой остальных разделов системы.
        </p>

        <div class="links">
          <span class="link">Как добавить школу →</span>
        </div>
      </div>
    </div>


    <!-- 2 -->

    <div class="step">
      <div class="number">02</div>

      <div>
        <h3>📍 Добавьте помещения</h3>

        <p>
          Добавьте помещения, в которых будут проходить занятия.
          Они понадобятся при создании расписания.
        </p>

        <div class="links">
          <span class="link">Как добавить помещение →</span>
        </div>
      </div>
    </div>


    <!-- 3 -->

    <div class="step">
      <div class="number">03</div>

      <div>
        <h3>👨‍🏫 Добавьте сотрудников</h3>

        <p>
          Добавьте педагогов и других сотрудников школы.
          Назначьте им необходимые роли и права доступа.
        </p>

        <div class="links">
          <span class="link">Как добавить сотрудника →</span>
          <span class="link">Роли и права →</span>
        </div>
      </div>
    </div>


    <!-- 4 -->

    <div class="step">
      <div class="number">04</div>

      <div>
        <h3>🎓 Создайте учебные группы</h3>

        <p>
          Создайте группы и заполните основные параметры:
          направление, возраст, педагогов и другие необходимые данные.
        </p>

        <div class="links">
          <span class="link">Как создать учебную группу →</span>
        </div>
      </div>
    </div>


    <!-- 5 -->

    <div class="step">
      <div class="number">05</div>

      <div>
        <h3>📅 Настройте расписание</h3>

        <p>
          Добавьте занятия для созданных групп.
          Укажите дни и время проведения, помещение и сотрудников.
        </p>

        <div class="links">
          <span class="link">Как создать расписание →</span>
        </div>
      </div>
    </div>


    <!-- 6 -->

    <div class="step">
      <div class="number">06</div>

      <div>
        <h3>🎫 Настройте ценники и абонементы</h3>

        <p>
          Подготовьте варианты оплаты занятий:
          настройте ценники и необходимые виды абонементов.
        </p>

        <div class="links">
          <span class="link">Ценники →</span>
          <span class="link">Виды абонементов →</span>
        </div>
      </div>
    </div>


    <!-- 7 -->

    <div class="step">
      <div class="number">07</div>

      <div>
        <h3>👥 Добавьте клиента и ученика</h3>

        <p>
          Создайте клиента, добавьте связанного с ним ученика
          и запишите ученика в подходящую учебную группу.
        </p>

        <div class="links">
          <span class="link">Как добавить клиента →</span>
          <span class="link">Как добавить ученика →</span>
          <span class="link">Запись в группу →</span>
        </div>
      </div>
    </div>


    <!-- 8 -->

    <div class="step">
      <div class="number">08</div>

      <div>
        <h3>💳 Добавьте абонемент</h3>

        <p>
          Добавьте ученику подходящий абонемент
          и при необходимости зарегистрируйте оплату.
        </p>

        <div class="links">
          <span class="link">Добавление абонемента →</span>
          <span class="link">Способы оплаты →</span>
        </div>
      </div>
    </div>


    <!-- 9 -->

    <div class="step">
      <div class="number">09</div>

      <div>
        <h3>✓ Проведите первое занятие</h3>

        <p>
          После занятия отметьте посещаемость учеников
          и проверьте корректность списания занятий по абонементам.
        </p>

        <div class="links">
          <span class="link">Посещаемость учеников →</span>
        </div>
      </div>
    </div>


    <!-- 10 -->

    <div class="step">
      <div class="number">10</div>

      <div>
        <h3>🔔 Настройте уведомления</h3>

        <p>
          Выберите необходимые автоматические уведомления
          и настройте коммуникацию с клиентами.
        </p>

        <div class="links">
          <span class="link">Уведомления →</span>
        </div>
      </div>
    </div>

  </div>


  <section class="finish">

    <div class="finish-icon">✓</div>

    <div>
      <h3>Основная настройка завершена</h3>

      <p>
        После выполнения этих шагов можно переходить
        к ежедневной работе с клиентами, учениками,
        занятиями и сотрудниками в Education ERP.
      </p>
    </div>

  </section>


  <div class="note">
    <strong>💡 Совет.</strong>
    Не обязательно настраивать все возможности Education ERP сразу.
    Начните с основных процессов школы, а дополнительные инструменты
    подключайте по мере необходимости.
  </div>

</div>

</body>

[/html]