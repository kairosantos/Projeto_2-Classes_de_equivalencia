


# 🧪 Projeto de QA – Casos de Teste e Classes de Equivalência

Este repositório contém um projeto de **Qualidade de Software (QA)** focado na criação de **casos de teste** e aplicação da técnica de **classes de equivalência** para validação dos campos **"Nome"** e **"Sobrenome"** do aplicativo Urban Routes.

O objetivo é garantir que esses campos aceitem apenas entradas válidas e tratem corretamente valores inválidos, assegurando a integridade dos dados e a conformidade com os requisitos do sistema.

---

## 📌 Objetivo

Este projeto foi desenvolvido com o intuito de:

- Validar os campos **Nome** e **Sobrenome** de forma estruturada  
- Aplicar técnicas de **particionamento em classes de equivalência**  
- Identificar possíveis falhas de validação  
- Garantir maior qualidade na entrada de dados do sistema  

---

## 🧠 Abordagem Utilizada

Foi aplicada a técnica de **Classes de Equivalência**, que consiste em dividir os dados de entrada em grupos (válidos e inválidos), reduzindo a quantidade de testes necessários sem comprometer a cobertura.

### 🔍 Exemplos de classes consideradas:

- ✅ Entradas válidas (letras, tamanho adequado)  
- ❌ Entradas inválidas (números, caracteres especiais não permitidos)  
- ⚠️ Campos vazios  
- ⚠️ Valores com espaços extras  
- ⚠️ Limites mínimo e máximo de caracteres  

---

## 🧪 Casos de Teste

Os casos de teste foram elaborados com base nas classes de equivalência identificadas, garantindo cobertura dos principais cenários:

- Testes positivos (dados válidos)  
- Testes negativos (dados inválidos)  
- Testes de borda (limites de caracteres)  
- Validação de mensagens de erro  

Cada caso de teste inclui:

- ID  
- Descrição  
- Pré-condições  
- Passos  
- Resultado esperado  

---

## 🧱 Estrutura do Projeto

O projeto está organizado de forma a facilitar entendimento e manutenção:

```

📁 project-root
├── 📄 casos_de_teste.xlsx   # Planilha com os casos de teste
├── 📄 README.md             # Documentação do projeto

```

---

## 🛠️ Boas Práticas Aplicadas

- ✔️ Uso de técnicas de teste (classes de equivalência)  
- ✔️ Cobertura de cenários positivos e negativos  
- ✔️ Testes de limites (boundary values)  
- ✔️ Clareza e padronização na documentação  
- ✔️ Foco em validação de dados de entrada  

---

## 📈 Resultados Esperados

- 🔍 Identificação de falhas de validação  
- 📉 Redução de inconsistências nos dados  
- 🚀 Melhoria na experiência do usuário  
- 📊 Maior confiabilidade do sistema  

---

## 📌 Considerações Finais

Este projeto demonstra como a aplicação de técnicas clássicas de teste, como **classes de equivalência**, pode otimizar a criação de cenários e aumentar significativamente a eficiência na validação de campos simples, mas críticos, como **Nome** e **Sobrenome**.

---
```
