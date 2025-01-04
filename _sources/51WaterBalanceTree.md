# 5.1 Water Balance of a Tree

We will revisit the water cycle and make connections between different parts of the water cycle within the CZ. We will rely on our understanding of the soil structure, vegetation physiology, and basic math skills needed to make calculations.

You will:
- You will integrate CZO data from multiple sensors to calculate a water balance centered on a tree. 
- You will apply concepts of fluxes and reservoirs to complete a mass balance equation on an annual time scale.



<div class="container">
<iframe src="https://www.youtube.com/embed/2oKYXKKf28g" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


## Hydrologic Cycle

 The hydrologic cycle (water cycle) is the movement of water on Earth from land to the oceans to the atmosphere and back to the land again. Water that is evaporated from oceans, lakes, and the land or transpired by plants becomes atmospheric moisture. Condensation in the atmosphere results in precipitation, in its many forms, back to the surface of the Earth. Some of the precipitation is intercepted by vegetation and other surfaces and evaporates back to the atmosphere before reaching the ground. Fallen precipitation that does reach the earth’s surface is partitioned into runoff or infiltrates into the ground. These waters contribute to soil and groundwater, which supply streams. Streams eventually flow into the oceans, completing the cycle.

```{figure} https://journals.ametsoc.org/view/journals/hydr/8/4/images/i1525-7541-8-4-758-f01.jpg
---
name: hydro-cycle
figclass: margin-caption
---
The hydrological cycle. Estimates of the main water reservoirs, given in plain font in $\pu{e3 km3}$, and the flow of moisture through the system, given in slant font ($\pu{e3 km3 yr−1}$), equivalent to Eg ($\pu{e18 g  yr−1}$).

Image source: [Estimates of the Global Water Budget and Its Annual Cycle Using Observational and Model Data in: Journal of Hydrometeorology Volume 8 Issue 4 (2007) (ametsoc.org)](https://journals.ametsoc.org/view/journals/hydr/8/4/jhm600_1.xml)
```

### Reservoirs

There have been many estimates of the amount of water stored in the various compartments on the earth and the major fluxes in the water budget. 

The oceans are, by far, the largest storehouse of water on Earth. Not only do the oceans provide evaporated water to the water cycle, they also allow water to move all around the globe as ocean currents.

```{figure} https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/styles/full_width/public/thumbnails/image/wss-where-is-earths-water-barchart.png?itok=C2EMUiCp
---
name: earth-water
figclass: margin-caption
---
Earth's water in different reservoirs or pools. Image source: [Oceans and Seas and the Water Cycle | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/oceans-and-seas-and-water-cycle)
```

