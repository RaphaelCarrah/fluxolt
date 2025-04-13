
🛠️ GERADOR DE PÁGINA DE ETAPAS 

Este projeto é uma ferramenta web interativa desenvolvida para facilitar a criação de páginas de fluxo operacionais no padrão visual do projeto Ele permite que qualquer colaborador, mesmo sem conhecimento técnico, monte páginas com etapas logísticas de forma padronizada, responsiva e pronta para impressão ou uso digital.

FUNCIONALIDADES:

- Criação de etapas com ícone (emoji ou imagem personalizada), título e descrição
- Upload de imagens com conversão automática para Base64
- Preview da imagem com botão de remoção
- Geração de HTML final com:
  - Scroll vertical com snapping
  - Navbar fixa com título do fluxo
  - Animação de seta indicativa
  - Layout 100% responsivo
- Botão para baixar o HTML final
- Botão para gerar PDF direto do navegador
- Logo da Lafaiete Tintas no canto inferior esquerdo com animação flutuante
- Botões de ação aparecem apenas após adicionar a primeira etapa

COMO USAR:

1. Abra o arquivo index.html em um navegador moderno (sem necessidade de servidor)
2. Preencha o nome do fluxo
3. Clique em "➕ Adicionar Etapa"
4. Escolha um emoji ou faça upload de uma imagem
5. Informe o título e a descrição da etapa
6. Adicione quantas etapas quiser
7. Após adicionar a primeira etapa, os botões "Download de Fluxo" (gera .html) e "Salvar em PDF" (abre janela de impressão) ficarão visíveis

O HTML gerado pode ser:
- Distribuído via QR Code
- Usado em painéis físicos
- Acessado por dispositivos móveis

TECNOLOGIAS UTILIZADAS:

- HTML5
- CSS3 (embutido)
- JavaScript puro (sem bibliotecas externas)
- Codificação Base64 para imagens
- Animações CSS
- Design responsivo com vw, vh, scroll-snap

PADRÃO VISUAL:

- Tema escuro
- Ícones grandes e centralizados
- Cada etapa ocupa 100% da tela
- Rolagem vertical com travamento em cada etapa
- Mobile-first

LOGO FLUTUANTE:

A logo aparece fixa no canto inferior esquerdo, com uma animação de sobe e desce contínua.  
Ela é embutida em Base64 diretamente no HTML gerado, como no exemplo abaixo:

<img class="floating-logo" src="data:image/png;base64,SUA_LOGO_AQUI" alt="logo" />

DICAS:

- Para trocar a logo, substitua o valor Base64 do src da imagem com class="floating-logo"
- Você pode hospedar o HTML em qualquer servidor simples, ou usar com QR Codes impressos
- Ideal para painéis de orientação, etiquetas visuais de processo e uso em coletor de dados



Feito com 💙 por Raphael Carrah
