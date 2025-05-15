
---

#### 3. **Documentação do Language Studio**
```markdown
# 📚 Guia do Azure Language Studio

## Serviços Utilizados
- **Análise de Sentimentos**:
  - Pontuação: 0.8 (Positivo)
  - Frases-chave extraídas: "excelente suporte", "facilidade de uso"

- **Reconhecimento de Entidades**:
  - Tipos detectados: `LOCAL` (São Paulo), `PESSOA` (Carlos Silva)

## Fluxo de Trabalho
1. Upload de arquivo `.txt` com avaliações de clientes
2. Configuração do modelo padrão `pt-BR`
3. Visualização dos resultados em JSON

## Exemplo de Saída
```json
{
  "sentiment": "positive",
  "keyPhrases": ["intuitivo", "rápido deploy"],
  "entities": [
    {"text": "Rio de Janeiro", "type": "LOCATION"}
  ]
}
