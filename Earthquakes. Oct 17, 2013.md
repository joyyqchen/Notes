October 17, 2013. Earthquakes
=====

<b>Geospacial Innovation Foundation (GIF) Information Sources</b>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Cal-Adapt<br>
&nbsp;&nbsp;&nbsp;&nbsp;-LandCarbon Atlas<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Berkeley Ecoinformatics Engine 
<br><br>
<b>SAMSI</b>
<br><br>
<b>ETAS</b><br>
&nbsp;&nbsp;&nbsp;&nbsp;<b>E</b>pidemic-<b>T</b>ype <b>A</b>ftershock <b>S</b>equence Model
<br><br>
<b>Rabbits and Earthwake Casinos</b><br>
&nbsp;&nbsp;&nbsp;&nbsp;What would make the casino metaphor apt?<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.The physics of earthquakes might be stochastic<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.Stochastic models might provide a compact, accurate description of earthquake phenomenology<br>
&nbsp;&nbsp;&nbsp;&nbsp;3.Stochastic models might be useful for predicting future seismicity<br>
&nbsp;&nbsp;&nbsp;&nbsp;Unless you believe(1), Rabbit Theorem says you can't conclude process is random<br>
&nbsp;&nbsp;&nbsp;&nbsp;Might still be useful to treat it as random for reason (2) or (3)<br>
&nbsp;&nbsp;&nbsp;&nbsp;We will look at (2) abd (3) for several common models
<br><br>
<b>Seismicity Models</b><br>
&nbsp;&nbsp;&nbsp;&nbsp;-Poisson<br>
&nbsp;&nbsp;&nbsp;&nbsp; Doesn't fit: too little clustering<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Poisson for "declusted" catalogs <br>
&nbsp;&nbsp;&nbsp;&nbsp; Will pass test if you remove enough events, but standard algorithms don't<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Gamma renewal<br>
&nbsp;&nbsp;&nbsp;&nbsp; Doesn't fit<br>
&nbsp;&nbsp;&nbsp;&nbsp;-ETAS<br>
&nbsp;&nbsp;&nbsp;&nbsp; Doesn't fit
<br><br>
<b>SCEC Data</b>
&nbsp;&nbsp;&nbsp;&nbsp;
<br><br>
<b>Methods</b><br>
&nbsp;&nbsp;&nbsp;&nbsp;GKl<br>
&nbsp;&nbsp;&nbsp;&nbsp;GKlb<br>
&nbsp;&nbsp;&nbsp;&nbsp;GKm<br>
&nbsp;&nbsp;&nbsp;&nbsp;Rl<br>
&nbsp;&nbsp;&nbsp;&nbsp;dT
<br><br>
<b>Automatic Alarm</b>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;-Automatic Alarm<br>
&nbsp;&nbsp;&nbsp;&nbsp; After every event with M>m, start an alarm of duration t <br>
&nbsp;&nbsp;&nbsp;&nbsp; No free parameters<br>
&nbsp;&nbsp;&nbsp;&nbsp; <b> STUPID METHOD </b><br>
&nbsp;&nbsp;&nbsp;&nbsp;-Magnitude-dependent Automatic Alarm (MDA) <br>
&nbsp;&nbsp;&nbsp;&nbsp; After every event with M>m, start an alarm of duration tu^M<br>
&nbsp;&nbsp;&nbsp;&nbsp; 1 free parameter (u)<br>
&nbsp;&nbsp;&nbsp;For both, adjust fraction of time covered by alarms through t.
&nbsp;&nbsp;&nbsp;&nbsp;-Optimal ETAS predictor: level set of conditional intensity.
&nbsp;&nbsp;&nbsp;&nbsp; ETAS has 4 free parameters: K, alpha, c, p.
