# Repositório GitHub Rembg Simplificado

Este repositório processa imagens enviadas pelo plugin WordPress usando o GitHub Actions.

## Como funciona
1. O plugin envia imagens (.png, .jpg, .jpeg) para este repositório.
2. O GitHub Actions detecta o envio e executa o workflow `rembg.yml`.
3. As imagens são movidas para `inputs/`, processadas pelo `rembg`, e os resultados vão para `outputs/`.
4. O plugin busca o resultado diretamente do GitHub.

## Estrutura automática
- As pastas `inputs/` e `outputs/` são criadas automaticamente pelo workflow.
