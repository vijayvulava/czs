# 5.1 Water Balance of a Tree

We will review the water cycle and explore the connections between its components in the Critical Zone (CZ). Understanding soil structure, plant physiology, and basic math skills will be essential for our calculations.

In this activity, you will:
- Integrate data from multiple sensors within the Critical Zone to calculate a water balance focused on a tree. 
- Apply the concepts of fluxes and reservoirs to complete a mass balance equation on an annual time scale.


<div class="container">
<iframe src="https://www.youtube.com/embed/2oKYXKKf28g" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


## Hydrologic Cycle

The hydrologic cycle, also known as the water cycle, is the continuous movement of water on Earth. This cycle involves water transitioning from land to the oceans, into the atmosphere, and back to the land. Water evaporates from oceans, lakes, and land, as well as being transpired by plants, which adds moisture to the atmosphere. When this moisture condenses, it results in precipitation, which can take various forms and fall back to the Earth's surface.

Some precipitation is intercepted by vegetation and other surfaces, where it may evaporate into the atmosphere before reaching the ground. The precipitation reaching the Earth's surface is then divided into runoff, which flows over the land or infiltrates the ground. This water contributes to soil moisture and groundwater, eventually feeding into streams. Over time, these streams flow back into the oceans, completing the cycle.

```{figure} https://journals.ametsoc.org/view/journals/hydr/8/4/images/i1525-7541-8-4-758-f01.jpg
---
name: hydro-cycle
figclass: margin-caption
---
The hydrological cycle. Estimates of the main water reservoirs, given in plain font in $\pu{e3 km3}$, and the flow of moisture through the system, given in slant font ($\pu{e3 km3 yr−1}$), equivalent to Eg ($\pu{e18 g  yr−1}$).

Image source: [Estimates of the Global Water Budget and Its Annual Cycle Using Observational and Model Data in: Journal of Hydrometeorology Volume 8 Issue 4 (2007) (ametsoc.org)](https://journals.ametsoc.org/view/journals/hydr/8/4/jhm600_1.xml)
```

### Reservoirs

There have been many estimates of the amount of water stored in the various compartments on the earth and the significant fluxes in the water budget. 

The oceans are, by far, the largest storehouse of water on Earth. Not only do the oceans provide evaporated water to the water cycle, but they also allow water to move all around the globe as ocean currents.

```{figure} https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/styles/full_width/public/thumbnails/image/wss-where-is-earths-water-barchart.png?itok=C2EMUiCp
---
name: earth-water
figclass: margin-caption
---
Earth's water is in different reservoirs or pools. Image source: [Oceans and Seas and the Water Cycle | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/oceans-and-seas-and-water-cycle)
```

It is estimated that of the $\pu{3.32e8 mi3}$ ($\pu{1.386e9 km3}$) of the world's water supply, about $\pu{3.21e8 mi3}$ ($\pu{1.338e9 km3}$) is stored in oceans. This accounts for approximately $\pu{96.5 \%}$ of all of Earth's water. The oceans are also estimated to supply about $\pu{90 \%}$ of the water that evaporates into the water cycle.

The water cycle and the volume of water in the oceans are dynamic. Over the "short term" of hundreds of years, the volume of the oceans does not change significantly. However, the amount of water in the oceans can vary over the long term. During the last Ice Age, sea levels were lower, and during colder climatic periods, more ice caps and glaciers formed, sequestering a portion of the global water supply as ice. This accumulation reduces the water available in other parts of the water cycle. Conversely, during warmer periods, such as the last global warming phase approximately 125,000 years ago, sea levels were about $\pu{5.5 m}$ higher than today. Three million years ago, sea levels could have been up to $\pu{50 m}$ higher.

While the amount of water trapped in glaciers and ice caps is a small percentage of all water on Earth, it represents a substantial portion of the world’s total freshwater. Charts and data indicate that only about $\pu{1.7 \%}$ of all water on Earth is contained in ice and snow, but approximately $\pu{68.7 \%}$ of Earth's total freshwater is stored in ice caps and glaciers.

