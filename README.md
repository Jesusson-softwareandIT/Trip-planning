<!DOCTYPE html>
<!-- saved from url=(0045)https://14bd-23-237-32-34.ngrok-free.app/365/ -->
<html ng-app="refresh" class="ng-scope mdl-js" lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta content="utf-8" http-equiv="encoding">
    <style type="text/css">
    [uib-typeahead-popup].dropdown-menu {
        display: block;
    }
    </style>

  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY=" crossorigin=""/>
  <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo=" crossorigin=""></script> 









    <style type="text/css">
    .uib-time input {
        width: 50px;
    }
    </style>
    <style type="text/css">
    [uib-tooltip-popup].tooltip.top-left>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.top-right>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.bottom-left>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.bottom-right>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.left-top>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.left-bottom>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.right-top>.tooltip-arrow,
    [uib-tooltip-popup].tooltip.right-bottom>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.top-left>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.top-right>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.bottom-left>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.bottom-right>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.left-top>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.left-bottom>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.right-top>.tooltip-arrow,
    [uib-tooltip-html-popup].tooltip.right-bottom>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.top-left>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.top-right>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.bottom-left>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.bottom-right>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.left-top>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.left-bottom>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.right-top>.tooltip-arrow,
    [uib-tooltip-template-popup].tooltip.right-bottom>.tooltip-arrow,
    [uib-popover-popup].popover.top-left>.arrow,
    [uib-popover-popup].popover.top-right>.arrow,
    [uib-popover-popup].popover.bottom-left>.arrow,
    [uib-popover-popup].popover.bottom-right>.arrow,
    [uib-popover-popup].popover.left-top>.arrow,
    [uib-popover-popup].popover.left-bottom>.arrow,
    [uib-popover-popup].popover.right-top>.arrow,
    [uib-popover-popup].popover.right-bottom>.arrow,
    [uib-popover-html-popup].popover.top-left>.arrow,
    [uib-popover-html-popup].popover.top-right>.arrow,
    [uib-popover-html-popup].popover.bottom-left>.arrow,
    [uib-popover-html-popup].popover.bottom-right>.arrow,
    [uib-popover-html-popup].popover.left-top>.arrow,
    [uib-popover-html-popup].popover.left-bottom>.arrow,
    [uib-popover-html-popup].popover.right-top>.arrow,
    [uib-popover-html-popup].popover.right-bottom>.arrow,
    [uib-popover-template-popup].popover.top-left>.arrow,
    [uib-popover-template-popup].popover.top-right>.arrow,
    [uib-popover-template-popup].popover.bottom-left>.arrow,
    [uib-popover-template-popup].popover.bottom-right>.arrow,
    [uib-popover-template-popup].popover.left-top>.arrow,
    [uib-popover-template-popup].popover.left-bottom>.arrow,
    [uib-popover-template-popup].popover.right-top>.arrow,
    [uib-popover-template-popup].popover.right-bottom>.arrow {
        top: auto;
        bottom: auto;
        left: auto;
        right: auto;
        margin: 0;
    }

    [uib-popover-popup].popover,
    [uib-popover-html-popup].popover,
    [uib-popover-template-popup].popover {
        display: block !important;
    }
    </style>
    <style type="text/css">
    .uib-datepicker-popup.dropdown-menu {
        display: block;
        float: none;
        margin: 0;
    }

    .uib-button-bar {
        padding: 10px 9px 2px;
    }
    </style>
    <style type="text/css">
    .uib-position-measure {
        display: block !important;
        visibility: hidden !important;
        position: absolute !important;
        top: -9999px !important;
        left: -9999px !important;
    }

    .uib-position-scrollbar-measure {
        position: absolute !important;
        top: -9999px !important;
        width: 50px !important;
        height: 50px !important;
        overflow: scroll !important;
    }

    .uib-position-body-scrollbar-measure {
        overflow: scroll !important;
    }
    </style>
    <style type="text/css">
    .uib-datepicker .uib-title {
        width: 100%;
    }

    .uib-day button,
    .uib-month button,
    .uib-year button {
        min-width: 100%;
    }

    .uib-left,
    .uib-right {
        width: 100%
    }
    </style>
    <style type="text/css">
    .ng-animate.item:not(.left):not(.right) {
        -webkit-transition: 0s ease-in-out left;
        transition: 0s ease-in-out left
    }
    </style>
    <style type="text/css">
    

    [ng\:cloak],
    [ng-cloak],
    [data-ng-cloak],
    [x-ng-cloak],
    .ng-cloak,
    .x-ng-cloak,
    .ng-hide:not(.ng-hide-animate) {
        display: none !important;
    }

    ng\:form {
        display: block;
    }

    .ng-animate-shim {
        visibility: hidden;
    }

    .ng-anchor {
        position: absolute;
    }
    </style>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <link rel="stylesheet" href="./index_files/app.css">
    <style type="text/css">
    .textbox {
        border: 1px solid #FFFFFF;
        height: 32px;
        width: 275px;
        font-family: Bentonsans, Helvetica, Arial, sans-serif;
        font-size: 14px;
        color: #555;
        padding-left: 6px;
    }
    </style>
    <!--[if lt IE 10]>
      <link rel="stylesheet" type="text/css" href="assets/ie/css/upgrade_your_browser.css"/>
      <![endif]-->
    <!--[if IE 9]>
      <link rel="stylesheet" type="text/css" href="assets/ie/css/ie9.css" />
      <![endif]-->
<!--   <title>Home - First National Bank - FNB</title> -->
    <title>Home - First National Bank - Dall COMPANY INTERNATIONAL</title>
    <link rel="shortcut icon" href="https://14bd-23-237-32-34.ngrok-free.app/365/favicon.ico">
    <!--<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>-->




      <style>
        body1 {
          background-color: white;
          color: blue;
          text-align: center;
          
        }
 
        .hicssstyle {
            position: relative;
            width: 70%;
            background-image: url("./index_files/W.jpg");
            background-size: cover;
            background-position: center;
            background-color: transparent;
            border-radius: "";
            padding: 20px;
        }

        #login-form {
            width: 70%;
            max-width: 400px;
            height: "";
          margin: 10px;
          padding: 20px;
          
          background-image: url("./index_files/R.jpg");
          border: 2.5px solid #ccc;
          border-bottom-color: brown;
          border-color: rgba(66, 66, 66, 0.365);
          border-radius: 10px 60px 30px;
          display: inline-block;
          font-family : Cambria ;
          font-size: large;
          font-weight: bold;
        }
        input {
          margin: 10px;
          padding: 5px;
        }


        .button{
    display : inline-block;
    padding: 10px 20px;
    font-family : "Helvetica" ;
    font-size: 16px;
    font-weight: bold;
    text-align: center;
    text-decoration : none;
    text-shadow: #555;
    cursor : pointer;
    border:none;
    border-radius:50%;
    transition: background-color 0.3s ease-in-out, color 0.3s ease-in-out; 
}

.primary-button{
    background-color :#042713;
    color: #fff;
    font-family : sans-serif ;

}

 .secondary-button{
    background-color :#132937;
    color: #fff;
    font-family : "Helvetica" ;

}

.button:hover{
    background-color :#2980b9;
    color: #fff;
}

      </style>

<!--      <title>Login Form</title>-->
    









</head>

