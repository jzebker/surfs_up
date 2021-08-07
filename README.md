# surfs_up
## Overview
W. Avy wants temperature data for the months of June and December in Oahu to determine if his surf and ice cream shop business is sustainable year-round.

## Results ([notebook](https://github.com/jzebker/surfs_up/blob/main/SurfsUp_Challenge.ipynb))

<table align="center">
<tr><th>June Temperatures</th><th>December Temperatures</th></tr>
<tr><td>
<table class="tg">
<thead>
  <tr>
    <th class="tg-r1fe"><span style="font-weight:bold">count</span></th>
    <th class="tg-1uwi">1700.000000</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">mean</span></td>
    <td class="tg-o3c1">74.944118</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">std</span></td>
    <td class="tg-1uwi">3.257417</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">min</span></td>
    <td class="tg-o3c1">64.000000</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">25%</span></td>
    <td class="tg-1uwi">73.000000</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">50%</span></td>
    <td class="tg-o3c1">75.000000</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">75%</span></td>
    <td class="tg-1uwi">77.000000</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">max</span></td>
    <td class="tg-o3c1">85.000000</td>
  </tr>
</tbody>
</table>
</td><td>
<table class="tg">
<thead>
  <tr>
    <th class="tg-5gnq"><span style="font-weight:bold">count</span></th>
    <th class="tg-yddu">1517.000000</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">mean</span></td>
    <td class="tg-o3c1">71.041529</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">std</span></td>
    <td class="tg-1uwi">3.745920</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">min</span></td>
    <td class="tg-o3c1">56.000000</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">25%</span></td>
    <td class="tg-1uwi">69.000000</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">50%</span></td>
    <td class="tg-o3c1">71.000000</td>
  </tr>
  <tr>
    <td class="tg-bsnz"><span style="font-weight:bold">75%</span></td>
    <td class="tg-1uwi">74.000000</td>
  </tr>
  <tr>
    <td class="tg-gt9q"><span style="font-weight:bold">max</span></td>
    <td class="tg-o3c1">83.000000</td>
  </tr>
</tbody>
</table>
</td></tr> </table>

<p align="center">
  <img width="500" src=https://user-images.githubusercontent.com/84994321/128430664-12dd9a24-8829-4ab4-8394-b46e51bb3e57.png>
</p>

• Per the data, it is on average 3.9 °F colder in Dec than in June

• The range of temperatures is slightly more spread out in Dec than in June

• The minimum temperature is lower for Dec than in June relative to other metrics

## Summary

Overall, it is slightly colder on Oahu in December than in June.  We found it to be on the order of a few degrees so it is not wildly different.  There do not seem to be "noticeable" seasons in Hawaii.  Barring hurricane season, the temperature specifically should not affect his ice cream and surfing business.

Additional queries (located in the "Stuff for readme" section of the provided .ipynb file):

• Looking at the data table, we have measurements for precipitation as well as temperature.  We can compare precipitation in June to December in Oahu; without further background on the data, my guess is these are rainfall totals per day.  I do not know if measurements are in cm or in but because we are looking for a trend, the graph may provide additional insight.

<p align="center">
  <img width="500" src=https://user-images.githubusercontent.com/84994321/128430940-6f8cb70c-ba25-422b-a8f2-9240da27dd18.png>
</p>

• The station table has info about location as well as elevation of the stations.  I looked at the average temperature per station by elevation below.  I do not know if the elevation is in feet or meters but, again, the trend is what we are after.  Unfortunately there just aren't enough stations to reliably create any kind of trend.

<p align="center">
  <img width="500" src=https://user-images.githubusercontent.com/84994321/128430994-ce730de8-d539-4fb5-b5e6-46963cf60248.png>
</p>

• According to common travel lore, the northern side of Oahu gets more rain so we COULD try to see this in the data.  We have latitude and longitude for the stations spread around the island but there are only nine locations.  Here is a look at average rainfall and average temperature by location:

<p align="center">
  <img width="400" alt="rainfall_by_loc" src="https://user-images.githubusercontent.com/84994321/128576402-e3804627-98d4-4eba-97c8-8ebee4c9aa49.png">
</p>

<p align="center">
  <img width="399" alt="temp_by_loc" src="https://user-images.githubusercontent.com/84994321/128576431-923500b7-6a32-4a4f-9b50-c801bf423487.png">
</p>

• Oahu is about 44 mi x 30 mi, I do not see any obvious trends
