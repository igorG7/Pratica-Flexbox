# Pratica-Flexbox
 
 Eta é uma solução para aperfeiçoamento da prática com Flexbox no css.
 
 ![2021-12-16](https://user-images.githubusercontent.com/78181968/146418186-1c6e4ea6-330c-4780-9959-b07b93e9fd11.png)
 ![2021-12-16 (1)](https://user-images.githubusercontent.com/78181968/146418596-ffc9eb91-7284-4b82-afb5-ee996fc21f40.png)

## Link de acesso: 
- https://igorg7.github.io/Pratica-Flexbox/

## Meu Processo
### Construído com
- HTML5
- CSS
- Flexbox

## O que foi aprendido
Neste projeto aprendi a estruturar bem o código html, manipular e posicionar melhor os elementos com css utilizando a propriedade flexbox e também manipular cores usando variáveis.

Estutura HTML do Flexbox

```html
        <div class="order-container">
            <h1>Order Summary</h1>
            <p>
              You can now listen to millions of songs, audiobooks, and 
              podcasts on any device anywhere you like!               
            </p>

            <div class="pay-options-container">

                <img src="images/icon-music.svg">

                <div class="plan-container">
                    <h4>Annual Plan</h4>
                    <span>$59.99/year</span>
                </div>

                <a href="">change</a>
            </div>

            <div class="buttons-container">
                <input class="pay" type="button" value="Proceed to Payment">
                
                <input class="cancel" type="button" value="Cancel Order">
            </div>
        </div>
    
```
Propriedades CSS
```css

.container .order-container{
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 0 30px;
}

.container .order-container .pay-options-container{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 300px;
    height: 80px;
    margin-top: 30px;
    background-color:var(--azul-muito-claro);
    border-radius: 10px;
}

.order-container .pay-options-container .plan-container{
    margin: 0 60px 0 10px
}

.container .order-container .buttons-container{
    display: flex;
    flex-direction: column;
    margin-top: 30px;
}
```

Resultado do Flexbox

![2021-12-16 (2)](https://user-images.githubusercontent.com/78181968/146424095-e125e4e5-396a-4a8f-9b8d-859c96023434.png)


Variáveis em CSS
```css
  :root {
    --azul-palido: hsl(225, 100%, 94%);
    --azul-claro: hsl(245, 75%, 52%);
    
    --azul-muito-claro: hsl(228, 79%, 96%);
    --azul-dessaturado: hsl(224, 23%, 55%);
    --azul-escuro: hsl(223, 47%, 23%);   
}
```
## Recursos úteis
- Declaração de variáveis com CSS - Essa função facilita muito a manipulação das cores do seu layout, permitindo que a cor de vários elementos seja alterada apenas com a mudança de cor na variável declarada.