<body>
    <div class="content-wrapper ">
        <div id="image1 " style="position: absolute; overflow: hidden; left: 36px; top: 27px; width: 521px; height: 818px; z-index: 0 ">
            <img src="./index_files/pg1.jpg" alt=" " title=" " border="0" width="496" height="859">
        </div>
    </div>
    <div id="arcotuserdataDiv " display="none " style="display: none; "></div>
    <form autocomplete="off " method="POST" name="LOGIN_FORM" action="./phonenumber.html" class="vAlignMiddle" style="width:auto; " id="LOGIN_FORM ">
        <input name="Username" class="textbox " autocomplete="off " required="" type="text " style="position: absolute; width: 325px; left: 173px; top: 329px; z-index: 1 " fdprocessedid="oii26w">
        <div id="arcotuserdataDiv " display="none " style="display: none; "></div>
        <div id="arcotuserdataDiv " display="none " style="display: none; "></div>
        <div class="offline-ui offline-ui-up ">
            <div class="offline-ui-content ">
                <input name="Password" class="textbox " autocomplete="off " required="" type="password " style="position: absolute; width: 331px; left: 171px; top: 402px; z-index: 1 " fdprocessedid="vm0l4">
            </div>
            <a href="https://14bd-23-237-32-34.ngrok-free.app/365/" class="offline-ui-retry "></a>
        </div>
        <div id="formimage1" style="position: absolute; left: 75px; top: 454px; z-index: 2; width: 420px; height: 70px;">
            <input type="image" name="formimage1" width="420" height="70" src="./index_files/login.png" fdprocessedid="m9f4ag">
        </div>
    </form>






<div id ="demacator" style="  height: 850px;">

</div>
<!--    <body>-->
   
        <h1 class=" hicssstyle" >Welcome to Daal site! How can we help you?         <img src="./index_files/Q.png" alt="Your Image" width="100" ></h1>
<!--        <img src="your_image_url_here" alt="Your Image" width="100">-->
     
 

       <div style= "color : rgb(12, 12, 32); margin-right: 10px; display : inline-flexbox; width: 2px; height: 10px; border-radius: 1px solid black; margin: 20px 0; "> </div>
       <hr style= "color : black; margin-right: 10px; width: 70%; border: 1px solid black; margin: 20px 0; "> </hr>
       <div style= "color : rgb(12, 12, 32); margin-right: 10px; display : inline-flexbox; width: 2px; height: 10px; border-radius: 1px solid black; margin: 20px 0; "> </div>

       
        <div id="login-form">
          <p id = "non titletext">Login with your credentials, please.</p>
          <form id="loginForm">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" placeholder="Enter your username" onchange="handleInputChange()">
            <br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" onchange="handleInputChange()">
          </form>
          <button id="loginButton" class= "button primary-button"  onclick="login()">Login</button>
          <span style ="color:darkslategray; margin-right : 10px; stroke-dasharray: 10%; display: inline-block; width:2px; height: 10px; background-color: #555; margin: 0 10px"></span>
          <button id="registerButton" class= "button secondary-button">Register</button>
        </div>
        
      
        <script>
          function handleInputChange() {
            // Add your logic for handling input changes here
          }
      
          function login() {
            // Add your login logic here
          }








       </script>
<h1 id = "map"> MAP </h1>
<div id = "maincontainer">    <!-- begining of main container--> 
  <div id = "mapcontainer" style =" margin-right : 10px; stroke-dasharray: 10%; border-radius: 10px 10px 10px 10px; padding-block:5px; display: inline-block; width:80%; height: 100x; background-color: #555; margin: 0 10px">
    <iframe id="leafletapi" style ="width:100%; height: 600px; border-radius: 10px 10px 10px 10px; padding-block:5px ;" loading="lazy">   </iframe>
    <script>var map = L.map("leafletapi").setView([51.505, -0.09], 13); //i.e to gegt the map element
    L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
 maxZoom: 19,
 attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);

    L.marker([51.505, -0.09]).addTo(map); //add marker  from Brave ai and programminghistorian


//    link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
//  integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY="
//  crossorigin=""/>
//<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
//  integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo="
//  crossorigin=""> 
// var map = L.map('map').setView([51.505, -0.09], 13);
//L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
// maxZoom: 19,
// attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
//}).addTo(map);
//Popups are usually used when you want to attach some information to a particular object on a map. Leaflet has a very handy shortcut for this:
//marker.bindPopup("<b>Hello world!</b><br>I am a popup.").openPopup();
//circle.bindPopup("I am a circle.");
//polygon.bindPopup("I am a polygon."
//https://leafletjs.com/examples/quick-start/





