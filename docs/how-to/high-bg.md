# Stuck on High (Glucose)

!!! info "Safety consideration"
    If the continued delivery of corrective insulin fails to bring down high glucose, remember to follow your doctor's recommendations for ketone testing, hydration, and/or more frequent glucose monitoring. Check for equipment failure (infected pump site? blocked cannula?). Try fresh insulin. Contact your doctor immediately if you are experiencing sustained high glucose despite continued insulin delivery and corrections.

*"How do I deal with high glucose that seems to be stuck?"*

> When you and your *Loop* are disagreeing about how much insulin you need to bring down a high glucose value, take a deep breath. Unfortunately, most of the time our disagreement is rooted in the impatience that the pump's insulin works so dang slow. We get tired of waiting another 4-6 hours until glucose will be back in range after a correction.

## Decision Guide: What to Try First

Before we start overriding Loop's predictions with manual actions, ask yourself these questions to help guide potential corrective actions:

### 1. First, Rule Out Equipment Issues

**Could this be caused by site failure or bad insulin?**

- ✅ **Try first**: Check pump site, replace if needed, try fresh insulin
- See [Site Failure](site-fail.md){: target="_blank" } for details

### 2. Is This Meal-Related?

**Is this consistently only after meals? Did I underestimate carbs?**

- ✅ **Try first**: [Adjust meal entries](#adjusting-meal-entries) to reflect actual carbs
- Alternative: [Provide pending insulin as bolus](#pending-insulin-as-bolus) to speed correction
- Alternative 2: If this happens frequently, you may need to [adjust your settings](../settings/adjust.md){: target="_blank" }

### 3. Is This Short-Term? (Hours to 1-2 days)

**Are you sick or stressed? Acute illness? Anaerobic exercise?**

- ✅ **Try first**: [Set lower temporary override targets](#lower-temporary-targets)
- Alternative: [Provide pending insulin as bolus](#pending-insulin-as-bolus) to speed correction
- Alternative 2: [Use an override](overrides.md){: target="_blank" } for the current situation

### 4. Is This Medium-Term? (Several days)

**Are you hormonal? Taking medication (like steroids)?**

- ✅ **Try first**: [Adjust settings](#adjust-settings) - increase basal rates by ~10%
- Can use overrides temporarily while testing new settings

### 5. Is This Long-Term or Unexplained?

**Has this been going on for a long time? Happens even overnight? Have you open loop tested your settings?**

- ✅ **Try first**: [Adjust settings](#adjust-settings) - likely need basal increase
- Consider: you may need to [adjust your settings](../settings/adjust.md){: target="_blank" }

### 6. Is IRC Enabled?

**The Integral Retrospective Correction (IRC) option can handle some glucose excursions.**

- ✅ **Safety first**: [LoopDocs IRC](https://loopkit.github.io/loopdocs//loop-3/features/#integral-retrospective-correction-irc) - if you have never used IRC, please read up on it in LoopDocs
- It is likely you will need to modify your settings - in general, the ISF folks need when IRC is enabled tends to be about 10% larger (weaker) of a number than when IRC is disabled


---

## Solutions in Detail (Ordered by Common Usage)

## Lower temporary targets

If you to believe the high glucose is a short-term issue, due to acute stress or anaerobic exercise for example, then using temporary lower override targets will help *Loop* be more aggressive at providing additional insulin. The pre-meal target would be a quick, easy implementation of this tool.

This technique, and the deliver [pending insulin as a bolus](#pending-insulin-as-bolus), are good to help control the urge to "rage" bolus which often yields an overcorrection and subsequent low blood glucose. These two techniques used in combination are often successful for most short-term situations or meals that are just taking a long time to "burn out".

## Pending insulin as bolus

To help correct a high glucose, *Loop* will apply a high temporary basal set to deliver the recommended dose over 30 minutes time when using `Temp Basal Only` strategy or a fraction of the recommended dose every 5 minutes when using Automatic Bolus strategy. If you are stuck on a high glucose and want to speed up the correction, you can try to "hurry" along the correction by opening  Loop&#39;s bolus tool. Within the information screen, you will see a "pending insulin" amount. That amount represents the amount of corrective insulin *Loop* plans on delivering. You can choose to manually enter in that amount on the bolus deliver line as an upfront correction bolus rather than waiting for it to be delivered. This generally represents a pretty easy, safe way to help reasonably speed up a correction.

The safety consideration for this is that you do not want to unintentionally stack insulin by using this technique repeatedly in a short period of time. Wait a reasonable amount of time, such as an hour or two, to give insulin a chance to start to affect blood glucose. If the correction still hasn't helped, you may want to consider another technique to help bring down blood glucose.

## Adjusting meal entries

Carbohydrate, fat, and protein estimations for bolusing are frequently a guessing game...and we've all guessed wrong before. If your blood glucose is remaining high due to a food guess gone wrong, you can definitely go back in time and adjust your meal's carbohydrate entry to more accurately reflect what you suspect it should have been. By adjusting the original entry, you'll help *Loop* know that the blood glucose effects it needs to control are greater (total carb entry increase) and/or longer (carbohydrate absorption time extension). Often, you'll find *Loop* will offer an additional bolus immediately after you save your adjusted carbohydrate entry, and/or the temporary basal adjustments will be more aggressive.

## Fake Carbohydrates 

Some people use "fake" carbohydrate entries to push *Loop* to be more aggressive with correcting a high glucose. This can be effective for hyperglycemia due to short-term causes but is not the recommended way of repeatedly dealing with high glucose. If you find yourself regularly using fake carbohydrates often, you may want to consider whether one of your underlying settings needs adjusting.

## Inject or Use Afrezza

You can always take an injection. Or if you use Afrezza, take that.

Typically you want to tell [Loop system about the extra insulin](https://loopkit.github.io/loopdocs//loop-3/features/#non-pump-insulin). But that is a personal choice.

## Prime insulin (Medtronic pumps only)

!!! warning "Medtronic-Specific Technique"
    This technique only applies to Medtronic pump users. Omnipod users cannot use this method.

    For others, see [Inject or Use Afrezza](#inject-or-use-afrezza)

If your Preferred Data Source is left on the default "Event History", *Loop* will not count insulin delivered from "prime" commands in the Medtronic pump. This means that any insulin you deliver through your infusion set while using the prime delivery will not count towards active insulin or insulin on board (IOB).

If you think that you are being affected by a short-term influence that will last for at least 4-6 hours, a conservative amount of primed insulin may help control high glucose more aggressively than *Loop* would have otherwise provided during the stressful event.

**If you choose to deliver insulin via prime command, remember that your active insulin or IOB will not be accurate for 6 hours after the delivery.** Caution should be taken using this method because if the short-term stress suddenly ends and glucose begins to drop again, the drop may be more pronounced than *Loop* predicts due to the untracked primed insulin. 

## Open loop and correct manually

Don't forget that you can always go old-school and open your Loop until the cause of the high glucose is sorted out and you can get back to normal operations.  Site failures are an especially good example of when open looping plus manual correction may be a less frustrating way of dealing with *Loop* during times when prediction just isn't meeting reality. Give IOB a chance to get back to reality by letting open loop run for 4-6 hours and you'll come back after site failure with a more functional *Loop* prediction.

## Adjust settings

Finally, if your underlying cause doesn't appear to be short-term (no site failures, no stressful event, no illness) or food-related (no recent meals, happens even overnight), then you may need to adjust your underlying settings to help *Loop* get a more accurate prediction curve working for you.

Long duration "stuck" high glucose most often means you'll need to increase your underlying basal rate(s). If  Loop&#39;s high temporary basals aren't making meaningful progress towards your correction range within 4-6 hours, and you don't suspect food, stress, or site failure, then a basal increase is likely a good place to start. Many people start with a 10% basal adjustment to begin with and wait to see the effectiveness before making any additional adjustments.

What kind of situations are most likely to need this adjustment? Monthly hormonal cycles and steroids are good examples of when underlying basal rate adjustments for a few days could help tremendously until things return to normal.

With children, settings adjustments may be required frequently.

Consult your healthcare provider if you are at all uncomfortable self-adjusting basal rates.

For more details: see [adjust your settings](../settings/adjust.md){: target="_blank" }.

## Maximum Basal Rate

It is worth mentioning one adjustment that will *not* be helpful in these situations. Increasing your maximum basal rate is very unlikely to resolve a stuck high glucose. Stuck high glucose is the result of Loop predicting that the insulin on board is sufficient to cover the needed correction. The issue is almost never that *Loop* is being limited by a maximum basal rate but rather that *Loop* is predicting that the insulin it has been delivering for awhile is adequate. In other words, *Loop* doesn't even think that it needs to reach that maximum basal rate.  The better adjustment would be to increase your scheduled basal rates and not the maximum basal rate listed in Delivery Limits.
