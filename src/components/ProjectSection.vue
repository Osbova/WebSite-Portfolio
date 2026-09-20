<template>
  <section class="projects-section" id="projects">
    <div class="container">
      <div class="section-header">
        <div class="header-badge">Portfolio</div>
        <h2 class="section-title">Мои <span class="accent-red">Проекты</span></h2>
        <p class="section-subtitle">Ключевые веб-платформы, сервисы и мобильные разработки</p>
      </div>
      <div class="projects-grid">
        
        <div class="project-card feature-card">
          <div class="card-glow cyan-glow"></div>
          
          <div class="card-header">
            <div class="project-type accent-cyan">
              <span class="type-icon">🌐</span> Full Stack Web App
            </div>
            <span class="status-tag finished">
              <span class="status-dot"></span> Завершен
            </span>
          </div>

          <h3 class="project-title">Аквавэй — Веб-платформа аквапарка</h3>
          
          <p class="project-description">
            Высоконагруженный веб-сервис с интерактивным интерфейсом для клиентов аквапарка. Включает систему онлайн-бронирования билетов, каталоги услуг и административную панель.
          </p>
          <ul class="project-features">
            <li>
              <span class="feature-icon">⚡</span>
              <span>Интерактивный SPA-интерфейс с реактивными компонентами</span>
            </li>
            <li>
              <span class="feature-icon">🛠️</span>
              <span>Асинхронный REST API бэкенд высокой производительности</span>
            </li>
            <li>
              <span class="feature-icon">🗄️</span>
              <span>Архитектура базы данных с реляционным связыванием таблиц</span>
            </li>
          </ul>
          <div class="tech-stack">
            <span class="tech-badge cyan">Vue 3</span>
            <span class="tech-badge red">FastAPI</span>
            <span class="tech-badge red">SQLAlchemy</span>
            <span class="tech-badge">Python</span>
            <span class="tech-badge">REST API</span>
          </div>
          <div class="card-actions">
            <a href="https://github.com/Osbova/Full-stack-Waterpark" class="btn-link secondary">
              <span>GitHub / Исходный код</span>
              <span class="arrow">→</span>
            </a>
          </div>
        </div>
        <div class="project-card">
          <div class="card-glow red-glow"></div>

          <div class="card-header">
            <div class="project-type accent-red">
              <span class="type-icon">🎮</span> Java Game Dev
            </div>
            <!-- Статус: Завершен -->
            <span class="status-tag finished">
              <span class="status-dot"></span> Завершен
            </span>
          </div>

          <div class="project-title-group">
            <h3 class="project-title">Space Debris Cleaner</h3>
            <span class="samsung-note">Samsung IT School (Проект 3 из 5)</span>
          </div>
          
          <p class="project-description">
            Динамичный 2D-экшен на Java, разработанный в рамках учебной программы Samsung. Игрок управляет специализированным кораблем и расчищает околоземную орбиту от космического мусора.
          </p>
          <ul class="project-features">
            <li>
              <span class="feature-icon">🚀</span>
              <span>Физическая модель движения и обработка сложных коллизий</span>
            </li>
            <li>
              <span class="feature-icon">👾</span>
              <span>Оптимизированная отрисовка спрайтов и частицевых эффектов</span>
            </li>
            <li>
              <span class="feature-icon">📱</span>
              <span>Адаптированное управление и поддержка сцен LibGDX</span>
            </li>
          </ul>
          <div class="tech-stack">
            <span class="tech-badge red">Java</span>
            <span class="tech-badge red">LibGDX</span>
            <span class="tech-badge">OOP</span>
            <span class="tech-badge">Gradle</span>
          </div>
          <div class="card-actions">
            <a href="https://github.com/Osbova/Space-Debris" class="btn-link secondary">
              <span>GitHub / Исходный код</span>
              <span class="arrow">→</span>
            </a>
          </div>
        </div>
        <!-- <div class="project-card placeholder-card">
          <div class="card-glow purple-glow"></div>

          <div class="card-header">
            <div class="project-type accent-purple">
              <span class="type-icon">🚀</span> Новый проект
            </div>
            <span class="status-tag looking-team">
              <span class="status-dot"></span> Ищу команду 0/2
            </span>
          </div>

          <h3 class="project-title">??</h3>
          
          <p class="project-description">
            Разработка нового пет-проекта. В данный момент собирается команда разработчиков (Frontend / Backend / Designer) для совместной реализации MVP.
          </p>

          <ul class="project-features">
            <li>
              <span class="feature-icon">💡</span>
              <span>Современный стек технологий</span>
            </li>
            <li>
              <span class="feature-icon">🤝</span>
              <span>Командная работа через Git / GitHub</span>
            </li>
          </ul>

          <div class="tech-stack">
            <span class="tech-badge purple">Vue 3</span>
            <span class="tech-badge purple">Python</span>
            <span class="tech-badge">AsyncIO</span>
          </div>

          <div class="card-actions">
            <a href="#contact" class="btn-link purple">
              <span>Присоединиться к разработке</span>
              <span class="arrow">→</span>
            </a>
          </div>
        </div> -->

      </div>

    </div>

    <div class="neon-divider-red"></div>
  </section>
</template>

<style scoped>
.projects-section {
  position: relative;
  padding: 100px 20px;
  background-color: #09090b;
  overflow: hidden;
}

.container {
  max-width: 1140px;
  margin: 0 auto;
}
.section-header {
  text-align: center;
  margin-bottom: 60px;
}

.header-badge {
  display: inline-block;
  font-family: 'Orbitron', sans-serif;
  font-size: 0.75rem;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #ef4444;
  background: rgba(239, 68, 68, 0.1);
  border: 1px solid rgba(239, 68, 68, 0.25);
  padding: 4px 14px;
  border-radius: 20px;
  margin-bottom: 12px;
}