Streams and lakes are the most visible components of the water cycle, yet very little of the Earth's water supply exists as freshwater on the land surface. Freshwater makes up only about $\pu{3 \%}$ of all water on Earth, with freshwater lakes and swamps accounting for just $\pu{0.29 \%}$ of this freshwater. Notably, $\pu{20 \%}$ of all fresh surface water can be found in Lake Baikal in Asia, while another $\pu{20 \%}$ (approximately $\pu{23,000 km3}$) is stored in the Great Lakes. Rivers hold only about $\pu{0.006 \%}$ of total freshwater reserves.

Water stored in groundwater constitutes a small percentage of all of Earth's water but represents a large proportion of total freshwater on the planet. Approximately $\pu{1.7 \%}$ of Earth's water is groundwater, and around $\pu{30.1 \%}$ of freshwater on Earth exists as groundwater. Out of this groundwater, about $\pu{54 \%}$ is saline, while the remaining $\pu{46 \%}$ is freshwater.

Water found in aquifers beneath the oceans is generally saline, whereas water below land surfaces (where precipitation infiltrates the ground) is mostly freshwater. A stable transition zone separates saline water from freshwater underground. Fortunately, the shallow aquifers tapped by wells contain freshwater, as attempting to irrigate crops with saline water would not support their growth.
### Fluxes

Fluxes are water moving between pools, such as evaporation, precipitation, discharge, recharge, or human use. 

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

A water budget is a quantitative method used to evaluate the availability and sustainability of water supply. It states that the change in water stored in a specific area, such as a watershed, is balanced by the rate at which water enters and exits that area. Understanding the water budget and the hydrologic processes provides a foundation for effective water resource management and environmental planning.

Changes in the water budgets of an area over time can help assess the impacts of climate variability and human activities on water resources. We can quantify how geology, soil types, vegetation, and land use influence the hydrologic cycle by comparing water budgets from different areas. The water budget is also crucial for quantifying energy and mass transfer within the Earth's critical zone (CZ).

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
In this equation, the change in water storage ($\Delta S$) in a system is equal to the difference in the inflow ($i$) and the outflow ($q$). This water balance equation can be expanded to be a little more informative as follows:

$$
P + Q_{In} = ET + Q_{Out} + \Delta S 
$$
where $Q$ is water flow into ($Q_{In}$) or out ($Q_{Out}$) of a watershed (can be separated into groundwater and surface water components), $P$ is precipitation, $ET$ is evapotranspiration (sum of evaporation from soils, surface water bodies, and plants), and $\Delta S$ is change in water storage within the system.

Meteorological and stream data will be required to calculate an annual water budget for a specific location.


<div class="container">
<iframe src="https://www.youtube.com/embed/g_s_toqrYVM" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

<div class="container">
<iframe src="https://www.youtube.com/embed/Mytgsu96izQ" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


### Precipitation

Liquid precipitation is typically measured using various rain gauges, including non-recording cylindrical containers, weighing gauges, float gauges, and tipping-bucket gauges. Each of these gauges measures precipitation at a specific point. Another method for measuring precipitation involves using radar, which measures the backscattered power of echo returns.

