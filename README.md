# automacao_networking
projeto de automação pra buscar na aba network os sites que se conectam com algumas urls específicas...

baixe e instale a versão 3.7+ do python para usar o selenium:
https://www.python.org/downloads/release/python-376/
https://pypi.org/project/selenium/4.9.1/

baixe a versão do ChromeDriver 113.0.5672.63:
https://chromedriver.chromium.org/downloads

baixe a versão 113.0.5672.127 do google chrome (procure na web).

obs: as versões do chrome e do ChromeDriver precisam ser parecidas pra funcionar.

pra ficar mais fácil use as versões que deixei no meu drive pois já estão testadas:
https://drive.google.com/drive/folders/12s7YTuzqPRDpx6n47j3DtwbpJpbQfGnL?usp=sharing

jogue o arquivo do ChromeDriver dentro da pasta raiz do seu projeto.

quando terminar de instalar ele vai abrir o navegador, então feche rapidamente antes que ele atualize.
agora desative as atualizações automáticas:

tecle windows + R
services.msc
serviço do google update > desativado
serviço do google update > desativado

agora abra o cmd (como administrador) e verifique se o pip esta instalado (senão reinicie o pc)

pip --version

agora instale o selenium com o comando:

pip install selenium

instale o anaconda

agora abra o 'anaconda prompt', entre com cd na pasta do seu projeto e digite 'jupyter notebook'

agora é só codar

recomendação:

use a extensão 'Dark Reader' no seu navegador para melhores experiências.