# Tidepool

{Disclosure: The original author of this page, Katie DiSimone, is employed by Tidepool. She used Tidepool before becoming an employee, and continues to use Tidepool for her Looping experience. She was not prompted to say anything in particular with regards to this information, it is written free-of-influence from her employer based on her own evaluation of Tidepool's services.}

## Tidepool's mission
In Tidepool's own words, their commitment to diabetes data and accessibility is pretty clear:

>Tidepool's mission is to make diabetes data more accessible, actionable and meaningful for people with diabetes, their care teams and researchers.

>We believe that connected data leads to better decision-making. Tidepool’s free software liberates data from diabetes devices, and places it in context of the real world. Tidepool is designed to help you discover insights and bring context to your diabetes management. And, to help make your data more actionable, we allow you to share your data with anyone you choose: caregivers, clinicians, endocrinologists, friends, researchers – anyone.

## Tidepool's Website
Tidepool's data presentation is easy on the eyes. Lots of easy colors, logical data layout, quick to access important information...basically a breeze to get your needed data and get on with your analysis.

<p align="center">
<img src="../img/tidepool_sample.png" width="750">
</p>

To use Tidepool, the process is pretty standard:

* Create a free Tidepool account to become the warehouse for your diabetes data.
* Upload device data to your account.

Children with type 1 diabetes can have their own data account, and parents can have a cargiver account. Users can also choose to share data with their encrinology clinic. 

### How do you upload data into Tidepool account?

There are two methods for uploading different data to your Tidepool account:

* **Tidepool Uploader** (program on your computer) -   Tidepool Uploader supports a large variety of current diabetes devices in the market; Animas, T-slim, Medtronic, Omnipod, Dexcom, and more. The full list of devices is [here](https://tidepool.org/products/tidepool-uploader/#devices). To upload the data from these devices, you download the free Tidepool Uploader program, connect your device to the computer according to the instructions provided in the Uploader, and your data is then securely uploaded and stored in your Tidepool account. Most users will perform uploads on a semi-regular basis; weekly, monthly, or prior to each clinic visit.  

* **Tidepool Mobile** (app on your phone) - Tidepool Mobile is available for both Android and iOS/iPhone users. Tidepool Mobile is a companion app to Tidepool that lets you add notes about meals, exercise or anything else. See your CGM, pump, and meter data alongside any notes you add. Track your favorite meals and your regular exercise, and learn from what happens.  

!!!info ""
    In summary, the Uploader is for uploading the numeric data from your various diabetes devices and the Mobile app is for adding the contextual information and notes to make your numeric data more useful.

### Does Tidepool Uploader work for Loop users?
There has been a lack of ability to get most Looper's data into Tidepool using the Tidepool Uploader. The only Loop-compatible pump supported in Tidepool Uploader is the x23/x54 pumps, so users of the x15 and x22 pumps cannot upload their pump data. Furthermore, the Medtronic pump still suffers from the lack of internal storage sufficient to store more than 7 days worth of Looping data. 

However, there has been a very exciting development! Tidepool's Mobile iOS app has been updated to upload Apple's HealthKit data into Tidepool. Since Loop uses HealthKit to store all of your insulin, carbohydrate, and Dexcom CGM data, this means Tidepool can now upload the full suite of available Loop information. So, there's no need to use Tidepool Uploader for Loop users...their Tidepool Mobile app can take care of the needed connections. Read below for lots of details about this important development.

### How can I share my Tidepool data?
Sharing the data is simple. You can click on your account’s Share option and enter in the email addresses for those that you want to share with. Those people will need a Tidepool account. If they don’t have one currently, they will follow easy prompts for an account setup after they’ve received your share invitation. Clinics using Tidepool will have a Tidepool account email that you can add to your account, enabling the clinic to easily view your data. You can also remove access for anyone with a simple click.

<p align="center">
<img src="../img/share_tidepool.png" width="550">
</p>

## Viewing your Tidepool data

There are two distinct viewing options for your Tidepool data, and they are not identical. You can either view your data:

1. Using a desktop computer using the Chrome browser or 
2. Using your Mobile app and associated notes

!!!info ""
    Currently, only the Chrome desktop browser is compatible. You will not be able to use Safari or other browsers to view the data, nor will using Chrome application on a mobile browser work. If you want to see your data on a computer, you need to use the Chrome browser. If you want to see your data on your phone, you must use the Tidepool Mobile app **<i>and</i>** use an associate note to view the data surrounding the note's time frame. Mobile data viewing is not a live stream, but rather available as "bookmarked" time periods anchored by notes.

### What Loop data will you see in desktop Chrome?
You will see your Loop's temporary basals, Dexcom CGM readings, boluses, notes, and various metrics about your data distribution. If you separately load your blood glucose meter or any other supported device to Tidepool, those will also overlay. See discussion below about what’s missing for Loop users and still being developed (hint…carbs aren’t showing yet).

<p align="center">
<img src="../img/loop_in_tidepool.png" width="750">
</p>

<p align="center">
<img src="../img/loop_in_tidepool2.png" width="750">
</p>

<p align="center">
<img src="../img/loop_in_tidepool3.png" width="750">
</p>

### What Loop data will you see in the Tidepool Mobile app?
The Tidepool Mobile app is not a live-viewing app of looping data. For people coming from Nightscout, this may be a bit confusing but realize the intended purpose of the Tidepool Mobile app isn’t live-viewing. It is the place that you can (1) upload/sync HealthKit data, (2) easily add/edit/delete notes to the data set, and (3) search for notes and view Loop data surrounding that note.

**In fact, you will basically see NO data in the Tidepool Mobile app unless you have Tidepool data uploaded and notes are added.** Once you add a note, you are basically placing a bookmark on the data set. You will be able to click on the note and see 7 hours of old data before the note, and then the note will continue to collect 7 hours of data to display after the note. So, technically, you’ll be able to refresh the app’s view to see current data for approximately 7 hours after a note is placed.

For example, here’s a sample data set below.  Over the last couple hours, my daughter noticed that she was staying above target (unusual for her on Loop with the meal she had) for quite a while. She had given a couple small corrections (see the two 1 unit correction boluses) without result. Which then she started her secondary troubleshooting…if it’s not the food, maybe it’s the infusion site? She realized it has been 4.5 days since changing her site. She changed the site, and logged a note using the Tidepool Mobile app. That note shows on my phone's Tidepool Mobile app, shows up on her Tidepool data for her endo to see too, and we can refresh the view to see how blood glucose trends for the next 7 hours after the site change.

<p align="center">
<img src="../img/ios_tidepool_example.png" width="250">
</p>

## Tidepool's Mobile app for iOS/iPhone
As part of Tidepool Loop development, Tidepool has been updating its iOS/iPhone app to integrate with Loop user's data stored in Apple's HealthKit database.

### How does the Loop data upload work?
The Tidepool Mobile iOS app is getting an update to sync a Looper’s diabetes-related HealthKit data into their Tidepool account. The app will continuously upload that data so long as the Tidepool Mobile app is open, even if it is only open in the background. That data will then be viewable in two places: on the Tidepool Mobile app itself or on your Tidepool account using desktop Chrome browser (although they are not identical viewing platforms, see discussion below). This means a Loop user will not have to plug any of their devices into a USB cable in order to upload their information to Tidepool.

### Is the Tidepool Mobile app a replacement for Nightscout?
Nope. This was not designed nor intended to be a replacement for your Nightscout site. They complement each other, rather than compete. This new upload of Loop data will allow Loop users and their clinics to have a powerful tool to analyze Loop data through an easy-to-use, shared hub.

### Are there any known issues with Loop and Tidepool Mobile app?
Sure, of course…you may have missed the word BETA in all the excitement. There are some bugs currently being worked out. For example, the carbs associated with the Loop uploads are being uploaded by Tidepool Mobile, but they aren’t currently rendered in your desktop view or the Tidepool Mobile view. If you look at the Daily view screenshot a little above…notice that the little yellow carb circles are missing? We will be getting that bug addressed. Soon, hopefully, your chart will include little carb circles like below (rendered with my crude skills for demonstration only).

<p align="center">
<img src="../img/tidepool_known_issues.png" width="750">
</p>

There are some calculated data areas that need updating, too. If you see a NaN (“not a number”), it is a placeholder for where a number will eventually go. We know and we don’t like seeing those either. We are keeping a list of the things that need addressing.

### What cool thing can you use this Tidepool Mobile app for?
I think the best thing about this Tidepool Mobile app (other than importing all Anna’s valuable Loop data automatically) is that I can keep a really easy searchable log of meal boluses. If you are still learning new meals in Loop…how much to bolus, how long of a carb absorption…these notes are searchable and super easy to add. Learning how to bolus for that Tofu Breakfast Burrito? (Don’t ask, that’s really a thing Anna is eating now.) Simply record a note of how you bolused for it. If you want to, come back afterwards and leave yourself some suggestions for the next time to try. This searchable information can also help for those teens that are learning and exercising independent skills. If they aren’t sure of how to bolus for a meal, this could give them an easy way to get tips from past success without necessarily having to stop and ask a parent. As much as a parent might scoff at the idea of a kid looking up a meal, if the alternative is asking a parent…that might be all the motivation it takes. Anna learned this little trick pretty quickly. Or how about co-parenting? Want to leave a note that another parent or caregiver can look up? How were the last Chicken McNuggets bolused for or when was the last site change can easily be tracked and retrieved with notes.

Search for the word burrito (doesn’t have to be a hashtag) and any notes with the word “burrito” will be available for review, as well as any added comments.

<p align="center">
<img src="../img/ios_tidepool_example2.png" width="450">
</p>

Another useful thing to track…hormones. What day-of-the-month and how did I change the basals? Looking to find patterns in those female hormones? This could be a really slick tracking tool to easily log periods of insulin resistance and what part of the cycle they are occurring at.

### Is the Tidepool Mobile app only for Loop users?
The updated Tidepool Mobile app will upload diabetes-related Health app data regardless of the source. Loop users store their data in Health app, so this is a nice fit. Other diabetes devices (e.g., OneDrop BG meter) and apps (e.g., Spike and Dexcom) also store their data in Health app. Some people even manually enter their diabetes data into Health app. For all those uses, the Tidepool Mobile app will upload the Health data. OpenAPS does not store its data in Health app, so this will not upload OpenAPS-related data.

### How can I get the Tidepool Mobile app?
Frankly, probably a lot of Loop users may not be familiar with Tidepool at all…so this post was part introduction and part announcement. Tidepool’s goal is to get a limited number of beta testers to help us identify bugs or problems.  We’d like to cover a variety of  Health-app users such as Loop, Dexcom, InPen, OneDrop, SpikeApp, SugarSense, OneTouch Reveal, and Accu-Check Connect. We’d like people who are willing to report bugs and won’t curse my name if you find one.

