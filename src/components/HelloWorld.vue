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
        <button @click="information" class="myButton">Information</button>
        <button @click="registration" class="myButton">Registration</button>
        <button @click="sponsorship" class="myButton">Sponsorship</button>
        <button @click="ourLinks" class="myButton">Our Links</button>
        <button @click="tac" class="myButton">Terms & Conditions</button>
      </div>
      <h1>Rotary Club of Stokesley</h1>
      <h1>Teams up with Village Water</h1>
      <img src="@/assets/page1logo.png" alt="logo" height="100" width="500">
      <br>
      <br>
      <br>
      <h2>LET’S PUT OUR BEST FEET FORWARD TO</h2>
      <h2>WALK FOR WATER: THE TEESDALE WAY</h2>
      <h3>SEPTEMBER 8, 2019 – SEPTEMBER 15, 2019 </h3>
      <img src="@/assets/page1.jpg" alt="logo" height="200" width="500">
      <p class="custom-p">The Rotary Club of Stokesley is organising a sponsored walk following the magnificent 100 miles of the Teesdale Way from Dufton in the Cumbrian Pennines to South Gare at the mouth of the Tees taking in the historic and scenic sights of Cumbria, Durham and Tees Valley en route. 
         The walk, which will span eight days, will raise funds for the Rotary-supported charity Village Water, (www.villagewater.org), which provides safe water, sanitation and hygiene for, and fosters independence among, African communities and accounts for every penny! </p>
      <hr>   
    </div>
    <!---WHY WALK----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="whyWalk">
      <h2>Why Walk?</h2>
      <div class="custom-p">
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
      <p class="custom-p">Those who may feel daunted by an eight day trek, can still join in because we’ve subdivided the route into manageable stages of 5-14 miles per day. You can join us for half a day, a full day or stay with us every step of the 100-mile way!</p>
      <p class="custom-p">The Walk For Water will be led by experienced rambler of Stokesley, who will be ably supported by keen hikers from The Rotary Club of Stokesley. The walk is open to all ages though youngsters under 16 years of age must be accompanied by a responsible adult. 
         Whilst the walk leader and Rotary members will be there to guide and support you, your personal health and safety is your own responsibility. </p>
      <h5>Below you'll find the route and stages:</h5>   
      <img src="@/assets/map.png">
      <b-table stacked="md" striped :items="items">
      </b-table>
      <h5 class="custom-p">
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
      <div class="custom-p">
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
      <div class="custom-p">
      <p><b>Disabled access: </b>Limited availability for disabled access.</p>
      <p><b>Where you can join us on the walk: </b>The start points for each day and half day sections are within this pack.</p>
      <p><b>Getting to and from the walk is your responsibility: </b>Official places and departure times showing where you can join the walk for a section, a day or several days is clearly marked on the Walk Sections sheet. Please be at your start point 30 minutes prior to your start time. There will be Marshals to greet you at these points. Post codes/map reference points are available on the mileage chart.</p>
      <p><b>BEFORE WE GO - PREPARING FOR THE WALK</b></p>
      </div>
      <div class="parent custom-p">
        <p>There’s lots to think about before we set off so here’s some helpful tips to get you planning</p>
        <ul>
          <li>The terrain is rugged for the first four days, so we advise good walking boots for these sections.</li>
          <li>Don’t forget some drinking water.</li>
          <li>Wear well-fitting comfortable boots or sturdy trail shoes depending on the weather.</li>
          <li>Don’t underestimate the weather, especially extremes of wet and wind.</li>
          <li>Dress in layers: thin thermals are good for base layers; woollen jumpers and/or mid weight polyester fleeces will suffice for mid-layers. <br/> While a waterproof jacket is essential to keep the wind and rain at bay.</li>
          <li>Opt for light, flexible, quick drying trousers or shorts if the weather is hot. Wear a hat if it’s sunny – and a different one if it’s cold!</li>
        </ul>
        <p><b>You may also like to take</b></p>
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
      <h5><b>WANT TO DONATE?</b></h5>
      <p>You can donate through our Virgin Giving page. Address is Virgin Giving Rotary Walk for Water</p>
      <p class="bacs"><i>Or pay by BACS online</i></p>
      <p class="bacs"><i>Sort code: 20-56-74</i></p>
      <p class="bacs"><i>Account number: 10435287</i></p>
      <p class="bacs"><i>Please include your surname and initials as reference eg w4w Blogs J</i></p>
      <p class="bacs"><i>Cheques made out to Rotary Club of Stokesley posted to 6 Thirsk Road, Stokesley TS9 5BW</i></p>
      <h3>Walk for Water with The Rotary Club of Stokesley
          and help other people while you are having fun!</h3>
      <img src="@/assets/tees3.jpg" alt="tees" height="500" width=80%>
      <p>
        <img src="@/assets/tees2.jpg" alt="tees" height="400" width="300">
        <img src="@/assets/z3.jpg" alt="tees" height="400" width="450">
      </p>
      <hr>
    </div>
    <!--- REGISTRATION ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="registration">
      <h2>Registration</h2>
      <div>
        <p class="reg-info">Date: September 8th through to September 15th 2019</p>
        <p class="reg-info">Start: Dufton</p>
        <p class="reg-info">Finish: South Gare (mouth of the river Tees)</p>
        <p class="reg-info">Please read information and walk schedule before completing the form.</p>
        <p class="reg-info">Registration fee is adults £10.00 per day up to £30 maximum.</p>
        <p class="reg-info">Young people under the age of 16 years £5.00</p>
        <p class="reg-info">Please send this form with cheques made payable to The Rotary Club of Stokesley, Walk for Water, 10 Millgin Court, Ingelby Barwick, Teesside TS17 5AY</p>
        <p class="reg-info">Please, please try to get your friends and neighbours to join you.</p>
        <p class="reg-info">Confirmation sponsor forms and full information will be emailed to you – Payment secures yourplace.</p>
        <br>
        <p>Please copy and paste the form below, into your email with the relevant information to: <b>walkforwaterfund@gmail.com</b></p>
        <div class="reg-div">
          <p class="reg"><b>Full Name:  </b></p>
          <p class="reg"><b>Address: </b></p>
          <p class="reg"><b>Home phone number: </b></p>
          <p class="reg"><b>Mobile phone number: </b></p>
          <p class="reg"><b>Name and Tel of Emergency contact: </b></p>
          <p class="reg">Please indicate which sections intend walking by placing a x in the relevant box</p>
          <p class="reg">September</p>
          <table>
            <tr>
              <th>Date</th>
              <th>8th </th> 
              <th>9th </th>
              <th>10th</th>
              <th>11th</th>
              <th>12th</th>
              <th>13th</th>
              <th>14th</th>
              <th>15th</th>
            </tr>
            <tr>
              <td>AM</td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td>PM</td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
          </table>
          <p class="reg">Where and how to pay:- <br>
          BACS Sort Code  20-56-74 account number 0010435287 with reference <br>
          W4W and surname Eg W4W Blogs J
          </p>
          <p class="reg"><b>Amount Paid Total: £ </b></p>
          <br>
          <p class="reg">Alternative ways to pay:- <br/> 
            <b>By post Amount enclosed: £ </b><br/> 
            Please make your check out to The Rotary Club of Stokesley <br/> 
            T0: Walk for Water <br/> 
            10 Millgin Court <br/> 
            Ingleby Barwick <br/> 
            Teesside TS17 5AY</p>
        </div>  
        <!-- <img src="@/assets/Email.png" alt="email" height="300" width="600"> -->
      </div>
      <hr>
    </div>
    <!--- SPONSORSHIP ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div" id="sponsorship">
      <h2>Sponsorship</h2>
      <h5>If you have registered and would like to download a sponsorship form press the button below</h5>
      <p>This will create a pdf which you can download and print from</p>
      <b-btn variant="outline-primary" @click="createSponsorPDF">Create PDF</b-btn>
      <hr>
    </div>
    <!--- OUR LINKS ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div parent" id="ourLinks">
      <h2>Our links</h2>
      <ul>
        <li><a href="https://www.rotary-ribi.org/clubs/homepage.php?ClubID=166" target="_blank" rel="noopener">Stokesley Rotary Club</a></li>
        <li><a href="http://www.classicsonshow.co.uk/" target="_blank" rel="noopener">Classics on Show</a></li>
        <li><a href="https://villagewater.org/" target="_blank" rel="noopener">Village Water Charity</a></li>
      </ul>
      <br>
      <img src="@/assets/page1logo.png" alt="logo" height="150" width="600">
      <h3>Rotaries Six Areas of Focus</h3>
      <ul>
        <li>Peace and conflict prevention/resolution</li>
        <li>Disease prevention and treatment</li>
        <li>Water and sanitation</li>
        <li>Maternal and child health</li>
        <li>Basic education and literacy</li>
        <li>Economic and community development</li>
      </ul>
      <hr>
    </div>
    <!--- T and C ----------------------------------------------------------------------------------------------------------------------------------------->
    <div class="child-div custom-p" id="tac">
      <h2>The Rotary Club of Stokesley</h2>
      <h3>TERMS AND CONDITIONS</h3>
      <p><b>Please ensure that you have read this document before submitting your registration form.</b></p>
      <p class="reg-info">“The event" – refers to the Teesdale Walk 2019.</p>
      <p class="reg-info">The Rotary Club of Stokesley includes the Walk Committee and "the organiser" means either or both.</p>
      <h5><b>Refunds</b></h5>
      <p>The event is for charity so no entry fee will be refunded unless the whole event is cancelled by the Walk Committee.</p>
      <h5><b>Safety</b></h5>
      <p class="reg-info">The Rotary Club of Stokesley will use its best endeavours to ensure that the event is safe for all participants but each participant must also take reasonable precautions to ensure their own safety. This would include, but is not limited to:</p>
      <p class="reg-info">Taking note of all information and advice provided by the Walk Committee with respect to appropriate clothing etc.</p>
      <p class="reg-info">Following the rules of the Highway Code and the Country Code insofar as they apply to pedestrians</p>
      <p class="reg-info">Following the instructions of the event organisers, the walk leader and other guides by -</p>
      <p class="reg-info">Behaving in a sensible and responsible manner</p>
      <p class="reg-info">Not doing anything that might endanger the health, safety or well-being of any person including themselves, other participants, and</p>
      <p class="reg-info">Not consuming alcohol immediately before or during the event.</p>
      <p class="reg-info">In registering for or taking part in the event you acknowledge that you do so at your own risk and that conditions may occur which give rise to risks that are unforeseen and / beyond the control of the Walk Committee.</p>
      <h5><b>Liability</b></h5>
      <p>The Rotary Club of Stokesley accepts no liability before after or during the event for damage to or loss of any property belonging to, or brought to the event by, any participant. The Rotary Club of Stokesley accepts no liability for any injury to any participant except where the injury is directly caused by the negligence of The Rotary Club of Stokesley.</p>
      <h5><b>Disqualification</b></h5>
      <p>The Walk Committee reserves the right to disqualify from the event any participant who appears not to be fit to take part or who acts in a manner which the Walk Committee considers to be a breach of these conditions and/or may adversely affect the reputation of The Rotary Club of Stokesley.</p>
      <h5><b>Health and Fitness</b></h5>
      <p>All participants must satisfy themselves, if necessary by taking medical advice, that they are in sufficiently good health and physically able to undertake the walk in which they have chosen to participate.</p>
      <p>Any prospective participant who has a disability must ensure both that they are fit to participate in their chosen walk section(s) and that they have support arranged to accompany or otherwise support them on the relevant walk before registering for the event.</p>
      <h5><b>Sponsorship</b></h5>
      <p>The event will be organised, certified and marshalled to a level appropriate for sponsors of participants to be able to be satisfied that the event is appropriate for sponsorship.</p>
      <h5><b>Publicity</b></h5>
      <p>The Organisers may arrange for the local press to attend the event and they may choose to take photographs. The Organisers may also take photographs that it may use for publicity in connection with future events or to publicise the activities of the Rotary Club of Stokesley.
