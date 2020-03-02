#landing-page {
    background-image: url("../images/bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.navigation {
    background: rgba(59, 6, 33, 0.815);
    color: #fff;
    font-weight: bolder;
}
.navbar-nav .nav-item .nav-link {
    color: rgb(50, 182, 153);
}

#pizzasize, #pizzatopping, #pizzacrust, #pizzanumbers, #pizzadelivery, #pizzacheckout {
    background: rgba(255, 255, 255, 0.76);
    padding: 25px;
    border-radius: 12px 5px;
    
}

#pizzaform {
    transition: .2s;
}
#pizzaform:hover {
    margin: -1% 0 0 0;
    transition: all .4s;
}

.setcont.defaultcont {
    display: flex;
}
.setcont {
    display: none;
}
$(document).ready(function () {
    $("input[type=button][value=Proceed]").click(function () {
        $("form#pizzaform").find("div.setcont.defaultcont").next().addClass("defaultcont");
        $("form#pizzaform").find("div.setcont.defaultcont").prev().removeClass("defaultcont");
    });
    $("input[type=button][value=Previous]").click(function () {
        $("form#pizzaform").find("div.setcont.defaultcont").prev().addClass("defaultcont");
        $("form#pizzaform").find("div.setcont.defaultcont").next().removeClass("defaultcont");
    });
    // pizza sizes
    let small = { name: "small", price: 300 };
    let medium = { name: "small", price: 450 };
    let large = { name: "small", price: 700 };

    //piza toppings
    let pepperoni = { name: "Pepperon…
# pizza
pizza website


## Author

[cephas]()

## Description
Pizzaland Amazing. https://cephaske254.github.io/pizza

## Installation / Setup instruction
* Open Terminal {Ctrl+Alt+T}
* cd pizza

* code . or atom . depending on the text editor of your choise.

## Technologies Used

* HTML5
* CSS
* Bootstrap
* jQuery

## BDD
| Behaviour      | Input        | Output       |
| :------------- | :----------: | -----------: |
|  Enter your name  |  cephas |     |
| Enter your Email Address  |  fleeksolutions@gmail.com|   |
| Enter your message or comment   |  I would love to work with you     |     |

## License
* MIT License:
* Copyright (c) 2019 *cephas*