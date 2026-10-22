# Anilha

Diário de cargas para a academia. Cadastre a ficha do seu personal, registre as séries durante o treino e acompanhe a evolução.

- Funciona offline, instalável na tela inicial (PWA).
- Sem conta, sem servidor, sem custo: os dados ficam no aparelho (localStorage).
- Backup e restauração por arquivo (aba Ficha).

## Publicar (GitHub Pages)

1. Crie um repositório novo e envie estes arquivos na raiz.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o endereço no celular e use "Adicionar à tela inicial".

## Atualizar

Envie os arquivos novos ao repositório. O app atualiza sozinho na abertura seguinte (pode precisar abrir duas vezes).

## Estrutura

- `index.html`: telas, estilos e lógica
- `sw.js`: cache para uso offline
- `manifest.webmanifest` e `icon-*.png`: instalação no celular
