# Análise de Texto com Azure AI Language

## Introdução

Este projeto segue as instruções do laboratório [Análise de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html) da Microsoft Learn. O objetivo é utilizar o **Azure AI Language** para realizar análise de sentimentos e extração de entidades em textos fornecidos.

## Processo Passo a Passo

### 1. Criação do Recurso no Azure

1. Acesse o [Portal do Azure](https://portal.azure.com) e faça login.
2. Crie um novo recurso do tipo **Language Service**.
3. Configure os parâmetros como nome, região e plano de preços.
4. Confirme e aguarde a implantação do recurso.

### 2. Acesso ao Language Studio

1. Navegue até o [Language Studio](https://language.cognitive.azure.com).
2. Selecione o recurso criado anteriormente.
3. Explore as ferramentas de análise de texto.

### 3. Análise de Sentimento

```bash
# Exemplo de entrada
"O atendimento foi excelente, gostei muito da experiência!"

# Saída esperada
Sentimento geral: Positivo
Sentimento por frases:
- "O atendimento foi excelente" -> Positivo
- "Gostei muito da experiência" -> Positivo
```

### 4. Extração de Entidades

```bash
# Exemplo de entrada
"A Microsoft tem sede em Redmond e foi fundada por Bill Gates."

# Saída esperada
Entidades identificadas:
- "Microsoft" -> Organização
- "Redmond" -> Local
- "Bill Gates" -> Pessoa
```

## Insights e Possibilidades

### Aprendizados

- O **Azure AI Language** é poderoso para extrair insights de grandes volumes de texto.
- A **análise de sentimentos** pode ajudar empresas a entenderem opiniões de clientes.
- A **extração de entidades** facilita a organização automática de informações.

### Possibilidades de Uso

- Monitoramento de feedbacks em redes sociais.
- Classificação automática de e-mails e tickets de suporte.
- Análise de sentimentos em avaliações de produtos.

---

## Referências

- [Documentação Oficial do Azure AI Language](https://learn.microsoft.com/azure/cognitive-services/language-service/overview)
- [Laboratório Oficial da Microsoft](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

Esse README serve como guia para reproduzir a experiência do laboratório e explorar as funcionalidades de análise de texto do Azure AI Language.

