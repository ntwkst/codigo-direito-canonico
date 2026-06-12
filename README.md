# ⚖️ Código de Direito Canônico — Completo em JSON

> **Salve Cristo Rei, Salve Maria Imaculada!**

## Apresentação

Este repositório contém o **Código de Direito Canônico** (1983) completo e estruturado em formato JSON — **1.752 cânones** da lei da Igreja Católica Latina, organizados em 7 livros.

O dataset é ideal para integração em plataformas web, aplicações móveis e sistemas de pesquisa que desejam oferecer acesso rápido, estruturado e confiável à legislação canônica oficial.

### 📖 Estrutura

```json
{
  "titulo": "Código de Direito Canônico",
  "totalCanones": 1752,
  "livros": [
    {
      "numero": 1,
      "titulo": "Das Normas Gerais",
      "canones": [
        {
          "numero": 1,
          "texto": "..."
        }
      ]
    }
  ]
}
```

### ✨ Características

- ✅ **100% Completo** — Todos os 1.752 cânones do CDC de 1983
- ✅ **Bem Estruturado** — 7 livros com cânones numerados
- ✅ **Encoding UTF-8** — Suporta caracteres acentuados em português
- ✅ **Pronto para Produção** — Testado e validado

### 🚀 Como Usar

```javascript
// JavaScript/Node.js
const cdc = require('./codigo-direito-canonico.json');

// Buscar cânon específico
const canon = cdc.livros[0].canones[0];
console.log(`Cân. ${canon.numero}: ${canon.texto}`);

// Iterar por livros
cdc.livros.forEach(livro => {
  console.log(`Livro ${livro.numero}: ${livro.titulo}`);
});
```

---

**Fiat voluntas tua. Veni, Domine Iesu!**

*Que se faça a tua vontade. Vem, Senhor Jesus!*
