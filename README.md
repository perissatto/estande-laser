# Estande Laser

Treino de tiro a seco com laser. A câmera do celular encontra o ponto vermelho no alvo, pontua cada tiro pelos anéis e mede o tempo de cada disparo a partir do bip.

**Site:** https://perissatto.github.io/estande-laser/ (página de apresentação)
**Plataforma:** https://perissatto.github.io/estande-laser/app.html (entrar com a conta Google)

- Ciclos configuráveis (quantidade e segundos), com bip de início e dois bips curtos no fim; tiros antes do bip (A) ou depois do fim (T) não pontuam.
- 4 alvos para imprimir (pasta `alvos/`): BullsEye, Quick Draw (cabeça e tronco), Duelo (J1 × J2) e High Score (5 discos). Os PDFs podem ser baixados direto no site.
- Calibração automática pelos 4 triângulos, que ficam na mesma posição em todos os alvos e corrigem a perspectiva; marcação manual por toque como alternativa.
- Zoom óptico da câmera quando o aparelho permite; zoom digital nos demais.
- Modos: Câmera ao vivo, Vídeo gravado (os bips são detectados no áudio) e Simulação.
- Ranking on-line (Firebase): precisão (média por tiro), reação média e volume de tiros.

`firestore.rules` contém as regras de segurança do Firestore usadas pelo app.
