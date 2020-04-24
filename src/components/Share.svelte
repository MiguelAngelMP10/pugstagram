<style>
  .Share {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    background-color: white;
    margin: 0 0 2em 0;
    width: 300px;
    height: 150px;
    position: absolute;
    top: 300px;
    left: 30%;
    z-index: 9;
    padding: 1em;
  }
  .Share-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Share-head h2 {
    font-size: 16px;
  }
  .Share-head i {
    cursor: pointer;
  }
  .Share-content-facebok a,
  .Share-content-whatsapp a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: black;
    font-size: 14px;
    margin: 1em 2em 0 0;
  }
  .Share-content-facebok i,
  .Share-content-whatsapp i {
    margin: 0 0.5em 0 0;
    font-size: 20px;
  }

  .Share-content-facebok i {
    color: #3b5998;
  }
  .Share-content-whatsapp i {
    color: #1bd741;
  }
</style>

<div class="Share">
  <div class="Share-head">
    <h2>Compartir</h2>
    <i class="fas fa-times-circle" on:click />

  </div>
  <div class="Share-content-facebok">
    <a
      href="https://www.facebook.com/sharer/sharer.php?&u=https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co"
      target="_blank">
      <i class="fab fa-facebook-square" />
      Compartir en Facebook!
    </a>
  </div>

  <div class="Share-content-whatsapp">
    <a
      href="https://api.whatsapp.com/send?&text=mira%20este%20hermoso%20pug%20https://pugstagram.co/"
      target="_blank">
      <i class="fab fa-whatsapp-square" />
      Compartir en Whatsapp!
    </a>
  </div>

</div>