It is estimated that of the  $\pu{3.32e8 mi3}$ ($\pu{1.386e9 km3}$) of the world's water supply, about  $\pu{3.21e8 mi3}$ ($\pu{1.338e9 km3}$) is stored in oceans. That is about $\pu{96.5 \%}$ percent of **[all Earth's water](https://www.usgs.gov/media/images/all-earths-water-a-single-sphere)**. It is also estimated that the oceans supply about $\pu{90 \%}$ of the evaporated water that goes into the water cycle.

The water cycle and the amount of water in the oceans is transient. Over the "short term" of hundreds of years, the oceans' volumes don't change much. But the amount of water in the oceans does change over the long term. During the last Ice Age, sea levels were lower. During colder climatic periods, more **[ice caps and glaciers](https://www.usgs.gov/special-topic/water-science-school/science/glaciers-and-icecaps)** form, and enough of the global water supply accumulates as ice which lessens the amount in other parts of the water cycle. The reverse is true during warm periods. During the last ice age **[glaciers](https://www.usgs.gov/special-topic/water-science-school/science/ice-snow-and-glaciers-and-water-cycle)** covered almost one-third of Earth's land mass, with the result being that the oceans were about $\pu{122 m}$ lower than today. During the last global "warm spell," about 125,000 years ago, the seas were about $\pu{5.5 m}$ higher than they are now. About three million years ago the oceans could have been up to $\pu{50 m}$ higher.

Even though the amount of water locked up in glaciers and ice caps is a small percentage of all water on (and in) the Earth, it represents a large percentage of the world's total freshwater. As these charts and the data table show, the amount of water locked up in ice and snow is only about $\pu{1.7 \%}$ of all water on Earth, but the majority of total freshwater on Earth, about $\pu{68.7 \%}$, is held in ice caps and glaciers.

Streams and lakes are the most visible part of the water cycle, but very little of Earth's water supply is stored as freshwater on the land surface. Freshwater represents only about $\pu{3 \%}$ of all water on Earth and freshwater lakes and swamps account for  $\pu{0.29 \%}$ of the Earth's freshwater. $\pu{20 \%}$ of all fresh surface water is in Lake Baikal in Asia and another $\pu{20 \%}$ (about $\pu{23,000 km3}$) is stored in the Great Lakes. Rivers hold only about $\pu{0.006 \%}$ of total freshwater reserves. 

Water locked up in groundwater is a small percentage of all of Earth's water, but it represents a large percentage of total freshwater on Earth. About $\pu{1.7 \%}$ of all of Earth's water is groundwater and about $\pu{30.1 \%}$ of **[freshwater](https://www.usgs.gov/special-topic/water-science-school/science/freshwater-lakes-and-rivers-and-water-cycle)** on Earth occurs as groundwater. Of this groundwater, about $\pu{54 \%}$ is saline, with the remaining $\pu{46 \%}$ is  freshwater.

Water in aquifers below the oceans is generally saline, while the water below the land surfaces (where freshwater, which fell as precipitation, infiltrates into the ground) is generally freshwater. There is a stable transition zone that separates saline water and freshwater below ground. It is fortunate for us that the relatively shallow aquifers that people tap with wells contain freshwater, since if we tried to irrigate crops with saline water, they would not grow well.

### Fluxes

Fluxes are the ways that water moves between pools, such as evaporation, precipitation, discharge, recharge, or human use. 

| Flux                                     | Flux rate estimate ($\pu{km3 yr-1}$)  | Range ($\pu{km3 yr-1}$)  |
|------------------------------------------|------------------------------------------------------------|-----------------------------------------------|
| Ocean circulation                        | 7,100,000                                                  | 6,100,000 - 9,100,000                         |
| Ocean evaporation                        | 420,500                                                    | 350,000 - 510,000                             |
| Precipitation over ocean                 | 380,500                                                    | 320,000 - 460,000                             |
| Precipitation over land                  | 110,600                                                    | 99,000 - 120,000                              |
| Evapotranspiration                       | 68,900                                                     | 62,000 - 75,000                               |
| Transport of moisture from ocean to land  | 46,000                                                     | 35,00 - 50,000                                |
| Streamflow to ocean                       | 46,000                                                     | 36,000 - 56,000                               |
| Groundwater recharge                     | 13,000                                                     | 12,000 - 25,000                               |
| Grazing water use                        | 10,000                                                     | 8,200 - 14,000                                |
| Agricultural water use                   | 10,840                                                     | 7,850 - 12,000                                |
| Groundwater discharge to ocean            | 4,500                                                      | 100 - 6,500                                   |
| Industrial water use                     | 1,130                                                      | 840 - 1,390                                   |
| Forestry water use                       | 960                                                        | 800 - 1,200                                   |
| Streamflow to closed basins               | 800                                                        | 600 - 1,100                                   |
| Municipal and domestic water use         | 590                                                        | 380 - 680                                     |


See [pools-and-fluxes (usgs.gov)](https://labs.waterdata.usgs.gov/visualizations/pools-and-fluxes/index.html#/) for an interactive version of the pools and fluxes of water on Earth. 

## Water Budget

Water budget provides a quantitative method for evaluating availability and sustainability of water supply. A water budget simply states that the rate of change in water stored in an area, such as a watershed, is balanced by the rate at which water flows into and out of the area. An understanding of water budget and the underlying hydrologic processes provides a foundation for effective water-resource and environmental planning and management. Observed changes in water budgets of an area over time can be used to assess the effects of climate variability and human activities on water resources. Comparison of water budgets from different areas allows the effects of factors such as geology, soils, vegetation, and land use on the hydrologic cycle to be quantified. Water budget also plays an important role in quantifying energy and mass transfer with the Earth's CZ.

```{figure} https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/water-budget-report-to-congress.png
---
name: water-budget
figclass: margin-caption
---
Components of a simple water budget for part of a watershed. Image source: [Water Budgets: Foundations for Effective Water-Resources and Environmental Management (usgs.gov)](https://pubs.er.usgs.gov/publication/cir1308)
```

The water balance equation in its most simple form is shown as:

$$
\Delta S = i - q
$$
In this equation, change in water storage ($\Delta S$) in a system and is equal to the difference in the inflow ($i$) and the outflow ($q$). This water balance equation can be expanded to be a little more informative as follows:

$$
P + Q_{In} = ET + Q_{Out} + \Delta S 
$$
where, $Q$ is water flow into ($Q_{In}$) or out ($Q_{Out}$) of a watershed (can be separated into groundwater and surface water components), $P$ is precipitation, $ET$ is evapotranspiration (sum of evaporation from soils, surface water bodies, and plants), and $\Delta S$ is change in water storage within the system.

To calculate an annual water budget for a specific location, meteorological and stream data will be required.


<div class="container">
<iframe src="https://www.youtube.com/embed/g_s_toqrYVM" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

<div class="container">
<iframe src="https://www.youtube.com/embed/Mytgsu96izQ" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


### Precipitation

Liquid precipitation is traditionally measured using various types of rain gages such as the non-recording cylindrical container type or the recording weighing type, float type and tipping-bucket type. All of the above gages measure precipitation at a point. Another method of measuring precipitation is through the use of radar. The actual measurement taken by the radar is of backscattered power of the echo returns.

A single point precipitation measurement is quite often not representative of the volume of precipitation falling over a given catchment area. A dense network of point measurements and/or radar estimates can provide a better representation of the true volume over a given area. A network of precipitation measurements can be converted to areal estimates using any of a number of techniques. See [Precipitation Measurements (weather.gov)](https://www.weather.gov/abrfc/map).

<div class="container">
<iframe src="https://www.youtube.com/embed/CisObgKNtYw" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

### Evapotranspiration

Evapotranspiration includes water evaporation into the atmosphere from the soil surface, evaporation from the capillary fringe of the groundwater table, and evaporation from water bodies on land. Evapotranspiration also includes transpiration, which is the water movement from the soil to the atmosphere via plants. Transpiration occurs when plants take up liquid water from the soil and release water vapor into the air from their leaves.

<div class="container">
<iframe src="https://www.youtube.com/embed/bXH1cFb0bbU" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Soil evaporation and plant transpiration  represent evaporative processes; the difference between the two rests in the path by which water moves from  the soil to the atmosphere. Water lost by transpiration must enter the plant via the roots, then pass to the  foliage where it is vaporized and lost to the atmosphere through tiny pores in the leaves known as stomata.  In contrast, water lost through soil evaporation passes directly from the soil to the atmosphere.  Evapotranspiration data are usually presented as a depth of water loss over a particular time period in a  manner similar to that of precipitation. Common units for ET are $\pu{in d−1}$ or $\pu{mm d−1}$.

The rate of ET for a given environment (vegetation) is a function of four critical factors. The first and most  critical factor is soil moisture. Evaporation (ET) simply can not take place if there is no water in the soil.  However, if adequate soil moisture is available, three additional factors -- plant type, stage of plant  development and weather -- affect ET rate.

Plant type refers to the species or variety of plant being grown and can greatly influence the rate of ET.  Grass and many non-native plants require considerable water when grown in the desert. In contrast, many  native plants are adapted to the desert and require much less water.  

Stage of plant development also plays a critical role in determining ET. Plant development encompasses  both the relative activity of the plant (e.g. dormant vs. actively growing) and plant size. For example,  dormant plants use and therefore need very little water, while lush, actively growing plants (under similar  conditions) will require considerably more water. Plant size and density also impact ET. Small plants and  areas with sparse plant canopies use far less water than large plants and areas with dense plant canopies.  

Weather is the fourth and last of the critical factors affecting ET. Weather conditions dictate the amount of  energy available for evaporation and therefore play a crucial role in determining ET rate. Four weather  parameters - solar radiation (amount of sunshine), wind speed, humidity and temperature - impact the rate  of ET. Solar radiation contributes huge amounts of energy to vegetation in the desert and thus is the  meteorological parameter with the greatest impact on ET on most days. In actuality, solar radiation is one  component of the total radiant energy balance of vegetation referred to as net radiation. Invisible, infrared  radiation represents the other component of net radiation. On most days, however, solar radiation is the  dominant component of net radiation because the infrared balance is negative and often small.  

Wind is the second most important factor in determining ET rate. The wind has two major roles; first, it  transports heat that builds up on adjacent surfaces such as dry desert or asphalt to vegetation which  accelerates evaporation (a process referred to as advection). Wind also serves to accelerate evaporation by  enhancing turbulent transfer of water vapor from moist vegetation to the dry atmosphere. In this case, the 
wind is constantly replacing the moist air located within and just above the plant canopy with dry air from  above.  

Humidity and temperature work in concert with each other to determine the dryness or drying power of the  atmosphere. The vapor pressure deficit (VPD) is the meteorological variable used to quantify the drying  power of the atmosphere. The VPD estimates the difference (or gradient) in vapor pressure (concentration  of water vapor) between the moist vegetation and the drier atmosphere above. Relative humidity, the  humidity variable most commonly reported in weather forecasts, is a poor indicator atmospheric dryness.  For example, the drying power (VPD) of an atmosphere with a $\pu{30\%}$ relative humidity and a $\pu{86 ^\circ F}$ temperature  is 2 times that of an atmosphere with the same $\pu{30\%}$ relative humidity and a $\pu{68 ^\circ F}$ temperature.

The final parameter affecting ET rate is temperature. We have already indicated that temperature impacts  ET through its impact on VPD and advection. In addition to these factors temperature impacts ET is some more subtle ways. When all other factors are equal, ET will be higher for warm as compared to cool  vegetation because less energy is required to evaporate water from the warm vegetation. Temperature also  impacts the relative effectiveness of the radiant energy and wind in evaporating water. Radiant energy is  more effectively utilized for ET when temperatures are high. In contrast, wind has more impact on ET when  temperatures are low.

Evapotranspiration is measured using an eddy covariance flux tower.  The basic approach assumes that within the boundary layer close to the earth’s surfaces ($\pu{50 – 100 m}$), the transport of moisture is governed by eddies that move air of higher moisture content upward and air of lower moisture content downward, resulting in the mass transfer of moisture. These movements are called fluxes, which are the rate of transfer of quantities of wind and moisture across a unit area.

See [Evapotranspiration and the Water Cycle | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/evapotranspiration-and-water-cycle)


### Infiltration and Soil Water

Infiltration ($f$) is the process of water entering the surface of the soil. Infiltration provides water for plant transpiration and ground water recharge. Soil water is the amount of water contained within the soil as well as how tightly it is held in the soil matrix. Infiltration rates can easily be affected by land management practices. There are two forces involved in infiltration: gravity and capillary forces. 

The infiltration rate is influenced by several factors, including soil texture, land management, soil moisture, salinity, temperature, and frozen soil. 
1. Soil Texture: Coarse-textured soils that have large pores, such as sandy loam or gravel, have higher infiltration rates than fine-textured soils composed of clay or silt loam that have a larger number but smaller size of pores. Also, clay pans or compacted layers in the soil act to reduce infiltration. We can use hydraulic conductivity as an expression of these different textures.
2. Soil Structure: Macropores, shrink/swell potential, and a restricting layer can all influence infiltration. Surface sealing can reduce infiltration rates during rainfall. Sealing can be caused by rainfall impact and colloidal swelling. Therefore, the surface cover of a soil can be important for infiltration.
3. Land Management: Forest cover typically has greater infiltration rates than grasslands because forests have more organic matter that causes soil aggregates to form. Burning an area would reduce infiltration rates because it would remove soil organic matter and reduce aggregation of soil particles. In some cases burning results in clogged soil pores, and burned surfaces can be hydrophobic. Soil compaction in urban areas is another example of the effect of land management on infiltration. However, mulching the surface can increase infiltration. Agricultural cropping is also known to reduce infiltration because the soil is less protected from rainfall impact.
4. Soil Moisture: The initial water content of the soil influences initial infiltration. As the moisture content increases in the soil, the infiltration rate decreases because the pores fill up. In very dry, sandy soils, the infiltration rate can actually increase over time with the release of trapped air, which initially impedes water infiltration.
5. Water Quality: Some of the chemical constituents in water can influence infiltration rates. For example, increased salinity of the water lowers the infiltration rate. Sodium in water breaks down aggregates and disperses the particles, resulting in clogged pores. Salt can be added to soil to lower the infiltration rate if desired, and road salt has this effect. Highly turbid surface water also reduces infiltration by clogging pores with sediment.
6. Temperature: The temperature of water influences the viscosity of water and therefore the infiltration rate. The infiltration rate would increase with temperature and decrease with increasing viscosity. A temperature increase from 40°F to 100°F could result in an increase in the infiltration rate by a factor of two.
7. Soil Freezing: Soil frost can affect infiltration rates, the effect depending on the type of frost present in the soil. The frozen structure of soil is impervious to air and water. Certain types of land management activities can influence the type of frost that forms. For example, clear-cutting favors concrete frost because less evapotranspiration may result in wetter soils in certain situations
8. Measuring Infiltration

Water infiltration into soil is typically measured using different types of infiltrometers.

[Double-ring infiltrometer](https://en.wikipedia.org/wiki/Infiltrometer) consists of two concentric metal or plastic rings that are driven into the soil. Water is poured into the inner ring, and the outer ring helps to minimize the lateral movement of water away from the inner ring. The rate at which water enters the soil in the inner ring is measured over time.

<div class="container">
<iframe src="https://www.youtube.com/embed/iwMgi0gDytI" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Disc infiltrometer is a portable device with a disc-shaped base that is placed on the soil surface. Water is supplied to the disc at a known rate, and the steady-state infiltration rate is calculated based on the water intake needed to maintain a constant level of water on the disc.

<div class="container">
<iframe src="https://www.youtube.com/embed/CnkwoGzWDDI" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

In all cases, the measurements are taken over time, and the infiltration rate is typically expressed in units of length per unit time (e.g., $\pu{cm hr-1}$ or $\pu{mm hr-1}$). The data can be used to characterize the soil's hydraulic properties and inform irrigation scheduling, drainage design, and hydrological modeling.

```{figure} https://edaphic.com.au/wp-content/uploads/2018/02/Decagon-Mini-Disk-Infiltrometer-in-Field-Web.jpg
---
name: mini-disc-infiltromter
figclass: margin-caption
---
A mini disc infiltrometer is used to measure rate of water infiltration and unsaturated hydraulic conductivity. Image source: [Edaphic Scientific](https://edaphic.com.au/products/soils/infiltrometer-mini-disk/)
```


There are two fundamental ways to characterize soil moisture. The first aspect is the amount of water or water content in the soil. The amount of water is important for soil recharge and overland flow. The second aspect is the energy status of soil moisture, which is important for evapotranspiration, tree growth, and water movement in the soil.

Both direct and indirect methods are used to determine soil water content. A soil moisture measurement can be obtained directly by gravimetric (weighing) methods.  Time domain reflectometry (TDR) is based on the dialectric constants for water and soil, the latter of which is a function of the soil water content.  A microwave pulse is sent through a steel rod, producing a waveform on an oscilloscope, which also measures the transit time of the pulse.

<div class="container">
<iframe src="https://www.youtube.com/embed/LNBN65P9UPY" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


## Water Budget of a Tree

<div class="container">
<iframe src="https://www.youtube.com/embed/aPQzLc8f0xE" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

<div class="container">
<iframe src="https://www.youtube.com/embed/9-dicqNoODg" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Plants are phenomenal hydraulic engineers. Using only the basic laws of physics and the simple manipulation of potential energy, plants can move water to the top of a tree. Plants can also use hydraulics to generate enough force to split rocks and buckle sidewalks. 

Trees transport water from their roots to leaves through a specialized vascular tissue called *xylem*. The xylem forms a continuous system of interconnected conduits that extends from the roots, through the trunk and branches, and into the leaves. This transport process proceeds as follows:
1. Root uptake: The root hairs and fine roots absorb water from the soil through osmosis. The water enters the xylem vessels of the roots.
2. Transpirational pull: As water evaporates from the leaf surfaces (transpiration), it creates a negative pressure or tension within the xylem vessels of the leaves. This tension is transmitted down through the interconnected xylem conduits.
3. Capillary action: The cohesive forces between water molecules and the adhesive forces between water and the xylem vessel walls create a continuous column of water within the xylem. This allows the transpirational pull to be transmitted all the way down to the roots.
4. Root pressure: In some cases, especially during the spring, the roots can also contribute a positive pressure called root pressure, which helps push water up the xylem.
5. Xylem transport: The transpirational pull and root pressure, combined with the cohesion and adhesion properties of water, cause the water to move upwards through the xylem vessels from the roots to the leaves.

The xylem vessels are reinforced with lignin, which provides structural support and prevents the vessels from collapsing under the negative pressure generated during transpiration. This efficient water transport system allows trees to move large volumes of water, even to great heights, to meet the transpirational demands of the leaves.



<div class="container">
<iframe src="https://www.youtube.com/embed/BickMFHAZR0" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Water potential plays a crucial role in the transport of water from roots to leaves in trees. Water potential is a measure of the potential energy of water, and it determines the direction and rate of water movement within the plant's vascular system. Here's how water potential influences water transport in trees:

1. Soil water potential: Water moves from regions of higher water potential to regions of lower water potential. The soil water potential is typically higher than the water potential inside the plant's roots, which drives the initial uptake of water from the soil into the root xylem.
2. Root water potential: As water enters the root xylem, it lowers the water potential in the roots compared to the surrounding soil, maintaining the driving force for water uptake.
3. Transpirational pull: Transpiration from the leaves creates a low water potential in the leaf cells, which is transmitted through the continuous xylem conduits as a tension or negative pressure. This transpirational pull establishes a water potential gradient from the roots to the leaves, facilitating the upward movement of water.
4. Cohesion-tension theory: The cohesive forces between water molecules ($\ce{H2O}$ are attracted to each other by $\ce{H}$-bonds) and the adhesive forces between water and the hydrophilic xylem vessel walls allow the transpirational pull to be effectively transmitted through the xylem, even over long distances, without breaking the continuous water column.
5. Root pressure: In some cases, the roots can generate positive root pressure, which increases the water potential in the root xylem and contributes to the overall driving force for water transport.

The water potential gradient established by transpiration, coupled with the cohesive and adhesive properties of water, ensures that water moves from the soil (higher water potential) into the roots, up through the xylem, and ultimately to the leaves (lower water potential) to replace the water lost through transpiration. This continuous process, driven by water potential differences, is essential for maintaining the water balance and supporting the physiological processes in trees.

The water potential in plant solutions is influenced by solute concentration, pressure, gravity, and factors called matrix effects. Water potential can be broken down into its individual components using the following equation:

$$
Ψ_{system}=Ψ_{total}=Ψ_s+Ψ_p+Ψ_g+Ψ_m
$$
where $Ψs$, $Ψp$, $Ψg$, and $Ψm$ refer to the solute, pressure, gravity, and matric potentials, respectively. *System* can refer to the water potential of the soil water ($Ψ_{soil}$), root water ($Ψ_{root}$), stem water ($Ψ_{stem}$), leaf water ($Ψ_{leaf}$) or the water in the atmosphere ($Ψ_{atmosphere}$). As the individual components change, they raise or lower the total water potential of a system. When this happens, water moves to equilibrate, moving from the system or compartment with a higher water potential to the system or compartment with a lower water potential. This brings the difference in water potential between the two systems ($\Delta Ψ$) back to zero ($\Delta Ψ = 0$). Therefore, for water to move through the plant from the soil to the air (a process called transpiration), the following relationship must hold: $Ψ_{soil} > Ψ_{root} > Ψ_{stem} > Ψ_{leaf} > Ψ_{atmosphere}$.  

Water only moves in response to $\Delta Ψ$, not in response to the individual components. However, because the individual components influence the total $Ψ_{system}$, by manipulating the individual components (especially $Ψ_s$), a plant can control water movement.

See [Transport of Water and Solutes in Plants - Biology 2e | OpenStax](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants) for information about how water flows through a plant system.


```{figure} https://openstax.org/apps/archive/20230220.155442/resources/bc6e2dbc1c7559822f42a0e88cb260bceb185c3c
---
name: sap-ascent-tree
figclass: margin-caption
---
The cohesion–tension theory of sap ascent is shown. Evaporation from the mesophyll cells produces a negative water potential gradient that causes water to move upwards from the roots through the xylem. Image source: [Transport of Water and Solutes in Plants](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants)
```

Plant transpiration is pretty much an invisible process. The water is evaporating from the leaf surfaces, but we cannot see the leaves "*breathing*".  One way to visualize transpiration is to put a plastic bag around some plant leaves. During a growing season, a single corn plant can transpire around $\pu{4 L d-1}$, a mature oak tree can transpire up to $\pu{400 L d-1}$, and a hectare of actively growing forest can transpire over $\pu{50,000 L d-1}$. At the ecosystem level, transpiration rates can range from less than $\pu{1 mm d-1}$ in arid regions to over $\pu{5 mm d-1}$ in tropical forests (note that the units are similar to precipitation units).

Since water vapor also evaporates from the soil, we would have seen even more water vapor captured if we had wrapped the plastic bag around the soil as well.

Evapotranspiration in a CZ (or an ecosystem) is a function of the following factors:
- Temperature: Higher temperatures generally increase transpiration rates due to increased evaporative demand.
- Humidity: Lower humidity leads to higher transpiration rates as the air can hold more water vapor.
- Wind: Increased wind speed can enhance transpiration by removing the saturated air around the leaves.
- Light: Higher light levels (e.g., full sun) typically increase transpiration as stomata open wider.
- Water availability: Transpiration rates decrease when soil water is limited to prevent excessive water loss.

```{admonition} Water Balance of a Tree

1. Consider the water balance at the scale of a single tree. What pools (reservoirs) are present? What processes change fluxes into and out of the reservoirs?
2. Label the water cycle around that tree including reservoirs and fluxes.
3. How would dominant components of the water cycle differ between different climates.
4. If you are designing a study to estimate water yield at a given climate ([Köppen climate classification - Wikipedia](https://en.wikipedia.org/wiki/K%C3%B6ppen_climate_classification)), what data do you need to collect in order to create a water balance for a tree here?
5. Write a general equation to calculate water yield or discharge from this system.
```


## Readings and resources for this section

1. [Surface Water Information by Topic | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/surface-water-information-topic)
2. [30.5 Transport of Water and Solutes in Plants - Biology 2e | OpenStax](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants)
3. [Estimates of the Global Water Budget and Its Annual Cycle Using Observational and Model Data in: Journal of Hydrometeorology Volume 8 Issue 4 (2007) (ametsoc.org)](https://journals.ametsoc.org/view/journals/hydr/8/4/jhm600_1.xml)
4. [Soil Moisture Response to Snowmelt and Rainfall in a Sierra Nevada Mixed‐Conifer Forest - Bales - 2011 - Vadose Zone Journal - Wiley Online Library](https://acsess.onlinelibrary.wiley.com/doi/abs/10.2136/vzj2011.0001)
5. [Physical Hydrology, Third Edition, by S. Lawrence Dingman](https://www.waveland.com/browse.php?t=382) - See OAKS for Chapters 1 and 2.