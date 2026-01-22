# 📟 CalculadoraJAVA

CalculadoraJAVA é um projeto simples em **Java** que implementa uma calculadora de operações matemáticas básicas utilizando entrada de dados via terminal. O objetivo principal do projeto é **praticar conceitos fundamentais da linguagem Java**, como:

* Estrutura de decisão (`switch-case`)
* Métodos estáticos
* Entrada de dados com `Scanner`
* Tipos primitivos (`int`, `double`)
* Organização de código

> ⚠️ **Status do projeto:** Em desenvolvimento. Ainda está em processo e receberá melhorias futuras.

---

## 🚀 Funcionalidades atuais

O programa permite ao usuário:

1. Escolher uma operação matemática:

   * Soma
   * Subtração
   * Multiplicação
   * Divisão
2. Informar dois números reais
3. Visualizar o resultado da operação escolhida

---

## 🧠 Lógica do funcionamento

1. O programa exibe um menu de opções
2. O usuário escolhe a operação desejada
3. O sistema solicita dois números
4. Um `switch-case` direciona para o método correto
5. O resultado é calculado e exibido no console

Cada operação matemática está isolada em um **método próprio**, facilitando a leitura, manutenção e futuras expansões.

---

## 🛠️ Tecnologias utilizadas

* **Java (JDK 8+)**
* IDE sugerida: Apache NetBeans, IntelliJ IDEA ou VS Code
* Execução via terminal/console

---

## ▶️ Como executar o projeto

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Compile o arquivo:

```bash
javac Calculaura.java
```

3. Execute o programa:

```bash
java Calculaura
```

---

## 📌 Estrutura do código

* `main()` → Responsável pela interação com o usuário
* `soma(double a, double b)`
* `subtracao(double a, double b)`
* `multiplicacao(double a, double b)`
* `divisao(double a, double b)`

Cada método retorna um `double` com o resultado da operação.

---

## 🔮 Futuras atualizações (planejadas)

As próximas versões do projeto podem incluir:

* 🔄 Laço de repetição para múltiplas operações sem reiniciar o programa
* ❌ Tratamento de erros (ex: divisão por zero)
* 🧾 Validação de entrada do usuário
* 🧮 Novas operações:

  * Potência
  * Raiz quadrada
  * Porcentagem
* 🖥️ Interface gráfica (Swing ou JavaFX)
* 🧪 Testes unitários
* 📦 Geração de arquivo `.jar`

---

## 📚 Objetivo educacional

Este projeto faz parte do processo de aprendizado em Java, com foco em:

* Lógica de programação
* Estruturação de métodos
* Boas práticas iniciais

Ele será evoluído conforme novos conceitos forem estudados.

---

## ✍️ Autoria

Projeto desenvolvido para fins educacionais.

Se tiver sugestões ou quiser contribuir, fique à vontade 🚀
