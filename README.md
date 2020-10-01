# Hate crime at football matches hit a three-year high #

287 incidents of hate crime at the end of the 2019/20 season is the highest number ever recorded in a single campaign.

The figure marks a **33% increase from the previous year**.

A hate crime can be defined as when a perpetrator is motivated or demonstrates hostility towards the victim's disability, race, religion, sexual orientation or transgender identity. 

The figures were all reported at football matches in a new experimental statistic from the [Home Office](https://www.gov.uk/government/statistics/football-related-arrests-and-banning-orders-england-and-wales-2019-to-2020-season)

Racially motivated hate crimes were the most common, with 214 reported incidents. This is up from 152 in the previous year.

Talking about the figure, founder of [Show Racism the Red Card](https://www.theredcard.org/) Ged Grebby said it was "worrying".

**"Racism is on the rise in society which means it will come into football. You cannot keep it away. It does not surprise us and it is a worrying trend.**

**"Education is key and hopefully we can all step up the efforts to do more."**

<iframe title="Incidents by hate crime type" aria-label="chart" id="datawrapper-chart-FEANJ" src="https://datawrapper.dwcdn.net/FEANJ/3/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="466"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

**Why does it matter?**

Overall, football banning orders and arrests have decreased.

The number of new banning orders issued fell by 34% to 360 compared to last year. Also, arrests dropped 21% to 1,089.

However, arrests made for racist and indecent chanting had a significant rise. 

<div class="flourish-embed flourish-chart" data-src="visualisation/3893202" data-url="https://flo.uri.sh/visualisation/3893202/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Even with the findings, Grebby remains optimistic that the situation is improving:

**"There has been huge progress over 30/40 years against racism. The Black Lives Matter movement was a massive show of strength. It has given us a huge amount of public support.**

**"We are putting calls out to educate people online and our output of short films has really stepped up. We are doing more on Facebook, Instagram and TikTok. All the things to generate a stronger anti-racism message."**

## Function Tutorial ##

**NB:** The majority of the analysis for this piece was through the sort and filter tools in Excel.

The first thing I noticed was that there were leading spaces in the first column. I used the =(LEFT(TRIM) function to remove those.

Another function I used was **IF**.

After I cleaned the arrests sheet, I created a new column next to the latest figures. I titled it 'improvement from last year?'.

I used the following algorithm: =IF(D5<C5,"Reduction","Increase")

D5 was the 2019/20 figure and C5 was the 2018/19 figure. The algorithm simply translates to if the number of incidents is smaller than last year, then print that as a reduction. If not, print increase.

This function allowed me to see which arrest types had increased or decreased. Straight away, hate crime stood out as an incident type that was getting worse.
I used my 'working' dataset to just show hate crimes. I then carried out percentage changes.
