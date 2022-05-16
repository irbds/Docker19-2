# Cowsay:

  ### Descrição:
   Este projeto foi desenvolvido como solução dos exercicios propostos pela escola de proramação Trybe.</br>
   Seu objetivo é criar uma imagem docker utilizando como base a imagem chuanwen/cowsay que pode ser encontrada [aqui](https://hub.docker.com/r/chuanwen/cowsay/).</br>
   Exercicio realizado no dia 13/05/2022.
   
  ### Funcionalidades:
   Ao criar um container utilizando a imagem base é retornado um texto aleatorio:</br>
   
    / To err is human, but when the eraser \
    | wears out before the pencil, you're  |
    \ overdoing it a little.               /
     --------------------------------------
              \   ^__^
               \  (oo)\_______
                  (__)\       )\/\
                      ||----w |
                      ||     ||"
   
   Com a imagem criada por esse Dockerfile podemos passar um texto como argumento ao criar o container, tendo assim total controle sobre o que é dito pela vaquinha.
    
    < Agora posso dizer qualquer coisa >
    ----------------------------------
            \    ^__^
              \  (oo)\_______
                 (__)\       )\/\
                     ||----w |
                     ||     ||
                     
### Como utilizar:
  1. faça clone o clone desse projeto com o seguinte comando:</br>
  
      SSH:
      
          git clone git@github.com:irbds/Docker19-2.git
          
  2. Entre na pasta criada
  
          cd Docker19-2/    
          
  3. Gere uma imagem a partir do Dockerfile 
        
          docker image build -t cow:cowSayAnything .
          
  4. Crie um conteiner a partir da imagem gerada com a frase que você quer que ela diga
  
          docker run cow:cowSayAnything SUA FRASE VAI AQUI
          
  5. Caso veja essa imagem em seu terminal significa que deu tudo certo
  
          < SUA FRASE VAI AQUI >
           ------------
                  \   ^__^
                   \  (oo)\_______
                      (__)\       )\/\
                          ||----w |
                          ||     ||

### Contato:
   Criticas, sugestões, elogios:
       
    igor.rafael.briano@gmail.com
    
### Autor:

    Igor Rafael
