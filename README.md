# Tradutor de Artigos Técnicos com AzureAI

## Visão Geral

Este projeto utiliza o serviço de Tradutor da AzureAI para traduzir artigos técnicos de forma eficiente e precisa. O Tradutor é uma API REST de tradução de texto multilíngue que oferece recursos avançados para lidar com diversos aspectos da tradução.

## Funcionalidades Principais

### Serviço Tradutor

- **Detecção de idioma**: Identifica automaticamente o idioma do texto de origem.
- **Tradução de um para muitos**: Permite traduzir um texto para múltiplos idiomas simultaneamente.
- **Transliteração de script**: Converte texto de um script para outro (por exemplo, do árabe para o latino).

### Processo de Tradução

1. **Detecção**: Identifica o idioma do texto de origem.
2. **Tradução**: Converte o texto para o idioma desejado.
3. **Transliteração**: Realiza a conversão de scripts, quando necessário.

### Opções Avançadas de Tradução

- **Alinhamento de palavras**: Mapeia a localização de cada palavra no texto traduzido, incluindo informações sobre o tamanho da fonte.
- **Comprimento da frase**: Fornece estimativas de caracteres para frases originais e traduzidas.
- **Filtro de conteúdo ofensivo**: Identifica e trata conteúdo potencialmente ofensivo.

## Tradução Personalizada

Para obter traduções mais precisas em domínios específicos, é possível criar um modelo de tradução personalizado:

1. Acessar o Portal do Tradutor Personalizado.
2. Criar um espaço de trabalho vinculado ao recurso do Tradutor de IA do Azure.
3. Criar um projeto de tradução.
4. Carregar arquivos de dados de treinamento.
5. Treinar o modelo personalizado.
6. Utilizar o modelo através da API do Tradutor, especificando o parâmetro de categoria com o ID do projeto.

## Benefícios

- Tradução rápida e precisa de artigos técnicos.
- Suporte a múltiplos idiomas e scripts.
- Opções avançadas para controle fino da tradução.
- Possibilidade de criar modelos personalizados para domínios específicos.

## Tecnologias Utilizadas

- Azure AI Translator
- API REST
- Azure OpenAI

