
# 🛒 Desafio Técnico: Tela de Busca e Seleção de Produtos

## 🎯 Objetivo

Desenvolver uma tela de vendas onde o usuário poderá buscar por produtos, selecionar e finalizar venda informando um método de pagamento.

Obs:

- Leitura dos produtos e formas de pagamento serão a partir de arquivos `.bin` na pasta **dataset**
- Selecionar múltiplos produtos da lista
- Exibir o total acumulado dos itens selecionados
- Exibir resultados com animação e uma interface estilizada e responsiva

---

## 📦 Funcionalidades Requeridas

### 🔍 Busca de Produtos

- Leitura local de um arquivo `produtos.bin` contendo até 10 mil produtos
- Campo de busca único:
  - Entrada numérica: busca por **código de barras**
  - Entrada textual: busca por **descrição do produto**
- Resultados exibidos com **scroll eficiente e animação**

### ✅ Seleção de Produtos

- Permitir seleção/deseleção de produtos na lista
- Destaque visual para os selecionados
- Cálculo exibidos em tempo real

### 🎨 UI e Estilização

- Lista com **animações** de entrada
- Estilo visual agradável
- Feedback visual em:
  - Tipo de busca detectado
  - Item selecionado
  - Total e quantidade na tela
- Suporte a tema claro e escuro (opcional)
---

## 🧠 Requisitos Técnicos

- Leitura eficiente de arquivos `.bin` contendo produtos e formas de pagamento
- Gerenciamento de estado
- Separação em camadas:
  - UI
  - Modelos de dados
  - Lógica de seleção/busca

---

## 📝 Entrega Esperada

- Projeto Flutter em repositório público no github
- `README.md` contendo:
  - Instruções para rodar o projeto desktop
  - Apk para teste em dispositivo físico
  - Justificativas técnicas para os pacotes utilizados

---

## 📊 Critérios de Avaliação

- [ ] Leitura do arquivo `.bin`
- [ ] Lógica de busca adaptativa e seleção
- [ ] Animações e feedback visual
- [ ] Organização e arquitetura do projeto
- [ ] Justificativa das ferramentas utilizadas

---

## 📁 Exemplos de modelos de dados

### Produto
```json
{
  "codigo_barras": "7898994085881",
  "descricao_longa": "MIST P/BOLO D BENTA LARANJA 450G",
  "descricao_curta": "MIST P/BOLO D BENTA LARAN",
  "preco_unitario": 4.99,
  "saldo_estoque": 39,
  "marca": "ISSAM"
}
```

### Forma de Pagamento

```json
{
  "id": 1,
  "descricao": "PIX"
}
```
---

Boa sorte! 🍀
