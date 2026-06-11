# Código de Direito Canônico

Código de Direito Canônico em formato JSON estruturado para consumo via API/web.

**Estrutura:**
- 7 Livros
- Títulos, Cânones
- 1752 cânones total (conforme CIC oficial)

**Uso:**
```javascript
fetch('https://raw.githubusercontent.com/NTWKST/codigo-direito-canonico/main/codigo-direito-canonico.json')
  .then(r => r.json())
  .then(data => console.log(data.livros))
```

**Promulgado em 1983** — Texto integral em Português.
