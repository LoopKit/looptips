# Health App

## Overview of HealthKit and Health

There's often confusion over the terminology surrounding Apple's health data storage so let's start there.

* **HealthKit** -- Apple's iOS database for storing health-related data. App developers can choose to use HealthKit to store information from their apps such as heart rate, blood glucose, insulin use, and a long list of other parameters

![Health Data](img/health-data.png){width="350"}
{align="center"}

* **Health App** -- Apple allows iOS users to manage HealthKit permissions and view stored HealthKit data through the use of Apple's Health app (standard on iPhones and iPods, but not available on iPads).  

## Loop's use of HealthKit

!!! info "Loop and HealthKit"
    Older versions of Loop, before version 3.0 was released, required the use of *Apple* Health for data storage older than 3 hours. This is no longer true.

    Loop version 3.x uses internal core storage of 7 days of data independent of *Apple* Health.

When you first install Loop onto your iPhone, you will be asked to setup  Loop&#39;s access to the HealthKit database. It is recommended that you enable iPhone's HealthKit for these interfaces

*Loop* App

* write to:
    * Blood Glucose, Carbohydrate and Insulin Delivery
* read from:
    * Blood Glucose, Insulin Delivery and Sleep

*CGM* App

There are a number of *CGM* apps. If the option is available, configure them with these permissions:

* write to:
    * Blood Glucose

Depending on the app, there may be other items you want to have the app read from *Apple* Health. That depends on the CGM.

!!! warning "*Dexcom* CGM"
    If you use one of the *Dexcom* Apps, enable it to write Blood Glucose to Apple Health.
    
    If that is not enabled, *Loop* will still function but it will not display blood glucose values older than 3 hours old.

You can always check your HealthKit settings by opening the Health App, clicking on *Sharing* at the bottom bar, scroll down and tap on the row labeled **Apps** and then clicking on the app's name you are interested in, for example, Loop.

Potential conflicts can arise when third-party apps are granted access to HealthKit permissions that may interfere with  Loop&#39;s specified data permissions.

With Loop 3, it is no longer the default that the *Loop* app reads carbohydrate from Apple Health. This prevents a problem that used to happen where third-party food apps were used to record meals. You can customize your *Loop* app to change this setting, but be aware that carbohydrate entries in HealthKit that were created by non-Loop apps will not be able to customize carbohydrate absorption times nor be edited later if needed. Refer to [LoopDocs: Carbohydrates and Apple HealthKit](https://loopkit.github.io/loopdocs/faqs/apple-health-faqs/#carbohydrates-and-apple-healthkit){: target="_blank"}.

## Your use of Health App

Summaries of your carbohydrates, insulin, and blood glucose results can be found by clicking on the *Health Data* at the bottom bar, and then selecting either the large *Nutrition* box (for carbohydrates) or smaller *Results* line (for insulin deliveries and blood glucose results).


![Health Data](img/health_data.jpg){width="350"}
{align="center"}

If you toggle on the "add to favorites" slider for the individual data categories (insulin, blood glucose, carbohydrates), the data from those categories will be added to your *Today* view for easy quick reference and access.

![Today Health](img/todayhealth.jpg){width="500"}
{align="center"}

The summary data for the categories can help you follow monthly trends, help identify periods of insulin sensitivity/resistance, evaluate total daily insulin use, breakdown of basal rate vs bolus insulin, and carbohydrate consumption. You can sort your data trends by day, week, month, or year views and scroll back through time in each of those data trends.  You can even quickly use these data for endocrinology appointment discussions...as they provide the endocrinologist with a very quick and useful set of data points directly from your *Loop*.


![Health 1](img/health1.jpg){width="750"}
{align="center"}

If you drag two fingers separately like you are spreading them apart, you can get averages for the data set your fingers are covering, as shown below.


![Health Average](img/health-avg.jpg){width="350"}
{align="center"}
