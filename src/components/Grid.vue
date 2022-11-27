<template>
  <main class="container">
    <div class="one flex--right-bottom"><h2>1</h2></div>
    <div class="two"><h2>2</h2></div>
    <div class="three flex--right-bottom"><h2>3</h2></div>
    <div class="four flex--right-top"><h2>1</h2></div>
    <div class="five flex--right-bottom"><h2>1</h2></div>
    <div class="six flex--right-top"><h2>1</h2></div>
    <div class="i0 container">
      <div class="seven flex--right-bottom"><h2>1</h2></div>
      <div class="eight flex--left-bottom"><h2>1</h2></div>
    </div>
    <div class="nine flex--right-top"></div>
    <div class="Ten flex--right-top"></div>
    <div class="i1 container">
      <div class="eleven"></div>
      <div class="twelve flex--right-top"></div>
    </div>
    <div class="thirteen"></div>
    <div class="fourteen"></div>
    <div class="fifteen flex--right-top"></div>
    <div class="sixteen flex--right-bottom"></div>
    <div class="seventeen flex--right-top"></div>
    <div class="i2 container">
      <div class="eigthteen"></div>
      <div class="nineteen flex--left-bottom"></div>
    </div>
    <div class="i3 container">
      <div class="twenty flex--left-bottom"></div>
      <div class="twenty-one flex--right-top"></div>
    </div>
    <div class="tweenty-two flex--right-top"></div>
    <div class="twenty-three flex--right-top"></div>
    <div class="twenty-four flex--right-bottom"></div>
    <div class="Chritmas">It's Christmas baby!</div>
  </main>
</template>

<style scoped>
.container {
  margin-top: 3em;
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

.container>* {
  border: 1px solid white;
  position: relative;
  margin: 5px;
  display: flex;
  padding: 0.8em;
  min-height: 4em;
}

.flex--left-bottom {
  align-items: flex-end;
}

.flex--right-bottom {
  justify-content: flex-end;
  align-items: flex-end;
}

.flex--right-top {
  justify-content: flex-end;
}

h2 {
  font-weight: 700;
  margin: 0;
}

.one { grid-area: one; }

.two { grid-area: two; }

.three { grid-area: three; }

.four { grid-area: four; }

.five { grid-area: five; }

.six { grid-area: six; }

.i0 {  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "seven"
    "eight";
}

.seven { grid-area: seven; }

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
