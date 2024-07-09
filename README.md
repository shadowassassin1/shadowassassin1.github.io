<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Menu with Description</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap"
      rel="stylesheet"
    />
    <style>
      * {
        margin: 0;
        padding: 0;
        font-family: "Roboto", sans-serif;
      }

      body {
        background-color: #525252;
      }

      .container {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
      }

      nav {
        background-color: #3384f2;
        width: 100%;
        max-width: 550px;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 50px;
        border-radius: 5px;
      }

      nav a {
        text-decoration: none;
        color: #85b9ff;
        font-weight: bold;
        text-transform: uppercase;
        position: relative;
        transition: 0.2s all ease-in-out;
      }

      nav a::before {
        position: absolute;
        content: "";
        left: 0;
        right: 0;
        bottom: -3px;
        height: 2px;
        background-color: #464646;
        transform: scaleX(1.4);
        margin-bottom: -15px;
        opacity: 0;
        visibility: hidden;
        transition: 0.3s 0.2s all ease-in-out;
      }

      nav a:hover {
        transform: scale(1.2);
        color: #fff;
      }

      nav a:hover::before {
        opacity: 1;
        visibility: visible;
        margin-bottom: -2px;
        transition: 0.3s all ease-in-out;
      }

      nav a::after {
        position: absolute;
        content: attr(data-des);
        bottom: 0;
        left: -10px;
        right: -10px;
        font-size: 9px;
        text-align: center;
        margin-bottom: -30px;
        opacity: 0;
        visibility: hidden;
        transition: 0.3s all ease-in-out;
      }

      nav a:hover::after {
        margin-bottom: -18px;
        opacity: 1;
        visibility: visible;
        transition: 0.3s 0.2s all ease-in-out;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <nav>
        <a href="" data-des="Main Page">Home</a>
        <a href="" data-des="What We Do">About</a>
        <a href="" data-des="What We Offer">Service</a>
        <a href="" data-des="Get In Touch">Contact</a>
        <a href="" data-des="Thoughts">Blog</a>
      </nav>
    </div>
  </body>
</html>


