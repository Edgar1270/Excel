# DIO Invest - Planilha Detalhada de Planejamento de Investimentos em FIIs

## 🌟 Visão Geral do Projeto

Este repositório hospeda a planilha "DIO Invest", uma ferramenta interativa e detalhada projetada para auxiliar no planejamento e na projeção de investimentos, com foco estratégico em **Fundos de Investimento Imobiliário (FIIs)**. Desenvolvida para ser intuitiva, a planilha permite que o usuário simule diversos cenários de investimento, visualize o potencial de crescimento do patrimônio acumulado e receba sugestões de alocação de capital em diferentes tipos de FIIs, empoderando-o a tomar decisões financeiras mais informadas e estratégicas.

Seja você um investidor iniciante ou alguém que busca uma ferramenta para organizar suas projeções futuras, a "DIO Invest" oferece um caminho claro para entender o impacto do investimento contínuo e da diversificação.

## ✨ Principais Funcionalidades

A planilha "DIO Invest" é organizada em seções lógicas, cada uma com um propósito específico para otimizar sua experiência de planejamento:

### 1. ⚙️ Configurações Iniciais

Esta seção é o ponto de partida para personalizar suas projeções:
* **`Salário`**: Insira sua renda mensal bruta ou líquida (conforme sua preferência para base de cálculo), que servirá de referência para a sugestão de investimento.
* **`Rendimento Carteira`**: Defina uma taxa de rendimento percentual mensal esperada para o total da sua carteira de investimentos. Este valor impactará diretamente as projeções de crescimento.
* **`Sugestão de Investimento (30%)`**: Este campo apresenta um percentual pré-configurado (30% do salário) como uma sugestão para o valor a ser investido mensalmente. Você pode ajustá-lo livremente para se adequar à sua capacidade e estratégia de poupança.

### 2. 📊 Investimento Mensal Detalhado

Aqui você define os parâmetros cruciais para a simulação:
* **`Quanto investir por mês?`**: O valor fixo em Reais (R$) que você pretende alocar em investimentos a cada mês.
* **`Por Quantos Anos?`**: O horizonte temporal da sua simulação de investimento. Altere este campo para ver o impacto de diferentes períodos.
* **`Taxa de Rendimento mensal?`**: A taxa de retorno percentual mensal esperada *especificamente para o valor investido*. É crucial diferenciar do `Rendimento Carteira` se você tiver estratégias diferentes.
* **`Patrimônio acumulado`**: **Este é o cálculo mais importante!** Mostra o seu patrimônio total projetado (investimentos + rendimentos compostos) ao final do período definido.
* **`Dividendos Mensais`**: Uma projeção de quanto você receberia em dividendos mensalmente, baseada no patrimônio acumulado e na taxa de rendimento.

### 3. 📈 Cenários de Crescimento (Longa Duração)

Esta seção oferece uma visão rápida do potencial de seus investimentos em diferentes marcos de tempo, atualizando-se automaticamente com base em suas configurações:
* Projeções claras de **`Patrimônio acumulado`** e **`Dividendo`** para períodos de **2, 5, 10, 20 e 30 anos**. Ideal para visualizar o poder dos juros compostos a longo prazo.

### 4. 💰 Perfil e Alocação Sugerida de FIIs

Uma das funcionalidades mais valiosas da planilha é a sugestão de diversificação focada em FIIs:
* **Perfil**: Identifica o perfil de investimento (`Moderado` no exemplo da imagem), que pode ser adaptado conforme a lógica interna da planilha ou preferências.
* **Valor a Ser Investido Por Mês**: Reafirma o valor mensal que será base para a alocação dos FIIs.
* **Sugestão de Distribuição de FIIs**: Uma proposta estratégica de como alocar seu investimento mensal entre os diferentes tipos de Fundos de Investimento Imobiliário:
    * `Papel`: FIIs que investem em títulos de dívida imobiliária (CRI, LCI).
    * `Tijolo`: FIIs que investem diretamente em imóveis físicos (shoppings, lajes corporativas, galpões logísticos).
    * `Híbridos`: FIIs que combinam características de "Papel" e "Tijolo".
    * `FOFs (Fundos de Fundos)`: FIIs que investem em cotas de outros FIIs.
    * `Desenvolvimento`: FIIs que investem em projetos de desenvolvimento imobiliário.
    * `Hotelarias`: FIIs especializados em empreendimentos hoteleiros.
* **Gráfico de Pizza (Visualização):** Uma representação gráfica intuitiva (gráfico de pizza) acompanha a sugestão, facilitando a compreensão visual da distribuição percentual entre os tipos de FIIs.

## 🚀 Como Utilizar a Planilha

Para começar a planejar seus investimentos com a "DIO Invest", siga estes passos simples:

1.  **Baixe a Planilha:**
    * Você pode fazer o download direto do arquivo `.xlsx` (ou similar) deste repositório, se disponível.
    * Ou, se preferir controlar versões, clone o repositório:
        ```bash
        git clone [https://github.com/seu-usuario/DIO-Invest-FIIs.git](https://github.com/seu-usuario/DIO-Invest-FIIs.git)
        cd DIO-Invest-FIIs
        ```
2.  **Abra com um Software Compatível:**
    * A planilha foi desenvolvida para ser totalmente funcional em softwares populares como **Microsoft Excel**, **Google Sheets** ou **LibreOffice Calc**.
3.  **Insira Seus Dados Financeiros:**
    * Navegue até a seção "**CONFIGURAÇÕES**" e ajuste seu `Salário` e o `Rendimento Carteira`.
    * Na seção "**INVESTIMENTO MENSAL**", preencha com seu `Quanto investir por mês?`, `Por Quantos Anos?` e a `Taxa de Rendimento mensal?` que você projeta.
    * **Dica:** Experimente diferentes valores para ver o impacto nas projeções!
4.  **Analise os Resultados e Sugestões:**
    * As seções "**Cenários**" e "**PERFIL**" serão atualizadas automaticamente, mostrando as projeções de patrimônio, dividendos e a alocação sugerida para FIIs. Use essas informações para guiar suas decisões de investimento.

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Planilha Eletrônica**: Desenvolvida e otimizada para ser utilizada em programas de planilhas como:
    * Microsoft Excel
    * Google Sheets
    * LibreOffice Calc
