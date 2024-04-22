1° Quando é realizado a instalação do Fallout New Vegas no Linux através da EpicGames, a estrutura do jogo é instalada no disco C: que é "emulada" para a estrutura do Windows, mas isso depende qual a localização aonde você instalou. (verifique isso).

2° Baixar a tradução do jogo no GameVicio, TriboGamer ou Nexus Mods
Link download Nexus Mods: https://www.nexusmods.com/newvegas/mods/72771 (Recomendado)
Link download GameVicio: https://www.gamevicio.com/traducao/traducao-de-fallout-new-vegas-para-portugues-brasil/
Link download Tribo Gamer: https://tribogamer.com/downloads/1087_baixar-traducao-para-fallout-new-vegas-fallout-new-vegas.html

3° Abrir o setup de instalação e localizar aonde o jogo está instalado, selecione o FalloutNV.exe, que geralmente a Epic Games vai criar no diretório: Home/Games/epic-games-store/drive_c/Program Files/Epic Games/FalloutNewVegas/Fallout New Vegas English
(Possa ser que esteja em outro diretório, procure bem antes de instalar)

4° Entrar na pasta "FalloutNewVegas" e localizar o arquivo launcher_settings.cfg

5° Abra o arquivo e procure por "BinaryPath" e deixe dessa forma
BinaryPath=FalloutNVLauncher_gv.exe

6°Ainda no mesmo arquivo procure por "ProcessTrackingNames" e deixe dessa forma ProcessTrackingNames=FalloutNVLauncher_gv.exe

7° Agora abra a pasta "Fallout New Vegas English"

8° Localize e abra o arquivo "Fallout_default.ini"

9° Procure por "STestFile1", ele estará logo no começo do arquivo e deixe da seguinte forma STestFile1=FNV PT-BR.esp.

7° Salve o arquivo e bom jogo.