# 🧠 Extração de Frases-Chave com Azure AI - Text Analytics

Este projeto demonstra o uso da ferramenta **Azure Language Studio** para extrair **frases-chave** (key phrases) de textos com o serviço **Text Analytics** do Azure AI.

---

## 💡 Objetivo

Utilizar inteligência artificial para analisar textos e identificar automaticamente as frases mais relevantes, facilitando a compreensão de conteúdos longos ou complexos.

---

## 🚀 Como funciona

1. Acesse o [Azure Language Studio](https://language.cognitive.azure.com/)
2. Crie (ou selecione) um recurso do tipo `Language`
3. Acesse a ferramenta de **Text Analytics**
4. Escolha a opção **Extract Key Phrases**
5. Insira um texto no campo de entrada e clique em **Run**
6. Veja as frases-chave identificadas pela IA do Azure

---

## 🖼️ Prints do processo

### 🔹 Interface do Language Studio
![print_language_studio](insights/print_language_studio.png)

### 🔹 Resultado da Análise
![print_resultado](insights/print_resultado.png)

---

## 📁 Estrutura do repositório

```bash
key-phrase-extraction/
├── inputs/
│   └── exemplo_texto.txt
├── insights/
│   └── print_language_studio.png
│   └── print_resultado.png
├── readme.md
