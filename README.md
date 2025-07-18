# Desafio Azure Speech Studio & Language Studio - DIO

## Descrição

Este repositório contém a documentação da minha experiência prática com as ferramentas **Azure Speech Studio** e **Azure Language Studio**, como parte do desafio proposto pela DIO. O objetivo foi aplicar conceitos de inteligência artificial aplicados à fala e linguagem natural, reforçando o aprendizado através da experimentação com as ferramentas da Microsoft.

---

## Objetivos do Desafio

- Explorar as funcionalidades do Speech Studio (fala para texto, texto para fala, tradução de fala)
- Utilizar o Language Studio para análise de texto (sentimento, entidades nomeadas, classificação)
- Documentar os processos e aprendizados
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento técnico

---

## Ferramentas Utilizadas

- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.azure.com/)
- Conta Microsoft gratuita
- GitHub para versionamento e publicação
- VS Code (editor de texto para Markdown)

---

## Atividades Realizadas

### 🔊 Azure Speech Studio

#### Speech-to-Text
- Teste com arquivos de áudio em português do Brasil.
- Reconhecimento de fala preciso, mesmo com ruído de fundo leve.
- Foi possível configurar idioma, ponto de pontuação e nível de precisão.

#### Text-to-Speech
- Geração de fala com diferentes vozes e sotaques.
- Personalização de tom, velocidade e pausas usando marcações SSML.

#### Speech Translation
- Tradução simultânea da fala em português para inglês.
- Resultados eficazes, embora com pequenas perdas de contexto em frases complexas.

---

### 🧾 Azure Language Studio

#### Análise de Sentimento
- Análise de textos opinativos (comentários de redes sociais, avaliações).
- Classificação precisa entre **positivo**, **neutro** e **negativo**.
- Pontuação atribuída a cada frase, útil para relatórios.

#### Extração de Entidades Nomeadas
- Extração automática de nomes de pessoas, locais, organizações e datas.
- Utilizado texto de notícias reais.

#### Classificação de Texto (Custom Text Classification)
- Teste com projeto customizado com dois rótulos: "Elogio" e "Crítica".
- Treinamento de modelo com poucos exemplos foi possível, mas melhor desempenho com mais dados.

#### Perguntas e Respostas
- Análise de documentos PDF para perguntas feitas em linguagem natural.
- Modelo retornou respostas contextualizadas baseadas no conteúdo.

---

## Aprendizados & Insights

- Ferramentas da Microsoft são muito acessíveis para iniciantes e não exigem código.
- Speech Studio é altamente responsivo e personalizável, ótimo para assistentes virtuais e transcrições.
- Language Studio permite construir soluções poderosas sem necessidade de conhecimento profundo em NLP.
- O uso de **SSML** para controle de voz no Text-to-Speech é um diferencial para produtos finais.
- Projetos de classificação personalizados demandam mais dados para boa performance.

---

## Conclusão

Este laboratório foi importante para consolidar meus conhecimentos sobre inteligência artificial aplicada à fala e linguagem natural. As ferramentas da Microsoft são acessíveis, poderosas e abrem portas para diversas aplicações no mundo real. Recomendo fortemente a prática a todos que desejam aprender IA de forma prática e objetiva.

---