.section-title {
  font-family: 'Orbitron', sans-serif;
  font-size: 2.8rem;
  font-weight: 900;
  color: #ffffff;
  text-transform: uppercase;
  letter-spacing: 2px;
  margin: 0 0 12px 0;
}

.section-subtitle {
  color: #71717a;
  font-size: 1rem;
  margin: 0;
}

.accent-red {
  color: #ef4444;
  text-shadow: 0 0 20px rgba(239, 68, 68, 0.6);
}

.accent-cyan {
  color: #38bdf8;
  text-shadow: 0 0 15px rgba(56, 189, 248, 0.4);
}

.accent-purple {
  color: #c084fc;
  text-shadow: 0 0 15px rgba(192, 132, 252, 0.4);
}
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 30px;
}
.project-card {
  background: rgba(18, 18, 22, 0.65);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 20px;
  padding: 32px;
  display: flex;
  flex-direction: column;
  backdrop-filter: blur(12px);
  transition: all 0.35s cubic-bezier(0.4, 0, 0.2, 1);
  position: relative;
  overflow: hidden;
}

.card-glow {
  position: absolute;
  top: 0;
  right: 0;
  width: 150px;
  height: 150px;
  border-radius: 50%;
  filter: blur(60px);
  opacity: 0.15;
  pointer-events: none;
  transition: opacity 0.3s ease;
}

.cyan-glow { background: #38bdf8; }
.red-glow { background: #ef4444; }
.purple-glow { background: #a855f7; }

.project-card:hover {
  transform: translateY(-6px);
  border-color: rgba(255, 255, 255, 0.2);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
}

.project-card:hover .card-glow {
  opacity: 0.35;
}
.card-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}

.project-type {
  font-family: 'Orbitron', sans-serif;
  font-size: 0.8rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
  display: flex;
  align-items: center;
  gap: 6px;
}
.status-tag {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 0.72rem;
  font-weight: 700;
  padding: 4px 12px;
  border-radius: 20px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.status-dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
}

.status-tag.finished {
  background: rgba(34, 197, 94, 0.1);
  color: #4ade80;
  border: 1px solid rgba(34, 197, 94, 0.3);
}
.status-tag.finished .status-dot {
  background: #4ade80;
  box-shadow: 0 0 8px #4ade80;
}

.status-tag.in-progress {
  background: rgba(234, 179, 8, 0.1);
  color: #facc15;
  border: 1px solid rgba(234, 179, 8, 0.3);
}
.status-tag.in-progress .status-dot {
  background: #facc15;
  box-shadow: 0 0 8px #facc15;
  animation: pulse 1.5s infinite;
}

.status-tag.looking-team {
  background: rgba(168, 85, 247, 0.1);
  color: #c084fc;
  border: 1px solid rgba(168, 85, 247, 0.3);
}
.status-tag.looking-team .status-dot {
  background: #c084fc;
  box-shadow: 0 0 8px #c084fc;
  animation: pulse 1.5s infinite;
}

@keyframes pulse {
  0% { opacity: 1; }
  50% { opacity: 0.3; }
  100% { opacity: 1; }
}
.project-title-group {
  margin-bottom: 12px;
}

.project-title {
  font-size: 1.4rem;
  color: #ffffff;
  margin: 0 0 4px 0;
  font-weight: 800;
  line-height: 1.3;
}

.samsung-note {
  display: inline-block;
  font-size: 0.78rem;
  color: #ef4444;
  font-weight: 600;
}

.project-description {
  color: #a1a1aa;
  font-size: 0.92rem;
  line-height: 1.6;
  margin-bottom: 24px;
}
.project-features {
  list-style: none;
  padding: 0;
  margin: 0 0 24px 0;
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.project-features li {
  color: #d4d4d8;
  font-size: 0.85rem;
  display: flex;
  align-items: flex-start;
  gap: 10px;
  line-height: 1.4;
}

.feature-icon {
  font-size: 0.9rem;
  flex-shrink: 0;
}

.tech-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: auto;
  margin-bottom: 24px;
}

.tech-badge {
  font-size: 0.78rem;
  font-weight: 600;
  padding: 4px 10px;
  border-radius: 6px;
  background: rgba(255, 255, 255, 0.04);
  color: #a1a1aa;
  border: 1px solid rgba(255, 255, 255, 0.08);
}

.tech-badge.cyan {
  color: #38bdf8;
  border-color: rgba(56, 189, 248, 0.25);
  background: rgba(56, 189, 248, 0.05);
}

.tech-badge.red {
  color: #ef4444;
  border-color: rgba(239, 68, 68, 0.25);
  background: rgba(239, 68, 68, 0.05);
}

.tech-badge.purple {
  color: #c084fc;
  border-color: rgba(192, 132, 252, 0.25);
  background: rgba(192, 132, 252, 0.05);
}
.card-actions {
  padding-top: 18px;
  border-top: 1px solid rgba(255, 255, 255, 0.06);
}

.btn-link {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: #38bdf8;
  text-decoration: none;
  font-size: 0.88rem;
  font-weight: 600;
  transition: all 0.2s ease;
}

.btn-link.purple {
  color: #c084fc;
}

.btn-link .arrow {
  transition: transform 0.2s ease;
}

.btn-link:hover {
  color: #ffffff;
}

.btn-link:hover .arrow {
  transform: translateX(4px);
}
.neon-divider-red {
  position: absolute;
  bottom: 0;
  left: 5%;
  width: 90%;
  height: 1px;
  background: linear-gradient(90deg, transparent 0%, #ef4444 50%, transparent 100%);
  box-shadow: 0 0 12px #ef4444;
}

@media (max-width: 768px) {
  .section-title {
    font-size: 2.2rem;
  }
}
</style>