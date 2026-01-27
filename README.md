# convite-config

Este repositório contém o arquivo `config.json`, responsável por definir
os textos, links e cores do site do convite de casamento.
---

## Textos do convite

### 📝 quote (frase em destaque)

Este campo define a frase principal exibida no topo do convite.

⚠️ IMPORTANTE:
- As aspas fazem parte do texto exibido
- Por isso, é obrigatório usar `\"` antes e depois da frase

### Exemplo CORRETO:
```json
"quote": "\"A medida do amor é amar sem medida\"."

### 📝 message (texto principal)

Este campo define o texto principal do convite.

⚠️ Para quebrar o texto em mais de uma linha, é obrigatório usar `\n`.

### Exemplo no `config.json`:
```json
"message": "Vamos casar e queremos \ncomemorar com você"

## Explicação de cada cor

### 🟣 primary
Cor principal do site.

Usada em:
- Barra **“CONVITE”**
- Ícones circulares
- Botões
- Tema geral do site (ThemeData)

---

### 🟣 textPurple
Cor dos textos principais.

Exemplo:
- “Vamos casar e queremos comemorar com você”

---

### ⚪ textLight
Cor dos textos secundários.

Exemplo:
- Data e horário do evento

---

### 🌈 gradient1 e gradient2
Cores do gradiente.

Usadas nos textos:
- **“CASAMENTO”**
- **“REGIANE & RODRIGO”**
