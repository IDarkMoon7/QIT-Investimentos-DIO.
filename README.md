# 🚀 QIT Investimentos

![Banner](assets/Banner_QIT_Investimentos.png)

Este projeto foi desenvolvido como um desafio prático da **DIO (Digital Innovation One)**. O objetivo é fornecer uma ferramenta de tomada de decisão financeira que projeta o acúmulo de patrimônio e a geração de renda passiva ao longo do tempo.

A **QIT Investimentos** é uma solução estruturada para auxiliar investidores a entenderem o impacto dos juros compostos e da alocação estratégica em fundos imobiliários. O desenvolvimento seguiu a metodologia ensinada pelo **Felipão (DIO)**, focando em separar claramente as camadas de entrada, processamento e visualização de dados.

---

## 🛠️ Passo a Passo do Desenvolvimento

### 1. Definição do Negócio e Pré-requisitos 
O projeto iniciou com a identificação das Perguntas de Negócio essenciais: 
* Quanto investir?
* Por quanto tempo?
* Taxa de retorno mensal;
* Patrimônio acumulado;
* Dividendos mensais;

Estabelecemos as **Variáveis Globais** no bloco de configurações, utilizando um salário base de **R$ 5.000,00** e uma regra de aporte de **30%**.

### 2. Estrutura Técnica e Nomeação 
Para garantir a escalabilidade e evitar erros, a base da tabela foi construída utilizando a **Nomeação de Intervalos**. Em vez de referências soltas, as fórmulas utilizam nomes claros, facilitando a auditoria e manutenção do sistema.

### 3. Simulador de Patrimônio (O Motor de Juros)
A lógica central baseia-se na fórmula de **Valor Futuro (VF)** para aportes mensais constantes:

$$VF = P \times \frac{(1 + i)^n - 1}{i}$$

* **P**: Aporte mensal sugerido (ex: R$ 1.000,00).
* **i**: Taxa de rendimento mensal (ex: 1,08%).
* **n**: Período total em meses.

### 4. Análise de Cenários
Desenvolvemos uma matriz de projeções que escala o patrimônio e os dividendos em janelas de 2, 5, 10, 20 e 30 anos. Isso permite visualizar o poder do tempo: em um cenário de 30 anos, o patrimônio pode ultrapassar **R$ 4 milhões**, com renda passiva superior a **R$ 43 mil** por mês.

### 5. Alocação Estratégica (FIIs)
A ferramenta detalha a distribuição do aporte mensal (para perfis Conservador, Moderado ou Agressivo) em diferentes tipos de fundos: 
* **Papel**: Foco em títulos de dívida imobiliária.
* **Tijolo**: Foco em imóveis físicos (shoppings, galpões).
* **Híbrido e FOFs**: Diversificação e fundos de fundos.

---

## 🎨 Interface e UX
O design foi planejado para ser intuitivo e "clean", utilizando uma paleta de cores amarela para destacar cabeçalhos e hierarquizar a informação. A organização em blocos permite que o usuário entenda sua estratégia financeira em segundos.

![Interface da Planilha QIT](https://github.com/IDarkMoon7/QIT-Investimentos-DIO./blob/main/docs/assets/Captura_de_tela_QIT.jpg)

---

## 📂 Estrutura do Repositório
* **docs/**: Contém a planilha original de investimentos.
* **assets/**: Contém as imagens e identidade visual do projeto.

---

## 👩‍💻 Autoria e Contexto
Projeto realizado por uma estudante de **Engenharia da Computação na UNIVESP** e **Embaixadora da DIO**, atualmente em transição de carreira para a área de tecnologia.
