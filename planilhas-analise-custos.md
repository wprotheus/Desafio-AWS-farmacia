# DIO - GFT Start #7 - Java

## Autor
🔸[wprotheus](https://github.com/wprotheus)

---

## Redução dos Custos em Farmácias com AWS

>---

# Planilhas de Análise de Custos

## Análise Inicial
### Exemplo de Custos Identificados
- **Instâncias EC2 ociosas**:
    - Tipo de instância: m5.large
    - Custo mensal: $120 por instância
    - Economia projetada ao parar ou redimensionar: $80 por instância.
- **Armazenamento S3**:
    - Buckets com dados raramente acessados (classe Standard).
    - Economia ao migrar para **S3 Glacier**: 40% do custo atual.

## Projeções de Economia
- **Instâncias EC2**:
    - Redução de custos com o uso de instâncias reservadas ou Savings Plans: 30%.
- **Armazenamento S3**:
    - Economia com camadas de armazenamento: 40%.
- **Total Estimado de Economia Mensal**:
    - Aproximadamente 20% dos custos totais da conta AWS.

