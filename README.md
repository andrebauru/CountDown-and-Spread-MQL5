# Countdown Candle

## Descrição

O **Countdown Candle** é um indicador personalizado para a plataforma MetaTrader 5 (MT5) que exibe, em tempo real, o tempo restante para o fechamento da vela (candle) atual. Além disso, o indicador mostra o spread atual do ativo no gráfico. Este indicador é ideal para traders que desejam monitorar o tempo de fechamento das velas e o spread diretamente no gráfico, sem precisar alternar entre diferentes janelas ou ferramentas.

## Características

- **Contagem Regressiva**: Mostra o tempo restante, em segundos, para o fechamento da vela atual.
- **Spread**: Exibe o spread atual (diferença entre os preços Bid e Ask) diretamente no gráfico.
- **Personalizável**: Permite ajustar a cor, tamanho da fonte, tipo de fonte e a posição do texto no gráfico.

## Instalação

1. **Baixe o arquivo**: Faça o download do arquivo `Countdown.mq5` e salve-o em uma pasta de sua escolha.
2. **Abra o MetaTrader 5**.
3. **Acesse o MetaEditor**: No MT5, clique em `Arquivo -> Abrir MetaEditor`.
4. **Coloque o arquivo no diretório correto**:
    - Navegue até `Indicadores` na árvore de navegação à esquerda.
    - Arraste e solte o arquivo `Countdown.mq5` na pasta `Indicators`.
5. **Compile o Indicador**: No MetaEditor, clique com o botão direito sobre o arquivo `Countdown.mq5` e selecione `Compilar`. Certifique-se de que não há erros.
6. **Volte ao MetaTrader 5**: Feche o MetaEditor e retorne ao MT5.

## Como Usar

1. **Adicione o Indicador ao Gráfico**:
   - No MT5, vá até o Navegador (`Ctrl+N`), e em `Indicadores`, localize o `Countdown Candle`.
   - Arraste o indicador para o gráfico desejado ou clique duas vezes para adicioná-lo.

2. **Configurações Disponíveis**:
   - **CountdownColor**: Escolha a cor do texto da contagem regressiva e do spread.
   - **FontSize**: Defina o tamanho da fonte para o texto.
   - **CornerPosition**: Selecione o canto do gráfico onde o texto será exibido. Opções:
     - `CORNER_LEFT_UPPER`: Canto superior esquerdo.
     - `CORNER_RIGHT_UPPER`: Canto superior direito.
     - `CORNER_LEFT_LOWER`: Canto inferior esquerdo.
     - `CORNER_RIGHT_LOWER`: Canto inferior direito.
   - **FontType**: Escolha o tipo de fonte para o texto (exemplo: Arial, Times New Roman).
   - **Timeframe**: Defina o timeframe (período) utilizado para calcular o tempo restante da vela atual (por padrão, é o mesmo do gráfico em que o indicador está sendo usado).

3. **Visualização no Gráfico**:
   - Após adicionar o indicador e configurar as opções, o tempo restante e o spread aparecerão no canto do gráfico escolhido.
   - O texto exibido terá o formato `Xs S`, onde `X` é o número de segundos restantes e `S` é o valor do spread.

## Exemplo de Uso

Suponha que você esteja operando em um gráfico de 1 minuto e queira monitorar o tempo de fechamento das velas junto com o spread atual. Adicione o `Countdown Candle` ao gráfico, selecione o canto superior direito (`CORNER_RIGHT_UPPER`), defina a cor para vermelho e o tamanho da fonte para 14. O tempo restante e o spread serão exibidos no canto superior direito do gráfico, permitindo uma visão clara e imediata dessas informações.

## Notas

- Este indicador foi desenvolvido por **AndreTsC** e é fornecido sem garantias. Use-o conforme sua própria necessidade e responsabilidade.
- Para suporte e mais informações, visite [mql.andretsc.com](https://mql.andretsc.com).

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para detalhes.
