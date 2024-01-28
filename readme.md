# TASK CALLBACK HELL.....

#### create a html file `index.html`

#### codes

```
<!DOCTYPE html>
<html lang="en">
 <head>
   <meta charset="UTF-8" />
   <meta http-equiv="X-UA-Compatible" content="IE=edge" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <title>Callback Hell</title>
   <link
     rel="stylesheet"
     href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css"
     integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn"
     crossorigin="anonymous"
   />
 </head>
 <body>
   <div class="container jumbotron" style="margin: auto">
     <p style="text-align: center">
       <span
         class="badge rounded-pill bg-danger"
         id="display"
         style="text-align: center; font-size: x-large"
       ></span>
     </p>
   </div>
   <script src="./js/script.js"></script>
   <script
     src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
     integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
     crossorigin="anonymous"
   ></script>
   <script
     src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"
     integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF"
     crossorigin="anonymous"
   ></script>
 </body>
</html>

```

#### create a js file `script.js`.

##### codes

```
"use strict";
let timer = 10;
let time = document.getElementById("display");
time.style.margin = "auto";
time.style.textAlign = "center";
time.style.border = "black 1px dotted";
time.style.maxWidth = "200px";
setTimeout(() => {
  time.innerHTML = timer--;
  setTimeout(() => {
    time.className = "badge rounded-pill bg-light text-dark";
    time.innerHTML = timer--;
    setTimeout(() => {
      time.className = "badge rounded-pill bg-danger";
      time.innerHTML = timer--;
      setTimeout(() => {
        time.className = "badge rounded-pill bg-light text-dark";
        time.innerHTML = timer--;
        setTimeout(() => {
          time.className = "badge rounded-pill bg-danger";
          time.innerHTML = timer--;
          setTimeout(() => {
            time.className = "badge rounded-pill bg-light text-dark";
            time.innerHTML = timer--;
            setTimeout(() => {
              time.className = "badge rounded-pill bg-danger";
              time.innerHTML = timer--;
              setTimeout(() => {
                time.className = "badge rounded-pill bg-light text-dark";
                time.innerHTML = timer--;
                setTimeout(() => {
                  time.className = "badge rounded-pill bg-danger";
                  time.innerHTML = timer--;
                  setTimeout(() => {
                    time.className = "badge rounded-pill bg-light text-dark";
                    time.innerHTML = timer--;
                    setTimeout(() => {
                      time.style.fontSize = "36px";
                      time.style.maxWidth = "500px";
                      time.className = "badge rounded-pill bg-danger";
                      time.innerHTML = "Happy Independence Day!";
                    }, 1000);
                  }, 1000);
                }, 1000);
              }, 1000);
            }, 1000);
          }, 1000);
        }, 1000);
      }, 1000);
    }, 1000);
  }, 1000);
}, 1000);

```

### conclution.

#### It count down 10 to 1 the shows the message `happy independance day`
