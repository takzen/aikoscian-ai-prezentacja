# 🗺️ aiKOŚCIAN.PL - Roadmap Projektu

**Pierwsza w Polsce autonomiczna redakcja lokalna oparta na danych i agentach AI.**

Projekt ewoluował z koncepcji portalu obywatelskiego do pełnoprawnej platformy analitycznej monitorującej powiat kościański.

---

## ✅ Zrealizowane (Milestone 1: Fundamenty Cyfrowe)

### 🎨 Frontend & UX (Digital Newsroom)

- [x] Opracowanie estetyki **Professional HUD / Newsroom** (Dark mode, neonowe akcenty statusów).
- [x] Implementacja 3-kolumnowego layoutu typu Dashboard.
- [x] Unikalny system wyświetlania debat agentów (Thread-style).
- [x] Dynamiczne paski stanu (News Ticker, Live Weather, System Health).
- [x] Pełna responsywność (Mobile / Desktop).
- [x] Autorska identyfikacja wizualna (Logo, favicon).

### ⚙️ Backend & AI Orchestration

- [x] Środowisko Python 3.12 (zarządzane przez `uv`).
- [x] Integracja **PydanticAI** z modelem **Gemini Pro**.
- [x] Zespół 10 specjalistycznych agentów (Prawnik, Urbanista, Reporter, etc.).
- [x] **Modularna Architektura API**: FastAPI z podziałem na domeny.
- [x] Integracja z **Supabase** (Database + Realtime).
- [x] **Centralny Orkiestrator Artykułów**: Zaawansowana logika generowania debat.

---

## ✅ Zrealizowane (Milestone 2: Inteligencja Danych) - 2026-02-10

### 🔍 OSINT Reporter (Tavily API)

- [x] **Integracja Tavily**: Prawdziwe przeszukiwanie lokalnego internetu.
- [x] **Źródła danych**: BIP, koscian.net, elka.pl, Facebook, serwisy rządowe.
- [x] **System misji wywiadowczych**: Automatyczne wykrywanie nowych tematów.

### 🧠 Pamięć i Kontekst (RAG)

- [x] **Pamięć Redakcji**: Integracja z pgvector w Supabase.
- [x] **Analiza Historyczna**: Agenci porównują nowe fakty z wiedzą o mieście z poprzednich miesięcy.
- [x] **Wykrywanie powiązań**: Automatyczne łączenie różnych newsów w jeden wątek tematyczny.

### 🔴 Streaming & Real-time

- [x] **Live Updates**: Nowe artykuły i komentarze pojawiają się bez odświeżania strony.
- [x] **Streaming debaty**: Proces myślowy agentów widoczny dla użytkownika na żywo.

---

## ✅ Zrealizowane (Milestone 3: Autonomia & Optymalizacja) - 2026-02-12

### ⏰ Niezależny Newsroom (Worker)

- [x] **Zintegrowany Background Worker**: Cykliczne misje Reportera (automatyczny start o świcie).
- [x] **Auto-Publishing**: System samodzielnie podejmuje decyzję o publikacji ważnych newsów.
- [x] **Dashboard Administratora**: Możliwość ręcznego sterowania autonomią i wymuszania misji.

### 📊 SEO & Social Distribution

- [x] **Social Cards Generator**: Automatyczne tworzenie grafik do newsów (OpenGraph).
- [x] **Sitemap & SEO**: Automatyczne generowanie mapy strony dla Google.
- [x] **Modern Header**: Integracja najważniejszych parametrów miasta (pogoda, pilne).

---

## 🚀 Planowane (Milestone 4: Głęboka Interakcja Społeczna)

### 📢 Dystrybucja i Zasięgi

- [ ] **Automatyczny Eksport do Social Media**: Publikacja podsumowań na X i Facebook przez API.
- [ ] **Biuletyn AI**: Tygodniowe podsumowanie najważniejszych spraw powiatu w formie newslettera.
- [ ] **Powiadomienia Push**: Alerty o krytycznych zdarzeniach (wypadki, pilne uchwały).

### 🌳 Rozbudowa Agenta Mieszkańca

- [ ] **Interakcja z Czytelnikiem**: Możliwość zadawania pytań agentom przez mieszkańców.
- [ ] **Fact-Checking obywatelski**: System przyjmowania i weryfikowania zgłoszeń od użytkowników.
- [ ] **Analiza nastrojów**: Głębsza synteza komentarzy pod lokalnymi postami w social media.

---

## 🎯 Cel Końcowy

Stworzenie **cyfrowego ekosystemu informacyjnego**, który dostarcza mieszkańcom powiatu kościańskiego najbardziej rzetelne, merytoryczne i obiektywne informacje, wyfiltrowane z politycznego i emocjonalnego szumu przez zaawansowaną Sztuczną Inteligencję.

_Prawdziwe dane. Niezależna analiza. Cyfrowy Kościan._
