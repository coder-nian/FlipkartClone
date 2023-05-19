**index.html**
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>eCommerce Homepage</title>
  <link rel="stylesheet" href="css/style.css" />
  <link rel="stylesheet" href="css/utility.css" />
  <link rel="stylesheet" href="css/responsive.css" />
  

</head>

<body>

  <header>
    <nav>
      <div class="logo">
        <img src="https://static-assets-web.flixcart.com/fk-p-linchpin-web/fk-cp-zion/img/flipkart-plus_8d85f4.png" />
      </div>
      <ul>
        <li> <a href="home.html">Home</a> </li>
        <li> <a href="about.html">About</a> </li>
        <li> <a href="Contact.html">Contact Us</a> </li>
      </ul>
      <div class="search">
        <input type="search" placeholder="Search">
        <button class="button">Search</button>
      </div>
    </nav>
  </header>


  <main>
    <div class="container">

      <div class="slider">
        <img src="" />
      </div>

      <div class="card">
        <h2 class="my-2">
          Check out Our Products!
        </h2>

        <div class="cards">

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>

          <div class="card-item">
            <img src="" />

            <div class="lines">
              <p class="text-center my-1">
                Our Product
              </p>
              <p class="text-center my-1">
                Offer
              </p>
              <p class="text-center my-1">
                Price
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

  </main>


  <footer class="flex-all-center">
    <p> Copyright &copy; eCommerce.com </p>
  </footer>

</body>

</html>
```

**style.css**
```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

:root{
  --bg-color: #2874f0;
}

*{
  margin: 0;
  padding: 0;
}

header{
  background-color: var(--bg-color);
  font-family: 'Poppins', sans-serif;
}

nav{
  display: flex;
}

.logo{
  display: flex;
  align-items: center;
}

.logo img{
  width: 88px;
padding: 0 25px;

}

nav ul{
  display: flex;
  justify-content: flex-start;
  align-items: center;
  height: 58px;
}

nav ul li{
  list-style: none;
  padding: 0 23px;
}

nav ul li a{
  color: white;
  text-decoration: none;
}

nav ul li a:hover{
  color: #0073ff;
  font-weight: bold;
}

.search{
  display: flex;
  align-items: center;
}

.search input{
  height: 27px;
  width: 30vw;
  border-radius: 5px;
  margin: 0 16px 0 56px;
  padding: 0 12px;
  font-family: 'Poppins', sans-serif;
}

.search button{
  font-family: 'Poppins', sans-serif;
  font-weight: 900;
}

.slider{
  width: 80vw;
  margin: 12px auto;
  overflow: hidden;
}

.card{
  max-width: 91vw;
  margin: 37px auto;
  font-family: 'Poppins', sans-serif;
}

.cards{
  display: flex;
  overflow: hidden;
}

.card-item{
  display: inline-flex;
  justify-content: center;
  flex-direction: column;
  margin: 0 15px;
}

.container{
  min-height: calc(100vh - 58px - 12vh);  
}

footer{
  height: 12vh;
  background-color: var(--bg-color);
  color: white ;
  font-family: 'Poppins', sans-serif;
}
```

**utility.css**
```css
.flex-all-center{
  display: flex;
  justify-content: center;
  align-items: center;
}

.button{
  padding: 5px 10px;
  background-color: var(--bg-color);
  color: white;
  border: 2px solid white;
  border-radius: 7px;
  cursor: pointer;
}

.my-1{
  margin: 5px 0;
}

.my-2{
  margin: 26px 0;
}

.text-center{
text-align: center;
}
```

**responsive.css**
```css
@media screen and (max-width: 1000px){

  .slider{
    height: 23vh;
  }
  
  nav{
    display: flex;
    flex-direction: column;     
  }

  .logo{
    justify-content: center;
    margin: 12px 0;
  }

  nav ul{
    justify-content: center;
    height: 34px;
  }
  
.search{
  justify-content: center; 
}

.search input{
  margin: 12px 16px
}

  .card-item img{
    width: 140px
  }
  
}
```
