## Análise de Sentimentos com Language Studio no Azure AI

### O que deve ser feito?

- [ ] Crie uma pasta chamada 'inputs' e crie um documento de texto com algumas sentenças
- [ ] Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo após a IA analisar suas sentenças
- [ ] Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

### Procedimento

1. Inicialmente, vamos criar um grupo de recursos no Portal do Azure para guardar nossos recursos

![alt text](../images/grupoDesafio3.png)

**Speech to text**

1. Diretamente dentro do [Speech Studio](https://speech.microsoft.com/portal) da Microsoft, vamos criar um novo recurso dentro do grupo de recursos que criamos

Você pode fazer isso indo nas configurações e selecionando **Criar novo recurso**

![alt text](../images/recursoSpeech.png)

2. Com o recurso criado, volte para a página inicial e desça até a sessão **Conversão de Fala em texto** e selecione a primeira opção

![alt text](../images/ConversaoFalaTexto.png)

3. Selecione o idioma do áudio para converter em texto e faça o upload. Você verá que aos poucos o áudio será transcrito em texto.

![alt text](./outputs/resultado%20speech.png)

### *Insights* e conclusões