# Nightscout

[Nightscout](http://nightscout.info) (NS) is a cornerstone of the DIY type 1 community. It is an excellent tool to remotely view Loop's actions and access insulin and blood glucose data. It allows for easy remote monitoring of Loop activities, troubleshooting of Loop errors, history of CGM, carbs, boluses, & temp basals, reports to analyze data trends and patterns. There is a Nightscout app in your iPhone App Store, or you can use a web browser to view the data.  [Setting up Nightscout for Loop](https://loopkit.github.io/loopdocs/nightscout/new_user/) is free and fairly quick. Once setup, the site can be accessed by anyone that you share your unique Nightscout URL with.  

## Nightscout Display
Nightscout is highly recommended for Loop users, especially those using Loop as caregivers. Nightscout displays are often the easiest way to troubleshoot Loop settings, if you are having problems and seeking input from others.  Below is some discussion about the general Nightscout display, as well as some Loop-specific display information.

<p align="center">
<img src="../img/example.jpg" width="700">
</p> 

</br>
<dl>
<dt>Blood Glucose</dt>
<dd>Your blood glucose readings from your CGM are shown in green, yellow, or red in the main graph area of NS.  You can adjust your high and low blood glucose targets in NS (when NS alerts will start for high/low BGs), but those will not affect your Loop performance. Loop only uses the blood glucose targets given in the Loop app settings. The main screen displays the time duration you have selected (in the example above, 12 hours of BG history). The very bottom of the screen shows the last 48-hours of blood glucose trends. You can scan backwards by dragging the bottom timeline to the left, if you want to review specific Loop actions or data in the last two days. </dd>
</br>
<dt>Carbohydrates</dt>
<dd>Carbohydrates are automatically uploaded to NS by the Loop app.  The amount of carbohydrates on board (active carbs or COB) can be seen by clicking the Loop pill.  The size of a white carbohydrate dot on the graph is proportional to the amount of carbohydrates entered...bigger meals get bigger dots. Loop does not read carbohydrates from NS (nor from the pump's bolus wizard) for use in looping calculations. Loop only uploads carbohydrates to NS that have been entered in the Loop app and recorded to HealthKit.</dd>
</br>
<dt>Boluses</dt>
<dd>Insulin boluses are also automatically uploaded to NS by the Loop app. The bolus is shown as a filled in blue lower-half of the dot, and the specific amount of the bolus is also shown. There may be a slight delay between when the carbohydrates for a meal are uploaded to NS to when the meal bolus appears. This is because depending on the pump model and size of bolus, the bolus may take a few minutes to actually be given and then Loop has to perform a pump read to verify the insulin delivery (i.e., the bolus was given). As shown in the example above, the meal carbohydrates have been uploaded, but the bolus delivery is still in progress. Insulin on board (active insulin or IOB) is also shown in the Loop pill.</dd>
</br>
<dt>Temporary Basals</dt>
<dd>Within your NS profile, you will enter in the scheduled basal rates from your Loop settings. This is not automatically updated when you update the Loop app; you will have to manually update your basal profile in your NS site if you change your basal profile in Loop. If you don't update the NS basal profile, it doesn't cause any problems in Loop function...you simply won't have accurate VISUAL representation of high/low temporary basals within NS. The dashed blue line represents the scheduled basal profile (as entered in your NS profile). The solid blue lines indicate the actual basal amounts set for a given time...so as Loop sets temporary basals higher or lower than your scheduled basal rate, the solid blue line will jump above or below your dashed blue line. There is a slight delay (up to 2-5 minutes) in the rendering of basal changes on the blue lines, so if you want the accurate current basal rate, you should check the Loop pill.</dd>
</br>
<dt>Predicted Blood Glucose</dt>
<dd>The purple line to the right of the blood gluose readings is Loop's predicted blood glucose curve.  Watching the behavior of that purple line can help you understand why Loop is making decisions regarding high or low temporary basals. You can read more on that topic in [the Algorithm section](https://kdisimone.github.io/looptips/algorithm/temp-basal/) of these docs.</dd>
</br>
<dt>Loop pill</dt>
<dd>The Loop pill is the little display box which when hovered over, or clicked, will provide additional information about recent Loop activities and status. Information included is the last time Loop ran, the temporary basal set, IOB, and COB. Looking at the Loop pill is a quick method for assessing if your Loop is currently active, as well.  The small symbols to the right of the word "Loop" have specific meaning. The small horizontal lightning bolt, shown in this example, is an active loop which recently enacted a temporary basal.</dd>
</br>
<dt>SAGE, BAGE, CAGE pills</dt>
<dd>The SAGE, BAGE, and CAGE pills are for sensor age, pump battery age, and cannula age. These optional pills can track the time since your CGM sensor, pump battery, and pump site were last changed. You can set up custom alerts to remind you when it is time to change the devices, or simply use the visuals to keep track of your particular timing for site/sensor changes.</dd>
</dl>

## Nightscout Reports

You can access the Reports tab from within your NS settings (the three horizontal lines in the upper right corner of your NS site).  There are several types of reports which may be useful to you and/or your health care provider. The report types are listed in tabs at the top of the Reports section, and you can also select the range of dates you'd like any report to cover.

<p align="center">
<img src="../img/reports.png" width="700">
</p> 

### Day to Day report

The day-to-day report will show detailed overlay of boluses, basals, carbohydrates, CGM, and treatment notes. If you select the optional check boxes, you can also see information such as the insulin distribution pie graphs shown on the right of the figure below.

<p align="center">
<img src="../img/day-to-day.png" width="700">
</p> 

### Daily Stats report

The daily stats report is pie chart showing the daily breakdown of your low, in-range, and high time in target, as well as other statistical analysis of your BG trends.

<p align="center">
<img src="../img/daily-stats.png" width="700">
</p> 

### Distribution report

The distribution report is a combination of all the individual daily stats reports all into one pie chart for the date range selected.

<p align="center">
<img src="../img/distribution.png" width="700">
</p> 

### Glucose Percentile report

The glucose percentile report will help you see just how consistent your blood glucose is at various times of day.  The average blood glucose is shown as a dark black line in the center of colored bars.  The wider the colored areas spread out from the center black line, the more scattered and variable your blood glucose values at that time have tended to be.

<p align="center">
<img src="../img/percentile.png" width="700">
</p> 

For the graph above, for example, the blood glucose control around 4-6 am is very consistent.  The most variable time appears to be near lunchtime.  The time of day where low blood glucose seems to be the most problematic is between 4-6 pm, which happens to be this person's exercise time.  Based on the data in this graph, the person may benefit from setting a higher target about 2 hours before exercise time in order to help with the pattern of low blood glucose that occurs most often during that time.

### Treatments

The treatments report will show a listing of all the temporary basals Loop sets, as well as boluses, carbohydrates, site changes, and any other "treatments" which have been entered into NS.

<p align="center">
<img src="../img/treatments.png" width="=700">
</p> 