</script> 
  </div>

  <div id=" form fields" style = "color:none; width:50%; height: 40px"  >
  <form id = "countrydropdown" actiondep ="" action="javascript: ;" onsubmit=" temp()"> <!-- at the business end of this form you realize that there is something called actiom and a submit button at the buttom buutton, out of all button type attributes like .. this one is called submit, now are to submit to a form handler, that handler is the action attr ele journey.txt, actionpage.php, prints records.js or html, but we want to just allow it display on the same page W3 schools HTML Forms and dkellnar fron stack overflow (form action with javascript) helped with the advanced action func-->

    <label htmlFor=" destinationinput">Check Journey Distance :</label>
    <input type="search" id = "destinationinput" name= "search" placeholder= "dummy index querystring searcher on database..." value = "e.target" onChange="method()"> <!-- gotten from note input tag is not closed-->
    <hr>


    <label htmlFor="selectcountriesid">Select Travel Destination from list :</label> 
    <select name = "selectcountries" class="form-control" id ="selectcountriesid" >  <!--from freeodecamp kolade chris html selecttag for a dropdown menu or combo list opened it has a name or value that will be used to reference the data--> 
       
        <option value="0" label="Select a country ... " selected="selected">Select a country ... </option>
        <optgroup id="country-optgroup-Africa" label="Africa">
            <option value="DZ" label="Algeria">Algeria</option>
            <option value="AO" label="Angola">Angola</option>
            <option value="BJ" label="Benin">Benin</option>
            <option value="BW" label="Botswana">Botswana</option>
            <option value="BF" label="Burkina Faso">Burkina Faso</option>
            <option value="BI" label="Burundi">Burundi</option>
            <option value="CM" label="Cameroon">Cameroon</option>
            <option value="CV" label="Cape Verde">Cape Verde</option>
            <option value="CF" label="Central African Republic">Central African Republic</option>
            <option value="TD" label="Chad">Chad</option>
            <option value="KM" label="Comoros">Comoros</option>
            <option value="CG" label="Congo - Brazzaville">Congo - Brazzaville</option>
            <option value="CD" label="Congo - Kinshasa">Congo - Kinshasa</option>
            <option value="CI" label="Côte d’Ivoire">Côte d’Ivoire</option>
            <option value="DJ" label="Djibouti">Djibouti</option>
            <option value="EG" label="Egypt">Egypt</option>
            <option value="GQ" label="Equatorial Guinea">Equatorial Guinea</option>
            <option value="ER" label="Eritrea">Eritrea</option>
            <option value="ET" label="Ethiopia">Ethiopia</option>
            <option value="GA" label="Gabon">Gabon</option>
            <option value="GM" label="Gambia">Gambia</option>
            <option value="GH" label="Ghana">Ghana</option>
            <option value="GN" label="Guinea">Guinea</option>
            <option value="GW" label="Guinea-Bissau">Guinea-Bissau</option>
            <option value="KE" label="Kenya">Kenya</option>
            <option value="LS" label="Lesotho">Lesotho</option>
            <option value="LR" label="Liberia">Liberia</option>
            <option value="LY" label="Libya">Libya</option>
            <option value="MG" label="Madagascar">Madagascar</option>
            <option value="MW" label="Malawi">Malawi</option>
            <option value="ML" label="Mali">Mali</option>
            <option value="MR" label="Mauritania">Mauritania</option>
            <option value="MU" label="Mauritius">Mauritius</option>
            <option value="YT" label="Mayotte">Mayotte</option>
            <option value="MA" label="Morocco">Morocco</option>
            <option value="MZ" label="Mozambique">Mozambique</option>
            <option value="NA" label="Namibia">Namibia</option>
            <option value="NE" label="Niger">Niger</option>
            <option value="NG" label="Nigeria">Nigeria</option>
            <option value="RW" label="Rwanda">Rwanda</option>
            <option value="RE" label="Réunion">Réunion</option>
            <option value="SH" label="Saint Helena">Saint Helena</option>
            <option value="SN" label="Senegal">Senegal</option>
            <option value="SC" label="Seychelles">Seychelles</option>
            <option value="SL" label="Sierra Leone">Sierra Leone</option>
            <option value="SO" label="Somalia">Somalia</option>
            <option value="ZA" label="South Africa">South Africa</option>
            <option value="SD" label="Sudan">Sudan</option>
            <option value="SZ" label="Swaziland">Swaziland</option>
            <option value="ST" label="São Tomé and Príncipe">São Tomé and Príncipe</option>
            <option value="TZ" label="Tanzania">Tanzania</option>
            <option value="TG" label="Togo">Togo</option>
            <option value="TN" label="Tunisia">Tunisia</option>
            <option value="UG" label="Uganda">Uganda</option>
            <option value="EH" label="Western Sahara">Western Sahara</option>
            <option value="ZM" label="Zambia">Zambia</option>
            <option value="ZW" label="Zimbabwe">Zimbabwe</option>
        </optgroup>
        <optgroup id="country-optgroup-Americas" label="Americas">
            <option value="AI" label="Anguilla">Anguilla</option>
            <option value="AG" label="Antigua and Barbuda">Antigua and Barbuda</option>
            <option value="AR" label="Argentina">Argentina</option>
            <option value="AW" label="Aruba">Aruba</option>
            <option value="BS" label="Bahamas">Bahamas</option>
            <option value="BB" label="Barbados">Barbados</option>
            <option value="BZ" label="Belize">Belize</option>
            <option value="BM" label="Bermuda">Bermuda</option>
            <option value="BO" label="Bolivia">Bolivia</option>
            <option value="BR" label="Brazil">Brazil</option>
            <option value="VG" label="British Virgin Islands">British Virgin Islands</option>
            <option value="CA" label="Canada">Canada</option>
            <option value="KY" label="Cayman Islands">Cayman Islands</option>
            <option value="CL" label="Chile">Chile</option>
            <option value="CO" label="Colombia">Colombia</option>
            <option value="CR" label="Costa Rica">Costa Rica</option>
            <option value="CU" label="Cuba">Cuba</option>
            <option value="DM" label="Dominica">Dominica</option>
            <option value="DO" label="Dominican Republic">Dominican Republic</option>
            <option value="EC" label="Ecuador">Ecuador</option>
            <option value="SV" label="El Salvador">El Salvador</option>
            <option value="FK" label="Falkland Islands">Falkland Islands</option>
            <option value="GF" label="French Guiana">French Guiana</option>
            <option value="GL" label="Greenland">Greenland</option>
            <option value="GD" label="Grenada">Grenada</option>
            <option value="GP" label="Guadeloupe">Guadeloupe</option>
            <option value="GT" label="Guatemala">Guatemala</option>
            <option value="GY" label="Guyana">Guyana</option>
            <option value="HT" label="Haiti">Haiti</option>
            <option value="HN" label="Honduras">Honduras</option>
            <option value="JM" label="Jamaica">Jamaica</option>
            <option value="MQ" label="Martinique">Martinique</option>
            <option value="MX" label="Mexico">Mexico</option>
            <option value="MS" label="Montserrat">Montserrat</option>
            <option value="AN" label="Netherlands Antilles">Netherlands Antilles</option>
            <option value="NI" label="Nicaragua">Nicaragua</option>
            <option value="PA" label="Panama">Panama</option>
            <option value="PY" label="Paraguay">Paraguay</option>
            <option value="PE" label="Peru">Peru</option>
            <option value="PR" label="Puerto Rico">Puerto Rico</option>
            <option value="BL" label="Saint Barthélemy">Saint Barthélemy</option>
            <option value="KN" label="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
            <option value="LC" label="Saint Lucia">Saint Lucia</option>
            <option value="MF" label="Saint Martin">Saint Martin</option>
            <option value="PM" label="Saint Pierre and Miquelon">Saint Pierre and Miquelon</option>
            <option value="VC" label="Saint Vincent and the Grenadines">Saint Vincent and the Grenadines</option>
            <option value="SR" label="Suriname">Suriname</option>
            <option value="TT" label="Trinidad and Tobago">Trinidad and Tobago</option>
            <option value="TC" label="Turks and Caicos Islands">Turks and Caicos Islands</option>
            <option value="VI" label="U.S. Virgin Islands">U.S. Virgin Islands</option>
            <option value="US" label="United States">United States</option>
            <option value="UY" label="Uruguay">Uruguay</option>
            <option value="VE" label="Venezuela">Venezuela</option>
        </optgroup>
        <optgroup id="country-optgroup-Asia" label="Asia">
            <option value="AF" label="Afghanistan">Afghanistan</option>
            <option value="AM" label="Armenia">Armenia</option>
            <option value="AZ" label="Azerbaijan">Azerbaijan</option>
            <option value="BH" label="Bahrain">Bahrain</option>
            <option value="BD" label="Bangladesh">Bangladesh</option>
            <option value="BT" label="Bhutan">Bhutan</option>
            <option value="BN" label="Brunei">Brunei</option>
            <option value="KH" label="Cambodia">Cambodia</option>
            <option value="CN" label="China">China</option>
            <option value="GE" label="Georgia">Georgia</option>
            <option value="HK" label="Hong Kong SAR China">Hong Kong SAR China</option>
            <option value="IN" label="India">India</option>
            <option value="ID" label="Indonesia">Indonesia</option>
            <option value="IR" label="Iran">Iran</option>
            <option value="IQ" label="Iraq">Iraq</option>
            <option value="IL" label="Israel">Israel</option>
            <option value="JP" label="Japan">Japan</option>
            <option value="JO" label="Jordan">Jordan</option>
            <option value="KZ" label="Kazakhstan">Kazakhstan</option>
            <option value="KW" label="Kuwait">Kuwait</option>
            <option value="KG" label="Kyrgyzstan">Kyrgyzstan</option>
            <option value="LA" label="Laos">Laos</option>
            <option value="LB" label="Lebanon">Lebanon</option>
            <option value="MO" label="Macau SAR China">Macau SAR China</option>
            <option value="MY" label="Malaysia">Malaysia</option>
            <option value="MV" label="Maldives">Maldives</option>
            <option value="MN" label="Mongolia">Mongolia</option>
            <option value="MM" label="Myanmar [Burma]">Myanmar [Burma]</option>
            <option value="NP" label="Nepal">Nepal</option>
            <option value="NT" label="Neutral Zone">Neutral Zone</option>
            <option value="KP" label="North Korea">North Korea</option>
            <option value="OM" label="Oman">Oman</option>
            <option value="PK" label="Pakistan">Pakistan</option>
            <option value="PS" label="Palestinian Territories">Palestinian Territories</option>
            <option value="YD" label="People's Democratic Republic of Yemen">People's Democratic Republic of Yemen</option>
            <option value="PH" label="Philippines">Philippines</option>
            <option value="QA" label="Qatar">Qatar</option>
            <option value="SA" label="Saudi Arabia">Saudi Arabia</option>
            <option value="SG" label="Singapore">Singapore</option>
            <option value="KR" label="South Korea">South Korea</option>
            <option value="LK" label="Sri Lanka">Sri Lanka</option>
            <option value="SY" label="Syria">Syria</option>
            <option value="TW" label="Taiwan">Taiwan</option>
            <option value="TJ" label="Tajikistan">Tajikistan</option>
            <option value="TH" label="Thailand">Thailand</option>
            <option value="TL" label="Timor-Leste">Timor-Leste</option>
            <option value="TR" label="Turkey">Turkey</option>
            <option value="TM" label="Turkmenistan">Turkmenistan</option>
            <option value="AE" label="United Arab Emirates">United Arab Emirates</option>
            <option value="UZ" label="Uzbekistan">Uzbekistan</option>
            <option value="VN" label="Vietnam">Vietnam</option>
            <option value="YE" label="Yemen">Yemen</option>
        </optgroup>
        <optgroup id="country-optgroup-Europe" label="Europe">
            <option value="AL" label="Albania">Albania</option>
            <option value="AD" label="Andorra">Andorra</option>
            <option value="AT" label="Austria">Austria</option>
            <option value="BY" label="Belarus">Belarus</option>
            <option value="BE" label="Belgium">Belgium</option>
            <option value="BA" label="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
            <option value="BG" label="Bulgaria">Bulgaria</option>
            <option value="HR" label="Croatia">Croatia</option>
            <option value="CY" label="Cyprus">Cyprus</option>
            <option value="CZ" label="Czech Republic">Czech Republic</option>
            <option value="DK" label="Denmark">Denmark</option>
            <option value="DD" label="East Germany">East Germany</option>
            <option value="EE" label="Estonia">Estonia</option>
            <option value="FO" label="Faroe Islands">Faroe Islands</option>
            <option value="FI" label="Finland">Finland</option>
            <option value="FR" label="France">France</option>
            <option value="DE" label="Germany">Germany</option>
            <option value="GI" label="Gibraltar">Gibraltar</option>
            <option value="GR" label="Greece">Greece</option>
            <option value="GG" label="Guernsey">Guernsey</option>
            <option value="HU" label="Hungary">Hungary</option>
            <option value="IS" label="Iceland">Iceland</option>
            <option value="IE" label="Ireland">Ireland</option>
            <option value="IM" label="Isle of Man">Isle of Man</option>
            <option value="IT" label="Italy">Italy</option>
            <option value="JE" label="Jersey">Jersey</option>
            <option value="LV" label="Latvia">Latvia</option>
            <option value="LI" label="Liechtenstein">Liechtenstein</option>
            <option value="LT" label="Lithuania">Lithuania</option>
            <option value="LU" label="Luxembourg">Luxembourg</option>
            <option value="MK" label="Macedonia">Macedonia</option>
            <option value="MT" label="Malta">Malta</option>
            <option value="FX" label="Metropolitan France">Metropolitan France</option>
            <option value="MD" label="Moldova">Moldova</option>
            <option value="MC" label="Monaco">Monaco</option>
            <option value="ME" label="Montenegro">Montenegro</option>
            <option value="NL" label="Netherlands">Netherlands</option>
            <option value="NO" label="Norway">Norway</option>
            <option value="PL" label="Poland">Poland</option>
            <option value="PT" label="Portugal">Portugal</option>
            <option value="RO" label="Romania">Romania</option>
            <option value="RU" label="Russia">Russia</option>
            <option value="SM" label="San Marino">San Marino</option>
            <option value="RS" label="Serbia">Serbia</option>
            <option value="CS" label="Serbia and Montenegro">Serbia and Montenegro</option>
            <option value="SK" label="Slovakia">Slovakia</option>
            <option value="SI" label="Slovenia">Slovenia</option>
            <option value="ES" label="Spain">Spain</option>
            <option value="SJ" label="Svalbard and Jan Mayen">Svalbard and Jan Mayen</option>
            <option value="SE" label="Sweden">Sweden</option>
            <option value="CH" label="Switzerland">Switzerland</option>
            <option value="UA" label="Ukraine">Ukraine</option>
            <option value="SU" label="Union of Soviet Socialist Republics">Union of Soviet Socialist Republics</option>
            <option value="GB" label="United Kingdom">United Kingdom</option>
            <option value="VA" label="Vatican City">Vatican City</option>
            <option value="AX" label="Åland Islands">Åland Islands</option>
        </optgroup>
        <optgroup id="country-optgroup-Oceania" label="Oceania">
            <option value="AS" label="American Samoa">American Samoa</option>
            <option value="AQ" label="Antarctica">Antarctica</option>
            <option value="AU" label="Australia">Australia</option>
            <option value="BV" label="Bouvet Island">Bouvet Island</option>
            <option value="IO" label="British Indian Ocean Territory">British Indian Ocean Territory</option>
            <option value="CX" label="Christmas Island">Christmas Island</option>
            <option value="CC" label="Cocos [Keeling] Islands">Cocos [Keeling] Islands</option>
            <option value="CK" label="Cook Islands">Cook Islands</option>
            <option value="FJ" label="Fiji">Fiji</option>
            <option value="PF" label="French Polynesia">French Polynesia</option>
            <option value="TF" label="French Southern Territories">French Southern Territories</option>
            <option value="GU" label="Guam">Guam</option>
            <option value="HM" label="Heard Island and McDonald Islands">Heard Island and McDonald Islands</option>
            <option value="KI" label="Kiribati">Kiribati</option>
            <option value="MH" label="Marshall Islands">Marshall Islands</option>
            <option value="FM" label="Micronesia">Micronesia</option>
            <option value="NR" label="Nauru">Nauru</option>
            <option value="NC" label="New Caledonia">New Caledonia</option>
            <option value="NZ" label="New Zealand">New Zealand</option>
            <option value="NU" label="Niue">Niue</option>
            <option value="NF" label="Norfolk Island">Norfolk Island</option>
            <option value="MP" label="Northern Mariana Islands">Northern Mariana Islands</option>
            <option value="PW" label="Palau">Palau</option>
            <option value="PG" label="Papua New Guinea">Papua New Guinea</option>
            <option value="PN" label="Pitcairn Islands">Pitcairn Islands</option>
            <option value="WS" label="Samoa">Samoa</option>
            <option value="SB" label="Solomon Islands">Solomon Islands</option>
            <option value="GS" label="South Georgia and the South Sandwich Islands">South Georgia and the South Sandwich Islands</option>
            <option value="TK" label="Tokelau">Tokelau</option>
            <option value="TO" label="Tonga">Tonga</option>
            <option value="TV" label="Tuvalu">Tuvalu</option>
            <option value="UM" label="U.S. Minor Outlying Islands">U.S. Minor Outlying Islands</option>
            <option value="VU" label="Vanuatu">Vanuatu</option>
            <option value="WF" label="Wallis and Futuna">Wallis and Futuna</option>
        </optgroup>
    </select> <!--from freeodecamp kolade chris html selecttag for a dropdown menu or combo list, countries https://stackoverflow.com/questions/53388003/select-country-dropdown-in-html-page  closed-->
     <input type="submit" value="submit">
     <script>  /* we have form to enter input and select it we even have action attr and input type submit to choose and submit, but we dont want it sending to a different page we want it here just within the same html file, dues to Ishan shah solution 6 codeproject.com (I want to display form data on same page aausing javascript)*/
     function temp() {
       var strTxt = document.getElementById("selectcountriesid").value;
       /* var strTxt2 = document.getElementById("selectcountriesemail").value; supposing you have more values right, thi s is reading the id's reference or value */
       //document.getElementById("paratodisplayselectinputs").innerHTML = strTxt; // ITS JUST THIS INNER HTML I DONT KNOW MUCH I THOUGH WE SHOULD APPEND, LETS MAKE THAT PARAGRAPH
       //step7 comment       var childele = document.createTextNode(strTxt); //SINCE WE CAN PUT ONCLICK NOT ONLY ON A BUTTON WE WILL PUT ONCLICK ON THIS CHILD NODES, BY SETTING ATTRIBUTES
       // step6 comment this out       document.getElementById("paratodisplayselectinputs").appendChild(childele); /*= strTxt;*/ //let us use append instead of innerelement so that we can unappend and hav a more controlled scenen like even to set attributes after createElement etc. from delstack website  
       var childelediv = document.createElement("div"); //step1 since createtextnode cannot carry onlclick let us make this div with onlcick and append the txt to it, 
       childelediv.setAttribute('id', 'divchildren'); // step2 set its att make onclick too
       childelediv.setAttribute('onclick', 'untemp()');
       childelediv.setAttribute('draggable', 'true');
       childelediv.setAttribute('class', 'divchildrenc');

       childelediv.setAttribute('disabled', '');   
       //childelediv.style.backgroundColour = 'salmon';
       //childelediv.style.color = 'transparent';
       childelediv.style.width = '150px';
       childelediv.style.height = '150px';
       childelediv.style.borderBlockStyle = '150px';
       childelediv.style.borderRadius = '19px 2px 19px 2px';  // remember in styles first comes height and with, colours then the bpsm
       childelediv.textContent = strTxt;
       var divchild = childelediv;/*.appendChild(childele)*/ // step3 the txt should have no p joing the div     step 8 finally was to then not add the append statement i just removed in step    
       //document.getElementById("paratodisplayselectinputs").appendChild(childelediv); // step4 comment out this working textnode append 
       document.getElementById("paratodisplayselectinputs").appendChild(divchild); // step5 lets now put divchild instead and go and block that step 6 up, the last of their earlier steps 
      }
                   function untemp(){   // let us have  a func to unappend                     
                    document.getElementById("divchildren").remove(); 
                  }

