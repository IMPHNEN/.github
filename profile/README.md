<style>
  * {
    transition: all 0.5s ease;
  }

  .imphnen.title {
    color: rgba(106, 191, 242, 1);
    font-size: 35px;
    text-align: center;
    align-content: center;
    margin: 5px auto;
    border-radius: 20px;
    max-width: 30%
  }

  .imphnen.title:hover {
    color: rgb(255, 255, 255);
    background-color: rgb(90, 183, 237, 1);
  }

  @keyframes imphnenen {
    from {
        content: "|";
    }
    to {
        content: ""
    }
  }

  .imphnen.elmanug {
    font-size: 20px; 
    text-align: center
  }
  .imphnen.elmanug::after {
    color: rgba(255, 255, 255);
    content: "";
    animation: imphnenen 1s linear infinite;
  }
  
</style>
<body>
  <div>
    <b>
      <p style="font-size: 20px; text-align: center; margin: auto">Welcome to Official Organization </p>
      <p class="imphnen title">IMPHNEN</p>
    </b>
    <a href="https://github.com/IMPHNEN"><img src="./banner.png" style="border-radius: 20px"></img></a>
    <p id="imphnen_anime" class="imphnen elmanug">Ingin Menjadi Programmer Handal Namun Enggan Ngoding</p>
    <hr>
  </div>
  
</body>