<template>
  <div id="app">

  <!-- Row 1 -->
  <div class="card-row">
 

     <div class="card-2">
     
      <img class="card-image-2"
           src="Waves_18 Logos/sbi.jpg"
           > 

      <p>This is some text</p>
      
     </div>
     
     
     
     
     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Time.png">

      <p>This is some text</p>

     </div>

     <div class="card-4">
     <img class="card-image-4"
           src="Waves_18 Logos/Uniball Logo 5X2feet.jpg"> 

      <p>This is some text</p>

     </div>

  </div>


  <div class="card-row">

    <div class="card-2">
      <img class="card-image-2"
           src="Waves_18 Logos/Smart-Logo.png">
     </div>
    


     <div class="card-2">
      <img class="card-image-2"
           src="Waves_18 Logos/idm.png">
     </div> 

  </div>

  <div class="card-row">

    
     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/1505827601372.jpg"
           >  

      <p>This is some text</p>

     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/ALILA DIWA GOA - BLACK.png"
           > 

      <p>This is some text</p>

     </div>

    
     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Copy of Real.jpg"
           > 
      <p>This is some text</p>

     </div>

  </div>



  <div class="card-row">

    
     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/DHL Logo.png"> 


      <p class="sponsor-name">DHL</p>
      <p class="sponsor-tag">Logistics Partner</p>

     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Doritos Logo.jpg">

      <p class="sponsor-name">Doritos</p>
      <p class="sponsor-tag">Snack Partner</p>
           
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Fashion Is Unlimited Logo - Red.jpg"> 

      <p class="sponsor-name">Unlimited</p>
      <p class="sponsor-tag">Fashion Partner</p>
     </div>

  </div>



  <div class="card-row">

     
     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Fastrack_Black.png"> 
     </div>


     <div class="card-4">
      <img class="card-image-4"
           src="Waves_18 Logos/Frosty_s.jpg"> 
     </div>

     <div class="card-4">
     <img class="card-image-4"
           src="Waves_18 Logos/hoomansofdogs.jpg"> 
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Goa Tourism Logo.png"> 
     </div>


  </div>



  <div class="card-row">


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/GrabOn_highres_darkgrey_secondary.png"> 
     </div>

     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/IMG-20181024-WA0021.jpg"> 
     </div>


  </div>


  <div class="card-row">


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Keventers.png.PNG"> 
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/lensfit.com (4)-1.png"> 
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Manforce Logo.jpg"> 
     </div>


  </div>

     <div class="card-row">

     <div class="card-4">
      <img class="card-image-4"
           src="Waves_18 Logos/The Souled Store.png"> 
     </div>


     <div class="card-4">
      <img class="card-image-4"
           src="Waves_18 Logos/Uniball Logo 5X2feet.jpg"> 
     </div>

     <div class="card-4">
      <img class="card-image-4"
           src="Waves_18 Logos/WFT.png"> 
     </div>
     

     <div class="card-4">
     <img class="card-image-4"
          src="Waves_18 Logos/youthopedia Logo.jpg"
          > 
     </div>


  </div>


  <div class="card-row">


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Paytm_logo.png"> 
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Sundaram Logo.png"> 
     </div>


     <div class="card-3">
      <img class="card-image-3"
           src="Waves_18 Logos/Swing By The Bay Full Logo.png"> 
     </div>


  </div>


	</div>
  </div>

</div>
</template>


<script>
export default {
  
  data() {
    return {
      selectedCard: -1,
      showText: false,
    }
  },
  methods: {  
    isSelected (cardIndex) {
      return this.selectedCard === cardIndex
    },

     displayText() {
          setTimeout(() => {
               this.showText = true;
          }, 300);
          
     },
     hideText() {
          setTimeout(() => {
               this.showText = false;
          }, 300);
     },
  }
};
</script>

<style scoped>

#app {
     background-image: url("https://firebasestorage.googleapis.com/v0/b/waves-assets.appspot.com/o/Backgrounds%2FBackground_Events-min.jpg?alt=media&token=f73ff590-5812-43e8-b6ee-62cc2cd7e442");
     background-size: cover;
     background-repeat: no-repeat;
}


.card-row {
  display: flex;
  justify-content: center;
  align-items: center;  
  min-width: 780px;
  width: 100%;
  height: 350px;
}



.card-image-3 {
  margin-top: 4px;
  margin-bottom: 4px;
  margin: auto;
  width: 80%;
  height: 180px;
  transition: height 0.3s, width 0.3s;
}

.card-3 {
  margin-top: 4px;
  margin-bottom: 4px;
  margin-left: 3%;
  margin-right: 3%;
  padding: auto;
  width: 20%;
  height: 180px;
  transition: height 0.3s, width 0.3s;
}

.card-3:hover {
  height: 230px;
  width: 25%;
}

.card-3:hover > img {
     height: 230px;
     width: 90%;
}

.card-3:hover > p {
     text-align: center;
     margin: 5px;
     display: block;
     
}


.card-image-2 {
  margin-top: 4px;
  margin-bottom: 4px;
  margin-left: 5%;
  margin-right: 5%;

  height: 180px;
  width: 80%;
  transition: height 0.3s, width 0.3s;
}

.card-2 {
  margin-top: 4px;
  margin-bottom: 4px;
  margin-left: 3%;
  margin-right: 3%;
  padding: auto;
  height: 180px;
  width: 28%;
  transition: height 0.3s, width 0.3s;
}

.card-2:hover {
  height: 230px;
  width: 30%;
}

.card-2:hover > img {
     height: 230px;
     width: 90%;
}

.card-2:hover > p {
     text-align: center;
     margin: 5px;
     display: block;
     

}


.card-image-4 {
     margin-top: 4px;
     margin-bottom: 4px;
     margin: auto;

     height: 180px;
     width: 80%;
     transition: height 0.3s, width 0.3s;
}


.card-4 {
     margin-top: 4px;
     margin-bottom: 4px;
     margin-left: 5%;
     margin-right: 5%;

     height: 180px;
     width: 15%;
     transition: height 0.3s, width 0.3s;
}

.card-4:hover {
     height: 230px;
     width: 20%;
}

.card-4:hover > img {
     height: 230px;
     width: 90%;
}

.card-4:hover > p {
     text-align: center;
     margin: 5px;
     display: block;
     
}

p {
     display: none;
}

.sponsor-name {
     font-style: bold;
     font-size: 40px;
}

.sponsor-tag {
     opacity: 0.6;
     font-style: italic;
     font-size: 25px;
}


</style>

