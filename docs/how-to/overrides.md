# Override Targets

Your Loop has two override icons you can select from the main toolbar: *Pre-meal* and *Custom Preset*. When activated, these targets will "override" or take the place of your usual correction range and therefore will affect Loop's decisions about insulin delivery.

* The *Pre-meal* icon can be configured to choose a target as low as the glucose safety range
* The [*Custom Preset*](https://loopkit.github.io/loopdocs/operation/features/overrides/) icon allows you select an existing named preset or create a new one
    * *Custom presets* allow you to adjust the target or the insulin needs sensitivity or both and provide a name so you can save and reuse that preset again.

* In an older version of Loop (version 1.9), and for the *twiist* commercial system, the *Custom Preset* icon is used for the *Workout* feature which only enables the user to change the target and not the insulin sensitivity.

*Loop* will indicate that an override target is active by showing a darker blue bar on the glucose chart showing the duration and location of the target.

You can set the value for the *Pre-meal* targets from the Correction Range area of Loop settings. Generally speaking, *pre-meal* targets are set to value(s) lower than your correction range.

A *Custom Preset* can be created or edited by tapping on the heart icon when no preset is active.

* If a *Custom Preset* is active, it can be edited by tapping on the name of the preset in the heads-up display (HUD)

!!! tip "Why Override Targets Work"
    Remember from [Think Like a Loop](think-like-loop.md): Loop makes all decisions based on your predicted glucose curve relative to your correction range. By changing the correction range temporarily with an override, you change how Loop responds. Lower targets make Loop more aggressive; higher targets make Loop more conservative.

!!! tip "What happens when the `Insulin Needs` setting is modified"
    When the `Insulin Needs` setting is modified in a *Custom Preset*, the effective basal rate (U/hr), ISF and CR are all adjusted in parallel. See the example table below using a pump that can delivery an increment of 0.05 U/hr scheduled basal rate using units associated with mg/dL.

    | Insulin Need | Basal Rate<br>U/hr | ISF | CR | Comment |
    |--:|:-:|--:|--:|:--|
    | 100% | 1.00  | 100 | 15 | Standard Therapy |
    | 90% | 0.90 | 111 | 16.7 | need less insulin than normal<br>more sensitive |
    |120% | 1.20 | 83 | 12.5 | need more insulin than normal<br>less sensitive |
    

## Pre-Meal Targets

The pre-meal target is also known as the **pre-meal preset**.
When activated by pressing the icon that looks like a timer :material-camera-timer: between a f&#8203;ork and a knife :fontawesome-solid-utensils:) it  will stay active for:  

* one hour, or
* until carbs are entered, or 
* until the pre-meal target is manually cancelled by pressing the icon again.

Pre-meal target will automatically end when one of those three things happens, whichever comes first will end the pre-meal target.

The original intent of the pre-meal target was to help give a gentle, easy pre-bolus effect to help lessen a post-meal blood glucose spike. By lowering your Loop's target going into a meal, you can get a "pre-bolus" effect because Loop will aim for that lower target and thus tend to set a little more aggressive insulin delivery while the target is active. Loop will recognize the "extra" insulin that has been delivered while pre-meal is active, and Loop will smartly take that into account when it is finally time to recommend a bolus at meal entry time.

Pre-meal target won't replace the utility of a true pre-bolus in most situations, but it can be useful in many situations beyond simply helping meals. This lower target can help Loop be more aggressive:

* During stressful events where adrenaline might be causing increased blood glucose
* During exercise that may tend to increase blood glucose
* During illness that is causing high blood glucose


## Custom Presets (OS-AID Loop v2 and newer)

The **Custom Presets**, often referred to as Overrides, offered with Loop starting with version 2.0, 31 December 2019, are significantly more flexible than the original Workout Targets.  Please refer to [LoopDocs Overrides](https://loopkit.github.io/loopdocs/operation/features/overrides/).

## Workout Targets (commercial *twist*)

The workout target, when activated, will give a duration choice of 1 hour, 2 hours, or indefinitely.  The workout target set greater than your usual correction range is useful to help in situations where Loop needs to be *less* aggressive with insulin delivery. The most common use of the workout target is to set it in advance and during exercise to help minimize IOB going into a workout. While the name is a hint to the most common timing of this override's use, there are other times when it can be helpful, such as:

* Helping to recover from low blood glucose treatment
* Helping after workouts when still experiencing increased insulin sensitivity
* Helping during illness which tends to lower blood glucose or increase insulin sensitivity

You can read more about the timing and use of workout targets before/during/after exercise on the [Exercise](exercise.md) page of these tips.
