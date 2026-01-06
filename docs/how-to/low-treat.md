# Low Treatments

Low blood glucose will still inevitably happen at some point, even with OS-AID use. A difficult carb count, illness, equipment malfunction, exercise...you name it, eventually something will help to cause a low glucose. 

## How to Treat

Overall, most people find that they can treat low glucose with **fewer rescue carbohydrates** than they needed before using a hybrid-closed loop system. Typically your OS-AID suspends your basal insulin before a low has been reached; consequently, you have less insulin on board (IOB) to overcome with carbohydrates. In other words, your OS-AID takes some of the momentum out of an upcoming glucose dip...which also makes it easier to pull up from declining glucose.

If you notice that your old way of treating low glucose is leading to rebound glucose greater than you expect/desire, eventually consider decreasing the amount of carbohydrates you use to treat predicted/upcoming low glucose.

!!! tip "Why Loop Prevents Deeper Lows"
    As explained in [Think Like a Loop](think-like-loop.md), Loop suspends insulin delivery (Action 1) when ANY part of your predicted glucose curve goes below your suspend threshold. This early suspension is why you typically need fewer carbs to treat lows with Loop.

## Logging Low Treatments

Another common question for new OS-AID users is whether to enter the carbohydrates used to treat a low blood sugar. The answer is that there is not a great agreement on how to deal with low treatment entries. The decision is dependent, often, on factors not just about the OS-AID algorithm; factors such as extra effort, use of OpenAPS's autotune (which needs all carbohydrate inputs to do a better estimation), or desire to have more thorough clinical records.

For the most part, you do not *have* to enter low treatments. Not logging low treatments will work out pretty well if you are not overtreating the low and you have your ISF pretty well determined. In the event you overtreat lows and your ISF value is too low, your OS-AID may be more likely to overtreat rebound situations.

One rule of thumb is that if you know you over-treated a low, and you normally log carbohydrates, then log the "extra" that you consumed.

## Roller Coaster after Low Treatment

If you are roller coastering glucose after treating lows (going low, quick rise from the treatment carbs, then drop again from Loop's high temporary basals during the rise, and then repeating pattern), here are some tips:

1. **While treating the low glucose**, try setting a temporary [override target](overrides.md) higher than your normal target with for an hour to help keep Loop from aggressively treating a rebound.

2. **Consider adjusting insulin needs in your override** When changing the insulin needs you are decreasing the effective scheduled basal rate and increasing (making weaker) the insulin sensitivity factor and carb ratio [Low Override](overrides.md#low-override)


If your ISF is set to a value that is too low compared to what it really should be, one of the most common symptoms you'll see is a roller coaster of blood glucose where the temporary basals are cycling between zero and strong high temporary rates. Here are some example graphs from *Looped* group. These are examples where too low of ISF is more than likely a large factor in the roller coaster (doesn't mean it is the only culprit and is more difficult to ferret out when food is involved like the second graph).  But, lightning bolt high temporary basals followed by very quick blood glucose drops and zero temps is usually too low of ISF value...raise the ISF value (e.g., go from 50 to 55) to help Loop know that each unit of insulin is actually having more impact than you'd previously thought.

![ISF 1](img/isf1.jpg){width="650"}

![ISF 2](img/isf2.jpg){width="650"}

![ISF 3](img/isf3.png){width="650"}