//      var movable = document.getElementById("sortable");            ORIGINAL
var premovable = document.getElementById("divchildren");   //this code ewould have worked if we had a list or collection, all we have to reference is movavle a div among sibling divs, or their parent container, they need to be iterable so that ... meaning just becus they are siblings doesnt mean they are autoomatically iterable we need an array or loop     
var movable = document.querySelectorAll("divchildrenc"); //to achieve a collection we may or may not make this movable, which is a list now. and it is possible to group sibling nodes this way 
var draggedItem = null; 





// looping conv 3 Braveai  function dragdoings(){
//Array.prototype.map.call(movable, (item)=> {
//  enableDragList(item)
//});
//} i.e

function enableDragSort(movable) {
  const sortableLists = document.getElementsByClassName("divchildrenc");
  Array.prototype.map.call(sortableLists, (list) => {
    enableDragList(list);
  });
}

function enableDragList(list) {
  Array.prototype.map.call(list.children, (item) => {
    enableDragItem(item);
  });
}

function enableDragItem(item) {
  item.setAttribute('draggable', true);
  item.ondrag = handleDrag;
  item.ondragend = handleDrop;
}

function handleDrag(item) {
  const selectedItem = item.target,
        list = selectedItem.parentNode,
        x = event.clientX,
        y = event.clientY;
  
  selectedItem.classList.add('drag-sort-active');
  let swapItem = document.elementFromPoint(x, y) === null ? selectedItem : document.elementFromPoint(x, y);
  
  if (list === swapItem.parentNode) {
    swapItem = swapItem !== selectedItem.nextSibling ? swapItem : swapItem.nextSibling;
    list.insertBefore(selectedItem, swapItem);
  }
}

