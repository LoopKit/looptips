
# Overrides

!!! info "`Override` (in the documentation) = `Preset` (in the application)"
    The Loop application and its documentation sometimes refer to the same concept in different ways:
    
    In Documentation  |       | In Application
    ---            | ---   | ---
     Override        | $$ = $$ | Preset
    Override Preset | $$ = $$  | Custom Preset
    Pre-Meal Target | $$ = $$  | Pre-Meal Preset
        
    For example, the *Loop* application uses the term **Pre-Meal Preset** to denote what the documentation refers to as the **Pre-Meal Override** (or **Pre-Meal Target**). They represent the same concept.

Your Loop has a built-in [Override](https://loopkit.github.io/loopdocs/operation/features/overrides/) preset you can activate: *`Pre-meal`*.   
## Configuring the Pre-Meal Override

You can set the value for this *Pre-Meal* Override preset from the Correction Range area of *Loop* settings. Generally speaking, the *Pre-Meal* is set to value(s) lower than your correction range. 

## Activating the Pre-Meal Override

You can activate the *Pre-Meal* Override by pressing the icon that looks like a timer :material-camera-timer: between a f&#8203;ork and a knife :fontawesome-solid-utensils:.

It  will stay active for:  

* one hour, or
* until carbs are entered, or 
* until the *Pre-Meal* Override is manually cancelled by pressing the icon again.

*Pre-meal* Override will automatically end when one of those three things happens, whichever comes first will end the pre-meal preset.

!!! info "How to Tell If an Override Is Active?"
     *Loop* will indicate that an Override is active by showing a darker blue bar on the blood glucose chart showing the duration and location of the target.
 
The original intent of the *Pre-Meal* Override was to help give a gentle, easy pre-bolus effect to help lessen a post-meal blood glucose spike. By lowering your Loop's target going into a meal, you can get a "pre-bolus" effect because Loop will aim for that lower target and thus tend to set a little more aggressive insulin delivery while the target is active. Loop will recognize the "extra" insulin that has been delivered while *Pre-Meal* is active, and *Loop* will smartly take that into account when it is finally time to recommend a bolus at meal entry time.

*Pre-meal* Override won't replace the utility of a true pre-bolus in most situations, but it can be useful in many situations beyond simply helping meals. This lower target can help *Loop* be more aggressive:

* During stressful events where adrenaline might be causing increased blood glucose
* During exercise that may tend to increase blood glucose
* During illness that is causing high blood glucose
