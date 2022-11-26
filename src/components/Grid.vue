<template>
  <main class="container">
    <div class="one">1</div>
    <div class="two">2</div>
    <div class="three">3</div>
    <div class="four">4</div>
    <div class="five">5</div>
    <div class="six">6</div>
    <div class="i2">
      <div class="sevne"></div>
      <div class="eight"></div>
    </div>
    <div class="nine"></div>
    <div class="Ten"></div>
    <div class="i1">
      <div class="eleven"></div>
      <div class="twelve"></div>
    </div>
    <div class="thirteen"></div>
    <div class="fourteen"></div>
    <div class="fifteen"></div>
    <div class="sixteen"></div>
    <div class="seventeen"></div>
    <div class="i2">
      <div class="eigthteen"></div>
      <div class="nineteen"></div>
    </div>
    <div class="i3">
      <div class="twenty"></div>
      <div class="twenty-one"></div>
    </div>
    <div class="tweenty-two"></div>
    <div class="twenty-three"></div>
    <div class="twenty-four"></div>
    <div class="Chritmas">It's Christmas baby!</div>
  </main>
</template>

<style scoped>
.container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
  grid-template-rows: 0.6fr 0.7fr 0.8fr 1.3fr 1.6fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "one two three three four"
    "five six . nine nine"
    "five Ten Ten . thirteen"
    "fourteen sixteen seventeen seventeen ."
    "fifteen sixteen . tweenty-two tweenty-two"
    "twenty-three twenty-three twenty-four Chritmas Chritmas";
}

.container * {
  border: 1px solid red;
  position: relative;
  margin: 5px;
}

.one { grid-area: one; }

.two { grid-area: two; }

.three { grid-area: three; }

.four { grid-area: four; }

.five { grid-area: five; }

.six { grid-area: six; }

.i2 {  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "sevne"
    "eight";
}

.sevne { grid-area: sevne; }

.eight { grid-area: eight; }

.nine { grid-area: nine; }

.Ten { grid-area: Ten; }

.i1 {  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "eleven"
    "twelve";
}

.eleven { grid-area: eleven; }

.twelve { grid-area: twelve; }

.thirteen { grid-area: thirteen; }

.fourteen { grid-area: fourteen; }

.fifteen { grid-area: fifteen; }

.sixteen { grid-area: sixteen; }

.seventeen { grid-area: seventeen; }

.i2 {  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "eigthteen"
    "nineteen";
}

.eigthteen { grid-area: eigthteen; }

.nineteen { grid-area: nineteen; }

.i3 {  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "twenty"
    "twenty-one";
}

.twenty { grid-area: twenty; }

.twenty-one { grid-area: twenty-one; }

.tweenty-two { grid-area: tweenty-two; }

.twenty-three { grid-area: twenty-three; }

.twenty-four { grid-area: twenty-four; }

.Chritmas { grid-area: Chritmas; }

</style>
