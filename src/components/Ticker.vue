<template>
  <div>
    <div class="hwrap">
      <div class="hmove">
        <div class="hitem">
          We are living in an inverted reality -- the clownworld.
        </div>
        <div class="hitem">
          Nothing makes sense in the clownworld -- it's been designed that way.
        </div>
        <div class="hitem">
          The COVID-1984 scamdemic is being utilized to destroy our freedoms
          -- and is being run by parasitic tyrants!
        </div>
        <div class="hitem">
          We are being lied to by design -- this is a new asymmetrical information style of warfare. 
        </div>
        <div class="hitem">
          Yesterday's conspiracy theory is today's conspiracy fact -- this is
          undeniable.
        </div>
        <div class="hitem">
          "If the situation was hopeless, their propaganda would be
          unnecessary." -- Unknown Author
        </div>
        <div class="hitem">
          Our compliance has gotten us to this point -- STOP COMPLYING!
        </div>
        <div class="hitem">
          The book of history is being written -- what will is say about YOU?
        </div>
        <div class="hitem">
          Will you concede the freedoms prior generations died for -- without a
          fight?
        </div>
        <div class="hitem">
        Be loud.  Get Angry.  Become ungovernable. -- NEVER COMPLY!
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hwrap {
  overflow: hidden; /* HIDE SCROLL BAR */
  background: rgba(165, 165, 165, 0.493);
  border-radius: 10px;
  border: 1px solid black;
  width: 100%;
  display: grid;
  grid-template-columns: 0.5fr 3fr;
}
.hmove {
  display: flex;
}
.hitem {
  flex-shrink: 0;
  width: 100%;
  box-sizing: border-box;
  padding: 10px;
  text-align: center;
  font-family: "Permanent Marker", cursive;
  font-size: 20px;
}
@keyframes tickerh {
  0% {
    transform: translate3d(100%, 0, 0);
  }
  100% {
    transform: translate3d(-1000%, 0, 0);
  }
}
.hmove {
  animation: tickerh linear 110s infinite;
}
.hmove:hover {
  animation-play-state: paused;
}
</style>