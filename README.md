# Vértice Estoque

Sistema web responsivo para controle simples de estoque.

## Recursos
- Cadastro de produto com nome, quantidade e valor unitário.
- Edição dos produtos cadastrados.
- Registro de venda por quantidade, com baixa automática no estoque.
- Alertas automáticos quando um produto fica com menos de 6 unidades (inclui estoque zerado).
- Painel com total de produtos, unidades e valor estimado em estoque.
- Histórico recente de vendas.
- Exportação do inventário para CSV.
- Layout responsivo para celular e computador.

## Como usar
Abra `index.html` em um navegador moderno. Não precisa instalar nada.

**Importante:** os dados são armazenados localmente no navegador/dispositivo por meio do `localStorage`. Eles não são sincronizados entre dispositivos e podem ser apagados ao limpar os dados do navegador. Use a exportação CSV para manter uma cópia do inventário.

## Publicar pelo GitHub Pages
1. Entre em https://github.com e crie um repositório chamado `vertice-estoque`.
2. Envie o arquivo `index.html` para a raiz do repositório (ou envie todos os arquivos deste pacote).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
6. Aguarde a publicação; o GitHub mostrará o endereço público na seção Pages.

O site é estático e não exige build. Para compartilhar dados de estoque entre pessoas ou dispositivos, será necessário adicionar um backend e autenticação.