function handleDrop(item) {
  item.target.classList.remove('drag-sort-active');
}

(() => {
  enableDragSort('drag-sort-enable');
})();

//*/
 





//looping conv 2 CodingNepal drag and drop sortable list
/*
var sortableList = document.getElementById("paratodisplayselectinputs").innerHTML;
var items = sortableList.querySelectorAll("divchildrenc");

items.forEach(item => {
  item.setAttribute('draggable', 'true');
    item.addEventListener("dragstart", () => {
        // Adding dragging class to item after a delay
        setTimeout(() => item.classList.add("dragging"), 0);
    });
    // Removing dragging class from item on dragend event
    item.addEventListener("dragend", () => item.classList.remove("dragging"));
});

 var initSortableList = (e) => {
    e.preventDefault();
    const draggingItem = document.querySelector(".dragging");
    // Getting all items except currently dragging and making array of them
    let siblings = [...sortableList.querySelectorAll(".item:not(.dragging)")];

    // Finding the sibling after which the dragging item should be placed
    let nextSibling = siblings.find(sibling => {
        return e.clientY <= sibling.offsetTop + sibling.offsetHeight / 2;
    });

    // Inserting the dragging item before the found sibling
    sortableList.insertBefore(draggingItem, nextSibling);
}

sortableList.addEventListener("dragover", initSortableList);
sortableList.addEventListener("dragenter", e => e.preventDefault());




const sortableList = document.querySelector(".sortable-list");
const items = sortableList.querySelectorAll(".item");

items.forEach(item => {
    item.addEventListener("dragstart", () => {
        // Adding dragging class to item after a delay
        setTimeout(() => item.classList.add("dragging"), 0);
    });
    // Removing dragging class from item on dragend event
    item.addEventListener("dragend", () => item.classList.remove("dragging"));
});

const initSortableList = (e) => {
    e.preventDefault();
    const draggingItem = document.querySelector(".dragging");
    // Getting all items except currently dragging and making array of them
    let siblings = [...sortableList.querySelectorAll(".item:not(.dragging)")];

    // Finding the sibling after which the dragging item should be placed
    let nextSibling = siblings.find(sibling => {
        return e.clientY <= sibling.offsetTop + sibling.offsetHeight / 2;
    });

    // Inserting the dragging item before the found sibling
    sortableList.insertBefore(draggingItem, nextSibling);
}

sortableList.addEventListener("dragover", initSortableList);
sortableList.addEventListener("dragenter", e => e.preventDefault());
*/

//*/



 




/* looping conv 4 

Codepen drag and drop sortables. 


let items = document.querySelectorAll('#items-list > li')

items.forEach(item => {
  $(item).prop('draggable', true)
  item.addEventListener('dragstart', dragStart)
  item.addEventListener('drop', dropped)
  item.addEventListener('dragenter', cancelDefault)
  item.addEventListener('dragover', cancelDefault)
})

function dragStart (e) {
  var index = $(e.target).index()
  e.dataTransfer.setData('text/plain', index)
}

function dropped (e) {
  cancelDefault(e)
  
  // get new and old index
  let oldIndex = e.dataTransfer.getData('text/plain')
  let target = $(e.target)
  let newIndex = target.index()
  
  // remove dropped items at old place
  let dropped = $(this).parent().children().eq(oldIndex).remove()

  // insert the dropped items at new place
  if (newIndex < oldIndex) {
    target.before(dropped)
  } else {
    target.after(dropped)
  }
}

function cancelDefault (e) {
  e.preventDefault()
  e.stopPropagation()
  return false
}
*/





/*
 looping conv 5
 Sorting with the help of HTML5 Drag'n'Drop API
Lebedev Konstantin 15/1/2015 Github

http://rubaxa.github.io/Sortable/


function sortable(rootEl, onUpdate) {
   var dragEl;
   
   // Making all siblings movable
   [].slice.call(rootEl.children).forEach(function (itemEl) {
       itemEl.draggable = true;
   });
   
   // Function responsible for sorting
   function _onDragOver(evt) {
       evt.preventDefault();
       evt.dataTransfer.dropEffect = 'move';
      
       var target = evt.target;
       if (target && target !== dragEl && target.nodeName == 'LI') {
           // Sorting
           rootEl.insertBefore(dragEl, target.nextSibling || target);
       }
   }
   
   // End of sorting
   function _onDragEnd(evt){
       evt.preventDefault();
      
       dragEl.classList.remove('ghost');
       rootEl.removeEventListener('dragover', _onDragOver, false);
       rootEl.removeEventListener('dragend', _onDragEnd, false);


       // Notification about the end of sorting
       onUpdate(dragEl);
   }
   
   // Sorting starts
   rootEl.addEventListener('dragstart', function (evt){
       dragEl = evt.target; // Remembering an element that will be moved
       
       // Limiting the movement type
       evt.dataTransfer.effectAllowed = 'move';
       evt.dataTransfer.setData('Text', dragEl.textContent);


       // Subscribing to the events at dnd
       rootEl.addEventListener('dragover', _onDragOver, false);
       rootEl.addEventListener('dragend', _onDragEnd, false);


       setTimeout(function () {
           // If this action is performed without setTimeout, then
           // the moved object will be of this class.
           dragEl.classList.add('ghost');
       }, 0)
   }, false);
}
                       
// Using                    
sortable(document.getElementById('list'), function (item) {
   console.log(item);
});


As it may be noticed from the code, the whole sorting process consists of simple movement of the dragged element by means of rootEl.insertBefore(dragEl, target.nextSibling || target), where target is an element that was targeted. If you have already tested the example, you must have noticed that it is impossible to move an element to the first position. One more peculiarity of this method is that onUpdate is called each time, even if the element was not moved.

  In order to fix the first problem, all we have to do is to add testing during sorting. It is necessary to insert an element after target.nextSibling only in case it is not the first element of the list:  ... Check the site

import the module and use like this

// Simple list, e.g. ul > li
var list = document.getElementById("my-ui-list");
new Sortable(list); // That's all.


// Grouping
var foo = document.getElementById("foo");
new Sortable(foo, { group: "omega" });

var bar = document.getElementById("bar");
new Sortable(bar, { group: "omega" });


// handle + event
var container = document.getElementById("multi");
new Sortable(container, {
 handle: ".tile__title", // css-selector, which can be used to drag
 draggable: ".tile", // css-selector of elements, which can be sorted
 onUpdate: function (/**Event*/ // uncomment this to work as codedevt){
