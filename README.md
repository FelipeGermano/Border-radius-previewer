# Editor de Border Radius

Uma aplicação web simples que permite aos usuários editar a propriedade `border-radius` de uma caixa e copiar o CSS resultante para a área de transferência. Os usuários podem modificar todos os 8 valores possíveis da propriedade `border-radius` para criar formas complexas.

## Funcionalidades

- Pré-visualização em tempo real das alterações no `border-radius`.
- Edite os quatro cantos (`top-left`, `top-right`, `bottom-left`, `bottom-right`).
- Suporte à edição dos raios horizontal e vertical.
- Copie o CSS gerado para a área de transferência com um único clique.
- Interface responsiva e fácil de usar.

## Como Usar

1. Abra a aplicação em um navegador web.
2. Use os campos de entrada para definir os valores desejados do `border-radius` para cada canto.
3. Visualize as alterações na caixa exibida ao vivo.
4. Clique no botão "Copiar CSS" para copiar o CSS gerado para a área de transferência.

## Instalação

1. Clone o repositório ou faça o download dos arquivos do projeto.
   ```bash
   git clone https://github.com/FelipeGermano/Border-radius-previewer.git
   ```
2. Navegue até o diretório do projeto.
   ```bash
   cd editor-border-radius
   ```
3. Abra o arquivo `index.html` em qualquer navegador web moderno.

## Arquivos

- `index.html`: Estrutura principal do HTML da aplicação.
- `style.css`: Folha de estilos para o design da aplicação.
- `script.js`: JavaScript para lidar com as interações do usuário e atualizações (embutido no HTML neste caso).

## Exemplo de Saída CSS

Ao modificar os valores de `border-radius`, você obterá um resultado semelhante a:

```css
border-radius: 10px 20px 30px 40px / 15px 25px 35px 45px;
```
