---
layout: posts
title:  "Implementação de um sistema de captura de movimentos de sinais de libras para animação de avatares 3D"
date:   2024-11-01 16:16:37 -0600
categories: trabalho
autornick: GabrielJV
autor: "Gabriel Junqueira do Val"
orientador: "Prof. Assoc. Antônio Carlos Sementille"

---

Este trabalho propõe um sistema que captura e redireciona os movimentos da Língua Brasileira de Sinais (LIBRAS) para animar avatares 3D, usando ferramentas de inteligência artificial e visão computacional. A captura dos gestos é realizada com o MediaPipe, que identifica e rastreia pontos-chave do corpo em vídeos de sinais de LIBRAS. Esses dados, uma vez extraídos, são processados pelo motor Unity3D, que anima avatares com base nas informações de movimento obtidas. O sistema segue um pipeline estruturado, que abrange desde o processamento inicial dos vídeos até a animação final dos avatares. Durante esse fluxo, os landmarks corporais são mapeados e aplicados a um esqueleto virtual. Que é renderizado pelo motor de jogos Unity3D e replica os movimentos como apresentados no dataset.
