<template>
  <section class="about-section" id="about">
    <div class="container">
      <div class="section-header">
        <h2 class="section-title">Обо <span class="accent-red">мне</span></h2>
        <div class="title-line"></div>
      </div>

      <div class="about-grid">
        <div class="about-card info-card">
          <h3 class="card-title">Кто я такой?</h3>
          <p class="about-text">
            Я Full Stack разработчик, занимаюсь созданием современных веб-приложений и функциональных Чат-ботов. 
          </p>
          <p class="about-text">
            Сфокусирован на написании чистого, масштабируемого кода, проработке удобного пользовательского интерфейса (UI/UX) и надежной бэкенд-архитектуры. Люблю решать сложные задачи и доводить проекты до идеального результата.
          </p>

          <div class="education-block">
            <h4 class="education-title"><span class="accent-cyan">#</span> Мое обучение</h4>
            <p class="about-text">
              Успешно закончил годовое обучение в <strong>Яндекс Лицее</strong>, а также защитил финальный проект в <strong>Samsung IT School</strong>. На данный момент обучаюсь на 2 курсе Яндекс Лицея.
            </p>
            <a href="https://t.me/ARESTOVAN_ZA_IZBIYENIE" target="_blank" class="diploma-note">
              <span class="note-icon">📁</span>
              <span class="note-text">За дипломами обращаться в личный чат</span>
              <span class="note-arrow">↗</span>
            </a>
          </div>
        </div>

        <div class="about-card stats-card">
          <div class="stat-item">
            <span class="stat-number accent-cyan">Full Stack</span>
            <span class="stat-label">Направление</span>
          </div>
          <div class="stat-item">
            <span class="stat-number accent-red">Web & Bots</span>
            <span class="stat-label">Специализация</span>
          </div>
          <div class="stat-item">
            <span class="stat-number">Clean Code</span>
            <span class="stat-label">Принцип разработки</span>
          </div>
        </div>
      </div>

      <div class="skills-wrapper">
        <h3 class="skills-title">Мой <span class="accent-cyan">Стек технологий</span></h3>
        <div class="skills-grid">
          <div class="skill-category">
            <h4 class="category-name">Frontend</h4>
            <div class="tech-tags">
              <span class="tech-tag cyan">Vue 3</span>
              <span class="tech-tag cyan">JavaScript / ES6+</span>
              <span class="tech-tag cyan">HTML5 / CSS3</span>
              <span class="tech-tag cyan">Composition API</span>
              <span class="tech-tag cyan">Vite</span>
            </div>
          </div>

          <div class="skill-category">
            <h4 class="category-name">Backend</h4>
            <div class="tech-tags">
              <span class="tech-tag red">Java</span>
              <span class="tech-tag red">Python</span>
              <span class="tech-tag red">FastAPI</span>
              <span class="tech-tag red">SQLAlchemy</span>
              <span class="tech-tag red">REST API</span>
              <span class="tech-tag red">PostgreSQL / SQLite</span>
            </div>
          </div>

          <div class="skill-category">
            <h4 class="category-name">Боты & Инструменты</h4>
            <div class="tech-tags">
              <span class="tech-tag white">Telegram Bots API</span>
              <span class="tech-tag white">Aiogram / Telebot</span>
              <span class="tech-tag white">Git / GitHub</span>
              <span class="tech-tag white">Linux / VPS</span>
              <span class="tech-tag white">Docker</span>
            </div>
          </div>
        </div>
      </div>

      <div class="services-wrapper">
        <h3 class="skills-title">Дополнительные <span class="accent-red">возможности</span></h3>

        <div class="services-grid">
          <div class="service-card">
            <div class="service-icon red">💳</div>
            <div class="service-info">
              <h4 class="service-name">Интеграция платежных систем</h4>
              <p class="service-desc">
                Подключение эквайринга и приема платежей (YooKassa, Telegram Stars, CryptoPay, CloudPayments) в ваши сайты и Telegram-боты.
              </p>
            </div>
          </div>

          <div class="service-card">
            <div class="service-icon cyan">⚡</div>
            <div class="service-info">
              <h4 class="service-name">Автоматизация процессов и скрипты</h4>
              <p class="service-desc">
                Разработка индивидуальных скриптов для рутинных задач, автопостинга, выгрузки данных и оптимизации рабочих процессов.
              </p>
            </div>
          </div>

          <div class="service-card">
            <div class="service-icon cyan">📊</div>
            <div class="service-info">
              <h4 class="service-name">Панели управления (Админки под ключ)</h4>
              <p class="service-desc">
                Создание удобных веб-интерфейсов для управления пользователями, контентом, статистикой и настройками ботов/сайтов.
              </p>
            </div>
          </div>

          <div class="service-card">
            <div class="service-icon red">🕷️</div>
            <div class="service-info">
              <h4 class="service-name">Парсинг и сбор данных</h4>
              <p class="service-desc">
                Автоматический сбор, фильтрация и структура информации с любых веб-ресурсов, сайтов и сервисов с сохранением в БД или Excel.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="neon-divider-cyan"></div>
  </section>
