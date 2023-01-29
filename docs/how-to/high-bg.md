# Stuck on High BG

!!! info "Safety consideration"
    If the continued delivery of corrective insulin fails to bring down high blood glucose, remember to follow your doctor's recommendations for ketone testing, hydration, and/or more frequent blood glucose monitoring. Check for equipment failure (infected pump site? blocked cannula?). Try fresh insulin. Contact your doctor immediately if you are experiencing sustained high blood glucose despite continued insulin delivery and corrections.

*"How do I deal with high blood glucose that seems to be stuck?"* When you and your Loop are disagreeing about the effectiveness of high temporary basals to bring down blood glucoose, take a deep breath. Unfortunately, most of the time our disagreement is rooted in the impatience that the pump's insulin works so dang slow.  We get tired of waiting another 4-6 hours until blood glucose will be back in range after a correction. So before we start overriding Loop's predictions with manual actions, it may be useful to ask yourself some questions first to help guide potential corrective actions:

* Is this temporary or has this been going on for a long time?
* Is this consistently only after meals?
* Have you open loop tested your settings?
* Are you sick or stressed?
* Are you hormonal?
* Are you taking medication?
* Could this be caused by site failure or bad insulin?

Based on the answers to those questions, you may want to choose on of the potential solutions for delivering extra insulin to help:

* Setting lower temporary blood glucose targets
* Providing the "pending" insulin upfront via correction bolus
* Adjusting meal entries
* Fake carbohydrates
* Priming in insulin
* Open loop and correct manually
* Adjust settings

## Lower temporary targets

If you to believe the high blood glucose is a short-term issue, due to acute stress or anaerobic exercise for example, then using temporary lower override targets will help Loop be more aggressive at providing additional insulin. The pre-meal target would be a quick, easy implementation of this tool.

This technique, and the delivery pending insulin as a bolus (described below), are good to help control the urge to "rage" bolusing which often yields an overcorrection and subsequent low blood glucose. These two techniques used in combination are often successful for most short-term situations or meals that are just taking a long time to "burn out".

## Pending insulin as bolus

To help correct a high blood glucose, Loop will apply a high temporary basal set to deliver over 30 minutes time. If you are stuck on a high blood glucose and want to speed up the correction, you can try to "hurry" along the correction by opening Loop's bolus tool. Within the information screen, you will see a "pending insulin" amount. That amount represents the amount of corrective insulin Loop plans on delivering with the currently running 30 minute temporary basal. You can choose to manually enter in that amount on the bolus deliver line as an upfront correction bolus, rather than waiting for it to be delivered over the next 30 minutes. This generally represents a pretty easy, safe way to help reasonably speed up a correction.

The safety consideration for this is that you do not want to unintentionally stack insulin by using this technique repeatedly in a short period of time. Wait a reasonable amount of time, such as an hour or two, to give insulin a chance to start to affect blood glucose. If the correction still hasn't helped, you may want to consider another technique to help bring down blood glucose.

## Adjusting meal entries

Carbohydrate, fat, and protein estimations for bolusing is frequently a guessing game...and we've all guessed wrong before. If your blood glucose is remaining high due to a food guess gone wrong, you can definitely go back in time and adjust your meal's carbohydrate entry to more accurately reflect what you suspect it should have been. By adjusting the original entry, you'll help Loop know that the blood glucose effects it needs to control are greater (total carb entry increase) and/or longer (carbohydrate absorption time extension). Often you'll find Loop will offer an additional bolus immediately after you save your adjusted carbohydrate entry and/or the temporary basal adjustments will be more aggressive.

## Fake Carbohydrates 

Some people use "fake" carbohydrate entries to push Loop to be more aggressive with correcting a high blood glucose. This can be effective for hyperglycemia due to short term causes, but is not the recommended way of repeatedly dealing with high blood glucose. If you find yourself regularly using fake carbohydrates often, you may want to consider whether one of your underlying settings needs adjusting.

## Prime insulin

If your Preferred Data Source is left on the default "Event History", Loop will not count insulin delivered from "prime" commands in the Medtronic pump. This means that any insulin you deliver through your infusion set while using the prime delivery will not count towards active insulin or insulin on board (IOB). 

If you think that you are being affected by a short term influence that will last for at least 4-6 hours, a conservative amount of primed insulin may help control high blood sugar more aggressively than Loop would have otherwise provided during the stressful event.

**If you choose to deliver insulin via prime command, remember that your active insulin or IOB will not be accurate for 6 hours after the delivery.**  Caution should be taken using this method because if the short term stress suddenly ends and blood glucose begins to drop again, the drop may be more pronounced than Loop predicts due to the untracked primed insulin.

Note:  For Omnipod users, Loop does not allow you to prime insulin in. 

## Open loop and correct manually

Don't forget that you can always go old-school and open your Loop until the cause of the high blood glucose is sorted out and you can get back to normal operations.  Site failures are an especially good example of when open looping plus manual correction may be a less frustrating way of dealing with Loop during times when prediction just isn't meeting reality. Give IOB a chance to get back to reality by letting open loop run for 4-6 hours and you'll come back after site failure with a more functional Loop prediction.

## Adjust settings

Finally, if your underlying cause doesn't appear to be short term (no site failures, no stressful event, no illness) or food related (no recent meals, happens even overnight), then you may need to adjust your underlying settings to help Loop get a more accurate prediction curve working for you.

Long duration "stuck" high blood glucose most often means you'll need to increase your underlying basal rate(s). If Loop's high temporary basals aren't making meaningful progress towards your correction range within 4-6 hours, and you don't suspect food, stress, or site failure, then a basal increase is likely a good place to start. Many people start with a 10% basal adjustment to begin with and wait to see the effectiveness before making any additional adjustments.

What kind of situations are most likely to need this adjustment? Monthly hormonal cycles and steroids are good examples of when underlying basal rate adjustments for a few days could help tremendously until things return to normal.

Consult your health care provider if you are at all uncomfortable self-adjusting basal rates.

## Maximum basal rate

It is worth mentioning one adjustment that will *not* be helpful in these situations. Increasing your maximum basal rate is very unlikely to resolve a stuck high blood glucose. Stuck high blood glucose is the result of Loop predicting that the insulin on board is sufficient to cover the needed correction. The issue is almost never that Loop is being limited by a maximum basal rate, but rather that Loop is predicting that the insulin it has been delivering for awhile is adequate. In other words, Loop doesn't even think that it needs to reach that maximum basal rate.  The better adjustment would be to increase your scheduled basal rates, and not the maximum basal rate listed in Delivery Limits.
