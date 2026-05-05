<style>
  body {
    background-color: #121212 !important;
    background-image: none !important; /* Removes Dinky's default texture */
    color: #d0d0d0 !important;
  }

  /* Target the theme's specific containers */
  header, #content-wrapper, .wrapper {
    background-color: #121212 !important;
    background: #121212 !important;
    border: none !important;
    box-shadow: none !important;
  }

  /* Keep text readable */
  h1, h2, h3, h4, strong, header h1 a {
    color: #ffffff !important;
  }
</style>

<div style="
    width: 240px; 
    height: 179px; 
    overflow: hidden; 
    position: relative; 
    border: 0px solid red;">
  
  <iframe 
    src="https://pulsoid.net/widget/view/1253cc20-0831-45ec-bfa4-bce269cfd9a5" 
    style="
        position: absolute;
        top: -73px;   /* Pulls the widget UP to crop the top */
        left: -55px;  /* Pulls the widget LEFT to crop the left side */
        width: 450px; /* Makes the internal frame larger for scaling */
        height: 450px;
        background: transparent;
        transform: scale(0.96); /* Adjust scale to fit the new crop box */
        transform-origin: left top;"
    frameborder="0" 
    scrolling="no">
  </iframe>
</div>

<div style="margin-top: 10px;">
  Hello World<br>
  Goodbye World
</div>
