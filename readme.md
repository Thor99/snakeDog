# Documentação do projeto "Snake", para a disciplina de Computacão Gráfica, turma de 2016.

## Objetivo:

* Usar estruturas de dados e a sintaxe do OpenGL para criar um jogo.

## Código:

O projeto foi desenvolvido utilizando as classes: Bitmap, Camera, Cube, Snake, Texture, Vec3D.

## Como utilizar:

O projeto possui quatro comandos por teclado:

* **Setinha para cima**: Usado para direcionar a snake para o norte.

* **Setinha para esquerda**: Usado para direcionar a snake para o oeste.

* **Setinha para baixo**: Usado para direcionar a snake para o sul.

* **Setinha para direita**: Usado para direcionar a snake para o leste.

## Como compilar:

> g++ -o main main.cpp cube.cpp camera.cpp Bitmap.cpp snake.cpp texture.cpp vec3d.cpp -std=c++11 -lglut -lGL -lGLU -lm

## Como executar:

> ./main

## Observação:

Tenha certeza que você possui um arquivo BMP chamado **"hugo.bmp"** no mesmo diretório que o projeto.
