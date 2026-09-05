# AeroFix — RES-APP

App de consulta visual de falhas de aerogeradores.

**Site:** https://manoellion.github.io/RES-APP/

## Arquivos

Esta raiz contém a versão compilada, pronta para o GitHub Pages. O código completo em TypeScript e React, com testes e instruções, está em [AeroFix-codigo-fonte.zip](AeroFix-codigo-fonte.zip).

## Publicação

Em Settings → Pages, selecione Deploy from a branch, branch main, pasta / (root). O GitHub Pages publica automaticamente alterações nos arquivos desta raiz.

## Alterar o aplicativo

Baixe e extraia o ZIP. Com Node.js 24 e pnpm, execute `pnpm install --frozen-lockfile`, `pnpm dev` e `pnpm build`. O projeto-fonte inclui um fluxo opcional de GitHub Actions para quem preferir publicar a árvore completa de código no repositório.

Os arquivos JavaScript e CSS deste deploy estão na raiz; os caminhos no index.html foram ajustados a essa organização.

## Dados e Drive

Cada usuário mantém sua base no navegador ou configura sua conexão com o Google Drive em Drive e backup. Não há dados pessoais nem credenciais no repositório. A integração Google exige configuração e teste com uma conta real. A origem OAuth para esta versão é `https://manoellion.github.io`.

Para transferir registros do site anterior, exporte o backup lá e importe aqui.
