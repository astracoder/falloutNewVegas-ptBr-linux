# Tradução Fallout New Vegas no Linux e Epic Games

## Guia criado por
[@astracoder](https://www.github.com/astracoder)

Esta é uma tradução completa do jogo Fallout: New Vegas para o Português. Explore o deserto pós-apocalíptico do sudoeste dos Estados Unidos em sua língua nativa. Contribua, relate problemas e desfrute desta experiência em português no universo de Fallout!

<img src="/falloutnv.jpg">

#

- 1° Quando é realizada a instalação do Fallout New Vegas no Linux através da EpicGames, a estrutura do jogo é instalada no disco C:, que é "emulada" para a estrutura do Windows, mas isso depende da localização onde você instalou (verifique isso).

- 2° Baixar a tradução do jogo no GameVicio, TriboGamer ou Nexus Mods:

    Link para download no Nexus Mods: [Nexus Mods](https://www.nexusmods.com/newvegas/mods/72771) (Recomendado) 

    Link para download no GameVicio: [GameVicio](https://www.gamevicio.com/traducao/traducao-de-fallout-new-vegas-para-portugues-brasil/)

    Link para download na Tribo Gamer: [Tribo Gamer](https://tribogamer.com/d ownloads/1087_baixar-traducao-para-fallout-new-vegas-fallout-new-vegas.html)

- 3° Abrir o setup de instalação e localizar onde o jogo está instalado, selecione o FalloutNV.exe, que geralmente a Epic Games vai criar no diretório: Home/Games/epic-games-store/drive_c/Program Files/Epic Games/FalloutNewVegas/Fallout New Vegas English (Pode ser que esteja em outro diretório, procure bem antes de instalar)


- 4° Entrar na pasta "FalloutNewVegas" e localizar o arquivo launcher_settings.cfg

- 5° Abra o arquivo e procure por "BinaryPath" e deixe dessa forma BinaryPath=FalloutNVLauncher_gv.exe

- 6° Ainda no mesmo arquivo procure por "ProcessTrackingNames" e deixe dessa forma ProcessTrackingNames=FalloutNVLauncher_gv.exe

<pre><code>
BinaryPath=FalloutNVLauncher_gv.exe
LocalePath=Fallout New Vegas
Languages=English, French, German, Italian, Spanish
ParseCommandLineArguments=true
Pass_Through_Arguments=true
ProcessTrackingNames=FalloutNVLauncher_gv.exe

BethNet_Enabled=True
BethNet_Product_Name=Fallout New Vegas
BethNet_Product_Version=1.0.0.0
BethNet_Id=1oyzzFC247Mr5weLqwFm6s20rVEKHSzDv0EMkNTr1CLUhtsFKGb5WoIKsg4xtacHwuAvSRFQ6wRWcokEkel9FXaCSwnAIZBiYBOukpLpMfAxxMpdr2WKQe1QCz6uEkC/HC2NklK/9cLRuN6qTIh3sWtvoL3+KLxBt4fREh1t1VKAWgTyu3EhFbp99G3HUxHMPA==
BethNet_Platform=EpicGamesLauncher
BethNet_PUID_CFG_Path=%LOCALAPPDATA%\BethesdaNet\EGS
BethNet_PUID_CFG_File=FalloutNV.cfg
</code></pre>

- 7° Agora abra a pasta "Fallout New Vegas English"

- 8° Localize e abra o arquivo "Fallout_default.ini", nele possui alguns parâmetros padrão de inicialização e vamos fazer uma alteração no arquivo de texto do jogo.

- 9° Procure por "STestFile1", ele estará logo no começo do arquivo e deixe da seguinte forma STestFile1=FNV PT-BR.esp.

<pre><code>
[General]
SStartingCell=
SCharGenQuest=00102037
SStartingCellY=
SStartingCellX=
SStartingWorld=
STestFile10=
STestFile9=
STestFile8=
STestFile7=
STestFile6=
STestFile5=
STestFile4=
STestFile3=
STestFile2=
STestFile1=FNV PT-BR.esp
</code></pre>

- 10° Arquivos da tradução - Deixe todas as opções selecionadas, principalmente a FalloutNV_lang.esp e FNV PT-BR.esp
- 
CaravanPack.esm
ClassicPack.esm
DeadMoney.esm
GunRunnersArsenal.esm
HonestHearts.esm
LonesomeRoad.esm
MercenaryPack.esm
OldWorldBlues.esm
TribalPack.esm
YUP - Base Game + All DLC.esm
YUP - NPC Fixes (Base Game + All DLC).esp

<img src="/loadFiles.png">

- 11° Salve o arquivo e bom jogo.

Todo esse guia foi feito para você, assim como eu, teve imensa dificuldade de conseguir colocar a tradução no Fallout, por ser uma estrutura Linux e o setup de instalação não conseguiu fazer de forma automática a manipulação desses parâmetros. 

