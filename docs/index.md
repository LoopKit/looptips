# Introduction

Welcome to LoopTips! The purpose of these pages is to help you make the most of your DIY closed-looping experience.

## Who Should Use LoopTips?

LoopTips is designed for people who:

- Already have Loop built and running
- Want to optimize their Loop settings and outcomes
- Need practical guidance on using Loop in daily life
- Want to understand how Loop makes decisions

If you haven't built Loop yet or need technical troubleshooting, visit [LoopDocs](https://loopkit.github.io/loopdocs/){: target="_blank" } first.

## LoopTips vs LoopDocs

Think of these two resources as complementary guides:

- **LoopDocs**: Building, installing, and technical troubleshooting
- **LoopTips**: Understanding Loop's algorithm, optimizing settings, and improving blood glucose (BG) outcomes

Some pages that originated in LoopTips are now included in LoopDocs. Don't be surprised when you find links between the sites. The color bar is deliberately a different shade to help you know where you are.

## How to Use This Documentation

**Start Here:**

1. **Settings** - Learn why settings matter and how to configure your initial settings correctly
2. **Think Like a Loop** - Understand how Loop makes decisions (essential reading!)
3. **Data Tools** - Set up tools to track and analyze your Loop data

**Daily Management:**

- CGM habits, managing insulin on board (IOB), treating lows, and using overrides

**Special Situations:**

- Exercise, site failures, being stuck on high BG, showering/swimming

**Data & Analysis:**

- Apple Health, Nightscout, Tidepool, and Perceptus for reviewing your Loop data

## Feedback Welcome

Your feedback helps improve these documents. Please share comments at:

- [Looped Facebook Group](https://www.facebook.com/groups/TheLoopedGroup){: target="_blank" }
- [Loop and Learn Facebook Group](https://www.facebook.com/groups/LoopandLearn){: target="_blank" }
- [Loop's Zulipchat](https://loop.zulipchat.com/#narrow/channel/270362-documentation/topic/LoopTips){: target="_blank" }

## What is a closed loop?

The U.S. Food and Drug Administration (FDA) has a general definition of an "artificial pancreas device system" (aka closed loop system) [on their website](https://www.fda.gov/medicaldevices/productsandmedicalprocedures/homehealthandconsumer/consumerproducts/artificialpancreas/ucm259548.htm#illustration){: target="_blank" }, quoted below.

![FDA Image](img/fda-image.png){width="450"}
{align="center"}

>*"Most Artificial Pancreas Device Systems consists of three types of devices already familiar to many people with diabetes: a continuous glucose monitoring system (CGM) and an insulin infusion pump. A blood glucose device (such as a glucose meter) is used to calibrate the CGM.*

>*A computer-controlled algorithm connects the CGM and insulin infusion pump to allow continuous communication between the two devices. Sometimes an artificial pancreas device system is referred to as a "closed-loop" system, an "automated insulin delivery" system, or an "autonomous system for glycemic control."*

>*An Artificial Pancreas Device System will not only monitor glucose levels in the body but also automatically adjust the delivery of insulin to reduce high blood glucose levels (hyperglycemia) and minimize the incidence of low blood glucose (hypoglycemia) with little or no input from the patient."*

## What is Loop?

The Loop app is a do-it-yourself closed loop algorithm and user interface, developed through the work of community volunteers. You can read about the history of Loop development in LoopDocs. Loop predicts future blood glucose based on basals, carbohydrate intake, insulin deliveries, and current CGM readings. These blood glucose predictions provide Loop with the information needed to recommend a temporary basal rate to attain a targeted glucose range in the future. The system can either operate as an “open loop” by making recommendations to the user for their approval before enacting or as a “closed loop” by automatically setting the recommended temporary basal rate.

As exciting as this sounds...we should first get the caveats out of the way.  There are some limitations on what kind of pumps/equipment are required.  This system doesn't work with most pumps and requires you to do some work. The pumps that are supported and the directions for building are thoroughly covered in [LoopDocs](https://loopkit.github.io/loopdocs/){: target="_blank" }.

## Terminology Used in This Documentation

Throughout LoopTips, we use standard abbreviations for common diabetes terms:

- **BG** = Blood Glucose (also referred to as "blood sugar")
- **IOB** = Insulin On Board (active insulin in your body)
- **COB** = Carbs On Board (carbohydrates still being digested)
- **ISF** = Insulin Sensitivity Factor (how much one unit of insulin lowers BG)
- **CR** = Carb Ratio (how many grams of carbs are covered by one unit of insulin)
- **DIA** = Duration of Insulin Action (how long insulin remains active)

When we say "correction range" or "target range," we're referring to the same thing - your desired BG range configured in Loop settings.

## Disclaimer

While it may seem obvious, please consult with your healthcare professional regarding your diabetes management. The suggestions and discussion in LoopTips are not a one-size-fits-all nor intended to replace the input from your doctor. You take full responsibility for building and running this system and do so at your own risk.

