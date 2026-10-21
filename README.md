# Estande Laser

Treino de tiro a seco com laser. A câmera do celular encontra o ponto vermelho no alvo, pontua cada tiro pelos anéis e mede o tempo de cada disparo a partir do bip.

**Usar:** https://perissatto.github.io/estande-laser/ (entrar com a conta Google)

- Ciclos configuráveis (quantidade e segundos), com bip de início e dois bips curtos no fim; tiros antes do bip (A) ou depois do fim (T) não pontuam.
- Calibração automática pelo alvo iTarget BullsEye: os 4 triângulos corrigem a perspectiva. Outros alvos ISSF com calibração por toque.
- Zoom óptico da câmera quando o aparelho permite; zoom digital nos demais.
- Modos: Câmera ao vivo, Vídeo gravado (os bips são detectados no áudio) e Simulação.
- Ranking on-line (Firebase): precisão (média por tiro), reação média e volume de tiros.

`firestore.rules` contém as regras de segurança do Firestore usadas pelo app.
