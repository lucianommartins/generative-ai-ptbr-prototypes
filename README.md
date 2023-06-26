# Generative AI

Este repositório é um fork não oficial do repositório [Generative AI](https://cloud.google.com/ai/generative-ai) de Google Cloud.

Aqui você encontra notebooks e conteúdos que demonstram como usar, desenvolver e gerenciar workflows de Generative AI utilizando [Generative AI](https://cloud.google.com/ai/generative-ai) na [Vertex AI](https://cloud.google.com/vertex-ai) da Google Cloud.


## Estrutura de Diretórios
```
generative-ai/
├── language/
    ├── examples/             
        ├── document-qa/             - exemplos de doc Q&A
        ├── document-summarization/  - exemplos de doc summarization
        ├── langchain-intro/         - exemplos de langchain
        ├── prompt-design/           - exemplos de prompts
        ├── reference-architectures/ - exemplos de use-cases architectures
        └── tuning/                  - exemplos com tuning models
└── setup-env/                       - instruções de setup
```

## Conteúdo
- [Language/](language/)
  - [Getting Started with Generative AI Studio without code](language/intro_generative_ai_studio.md)
  - [Intro to Vertex AI PaLM API](language/intro_palm_api.ipynb)
  - [Intro to Prompt Design](language/intro_prompt_design.ipynb)
  - [Examples/](language/examples/)
    - [Prompt Design/](language/examples/prompt-design/)
      - [Ideation](language/examples/prompt-design/ideation.ipynb)
      - [Question & Answering](language/examples/prompt-design/question_answering.ipynb)
      - [Text Classifiction](language/examples/prompt-design/text_classification.ipynb)
      - [Text Extraction](language/examples/prompt-design/text_extraction.ipynb)
      - [Text Summarization](language/examples/prompt-design/text_summarization.ipynb)
    - [Reference-architectures/](language/examples/reference-architectures/) \***NEW**\*
      - [Product Description Generator from Image](language/examples/reference-architectures/product_description_generator_image.ipynb)
    - [Document Q&A/](language/examples/document-qa/) \***NEW**\*
      - [Question Answering with Large Documents with LangChain](language/examples/document-qa/question_answering_large_documents_langchain.ipynb)
      - [Question Answering with Large Documents (without LangChain)](language/examples/document-qa/question_answering_large_documents.ipynb)
    - [Document Summarization/](language/examples/document-summarization/) \***NEW**\*
      - [Summarization with Large Documents with LangChain](language/examples/document-summarization/summarization_large_documents_langchain.ipynb)
      - [Summarization with Large Documents (without LangChain)](language/examples/document-summarization/summarization_large_documents.ipynb)
    - [LangChain-intro/](language/examples/langchain-intro/) \***NEW**\*
      - [Getting Started with LangChain 🦜️🔗 + Vertex AI PaLM API](language/examples/langchain-intro/intro_langchain_palm_api.ipynb)
    - [Tuning/](language/examples/tuning/)
      - [Tuning a Foundational Model, Deploying, and Making Predictions](language/examples/tuning/getting_started_tuning.ipynb)
      

## Configurando um projeto na Google Cloud
Você precisará de um projeto na Google Cloud para utilizar estes recursos.

1. [Selecione ou crie um projeto na Google Cloud](https://console.cloud.google.com/cloud-resource-manager). Quando você criar sua conta, você terá U$300,00 de créditos para suas atividades iniciais .

2. [Configure uma billing account em seu projeto](https://cloud.google.com/billing/docs/how-to/modify-project).

3. [Ative a API da Vertex AI](https://console.cloud.google.com/flows/enableapi?apiid=aiplatform.googleapis.com). 

## Configure seu ambiente Python ou Jupyter
Leia o arquivo README localizado no diretório [setup-env](https://github.com/GoogleCloudPlatform/generative-ai/tree/main/setup-env) sobre informações de como utilizar estes recursos no Google Colab ou diretamente na Vertex AI Workbench.

## Recursos de Generative AI na Google Cloud
Cheque a list de [recursos de Google Generative AI](RESOURCES.md) como páginas oficiais de produtos, documentações, vídeos, cursos gratuitos e mais.

## Contribuindo
Contribuições são super bem vindas! Verifique como em [Contributing Guide](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/CONTRIBUTING.md) no repositório oficial de Google Cloud.

## Buscando ajuda
Por favor use a [página de issues](https://github.com/GoogleCloudPlatform/generative-ai/issues) do repositório oficial de Google Cloud para compartilhar feedbacks ou submeter relatórios de bugs.

## Disclaimer
Esse repositório não é um produto Google oficialmente suportado. Os códigos aqui presentes são puramente para demontração.