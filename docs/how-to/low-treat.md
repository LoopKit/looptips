# Low Treatments

Low blood glucose will still inevitably happen at some point, even with Loop use. A difficult carb count, illness, equipment malfunction, exercise...you name it, eventually something will help to cause a low blood glucose. 

## How to Treat
Overall, most people find that they can treat low blood glucose with fewer rescue carbohydrates than they previously used to. Since typically Loop will have been suspending your basal insulin before a low has been reached, you will typically have less IOB to overcome with carbohydrates. In other words, Loop takes some of the momentum out of an upcoming blood glucose dip...which also makes it easier to pull up from declining blood glucose.

If you notice that your old way of treating low blood glucose is leading to rebound blood glucose greater than you expect/desire, eventually consider decreasing the amount of carbohydrates you use to treat predicted/upcoming low blood glucose.

## Logging Low Treatments

Another common question for new Loop users is whether to enter the carbohydrates used to treat a low blood sugar. The answer is that there is not a great agreement across all Loop users on how to deal with low treatment entries. The decision is dependent, often, on factors not just about the Loop algorithm; factors such as extra effort, use of OpenAPS's autotune (which needs all carbohydrate inputs to do a better estimation), or desire to have more thorough clinical records.

For the most part, you do not *have* to enter low treatments. Not logging low treatments will work out pretty well if you are not overtreating the low and you have your ISF pretty well determined. In the event you overtreat lows and your ISF value is too low, your Loop may be more likely to overtreat rebound situations.

## Roller Coaster after Low Treatment

If you are roller coastering blood glucose after treating lows (going low, quick rise from the treatment carbs, then drop again from Loop&#39;s high temporary basals during the rise, and then repeating pattern), here are some tips:

* While treating the low blood sugar, try setting a temporary workout target of an hour to help keep Loop from aggressively treating a rebound.  
* Consider lowering your maximum basal rate in Loop (within the Delivery Limits setting). This will limit Loop's ability to aggressively treat the rebound rise and allow you to work on getting your settings adjusted if needed.  
* Consider raising your ISF value (for example, if your ISF is set to 50, consider raising the value to 55) to help Loop understand that a smaller magnitude of insulin adjustment is needed. In other words, tell Loop that insulin is packing a bigger punch than you'd previously thought.  

If your ISF is set to a value that is too low compared to what it really should be, one of the most common symptoms you'll see is a roller coaster of blood glucose where the temporary basals are cycling between zero and strong high temporary rates. Here are some example graphs from *Looped* group. These are examples where too low of ISF is more than likely a large factor in the roller coaster (doesn't mean it is the only culprit and is more difficult to ferret out when food is involved like the second graph).  But, lightning bolt high temporary basals followed by very quick blood glucose drops and zero temps is usually too low of ISF value...raise the ISF value (e.g., go from 50 to 55) to help Loop know that each unit of insulin is actually having more impact than you'd previously thought.

![ISF 1](img/isf1.jpg){width="650"}

![ISF 2](img/isf2.jpg){width="650"}

![ISF 3](img/isf3.png){width="650"}


