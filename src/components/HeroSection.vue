<template>
  <section class="hero-section" id="hero">
    <div class="glow-bg"></div>

    <div class="hero-content">
      <div class="status-badge">
        <span class="status-dot"></span>
        <span>Доступен для новых проектов</span>
      </div>
      <h1 class="hero-title">
        Привет! Я <span class="accent-text">Full Stack</span> разработчик
      </h1>
      <p class="hero-subtitle">
        Делаю акцент на создание <span class="highlight-cyan">Веб-приложений</span> и <span class="highlight-red">Ботов</span>
      </p>
      <div class="hero-actions">
        <a href="#projects" class="btn btn-primary">Мои проекты</a>
        <a href="#contact" class="btn btn-secondary">Связаться</a>
      </div>
    </div>
    <div class="neon-divider"></div>
  </section>
</template>
<style scoped>
.hero-section {
  position: relative;
  min-height: calc(100vh - 75px);
  margin-top: 75px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 60px 20px;
  box-sizing: border-box;
  overflow: hidden;
}
.glow-bg {
  position: absolute;
  top: 30%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 500px;
  height: 300px;
  background: radial-gradient(circle, rgba(58, 189, 248, 0.15) 0%, rgba(239, 68, 68, 0.08) 50%, transparent 80%);
  filter: blur(60px);
  pointer-events: none;
}

.hero-content {
  position: relative;
  z-index: 2;
  max-width: 900px;
  text-align: center;
}

.status-badge {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.1);
  padding: 8px 18px;
  border-radius: 30px;
  font-size: 0.85rem;
  color: #a1a1aa;
  margin-bottom: 28px;
  backdrop-filter: blur(5px);
}

.status-dot {
  width: 8px;
  height: 8px;
  background-color: #22c55e;
  border-radius: 50%;
  box-shadow: 0 0 10px #22c55e;
}

.hero-title {
  font-size: 3.5rem;
  font-weight: 900;
  line-height: 1.15;
  margin-bottom: 20px;
  color: #ffffff;
  letter-spacing: -0.5px;
}

.accent-text {
  background: linear-gradient(135deg, #38bdf8 0%, #ef4444 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 30px rgba(56, 189, 248, 0.3);
}
.hero-subtitle {
  font-size: 1.4rem;
  color: #a1a1aa;
  max-width: 700px;
  margin: 0 auto 40px auto;
  line-height: 1.6;
}

.highlight-cyan {
  color: #38bdf8;
  font-weight: 700;
  text-shadow: 0 0 12px rgba(56, 189, 248, 0.5);
}

.highlight-red {
  color: #ef4444;
  font-weight: 700;
 text-shadow: 0 0 12px rgba(239, 68, 68, 0.5);
}

.hero-actions {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.btn {
  padding: 14px 32px;
  border-radius: 12px;
  font-weight: 700;
  font-size: 1rem;
  text-decoration: none;
  transition: all 0.3s ease;
  cursor: pointer;
}

.btn-primary {
  background: #ef4444;
  color: #ffffff;
  box-shadow: 0 0 20px rgba(239, 68, 68, 0.4);
  border: 1px solid #ef4444;
}

.btn-primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 0 30px rgba(239, 68, 68, 0.7);
  background: #dc2626;
}

.btn-secondary {
  background: rgba(255, 255, 255, 0.05);
  color: #ffffff;
  border: 1px solid rgba(255, 255, 255, 0.15);
  backdrop-filter: blur(10px);
}

.btn-secondary:hover {
  transform: translateY(-2px);
  border-color: #38bdf8;
  color: #38bdf8;
  box-shadow: 0 0 15px rgba(56, 189, 248, 0.3);
}

.neon-divider {
  position: absolute;
  bottom: 0;
  left: 5%;
  width: 90%;
  height: 2px;
  background: linear-gradient(90deg, transparent 0%, #ef4444 50%, transparent 100%);
  box-shadow: 0 0 15px #ef4444, 0 0 25px #ef4444;
}

@media (max-width: 768px) {
  .hero-title {
    font-size: 2.2rem;
  }

  .hero-subtitle {
    font-size: 1.1rem;
  }

  .hero-actions {
    flex-direction: column;
    width: 100%;
  }

  .btn {
    width: 100%;
    box-sizing: border-box;
  }
}
</style>