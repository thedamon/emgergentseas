
<template>
  <div class="index">
    <pre aria-hidden="true">✷  · 　 　      　　.  　　 　　 　    　✵   ✷  　　  ·     　　  　　 　　✵  *  .         　　　　.  　 　 　　     　* 　　　 　　 · ✦         ✦ .· 　　 ·      ✦  ✵  · . 　  　   *      .          * 　 　　　　✷     .    　.         ·  　 .   　·. ✷   ⋆   ✹  . 　　 ✵      +  ˚      * 　　　　　* 　　　　　　  ⋆ 　　 ✧ *  · 　 . 　 ✧ ˚ 　 *   　 +  ˚   · .  .　　*  * 　 ˚  .　　　　　 +  　　　 *  *　　 　 　.  ·✵  . 　   ˚ . 　  ✵　 　　　 　　　　.  ˚ 　  　  　 ✧ ·  　　 ⊹ *  .  　　  　 　  　 · 　　　　　　　 ✦  ⊹ 　  　 　  　　   ✵                         ˚ 　　        ✹   .  　　   ✦ 　 *     　　  ✹  ˚   　   ·.　    　　 *　✷   　　　　　    　　  　　 .  　* ·  　     ✺ 　　　　　　　　.   *  　    　 ˚  　　 ✧    ⋆  *   　　 ✦  ·     　 *   . 　✵   *　     ··  　　 　　 　　 　　　　    　　　　 · . .  .  ✦ 　      ✵ * .  ·　　　　　 . 　　　     · ˚ 　 ·     ✵   　　 .　　 　　 . ·     .  .   　     ˚     　 　 ˚  *  ˚     　　. · * 　 　　　　    　 　 　 ⋆ 　　　　 　　     　   　　　 . 　　　  . 　　    　　  ⋆ 　　　　　 .    ˚ 　 　　　　　　　✷      　　 · 　　　　　     　　  　  　 　 　  　 ⋆     · 　*  .  ✧ ˚ 　 .  ✦ *      * 　· 　  　　 　　　    　 ·  ·  　 　✷        　 ✫ · *  ✹    </pre>
    <div class="container">
      <header>
        <p><strong>EmergentSeas</strong> presents</p>
        <h1>My Planet and Me</h1>
        <h2>In which a sad millennial receives telepathic communications from a distant planet.</h2>

        <p></p>

        <img src="../assets/floor.jpg" alt="Damon lying on a wooden floor looking overwhelmed">
      </header>

      <!-- <section class="links">
        <a href="">Buy tickets</a>
        <a href="">Facebook</a>
      </section> -->

      <section class="info">
        <div class="info-block">
          <p>All performances at The Arts Project, 203 Dundas St, London</p>

          <ul class="showtimes">
            <li>Thurs, June 1 7:00pm</li>
            <li>Sat, June 3 5:00pm</li>
            <li>Sun, June 4 9:00pm</li>
            <li>Tues, June 6 6:30pm</li>
            <li>Fri, June 9 8:00pm</li>
            <li>Sat, June 10 1:00pm</li>
          </ul>

          <p>Tickets available May 1st at <a href="http://londonfringe.ca">the Fringe website</a></p>
        </div>
        <div class="info-block">
          <ul class="credits-primary">
            <li>Produced, written and performed by <span>Damon Muma</span></li>
            <li>Directed by <span>Kristin Bennett, Cara Moyer and Damon Muma</span></li>
            <li>Original Sounds: <span><a href="https://wormwoodmusic.bandcamp.com/">Wormwood</a></span></li>
            <li>Stage Manager: <span>Cara Moyer</span></li>
            <li>Dramaturge: <span>Kristin Bennett</span></li>
            <li>Movement Coach: <span><a href="https://hannahgoldberg.wixsite.com/dance">Hannah Goldberg</a></span></li>
            <li>Poster and logo artwork: <span><a href="http://cargocollective.com/RobinHenry">Robin Henry</a></span></li>
            <li>Trailer: <span>Pam Haasen, Matt Dupont</span></li>
          </ul>

          <h2>Very Special Thanks:</h2>
          <p>
            Emma Bulpin, Laurie Bursch, Valerie Cotic, Jason Dickson, Caleb Heddle, Pam Haasen, Antony Hare, Dorit Osher, Jon Patterson, Kara Riepart, Savannah Sewell, Margot Stothers, Matthew Trueman
          </p>
        </div>
      </section>
    </div>
</div>
</template>

<style>
  html {
    background-color: black;
    color: white;
    font-family: 'Open Sans', sans-serif;
    font-weight: 400;
    line-height: 1.3;
    font-size: 20px;
  }
  h1, h2, h3, h4 {
    font-weight: normal;
  }
  h1 {
    margin-top: 0;
    font-size: 60px;
    font-family: 'Space Mono', monospace;
    font-style: italic;
    text-align: center;
  }
  header p {
    margin: 0;
  }
  body {}
  body::before {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    opacity: .4;
    z-index: -1;
    background: url('../assets/starfield.jpg');
    background-size: cover;
  }
  a {color: white;}
  pre {
    /*animation: flicker .5s infinite;*/
    color: rgba(255,255,255,0.2);
    position: fixed;
    width: 100%;
    top: 0;
    bottom: 0;
    word-break: break-all;
    white-space: pre-wrap;
    left: 0;
    right: 0;
    padding: 0;
    margin: 0;
    letter-spacing: 2px;
    line-height: 2.2;
    font-family: 'Arial';
    font-size: 2.5vmax;
    z-index: -1;
    pointer-events: none;
  }

  .container {
    padding: 3vw 6vw;
    margin: 0vw 12vw ;
    color: white;
    /*background-color: rgba(255,255,255,.2);*/
    background: linear-gradient(328deg, rgba(0,0,0,0.15) 0%, rgba(255,255,255,0.15) 100%);
  }

  .info {
    text-align: center;
    font-size: 24px;
  }

  img {
    width: 100%;
  }

  ul, ol {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  @keyframes flicker {
    0% {color:rgba(255,255,255,.1);}
    9% {color:rgba(255,255,255,0);}
    10% {color:rgba(255,255,255,.5);}
    13% {color:rgba(255,255,255,0);}
    20% {color:rgba(255,255,255,.5);}
    75% {color:rgba(255,255,255,.3);}
  }
</style>
