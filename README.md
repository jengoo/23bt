<!doctype html>
<head>
  <link href="css/bootstrap.min.css" rel="stylesheet">
  <script type= "text/javascript" src = "countries.js"></script>
  <script src="lib/jquery.js"></script>
  <script src="popup.js"></script>
  <title>Heated Sneaks 4IN1 Bot</title>   
</head>
<body style="background-image: url('img/pattern.jpg');">
    <div class="mainContainer form-horizontal" style="width:380px; margin:0 auto; ">						        
        <div class="formContainer form-group" style="background-color: #ffffff; padding-left:40px;">
            <div align="center" >
			    <hr style="height:5px;" class="col-sm-10" color="#af2004">
                <div class="col-sm-10">
                    <a href="http://HEATEDSNEAKS.COM/" target="_new">
						<img src="img/img.jpg" width= align="center">
					</a>
                </div>
				<hr style="height:5px;" class="col-sm-10" color="#af2004">
                <span align="center" class="col-sm-10"><h4 style="text-decoration: underline; font-weight: bold;">BASIC INFORMATION</h4></span>				
                <label class="col-sm-10">Shoes Size:</label> 
                <div class="col-sm-10">
                    <select name="shoesSize" id="shoesSize" class="size-dropdown form-control">
						<option name="skuId" value="05.0"> 5</option>
						<option name="skuId" value="05.5"> 5.5</option>
						<option name="skuId" value="06.0"> 6</option>
						<option name="skuId" value="06.5"> 6.5</option>
						<option name="skuId" value="07.0"> 7</option>
						<option name="skuId" value="07.5"> 7.5</option>
						<option name="skuId" value="08.0"> 8</option>
						<option name="skuId" value="08.5"> 8.5</option>
						<option name="skuId" value="09.0"> 9</option>
						<option name="skuId" value="09.5"> 9.5</option>
						<option name="skuId" value="10.0"> 10</option>
						<option name="skuId" value="10.5"> 10.5</option>
						<option name="skuId" value="11.0"> 11</option>
						<option name="skuId" value="11.5"> 11.5</option>
						<option name="skuId" value="12.0"> 12</option>
						<option name="skuId" value="12.5"> 12.5</option>
						<option name="skuId" value="13.0"> 13</option>
						<option name="skuId" value="13.5"> 13.5</option>
						<option name="skuId" value="14.0"> 14</option>
						<option name="skuId" value="14.5"> 14.5</option>
						<option name="skuId" value="15.0"> 15</option>
						<option name="skuId" value="15.5"> 15.5</option>
						<option name="skuId" value="16.0"> 16</option>
						<option name="skuId" value="16.5"> 16.5</option>
						<option name="skuId" value="17.0"> 17</option>
						<option name="skuId" value="17.5"> 17.5</option>
						<option value="" disabled=""></option>				
                    </select>
                </div><br/>				
                <label class="col-sm-10">Retry Delay:</label>
                <div class="col-sm-10">
                    <input type="text" name="keywords" id="timeout" class="form-control" placeholder="Enter time in milliseconds only.">
                </div><br/>				
                <label class="col-sm-10">Auto Checkout:</label>
                <div class="col-sm-10">
                    <select name="autocheckoutselect" id="autocheckoutselect" class="size-dropdown form-control">
						<option name="autocheckoutselectname" value="no" id="autocheckoutselect1" selected>No</option> 
						<option name="autocheckoutselectname" value="yes" id="autocheckoutselect2">Yes</option>               
                    </select>
                </div><br/>   				   
				<label class="col-sm-10">Checkout Type:</label>
				<div class="col-sm-10">
					<select name="checkoutType" id="checkoutType" class="size-dropdown form-control">
						<option name="checkoutTypeSelect" value="partial" id="checkoutType1" selected>AutoFill Only</option> 
						<option name="checkoutTypeSelect" value="complete" id="checkoutType2">Full Checkout</option>               
					</select>
				</div><br/> 					
				<label class="col-sm-10">Checkout Delay:</label>
				<div class="col-sm-10">
					<input type="text" name="checkoutDelay" id="checkoutDelay" class="form-control" placeholder="Enter Checkout Delay">
				</div>  <br/>  
				<label class="col-sm-10">Proxy Address:</label>
				<div class="col-sm-10">
					<input type="text" name="proxy" id="proxy" class="form-control" placeholder="Proxy IP:Port:Username:Password">
				</div>  <br/>
				<div class="col-sm-10">
                <label>Proxy Use?</label>			
				<input type="checkbox" name="proxyuse" id="proxyuse" > 	
                </div>			
				<span align="center" id="billingaddress" class="col-sm-10"><h4 style="text-decoration: underline; font-weight: bold;">BILLING ADDRESS</h4></span>
                <div id="billingaddressdiv">				
					<label class="col-sm-10">Country:</label>
					<div class="col-sm-10">
						<select id="billCountry" name="billCountry" class=" form-control">			
							<option value="AF">Afghanistan</option>           
							<option value="AS">American Samoa</option>           
							<option value="AD">Andorra</option>            
							<option value="AO">Angola</option>            
							<option value="AI">Anguilla</option>           
							<option value="AQ">Antarctica</option>            
							<option value="AG">Antigua and Barbuda</option>            
							<option value="AR">Argentina</option>            
							<option value="AM">Armenia</option>           
							<option value="AU">Australia</option>            
							<option value="AT">Austria</option>            
							<option value="AZ">Azerbaijan</option>            
							<option value="BH">Bahrain</option>            
							<option value="BD">Bangladesh</option>           
							<option value="BB">Barbados</option>          
							<option value="BE">Belgium</option>           
							<option value="BZ">Belize</option>           
							<option value="BJ">Benin</option>           
							<option value="BT">Bhutan</option>           
							<option value="BO">Bolivia</option>           
							<option value="BW">Botswana</option>           
							<option value="BV">Bouvet Island</option>           
							<option value="BR">Brazil</option>          
							<option value="IO">British Indian Ocean Territory</option>          
							<option value="VG">British Virgin Islands</option>         
							<option value="BN">Brunei</option>           
							<option value="BG">Bulgaria</option>          
							<option value="BI">Burundi</option>           
							<option value="KH">Cambodia</option>  
							<option value="CA">Canada</option>           
							<option value="KY">Cayman Islands</option>          
							<option value="TD">Chad</option>          
							<option value="CL">Chile</option>          
							<option value="CN">China</option>         
							<option value="CX">Christmas Island</option>
							<option value="CC">Cocos Islands</option>          
							<option value="CO">Colombia</option>
							<option value="KM">Comoros</option>
							<option value="CG">Congo</option>
							<option value="CK">Cook Islands</option>
							<option value="CU">Cuba</option>
							<option value="CY">Cyprus</option>
							<option value="CZ">Czech Republic</option>
							<option value="DK">Denmark</option>
							<option value="DJ">Djibouti</option>
							<option value="EC">Ecuador</option>
							<option value="SV">El Salvador</option>
							<option value="GQ">Equatorial Guinea</option>
							<option value="ER">Eritrea</option>
							<option value="ET">Ethiopia</option>
							<option value="FK">Falkland Islands</option>
							<option value="FO">Faroe Islands</option>
							<option value="FJ">Fiji</option>
							<option value="FI">Finland</option>
							<option value="FR">France</option>
							<option value="GF">French Guiana</option>
							<option value="PF">French Polynesia</option>
							<option value="TF">French Southern Territories</option>
							<option value="GA">Gabon</option>
							<option value="GE">Georgia</option>
							<option value="DE">Germany</option>
							<option value="GI">Gibraltar</option>
							<option value="GR">Greece</option>
							<option value="GL">Greenland</option>
							<option value="GD">Grenada</option>
							<option value="GP">Guadeloupe</option>
							<option value="GU">Guam</option>
							<option value="GN">Guinea</option>
							<option value="HM">Heard Island And McDonald Islands</option>
							<option value="HN">Honduras</option>
							<option value="HK">Hong Kong</option>
							<option value="HU">Hungary</option>
							<option value="IS">Iceland</option>
							<option value="IQ">Iraq</option>
							<option value="IE">Ireland</option>
							<option value="IL">Israel</option>
							<option value="IT">Italy</option>
							<option value="JP">Japan</option>
							<option value="KZ">Kazakhstan</option>
							<option value="KE">Kenya</option>
							<option value="KI1">Kiribati</option>
							<option value="KW">Kuwait</option>
							<option value="KG">Kyrgyzstan</option>
							<option value="LA">Laos</option>
							<option value="LV">Latvia</option>
							<option value="LS">Lesotho</option>
							<option value="LR">Liberia</option>
							<option value="LY">Libya</option>
							<option value="LI">Liechtenstein</option>
							<option value="LU">Luxembourg</option>
							<option value="MG">Madagascar</option>
							<option value="MW">Malawi</option>
							<option value="MV">Maldives</option>
							<option value="MT">Malta</option>
							<option value="MH">Marshall Islands</option>
							<option value="MQ">Martinique</option>
							<option value="MU">Mauritius</option>
							<option value="YT">Mayotte</option>
							<option value="MX">Mexico</option>
							<option value="FM">Micronesia</option>
							<option value="MC">Monaco</option>
							<option value="MS">Montserrat</option>
							<option value="MZ">Mozambique</option>
							<option value="MM">Myanmar</option>
							<option value="NA">Namibia</option>
							<option value="NR">Nauru</option>
							<option value="NP">Nepal</option>
							<option value="NL">Netherlands</option>
							<option value="AN">Netherlands Antilles</option>
							<option value="NC">New Caledonia</option>
							<option value="NZ">New Zealand</option>
							<option value="NI">Nicaragua</option>
							<option value="NU">Niue</option>
							<option value="NF">Norfolk Island</option>
							<option value="KP">North Korea</option>
							<option value="MP">Northern Mariana Islands</option>
							<option value="NO">Norway</option>
							<option value="OM">Oman</option>
							<option value="PW">Palau</option>
							<option value="PA">Panama</option>
							<option value="PG">Papua New Guinea</option>
							<option value="PY">Paraguay</option>
							<option value="PE">Peru</option>
							<option value="PH">Philippines</option>
							<option value="PN">Pitcairn</option>
							<option value="PL">Poland</option>
							<option value="PT">Portugal</option>
							<option value="PR">Puerto Rico</option>
							<option value="RE">Reunion</option>
							<option value="RO">Romania</option>
							<option value="RW">Rwanda</option>
							<option value="SH">Saint Helena</option>
							<option value="SM">San Marino</option>
							<option value="ST">Sao Tome And Principe</option>
							<option value="SA">Saudi Arabia</option>
							<option value="SS">Seychelles</option>
							<option value="SG">Singapore</option>
							<option value="SK">Slovakia</option>
							<option value="SB">Solomon Islands</option>
							<option value="SO">Somalia</option>
							<option value="ZA">South Africa</option>
							<option value="GS">South Georgia And The South Sandwich Islands</option>
							<option value="KR">South Korea</option>
							<option value="ES">Spain</option>
							<option value="LK">Sri Lanka</option>
							<option value="KN">Saint Kitts And Nevis</option>
							<option value="PM">Saint Pierre And Miquelon</option>
							<option value="SD">Sudan</option>
							<option value="SJ">Svalbard And Jan Mayen</option>
							<option value="SE">Sweden</option>
							<option value="CH">Switzerland</option>
							<option value="SY">Syria</option>
							<option value="TW">Taiwan</option>
							<option value="TJ">Tajikistan</option>
							<option value="TZ">Tanzania</option>
							<option value="TH">Thailand</option>
							<option value="TP">Timor-Leste</option>
							<option value="TG">Togo</option>
							<option value="TK">Tokelau</option>
							<option value="TO">Tonga</option>
							<option value="TT">Trinidad and Tobago</option>
							<option value="TR">Turkey</option>
							<option value="TM">Turkmenistan</option>
							<option value="TC">Turks And Caicos Islands</option>
							<option value="TV">Tuvalu</option>
							<option value="UM">United States Minor Outlying Islands</option>
							<option value="UG">Uganda</option>
							<option value="AE">United Arab Emirates</option>
							<option value="GB">United Kingdom</option>
							<option value="US">United States</option>
							<option value="UZ">Uzbekistan</option>
							<option value="VU">Vanuatu</option>
							<option value="VA">Vatican</option>
							<option value="VI">U.S. Virgin Islands</option>
							<option value="WF">Wallis And Futuna</option>
							<option value="EH">Western Sahara</option>
							<option value="WS">Samoa</option>
							<option value="YE">Yemen</option>
							<option value="ZR">Zaire</option>
							<option value="ZM">Zambia</option>
							<option value="ZW">Zimbabwe</option>                     
						</select>  
					</div> <br/>         
					<label class="col-sm-10">First Name:</label>
					<div class="col-sm-10">
						<input type="text" name="billFirstName" id="billFirstName" class="form-control" placeholder="Enter First Name">
					</div><br/>
					<label class="col-sm-10">Last Name:</label>
					<div class="col-sm-10">
						<input type="text" name="billLastName" id="billLastName" class="form-control" placeholder="Enter Last Name">
					</div><br/>
					<label class="col-sm-10">Street Address1:</label>
					<div class="col-sm-10">
						<input type="text" name="billStreetAddress1" id="billStreetAddress1" class="form-control" placeholder="Enter Street Address1">
					</div><br/>
					<label class="col-sm-10">Street Address2:</label>
					<div class="col-sm-10">
						<input type="text" name="billStreetAddress2" id="billStreetAddress2" class="form-control" placeholder="Enter Street Address2">
					</div><br/>
					<label class="col-sm-10">Zip Code:</label>
					<div class="col-sm-10">
						<input type="text" name="billZipCode" id="billZipCode" class="form-control" placeholder="Enter Zip Code">
					</div><br/>
					<label class="col-sm-10">City:</label>
					<div class="col-sm-10">
						<input type="text" name="billCity" id="billCity" class="form-control" placeholder="Enter City">
					</div><br/>
					<label class="col-sm-10">State:</label>
					<div class="col-sm-10">
						<select name="billState" id="billState" class="form-control">
							<option value="">Pick State</option>
							<optgroup label="United States">
								<option value="AL">Alabama</option>
								<option value="AK">Alaska</option>
								<option value="AS">American Samoa</option>
								<option value="AZ">Arizona</option>
								<option value="AR">Arkansas</option>
								<option value="AA">Armed Forces America</option>
								<option value="AE">Armed Forces Europe</option>
								<option value="AP">Armed Forces Pacific</option>
								<option value="CA">California</option>
								<option value="CO">Colorado</option>
								<option value="CT">Connecticut</option>
								<option value="DE">Delaware</option>
								<option value="DC">Dist Of Columbia</option>
								<option value="FL">Florida</option>
								<option value="GA">Georgia</option>
								<option value="GU">Guam</option>
								<option value="HI">Hawaii</option>
								<option value="ID">Idaho</option>
								<option value="IL">Illinois</option>
								<option value="IN">Indiana</option>
								<option value="IA">Iowa</option>
								<option value="KS">Kansas</option>
								<option value="KY">Kentucky</option>
								<option value="LA">Louisiana</option>
								<option value="ME">Maine</option>
								<option value="MH">Marshall Islands</option>
								<option value="MD">Maryland</option>
								<option value="MA">Massachusetts</option>
								<option value="MI">Michigan</option>
								<option value="FM">Micronesia, Federated States Of</option>
								<option value="MN">Minnesota</option>
								<option value="MS">Mississippi</option>
								<option value="MO">Missouri</option>
								<option value="MT">Montana</option>
								<option value="NE">Nebraska</option>
								<option value="NV">Nevada</option>
								<option value="NH">New Hampshire</option>
								<option value="NJ">New Jersey</option>
								<option value="NM">New Mexico</option>
								<option value="NY">New York</option>
								<option value="NC">North Carolina</option>
								<option value="ND">North Dakota</option>
								<option value="MP">Northern Mariana Islands</option>
								<option value="OH">Ohio</option>
								<option value="OK">Oklahoma</option>
								<option value="OR">Oregon</option>
								<option value="PW">Palau (Micronesia)</option>
								<option value="PA">Pennsylvania</option>
								<option value="PR">Puerto Rico</option>
								<option value="RI">Rhode Island</option>
								<option value="SC">South Carolina</option>
								<option value="SD">South Dakota</option>
								<option value="TN">Tennessee</option>
								<option value="TX">Texas</option>
								<option value="UM">U S Minor Outlying Islands</option>
								<option value="UT">Utah</option>
								<option value="VT">Vermont</option>
								<option value="VI">Virgin Islands Of The United States</option>
								<option value="VA">Virginia</option>
								<option value="WA">Washington</option>
								<option value="WV">West Virginia</option>
								<option value="WI">Wisconsin</option>
								<option value="WY">Wyoming</option>  
							</optgroup>
							<optgroup label="England">
								<option>Bedfordshire</option>
								<option>Berkshire</option>
								<option>Bristol</option>
								<option>Buckinghamshire</option>
								<option>Cambridgeshire</option>
								<option>Cheshire</option>
								<option>City of London</option>
								<option>Cornwall</option>
								<option>Cumbria</option>
								<option>Derbyshire</option>
								<option>Devon</option>
								<option>Dorset</option>
								<option>Durham</option>
								<option>East Riding of Yorkshire</option>
								<option>East Sussex</option>
								<option>Essex</option>
								<option>Gloucestershire</option>
								<option>Greater London</option>
								<option>Greater Manchester</option>
								<option>Hampshire</option>
								<option>Herefordshire</option>
								<option>Hertfordshire</option>
								<option>Isle of Wight</option>
								<option>Kent</option>
								<option>Lancashire</option>
								<option>Leicestershire</option>
								<option>Lincolnshire</option>
								<option>Merseyside</option>
								<option>Norfolk</option>
								<option>North Yorkshire</option>
								<option>Northamptonshire</option>
								<option>Northumberland</option>
								<option>Nottinghamshire</option>
								<option>Oxfordshire</option>
								<option>Rutland</option>
								<option>Shropshire</option>
								<option>Somerset</option>
								<option>South Yorkshire</option>
								<option>Staffordshire</option>
								<option>Suffolk</option>
								<option>Surrey</option>
								<option>Tyne and Wear</option>
								<option>Warwickshire</option>
								<option>West Midlands</option>
								<option>West Sussex</option>
								<option>West Yorkshire</option>
								<option>Wiltshire</option>
								<option>Worcestershire</option>
							</optgroup>
							<optgroup label="Wales">
								<option>Anglesey</option>
								<option>Brecknockshire</option>
								<option>Caernarfonshire</option>
								<option>Carmarthenshire</option>
								<option>Cardiganshire</option>
								<option>Denbighshire</option>
								<option>Flintshire</option>
								<option>Glamorgan</option>
								<option>Merioneth</option>
								<option>Monmouthshire</option>
								<option>Montgomeryshire</option>
								<option>Pembrokeshire</option>
								<option>Radnorshire</option>
							</optgroup>
							<optgroup label="Scotland">
								<option>Aberdeenshire</option>
								<option>Angus</option>
								<option>Argyllshire</option>
								<option>Ayrshire</option>
								<option>Banffshire</option>
								<option>Berwickshire</option>
								<option>Buteshire</option>
								<option>Cromartyshire</option>
								<option>Caithness</option>
								<option>Clackmannanshire</option>
								<option>Dumfriesshire</option>
								<option>Dunbartonshire</option>
								<option>East Lothian</option>
								<option>Fife</option>
								<option>Inverness-shire</option>
								<option>Kincardineshire</option>
								<option>Kinross</option>
								<option>Kirkcudbrightshire</option>
								<option>Lanarkshire</option>
								<option>Midlothian</option>
								<option>Morayshire</option>
								<option>Nairnshire</option>
								<option>Orkney</option>
								<option>Peeblesshire</option>
								<option>Perthshire</option>
								<option>Renfrewshire</option>
								<option>Ross-shire</option>
								<option>Roxburghshire</option>
								<option>Selkirkshire</option>
								<option>Shetland</option>
								<option>Stirlingshire</option>
								<option>Sutherland</option>
								<option>West Lothian</option>
								<option>Wigtownshire</option>
							</optgroup>
							<optgroup label="Northern Ireland">
								<option>Antrim</option>
								<option>Armagh</option>
								<option>Down</option>
								<option>Fermanagh</option>
								<option>Londonderry</option>
								<option>Tyrone</option>
							</optgroup>							
						</select> 
					</div> <br/>           
					<label class="col-sm-10">Phone :</label><p>
					<div class="col-sm-10">
						<input type="text" name="billPhone" id="billPhone" class="form-control" placeholder="Enter Phone Number">
					</div><br/>
					<label class="col-sm-10">Email Address:</label>
					<div class="col-sm-10">
						<input type="text" name="billEmail" id="billEmail" class="form-control" placeholder="Enter Email Address">
					</div><br/>	
                </div>	

				
				<span align="center" id="shippingaddress" class="col-sm-10"><h4 style="text-decoration: underline; font-weight: bold;">SHIPPING ADDRESS</h4></span>
				<div id="shippingaddressdiv">
					<div align="left" class="col-sm-10">
						<input type="radio" value="bill" name="shipAddress" id="bill" checked="checked">Ship To Billing Address.
					</div>
					<div align="left" class="col-sm-10">
						<input type="radio" value="new" name="shipAddress" id="new">Ship To Following Address.
					</div> 
					<br/>
					<label class="col-sm-10">Country:</label>
					<div class="col-sm-10">
						<select id="newCountry" name="newCountry" class="form-control">			
							<option value="AF">Afghanistan</option>            
							<option value="AS">American Samoa</option>           
							<option value="AD">Andorra</option>           
							<option value="AO">Angola</option>            
							<option value="AI">Anguilla</option>
							<option value="AQ">Antarctica</option>
							<option value="AG">Antigua and Barbuda</option>
							<option value="AR">Argentina</option>
							<option value="AM">Armenia</option>
							<option value="AU">Australia</option>
							<option value="AT">Austria</option>
							<option value="AZ">Azerbaijan</option>
							<option value="BH">Bahrain</option>
							<option value="BD">Bangladesh</option>
							<option value="BB">Barbados</option>
							<option value="BE">Belgium</option>
							<option value="BZ">Belize</option>
							<option value="BJ">Benin</option>
							<option value="BT">Bhutan</option>
							<option value="BO">Bolivia</option>
							<option value="BW">Botswana</option>
							<option value="BV">Bouvet Island</option>
							<option value="BR">Brazil</option>
							<option value="IO">British Indian Ocean Territory</option>
							<option value="VG">British Virgin Islands</option>
							<option value="BN">Brunei</option>
							<option value="BG">Bulgaria</option>
							<option value="BI">Burundi</option>
							<option value="KH">Cambodia</option>
							<option value="CA">Canada</option>
							<option value="KY">Cayman Islands</option>
							<option value="TD">Chad</option>
							<option value="CL">Chile</option>
							<option value="CN">China</option>
							<option value="CX">Christmas Island</option>
							<option value="CC">Cocos Islands</option>
							<option value="CO">Colombia</option>
							<option value="KM">Comoros</option>
							<option value="CG">Congo</option>
							<option value="CK">Cook Islands</option>
							<option value="CU">Cuba</option>
							<option value="CY">Cyprus</option>
							<option value="CZ">Czech Republic</option>
							<option value="DK">Denmark</option>
							<option value="DJ">Djibouti</option>
							<option value="EC">Ecuador</option>
							<option value="SV">El Salvador</option>
							<option value="GQ">Equatorial Guinea</option>
							<option value="ER">Eritrea</option>
							<option value="ET">Ethiopia</option>
							<option value="FK">Falkland Islands</option>
							<option value="FO">Faroe Islands</option>
							<option value="FJ">Fiji</option>
							<option value="FI">Finland</option>
							<option value="FR">France</option>
							<option value="GF">French Guiana</option>
							<option value="PF">French Polynesia</option>
							<option value="TF">French Southern Territories</option>
							<option value="GA">Gabon</option>
							<option value="GE">Georgia</option>
							<option value="DE">Germany</option>
							<option value="GI">Gibraltar</option>
							<option value="GR">Greece</option>
							<option value="GL">Greenland</option>
							<option value="GD">Grenada</option>
							<option value="GP">Guadeloupe</option>
							<option value="GU">Guam</option>
							<option value="GN">Guinea</option>
							<option value="HM">Heard Island And McDonald Islands</option>
							<option value="HN">Honduras</option>
							<option value="HK">Hong Kong</option>
							<option value="HU">Hungary</option>
							<option value="IS">Iceland</option>
							<option value="IQ">Iraq</option>
							<option value="IE">Ireland</option>
							<option value="IL">Israel</option>
							<option value="IT">Italy</option>
							<option value="JP">Japan</option>
							<option value="KZ">Kazakhstan</option>
							<option value="KE">Kenya</option>
							<option value="KI1">Kiribati</option>
							<option value="KW">Kuwait</option>
							<option value="KG">Kyrgyzstan</option>
							<option value="LA">Laos</option>
							<option value="LV">Latvia</option>
							<option value="LS">Lesotho</option>
							<option value="LR">Liberia</option>
							<option value="LY">Libya</option>
							<option value="LI">Liechtenstein</option>
							<option value="LU">Luxembourg</option>
							<option value="MG">Madagascar</option>
							<option value="MW">Malawi</option>
							<option value="MV">Maldives</option>
							<option value="MT">Malta</option>
							<option value="MH">Marshall Islands</option>
							<option value="MQ">Martinique</option>
							<option value="MU">Mauritius</option>
							<option value="YT">Mayotte</option>
							<option value="MX">Mexico</option>
							<option value="FM">Micronesia</option>
							<option value="MC">Monaco</option>
							<option value="MS">Montserrat</option>
							<option value="MZ">Mozambique</option>
							<option value="MM">Myanmar</option>
							<option value="NA">Namibia</option>
							<option value="NR">Nauru</option>
							<option value="NP">Nepal</option>
							<option value="NL">Netherlands</option>
							<option value="AN">Netherlands Antilles</option>
							<option value="NC">New Caledonia</option>
							<option value="NZ">New Zealand</option>
							<option value="NI">Nicaragua</option>
							<option value="NU">Niue</option>
							<option value="NF">Norfolk Island</option>
							<option value="KP">North Korea</option>
							<option value="MP">Northern Mariana Islands</option>
							<option value="NO">Norway</option>
							<option value="OM">Oman</option>
							<option value="PW">Palau</option>
							<option value="PA">Panama</option>
							<option value="PG">Papua New Guinea</option>
							<option value="PY">Paraguay</option>
							<option value="PE">Peru</option>
							<option value="PH">Philippines</option>
							<option value="PN">Pitcairn</option>
							<option value="PL">Poland</option>
							<option value="PT">Portugal</option>
							<option value="PR">Puerto Rico</option>
							<option value="RE">Reunion</option>
							<option value="RO">Romania</option>
							<option value="RW">Rwanda</option>
							<option value="SH">Saint Helena</option>
							<option value="SM">San Marino</option>
							<option value="ST">Sao Tome And Principe</option>
							<option value="SA">Saudi Arabia</option>
							<option value="SS">Seychelles</option>
							<option value="SG">Singapore</option>
							<option value="SK">Slovakia</option>
							<option value="SB">Solomon Islands</option>
							<option value="SO">Somalia</option>
							<option value="ZA">South Africa</option>
							<option value="GS">South Georgia And The South Sandwich Islands</option>
							<option value="KR">South Korea</option>
							<option value="ES">Spain</option>
							<option value="LK">Sri Lanka</option>
							<option value="KN">Saint Kitts And Nevis</option>
							<option value="PM">Saint Pierre And Miquelon</option>
							<option value="SD">Sudan</option>
							<option value="SJ">Svalbard And Jan Mayen</option>
							<option value="SE">Sweden</option>
							<option value="CH">Switzerland</option>
							<option value="SY">Syria</option>
							<option value="TW">Taiwan</option>
							<option value="TJ">Tajikistan</option>
							<option value="TZ">Tanzania</option>
							<option value="TH">Thailand</option>
							<option value="TP">Timor-Leste</option>
							<option value="TG">Togo</option>
							<option value="TK">Tokelau</option>
							<option value="TO">Tonga</option>
							<option value="TT">Trinidad and Tobago</option>
							<option value="TR">Turkey</option>
							<option value="TM">Turkmenistan</option>
							<option value="TC">Turks And Caicos Islands</option>
							<option value="TV">Tuvalu</option>
							<option value="UM">United States Minor Outlying Islands</option>
							<option value="UG">Uganda</option>
							<option value="AE">United Arab Emirates</option>
							<option value="GB">United Kingdom</option>
							<option value="US">United States</option>
							<option value="UZ">Uzbekistan</option>
							<option value="VU">Vanuatu</option>
							<option value="VA">Vatican</option>
							<option value="VI">U.S. Virgin Islands</option>
							<option value="WF">Wallis And Futuna</option>
							<option value="EH">Western Sahara</option>
							<option value="WS">Samoa</option>
							<option value="YE">Yemen</option>
							<option value="ZR">Zaire</option>
							<option value="ZM">Zambia</option>
							<option value="ZW">Zimbabwe</option>
						</select>  
					</div><br/>						
					<label class="col-sm-10">First Name:</label>
					<div class="col-sm-10">
						<input type="text" name="newFirstName" id="newFirstName" class="form-control" placeholder="Enter First Name">
					</div><br/>
					<label class="col-sm-10">Last Name:</label>
					<div class="col-sm-10">
						<input type="text" name="newLastName" id="newLastName" class="form-control" placeholder="Enter Last Name"> 
					</div><br/>
					<label class="col-sm-10">Street Address1:</label>
					<div class="col-sm-10">
						<input type="text" name="newStreetAddress1" id="newStreetAddress1" class="form-control" placeholder="Enter Street Address1">
					</div><br/>
					<label class="col-sm-10">Street Address2:</label>
					<div class="col-sm-10">
						<input type="text" name="newStreetAddress2" id="newStreetAddress2" class="form-control" placeholder="Enter Street Address2">
					</div><br/>
					<label class="col-sm-10">Zip Code:</label>
					<div class="col-sm-10">
						<input type="text" name="newZipCode" id="newZipCode" class="form-control" placeholder="Enter Zip Code"> 
					</div><br/>
					<label class="col-sm-10">City:</label>
					<div class="col-sm-10">
						<input type="text" name="newCity" id="newCity" class="form-control" placeholder="Enter City"> 
					</div><br/>
					<label class="col-sm-10">State:</label>
					<div class="col-sm-10">
						<select name="newState" id="newState" class="form-control">
							<option value="">Pick State</option>
							<optgroup label="United States">
								<option value="AL">Alabama</option>
								<option value="AK">Alaska</option>
								<option value="AS">American Samoa</option>
								<option value="AZ">Arizona</option>
								<option value="AR">Arkansas</option>
								<option value="AA">Armed Forces America</option>
								<option value="AE">Armed Forces Europe</option>
								<option value="AP">Armed Forces Pacific</option>
								<option value="CA">California</option>
								<option value="CO">Colorado</option>
								<option value="CT">Connecticut</option>
								<option value="DE">Delaware</option>
								<option value="DC">Dist Of Columbia</option>
								<option value="FL">Florida</option>
								<option value="GA">Georgia</option>
								<option value="GU">Guam</option>
								<option value="HI">Hawaii</option>
								<option value="ID">Idaho</option>
								<option value="IL">Illinois</option>
								<option value="IN">Indiana</option>
								<option value="IA">Iowa</option>
								<option value="KS">Kansas</option>
								<option value="KY">Kentucky</option>
								<option value="LA">Louisiana</option>
								<option value="ME">Maine</option>
								<option value="MH">Marshall Islands</option>
								<option value="MD">Maryland</option>
								<option value="MA">Massachusetts</option>
								<option value="MI">Michigan</option>
								<option value="FM">Micronesia, Federated States Of</option>
								<option value="MN">Minnesota</option>
								<option value="MS">Mississippi</option>
								<option value="MO">Missouri</option>
								<option value="MT">Montana</option>
								<option value="NE">Nebraska</option>
								<option value="NV">Nevada</option>
								<option value="NH">New Hampshire</option>
								<option value="NJ">New Jersey</option>
								<option value="NM">New Mexico</option>
								<option value="NY">New York</option>
								<option value="NC">North Carolina</option>
								<option value="ND">North Dakota</option>
								<option value="MP">Northern Mariana Islands</option>
								<option value="OH">Ohio</option>
								<option value="OK">Oklahoma</option>
								<option value="OR">Oregon</option>
								<option value="PW">Palau (Micronesia)</option>
								<option value="PA">Pennsylvania</option>
								<option value="PR">Puerto Rico</option>
								<option value="RI">Rhode Island</option>
								<option value="SC">South Carolina</option>
								<option value="SD">South Dakota</option>
								<option value="TN">Tennessee</option>
								<option value="TX">Texas</option>
								<option value="UM">U S Minor Outlying Islands</option>
								<option value="UT">Utah</option>
								<option value="VT">Vermont</option>
								<option value="VI">Virgin Islands Of The United States</option>
								<option value="VA">Virginia</option>
								<option value="WA">Washington</option>
								<option value="WV">West Virginia</option>
								<option value="WI">Wisconsin</option>
								<option value="WY">Wyoming</option>  
							</optgroup>
							<optgroup label="England">
								<option>Bedfordshire</option>
								<option>Berkshire</option>
								<option>Bristol</option>
								<option>Buckinghamshire</option>
								<option>Cambridgeshire</option>
								<option>Cheshire</option>
								<option>City of London</option>
								<option>Cornwall</option>
								<option>Cumbria</option>
								<option>Derbyshire</option>
								<option>Devon</option>
								<option>Dorset</option>
								<option>Durham</option>
								<option>East Riding of Yorkshire</option>
								<option>East Sussex</option>
								<option>Essex</option>
								<option>Gloucestershire</option>
								<option>Greater London</option>
								<option>Greater Manchester</option>
								<option>Hampshire</option>
								<option>Herefordshire</option>
								<option>Hertfordshire</option>
								<option>Isle of Wight</option>
								<option>Kent</option>
								<option>Lancashire</option>
								<option>Leicestershire</option>
								<option>Lincolnshire</option>
								<option>Merseyside</option>
								<option>Norfolk</option>
								<option>North Yorkshire</option>
								<option>Northamptonshire</option>
								<option>Northumberland</option>
								<option>Nottinghamshire</option>
								<option>Oxfordshire</option>
								<option>Rutland</option>
								<option>Shropshire</option>
								<option>Somerset</option>
								<option>South Yorkshire</option>
								<option>Staffordshire</option>
								<option>Suffolk</option>
								<option>Surrey</option>
								<option>Tyne and Wear</option>
								<option>Warwickshire</option>
								<option>West Midlands</option>
								<option>West Sussex</option>
								<option>West Yorkshire</option>
								<option>Wiltshire</option>
								<option>Worcestershire</option>
							</optgroup>
							<optgroup label="Wales">
								<option>Anglesey</option>
								<option>Brecknockshire</option>
								<option>Caernarfonshire</option>
								<option>Carmarthenshire</option>
								<option>Cardiganshire</option>
								<option>Denbighshire</option>
								<option>Flintshire</option>
								<option>Glamorgan</option>
								<option>Merioneth</option>
								<option>Monmouthshire</option>
								<option>Montgomeryshire</option>
								<option>Pembrokeshire</option>
								<option>Radnorshire</option>
							</optgroup>
							<optgroup label="Scotland">
								<option>Aberdeenshire</option>
								<option>Angus</option>
								<option>Argyllshire</option>
								<option>Ayrshire</option>
								<option>Banffshire</option>
								<option>Berwickshire</option>
								<option>Buteshire</option>
								<option>Cromartyshire</option>
								<option>Caithness</option>
								<option>Clackmannanshire</option>
								<option>Dumfriesshire</option>
								<option>Dunbartonshire</option>
								<option>East Lothian</option>
								<option>Fife</option>
								<option>Inverness-shire</option>
								<option>Kincardineshire</option>
								<option>Kinross</option>
								<option>Kirkcudbrightshire</option>
								<option>Lanarkshire</option>
								<option>Midlothian</option>
								<option>Morayshire</option>
								<option>Nairnshire</option>
								<option>Orkney</option>
								<option>Peeblesshire</option>
								<option>Perthshire</option>
								<option>Renfrewshire</option>
								<option>Ross-shire</option>
								<option>Roxburghshire</option>
								<option>Selkirkshire</option>
								<option>Shetland</option>
								<option>Stirlingshire</option>
								<option>Sutherland</option>
								<option>West Lothian</option>
								<option>Wigtownshire</option>
							</optgroup>
							<optgroup label="Northern Ireland">
								<option>Antrim</option>
								<option>Armagh</option>
								<option>Down</option>
								<option>Fermanagh</option>
								<option>Londonderry</option>
								<option>Tyrone</option>
							</optgroup>	
						</select>            
					</div><br/>
					<label class="col-sm-10">Phone:</label>
					<div class="col-sm-10">
						<input type="text" name="newPhone" id="newPhone" class="form-control" placeholder="Enter Phone Number"> 
					</div><br/>
					<label class="col-sm-10">Email Address:</label>
					<div class="col-sm-10">
						<input type="text" name="newEmail" id="newEmail" class="form-control" placeholder="Enter Email Address"> 
					</div><br/>
                </div>			

				
				<span align="center" id="paymentinfo" class="col-sm-10"><h4 style="text-decoration: underline; font-weight: bold;">PAYMANT INFORMATION</h4></span>	
                <div id="paymentinfodiv">				
					<label class="col-sm-10">Payment Method:</label>
					<div class="col-sm-10">
						<select name="paymentMethod" id="paymentMethod" class="size-dropdown form-control">						
							<option value="creditCard"  id="creditCard" selected>Credit Card</option> 
							<option value="paypal"  id="paypal">PayPal</option> 						
						</select>
					</div><br/> 				
					<div>
						<label class="col-sm-10">PayPal Id:</label>
						<div class="col-sm-10">
							<input type="text" name="paypalEmail" id="paypalEmail" class="form-control" placeholder="Enter PayPal Id">
						</div>
						<label class="col-sm-10">PayPal Password:</label>
						<div class="col-sm-10">
							<input type="text" name="paypalPassword" id="paypalPassword" class="form-control" placeholder="Enter PayPal Password">
						</div>                
					</div>
					<div >     
						<label class="col-sm-10">Card Type:</label>
						<div class="col-sm-10">
							<select name="paymentCard" id="paymentCard" class="size-dropdown form-control">						
								<option value="mc"  id="masterCard" selected>Master Card</option> 
								<option value="visa"  id="visaCard" >Visa Card</option>
								<option value="ae"  id="americanExpress" >American Express</option> 
								<option value="dsc" id="discoverCard" >Discover Card</option> 
								<option value="jcb" id="jcbCard" >JCB Card</option> 
								<option value="dc" id="dinersClub" >Diners Club</option> 
							</select>
						</div><br/>
						<label class="col-sm-10">Card Number:</label> 
						<div class="col-sm-10">                        
							<input type="text" id="cardNumber" class="form-control" placeholder="Enter Card Number">
						</div>
						<label class="col-sm-10">Name On Card:</label> 
						<div class="col-sm-10">
							<input type="text" name="cardHolderName" id="cardHolderName" class="form-control" placeholder="Enter Card Holder Name"> 
						</div>            
						<label class="col-sm-10">Expiration Month:</label>
						<div class="col-sm-10">
							<select name="payMethodPaneExpireMonth" id="expireMonth" class="size-dropdown form-control">
								<option value="01">January</option>
								<option value="02">February</option>
								<option value="03">March</option>
								<option value="04">April</option>
								<option value="05">May</option>
								<option value="06">June</option>
								<option value="07">July</option>
								<option value="08">August</option>
								<option value="09">September</option>
								<option value="10">October</option>
								<option value="11">November</option>
								<option value="12">December</option>
							</select>
						</div>
						<label class="col-sm-10">Expiration Year:</label>
						<div class="col-sm-10">					
							<select name="payMethodPaneExpireYear" id="expireYear" class="size-dropdown form-control">
								<option value="16">2016</option>
								<option value="17">2017</option>
								<option value="18">2018</option>
								<option value="19">2019</option>
								<option value="20">2020</option>
								<option value="21">2021</option>
								<option value="22">2022</option>
								<option value="23">2023</option>
								<option value="24">2024</option>
								<option value="25">2025</option>
								<option value="26">2026</option>
								<option value="27">2027</option>
								<option value="28">2028</option>
								<option value="29">2029</option>
								<option value="30">2030</option> 
							</select>
						</div>
						<label class="col-sm-10">CVV Code:</label>
						<div class="col-sm-10">
							<input type="text" maxlength="4" size="3" id="cardCVV" name="payMethodPaneCVV" class="form-control" placeholder="Enter CVV">
						</div>
					</div>
					</div>
					<hr style="height:5px;" class="col-sm-10" color="#af2004">
					<div class="col-sm-10">
						<button href="#" id="save" value="SAVE" class="btn-info" style="width:100px;">
							<span><h4> SAVE </h4></span>
						</button> 					
						<button href="#" id="start" value="START" class="btn-success" style="width:100px;">
							<span><h4> START </h4></span>
						</button>
					</div>
					<hr style="height:0px;" class="col-sm-10" color="#000000">
				</div>				
            </div>
        </div>
    </div> 
</body>

