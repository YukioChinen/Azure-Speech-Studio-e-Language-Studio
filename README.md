# Azure Speech Studio e Language Studio

Este repositório contém um guia prático para criar um ambiente no portal da Azure e explorar a funcionalidade de análise de sentimentos de texto utilizando os serviços cognitivos do Azure. O objetivo é servir como material de apoio para estudos e futuras implementações.

---

## Objetivo

- Demonstrar como configurar um ambiente no Azure.
- Explorar a funcionalidade de análise de sentimentos de texto diretamente no portal da Azure.
- Fornecer insights e boas práticas adquiridas durante a prática.

---

## Pré-requisitos

Antes de começar, certifique-se de ter:

1. Uma conta no [Portal da Azure](https://portal.azure.com/).

---

## Passo a Passo: Criando um Ambiente no Portal da Azure

### 1. Criar uma Conta no Azure
1. Acesse o [Portal da Azure](https://portal.azure.com/).
2. Caso ainda não tenha uma conta, clique em **"Criar conta gratuita"** e siga as instruções.
3. Após criar a conta, faça login no portal.

**Insight:** A conta gratuita do Azure oferece créditos iniciais que podem ser usados para explorar os serviços. Aproveite para testar diferentes recursos sem custos adicionais.

---

### 2. Criar um Recurso de Serviço Cognitivo
1. No portal, clique em **"Criar um recurso"**.
2. Em **"Categorias"**, selecione **"Serviços de Linguagem"**.
3. Clique em **"Criar"** e preencha os seguintes campos:
   - **Grupo de Recursos:** Crie um novo ou selecione um existente.
   - **Região:** Escolha a mais próxima de sua localização.
   - **Nome do Recurso:** Escolha um nome único.
   - **Plano de Tarifação:** Selecione o plano gratuito para testes iniciais.
4. Clique em **"Revisar e Criar"** e, em seguida, em **"Criar"**.

**Insight:** Escolher a região mais próxima reduz a latência e melhora o desempenho dos serviços.

---

### 3. Explorar a Análise de Sentimentos no Portal
1. Após a criação do recurso, acesse o link **[Azure Cognitive Services](https://language.cognitive.azure.com)**.
2. Preencha os campos:
    - Assinatura Azure.
    - Tipo de Serviço.
    - Nome do serviço.
3. Clique em **"Done"**.
4. Vá para a aba de **"Classify texts"**.
5. Selecione a opção **"Analyze sentiment and opinions"**.
6. Nesta tela, é possível utilizar exemplos de textos para testar a funcionalidade de analisar o sentimento e opiniões de textos.

**Texto de exemplo:**

```plaintext
Tired hotel with poor service
The Royal Hotel, London, United Kingdom
5/6/2018
This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
```

7. Verifique a saída com o resultado de cada frase.

**Insight:** O portal permite que você teste rapidamente a funcionalidade de análise de sentimentos sem a necessidade de configurar um ambiente local ou escrever código.

---

## Conclusão

Este guia fornece uma introdução prática ao uso do Azure para análise de sentimentos diretamente no portal. Explore outros serviços do Azure, como Speech-to-Text e Language Understanding, para expandir suas aplicações.

**Dica:** Consulte os seguintes links para aprofundar seus conhecimentos e explorar mais funcionalidades:

- [Laboratório de Speech-to-Text no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
- [Laboratório de Análise de Texto no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
- [Documentação oficial do Azure](https://learn.microsoft.com/azure/)

