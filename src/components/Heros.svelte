
<div class="heroPictureContainer">
    <div class="grid">
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="time">00:00</div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>
<div class="heropic"></div>

</div>
</div>


<style>
.heroPictureContainer{
    position: fixed;
    top:0;
    width: 100vw;
  padding-bottom: 5px;
    background-color: black;
    display:flex;
    justify-content: center;
    
    
}
.grid{
    display: grid;
    grid-template-rows: 10fr;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-gap:5px;
    align-items: center;
    justify-items: center;
    max-width: 800px;


}
.heropic{
   width: 60px;
    min-width: 30px;
    height: 100%;
    min-height: 60px;
    background-color: white;
}
.time{
    color: white;
}
</style>