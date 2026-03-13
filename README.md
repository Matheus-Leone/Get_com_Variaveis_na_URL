# 📌 Calculadora REST API - Spring Boot

Projeto desenvolvido em **Java com Spring Boot** contendo uma série de endpoints REST que realizam operações matemáticas básicas e alguns cálculos úteis.

Este projeto foi criado como exercício para praticar conceitos de **API REST**, **Path Variables**, **Request Params** e estrutura básica de aplicações Spring Boot.

---

# 🚀 Tecnologias utilizadas

* Java
* Spring Boot
* Maven
* VS Code
* Git e GitHub

---

# 📂 Estrutura do Projeto

```
src
 └─ main
     └─ java
         └─ com.aulaback.aula
             └─ ExercicioCalculadora.java
```

O controller principal possui diversos endpoints para realizar cálculos matemáticos.

---

# 🔗 Endpoints da API

A base da API é:

```
http://localhost:8080/calculadora
```

## 1️⃣ Soma

```
GET /calculadora/soma/{a}/{b}
```

Exemplo:

```
/calculadora/soma/5/3
```

---

## 2️⃣ Subtração

```
GET /calculadora/subtrair?a=10&b=4
```

---

## 3️⃣ Multiplicação

```
GET /calculadora/multiplicar/{a}/{b}
```

Exemplo:

```
/calculadora/multiplicar/6/7
```

---

## 4️⃣ Divisão

```
GET /calculadora/dividir?a=20&b=5
```

Retorna erro caso o divisor seja **0**.

---

## 5️⃣ Quadrado de um número

```
GET /calculadora/quadrado/{numero}
```

Exemplo:

```
/calculadora/quadrado/8
```

---

## 6️⃣ Conversão Celsius → Fahrenheit

```
GET /calculadora/celsius-para-fahrenheit?celsius=30
```

---

## 7️⃣ Cálculo de IMC

```
GET /calculadora/imc?peso=70&altura=1.75
```

---

## 8️⃣ Antecessor e Sucessor

```
GET /calculadora/antecessor-sucessor/{numero}
```

Resposta em JSON:

```
{
  "numero": 10,
  "antecessor": 9,
  "sucessor": 11
}
```

---

## 9️⃣ Cálculo de desconto

```
GET /calculadora/desconto?valor=200&percentual=10
```

---

## 🔟 Tabuada

```
GET /calculadora/tabuada/{numero}
```

Retorna a tabuada de 1 até 10.

---

# ▶️ Como executar o projeto

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Entre na pasta do projeto:

```
cd nome-do-projeto
```

3. Execute a aplicação Spring Boot.

4. A API estará disponível em:

```
http://localhost:8080
```

---

# 📖 Objetivo do projeto

Praticar conceitos de:

* APIs REST
* Spring Boot
* Parâmetros em endpoints
* Operações matemáticas em Java
* Estrutura de controllers

---

# 👨‍💻 Autor

#Matheus Leone 
#RA 248206
Projeto desenvolvido para fins de estudo em **Java + Spring Boot**.
