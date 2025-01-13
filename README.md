# Vida na tela
##### Um conjunto de dois códigos, na lingaugem Macro KeyBind, que coloca a vida do player na tela e altera as cores do texto de acordo com o valor exposto
###### A onChat foi feita para funcionar no servidor CraftLandia, mas pode ser alterada para qualquer um. Ela só serve para reiniciar o código ao relogar.

- **Instalação da macro**
	- Abra o Minecraft;
	- Abra a tela de teclado do mod Macro KeyBind (ESC -> Opções -> Controles -> Macro Settings);
	- Abra uma das teclas cinzas;
	- Digite o seguinte código:
		 `$$<vida.txt>`
	- Clique em `Edit File`;
	- Digite `vida` e clique em `Create`;
	- Cole o conteúdo do arquivo `vida.txt` e clique em Save.
   
- **Instalação da onChat**
	- Abra o Minecraft;
	- Abra a tela de teclado do mod Macro KeyBind (ESC -> Opções -> Controles -> Macro Settings);
	- Clique na seta para a direita, amarela, no canto superior esquerdo da tela;
  - Clique em `onChat`;
  - Digite o seguinte código, no final do que já está nessa tela:
		 `$$<onchat_vida.txt>`
  - Clique em `Edit File`;
  - Digite `onchat_vida` e clique em `Create`;
  - Cole o conteúdo do arquivo `onchat_vida.txt` e clique em Save.
    
- **Criação da label**
	- Abra o Minecraft;
	- Abra a tela de teclado do mod Macro KeyBind (ESC -> Opções -> Controles -> Macro Settings);
	- No canto inferior direito, clique em `GUI Editor`;
  - Dê um clique duplo em `ingame`, no canto esquerdo da tela;
  - Clique no botão `Button Panel Commands`, no canto inferior esquerdo da tela, e clique em `Add Label`;
  - Escolha uma posição para a label, na tela, e dê um clique com o botão esquerdo do mouse;
  - Altere o campo `Control Name` para `vida`;
  - \[OPCIONAL] Clique na caixa à direita de `Background colour` e arraste a barra de `Opacity` para zero;
  - \[OPCIONAL] Altere o `Text Align` para `Middle Centre`;
  - Clique em `OK` para salvar.
    
- **Uso**
	- Inicie a macro pressionando a tecla escolhida ao instalar o código

### Referências:
- [Macro KeyBind Mod](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1275039-macro-keybind-mod), o mod utilizado para executar o script ~ by [Mumfrey](https://github.com/mumfrey)
- [LiteLoader](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1290155-liteloader), o carregador de mods necessário para usar o mod ~ by [Mumfrey](https://github.com/mumfrey)
- [Documentação extraoficial](https://beta.mkb.gorlem.ml/docs/actions/), contendo informações acerca da linguagem que o mod cria ~ by [Gorlem](https://github.com/Gorlem/)  
- [MKB Syntax Highlighting](https://github.com/KeeMeng/MKB-Syntax-Highlighting), um plugin para o software Sublime Text que ajuda a programar em MKB ~ by [KeeMeng (TKM)](https://github.com/KeeMeng) 
