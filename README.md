> Context :

A company started working on the mobile apps vertical in July 2020. After preliminary expert calls with mobile gaming editors, it appeared that 2 important labels were needed in their datasets to make any kind of useful analysis: the app title (eg “Candy Crush Saga”) and the editor name (eg “King”)

Using receipt data from the App Store (iOs) and the Play Store (Android), This company can collect one very valuable information for mobile apps editors: in-app purchases (IAP) data, which are any type of transaction where a user pays from inside an application

Unfortunately, App Store receipts display very little information: we can only collect the name of the IAP (eg “gros sac de gemmes”), the url of the logo of the application and the price of the IAP

Using external data, we managed to collect a database of logo URLs and corresponding app name and editor name
     
> Strategy :     

    1. Enrich the table extract to add an app title and editor name for each record by matching the images behind each URL with the ones in the external source extract
    2. Analyze the enriched extract and make conclusions on the impact of the Covid confinement in France 

> Here are the conclusions :

<div id="header" align="center">
<img src='src/app_distribution.png' width="600" height="400">
</div>

All the orders are mostly between 0 & 20 euros.

<div id="header" align="center">
<img src='src/total_order_editor.png' width="600" height="400">
</div>

Netflix and Supercell represent the largest market share.

<div id="header" align="center">
<img src='src/global_market.png' width="600" height="400">
</div>

The confinement seems to be beneficial for the global market.

<div id="header" align="center">
<img src='src/total_paid_editors_conf.png' width="600" height="400">
</div>

Disney has launched their app during the 2020 confinement,
which could explain the global profit of the confinement.
Let's have a look by app domain.

> GAMING APPS

<div id="header" align="center">
<img src='src/playrix_king.png' width="600" height="400">
</div>

Playrix and King have same trend. The confinement is
beneficial for turnover for the first month but people
lose interest during the second month and the month
after.

<div id="header" align="center">
<img src='src/Supercell_app.png' width="600" height="400">
</div>

During the first month, 2020 confinement had a
negative impact on the 3 Supercell apps. Clash Royale
and Clash of Clans stabilised during the second
month. Brawl Stars was the most impacted but people
regained interest right after.

> DATING/STREAMING APPS

<div id="header" align="center">
<img src='src/Tinder.png' width="600" height="400">
</div>

Tinder was very impacted by the covid-19 with a -70%
evolution rate the first month of the confinement. It
seems people had a little interest on Tinder app
during confinement but right after they used it a lot.

<div id="header" align="center">
<img src='src/Streaming_app.png' width="600" height="400">
</div>

Both of the streaming apps seem to have the same
trend. Over the year, Netflix continued to rise but
CANAL + stabilized. It is difficult to estimate the impact
of the covid 19 confinement on those apps.
