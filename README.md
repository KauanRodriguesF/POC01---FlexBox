<div align="center">
    <h1>📐 Prova de Conceito - Flexbox 📐</h1>
    <p>Este projeto demonstra o uso do modelo Flexbox para a construção de layouts flexíveis e responsivos, explicando diversas propriedades e seus usos.</p>
</div>

## 📋 Descrição do Projeto

Esta Prova de Conceito (POC) apresenta os conceitos fundamentais do Flexbox, uma técnica de layout poderosa no CSS. O projeto inclui uma série de exemplos práticos que demonstram como as propriedades Flexbox funcionam e como elas podem ser aplicadas para criar layouts responsivos e dinâmicos.

## 🚀 Funcionalidades

- **Exemplos Práticos de Propriedades Flexbox**: O projeto explora diversas propriedades do Flexbox, como `gap`, `align-content`, `align-items`, `align-self`, `justify-content`, `flex-wrap`, `flex-grow` e `flex-direction`.
- **Layout Responsivo**: Com a ajuda do Flexbox, o layout se adapta bem a diferentes tamanhos de tela.
- **Demonstração Visual**: Cada exemplo é representado por blocos visuais que ilustram o comportamento de cada propriedade Flexbox.

## 🎨 Layout

A interface é organizada em seções para cada propriedade Flexbox, onde um exemplo visual acompanha uma breve explicação do comportamento de cada propriedade. Os exemplos incluem:

- **GAP**: Controla o espaço entre os itens flexíveis.
- **ALIGN CONTENT**: Define o alinhamento das linhas de um container flexível.
- **ALIGN ITEMS**: Determina o alinhamento dos itens flexíveis ao longo do eixo cruzado.
- **ALIGN SELF**: Permite substituir o alinhamento padrão de um item flexível individual.
- **JUSTIFY CONTENT**: Define o alinhamento ao longo do eixo principal.
- **FLEX WRAP**: Controla se os itens flexíveis devem quebrar em várias linhas.
- **FLEX GROW**: Define a capacidade de um item flexível de crescer dentro do container.
- **FLEX DIRECTION**: Define a direção em que os itens flexíveis são dispostos.

## 🛠️ Tecnologias Utilizadas
HTML e CSS

## 📘 Exemplos de Código

### Exemplo 1: Propriedade GAP
No exemplo abaixo, a propriedade `gap` está sendo utilizada para adicionar um espaçamento de `30px` entre os itens flexíveis:

- **HTML**
    ```html
    <section id="gap-poc">
        <h2>GAP</h2>
        <div class="flex-exemplos">
            <div class="gap">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .gap {
        display: flex;
        gap: 30px;
    }
    ```

### Exemplo 2: Propriedade ALIGN CONTENT
Neste exemplo, a propriedade `align-content` é utilizada para alinhar as linhas do contêiner flexível:

- **HTML**
    ```html
    <section id="aligncontent-poc">
        <h2>ALIGN CONTENT</h2>
        <div class="flex-exemplos">
            <div class="align-content">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .align-content {
        display: flex;
        align-content: flex-start; 
        height: 150px; 
    }
    ```

### Exemplo 3: Propriedade ALIGN ITEMS
No exemplo a seguir, a propriedade `align-items` é utilizada para alinhar os itens flexíveis ao longo do eixo cruzado:

- **HTML**
    ```html
    <section id="alignitems-poc">
        <h2>ALIGN ITEMS</h2>
        <div class="flex-exemplos">
            <div class="align-items">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .align-items {
        display: flex;
        align-items: center; 
        height: 100px; 
    }
    ```

### Exemplo 4: Propriedade ALIGN SELF
Neste exemplo, a propriedade `align-self` é utilizada para permitir que o alinhamento padrão seja substituído por itens individuais:

- **HTML**
    ```html
    <section id="alignself-poc">
        <h2>ALIGN SELF</h2>
        <div class="flex-exemplos">
            <div class="align-self">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .align-self {
        display: flex;
        height: 100px; 
    }

    .align-self .quadrado:nth-child(2) {
        align-self: center;
    }
    ```

### Exemplo 5: Propriedade JUSTIFY CONTENT
A propriedade `justify-content` é usada para alinhar os itens ao longo do eixo principal:

- **HTML**
    ```html
    <section id="justifycontent-poc">
        <h2>JUSTIFY CONTENT</h2>
        <div class="flex-exemplos">                
            <div class="justify-content">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .justify-content {
        display: flex;
        justify-content: space-between; 
        width: 200px; 
    }
    ```

### Exemplo 6: Propriedade FLEX WRAP
Neste exemplo, a propriedade `flex-wrap` permite que os itens flexíveis sejam agrupados em várias linhas:

- **HTML**
    ```html
    <section id="flexwrap-poc">
        <h2>FLEX WRAP</h2>
        <div class="flex-exemplos">
            <div class="flex-wrap">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
                <div class="quadrado">4</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .flex-wrap {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }
    ```

### Exemplo 7: Propriedade FLEX GROW
A propriedade `flex-grow` define a capacidade de um item flexível crescer, se necessário:

- **HTML**
    ```html
    <section id="flexgrow-poc">
        <h2>FLEX GROW</h2>
        <div class="flex-exemplos">
            <div class="flex-grow">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .flex-grow {
        display: flex;
        width: 100%;
    }

    .flex-grow .quadrado {
        flex-grow: 2; 
    }
    ```

### Exemplo 8: Propriedade FLEX DIRECTION
Neste exemplo, a propriedade `flex-direction` é utilizada para definir a direção que os itens flexíveis são dispostos:

- **HTML**
    ```html
    <section id="flexdirection-poc">
        <h2>FLEX DIRECTION</h2>
        <div class="flex-exemplos">
            <div class="flex-direction">
                <div class="quadrado">1</div>
                <div class="quadrado">2</div>
                <div class="quadrado">3</div>
            </div>
        </div>
    </section>
    ```

- **CSS**
    ```css
    .flex-direction {
        display: flex;
        flex-direction: column-reverse;
        height: 150px;
    }
    ```


## 💡 Conceitos Abordados
- **Flexbox**: Sistema de layout unidimensional do CSS que organiza os itens de forma eficiente, distribuindo espaço no container e melhorando a capacidade de resposta do design.
- **Propriedades Flexbox**: Cada seção explora uma propriedade específica do Flexbox, com explicações claras e exemplos visuais de sua aplicação.

## 🔍 Como Visualizar o Projeto
- Clone o repositório para a sua máquina local.
- Abra o arquivo `index.html` em seu navegador para visualizar os exemplos de Flexbox.




