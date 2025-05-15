# Guia Azure Speech Studio

1. Acessar o [Speech Studio](https://speech.microsoft.com/)
2. Crie um recurso de **Serviço de Fala** no Azure
3. Utilize a chave de assinatura para autenticação

## Funcionalidades testadas
- **Texto para Fala**:
  - Vozes disponíveis: `pt-BR-AntonioNeural` (masculino), `pt-BR-FranciscaNeural` (feminino)
  - Formato de saída: `.wav`

- **Fala para texto**:
  - Reconhecimento de áudio em tempo real

## Exemplo de código (em Python!)
```python
speech_synthesizer = speechsdk.SpeechSynthesizer(speech_config=speech_config)
result = speech_synthesizer.speak_text_async("Olá mundo!").get()
