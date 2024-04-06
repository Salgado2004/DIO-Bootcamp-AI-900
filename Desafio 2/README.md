## Reconhecimento Facial e transformação de imagens em Dados no Azure ML

### O que deve ser feito?
- [x] Crie uma pasta chamada 'inputs' e salve as imagens que você utilizou
- [x] Crie uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens
- [x] Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo.
- [x] Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

### Procedimento

Esse desafio tem o objetivo de implementar o reconhecimento facial e de documentos utilizando o Azure Vision Studio. Para a realização dos testes, foi necessário acessar essa plataforma, explorando suas funcionalidades para criar uma solução eficaz.

1. Antes de acessar a plataforma, é necessário criar um recurso do Azure Ai Services. Isso pode ser feito dentro do [Portal do Azure](https://portal.azure.com/#home).

![alt text](../images/RecursoNoPortal.png)

2. Depois disso, acesse o [Azure Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured) para começar a experimentar os recursos.

![alt text](../images/HomeVisionStudio.png)

3. Agora vamos para os testes com Reconhecimento de imagens

**Reconhecimento de rostos em imagens**

O serviço _Detect faces in images_ do Azure Vision Studio é uma ferramenta de inteligência artificial que identifica e analisa rostos em imagens.

1. Na tela inicial do Vision Studio, acesse a aba **Face**

![alt text](../images/Gallerie1.png)

2. Você pode selecionar tanto as imagens que a Microsoft disponibiliza para testes ou fazer upload de uma imagem sua.

No meu caso, escolhi uma imagem minha

![alt text](../images/ImageSelection.png)

3. O Resultado irá aparecer abaixo, com o rosto detectado marcado na imagem e um pequeno prompt ao lado.

![Resultado do Face detection](../images/FaceDetection.png)

**Descrição de cenários**

O serviço _Add captions to images_ do Azure Vision Studio é uma solução de inteligência artificial que gera legendas descritivas para imagens, facilitando a compreensão do conteúdo visual.

1. Novamente na tela inicial, acesse a aba **Image Analysis**

![alt text](../images/Gallerie2.png)

2. Selecione a opção **Add captions to images**

![alt text](../images/AddCaptions.png)

3. Novamente ele irá permitir que você escolha uma imagem ou faça upload. O Resultado é um prompt em inglês com uma breve descrição do que foi detectado na imagem

![alt text](../images/CaptionAdded.png)

**Optical Character Recognition (OCR)**

O serviço _Extract text from images_ do Azure Vision Studio é uma ferramenta de inteligência artificial que extrai texto de imagens, transformando conteúdo visual em dados manipuláveis.

1. Na tela inicial, acesse a aba **Optical character recognition**

![alt text](../images/Gallerie3.png)

2. Assim como as demais opções, o recurso também irá permitir o upload ou seleção de imagens.

![alt text](./output/resultado%20text.png)

### *Insights* e conclusões

O Azure Vision Studio, com seus serviços de "_Detect faces in images_", "_Add captions to images_" e "_Extract text from images_", oferece um conjunto muito interessante de ferramentas para trabalhar com imagens e inteligência artificial. Esses serviços permitem que os usuários explorem o potencial da IA para analisar e interpretar conteúdo visual de maneira eficaz. Seja identificando rostos, gerando legendas descritivas ou extraindo texto de imagens, o Azure Vision Studio está equipado para lidar com uma variedade de desafios relacionados à imagem, abrindo novas possibilidades para a inovação em diversos campos.