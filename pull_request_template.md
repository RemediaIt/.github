# 📝 {{TICKET}} — krótki tytuł PR
<!-- Przykład: RMD-123: Dodanie paginacji do listy zamówień -->

## 🔧 Zakres zmian
- [ ] Backend
- [ ] Frontend
- [ ] Infra / CI
- [ ] Inne: …

---

## 🔗 Powiązania

| Typ          | Link |
|--------------|------|
| Jira ticket  | [{{TICKET}}](https://remedia-it.atlassian.net/browse/{{TICKET}}) |
| Dokumentacja | [Confluence](https://confluence.example.com/...) |

---

## ✨ Opis
<!-- Kilka zdań: co, dlaczego, jak sprawdzić w skrócie. -->
- …

---

## ⚠️ Ryzyka / kompatybilność
- [ ] Zmiana schematu bazy (opis migracji + plan rollbacku)
- [ ] Zmiana kontraktu API (breaking change)
- [ ] Potencjalny wpływ na wydajność
- [ ] Wpływ na bezpieczeństwo
- [ ] Wymaga zmian w konfiguracji / DevOps
- [ ] Inne: …

<details>
<summary>📦 Migracje DB (jeśli dotyczy)</summary>

- **Skrypt migracji**: …
- **Plan rollbacku**: …
- **Szacowany czas**: …
- **Wpływ na dane / downtime**: …
</details>

---

## 🧪 Testy / weryfikacja
- [ ] Testy automatyczne uruchomione lokalnie (unit / integration / e2e)
- [ ] Dodano nowe testy (jeśli potrzebne)
- [ ] Opisano manualne kroki weryfikacji (poniżej)

<details>
<summary>🧭 Kroki do odtworzenia / QA</summary>

1. …
2. …
3. Oczekiwany rezultat: …
</details>

---

<!-- Sekcja FRONTEND – wypełnij tylko gdy dotyczy -->
<details>
<summary>🌐 Frontend (jeśli dotyczy)</summary>

### Sprawdzone przeglądarki
- [ ] Chrome
- [ ] Firefox
- [ ] Edge
- [ ] Safari
- [ ] Mobile (Android/iOS)

### Zrzuty ekranu / nagrania
<!-- Wklej obrazy lub linki (np. Loom) -->
- …

### Uwagi FE
- [ ] Wpływ na responsywność / layout
- [ ] Potencjalny wpływ na wydajność renderowania (np. duże listy, grafika 3D)
- [ ] Zmiany w kontrakcie API / format danych (integracja FE/BE)
- [ ] Problemy z kompatybilnością przeglądarek (layout, JS, WebGL)
</details>

---

<!-- Sekcja BACKEND – wypełnij tylko gdy dotyczy -->
<details>
<summary>🧰 Backend (jeśli dotyczy)</summary>

- [ ] Zmiany w kontrakcie API opisane w OpenAPI / dokumentacji
- [ ] Zmienione endpointy są wstecznie kompatybilne (albo opisano breaking changes)
- [ ] Analiza ryzyk wydajnościowych (N+1, blokady, IO, cache)
- [ ] Monitorowanie / alerty / metryki zaktualizowane
</details>

---

## 🚀 Wdrożenie / rollout
- [ ] Feature flag / plan stopniowego wdrożenia
- [ ] Notatki do release (changelog)
- [ ] Kroki po wdrożeniu (np. migracje ręczne, warm-up cache)

---

## ✅ Checklista przed mergem
- [ ] Link do Jiry
- [ ] Link do dokumentacji
- [ ] Przeszedł Code Review (≥1 dev)
- [ ] Testy zielone w CI
- [ ] (Jeśli dotyczy) migracje/monitoring/feature flag gotowe
