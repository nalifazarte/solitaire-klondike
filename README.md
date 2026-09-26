# Solitaire Klondike

Um jogo gratuito de Klondike, sem anúncios, dependências externas ou chamadas de rede durante a partida. Os arquivos são estáticos e preparados para publicação no GitHub Pages e instalação como PWA.

## Estado atual

- Protótipo funcional com compra de 1 ou 3 cartas, pilhas de fundação, movimentos válidos, desfazer e nova partida.
- Cartas de frente renderizadas como imagens PNG em tempo de execução; o verso do primeiro tema é uma ilustração PNG local.
- Manifesto e service worker preparados para uso offline.
- Sem garantia de que toda distribuição aleatória seja ganhável.

## Publicar no GitHub Pages

1. Em **Settings → Pages**, defina **Source: GitHub Actions**.
2. Faça push para `main`. O workflow `.github/workflows/deploy.yml` publica o conteúdo deste diretório.
3. A URL do projeto será `https://nalifazarte.github.io/solitaire-klondike/` depois da primeira publicação.

Abra a URL uma vez online para instalar e permitir que o service worker guarde os arquivos. Depois disso, a partida funciona sem conexão.

## Instalar

- **iPhone/iPad:** abra no Safari, toque em Compartilhar e escolha **Adicionar à Tela de Início**.
- **Android:** abra no Chrome e escolha **Instalar app** ou **Adicionar à tela inicial**.

## Referências de temas recebidas

As referências abaixo ficam guardadas como direções para temas futuros. Para controlar o tamanho e o custo de geração, este início implementa e gera arte apenas para **Noite Estrelada**; nenhum dos decks futuros foi produzido.

1. Noite Estrelada — raios celestes, estrelas e folk-art colorida.
2. Gato Geométrico — creme, amarelo e verde-água.
3. Pop Rosa & Azul — cartas gráficas em rosa, azul e laranja.
4. Folk Fantástico — criaturas ornamentais e cores saturadas.
5. Gravura Vintage — ilustração de corte clássica em roxo.
6. Botânico Monocromático — retratos ornamentais em preto e marfim.
7. Primárias Gráficas — formas geométricas em azul, coral e amarelo.
8. Rosa Art Déco — rosa, vermelho e detalhes florais elegantes.
9. Pixel 8-bit — personagens e naipes em pixel art.
10. Preto & Laranja — alto contraste e formas minimalistas.
11. Rosa Romântico — naipes delicados e embalagem floral.
12. Minimalismo Geométrico — papel texturizado, grade discreta e naipes em vermelho escuro.

As imagens são usadas como referência de estilo para criar arte original, sem reproduzir marcas ou textos das embalagens fotografadas. O verso gerado foi otimizado para JPEG para reduzir o download e o cache offline.

