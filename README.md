
<html>
    <head>
      <title>AmpedUP Supplies</title>
      <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
      <style>
        * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }
        .header{
          display: flex;
          align-items: center;
          justify-content: space-between;
          height: 90px;
          background-color: black;
          color: white;
        }
        .logo{
          width: 200px;
          height: auto;
          margin-left: 20px;
        }
        .navbar{
          margin-right: 20px;
        }
        .btn{
          margin-left: 10px;
          padding: 8px 16px;
          background-color: transparent;
          color: white;
          border: 2px solid white;
          border-radius: 5px;
          cursor: pointer;
          font-weight: bold;
        }
        .btn:hover{
          background-color: aquamarine;
          color: black;
          transition: background-color 0.3s ease-in-out;
        }
        .ad-img{
          background-color: black;
          padding: 20px;
        }
        .ad{
          width: 100%;
        }
        .product{
          
          padding: 10px;
          text-align: center;
          font-size: 40px;
          font-weight: 600;
        }
        .product-container{
          display: flex;
          flex-wrap: wrap;
          justify-content: center; 
          gap: 20px; 
        }
        .product-item{
          flex: 0 0 calc(25% - 40px);
          max-width: calc(25% - 40px); 
        }
        .product-item img{
          max-height: 100%;
          width: auto;
        }
        .product-container{
          display: flex;
          flex-wrap: wrap;
          justify-content: center; 
          gap: 20px; 
        }
        .product-item{
          display: flex;
          flex-direction: column;
          align-items: center;
          flex: 0 0 calc(25% - 40px); 
          max-width: calc(25% - 40px);
          border: 2px solid black; 
          border-radius: 12px;
          padding: 10px; 
        }
        .btn1{
          margin-top: 10px; 
          padding: 10px 18px;
          background-color: black;
          color: white;
          border: 2px solid black;
          border-radius: 5px;
          cursor: pointer;
          font-weight: bold;
        }
          
        .btn1:hover{
          background-color: aquamarine;
          color: black;
          transition: background-color 0.3s ease-in-out;
        }
        .btn2{
          margin-top: 10px;
          padding: 8px 16px;
          background-color: aquamarine;
          color: black;
          border: 2px solid aquamarine;
          border-radius: 5px;
          cursor: pointer;
          font-weight: bold;

        }
        .btn2:hover{
          background-color: transparent;
          color: aquamarine;
          transition: background-color 0.3s ease-in-out;
        }
        .contactform{
          display: flex;
          align-items: center;
          justify-content: space-between;
          height: 600px;
          background-color: black;
          color: white;
        }
        .productname{
          text-align: center;
          font-size: 20px;
        }
      input[type="text"],
      input[type="email"],
      textarea {
        width: 100%;
        padding: 10px;
        font-size: 16px;
        color: #000000;
        border: 1px solid #ccc;
        border-radius: 5px;
        margin-bottom: 10px;
      }
      input[type="submit"]{
        background-color: aquamarine;
        position: relative;
        left: 300px;
        width: 50%;
        color: #000;
        border: 2px solid aquamarine;
        border-radius: 5px;
        padding: 6px 12px;
        font-size: 14px;
        font-weight: bold;
        cursor: pointer;
        transition: background-color 0.3s ease-in-out;
      }
      input[type="submit"]:hover{
        background-color: transparent;
        color: aquamarine;
      }
      .footer{
        background-color: black;
        color: #fff;
        padding: 20px;
        text-align: center;
      }
    .footer-links{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        margin-bottom: 10px;
     }
    .footer-links a{
        color: #fff;
        margin: 0 10px;
        text-decoration: none;
     }
    .footer-links a:hover{
        text-decoration: underline;
     }
    .footer-contact{
        margin-top: 20px;
        font-size: 14px;
     }
     .p1{
      color: aquamarine;
     }
  </style>
    </head>
    <body>
      <header class="header">
        <img class="logo" src="image.png" alt="Logo">
        <nav class="navbar">
            <a href="#footer1">
          <button class="btn">About</button></a>
          <a href="#contactform">
          <button class="btn">Contact</button></a>
        </nav>
      </header> 
      <div class="ad-img">
        <img class="ad" src="adv.jpg" alt="ad">
      </div>  
      <br>
      <br><br><br>
      <hr>
      <br>
      <section>
        <div id="product" class="product">Our Product</div>
        <br><br>
        <div class="product-container">
          <div class="product-item">
            <img src="https://lumprodsta.blob.core.windows.net/prodcontainer/Images/e3b96cd5-a7be-49d2-8525-766a2522ef28_Home-UPS-%26-Inverter.png" alt="product1">
            <br>
            <h1 class="productname">UPS & INVERTER</h1>
            <br>
            <a href="product1.html">
            <button class="btn1">Buy Now</button></a>
          </div>
          <div class="product-item">
            <img src="https://lumprodsta.blob.core.windows.net/prodcontainer/Images/80cf4351-199b-49ac-bbf2-64500ec0f62e_batteries-1.png" alt="product2">
            <br>
            <h1 class="productname">BATTERIES</h1>
            <br>
            <a href="product2.html">
            <button class="btn1">Buy Now</button></a>
          </div>
          <div class="product-item">
            <img src="https://lumprodsta.blob.core.windows.net/prodcontainer/Images/49f91aa3-b7e5-4394-9eb5-07090bed0105_Inverter-Battery-Combo.png" alt="product3">
            <br>
            <h1 class="productname">INVERTER & BATTERY COMBO</h1>
            <br>
            <a href="product3.html">
            <button class="btn1">Buy Now</button></a>
          </div>
          <div class="product-item">
            <img src="https://lumprodsta.blob.core.windows.net/prodcontainer/Images/833876f8-65c8-4415-a54f-8c8eb53f0e7e_Accessories.png" alt="product4">
            <br>
            <h1 class="productname">ACCESSORIES</h1>
            <br>
            <a href="product4.html">
            <button class="btn1">Buy Now</button></a>
          </div>
        </div>
        <br><br>
      </section>
      <br><br><br>
      <section>
      <div id="contactform" class="contactform bg-black text-white py-20 px-4 md:flex md:items-center">
        <img class="logo w-48 h-auto md:mr-20 md:mb-0 mb-10" src="image.png" alt="Logo">
        <div class="md:flex-grow">
            <h2 class="text-3xl font-bold mb-8">Contact Us</h2>
            <form action="process_form.php" method="POST" class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <input type="submit" value="Submit" class="btn2 col-span-2">
            </form>
        </div>
      </section>
        <footer class="footer">
          <div class="footer-links">
              <a href="#">Home</a>
              <a href="#about">About</a>
              <a href="#product">Products</a>
              <a href="#contactform">Contact</a>
          </div>
          <div id="footer1" class="footer-contact">
              <p>Contact us at: +91-92111132444</p>
              <p> S-11, Gali No 3, Okhla Phase III, New Delhi, India 
              </p>
          </div>
          <p class="p1">&copy; 2023 AmpedUp Supplies. All rights reserved.</p>
      </footer>
  </div>
    </body>    
</html>
