# 🧠 Introdução ao Progress 4GL (OpenEdge ABL)

Este repositório contém **exemplos práticos e comentados** de programação em **Progress 4GL (OpenEdge ABL)** — uma linguagem usada amplamente em sistemas corporativos (como o **TOTVS Protheus**, **Datasul**, entre outros).

O conteúdo abrange desde a **definição de variáveis** até **manipulação de dados em banco**, passando por **estruturas de decisão**, **laços de repetição** e **tratamento de erros**.

> 🔧 Este material foi criado como base de estudos pessoais antes da integração do **Progress 4GL com JavaScript/Front-End**, para posterior uso como **back-end**.

---

## 📘 Conteúdos abordados

### 🧩 1. Definição de Variáveis

Declaração e inicialização de variáveis de diferentes tipos:

```progress
DEF VAR iInteiro AS INT.
DEF VAR dDecimal AS DEC FORMAT ">>,>>>,>>9.99".
DEF VAR cChar    AS CHAR.
DEF VAR lgChar   AS LONGCHAR.
DEF VAR lBollean AS LOGICAL INITIAL YES.
DEF VAR dDate    AS DATE.
DEF VAR dtDateTime AS DATETIME.
DEF VAR aArray   AS INT EXTENT 4.