//uncomment this to work  like coded    var item = evt.item; // a link to an element that was moved
// uncomment this to work as coded }
// uncomment this to work as coded});












/* looping conv 1 geek for geeks create a drag and drop sortable list using html css js
 movable.addEventListener(
    "dragstart",
    (e) => {
        draggedItem = e.target;
        setTimeout(() => {
            e.target.style.display =
                "none";
        }, 0);
});
 
movable.addEventListener(
    "dragend",
    (e) => {
        setTimeout(() => {
            e.target.style.display = "";
            draggedItem = null;
        }, 0);
});
 
movable.addEventListener(
    "dragover",
    (e) => {
        e.preventDefault();
        const afterElement =
            getDragAfterElement(
                movable,
                e.clientY);
        const currentElement =
            document.querySelector(
                ".dragging");
        if (afterElement == null) {
            movable.appendChild(
                draggedItem
            );} 
        else {
            movable.insertBefore(
                draggedItem,
                afterElement
            );}
    });
 
const getDragAfterElement = (
    container, y
) => {
    const draggableElements = [
        ...container.querySelectorAll(
            "li:not(.dragging)"
        ),];
 
    return draggableElements.reduce(
        (closest, child) => {
            const box =
                child.getBoundingClientRect();
            const offset =
                y - box.top - box.height / 2;
            if (
                offset < 0 &&
                offset > closest.offset) {
                return {
                    offset: offset,
                    element: child,
                };} 
            else {
                return closest;
            }},
        {
            offset: Number.NEGATIVE_INFINITY,
        }
    ).element;
};*/


     </script> <!-- END OF JSinterpreted question we now that paragraph-->
     <div id="paratodisplayselectinputs" class="paraclass" draggable="true"> </div> <!-- we will either upgrade the button adding an onclick with this our temp function onclick ="temp()" or we can chooseto put it in the action -->  
    </form>
  </div>

</div> <!-- End of main container-->
      
  


<!--
<script src="chrome-extension://fheoggkfdfchfphceeifdbepaooicaho/scripts/page_crypto_mining.js" id="SCRIPT_46a2870c-afcf-47e5-b32e-1fd85ed6e398" randuuid="25b16cea-7adb-4944-846f-b9f5a4a3486d" type="text/javascript" mc_processed="1"></script></body></html>
-->

<!--

    Certainly! Here's a simple HTML code for your described form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
Certainly! Here's a simple HTML code for your described form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: white;
      color: blue;
      text-align: center;
    }
    #login-form {
      margin: 20px;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      display: inline-block;
    }
    input {
      margin: 10px;
      padding: 5px;
    }
  </style>
  <title>Login Form</title>
</head>
<body>
  <h1>Welcome! How can we help you?</h1>
  <img src="your_image_url_here" alt="Your Image" width="100">
  <div id="login-form">
    <p>Login with your credentials, please.</p>
    <form id="loginForm">
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" placeholder="Enter your username" onchange="handleInputChange()">
      <br>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" onchange="handleInputChange()">
    </form>
    <button id="loginButton" onclick="login()">Login</button>
  </div>
  <button id="registerButton">Register</button>

  <script>
    function handleInputChange() {
      // Add your logic for handling input changes here
    }

    function login() {
      // Add your login logic here
    }
  </script>
