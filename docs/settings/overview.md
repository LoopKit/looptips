# Overview

In the context of the following discussion, the term "settings" refers to information that the user typically enters into their pump.  These settings include:

* basal rate schedule
* insulin sensitivitiy factor (ISF)
* carb ratio
* duration of insulin action (DIA)
* correction/target range

Typically, most people with type 1 diabetes consult with their endocrinologist to develop and revise their settings.  The endocrinologist usually reviews the patient's BG and treatments history at each appointment to assess whether settings need to be adjusted.  There are several great books available about the topic (Think Like A Pancreas, etc)

## Why settings still matter

With all the excitement about automated insulin delivery, some people mistakenly assume that the user's settings don't matter anymore....that **<i>everything</i>** is automated. However, settings do still matter as they provide the basis for Loop's math.  Diabetes is not a static math equation.  What worked for basals, insulin sensitivity, or carb ratios yesterday...well, that might not work today.  The degree that those variations happen can affect your looping experience.

Let's give some examples to help.  When you go to calculate a meal bolus, your math probably looks similar to this:

<p align="center">
<img src="../img/bolus-equation.jpg" width="450">
</p>

But then many times you are also probably adjusting that math based on any number of "factors" that you are aware could be affecting your BG.  [Diatribe](https://diabetesresearchconnection.org/42-factors-affect-blood-glucose/) put together this great list of factors that affect BGs, and therefore could also affect how you'd adjust your insulin delivery from what they otherwise would normally be.

<p align="center">
<img src="../img/bg-factors.png" width="450">
</p>

Some of those factors you are already used to making allowances for, such as:

* Pizza boluses...You probably are accustomed to needing an extended bolus and/or higher temp basal rate to help with the late BG spike common after the initial bolus starts to wear off.  That pizza takes a long time to digest thanks to those slow-acting fats.  
* Medications...How about that time that you had to take steroids for an achy joint?  Those steroids probably resulted in a dramatic overall increase in insulin needs for several days.
* Hormones...monthly hormone cycles have many women adjusting their basal rates and insulin sensitivity schedules for a week or so each month.
* Exercise...always a tough one because some exercise may make your BG rise (lifting weights) and other exercise may make your BG drop (running).  Through repetition, most people have learned how to adjust for exercise by using temp basal rates or timing of meals/boluses.

The degree to which Loop can deal with those factors is largely dependent on the duration of the "factor" itself and how well we can communicate to Loop that those factors are at play.  For things we know are coming, we can tell Loop in advance, and Loop has ways of dealing with them mathematically.  In the pizza example, Loop lets us mark the meal as long, slow digestion and therefore better react to a potential late BG rise.  For exercise, we can use temporary targets before/after exercise to help Loop administer less insulin for awhile.

If, however, your insulin needs are impacted by something unnanouced such as horomone cycles, stress, or illness then sometimes your Loop may not be able to consistently hold you at your target BG range.  You may end up holding steady at a higher BG than you'd prefer.  This is because Loop's math is still using the inputs that were from before you got sick/stressed/horomone'd (new word).  Then the decision becomes "Do you adjust your settings now or just wait it out until the stressor goes away?" 

## What if settings are "off"?

Loop is primarily a set of math equations called an algorithm.  The recommendations and actions that Loop takes are based on math.  If the inputs to those math equations (aka your settings) are not accurate, your results for blood glucose control may also not be optimal.

Let's use an analogy to explain the impact of settings.  Imagine your are trying to keep a house plant healthy.  If you water it "just right", the plant is green and lush.  After much trial and error, you've discovered that 1/3 cup of water every other day is "just right".  Everything is beautiful...plant is happy.

Until, your mom decided to move the plant into the warmest room of the house.  Now the plant's soil is evaporating water at a quicker rate.  You notice this is leaving the plant stressed and not quite as perky looking.  If you continued to water just 1/3 cup of water every other day...the plant would not be as healthy as it was in the cooler room.  What changed?  The underlying need for water changed due to a stressor (hotter room).  Knowing that there was a stressor, you have some options:

1. Keep the same watering schedule.  Before choosing this option you might want to know how long your mom is staying.  If she will be gone soon and you can move the plant back into the cooler room, maybe you choose this option.  The affect on the plant, while not ideal, will be short-lived and you just don't want to deal with mom-drama about plant locations.  Ride out the short-term stress.
2. Increase your watering schedule.  If mom is going to be visiting for a long time, it might be best to adjust your watering schedule.  You might not be quite sure how much, but you know it's something.  You can periodically check in on the plant and soil moisture to see how it is responding to a little more water.

Much like the plant and its watering schedule, your basic insulin settings are what keeps your BGs steady *without stessors* present.  For much of the time, the stressors in type 1 are short-lived and temporary (we just ride them out)...carb count a little off, math test in fourth period, public speaking engagement, etc.  Loop does well helping with the short-term stressors.  They don't represent a prolonged need to change settings and the BG-impacts are short-lived. 

However, the longer term stressors are often helped by settings adjustments.  Examples of longer term stressors are medications, illness, hormones, travel, or altitude.   By letting Loop know that the status quo has changed (more/less insulin is needed overall) will help BGs get and stay in range.  If you have told Loop that your insulin need is 1 unit/hour, but in reality you're needing 1.3 units/hour because you've traveled to a colder place and will be sedentary for days...you will likely find yourself steady but higher than your target range while looping.  The high temp basals that Loop will be providing in an attempt to bring you back to target will simply be going to fill the lack of adequate basal scheduled.  If you update your basal schedule to reflect 1.3 units/hour of basal needs, Loop would be better positioned to provide needed insulin delivery to keep you in target range.

## Automated settings adjustments

A common sentiment among new Loop users goes something like *"Why doesn't Loop see that I'm stuck on a high BG?  Why doesn't it bring me back to my target BG?"*

What's actually being implied is that the user thinks Loop should be doing some sort of retrospective analysis on the user's BG and data to make a "better" decision.   The user wants Loop to learn from recent data.  

There is a short-term retrospective analysis built into Loop which will apply a weighted-correction based on the past 60 minutes of BG changes.  However, larger-scale "learning" is not currently a part of Loop's algorithm. 

Perhaps in subsequent versions of Loop, auto-adjustment of settings or machine learning will be incorporated.  Until then, you will need to tell Loop if your plant has moved long-term to a warmer room ;)


