# 🎤 Análise de Fala e Linguagem Natural com Azure AI

Este projeto tem como objetivo explorar as capacidades de IA da Azure para processamento de voz e linguagem natural

## 📝 Descrição do Desavio
Desenvolver habilidades práticas com:
- Azure Speech Studio
- Azure Language Studio

## 🧠 Objetivos de Aprendizagem
| Habilidade | Ferramenta | Aplicação |
|------------|-----------|-----------|
| Processamento de voz | Speech Studio | Conversão texto-voz e vice-versa |
| NLP | Language Studio | Análise de sentimentos, reconhecimento de entidades |

## 🛠️ Tecnologias Utilizadas
- **Azure Speech Studio**
  - Síntese de voz
  - Reconhecimento de fala
- **Azure Language Studio**
  - Análise de sentimentos
  - Extração de frases-chave
    

## 📋 Passos do Projeto
1. **Configuração Inicial**
   - Criação de recursos no Azure
   - Acesso aos estúdios

2. **Experimentos Práticos**
   -  Conversão texto-voz com diferentes vozes
   -  Extração de entidades de textos
   -  Análise de sentimentos em avaliações


## 💡 Insights e Aprendizados
```python
# Exemplo de código para síntese de voz
import azure.cognitiveservices.speech as speechsdk

speech_config = speechsdk.SpeechConfig(
    subscription="SUA_CHAVE", 
    region="eastus"
)
