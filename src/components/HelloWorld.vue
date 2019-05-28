<template>
  <div>
    <div class="welcome">
      <button @click="top" id="myBtn" title="Go to top" class="myBtn">Back To Top</button>
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
    <!-- <div class="why-walk">
      <h2>Why Walk?</h2>
      <div class="why-walk-p">
        <p>Because apart from enjoying the marvellous scenery and keeping healthy, you’ll be helping to transform the lives of villagers in Zambia’s Western Province where almost half the population still lacks safe water. Village Water’s ‘One Village At A Time’ campaign is hoping to change this.</p>
        <p>Here the scarcity of safe water means eye and infections are prevalent as is diarrhoea, in fact it kills 10 children under five years of age every day in Zambia! People often have to walk miles to a safe water source – so every step you take will remind you of their daily drudge and the reason to keep on walking!</p>
        <p>The funds raised will help supply wells so that villagers can grow their own vegetables and bananas for themselves and sell to raise income. The community will get the education and support they need to take charge of their own hygiene and sanitation, and a protected waterpoint and training to maintain it. So lasting safe water is close to home whenever they need it.</p>
        <img src="@/assets/z1.png" alt="logo" height="200" >
        <img src="@/assets/51.png" alt="logo" height="200" width="200">
      </div>
      <hr>
    </div> -->
    <!-- <div class="the-walk">
      <h2>The Walk</h2>
      <h4>You can do it!</h4>
      <p>Those who may feel daunted by an eight day trek, can still join in because we’ve subdivided the route into manageable stages of 5-14 miles per day. You can join us for half a day, a full day or stay with us every step of the 100-mile way!</p>
      <p>The Walk For Water will be led by experienced rambler of Stokesley, who will be ably supported by keen hikers from The Rotary Club of Stokesley. The walk is open to all ages though youngsters under 16 years of age must be accompanied by a responsible adult. 
         Whilst the walk leader and Rotary members will be there to guide and support you, your personal health and safety is your own responsibility. </p>
      <h5>Below you'll find the route and stages:</h5>   
      <img src="@/assets/map.png">
      <table>
        <tr>
          <th>Section</th>
          <th>What to expect</th>
          <th>First section</th>
          <th>Second section</th>
        </tr>
        <tr>
          <th>Day 1: Sunday 8th September </th>
          <th>A long, strenuous climb of 420m over 4miles to High Cup Nick. You'll encounter a number of fords before a rocky path down to to Cauldron Snout. There's some rocky paths on the way to Widdy Bank farm before an easier final section. Excellent views.</th>
          <th>9.6 miles Strenuous</th>
          <th>4.4 miles Strenuous </th>
        </tr>
        <tr>
          <th>Day 2: Monday 9th September</th>
          <th>A day of scenic views, passing High and Low Force, then through meadowland to Middleton in Teesdale</th>
          <th>5.4 miles Moderate</th>
          <th>3.6 miles Easy</th>
        </tr>
        <tr>
          <th>Day 3: Tuesday 10th September</th>
          <th>A day of picture postcard views passing through Romaldkirk to Barnard Castle</th>
          <th>6.2 miles Moderate</th>
          <th>6.8 miles Moderate</th>
        </tr>
        <tr>
          <th>Day 4: Wednesday 11th September</th>
          <th>A day of historic sites from Barnard Castle, past Egglestone Abbey, skirting Rokeby Park then to Whorlton Bridge and on to Gainford.</th>
          <th>4.5 miles Moderate</th>
          <th>5.9 miles Moderate</th>
        </tr>
        <tr>
          <th>Day 5: Thursday 12th September</th>
          <th>The path now starts to meander through farmland which can be muddy. Once we reach Broken Scar the route skirts close to Darlington before going through Croft to Hurworth.</th>
          <th>8.4 miles Moderate</th>
          <th>7.1 miles Moderate</th>
        </tr>
        <tr>
          <th>Day 6: Friday 13th September</th>
          <th>After following a minor road from Hurworth to Neasham we return to a footpath by the river. Whilst fairly easy walking this path is not well maintained and can be muddy.</th>
          <th>6.6 miles Moderate</th>
          <th>7.6 miles Moderate</th>
        </tr>
        <tr>
          <th>Day 7: Saturday 14th September</th>
          <th>From Yarm we enter the more residential part of the route but still with good open spaces, and the added interest of the Tees Barrage and the Transporter Bridge.</th>
          <th>8.1 miles Moderate</th>
          <th>5.3 miles Easy</th>
        </tr>
        <tr>
          <th>Day 8: Sunday 15th September</th>
          <th>The day's first stage mainly follows the disused railway line through Middlesbrough's industrial heartland. We celebrate the end of our walk with a stretch from Redcar to South Gare and the mouth of the Tees.</th>
          <th>7.4 miles Easy</th>
          <th>3.1 miles Easy</th>
        </tr>
        <tfoot>
          <th colspan="4">
          Important note: As Giant Hogweed grows in a number of places along the Tees, especially from Day 5 to the first stage of day 7,  you are advised to wear long trousers.
          </th>
        </tfoot>
      </table>
        <p>
        <img src="@/assets/tees1.jpg" alt="logo" height="250" width="300">
        <img src="@/assets/z2.png" alt="logo" height="250" width="300" >
        </p>
        <hr>
    </div>
    <div class="our-links">
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
  props: {
    msg: String,
    items: [
      {date: "Day 1: Sunday 8th September", 
       example: "A long, strenuous climb of 420m over 4miles to High Cup Nick. You'll encounter a number of fords before a rocky path down to to Cauldron Snout. There's some rocky paths on the way to Widdy Bank farm before an easier final section. Excellent views.",
       section1: "9.6 miles Strenuous",
       section2: "4.4 miles Strenuous"},
    ]
  },
  methods: {
    whyWalk(){
      window.scrollTo(0,750);
    },
    theWalk(){
      window.scrollTo(0,1420);
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

  h3 {
    margin-top: 0px;
    margin-bottom: 0px;
  }

  .welcome {
    height: 730px;
    width: 100%;
    background-color: white;
  }
  .why-walk {
    height: 650px;
    width: 100%;
    background-color: white;
  }
  .why-walk-p {
    width: 80%;
    text-align: center;
    margin: auto;
  }
  .the-walk {
    height: 1300px;
    width: 100%;
    background-color: white;
  }
  .our-links {
    height: 800px;
    width: 100%;
    background-color: white;
  }

  table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 80%;
    margin: auto;
  }

  td, th {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 8px;
  }

  tr:nth-child(even) {
    background-color: #dddddd;
  }

  @media only screen and (max-width : 768px) {

    table {
      width: auto ;
      max-width: 100% ;
      height: auto ;
    }

    img {
    width: auto ;
    max-width: 100% ;
    height: auto ;
    }

    p {
      height: auto;
      width: auto ;
    max-width: 100% ;
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
  -moz-box-shadow:inset 0px 1px 0px 0px #8a2a21;
	-webkit-box-shadow:inset 0px 1px 0px 0px #8a2a21;
	box-shadow:inset 0px 1px 0px 0px #8a2a21;
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #c62d1f), color-stop(1, #f24437));
	background:-moz-linear-gradient(top, #c62d1f 5%, #f24437 100%);
	background:-webkit-linear-gradient(top, #c62d1f 5%, #f24437 100%);
	background:-o-linear-gradient(top, #c62d1f 5%, #f24437 100%);
	background:-ms-linear-gradient(top, #c62d1f 5%, #f24437 100%);
	background:linear-gradient(to bottom, #c62d1f 5%, #f24437 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#c62d1f', endColorstr='#f24437',GradientType=0);
	background-color:#c62d1f;
	-moz-border-radius:6px;
	-webkit-border-radius:6px;
	border-radius:6px;
	border:1px solid #d02718;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:15px;
	font-weight:bold;
	padding:6px 24px;
	text-decoration:none;
	text-shadow:0px 1px 0px #810e05;
  
}

</style>
