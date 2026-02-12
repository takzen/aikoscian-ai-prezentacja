# 🏗️ Architektura Systemu aiKOŚCIAN

System został zaprojektowany w architekturze wieloagentowej, gdzie autonomiczne jednostki AI współpracują nad analizą lokalnych wydarzeń.

## 1. Cykl Redakcyjny (Flow)

1. **Zwiad (Reporter Agent)**: Autonomiczny skaner przeszukuje sieć (BIP, serwisy informacyjne, social media) za pomocą Tavily API. Wykrywa tematy o wysokim znaczeniu dla powiatu (inwestycje, przetargi, wypadki).
2. **Kolegium Redakcyjne (Orchestrator)**: System buduje kontekst merytoryczny, pobierając:
   - Dokładne dane z internetu.
   - Kontekst historyczny i prawny.
3. **Debata Ekspercka**:
   - Wybrane modele AI (specjaliści) nawiązują debatę. Każdy agent analizuje problem ze swojej perspektywy (np. Prawnik sprawdza uchwały, Urbanista analizuje przestrzeń).
   - Wynik jest syntezowany w spójny artykuł analityczny.
4. **Publikacja**: Artykuł trafia do bazy (Supabase) i jest serwowany w czasie rzeczywistym na frontendzie.

## 2. Pamięć Systemowa

Używamy bazy PostgreSQL (Supabase) do przechowywania pełnej historii debat i faktów. Agenci mają dostęp do kontekstu poprzednich spraw, co pozwala na wykrywanie powtarzających się problemów lub kontynuację wielomiesięcznych wątków inwestycyjnych.

## 3. Autonomia Redakcji

System operuje na niezależnym workerze (Python), który wykonuje zadania w harmonogramie. Redakcja nie wymaga ingerencji człowieka – od znalezienia tematu po publikację gotowej analizy z tweetem promocyjnym.

## 4. Design Professional HUD

Interfejs użytkownika (Next.js) został zaprojektowany w estetyce "Digital Newsroom". Wykorzystuje on surowy, techniczny wygląd, który podkreśla oparcie na danych, a nie na tradycyjnym, subiektywnym dziennikarstwie.
