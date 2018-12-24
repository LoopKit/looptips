# Bolus Recommendations

Loop will also recommend bolus insulin corrections when the eventual blood glucose is greater than the correction target and the active insulin is not sufficient to cover the predicted excursion above correction target. Note that Loop never issues a bolus command automatically; all boluses are initiated by the user. 

The bolus dose calculation is identical to the dose equation given in the basal recommendations section, with the exception that:

* the insulin contribution from the currently running temporary basal set by Loop is removed or subtracted from the recommended bolus amount, and  
* the delta is calculated for the top of your correction range, rather than the average of the correction range.

For recently saved carbohydrates where the projected carbohydrate absorption will outlast the insulin activity duration (e.g., very slow digesting meals like pizza or pasta), Loop’s algorithm will inherently decrease the initial meal bolus — to prevent hypoglycemia events that often occur after these meals — by only recommending enough bolus to prevent going below the correction range. As described above, the Loop algorithm computes the recommended bolus such that predicted glucose will not dip below the correction range. This may result in a future blood glucose predicted above correction range, but will prevent a hypo event shortly after the meal (as is sometimes occurs for people giving a "pizza bolus" in traditional pump therapy). Loop will then later make corrections by issuing higher temporary basals. In effect, this algorithm behavior mimics traditional pump therapy of “extended” or “dual wave” bolusing, but with the benefit of added information about actual carbohydrate absorption effects as time goes by.

Finally, Loop checks that the result of the calculations are below the maximum single bolus the Loop user specified in their settings. If the calculated bolus is less than the maximum single bolus setting, then the recommended bolus will be displayed in Loop’s bolus tool.

!!!info "Bolusing safety feature"
    If the current blood glucose, or any predicted blood glucose, falls below the suspend threshold, Loop will not return a recommended bolus. When the minimum blood glucose rises above suspend threshold, the bolus tool will provide a recommended bolus.


## Example long absorption time bolus

For an example of Loop's bolus adjustments using carbohydrate absorption time, let's take a look at an example meal.  This is an example of a long absorption meal. This is a mushroom (arborio) risotto dish with heavy whipping cream and cheese ingredients. While some white rice can be fairly quick acting, after several times eating this dish, the family has noticed that the meal tends to have a longer, slower duration of impact on blood glucose. Using a "taco" icon (3 hours absorption) was causing slight low blood glucose soon after eating the meal. Therefore, they have been using the pizza icon to enter the meal's carbohydrate absorption time.

<p align="center">
<img src="../img/pizza_bolus.jpg" width="400">
</p>

The initial meal entry was 70g at a "pizza" icon aborption time (4 hours). Based on carbohydrate ratio of 8 g/U, the initial bowl of risotto at 60g should have been a bolus of 7.5 units. Loop recommended 5.3 units, or about 70% of the total bolus that would be needed to cover the total carbohydrates. Loop recommended the lower upfront bolus because a full bolus would have overwhelmed the slow absorption of carbohydrates, and the likelihood would be a low blood glucose shortly after eating. 

As the meal was being absorped, Loop was tracking the carbohydrates still remaining to be absorped and expecting that blood glucose values would be rising soon (knowing that there was still insulin needing to be delivered once safely passed the near-meal low blood glucose potential). Loop would have provided the additional insulin via high temporary basals after seeing blood glucose impacts which indicated the potential for a low blood glucose had passed. 

The Loop user then had a second, smaller bowl of risotto about 90 minutes later, and entered 30g at 4 hours absorption again. Notice this bowl of risotto had a bolus recommendation much different than the original bowl. The second bowl had a recommendation of 5 units, much greater amount of bolus relative to the amount of carbs entered than the first bowl had received, and more than the carbohydrate ratio alone would provide (3.75 units). Why the "extra" 1.25 units? Because Loop was including *some* extra bolus amount to cover what it predicted could safely be provided from the amount *not* given in the original bowl's bolus (the original bolus was approximately 2.2 units short of carbohydrate ratio alone recommendation). If the user had not had the second bowl, Loop would have been providing high temporary basals as soon as blood glucose had exceeded the correction range. And in fact, you can see that Loop still provided the remaining insulin via high temporary basals as blood glucose rose after the second bowl, in effect making up the small remaining difference.

