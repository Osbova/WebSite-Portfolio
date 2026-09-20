<script setup>
import { ref } from 'vue'
</script>

<template>
  <header class="header">
    <a href="#hero" class="logo">
      osbovo<span class="dot"></span>
    </a>
    <nav class="nav-links">
      <a href="#about">Обо мне</a>
      <a href="#projects">Проекты</a>
      <a href="#contact">Контакты</a>
    </nav>
  </header>
</template>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 75px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 50px;
  box-sizing: border-box;
  
  
  background: rgba(9, 9, 11, 0.85);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid rgba(255, 255, 255, 0.08);
  z-index: 1000;
}

.logo {
  font-family: 'Orbitron', sans-serif; 
  font-size: 1.8rem;
  font-weight: 900;
  color: #ffffff;
  text-decoration: none;
  text-transform: lowercase;
  letter-spacing: 2px;
  position: relative;
  display: inline-block;
  padding-bottom: 4px;
  text-shadow: 
    0 0 5px rgba(56, 189, 248, 0.6),
    0 0 15px rgba(56, 189, 248, 0.4);
  transition: all 0.3s ease;
}


.logo::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 3px;
  background: #ef4444; 
  box-shadow: 0 0 10px #ef4444, 0 0 20px #ef4444; 
  border-radius: 2px;
}

.logo .dot {
  color: #ef4444;
}

.logo:hover {
  text-shadow: 
    0 0 8px rgba(56, 189, 248, 0.9),
    0 0 25px rgba(56, 189, 248, 0.7);
}

.nav-links {
  display: flex;
  gap: 32px;
}

.nav-links a {
  color: #a1a1aa;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  text-transform: uppercase;
  letter-spacing: 1px;
  transition: all 0.2s ease;
}

.nav-links a:hover {
  color: #38bdf8;
  text-shadow: 0 0 8px rgba(56, 189, 248, 0.5);
}
</style>
