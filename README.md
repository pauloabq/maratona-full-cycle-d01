# Índice
- [Sobre](#sobre)
- [Desafio 1 (Enunciado)](#desafio-1-enunciado)
- [Resolução do desafio](#resolução-do-desafio)  

# Sobre

Repositório contendo o desafio 01 elaborado na **Maratona Full Cycle 2.0** promovido pela **[Full Cycle](http://fullcycle.com.br)** (School of Net e Code Education). Os desafios consistiam em elaborar as aplicações, criar as imagens com o docker e publica-las  no dockerhub.
- O desafio 1 consistia em subir um servidor NodeJS com uma mensagem.

# Desafio 1 (Enunciado)

## Instalação e preparação do ambiente

O primeiro passo para que você consiga acompanhar muito bem a Maratona é ter o seu ambiente de desenvolvimento pronto para conseguir simular tudo que te apresentaremos nos próximos vídeos. Nesse ponto o que você deve fazer como desafio será:

1. Instalar o Node.js em seu computador
2. Criar um webserver que escuta na porta 3000
3. Ao acessar o webserver, a seguinte mesagem deverá aparecer: "Maratona Full Cycle 2.0"
4. Instalar o Docker em seu computador
5. Gerar uma imagem Docker dessa aplicação a partir da imagem node:14.1-alpine.
6. Publicar a imagem no Dockerhub
7. Quando executarmos: docker run -p 3000:3000 seu-login-docker/nome-da-sua-imagem deveremos ver a mensagem na porta 3000 de nosso browser
8. Postar nos comentários do vídeo a URL da sua imagem para que possamos executar

# Resolução do desafio

## Imagem Docker do desafio:
`https://hub.docker.com/r/pauloabq/maratona-full-cycle-d01`

### Instruções

Baixar a imagem docker e rodar:
```
docker pull pauloabq/maratona-full-cycle-d01
docker run -p 3000:3000 pauloabq/maratona-full-cycle-d01
```