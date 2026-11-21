# Campanha Presidencial — IA Responsável

Versão web do jogo Pygame publicada com GitHub Pages e `pygbag 0.9.2`.

- Jogo: https://bm000001.github.io/t1/
- Celular: prefira a orientação horizontal. Toque na tela para iniciar o Pygame.
- Perguntas, alternativas, feedbacks, arte do personagem, pontuação (+20/−10) e regra da meta de 55% foram preservados.
- Correções de compatibilidade: territórios e IDs únicos das 24 missões foram alinhados ao mapa; a meta de 55% usa o total real de pontos das 24 missões.
- O bundle web não inclui `spritesheet.bmp`: a busca no código confirmou que o jogo não a carrega; a imagem do personagem usada na execução (`jogador.png`) está incluída.
- O commit original segue recuperável no histórico como ancestral: `38bed0af0b1cd03b998f5645fc913c954a36bfc0`.

O runtime Pygbag carrega `pygame.apk`. O workflow em `.github/workflows/pages.yml` publica o diretório raiz a cada atualização de `main`.
