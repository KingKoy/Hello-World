<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css" href=>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="myScript.js"></script>
</head>

<body style="font-family:Verdana;color:#aaaaaa;">
    <div class="peertopeerimage">
        <ul class="uppernav">
            <li><a href="#help">Help</a></li>
            <li><a href="#contact">Login</a></li>
            <li><a href="#about">About Us</a></li>
            <li style="float:left"><a href="EmailAddress"><i class="fa fa-envelope"></i> uhc_peertopeer_scheduling@uhc.com</a></li>
            <li style="float:left"><a href="#PhoneNumber"><i class="fa fa-phone"></i> 800-955-7615</a></li>
        </ul>
    </div>

    <div style="overflow:auto">
        <ul class="topnav">
            <li><a class="active" href="#home">Home</a></li>
            <li><a href="#Update">Update</a></li>
            <li><a href="#Services">Services</a></li>
            <li><a href="#Contact">Contact</a></li>
            <li style="float:right"><a href="#Search"><i class="fa fa-search"></i></a></li>
        </ul>
    </div>

    <!-- code for forms -->

    <div id="myCont" class="container">




        <div class="col-26-4-i">
            <label id="iconpeertopeer" onclick="hideForm()" for="myForms"><i class= "fa fa-bars"></i></label>
        </div>


        <form id="myForm">


            <!--dropdown code for forms -->

            <div class="row">
                <div class="col-65">
                    <select onchange="displayDate()" id="request" name="request" required>
        <option value="" disabled selected>Request via</option>
        <option value="Phone">PHONE</option>
        <option value="Email">EMAIL</option>
        <option value="VoiceMail">VOICE MAIL</option>
      </select>
                </div>
            </div>

            <div class="row">
                <div class="col-65">
                    <select id="appeal" name="appeal" required>
          <option class="DDplace" value="" disabled selected hidden>Any Appeals on file?</option>
          <option value="yes">YES</option>
          <option value="no">NO</option>

        </select>
                </div>
            </div>


            <div class="row">
                <div class="col-65">
                    <select id="type" name="typeofcase" required>
            <option class="DDplace" value="" disabled selected hidden>Type of Case</option>
            <option value="CCR">CCR</option>
            <option value="ICM">ICM</option>

          </select>

                </div>
            </div>
            <div class="row">
                <div class="col-65">
                    <select id="kindoftemplate" name="kindoftemplate" required>
              <option class="DDplace" value="" disabled selected hidden>Kind of Template</option>
              <option value=0>ICM STANDARD</option>
              <option value=1>ICM PREFERRED</option>
              <option value=2>ICM APPOINTMENT</option>
              <option value=3>E&I TXFI ICM</option>
              <option value=4>TXFI LTR R DECLINE ICM</option>
              <option value=5>TXFI LTR R ACCEPTED ICM</option>
              <option value=6>M&R LTR NOT SENT ICM</option>
              <option value=7>M&R DECLINE ICM</option>
              <option value=8>M&R ACCPTED ICM</option>
              <option value=9>CCR STANDARD</option>
              <option value=10>E&I TXFI CCR</option>
              <option value=11>TXFI LTR R DECLINE CCR</option>
              <option value=12>TXFI LTR R ACCEPTED CCR</option>
              <option value=13>M&R LTR NOT R CCR</option>
              <option value=14>M&R DECLINE CCR</option>
              <option value=15>M&R ACCPTED CCR</option>
             
            </select>
                </div>
            </div>


            <div class="row">
                <div class="col-65">
                    <select id="resolution" name="resolution" required>
                <option class="DDplace" value="" disabled selected hidden>Resolution</option>
                <option value="Appointment">APPOINTMENT</option>
                <option value="Transfer">TRANSFER</option>
                <option value="EHR">EHR</option>
                <option value="Inquiry">INQUIRY</option>
                <option value="Sup Call">SUP CALL</option>

              </select>

                </div>
            </div>
            <div class="row">
                <div class="col-65">
                    <select id="Dept" name="Department" required>
                  <option class="DDplace" value="" disabled selected hidden>Department</option>
                  <option value="Offshore">OFFSHORE</option>
                  <option value="Onshore">ONSHORE</option>
                  <option value="Other">OTHER</option>

                </select>
                </div>
            </div>
            <!--dropdown code for forms -->

            <div class="row">
                <div class="col-75">
                    <textarea id="subject" name="subject" placeholder="This is a free Note..." style="height:60px"></textarea>
                </div>
            </div>


            <div class="row">
                <div class="col-75">
                    <input type="text" id="rmdName" name="" placeholder="RMD MSID/NAME">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="rnName" name="" placeholder="RN MSID/NAME">
                </div>
            </div>


            <div class="row">
                <div class="col-75">
                    <input type="text" id="Srn" name="serviceReferenceNumber" placeholder="Service Reference Number">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="MembersId" name="membersid" placeholder="Member's ID Number">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Membersname" name="membersname" placeholder="Members Name">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Callername" name="callersname" placeholder="Caller's Name">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Callernumber" name="callersnumber" placeholder="Caller's Phone Numnber">
                </div>
            </div>


            <div class="row">
                <div class="col-75">
                    <input type="text" id="Callersemailadd" name="callerseadd" placeholder="Caller's Email Address">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Providersname" name="Providername" placeholder="Provider's Name">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Providerscpnumber" name="Providercpnumber" placeholder="Provider's Cellphone Number">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Providersofnumber" name="Providerofnumber" placeholder="Provider's Office Phone Number">
                </div>
            </div>




            <div class="row">
                <div class="col-70">
                    <select id="Title" name="title" required>
        <option class="DDplace" value="" disabled selected hidden>Provider's Title</option>
        <option value="MD">MD</option>
        <option value="DO">DO</option>
        <option value="NURSE PRACTITIONER">NURSE PRACTITIONER</option>
        <option value="LICENSED PHYSICIAN ASSISTANT">LICENSED PHYSICIAN ASSISTANT</option>
        <option value="PODIATRIST">PODIATRIST</option>
        <option value="CHIROPRACTOR">CHIROPRACTOR</option>
        <option value="DENTIST">DENTIST</option>
        <option value="GENETICS COUNSELOR">GENETICS COUNSELOR</option>
        <option value="OPTOMETRIST">OPTOMETRIST</option>
        <option value="PSYCHOLOGIST">PSYCHOLOGIST</option>

    </select>
                </div>
            </div>

            <div class="row">
                <div class="col-70">
                    <select id="timezone" name="timezone" required>
                      <option class="DDplace" value="" disabled selected hidden>Time Zone</option>
                      <option value="ET">ET</option>
                      <option value="CT">CT</option>
                      <option value="MT">MT</option>
                      <option value="PT">PT</option>
                      <option value="AZ">AZ</option>
                    </select>
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Providersinvolved" name="Providerinvolved" placeholder="How is this provider involved in the care of the member?">
                </div>
            </div>

            <div class="row">
                <div class="col-75">
                    <input type="text" id="Timestamp" name="Timestamps" placeholder="Timestamp of request">
                </div>
            </div>



            <div class="row">
                <div class="col-25">
                    <label for="bolapp">Appointment requested?</label>
                </div>
                <div class="col-80">
                    <select id="App" name="boleanapp" required>
                      <option class="DDplace" value="" disabled selected hidden>Select</option>
                      <option value="YES">YES</option>
                      <option value="NO">NO</option>
                      </select>
                </div>
            </div>

            <div class="row">
                <div class="col-85">
                    <input type="text" id="appointment" name="appointments" placeholder="Date and Time of Appointment">
                </div>
            </div>

            <div class="row">
                <div class="col-25">
                    <label for="bolpre">Preferred Timeframe requested?</label>
                </div>
                <div class="col-80">
                    <select id="frame" name="boleanframe" required>
                      <option class="DDplace" value="" disabled selected hidden>Select</option>
                      <option value="YES">YES</option>
                      <option value="NO">NO</option>
                     </select>
                </div>
            </div>

            <div class="row">

                <div class="col-85">
                    <input type="text" id="timeframe" name="timeframes" placeholder="Preferred Timeframe range and date">
                </div>
            </div>


            <div class="row">

                <div class="coltemplate">
                    <input type="button" onclick="myFunction()" value="CREATE TEMPLATE">
                </div>
            </div>
            <div class="row">
                <div class="coltemplate">
                    <input type="button" onclick="myFunctions()" value="TRACK">
                </div>
            </div>
            <!-- <div class="coltemplate">
                <input type="button" onclick="myMail()" value="SEND EMAIL">
            </div> -->
        </form>
    </div>

    <!-- code for forms -->

    <div id="centerCon" class="center">
        <div class="Templatediv">
            <div class="centerchild">
                <h3 class="headernotes">Note Template</h3>
                <div class="centerchild">
                    <p class="indent" id="demo"></p>
                </div>
            </div>

            <div class="centerchild">
                <h3 class="headernotes">Email Template</h3>
                <div class="centerchild">
                    <p id="subti"></p>
                </div>
                <div class="centerchild">
                    <p class="indent" id="email"></p>
                </div>
            </div>
        </div>
        <!-- 
        <div class="col-75">
            <input type="text" id="subline" name="subline">
        </div>
    </div>
    <div class="centerchild">
        <div class="col-75">
            <textarea id="email" name="subject" style="height:60px"></textarea>
        </div>
    </div> -->

        <div class="mytimezone">

            <h3 id="timeheader" class="headernote">Timezone Converter</h3>

            <div id="frm1form">
                <form id="frm1" onsubmit="return false">
                    <input onchange="mytimeconverter()" id="inpppuuuutttt" type="text" name="timezno">
                    <select onchange="mytimeconverter()" id="origtimezn" name="timezoneo">
                    <option value=0>HI</option>
                    <option value=1>AK</option>
                    <option value=2>PT</option>
                    <option value=3>AZ</option>
                    <option value=4>MT</option>
                    <option value=5>CT</option>
                    <option value=6>ET</option>
                        </select><br>
                </form>
            </div>


            <div id="frm2form">


                <input onchange="mytimeconverter()" id="timezoneee" type="text" name="timezno">

                <select onchange="mytimeconverter()" id="convertedtime" name="timezoneo">
                                    <option value=0>HI</option>
                                    <option value=1>AK</option>
                                    <option value=2>PT</option>
                                    <option value=3>AZ</option>
                                    <option value=4>MT</option>
                                    <option value=5>CT</option>
                                    <option value=6>ET</option>
                                </select><br>

                </form>
            </div>
        </div>
    </div>


    <div id="demo"></div>



    <div class="right">


        <div class="card" id="myjobaid">

            <div class="row1">

                <div class="col-26">
                    <label for="myjodaid">MY JOB AID</label>
                </div>
            </div>

            <div class="row1">

                <input type="button" value="PEER TO PEER TIPS">

            </div>

            <div class="row1">
                <input type="button" value="ENI TEXAS TIPS">
            </div>

            <div class="row1">
                <input type="button" value="MNR AND CNS DUAL PLAN TIPS">
            </div>

            <div class="row1">
                <input type="button" value="CNS ICM TIPS">
            </div>

            <div class="row1">
                <input type="button" value="CCR EI RMD ASSGN GRID">
            </div>

            <div class="row1">
                <input type="button" value="P2P FREQUENTLY USED PHONE">
            </div>



            <div class="row1">
                <input type="button" value="ICM MD GRID">
            </div>

            <div class="row1">
                <input type="button" value="ENI & MNR ICM PTO QUEUES">
            </div>

        </div>

        <div class="card" id="mysched">
            <div class="row1">

                <div class="col-26">
                    <label for="rmdschedule">RMD SCHEDULE CHART</label>
                </div>
            </div>

            <div class="row1">
                <input type="button" value="ENI RMD SCHEDULE CHART">
            </div>

            <div class="row1">
                <input type="button" value="CNS RMD SCHEDULE CHART">
            </div>
        </div>




        <div class="card" id="mytool">
            <div class="row1">

                <div class="col-26">
                    <label for="mytool">MY TOOLS</label>
                </div>
            </div>

            <div class="row1">
                <input type="button" value="RESTRICTED PLAN TOOL">
            </div>

            <div class="row1">
                <input type="button" value="TIMEZONE CONVERTER TOOL">
            </div>
        </div>


        <div class="card" id="mylinks">

            <div class="row1">

                <div class="col-26">
                    <label for="myjodaid">MY LINKS</label>
                </div>
            </div>

            <div class="row1">
                <input type="button" value="LEGACY ENI COMMERCIAL">
            </div>

            <div class="row1">
                <input type="button" value="MASTER MD OOO">
            </div>

            <div class="row1">
                <input type="button" value="CALL SCHED CCR ENI/CNS/MNR">
            </div>

            <div class="row1">
                <input type="button" value="CCR E&I Medical Director Assignment Grid ">
            </div>

            <div class="row1">
                <input type="button" value="CNS TAFW CALENDAR">
            </div>

            <div class="row1">
                <input type="button" value="ACQUIRED ENTITIES TEAM PTO">
            </div>

            <div class="row1">
                <input type="button" value="JOB AIDS">
            </div>
        </div>
    </div>
</body>

</html
