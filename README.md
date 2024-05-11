![banner_sketchinspire](https://github.com/beatrizdea-pd/SketchInspira/assets/169511771/966b3d95-00dd-4249-b87f-9a7a043715ca)

# ✍🌈 **SketchInspira** 🌈✍

**Descrição:** Imagine um app que transforma suas ideias em briefings detalhados em um piscar de olhos. Com o **SketchInspira**, você pode dar vida aos seus projetos de forma rápida, eficiente e criativa. Através da inteligência artificial da google, o Gemini, o **SketchInspira** interpreta briefings em forma de texto ou imagens, extraindo as ideias principais, o público-alvo e os requisitos do projeto. Incrível, né? Mas não para por aí!

Tire uma foto do seu produto ou ideia do papel e o **SketchInspira** gera um briefing detalhado para você a partir do seu sketch. E ainda tem mais! Ele cria conceitos e traz tendências para produtos físicos com base em seus briefings, permitindo que você explore diferentes estilos e possibilidades rapidamente. E para te ajudar a refinar seus designs, o **SketchInspira** oferece feedback instantâneo, otimizando o processo criativo focado em auxiliar o designer.

Com esse app, você acelera o desenvolvimento de produtos, explora mais ideias em menos tempo, supera bloqueios criativos, melhora a comunicação com stakeholders e cria produtos inovadores e diferenciados. Experimente o **SketchInspira** hoje mesmo e veja como a IA pode transformar seu projeto de design!

**SketchInspira**: Sketch em briefing -> Briefing em Inspiração.

**Autor**: Beatriz Dea

**Modelo**: Gemini-1.5-Pro-Latest

---

# ✍🌈 **Exemplo do APP - Mockup** 🌈✍

![MOCKUP_Versão1 0](https://github.com/beatrizdea-pd/SketchInspira/assets/169511771/7c6c8386-688c-4a43-8a0e-3c44037edcaf)

![MOCKUP_Versão1 0-Screens](https://github.com/beatrizdea-pd/SketchInspira/assets/169511771/b42039c1-95ae-4706-bb10-e5d6039ed984)

# ✍🌈 **⚙ Configurações ⚙** 🌈✍

Esse guia assume que você está familiarizado com o uso de algum console e que fez o clone do projeto em seu computador. Uma vez feito isso, navegue para a pasta do projeto e execute os passos abaixo.

## **1 - Crie uma conta gratuita do Google Collab**

Entre na plataforma gratuita do Google Collab (https://colab.research.google.com/), abra um notebook novo e importe o código.

## **2 - Adicione uma chave de API do Google AI**

Para que sistema funcione corretamente, é necessário uma chave de API do Google AI Studio que pode ser obtida em https://aistudio.google.com/app/apikey. Uma vez obtida a chave, adicione sua key substituindo "SECRET_KEY" com a sua key nessa parte do código:

```
#Configuração para uso da API KEY

API_KEY = userdata.get("SECRET_KEY")

genai.configure(api_key=API_KEY)
```

## **3 - Acesse o sistema e de start em ordem das box de configurações.**

Para que sistema funcione corretamente, é necessário dar início em cada box em ordem:

```
#Instalação do Google Generative AI
#Importação das bibliotecas utilizadas
#Configuração para uso da API KEY
#Configuração do modelo
#Configuração dos filtros.
#Definindo modelo que será utilizado
#Upload do sketch escolhido
#Prompt
```

---

#  **Mais do que uma aplicação, uma ferramenta poderosa para Designers!**

Revolucione o seu processo de design com o SketchInspire e:

- Acelere o desenvolvimento de produtos.
- Explore mais ideias em menos tempo.
- Supere bloqueios criativos.
- Melhore a comunicação com stakeholders.
- Crie produtos inovadores e diferenciados.

# ✍🌈 **Como Funciona?** 🌈✍

Objetivo: Analisar uma imagem e gerar um briefing completo de projeto de design de produto/design industrial com base na inteligência artificial Gemini 1.5 Pro do Google AI Studio.

## **Passo 1: Carregar Imagem**

Carregue a imagem que representa o produto ou ideia que você deseja analisar.

Formatos Suportados: JPEG, PNG, GIF (máximo 10MB).

Orientação: A imagem pode ser horizontal ou vertical.

Qualidade: Utilize uma imagem com boa resolução e iluminação adequada para facilitar a análise.


## **Passo 2: Análise Avançada**

Descrição: O Gemini 1.5 Pro deve realizar uma análise profunda da imagem, utilizando técnicas de processamento de linguagem natural (PLN) e visão computacional para identificar:

Elementos visuais: Formas, cores, texturas, padrões, proporções, materiais, etc.

Contexto: Ambiente, uso previsto do produto, público-alvo, etc.

Funcionalidades: Funções principais e secundárias do produto, interações com o usuário, etc.

Estética: Estilo visual geral, tendências de design, etc.

## **Passo 3: Geração de Briefing Detalhado**

Com base na análise da imagem, o Gemini 1.5 Pro deve gerar um briefing completo de projeto de design de produto/design industrial que inclua:

Conceito: Descrição da essência do produto, sua proposta de valor e o problema que ele resolve.

Público-Alvo: Definição do público-alvo principal e secundário, suas necessidades, desejos e expectativas.

Objetivo Geral: Especificação do objetivo principal do projeto de design.

Requisitos de Design: Detalhes sobre os aspectos funcionais e estéticos do produto, incluindo ergonomia, usabilidade, materiais, cores, estilo visual, etc.

Requisitos Não Funcionais: Especificações sobre aspectos não funcionais do produto, como segurança, confiabilidade, sustentabilidade, etc.

Requisitos Funcionais: Descrição detalhada das funcionalidades do produto, incluindo interações com o usuário, fluxos de trabalho, etc.


---

## **✨ Resultado do Script ✨** 

**Imagem de Teste**

![image-skecthtest](https://github.com/beatrizdea-pd/SketchInspira/assets/169511771/0367bae2-1346-4e34-ab68-30a02570fc17)

**Briefing Gerado**

## **Luminary Grip** - Iluminando sua jornada com firmeza.

### Conceito:
A Luminary Grip é uma lanterna robusta e ergonômica projetada para uso em diversas situações, com foco em atividades ao ar livre e trabalhos que exigem iluminação potente e confiável. Sua proposta de valor reside na combinação de alta potência de iluminação, design ergonômico para uso prolongado, resistência a impactos e intempéries, e funcionalidades adicionais que a tornam versátil e prática.

**Problema que resolve:** 
Muitas lanternas no mercado são frágeis, desconfortáveis para uso prolongado, possuem iluminação fraca ou funcionalidades limitadas. A Luminary Grip surge como uma solução completa para quem precisa de uma lanterna confiável e eficiente em qualquer situação.

### Público-Alvo:
* **Principal:**  Aventureiros, campistas, esportistas, trabalhadores de campo (construção, segurança, etc.), amantes de DIY.
* **Secundário:**  Qualquer pessoa que necessite de uma lanterna potente e confiável para uso doméstico ou em situações de emergência.

**Necessidades, desejos e expectativas:**
* Iluminação potente e de longo alcance.
* Resistência a quedas, água e poeira.
* Conforto e ergonomia para uso prolongado.
* Durabilidade da bateria.
* Funcionalidades adicionais que agregam valor (foco ajustável, modos de iluminação, etc.).
* Design moderno e atraente.

### Objetivo Geral:
Desenvolver uma lanterna inovadora que alie funcionalidade, durabilidade e design ergonômico, tornando-se a escolha ideal para usuários que buscam performance e confiabilidade em qualquer situação.

### Requisitos de Design:
* **Ergonomia:**  
    * Alça ergonômica emborrachada para firmeza e conforto durante o uso prolongado. 
    * Botão de acionamento intuitivo e de fácil acesso.
    * Peso equilibrado para evitar fadiga.
* **Usabilidade:**  
    * Interface simples e intuitiva, com poucos botões multifuncionais.
    * Foco ajustável facilmente.
    * Design modular que permite acoplar acessórios.
* **Materiais:**  
    * Liga de alumínio resistente a impactos e corrosão.
    * Borracha antiderrapante para a alça e áreas de contato.
    * Lentes de vidro temperado resistentes a riscos.
* **Cores:**  
    * Preto fosco como cor principal, transmitindo robustez e sofisticação.
    * Detalhes em laranja vibrante para destacar botões e funcionalidades.
* **Estilo Visual:**  
    * Moderno, robusto e funcional. 
    * Linhas limpas e geométricas, transmitindo precisão e tecnologia.

### Requisitos Não Funcionais:
* **Segurança:**  
    * Produto deve atender aos padrões de segurança internacionais para dispositivos eletrônicos.
    * Vedação eficaz contra água e poeira (IP67 ou superior).
    * Circuitos protegidos contra superaquecimento.
* **Confiabilidade:**  
    * Componentes de alta qualidade para garantir longa vida útil.
    * Testes rigorosos de resistência e durabilidade.
    * Garantia de 2 anos.
* **Sustentabilidade:**  
    * Uso de materiais reciclados e recicláveis.
    * Embalagem minimalista e eco-friendly.
    * Bateria recarregável de alta capacidade.

### Requisitos Funcionais:
* **Iluminação:**  
    * LED de alta potência com alcance mínimo de 200 metros.
    * Diferentes modos de iluminação: alto, médio, baixo, SOS, strobe.
    * Foco ajustável para alternar entre facho concentrado e amplo.
* **Bateria:**  
    * Bateria recarregável de lítio com autonomia mínima de 5 horas no modo alto.
    * Indicador de nível de bateria.
    * Possibilidade de carregamento via USB-C.
* **Funcionalidades Adicionais:**  
    * Base magnética para fixação em superfícies metálicas.
    * Clip para cinto ou mochila.
    * Possibilidade de acoplar acessórios, como filtros de luz e difusores.

A Luminary Grip será a escolha definitiva para quem busca uma lanterna robusta, confiável e versátil, pronta para qualquer desafio. 

---

#  **🧠 Em Desenvolvimento 🧠** 

### SketchInspira v1

- :white_check_mark:  Construção do Planejamento de Projeto e uma lista de tarefas a serem concluídas.

- :white_check_mark:   Construção e estudo do código para Instalação do Google Generative AI.

- :white_check_mark:   Construção e estudo do código para Importação das bibliotecas utilizadas.

- :white_check_mark:   Construção e estudo do código para Configuração para uso da API KEY.

- :white_check_mark:   Construção e estudo do código para Configuração do modelo (temperatura e número de respostas).

- :white_check_mark:   Construção e estudo do código para Configuração dos filtros.

- :white_check_mark:   Construção e estudo do código para Definindo modelo que será utilizado (Gemini 1.5 Pro Latest).

- :white_check_mark:   Construção e estudo do código para Upload de sketchs.

- :white_check_mark:   Construção e estudo do código para Prompt para a criação de um briefing de projeto de produto à partir da analise da imagem.

### SketchInspira v2

💭  Construção e estudo do código para Promp de chat que reconhece um texto, analisa e gera um briefing completo de projeto de produto/design industrial, incluindo tendências do mercado, fontes de inspiração, palavras-chave, autores relevantes e produtos similares.