</template>

<style scoped>
.about-section {
  position: relative;
  padding: 100px 20px;
  background-color: #09090b;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}

.section-header {
  margin-bottom: 50px;
}

.section-title {
  font-family: 'Orbitron', sans-serif;
  font-size: 2.5rem;
  font-weight: 900;
  color: #ffffff;
  text-transform: uppercase;
  letter-spacing: 2px;
  margin: 0 0 10px 0;
}

.accent-red {
  color: #ef4444;
  text-shadow: 0 0 15px rgba(239, 68, 68, 0.5);
}

.accent-cyan {
  color: #38bdf8;
  text-shadow: 0 0 15px rgba(56, 189, 248, 0.5);
}

.title-line {
  width: 80px;
  height: 4px;
  background: #ef4444;
  border-radius: 2px;
  box-shadow: 0 0 10px #ef4444;
}

.about-grid {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 24px;
  margin-bottom: 60px;
}

.about-card {
  background: rgba(24, 24, 27, 0.6);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 16px;
  padding: 32px;
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
}

.about-card:hover {
  border-color: rgba(239, 68, 68, 0.4);
  box-shadow: 0 0 20px rgba(239, 68, 68, 0.15);
  transform: translateY(-3px);
}

.card-title {
  font-size: 1.4rem;
  color: #ffffff;
  margin-top: 0;
  margin-bottom: 16px;
}

.about-text {
  color: #a1a1aa;
  font-size: 1.05rem;
  line-height: 1.7;
  margin-bottom: 14px;
}

.about-text:last-child {
  margin-bottom: 0;
}

.education-block {
  margin-top: 24px;
  padding-top: 20px;
  border-top: 1px solid rgba(255, 255, 255, 0.08);
}

.education-title {
  font-size: 1.15rem;
  color: #ffffff;
  margin-top: 0;
  margin-bottom: 12px;
  font-weight: 700;
}

.education-block strong {
  color: #f4f4f5;
  font-weight: 600;
}

.diploma-note {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  margin-top: 14px;
  padding: 10px 16px;
  background: rgba(56, 189, 248, 0.06);
  border: 1px dashed rgba(56, 189, 248, 0.35);
  border-radius: 10px;
  font-size: 0.88rem;
  color: #38bdf8;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
  cursor: pointer;
}

.diploma-note:hover {
  background: rgba(56, 189, 248, 0.12);
  border-color: rgba(56, 189, 248, 0.7);
  box-shadow: 0 0 16px rgba(56, 189, 248, 0.25);
  transform: translateY(-2px);
  color: #7dd3fc;
}

.note-icon {
  font-size: 1.05rem;
  line-height: 1;
}

.note-text {
  color: inherit;
}

.note-arrow {
  font-size: 0.95rem;
  font-weight: 700;
  transition: transform 0.2s ease;
}

.diploma-note:hover .note-arrow {
  transform: translate(2px, -2px);
}

.stats-card {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  gap: 20px;
}

.stat-item {
  display: flex;
  flex-direction: column;
}

.stat-number {
  font-family: 'Orbitron', sans-serif;
  font-size: 1.5rem;
  font-weight: 800;
  color: #ffffff;
}

.stat-label {
  font-size: 0.85rem;
  color: #71717a;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-top: 4px;
}

.skills-wrapper {
  margin-top: 40px;
}

.skills-title {
  font-size: 1.8rem;
  color: #ffffff;
  margin-bottom: 28px;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
}

.skill-category {
  background: rgba(24, 24, 27, 0.4);
  border: 1px solid rgba(255, 255, 255, 0.06);
  border-radius: 16px;
  padding: 24px;
  transition: all 0.3s ease;
}

.skill-category:hover {
  border-color: rgba(56, 189, 248, 0.3);
  box-shadow: 0 0 20px rgba(56, 189, 248, 0.1);
}

.category-name {
  font-size: 1.1rem;
  color: #ffffff;
  margin-top: 0;
  margin-bottom: 18px;
  padding-bottom: 8px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.08);
}

