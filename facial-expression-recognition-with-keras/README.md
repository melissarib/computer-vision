# Facial-Expression-Recognition
Este projeto faz parte do Projeto Guiado do Coursera - [Facial Expression Recognition with Keras](https://www.coursera.org/projects/facial-expression-recognition-keras) 

Neste projeto, iremos construir e treinar uma rede neural convolucional (CNN) no Keras a partir do zero para reconhecer expressões faciais.

Os dados consistem em imagens de rostos em tons de cinza de 48x48 pixels. O objetivo é classificar cada rosto com base na emoção mostrada na expressão facial em uma das sete categorias (0 = Zangado, 1 = Nojo, 2 = Medo, 3 = Feliz, 4 = Triste, 5 = Surpresa, 6 = Neutro) . 

Usaremos OpenCV para detectar automaticamente rostos em imagens e desenhar caixas delimitadoras ao redor deles. Depois de treinar, salvar e exportar o CNN, serviremos diretamente o modelo treinado para uma interface da web e realizaremos o reconhecimento de expressão facial em tempo real em dados de vídeo e imagem.

O projeto pode ser dividido em duas partes:
1) Construir e treinar um modelo em Keras para reconhecimento de expressão facial.
2) Implantar o modelo na web usando FLASK.

Enjoy it! ♡
