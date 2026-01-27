# convite-config

## ⚠️ ATENÇÃO AO EDITAR OS TEXTOS (MUITO IMPORTANTE)

Antes de alterar qualquer texto no arquivo `config.json`, é **fundamental entender o uso dos caracteres especiais `\n` e `\"`**.  
Eles **NÃO estão ali por acaso** e **não devem ser removidos**, pois isso pode causar erros no layout ou até quebrar o funcionamento do site/app.

---
### 🔹 Uso do `\n` — Quebra de linha

O `\n` é um **caractere especial usado para criar uma quebra de linha** dentro de um texto.

Ou seja:
- Tudo que vem **antes do `\n`** aparece em uma linha
- Tudo que vem **depois do `\n`** aparece **na linha de baixo**

### 🔹 Uso do `\"` — Aspas dentro do texto (MUITO IMPORTANTE)

No formato **JSON**, o caractere de aspas (`"`) é usado para **delimitar textos**.  
Isso significa que o JSON entende que um texto **começa e termina com aspas**.

Por esse motivo, quando precisamos **mostrar aspas dentro do próprio texto**, é obrigatório usar `\"`.  
Esse caractere indica que a aspa **faz parte do conteúdo** e não do formato do arquivo.

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
