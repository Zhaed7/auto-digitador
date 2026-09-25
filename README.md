# Auto-Digitador 

Um script simples e eficiente em Python para digitação automática de textos. Desenvolvido com uma interface gráfica amigável, ele é otimizado para teclados no padrão ABNT 2, garantindo o funcionamento perfeito de acentos, pontuações e do caractere "ç".

## Funcionalidades
Suporte ABNT 2: Utiliza a biblioteca `keyboard` para injetar os caracteres diretamente no sistema, evitando bugs com acentos (á, ê, ã) e cedilha (ç).
Interface Gráfica: Janela simples e intuitiva feita com `Tkinter` (fundo azul escuro e letras brancas).
Processamento em Segundo Plano: Utiliza `threading` para realizar a contagem do delay sem congelar a interface (Não trava a tela!).
Delay Estratégico: Pausa de 10 segundos antes de iniciar a digitação, dando tempo suficiente para o usuário focar na janela onde o texto será inserido.

## Plataformas
Disponível para sistemas Windows, entretanto em breve estou preparando a versão pra rodar em distro Linux como o Linux Mint
