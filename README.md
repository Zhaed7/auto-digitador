# Auto-Digitador 

Um script simples e eficiente em Python para digitação automática de textos. Desenvolvido com uma interface gráfica amigável, ele é otimizado para teclados no padrão ABNT 2, garantindo o funcionamento perfeito de acentos, pontuações e do caractere "ç".

## Funcionalidades
Suporte ABNT 2: Utiliza a biblioteca `keyboard` para injetar os caracteres diretamente no sistema, evitando bugs com acentos (á, ê, ã) e cedilha (ç).
Interface Gráfica: Janela simples e intuitiva feita com `Tkinter` (fundo azul escuro e letras brancas).
Processamento em Segundo Plano: Utiliza `threading` para realizar a contagem do delay sem congelar a interface (Não trava a tela!).
Delay Estratégico: Pausa de 10 segundos antes de iniciar a digitação, dando tempo suficiente para o usuário focar na janela onde o texto será inserido.

## Plataformas
Disponível para sistemas Windows e Android 

## Instalação: ANDROID
para instalar no android, baixe o `apk`, logo após na sua loja de aplicativos instale o `Zarchive`, aceite suas permissões, vá ate a pasta `Downloads` e clique no arquivo chamado : `auto-Digitador-Mobile.apk`. ele pedira permissão para instalar programas externos, aceite e continue. quando instalar ele aparecera na pagina inicial. clique nele e siga as instruções, abra o aplicativo e clique em cada um dos botões e ative cada uma das permissões, logo após aparecera uma bolinha roxa que ao clicar abre seu `Macro` no espaço disponivel cole o texto e clique em iniciar e selecione o lugar para ele digitar automaticamente. durante o processo `NÃO MECHA NO CELULAR`