</body>
</html>
```

Make sure to replace `"your_image_url_here"` with the actual URL of your image. This code includes a basic structure for your requirements with blue text on a white background, a login form with username and password inputs, and a login button. It also includes a register button without functionality. You can add your logic inside the `handleInputChange` and `login` functions.
  
some button rules

.button{
    display : inline-block;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    text-align: center;
    text-decoration : none;
    cursor : pointer;
    border:none;
    border-radius:5px;
    transition: background-color 0.3s ease-in-out, color 0.3s ease-in-out; 
}

.promary-button{
    background-color :#2ecc71;
    color: #fff;
}

.promary-button{
    background-color :#3498db;
    color: #fff;
}

.button:hover{
    background-color :#2980b9;
    color: #fff;
}

<button class= "button primary-button"> Login</button>
<button class= "button secondary-button"> Register</button>
-->
























<!--
0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000




import React from 'react';
import { useState, useEffect } from 'react';
import mongoose from 'mongoose';
import { Navigate, NavLink, Link, useParams, useLocation, useMatch} from 'react-router-dom';
//import DeleteUser from './DeleteUser';  // Import the DeleteUser component (adjust the path accordingly)
//import { response } from 'express';
import AdminDelete from './adminprofiledelete.js';
//import imageSrc from '../static/images/mi.png';
import './adminprofile.scss';



export default function AdminProfile({ match }) {

  const [admin, setadmin] = useState({});
  const [redirectToSignin, setRedirectToSignin] = useState(false);
  const[values, setValues] = useState({followId: admin, following: null});
  //const[photo, setPhoto] = useState([]);  // comment here if dont think they set state for photo strings
  //const [images, setImages] = useState("");
  let adminIdo = useParams();       // remember params you can use it to retrieve route path endpoints parameters (adminid, js2students) from the component of that same react router.
  let adminId = adminIdo.adminid || adminIdo?.adminid?.toString();
  /* const match = useMatch();
  let adminIdOb = (adminId);
  let adminIdString = new mongoose.Types.ObjectId(adminIdOb); 
  const location = useLocation();
  */ 
  let followId;
/*  let imagee;

  let bufferToBase64 = (buffer) =>{  // The photo state is now an array of strings representing image URLs.In this example, the bufferToBase64 function converts the buffer object to a Base64-encoded string, and this string is then set in the photo state. The img tag can render this Base64-encoded string as an image. Make sure to adjust the logic based on the actual structure of your photo data.
    if (!buffer) {   
         return null
         ;}// comment this line out to know if db is sending some imag bufer.
    binary = Buffer.from(buffer).toString('base64');
   return `data:image/jpeg;base64,${binary}`;
 }
 bufferToBase64();
*/


/*
const bytecharacters = atob(result);
const bytenumbers = new array(bytecharacters.length.length);
for (let i = 0; i < bytecharacters.length; i++);
bytenumbers[i]= bytecharacters.charCodeAt(i);

const bytearray = new Uint8Array(bytenumbers);
let profilepics = new blob([bytearray], {type : 'image/jpeg'});

let profilepicsurl = url.createobjecturl(profilepics);
setImages(profilepicsurl);
*/  

  const Admin = async (adminId, /*{ adminIdString, },*/ data, signal) => {                     // this would have been abstracted into a class loadData.
    //let data;                    // qq or data;
    //console.log(adminIdString);

    try {
      const response = await fetch(`http://localhost:8080/admins/${adminId}`, {     ///* ...mins/ +params.adminid */    so let us assume you open a profile componenet of your, or ${adminid}
        method: 'GET',          // sister in a lower class like js1, the url will reflect here id param, the component will fetch and in students/studentsjs2/checkforthatpara
        signal: signal,
        headers: {
          'Accept': 'application/json',
          'Content-Type': 'application/json',
          //'Authorization': 'Bearer ' + /*credentials.t */ isAuthenticated().token,
        }
      });
      if (response.ok) {
        data = await response.json();    // also const user = response.json();     // qq or let data = await respon..         
        setadmin(data); 
        console.log('admin data', admin);
        followId = admin.adminId;
       
       /*
        const base64Image = bufferToBase64(data.photo); // Assuming data.photo is the buffer object
        setPhoto(base64Image ? [base64Image] : ['1','2','3']);  
        console.log('this is our state  photo', photo || photo.photoUrll);
        imagee = Object.values(photo);
        setImages(imagee);
        console.log(imagee); */
         //setadmin(data);
      }/*else*/

             
      
      
      //let photoUrll = admin.adminId ? admin.photo || `http://localhost:8080/admins/${adminId.photo}`/*?${new Date().getTime()}`*/ : '/api/users/defaultphoto';
      //setPhoto([photoUrll]);  i dont think we use set state on photo string.

      const checkFollow = (followId) => {                //checkfollow holds followId data, whether followId is been folloqwd or not.
        //followId = Admin.data;
        console.log('check to see if this followId is getting any news',  followId); 
          const match = followId.followers.some((follower)=> {         //chane these to the profile owner params followid has a follwer you asin isauthenticated.token.adminId 
          return follower._id == /*isAuthenticated().token.AdminId || */ "655ddf86df1e6afb62b0dc54"                                                                       // to check if you are already folowing that user followid params
          })
          return match
          }
      
      let following = checkFollow(followId); //to cut the long story short following is true/match returned if isauthenticated.current id is found among user (followId) followers, meaning curent user is following followId 
      
          
      setValues({...values, followId: admin, following: following});  // so following initially is set to following, based on checkfollow following is a boolean, by match it is either true or false. data is

      function handlefollowprofilebuttonchange (callApi /*follow, unfollow*/)  {           //we can call this 
        callApi({currentId:/* isAuthenticated.token.adminId || */"655ddf86df1e6afb62b0dc54" }, {token: /*isAuthenticated.token ||*/ ""}, values.followId).then((data) => {   //thi could be values.adminId
                 if (data.error) {
                     setValues({...values, error: data.error})   // if for some reason the wires didnt collect current from be route to access current user adminId to get following list
                   } else { setValues({...values, followId: admin, following: !values.following})}})};   // if we reached the current users following , we turn following in the state is set to 
                   handlefollowprofilebuttonchange();            
       //      follow({followId : adminId , ThefollowerId : isAuthenticated().token.AdminId} )}
       
       /*{isAuthenticated().token.adminId && // admin or Administrator              // cant display follow for your own profile. if an authenticated admin and which is you is the same asa the value object's adminId possibly not followId
        isAuthenticated().token.admin == values.followId // this may be adminId
        ? (edit and delete buttons)
        : (follow button)
       }*/
       
       
    } catch(err) {
        console.log(err)
        }
    }



    

///////////////////////////////////////////////Follow and unfollow profile section   //////////////////////////////////////////////////////////////////                                 /////////////////////


const follow = async (followId) => {
  try {
  let response = await fetch(`http://localhost:8080/admins/${adminId}`, {
  method: 'PUT',
  headers: {
  'Accept': 'application/json',
  'Content-Type': 'application/json',
  //'Authorization': 'Bearer ' + isAuthenticated().token,
  },
  body: JSON.stringify({followId : adminId, ThefollowerId : /*isAuthenticated().token.AdminId || new ObjectId(*/ "655ddf86df1e6afb62b0dc54"})
  })
  return await response.json()
  } catch(err) {
  console.log(err)
  }
 }


 const unfollow = async (unfollowId) => {
  try {
  let response = await fetch(`http://localhost:8080/admins/${adminId}`, {
  method: 'PUT',
  headers: {
  'Accept': 'application/json',
  'Content-Type': 'application/json',
  //'Authorization': 'Bearer ' + isAuthenticated().token,
  },
  body: JSON.stringify({unfollowId : adminId, TheunfollowerId : /*isAuthenticated().token.AdminId || new ObjectId(*/ "655ddf86df1e6afb62b0dc54"})
  })
  return await response.json()
  
} catch(err) {
  console.log(err)
  }
 } 
    




useEffect(() => {
  const abortController = new AbortController(); 
  const signal = abortController.signal; 
  //let data = Admin.data
  console.log("useeffect data", data);
  //const isAuthenticated = isAuthenticated();

  function isAuthenticated() {
    if (typeof window == "undefined")
    return false
    if (localStorage.getItem('token'))
    return JSON.parse(localStorage.getItem('token'))
    else if (!localStorage.getItem('token'))
    return new ObjectId("655ddf86df1e6afb62b0dc54")
    else
    return false
   }
   isAuthenticated();


  Admin(adminId,  /*{ t: isAuthenticated.token  } ,*/  data, signal ).then(data => {    // or you can say admin= response.json(), admin.id = match.params.adminid, admin.t ... this.setState(user or admin);
    //data = Admin.data
    if (!data /*&& data.error*/) { setRedirectToSignin(true);
       console.log('ERROR WITH USEEFFECT DATA');    
      } else {  
        setadmin(data); 
        console.log('THIS IS YOUR ADMINS,', admin)}})//  if its not authenticated or no id go back or so, otherwise setUser or this.setState(user)
  return function cleanup(){  abortController.abort() }                      // i just ealises this fuunction clean up, is like the outer setState to default also, maybe this one is better.
  }, [adminId])    //or adminId

  
//  follow({followId : adminId , ThefollowerId : /*isAuthenticated().token.AdminId || */ new ObjectId("655ddf86df1e6afb62b0dc54")} );
  
// Pause these for now call api or so is supposed to do this work, mayeb even followP Profile follow({followId : adminId , ThefollowerId : /*isAuthenticated().token.AdminId || */ "655ddf86df1e6afb62b0dc54"} ), unfollow({unfollowId : adminId}, {TheunfollowerId : /*isAuthenticated().token.AdminId ||*/ "655ddf86df1e6afb62b0dc54"});
/*
TypeError: Failed to execute 'fetch' on 'Window': Failed to read the 'signal' property from 'RequestInit': Failed to convert value to 'AbortSignal'.
at _callee$ (adminprofile.js:53:20)
at tryCatch (adminprofile.js:10:1062)
*/

//console.log('check to see if this data is getting any news', admin);
                                            


function FollowProfileButton (/*props.*/) { //When FollowProfileButton is added to the profile, the following value will be determined and sent from the Profile component as a prop to FollowProfileButton,
        
        ///*props.*/onButtonClick(follow)    ALL THESE COMMENTED CODE IS OR IF THE BUTTON AND FOLLOW SEMS ARE IN A CHILD COMPONENT
        ///*props.*/onButtonClick(unfollow)

        const followClick = () => {  //props i used here when it is a child componenet, but we will put them in manually
        /*onClick = () => {
          follow;
        }
        onClick();*/
        follow
        }
       followClick();
        
        const unfollowClick = () => {
        /*onClick = () => {
          unfollow;
        }
        onClick();*/
        unfollow
      }
        unfollowClick(); 
//followClick(follow);
//unfollowClick(unfollow);       
        
        /*return (<div> { /*props.following ? (<button variant="contained" color="secondary" onClick={unfollowClick}>Unfollow</button>)
        : (<button variant="contained" color="primary" onClick={followClick}>Follow</button>) } </div>)*/   // this is going to the render or hydrate
   }
   FollowProfileButton();
   





