<template>
  <div>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay" crossorigin="anonymous">
    <!-- <button @click="top" id="myBtn" title="Go to top" class="myBtn">Back To Top</button> -->
    <i class="fas fa-arrow-circle-up fa-2x myBtn" id="myBtn" @click="top"></i>
    <div class="child-div">
      <div> <!-- Navigation -->
        <p>Click to navigate the page</p>
        <button @click="whyWalk" class="myButton">Why Walk?</button>
        <button @click="theWalk" class="myButton">The Walk</button>
        <button @click="ourLinks" class="myButton">Our Links</button>
      </div>
      <h1>Rotary Club of Stokesley</h1>
      <h1>Teams up with Village Water</h1>
      <img src="@/assets/page1logo.png" alt="logo" height="100" width="500">
      <h2>LET’S PUT OUR BEST FEET FORWARD TO</h2>
      <h2>WALK FOR WATER: THE TEESDALE WAY</h2>
      <h3>SEPTEMBER 8, 2019 – SEPTEMBER 15, 2019 </h3>
      <img src="@/assets/page1.jpg" alt="logo" height="200" width="500">
      <p>The Rotary Club of Stokesley is organising a sponsored walk following the magnificent 100 miles of the Teesdale Way from Dufton in the Cumbrian Pennines to South Gare at the mouth of the Tees taking in the historic and scenic sights of Cumbria, Durham and Tees Valley en route. 
         The walk, which will span eight days, will raise funds for the Rotary-supported charity Village Water, (www.villagewater.org), which provides safe water, sanitation and hygiene for, and fosters independence among, African communities and accounts for every penny! </p>
      <hr>   
    </div>
    <!---WHY WALK----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="whyWalk">
      <h2>Why Walk?</h2>
      <div class="why-walk-p">
        <p>Because apart from enjoying the marvellous scenery and keeping healthy, you’ll be helping to transform the lives of villagers in Zambia’s Western Province where almost half the population still lacks safe water. Village Water’s ‘One Village At A Time’ campaign is hoping to change this.</p>
        <p>Here the scarcity of safe water means eye and infections are prevalent as is diarrhoea, in fact it kills 10 children under five years of age every day in Zambia! People often have to walk miles to a safe water source – so every step you take will remind you of their daily drudge and the reason to keep on walking!</p>
        <p>The funds raised will help supply wells so that villagers can grow their own vegetables and bananas for themselves and sell to raise income. The community will get the education and support they need to take charge of their own hygiene and sanitation, and a protected waterpoint and training to maintain it. So lasting safe water is close to home whenever they need it.</p>
        <img src="@/assets/z1.png" alt="logo" height="400">
        <img src="@/assets/51.png" alt="logo" height="200" width="200">
      </div>
      <hr>
    </div>
    <!--- THE WALK ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="theWalk">
      <h2>The Walk</h2>
      <h4>You can do it!</h4>
      <p>Those who may feel daunted by an eight day trek, can still join in because we’ve subdivided the route into manageable stages of 5-14 miles per day. You can join us for half a day, a full day or stay with us every step of the 100-mile way!</p>
      <p>The Walk For Water will be led by experienced rambler of Stokesley, who will be ably supported by keen hikers from The Rotary Club of Stokesley. The walk is open to all ages though youngsters under 16 years of age must be accompanied by a responsible adult. 
         Whilst the walk leader and Rotary members will be there to guide and support you, your personal health and safety is your own responsibility. </p>
      <h5>Below you'll find the route and stages:</h5>   
      <img src="@/assets/map.png">
      <b-table stacked="md" striped :items="items">
      </b-table>
      <h5>
        Important note: As Giant Hogweed grows in a number of places along the Tees, especially from Day 5 to the first stage of day 7,  you are advised to wear long trousers.
      </h5>  
        <p>
        <img src="@/assets/tees1.jpg" alt="logo" height="400" width="300">
        <img src="@/assets/z2.png" alt="logo" height="250" width="300" >
        </p>
        <hr>
    </div>
    <!--- INFORMATION ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="information">
      <h2>Information</h2>
      <div>
        <h5><b>All funds raised will go to Village Waters one Village at a Time Project in Zambia.</b></h5>
        <h5><b>You will first need to register for the walk.</b></h5>
        <p>The registration fee is adults £10.00 per day up to £30 maximum.</p>
        <p>Young people under the age of 16 years £5.00</p>
        <p class="bacs"><i>Please register and pay by BACS online</i></p>
        <p class="bacs"><i>Sort code: 20-56-74</i></p>
        <p class="bacs"><i>Account number: 10435287</i></p>
        <p class="bacs"><i>Please include your surname and initials as reference eg w4w Blogs J</i></p>
        <p>Your information pack, including Registration and Sponsorship forms, and can be obtained from walk4waterfund@gmail.com</p>
        <p>The start points and times for each day and half day sections are clearly identified in your information pack but please be aware, getting to and from the start and finish points is your own responsibility so forward-planning is key. Marshals will
           greet you at the start points and you’ll find post codes/map reference points on the mileage chart.</p>
        <br>
      </div>
      <p><b>Disabled access: </b>Limited availability for disabled access.</p>
      <p><b>Where you can join us on the walk: </b>The start points for each day and half day sections are within this pack.</p>
      <p><b>Getting to and from the walk is your responsibility: </b>Official places and departure times showing where you can join the walk for a section, a day or several days is clearly marked on the Walk Sections sheet. Please be at your start point 30 minutes prior to your start time. There will be Marshals to greet you at these points. Post codes/map reference points are available on the mileage chart.</p>
      <p><b>BEFORE WE GO - PREPARING FOR THE WALK</b></p>
      <div class="parent">
        <p>There’s lots to think about before we set off so here’s some helpful tips to get you planning</p>
        <ul>
          <li>The terrain is rugged for the first four days, so we advise good walking boots for these sections.</li>
          <li>Don’t forget some drinking water.</li>
          <li>Wear well-fitting comfortable boots or sturdy trail shoes depending on the weather.</li>
          <li>Don’t underestimate the weather, especially extremes of wet and wind.</li>
          <li>Dress in layers: thin thermals are good for base layers; woollen jumpers and/or mid weight polyester fleeces will suffice for mid-layers. <br/> While a waterproof jacket is essential to keep the wind and rain at bay.</li>
          <li>Opt for light, flexible, quick drying trousers or shorts if the weather is hot. Wear a hat if it’s sunny – and a different one if it’s cold!</li>
        </ul>
        <p>You may also like to take</p>
        <ul>
          <li>A basic first aid kit</li>
          <li>Camera</li>
          <li>Sunglasses</li>
          <li>Binoculars</li>
          <li>Mobile Phone</li>
          <li>Walking stick</li>
          <li>Pre-packed refreshments</li>
          <li>Your own map - though Rotary guides will have maps</li>
          <li>And, of course, <b>Dont forget sunscreen!</b></li>
        </ul>
        <h5>WANT TO KNOW MORE OR TALK IT OVER</h5>
        <p>If you want to know anything specific, we’d be happy to help. Please call 01642 714562 or email us on walkforwaterfund@gmail.com</p>
        <p><b>We welcome young people to participate: </b>Young people under the age of 16 must always have a responsible adult to walk with them.</p>
      </div>  
    </div>
    <!-- <div class="our-links">
      <h2>Our links</h2>
      <ul>
        <li><a href="https://www.rotary-ribi.org/clubs/homepage.php?ClubID=166" target="_blank" rel="noopener">Stokesley Rotary Club</a></li>
        <li><a href="https://villagewater.org/" target="_blank" rel="noopener">Village Water Charity</a></li>
      </ul>
    </div> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
       items: [
            {
              date: "Day 1: Sunday 8th September", 
              WhatToExpect: "A long, strenuous climb of 420m over 4miles to High Cup Nick. You'll encounter a number of fords before a rocky path down to to Cauldron Snout. There's some rocky paths on the way to Widdy Bank farm before an easier final section. Excellent views",
              FirstSection: "9.6 miles Strenuous",
              SecondSection: "4.4 miles Strenuous"},
            {
              date: "Day 2: Monday 9th September", 
              WhatToExpect: "A day of scenic views, passing High and Low Force, then through meadowland to Middleton in Teesdale",
              FirstSection: "5.4 miles Moderate",
              SecondSection: "3.6 miles Easy"},
            {
              date: "Day 3: Tuesday 10th September", 
              WhatToExpect: "A day of picture postcard views passing through Romaldkirk to Barnard Castle",
              FirstSection: "6.2 miles Moderate",
              SecondSection: "6.8 miles Moderate"},
            {
              date: "Day 4: Wednesday 11th September", 
              WhatToExpect: "A day of historic sites from Barnard Castle, past Egglestone Abbey, skirting Rokeby Park then to Whorlton Bridge and on to Gainford",
              FirstSection: "4.5 miles Moderate",
              SecondSection: "5.9 miles Moderate"},
            {
              date: "Day 5: Thursday 12th September", 
              WhatToExpect: "The path now starts to meander through farmland which can be muddy. Once we reach Broken Scar the route skirts close to Darlington before going through Croft to Hurworth",
              FirstSection: "8.4 miles Moderate",
              SecondSection: "7.1 miles Moderate"},
            {
              date: "Day 6: Friday 13th September", 
              WhatToExpect: "After following a minor road from Hurworth to Neasham we return to a footpath by the river. Whilst fairly easy walking this path is not well maintained and can be muddy",
              FirstSection: "6.6 miles Moderate",
              SecondSection: "7.6 miles Moderate"},
            {
              date: "Day 7: Saturday 14th September", 
              WhatToExpect: "From Yarm we enter the more residential part of the route but still with good open spaces, and the added interest of the Tees Barrage and the Transporter Bridge",
              FirstSection: "8.1 miles Moderate",
              SecondSection: "5.3 miles Easy"},
            {
              date: "Day 8: Sunday 15th September", 
              WhatToExpect: "The day's first stage mainly follows the disused railway line through Middlesbrough's industrial heartland. We celebrate the end of our walk with a stretch from Redcar to South Gare and the mouth of the Tees",
              FirstSection: "7.4 miles Easy",
              SecondSection: "3.1 miles Easy"},
        ],

    }
  },
  props: {
    msg: String,
  },
  methods: {
    whyWalk(){
      document.getElementById('whyWalk').scrollIntoView();
    },
    theWalk(){
      document.getElementById('theWalk').scrollIntoView();
    },
    top(){
      window.scrollTo(0,0);
    },
    ourLinks(){
      window.scrollTo(0,2750);
    },
    handleScroll () {
      if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
      } else {
        document.getElementById("myBtn").style.display = "none";
      }
    }
  },
  created () {
    window.addEventListener('scroll', this.handleScroll);
  },
  destroyed () {
    window.removeEventListener('scroll', this.handleScroll);
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "https://use.fontawesome.com/releases/v5.7.2/css/all.css";

  h3 {
    margin-top: 0px;
    margin-bottom: 0px;
  }

  .child-div {
    height: 100%;
    width: 100%;
    background-color: white;
  }
  
  .bacs {
    margin-top: 0px;
    margin-bottom: 0px;
  }
  .bacs {
    margin-top: 5px;
    margin-bottom: 5px;
  }

  .parent {
    margin: auto;
    text-align: center;
  }
  .parent > ul {
    display: inline-block;

  }

  /* .welcome {
    height: 100%;
    width: 100%;
    background-color: white;
    
  }
  .why-walk {
    height: 100%;
    width: 100%;
    background-color: white;
  } */
  .why-walk-p {
    width: 80%;
    text-align: center;
    margin: auto;
  }
  /* .the-walk {
    height: 1300px;
    width: 100%;
    background-color: white;
  }
  .our-links {
    height: 800px;
    width: 100%;
    background-color: white;
  } */

  /* table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 80%;
    margin: auto;
    -webkit-overflow-scrolling: touch;
    overflow-x: auto;
    display: block;
  } */

  /* td, th {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 8px;
  } */
/* 
  tr:nth-child(even) {
    background-color: #dddddd;
  } */

  @media only screen and (max-width : 768px) {

    /* table {
      width: 100%;
      max-width: 100% ;
    } */

    img {
    width: auto ;
    max-width: 100% ;
    height: auto ;
    }

    .why-walk-p {
      width: 100% ;
    }

  }

  .myButton {
	-moz-box-shadow:inset 0px 1px 0px 0px #ffffff;
	-webkit-box-shadow:inset 0px 1px 0px 0px #ffffff;
	box-shadow:inset 0px 1px 0px 0px #ffffff;
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ffffff), color-stop(1, #f6f6f6));
	background:-moz-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-webkit-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-o-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-ms-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:linear-gradient(to bottom, #ffffff 5%, #f6f6f6 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#f6f6f6',GradientType=0);
	background-color:#ffffff;
	-moz-border-radius:6px;
	-webkit-border-radius:6px;
	border-radius:6px;
	border:1px solid #dcdcdc;
	display:inline-block;
	cursor:pointer;
	color:#666666;
	font-family:Arial;
	font-size:15px;
	font-weight:bold;
	padding:6px 24px;
	text-decoration:none;
	text-shadow:0px 1px 0px #ffffff;
}
.myButton:hover {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #f6f6f6), color-stop(1, #ffffff));
	background:-moz-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-webkit-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-o-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-ms-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:linear-gradient(to bottom, #f6f6f6 5%, #ffffff 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#f6f6f6', endColorstr='#ffffff',GradientType=0);
	background-color:#f6f6f6;
}
.myButton:active {
	position:relative;
	top:1px;
}

.myBtn {
  display: none; 
  position: fixed; /* Fixed/sticky position */
  bottom: 20px; /* Place the button at the bottom of the page */
  right: 30px; /* Place the button 30px from the right */
  z-index: 99; /* Make sure it does not overlap */
	display:inline-block;
	cursor:pointer;
  color: red;
  opacity: 0.7;
}

</style>
