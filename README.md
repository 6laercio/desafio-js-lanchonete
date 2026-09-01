# 🍔 Desafio JS: Sistema de Lanchonete

Bem-vindo ao seu primeiro desafio prático de JavaScript! 🚀 

Você foi contratado para criar um pequeno script que calcula o valor final da conta dos clientes de uma lanchonete. Sua missão é criar uma função que receba os preços dos itens que o cliente pediu, some tudo, aplique descontos e cobre a taxa de entrega.

Este desafio foi criado para testar seus conhecimentos fundamentais em:
* Variáveis
* Loops
* Funções
* Condicionais
* Operadores (Atribuição, Aritmético, Comparação, Lógicos, Ternário e String)

---

## 📝 O que você precisa fazer:

1. **Crie uma função** chamada `fecharConta`. Ela deve receber dois parâmetros: 
   * Uma lista (array) com os preços dos produtos (ex: `[10, 15, 8]`).
   * Uma variável booleana (`true` ou `false`) chamada `temCartaoVip`.
2. Dentro da função, crie uma **variável** chamada `total` começando com o valor `0`.
3. Use um **loop** (como o `for` ou `while`) para passar por todos os preços da lista e somá-los à variável `total`.
4. Crie uma **condicional** (`if / else`): Se o `total` for maior que `30` **E** o cliente tiver o cartão VIP (`temCartaoVip`), aplique um desconto de 10% no total (ou seja, diminua 10% do valor).
5. Use o **operador ternário** para calcular uma `taxaEntrega`: Se o `total` for maior ou igual a `50`, a taxa de entrega é `0`. Caso contrário, a taxa é `5`. Some essa taxa ao `total`.
6. No final da função, **retorne** uma frase juntando texto e variável. O resultado deve ser exatamente assim: `"O valor final da sua conta é R$ "` + o valor total.

---

## 💻 Como rodar este desafio na sua máquina

Para resolver e testar este desafio, siga os passos abaixo para clonar o repositório e executar o código no seu ambiente local.

### Pré-requisitos
* Ter o **[Git](https://git-scm.com/)** instalado na sua máquina.
* Ter o **[Node.js](https://nodejs.org/)** instalado (para rodar o JavaScript fora do navegador).
* Um editor de código, como o **[VS Code](https://code.visualstudio.com/)**.

### Passo a Passo

**1. Clone o repositório**
Abra o seu terminal (Prompt de Comando, PowerShell ou terminal do seu sistema) e digite o comando abaixo para baixar o projeto:
```bash
git clone https://github.com/6laercio/desafio-js-lanchonete.git
```

**2. Acesse a pasta do projeto**
Ainda no terminal, entre na pasta que acabou de ser criada:
```bash
cd desafio-js-lanchonete
```

**3. Abra o projeto no seu editor de código**
Se você usa o VS Code, pode abrir o projeto diretamente do terminal digitando:
```bash
code .
```

**4. Resolva o desafio**
* Crie um arquivo chamado `desafio.js`.
* Escreva a sua função `fecharConta` dentro deste arquivo, seguindo as regras da seção "O que você precisa fazer".
* No final do arquivo, faça alguns testes para ver se sua lógica está funcionando. Exemplo:
  ```javascript
  // Adicione isso no final do arquivo desafio.js para testar
  console.log(fecharConta([15, 20, 10], true)); 
  ```

**5. Teste o seu código**
Abra o terminal integrado do seu editor (no VS Code: `Ctrl + '` ou `Visualizar > Terminal`) e execute o seu arquivo com o Node.js digitando:
```bash
node desafio.js
```
Se tudo der certo, você verá a mensagem com o valor total impresso na tela! 🎉

---
Boa sorte, dev! Qualquer dúvida, chame seu orientador. 🚀