However, a single-point precipitation measurement often does not accurately represent the total volume of precipitation falling over a larger catchment area. A dense network of point measurements and/or radar estimates can be utilized to better represent the precipitation volume. This network can be converted into areal estimates using various techniques. For more information, see [Precipitation Measurements (weather.gov)](https://www.weather.gov/abrfc/map).

<div class="container">
<iframe src="https://www.youtube.com/embed/CisObgKNtYw" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

### Evapotranspiration

Evapotranspiration refers to water evaporating into the atmosphere from various sources. This includes evaporation from the soil surface, the capillary fringe of the groundwater table, and bodies of water on land. Additionally, evapotranspiration encompasses transpiration and water movement from the soil to the atmosphere through plants. During transpiration, plants absorb liquid water from the soil and release water vapor into the air through their leaves.

<div class="container">
<iframe src="https://www.youtube.com/embed/bXH1cFb0bbU" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Soil evaporation and plant transpiration are both processes through which water is lost to the atmosphere, but they differ in how water moves from the soil to the air. In transpiration, water is absorbed by the plant's roots, travels through the plant, and is vaporized in the leaves before escaping into the atmosphere through tiny openings called stomata. In contrast, soil evaporation occurs when water moves directly from the soil surface to the atmosphere. Evapotranspiration (ET) data are typically expressed as a depth of water loss over a specific time, similar to precipitation measurements, with standard units being inches per day (in d⁻¹) or millimeters per day (mm d⁻¹). 

Four key factors influence the rate of ET in a given environment. The most critical factor is soil moisture; without sufficient water in the soil, evaporation and transpiration cannot occur. However, when there is adequate soil moisture, three additional factors come into play: plant type, stage of plant development, and weather conditions.

Plant type refers to the species or variety of cultivated plants and can significantly impact ET rates. For example, grasses and many non-native plants require substantial water in desert environments.  In contrast, many native plants have adapted to arid conditions and require much less water.

The stage of plant development also plays an essential role in determining ET. This stage encompasses the plant's activity level (e.g., dormant vs. actively growing) and the size of the plant. Dormant plants use very little water, whereas lush, actively growing plants need considerably more. Additionally, the size and density of the plants affect ET; smaller plants and areas with sparse canopies use significantly less water than larger plants and areas with dense canopies. 

Together, these factors dictate the overall evapotranspiration rate in any given environment.


Weather is the fourth and final critical factor affecting evapotranspiration (ET). Weather conditions determine the energy available for evaporation, which is crucial in determining the ET rate. Four weather parameters—solar radiation (the amount of sunshine), wind speed, humidity, and temperature—impact the rate of ET. 

Solar radiation contributes significant energy to vegetation, especially in desert environments. It is often the meteorological parameter with the most significant impact on ET on most days. Solar radiation is one component of vegetation's total radiant energy balance, known as net radiation. The other component is invisible infrared radiation. However, on most days, solar radiation is the dominant component of net radiation because the infrared balance is usually negative and relatively small.

Wind is the second most important factor influencing the ET rate. Wind serves two significant roles: first, it transports heat from adjacent surfaces (such as desert soils or asphalt) to vegetation, accelerating evaporation—a process known as advection. Additionally, wind enhances evaporation by improving the turbulent transfer of water vapor from moist vegetation to the drier atmosphere. This process involves the wind continually replacing the moist air within and just above the plant canopy with drier air from above.

Humidity and temperature work together to determine the drying power of the atmosphere. The vapor pressure deficit (VPD) is the key meteorological variable to quantify this drying power. The VPD estimates the difference (or gradient) in vapor pressure (water vapor concentration) between moist vegetation and the drier atmosphere above. Relative humidity, the most commonly reported humidity variable in weather forecasts, is not a reliable indicator of atmospheric dryness. For example, the drying power (VPD) of an atmosphere with 30% relative humidity at 86°F is twice that of an atmosphere with the same 30% relative humidity at 68°F.

The final parameter affecting the ET rate is temperature. We have noted that temperature influences ET through its effects on VPD and advection. Moreover, there are more subtle ways in which temperature affects ET. When all other factors are equal, ET will be higher for warm vegetation than cool vegetation because less energy is needed to evaporate water from warm surfaces. Additionally, temperature affects the effectiveness of radiant energy and wind in promoting evaporation. Radiant energy is utilized more effectively for ET when temperatures are high, while wind significantly impacts ET when temperatures are low.

Evapotranspiration is measured using an eddy covariance flux tower. This approach assumes that, within the boundary layer close to the Earth's surface (50–100 meters), moisture transport is governed by eddies that move air with higher moisture content upward and air with lower moisture content downward. This process results in the mass transfer of moisture, referred to as fluxes, which represent the rate of transfer of wind and moisture across a unit area.

See [Evapotranspiration and the Water Cycle | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/evapotranspiration-and-water-cycle)


### Infiltration and Soil Water

**Infiltration** ($f$) is the process by which water enters the soil surface. This process is essential as it provides water for plant transpiration and contributes to groundwater recharge. Soil water refers to the amount of water contained within the soil and how tightly it is held within the soil matrix. Infiltration rates can be significantly affected by land management practices. The two primary forces involved in infiltration are gravity and capillary forces.

Several factors influence the infiltration rate, including soil texture, land management practices, soil moisture, salinity, temperature, and frozen soil.

1. **Soil Texture:** Coarse-textured soils, such as sandy loam or gravel, have larger pores and, therefore, exhibit higher infiltration rates compared to fine-textured soils like clay or silt loam, which have a more significant number of smaller pores. Additionally, clay pans or compacted layers within the soil can reduce infiltration. Hydraulic conductivity can express the differences in infiltration across various soil textures.

2. **Soil Structure:** Features such as macropores, shrink/swell potential, and restricting layers can all influence infiltration. Surface sealing can decrease infiltration rates during rainfall, which is caused by the impact of rain and colloidal swelling. Thus, the surface cover of the soil is vital for optimizing infiltration.

3. **Land Management:** Forest cover generally leads to greater infiltration rates than grasslands because the organic matter in forests promotes the formation of soil aggregates. Conversely, burning vegetation can reduce infiltration rates by removing soil organic matter and causing soil particles to lose aggregation. Burning can sometimes result in clogged soil pores, and burnt surfaces can become hydrophobic. Additionally, urban soil compaction can negatively impact infiltration. However, mulching can improve infiltration rates. Agricultural cropping often reduces infiltration since it exposes the soil to rainfall impact.

4. **Soil Moisture:** The initial water content of the soil affects the infiltration rate. The infiltration rate decreases as the moisture content increases because the pores become filled with water. In arid, sandy soils, the infiltration rate can increase over time as trapped air is released, which initially impedes water infiltration.

5. **Water Quality:** Certain chemical constituents in water can influence infiltration rates. For example, increased salinity lowers the infiltration rate. Sodium in water can break down aggregates and disperse soil particles, leading to clogged pores. Adding salt to soil can intentionally reduce infiltration rates; road salt has a similar effect. Highly turbid surface water can also decrease infiltration by clogging pores with sediment.

6. **Temperature:** Water temperature affects its viscosity, influencing the infiltration rate. Higher temperatures generally increase infiltration rates, while increased viscosity decreases them. For instance, a temperature increase from 40°F to 100°F could double the infiltration rate.

7. **Soil Freezing:** Soil frost can impact infiltration rates, with the effect varying depending on the type of frost present. Frozen soil is typically impervious to air and water. Specific land management practices can influence the type of frost that forms; for example, clear-cutting can lead to concrete frost formation due to reduced evapotranspiration, which may result in wetter soils in specific scenarios.

8. **Measuring Infiltration:** 

This section will address methods to measure infiltration rates effectively and quantitatively. 

Overall, understanding these factors is crucial for managing soil water resources effectively.
Water infiltration into soil is typically measured using different types of infiltrometers.

[Double-ring infiltrometer](https://en.wikipedia.org/wiki/Infiltrometer) consists of two concentric metal or plastic rings driven into the soil. Water is poured into the inner ring, and the outer ring helps to minimize the lateral movement of water away from the inner ring. The rate at which water enters the soil in the inner ring is measured over time.

<div class="container">
<iframe src="https://www.youtube.com/embed/iwMgi0gDytI" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

A disc infiltrometer is a portable device with a disc-shaped base placed on the soil surface. Water is supplied to the disc at a known rate, and the steady-state infiltration rate is calculated based on the water intake needed to maintain a constant level of water on the disc.

<div class="container">
<iframe src="https://www.youtube.com/embed/CnkwoGzWDDI" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

In all cases, the measurements are taken over time, and the infiltration rate is typically expressed in units of length per unit of time (e.g., $\pu{cm hr-1}$ or $\pu{mm hr-1}$). The data can characterize the soil's hydraulic properties and inform irrigation scheduling, drainage design, and hydrological modeling.

```{figure} https://edaphic.com.au/wp-content/uploads/2018/02/Decagon-Mini-Disk-Infiltrometer-in-Field-Web.jpg
---
name: mini-disc-infiltromter
figclass: margin-caption
---
A mini disc infiltrometer measures the water infiltration rate and unsaturated hydraulic conductivity. Image source: [Edaphic Scientific](https://edaphic.com.au/products/soils/infiltrometer-mini-disk/)
```


There are two fundamental ways to characterize soil moisture. The first aspect is the soil's water or water content. The amount of water is essential for soil recharge and overland flow. The second aspect is the energy status of soil moisture, which is important for evapotranspiration, tree growth, and water movement in the soil.

Both direct and indirect methods are used to determine soil water content. A soil moisture measurement can be obtained directly by gravimetric (weighing) methods.  Time domain reflectometry (TDR) is based on the dielectric constants for water and soil, the latter of which is a function of the soil water content.  A microwave pulse is sent through a steel rod, producing a waveform on an oscilloscope, which also measures the transit time of the pulse.

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

Plants are remarkable hydraulic engineers. They can move water to the tops of trees using only the fundamental laws of physics and the simple manipulation of potential energy. Additionally, plants can generate enough hydraulic force to split rocks and buckle sidewalks.

Trees transport water from their roots to their leaves through a specialized vascular tissue called xylem. The xylem forms a continuous system of interconnected conduits that extend from the roots, through the trunk and branches, and into the leaves. This process occurs in several steps:

1. **Root Uptake:** The root hairs and fine roots absorb water from the soil through osmosis. The water then enters the xylem vessels in the roots.

2. **Transpirational Pull:** As water evaporates from the leaf surfaces—a process known as transpiration—it creates a negative pressure or tension within the xylem vessels of the leaves. This tension is transmitted down through the interconnected xylem conduits.

3. **Capillary Action:** The cohesive forces between water molecules and the adhesive forces between water and the xylem vessel walls create a continuous water column within the xylem. This mechanism allows the transpirational pull to be transmitted down to the roots.

4. **Root Pressure:** In some cases, particularly during the spring, the roots can generate a positive pressure known as root pressure, which helps push water up through the xylem.

5. **Xylem Transport:** The combination of transpirational pull and root pressure, along with water's cohesion and adhesion properties, causes the water to move upward through the xylem vessels from the roots to the leaves.

The xylem vessels are reinforced with lignin, which provides structural support and prevents the vessels from collapsing under the negative pressure created during transpiration. This efficient water transport system enables trees to move large volumes of water, even to great heights, to meet the demands of leaf transpiration.


<div class="container">
<iframe src="https://www.youtube.com/embed/BickMFHAZR0" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


Water potential is crucial in water transport from the roots to tree leaves. It measures the potential energy of water, determining the direction and rate of water movement within the plant's vascular system. Here’s how water potential influences this process:

1. **Soil Water Potential**: Water moves from higher water potential to areas of lower water potential. The water potential in the soil is typically higher than that in the plant's roots, driving the initial uptake of water from the soil into the root xylem.

2. **Root Water Potential**: Water entering the root xylem lowers the water potential in the roots compared to the surrounding soil, thereby maintaining the driving force for further water uptake.

3. **Transpirational Pull**: Transpiration from the leaves creates a low water potential in the leaf cells. This change is transmitted through the continuous xylem conduits as tension or negative pressure. The transpirational pull establishes a water potential gradient from the roots to the leaves, facilitating the upward movement of water.

4. **Cohesion-Tension Theory**: The cohesive forces between water molecules (due to hydrogen bonding) and the adhesive forces between water and the hydrophilic xylem vessel walls allow the transpirational pull to be effectively transmitted through the xylem. This occurs even over long distances without breaking the continuous water column.

5. **Root Pressure**: In some cases, roots can generate positive pressure, which increases the water potential in the root xylem, contributing to the overall driving force for water transport.

The water potential gradient created by transpiration, combined with the cohesive and adhesive properties of water, ensures that water moves from the soil (higher water potential) into the roots, through the xylem, and ultimately to the leaves (lower water potential) to replenish the water lost through transpiration. This continuous process, driven by differences in water potential, is essential for maintaining water balance and supporting tree physiological processes.

The water potential in plant solutions is influenced by solute concentration, pressure, gravity, and factors called matrix effects. Water potential can be broken down into its components using the following equation:

$$
Ψ_{system}=Ψ_{total}=Ψ_s+Ψ_p+Ψ_g+Ψ_m
$$
The symbols $Ψ_s$, $Ψ_p$, $Ψ_g$, and $Ψ_m$ represent the solute, pressure, gravity, and matric potentials, respectively. The term *system* can refer to the water potential in various compartments, including soil water ($Ψ_{soil}$), root water ($Ψ_{root}$), stem water ($Ψ_{stem}$), leaf water ($Ψ_{leaf}$), or the water in the atmosphere ($Ψ_{atmosphere}$). Changes in the individual components of these potentials either increase or decrease the total water potential of a system. 

When this happens, water moves to achieve equilibrium, transitioning from a compartment with higher water potential to one with lower water potential. This movement continues until the difference in water potential between the two systems ($\Delta Ψ$) reaches zero ($\Delta Ψ = 0$). For water to flow through a plant from the soil to the air—a process known as transpiration—the following relationship must be maintained: $Ψ_{soil} > Ψ_{root} > Ψ_{stem} > Ψ_{leaf} > Ψ_{atmosphere}$. 

Water movement is driven solely by $\Delta Ψ$, rather than by the individual components themselves. However, since these components influence the overall $Ψ_{system}$, a plant can regulate water movement by adjusting the individual components, particularly the solute potential ($Ψ_s$).

See [Transport of Water and Solutes in Plants - Biology 2e | OpenStax](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants) for information about how water flows through a plant system.


```{figure} https://openstax.org/apps/archive/20230220.155442/resources/bc6e2dbc1c7559822f42a0e88cb260bceb185c3c
---
name: sap-ascent-tree
figclass: margin-caption
---
The cohesion–tension theory of sap ascent is shown. Evaporation from the mesophyll cells produces a negative water potential gradient that causes water to move upwards from the roots through the xylem. Image source: [Transport of Water and Solutes in Plants](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants)
```

Plant transpiration is essentially an invisible process. Water evaporates from the surfaces of leaves, but we cannot see the leaves "breathing." One way to visualize transpiration is to place a plastic bag around some leaves. During a growing season, a single corn plant can transpire around 4 liters per day, a mature oak tree can transpire up to 400 liters per day, and a hectare of actively growing forest can transpire more than 50,000 liters per day. At the ecosystem level, transpiration rates can vary, ranging from less than 1 millimeter per day in arid regions to over 5 millimeters per day in tropical forests (note that these units are similar to those used for precipitation).

Since water vapor also evaporates from the soil, we would have observed even more water vapor captured if we had wrapped the plastic bag around the soil.

Several factors influence evapotranspiration in a critical zone (or ecosystem):
- **Temperature**: Higher temperatures generally increase transpiration rates due to greater evaporative demand.
- **Humidity**: Lower humidity results in higher transpiration rates, as the air can hold more water vapor.
- **Wind**: Increased wind speed can enhance transpiration by removing the saturated air surrounding the leaves.
- **Light**: Higher light levels (e.g., full sun) usually increase transpiration as stomata open wider.
- **Water Availability**: Transpiration rates decrease when soil water is limited, helping to prevent excessive water loss.

```{admonition} Water Balance of a Tree

1. Consider the water balance at the scale of a single tree. What pools (reservoirs) are present? What processes change fluxes into and out of the reservoirs?
2. Label the water cycle around that tree, including reservoirs and fluxes.
3. How would dominant water cycle components differ between different climates?
4. If you are designing a study to estimate water yield at a given climate ([Köppen climate classification - Wikipedia](https://en.wikipedia.org/wiki/K%C3%B6ppen_climate_classification)), what data do you need to collect to create a water balance for a tree here?
5. Write a general equation to calculate water yield or discharge from this system.
```


## Readings and resources for this section

1. [Surface Water Information by Topic | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/surface-water-information-topic)
2. [Physical Hydrology, Third Edition, by S. Lawrence Dingman](https://www.waveland.com/browse.php?t=382) - See OAKS for Chapters 1 and 2.
3. [30.5 Transport of Water and Solutes in Plants - Biology 2e | OpenStax](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants)
4. Godoy, V., et al. 2021. “The Global Water Cycle Budget: A Chronological Review.” [Surveys in Geophysics 2021 42:5 42 (5): 1075–1107.](https://doi.org/10.1007/S10712-021-09652-6)
5. Trenberth, K.E., et al. 2007. “Estimates of the Global Water Budget and Its Annual Cycle Using Observational and Model Data.” [Journal of Hydrometeorology 8 (4): 758–69.](https://doi.org/10.1175/JHM600.1)
6. Bales, R.C., et al. 2011. “Soil Moisture Response to Snowmelt and Rainfall in a Sierra Nevada Mixed-Conifer Forest.” [Vadose Zone Journal 10 (3): 786–99.](https://doi.org/10.2136/VZJ2011.0001)
7. Abbott, B.W. et al. 2019. “Human Domination of the Global Water Cycle Absent from Depictions and Perceptions.” [Nature Geoscience 2019 12:7 12 (7): 533–40.](https://doi.org/10.1038/s41561-019-0374-y)