This area is ***under construction***. It will be completed in stages as my motorcycle tuning setup becomes more mature over time. For now it should be used as a guide only.<br />

Please note, these settings are Blackbird specific, so may not work on other models. Inline-4 models however will have a lot of overlap with these settings so various settings may be useful to you if you have CBR.<br /><br />
Noting also that this is for a naturally aspirated Honda Blackbird (no boost) and also using all the stock sensors on the motorcycle.

<br /><br />

# Blackbirds wiring harness to microRusEFI pins

***This section is not complete***<br /><br />

This section details the wiring and connectivity between the Honda wiring harness and microRusEFI connector pins. It should be read in conjunction with [this](https://github.com/BlackbirdStandalone/Documentation/blob/57d9719dac895df7be5ee6f44d175e8deff9f380/wiring/2002_Australian_ECU_Wiring_CBR1100XX_v1.1_Apr_2026.pdf) wiring document.<br />

The microRusEFI pinout can be found [here](https://rusefi.com/docs/pinouts/microrusefi/?connector=main).

<table border="3">
<p style="text-align: left;">The following table is a mapping of the Honda wiring harness to microRusEFI's pins..</p>

<tr>
<td align="center" valign="center"><b>microRusEFI pin #</b></td>
<td align="center" valign="center"><b>Honda harness pin #</b></td>
<td align="center" valign="center"><b>Honda harness wire colour</b></td>
<td align="center" valign="center"><b>Function</b></td>
</tr>

<tr>
<td align="center" valign="center">1</td>
<td align="center" valign="center">Gray (B2)</td>
<td align="center" valign="center">Black/white</td>
<td align="center" valign="center">12v Power from Key ignition.<br />Co-joined to microRusEfi pin 5.</td>
</tr>

<tr>
<td align="center" valign="center">2</td>
<td align="center" valign="center">Black (A10)</td>
<td align="center" valign="center">Green/pink</td>
<td align="center" valign="center">Main ground #1</td>
</tr>

<tr>
<td align="center" valign="center">3</td>
<td align="center" valign="center">Black (A17)</td>
<td align="center" valign="center">Green/blue</td>
<td align="center" valign="center">FAN (relay)</td>
</tr>

<tr>
<td align="center" valign="center">4</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">5</td>
<td align="center" valign="center">Gray (B2)</td>
<td align="center" valign="center">Black/white</td>
<td align="center" valign="center">12v Power from Key ignition.<br />Co-joined to microRusEfi pin 1.</td>
</tr>

<tr>
<td align="center" valign="center">6</td>
<td align="center" valign="center">Black (A11)</td>
<td align="center" valign="center">Green</td>
<td align="center" valign="center">Main ground #2</td>
</tr>

<tr>
<td align="center" valign="center">7</td>
<td align="center" valign="center">Black (A6)</td>
<td align="center" valign="center">Brown/black</td>
<td align="center" valign="center">FUEL PUMP OUT (relay)</td>
</tr>

<tr>
<td align="center" valign="center">8</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">9</td>
<td align="center" valign="center">Black (A9)</td>
<td align="center" valign="center">Yellow/blue</td>
<td align="center" valign="center">Ignition #1.<br />(Coil for cyl #1 & #4)<br />R.H.S on bike</td>
</tr>

<tr>
<td align="center" valign="center">10</td>
<td align="center" valign="center">Black (A20)</td>
<td align="center" valign="center">Blue/yellow</td>
<td align="center" valign="center">Ignition #2.<br />(Coil for cyl #2 & #3)<br />L.H.S on bike</td>
</tr>

<tr>
<td align="center" valign="center">11</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">12</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">13</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">14</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">15</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">16</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">17</td>
<td align="center" valign="center">Black (A22)</td>
<td align="center" valign="center">Green/pink</td>
<td align="center" valign="center">Signal ground</td>
</tr>

<tr>
<td align="center" valign="center">18</td>
<td align="center" valign="center">Gray (B13)</td>
<td align="center" valign="center">Pink/white</td>
<td align="center" valign="center">CLT</td>
</tr>

<tr>
<td align="center" valign="center">19</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">20</td>
<td align="center" valign="center">Gray (B9)</td>
<td align="center" valign="center">Red/yellow</td>
<td align="center" valign="center">TPS</td>
</tr>

<tr>
<td align="center" valign="center">21</td>
<td align="center" valign="center">Black (A22)</td>
<td align="center" valign="center">Green/pink</td>
<td align="center" valign="center">Signal ground</td>
</tr>

<tr>
<td align="center" valign="center">22</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">23</td>
<td align="center" valign="center">Gray (B6)</td>
<td align="center" valign="center">Gray/blue</td>
<td align="center" valign="center">IAT</td>
</tr>

<tr>
<td align="center" valign="center">24</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">25</td>
<td align="center" valign="center"><i>TBD</i></td>
<td align="center" valign="center"><i>TBD</i></td>
<td align="center" valign="center">HALL CAM<br /> (Tooth eater)</td>
</tr>

<tr>
<td align="center" valign="center">26</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">27</td>
<td align="center" valign="center">Gray (B7)</td>
<td align="center" valign="center">Green/yellow</td>
<td align="center" valign="center">MAP</td>
</tr>

<tr>
<td align="center" valign="center">28</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">29</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">30</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">31</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">32</td>
<td align="center" valign="center">Gray (B5)</td>
<td align="center" valign="center"><i>TBD</i></td>
<td align="center" valign="center">O2 sensor</td>
</tr>

<tr>
<td align="center" valign="center">33</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">34</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">35</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">36</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">37</td>
<td align="center" valign="center">Black (A13)</td>
<td align="center" valign="center">Pink/yellow</td>
<td align="center" valign="center">Fuel injector #1</td>
</tr>

<tr>
<td align="center" valign="center">38</td>
<td align="center" valign="center">Black (A2)</td>
<td align="center" valign="center">Pink/blue</td>
<td align="center" valign="center">Fuel injector #2</td>
</tr>

<tr>
<td align="center" valign="center">39</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">40</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">41</td>
<td align="center" valign="center">Black (A12)</td>
<td align="center" valign="center">Pink/green</td>
<td align="center" valign="center">Fuel injector #3</td>
</tr>

<tr>
<td align="center" valign="center">42</td>
<td align="center" valign="center">Black (A1)</td>
<td align="center" valign="center">Pink/black</td>
<td align="center" valign="center">Fuel injector #4</td>
</tr>

<tr>
<td align="center" valign="center">43</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
<td align="center" valign="center">-</td>
</tr>

<tr>
<td align="center" valign="center">44</td>
<td align="center" valign="center">Gray (B1)</td>
<td align="center" valign="center">Yellow/red</td>
<td align="center" valign="center">5v sensor supply from ECU</td>
</tr>

<tr>
<td align="center" valign="center">45</td>
<td align="center" valign="center"><i>TBD</i></td>
<td align="center" valign="center"><i>TBD</i></td>
<td align="center" valign="center">HALL CRANK<br /> (Tooth eater)</td>
</tr>

</table>

<br /><br />

# microRusEFI Tuner Studio setup for the Honda Blackbird

## Vehicle Setup

I am using a build of microRusEFI from the repository that is tagged as "release_20260220_2". Your build may be different, however your Tuner Studio parameters should be set the same (for the most part).<br />

<b><i>Setup -> Vehicle Information</i></b><br />

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/VehicleInformation.png#center">
</img>

<br /><br />

## Rev limiter

Here we set the engine cut-off protection at around redline. I've set 11,000 but you can set 10,500 or whatever suits you. The main fields that matter are the ones highlighted in red.<br />

<b><i>Setup -> Limits and protection -> Limits and fallbacks</i></b><br />

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/LimitsAndFallbacks.png#center">
</img>

<br /><br />

## Trigger Setup

This trigger section requires that either:<br />
<ol>
<li>The tooth eater to be present or,</li>
<li>For you to find your own means of doing your own triggering. Hopefully a suitable configuration is already made available for you in your ECU system, but if not (and as a last resort) you may need to hacksaw two teeth off your cam trigger wheel. If you are physically removing two of the three teeth from your cam trigger wheel, then choose two teeth to remove then time your engine with a timing light accordingly at a fixed angle of 0 Deg at TDC. I.e. Most of this page should apply, however the <b><i>Trigger Advance Angle</i></b> is something you will need to discover for yourself.</li>
</ol>
This section also requires the VR conditioner circuit to be present. If you are running the tooth eater, then this is available as a speeduino compatible plug in module.<br />

If you are using the tooth eater module, then you can use these settings shown below. The tooth eater uses the tooth with the red arrow pointing to it (see the main page).<br />

<table border="1">

<tr> 
<td width="30%">
<strong>Firmware version</strong>
</td>
<td width="70%">
<strong>Trigger Advance Angle</strong>
</td>
</tr>

<tr> 
<td width="30%">
<strong>v1.1</strong>
</td>
<td width="70%">
?TBD? - Coming soon
</td>
</tr>

<tr> 
<td width="30%">
<strong>v1.0</strong>
</td>
<td width="70%">
130
</td>
</tr>

</table>


<b><i>Setup -> Trigger</i></b><br />
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/TriggerSettings.png#center">
</img>



<br /><br />




## Ignition Setup

<b><i>Ignition -> Ignition hardware</i></b><br />
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/IgnitionHardware.png#center">
</img>

<br /><br />

## Sensor Calibration

<b><u>Map calibration</b></u><br />
I've found these settings to align very accurately.

<b><i>Sensors -> Map sensor</i></b><br />
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/MapCalibration.png#center">
</img>

<br /><br />

<b><u>Intake air temperature (IAT) calibration</b></u><br />
These settings are not perfect, however I've found them to work well enough. They are in the ballpark.

<b><i>Sensors -> IAT sensor</i></b><br />
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/IAT_Sensor.png#center">
</img>

<br /><br />

<b><u>Coolant sensor (CLT) calibration</b></u><br />

These settings are not perfect, however I have found these settings to work in practical terms. When the engine is colder the reading on the dash compared to what is in Tuner Studio will have some error involved (perhaps 5 to 10 Deg). However as the engine gets hotter and is up to temperature, I have found that the error is fairly negligible, perhaps within a few degrees at most.<br />

<b><i>Sensors -> CLT sensor</i></b><br />
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="./images/CLT_Sensor.png#center">
</img>

<br /><br />