.tech-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.tech-tag {
  font-size: 0.85rem;
  font-weight: 600;
  padding: 6px 14px;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.1);
  transition: all 0.2s ease;
}

.tech-tag.cyan {
  color: #38bdf8;
  border-color: rgba(56, 189, 248, 0.3);
}

.tech-tag.cyan:hover {
  background: rgba(56, 189, 248, 0.15);
  box-shadow: 0 0 12px rgba(56, 189, 248, 0.3);
}

.tech-tag.red {
  color: #ef4444;
  border-color: rgba(239, 68, 68, 0.3);
}

.tech-tag.red:hover {
  background: rgba(239, 68, 68, 0.15);
  box-shadow: 0 0 12px rgba(239, 68, 68, 0.3);
}

.tech-tag.white {
  color: #e4e4e7;
  border-color: rgba(255, 255, 255, 0.15);
}

.tech-tag.white:hover {
  background: rgba(255, 255, 255, 0.1);
  box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
}

.services-wrapper {
  margin-top: 50px;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
}

.service-card {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  background: rgba(24, 24, 27, 0.4);
  border: 1px solid rgba(255, 255, 255, 0.06);
  border-radius: 16px;
  padding: 24px;
  transition: all 0.3s ease;
}

.service-card:hover {
  border-color: rgba(239, 68, 68, 0.3);
  box-shadow: 0 0 20px rgba(239, 68, 68, 0.1);
  transform: translateY(-2px);
}

.service-icon {
  font-size: 1.8rem;
  padding: 10px;
  border-radius: 12px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.08);
  line-height: 1;
}

.service-icon.red {
  box-shadow: 0 0 10px rgba(239, 68, 68, 0.2);
}

.service-icon.cyan {
  box-shadow: 0 0 10px rgba(56, 189, 248, 0.2);
}

.service-name {
  font-size: 1.1rem;
  color: #ffffff;
  margin: 0 0 8px 0;
  font-weight: 700;
}

.service-desc {
  font-size: 0.9rem;
  color: #a1a1aa;
  line-height: 1.5;
  margin: 0;
}

.neon-divider-cyan {
  position: absolute;
  bottom: 0;
  left: 5%;
  width: 90%;
  height: 2px;
  background: linear-gradient(90deg, transparent 0%, #38bdf8 50%, transparent 100%);
  box-shadow: 0 0 15px #38bdf8, 0 0 25px #38bdf8;
}

@media (max-width: 900px) {
  .about-grid,
  .skills-grid,
  .services-grid {
    grid-template-columns: 1fr;
  }
}
</style>