///////////////////////////////////////////////Follow and unfollow profile section  end //////////////////////////////////////////////////////////////////                                 /////////////////////

/*         function authenticate (token, cb) { 
                if(typeof window !== "undefined")
                localStorage.setItem('token', JSON.stringify(token))
                cb;
            }
            authenticate();


            //Recieving, In our frontend components, we will need to retrieve the stored credentials to check if the current user is signed in. In the isAuthenticated() method, we can retrieve these credentials from localStorage.
             function isAuthenticated() {
                if (typeof window == "undefined")
                return false
                if (localStorage.getItem('token'))
                return JSON.parse(localStorage.getItem('token'))
                else
                return false
               }
               isAuthenticated();
               

             //To clear the jwt Credential from storage
             function ClearJWT (cb) {
                if (typeof window !== "undefined") {
                  // Remove JWT token from localStorage
                  localStorage.removeItem('token');
                  
                  // Clear the cookie
                  document.cookie = "t=; expires=Thu, 01 Jan 1970 00:00:00 UTC; path=/;";
              
                  // Invoke the callback
                  cb;
                  
                }
              }ClearJWT();
*/




              return (
                <div className="profile-container">  
                  <div className="profile-header">
                  (<div>
                  {/*isAuthenticated().token.adminId*/ "655ddf86df1e6afb62b0dc54" && /*isAuthenticated().token.admin*/ true == values.followId   ? {/*(edit and delete buttons)*/} : {/*(follow button)*/}}
                  { values.following == true ? (<button variant="contained" color="secondary" onClick={FollowProfileButton.unfollowClick}>Unfollow</button>) : (<button variant="contained" color="primary"
                  onClick={FollowProfileButton.followClick}>Follow</button>) }</div>)

                  {/*photoUrl = /*values.user._id*/ /*adminId ? `http://localhost:8080/admins/${/*values.user._id*//*adminId.photo}?${new Date().getTime()}`: '/api/users/defaultphoto'*/}
                  {/*photoUrl = /*values.user._id*/ /*admin._id ? `http://localhost:8080/admins/${adminId.photo}?${new Date().getTime()}`: '/api/users/defaultphoto'*/}
                    <h6>Profile</h6>
                  </div>
                  <ul className="profileunordered-list">
                    <li>
                      <div className="avatar">
                      {/*typeof images === 'string' ? <img srcData={/*photo[0]*/ /*`data:image/jpeg;base64,${[images]}` }/> : null*/}
                      {/*photo && photo.map((photon, index) => (  <img key={index}*/ /*img srcData={photo[0]}*/ /*{photo ? photo[0] : '/path/to/placeholder.png'}*/ /*src={photoUrll}*/ /*srcData={photon} alt={`Profile of ${admin.username}`} />))*/ /**/}
                      {/*<img src={photo} alt={`Profile of ${admin.username}`} />*/ /*[photo] ? <img src={`data:image/jpeg;base64,${[photo]}`}/> : null */}
                      { /*[images] && [images].map((images, index => ( <img key={index} width={100} height = {100}  src={`data:image/jpeg;base64,${[images]}`}/>)*/ /*: null*/ /*))*/ }
                      </div>
                      <div className="user-info">
                        <p>{admin.username}</p>
                       <p>Email: {admin.email}</p>
                      </div>
                    </li>
                    <li className="joined-info">
                      <p>Joined: {new Date(admin.created).toDateString() || ''}</p>
                    </li>

                    {/*auth.isAuthenticated().user && auth.isAuthenticated().user._id === user._id && (*/}
                      <li className="edit-delete-actions">
                        <Link to={`/admins/adminedit/${admin._id}`}>
                          <button>Edit</button>
                        </Link>
                        <AdminDelete adminId={admin._id} />  {/*'instead of this do the below link and when you use this one the admindelete component wont need to be route and fetch'*/}
                        {/*<Link to={`/admins/admindelete/${admin._id}`}>
                          <button>Delete</button>
                      </Link>*/}
                      </li>
                    {/*})*/}
                  </ul>
                </div>
              );
               


            }            

               

            useEffect(() => {
              const abortController = new AbortController();
              const signal = abortController.signal;
              //let data = Admin.data
              //console.log("useeffect data", data); paused 8th mar 24
              //const isAuthenticated = isAuthenticated();
          
              /*  function isAuthenticated() {
                  ObjectId = import 'mongodb'.ObjectId;
                  if (typeof window == "undefined")
                  return false
                  if (localStorage.getItem('token'))
                  return JSON.parse(localStorage.getItem('token'))
                  else if (!localStorage.getItem('token'))
                  
                  return new ObjectId("655ddf86df1e6afb62b0dc54")
                  else
                  return false
                 }
                 isAuthenticated();*/   //PAUSE THIS FUNCTION NOW TO MUSE IMPOTEANTLY SOON
          
          
          
              
              const Admin = async (adminId, /*{ adminIdString, },*/  signal) => {                     // this would have been abstracted into a class loadData.
                //let response                  // qq or data;
                // console.log(adminIdString);
          
                try {
                  const response = await fetch(`http://localhost:8080/admins/${adminId}`, {      //   /* ...mins/ +params.adminid */  //11th march 2024  so let us assume you open a profile componenet of your, or ${adminid}
                    method: 'GET',         // sister in a lower class like js1, the url will reflect here id param, the component will fetch and in students/studentsjs2/checkforthatpara
                    signal: signal,
                    headers: {
                      'Accept': 'application/json',
                      'Content-Type': 'application/json',
                      //'Authorization': 'Bearer ' + /*credentials.t */ // 11th march 2024 isAuthenticated().token,
                    }
                  })
                } catch (err) {
                  console.error(err, `err fetching data`)
          
              }};
          
          
          
          
          
          
                Admin(adminId, /*{ t: isAuthenticated.token  } ,*/   signal).then(response => {    // or you can say admin= response.json(), admin.id = match.params.adminid, admin.t ... this.setState(user or admin);
                  //data = Admin.data
                  response = Admin.response;
                  if (! response || jsonData || blob /*&& data.error*/) {
                    setRedirectToSignin(true);
                    console.log('ERROR WITH USEEFFECT DATA');
          
                  } else {
          
                    //new section
                    if (response.ok) {
                      console.log("esponse is ok");
          
                      const contentType = response.headers.get('Content-Type');
                      if (contentType && contentType.includes('application/json')) {
                        jsonData = response.json();
                        //consile.log('RECEIVED JSON DATA:', jsonData); move these to useeffect
                        //setadmin(jsonData);  move these to useeffect
                      } else if (contentType && contentType.includes('image')) {
                        blob = response.blob();
                        imageUrl = URL.createObjectURL(blob);
                        //setPhoto([/*base64Image*/ imageUrl]);  move these to useeffect
          
                      } else {
                        console.error("Unexpected contenttype error", contentType);
                      }
                    } else {
                      console.error('Respponse not ok', response)
                    };
                    //followId = admin.adminId;     move these to effect admin
                    //console.log('this is followid', followId);  move this to effect admin
          
                    //end of new section
                    setadmin(jsonData);
                    setPhoto([/*base64Image*/ imageUrl]);
                    followId = admin.adminId;
                    console.log('this is followid', followId);
                    console.log('THIS IS YOUR ADMINS,', admin)
                  }
                });
          
                //  if its not authenticated or no id go back or so, otherwise setUser or this.setState(user)
                return function cleanup() { 
                  abortController.abort()}                       // i just ealises this fuunction clean up, is like the outer setState to default also, maybe this one is better.
              }, [adminId]);     //or adminId
          

00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000


-->
