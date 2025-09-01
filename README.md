# 📦 Mini sistema de vendas

Aplicativo Flutter multiplataforma para registro de vendas e visualização de faturamento utilizando dados binários e persistência local.

---

## Descrição do projeto

Este desafio consiste em desenvolver um mini aplicativo de vendas em FLUTTER onde o operador poderá fazer login/cadastro, realizar vendas para clientes bem como acompanhar o faturamento no período. O acesso aos dados de produtos e clientes deve ser por meio dos arquivos .bin na pasta "dataset", os usuários e vendas realizadas devem ser armazenadas em um banco de dados local definido pelo desenvolvedor.

Obs: 

O Desenvolvedor terá a liberdade de escolher o banco de dados local justificando a escolha. \
O projeto deve ser multiplataforma e ser responsivo tanto para dispositivos desktop quanto para mobile.
Caso seja usado em desktop, deverá conter os seguintes atalhos:

F1. Iniciar Venda.\
F2. Incluir Produto.\
F3. Incluir Cliente.\
F4. Finalizar Venda.\
F5. Cancelar Venda Atual; (resetar)

ATENÇÃO: 
1. Arquivos .bin são somente para leitura dos dados.
2. No banco local deverá conter somente os usuários, vendas, clientes e produtos relacionados para análise futura.
3. Na pesquisa de clientes deverá ter um único campo de pesquisa com busca automática ao digitar. Este campo deverá conseguir diferenciar a busca tanto por CPF/CNPJ quanto pelo nome do cliente.
4. Na tela de listagem de vendas deverá conter um botão "Exportar para CSV" que gera um arquivo e permite compartilhar com alguém.


## 🚀 Funcionalidades Implementadas

Checklist das principais funcionalidades:

- [ ] Login e cadastro local
- [ ] Leitura de arquivos `.bin` (produtos e clientes)
- [ ] Iniciar venda e adição de produtos ao carrinho
- [ ] Leitura do produto por código de barras utilizando a câmera do dispositivo
- [ ] Apenas uma venda ativa por vez
- [ ] Gráfico de vendas realizadas no período selecionado "Data inicial e final"
- [ ] Listagem de vendas realizadas (somente cabeçalho e resumo)
- [ ] Exportar vendas para CSV
- [ ] Atalhos de teclado no desktop (F1 a F6)

---

## 🔧 Tecnologias Utilizadas

Liste os principais pacotes e ferramentas usados, com uma breve justificativa técnica para cada.

- **Gerenciamento de estado:** 
  > _Motivação: explique por que essa abordagem foi escolhida para gerenciar estado nesse projeto._

- **Persistência local:** 
  > _Motivação: explique como o pacote escolhido facilita a modelagem e consulta do banco._

- **Leitura de arquivos binários:**  
  > _Explique a abordagem usada para interpretar os dados binários._

- **Leitor de código de barras:**  
  > _Justifique a escolha e como foi integrada ao fluxo de venda._

- **Busca de cliente:**  
  > _Explique como foi implementado o campo único de busca de cliente._
---

## 🏗️ Arquitetura

Descreva brevemente a estrutura do projeto:

- Como os módulos estão organizados?
- Como as camadas foram separadas?
- Como foi pensado o fluxo offline e retomada da venda?

---

## 📱 Instruções de entrega

1. Link do repositório público contendo o projeto e um README.md respondendo as perguntas deste documento;
2. Enviar APK para testes em dispositivo físico;

---

## 🤔 Considerações Finais

- Quais foram os maiores desafios?
- Há algo que você faria diferente em uma segunda versão?

---