Images of children under 16 will not be taken or used if it can be avoided.</p>
    </div>
  </div>
</template>

<script>
import jsPDF from 'jspdf'
import 'jspdf-autotable';
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
    information() {
      document.getElementById('information').scrollIntoView();
    },
    registration() {
      document.getElementById('registration').scrollIntoView();
    },
    sponsorship() {
      document.getElementById('sponsorship').scrollIntoView();
    },
    ourLinks(){
        document.getElementById('ourLinks').scrollIntoView();
    },
    tac(){
        document.getElementById('tac').scrollIntoView();
    },
    top(){
      window.scrollTo(0,0);
    },
    createSponsorPDF() {
      var rotaryLogo = {
          src: 'data:image/png;base64,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'
      }
      var villageLogo = {
        src: 'data:image/png;base64,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'
      }
      var text = "Using Gift Aid means that for every pound you raise, we can claim an extra 25% more from the government helping your donation grow and it will not cost you a penny! This means £100 can be increased to £125 as long as donations are made through Gift Aid, to qualify agree:- “By ticking the Gift Aid box, I confirm I have paid or will pay an amount of UK Income Tax and/or Capital Gains Tax for the tax year 2018/2019 that is at least equal to the amount of tax that all charities and CASCs that I am donating to will reclaim on my gifts for 2019/2020. I understand that VAT and Council Tax do not qualify. I understand that the charity will reclaim 25p of tax on every £1 I donate”"		
      var text2 = "Please pay sponsorship by cheque or BACS payable to Rotary Club of Stokesley Trust Fund, Sort code 20-56-74 Account 00320382. Post to 6 Thirsk Road Stokesley TS9 5BW. Please add W4W your surname name & initial as reference if using BACS. Eg W4W Blogs J"	
      var doc = new jsPDF('p', 'pt');
      doc.addImage(rotaryLogo.src, 'PNG', 10, 10, 50, 50);
      doc.addImage(villageLogo.src, 'PNG', 500, 20, 70, 40);
      doc.setFontSize(13);
      doc.text('Rotary Club of Stokesley', 10, 73);
      doc.text('Walker Name & Number: ', 250, 73);
      doc.rect(248,60,300,20);
      doc.setFontSize(12);
      doc.text('Rotary Club of Stokesley Trust Fund is a Registered Charity - No: 1032456', 100, 100);
      doc.text('TEESDALE WAY SPONSORED WALK 8th-15th September 2019', 125, 115);
      doc.text('SPONSORSHIP SHEET', 225, 130);
      doc.text('The funds raised by me will support the following charity', 155, 145);
      doc.setFontStyle('bold');
      doc.text('Charity Name: Village Water', 225, 165);
      doc.setFontStyle('normal');
      doc.text('GIFT AID:', 20, 200);
      doc.setFontSize(10);
      var splitTitle = doc.splitTextToSize(text, 550);
      doc.text(20, 215, splitTitle);
      doc.setFontStyle('bold');
      var splitTitle2 = doc.splitTextToSize(text2, 570);
      doc.text(20, 290, splitTitle2);
      doc.rect(20,330,550,440);
      doc.setFontStyle('bold');
      doc.text('FullName',45,345);
      doc.line(120,390,120,770);
      doc.line(120,330,120,365);
      doc.text('Home Address (not work please)',150,345);
      doc.line(330,390,330,770);
      doc.line(330,330,330,365);
      doc.text('PostCode',340,345);
      doc.line(400,390,400,770);
      doc.line(400,330,400,365);
      doc.text('Amount',405,345);
      doc.line(450,390,450,770);
      doc.line(450,330,450,365);
      doc.text('Gift',455,345);
      doc.text('Aid',455,356);
      doc.line(480,390,480,770);
      doc.line(480,330,480,365);
      doc.text('Date',500,345);
      doc.text('Received',500,356);
      doc.line(20,365,570,365);
      doc.setFontStyle('bold');
      doc.text('We need all your details if you are Gift Aiding your sponsorship otherwise',120, 375);
      doc.text('we cannot claim on your behalf!',220, 385);
      doc.line(20,390,570,390);
      doc.line(20,410,570,410);
      doc.line(20,430,570,430);
      doc.line(20,450,570,450);
      doc.line(20,470,570,470);
      doc.line(20,490,570,490);
      doc.line(20,510,570,510);
      doc.line(20,530,570,530);
      doc.line(20,550,570,550);
      doc.line(20,570,570,570);
      doc.line(20,590,570,590);
      doc.line(20,610,570,610);
      doc.line(20,630,570,630);
      doc.line(20,650,570,650);
      doc.line(20,670,570,670);
      doc.line(20,690,570,690);
      doc.line(20,710,570,710);
      doc.line(20,730,570,730);
      doc.line(20,750,570,750);
      doc.line(20,770,570,770);
      doc.text('Sheet 1 of..........', 20, 790);
      doc.text('Total all sheets..........', 20, 815);
      doc.text('Total this sheet..........', 430, 790);
      doc.text('Total Gift Aid all sheets..........', 430, 815);
      doc.save('SponsorshipPDF');
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

  .reg-div {
    width: 35%;
    margin: auto;
    text-align: center;
    border-style: solid;
  }

  .reg {
    margin-top: 0px;
    margin-bottom: 0px;
    text-align: left;
  }

  .reg-info {
    margin-top: 3px;
    margin-bottom: 3px;
  }

  .parent {
    margin: auto;
    text-align: center;
  }
  .parent > ul {
    display: inline-block;
  }

  .custom-p {
    width: 80%;
    text-align: center;
    margin: auto;
  }

  table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
  width:40%;
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

    table, th, td {
      width:100%;
    }

    .reg-div {
      width: 100%;
    }

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
