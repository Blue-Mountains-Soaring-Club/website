---
title: "Weather"
date: 2022-08-17T06:46:14+10:00
draft: false
menu:
    main:
        identifier: weather
        name: Weather
        weight: 4
---

Current conditions and forecasts for Mount Blackheath

<div class="container">

<iframe id="mtblackheathwind" class="weatherItem" scrolling="no" src="https://mtblackheathwind.net" frameborder="0"></iframe>

<img class="weatherItem" src="https://weathercams.airservicesaustralia.com/wp-content/uploads/airports/063292/063292_225.jpg?v=1691899363">

<iframe class="weatherItem" height="700px" src="https://embed.windy.com/embed2.html?lat=-33.705&lon=150.250&detailLat=-33.654&detailLon=150.250&&width=1200&height=550&zoom=9&level=surface&overlay=wind&product=ecmwf&menu=&message=true&marker=&calendar=now&pressure=&type=map&location=coordinates&detail=true&metricWind=km%2Fh&metricTemp=%C2%B0C&radarRange=-1" frameborder="0"></iframe>

<img class="weatherItem raspItem" src="http://ausrasp.nfshost.com/NSWSOUTH/OUT+0/FCST/meteogram_Blackheath.png">
<img class="weatherItem raspItem" src="http://ausrasp.nfshost.com/NSWSOUTH/OUT+1/FCST/meteogram_Blackheath.png">
<img class="weatherItem raspItem" src="http://ausrasp.nfshost.com/NSWSOUTH/OUT+2/FCST/meteogram_Blackheath.png">

<iframe class="weatherItem" src="https://cdnres.willyweather.com.au/widget/loadView.html?id=72384" height="550px" frameborder="0"  scrolling="no"></iframe>

<img class="weatherItem" src="https://my.meteoblue.com/images/meteogram?temperature_units=C&windspeed_units=kmh&precipitation_units=mm&darkmode=false&iso2=au&lat=-33.6153&lon=150.267&asl=1093&tz=Australia%2FSydney&dpi=72&apikey=jhMJTOUVRNvs25m4&lang=en&location_name=Mount+Boyce&sig=d8431e283d55ee80885e75ab07dd1120">

<img class="weatherItem" src=https://borah.flymanilla.com/weather/synimage/synoptic.png>
<div>

<style>
    .container {
        text-align: center
    }
    .weatherItem {
        width: 100%;
        margin-bottom: 80px;
    }
    .raspItem {
        max-width: 700px;
    }

    @media (min-width: 571px) {
        #mtblackheathwind {
            height: 558px;
        }
    }
    @media (max-width: 570px) {
        #mtblackheathwind {
            height: 590px;
        }
    }
    @media (max-width: 375px) {
        #mtblackheathwind {
            height: 610px;
        }
    }
    @media (max-width: 350px) {
        #mtblackheathwind {
            height: 640px;
        }
    }@media (max-width: 300px) {
        #mtblackheathwind {
            height: 700px;
        }
    }
</style>
