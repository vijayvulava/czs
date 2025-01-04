# 4.1 Energy Budget

We will analyze water and energy flux data collected from different biomes to enhance our understanding of the measurements, processes, and regional exchanges of water and energy. This analysis pertains to the grand challenges of grasping essential climate dynamics, boundary layer processes, Earth's energy budget, and radiative forcing. It also aligns with the geoscience literacy themes of energy sources that drive Earth processes and the changes occurring in the Earth system at multiple scales, along with the interconnections between the water and energy cycles. 

Two primary learning goals of this module are to understand better how the conservation of mass and energy leads to the development of the water and energy budget equation and to explore and extract data from Critical Zone Observatory (CZO) flux databases.

In this module, we will:

- Use diagrams of the water and energy cycles to discuss how these elements are partitioned at the watershed scale.
- Learn about the instruments used to collect water and energy flux data.
- Examine radiative forcings gathered from various CZO sites to compare climatic and site-specific influences.
- Explore and visualize energy flux data from CZO and related databases.
- Calculate a measure of Effective Energy and Mass Transfer ($EEMT$) in relation to the potential for Critical Zone evolution.
- Use CZO micro-meteorological data to calculate reference evaporation at a chosen site.

<div class="container">
<iframe src="https://www.youtube.com/embed/U2CPwWgY_G4" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


## Solar Energy

The energy released by the Sun is known as *radiant energy*, which travels in waves through space. These *electromagnetic waves* possess electrical and magnetic properties that enable them to cover vast distances at the speed of light. Electromagnetic waves behave like ocean waves, featuring crests and troughs; however, they do not transport matter. When an object absorbs radiant energy, it is converted into heat.

The term *electromagnetic energy* encompasses all forms of energy that travel in waves through space, including light, heat, X-rays, radar, and radio waves. Each type of wave has a specific *wavelength* and *frequency*. The complete range of all possible wavelengths of electromagnetic energy is referred to as the electromagnetic spectrum.

The Sun emits radiant energy composed of 8% ultraviolet, X-ray, and gamma-ray wavelengths, 47% visible light wavelengths, and 45% infrared wavelengths.

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/EM_Spectrum_Properties_edit.svg/1920px-EM_Spectrum_Properties_edit.svg.png
---
name: electromagnetic-spectrum
figclass: margin-caption
---
The electromagnetic spectrum shows various properties across the range of frequencies and wavelengths. Image source: [Electromagnetic spectrum - Wikipedia](https://en.wikipedia.org/wiki/Electromagnetic_spectrum)
```

>An important physical law states that all objects radiate energy in wavelengths related to their surface temperatures: The hotter the object, the shorter the wavelengths emitted. This law holds for the Sun and Earth.

### Heat and Temperature

Temperature and heat are distinct yet interconnected concepts. Temperature measures the average kinetic energy, or average speed, of individual molecules in a substance. When molecular movement increases, the temperature rises. In contrast, heat is a form of energy that transfers between molecules and, consequently, between different bodies or substances. Heat is the flow of kinetic energy driven by a temperature difference.

While heat is regarded as energy, temperature is related to the amount of energy in a substance. Heat crosses a system boundary in response to a temperature gradient. Since temperature reflects the average kinetic energy of molecules, it can also be understood as a measure of heat. An object with a "hot" temperature contains more heat energy, whereas an object with a "cold" temperature contains less.

Heat always flows from matter at a higher temperature to matter at a lower temperature. This heat flow between objects or substances ceases once their temperatures, and thus their kinetic energy levels, equalize.

When we apply these principles to the Sun and Earth, we observe that the hot Sun radiates shorter wavelengths of energy, primarily around 0.5 µm, with most radiation occurring in the visible region of the electromagnetic spectrum. In contrast, the cooler Earth emits energy at longer wavelengths, primarily in the infrared range, centered around 10 µm.

As electromagnetic energy travels through Earth's atmosphere, certain gases, such as water vapor and carbon dioxide, absorb specific wavelengths. These gases exhibit varying responses to radiation, being transparent to some wavelengths while absorbing others.

```{figure} https://earthobservatory.nasa.gov/ContentFeature/EnergyBalance/images/reflected_radiation.jpg
---
name: atmos-energy-budget
figclass: margin-caption
---
Of the $\pu{340 W m-2}$ of solar energy that falls on the Earth, $\pu{29 \%}$ is reflected into space, primarily by clouds, other bright surfaces, and the atmosphere itself. About $\pu{23 \%}$ of incoming energy is absorbed in the atmosphere by atmospheric gases, dust, and other particles. The remaining $\pu{48 \%}$ is absorbed at the surface. Image source: [Climate and Earth’s Energy Budget (nasa.gov)](https://earthobservatory.nasa.gov/features/EnergyBalance/page1.php)
```

For more information, see [Climate and Earth’s Energy Budget (nasa.gov)](https://earthobservatory.nasa.gov/features/EnergyBalance/page1.php).

## Earth-Atmosphere Energy

The inputs for the Earth–atmosphere energy budget consist of shortwave radiation, which includes ultraviolet light, visible light, and near-infrared wavelengths. Only a portion of the *insolation* (incoming solar radiation) that enters Earth's atmosphere reaches its surface; the rest is either reflected into space or absorbed by the atmosphere. Insolation arrives at the Earth's surface as either direct or diffuse radiation. Direct sunlight creates shadows, while diffuse radiation provides a shadowless light seen in shaded areas or on cloudy days. This energy is then absorbed by the Earth's surface and converted into heat. The outputs of our energy budget include shortwave radiation (the light reflected before reaching the Earth's surface) and longwave radiation in the thermal infrared wavelengths.


```{figure} https://www.noaa.gov/media/image_download/60247be8-d80e-4d4d-a482-de49136b195f
---
name: earth-energy-budget
figclass: margin-caption
---
The earth-atmosphere energy balance is the balance between incoming energy from the Sun and outgoing energy from the Earth. The energy released from the Sun is emitted as shortwave light and ultraviolet energy. When it reaches the Earth, some are reflected in space by clouds, some are absorbed by the atmosphere, and some are absorbed at the Earth's surface. Image source: [The Earth-Atmosphere Energy Balance (weather.gov)](https://www.weather.gov/jetstream/energy)
```

### Types of Energy Transfers

Insolation, or incoming solar radiation, is the primary energy input driving the Earth-atmosphere system, but its intensity varies across different global locations. In the equatorial and tropical regions, there are only minor variations in day length and high sun altitude, resulting in relatively consistent insolation values ranging from approximately 180 to 220 W m². However, insolation decreases toward the poles, particularly around 25° latitude in the Northern and Southern Hemispheres. Generally, low-latitude deserts worldwide experience greater insolation at the surface due to frequently cloudless skies.

As insolation travels toward the Earth’s surface, it encounters an increasing density of atmospheric molecules. These gases, dust, cloud droplets, water vapor, and pollutants interact with insolation, redirecting radiation without changing its wavelengths. This phenomenon is known as *scattering*, and it accounts for some of the insolation that does not reach Earth’s surface but is instead reflected into space. Diffuse radiation is the portion of incoming energy that successfully reaches Earth’s surface after scattering.

Additionally, some of the arriving solar energy is directly reflected into space, a process called *reflection*. Over a year, clouds reflect about 20% of insolation, significantly more than what is reflected by Earth’s surface. Air pollutants, whether natural or man-made, also contribute to this reflection. The roles of clouds and aerosols in the Earth-atmosphere energy budget will be discussed further.

*Albedo* describes a surface's reflective quality or intrinsic brightness. Albedo is an essential factor influencing the amount of insolation that reaches Earth, expressed as the percentage of insolation reflected: 0% indicates total absorption, while 100% signifies total reflectance.

Insolation—both direct and diffuse—that is not part of the 31% reflected by Earth’s surface and atmosphere is absorbed either by the atmosphere or by Earth’s surface. Absorption involves the assimilation of radiation by molecules of matter, which converts radiation from one form of energy to another. Solar energy is absorbed by land and water surfaces (about 45% of insolation) and atmospheric gases, dust, clouds, and stratospheric ozone. Once at Earth’s surface, this absorbed energy is converted into either longwave radiation or chemical energy, such as the energy used by plants during photosynthesis. The absorption process raises the temperature of the absorbing surface.


### Heat Transfer at Earth's Surface

Two types of heat energy are essential for understanding Earth's and the atmosphere's energy budgets. *Sensible heat* can be “sensed” as temperature because it comes from the kinetic energy of molecular motion. To feel this heat, radiant energy from the Sun must first be absorbed. *Latent heat*, or “hidden” heat, is the energy gained or lost when a substance changes from one state to another, from liquid water to water vapor or from liquid water to ice. Unlike sensible heat transfer, latent heat transfer occurs without a change in the substance's temperature while it undergoes a physical change. However, the surroundings may gain or lose heat. The latent heat absorbed during evaporation is a significant component of the Earth-atmosphere energy system.

Heat energy, called thermal energy, can be transferred throughout the Earth's atmosphere, land, and water bodies through several processes. *Radiation* is the transfer of heat through electromagnetic waves.

*Conduction* involves the molecule-to-molecule transfer of heat energy as it diffuses through a substance. When molecules warm up, their vibration increases, causing them to collide with neighboring molecules, transferring heat from warmer to cooler areas.

In gases and liquids, energy is also transferred through *convection*, which transfers heat by mixing or circulation. In the atmosphere or bodies of water, warmer (less dense) masses tend to rise, while cooler (denser) masses sink, establishing convection patterns. This physical mixing usually involves strong vertical motion. When horizontal motion predominates, this process is called *advection*.


```{figure} https://upload.wikimedia.org/wikipedia/commons/f/f4/Heat-transmittance-means2.jpg
---
name: heat-transfer
figclass: margin-caption
---
The four fundamental modes of heat transfer processes are illustrated with a campfire. Image source: [Heat transfer - Wikipedia](https://en.wikipedia.org/wiki/Heat_transfer)
```

## Energy Balance at Earth's Surface

Energy and moisture are constantly exchanged with the lower atmosphere at the Earth's surface, known as the boundary layer. Various characteristics of Earth's surface, such as the presence or absence of vegetation and local topography, influence the energy balance within this boundary layer. Additionally, the height of the boundary layer varies over time and across different locations.

In any given location, the surface receives and loses shortwave (SW) and longwave (LW) energy according to a straightforward scheme:

Net radiation ($R_n$) is the total of all radiation gains and losses and fluctuates with the length of the day throughout the seasons, the amount of cloud cover, and latitude.

$$ 
R_n = SW_{Insolation} \downarrow - SW_{Reflection} \uparrow + LW_{Infrared} \downarrow - LW_{Infrared} \uparrow
$$

Heat is transferred in and across most soil surfaces mainly through conduction. This transfer occurs predominantly downward during the day (or in summer), while heat moves toward the surface at night (or in winter). Generally, energy exchange with the surface or surrounding materials becomes minimal at a depth of less than a meter. Energy flowing from the atmosphere into the surface is considered a positive value (a gain), while energy moving outward through sensible and latent heat transfers is regarded as a negative value (a loss) in the surface account.


## Effective Energy and Mass Transfer

An integrated framework based on thermodynamic theory characterizes the critical zone (CZ) as a system open to energy and mass fluxes, influenced by radiant, geochemical, and elevational gradients. [Rasmussen et al. (2011)](https://doi.org/10.1007/s10533-010-9476-8) demonstrated the relative importance of solar radiation, water, carbon, and physical/chemical denudation mass fluxes in the CZ energy balance. They used rates of effective energy and mass transfer ($EEMT$, $\pu{W m-2}$) measured in watts per square meter (W m⁻²) to quantify the relevant flux-gradient relationships.

$EEMT$ includes inputs of energy associated with reduced carbon from primary production ($E_{BIO}$) and heat influx to the soil from precipitation minus evapotranspiration and surface runoff ($E_{PPT}$):

$$
EEMT = E_{BIO} + E_{PPT}
$$

The balance of energy and mass flux involved in CZ development (Λ) may then be stated as:

$$
Λ = E_{ET}+E_{PPT}+E_{BIO}+E_{ELV}+E_{GEO}+ξ
$$

Each term is defined below:

The energy and mass flux associated with evapotranspiration, denoted as $E_{ET}$ (in $\pu{W m-2}$), can be expressed by the equation:

$$
E_{ET} = ET \cdot h_\nu
$$

In this equation, $ET$ represents the mass flux of precipitation to evapotranspiration (in $\pu{kg m-2 s-1}$), and $h_\nu$ is the latent heat of vaporization (in $\pu{J kg-1}$), which quantifies the fraction of radiant energy used to evaporate a given mass of water. This energy flux is primarily transferred from the Critical Zone (CZ) and returned to the atmosphere.

The water mass flux converted to energy flux is represented as $E_{PPT}$ (in $\pu{W m-2}$) and can be calculated using the formula:

$$
E_{PPT} = F \cdot c_w \cdot \Delta T
$$

Here, $F$ is the mass flux of precipitation to base flow from the water balance (in $\pu{kg m-2 s-1}$), $c_w$ is the specific heat of water (in $\pu{J kg-1 K-1}$), and $\Delta T = T_{ambient} - T_{ref}$, where $T_{ambient}$ refers to the ambient water temperature at the time of water flux (assumed to be equal to the ambient air temperature), and $T_{ref}$ is a reference temperature (273 K). When $T_{ref} > T_{ambient}$, then $E_{PPT} = 0\).

The carbon mass flux, represented as $NPP$, can also be converted to energy flux and is denoted as $E_{BIO}$ (in $\pu{W m-2}$):

$$
E_{BIO} = NPP \cdot h_{BIO}
$$

In this formula, $NPP$ stands for net primary production (in $\pu{kg m-2 s-1}$), and $h_{BIO}$ is the specific biomass enthalpy (in $\pu{J kg-1}$). We assume an average $h_{BIO} = \pu{22e6 J kg-1}$ based on the average values for various organic materials derived from calorimetric analyses.
 
Physical denudation can be expressed in energy flux units as $E_{ELV}$ (in $\pu{W m-2}$), based on the change in the potential energy of uplifted sediment. It is calculated using the equation:

$$
E_{ELV} = m \cdot g \cdot U
$$

where $m$ is the mass of sediment per unit area (in $\pu{kg m-2}$), $g$ is the gravitational constant (approximately $\pu{9.81 m s-2}$), and $U$ is the uplift rate (in $\pu{m s-1}$). The mass of sediment available for transport can be approximated using rock density, $\rho$ (in $\pu{kg m-3}$), and regolith depth, $H_S$ (in $\pu{m}$), where $m = \rho \cdot H_S$, assuming that all soil and saprolite layers have the potential to be physically transported.

The mass and energy flux associated with chemical denudation and specific mineral transformations can be approximated using the Gibbs free energy $\Delta_{rxn}G^\circ$ (in $\pu{J mol-1}$) of a given mineral transformation reaction under the relevant environmental conditions, along with the associated mass flux:

$$
E_{GEO} = N \Delta_{rxn}G^\circ
$$

In this equation, $N$ represents the mass flux per unit area (in $\pu{mol m-2 s-1}$), a function of reaction rate and stoichiometric coefficient.

The term $\xi$ encompasses the net energy flux associated with any additional material flux into the system, such as dust, atmospheric solutes, or anthropogenic inputs like fertilizers or other amendments.

Generally, some energetic fluxes may be negligible relative to other terms but can be relevant for specific ecosystems. Over annual timescales, the relative magnitude of the individual fluxes indicates that latent heat transfer by evapotranspiration is the most significant energy flux. However, as noted, this energy is transferred mainly from the CZ back to the atmosphere, resulting in a less direct impact on subsurface development.

Considering the range of values, the key parameters for quantifying the flux of energy into and through the subsurface CZ are $E_{PPT}$ and $E_{BIO}\). These parameters describe the fraction of energy and mass effectively transferred into and through the subsurface CZ and are among the two parameters initially included in the $EEMT$ term.


## Water Budget

The hydrological cycle is crucial in transporting and cycling nutrients and energy. To manage water effectively and fairly, it's essential to quantify the various components of the hydrological cycle, a process known as constructing a water budget for a specific area. Human activities have altered the hydrological cycle, impacting specific water budget components and the water movement between these components.

```{figure} https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/media/images/USGS_WaterCycle_English_ONLINE_20221013.png
---
name: water-cycle
figclass: margin-caption
---
Global water cycle and how human water use affect where water is stored, how it moves, and how clean it is. Image source: [Water Cycle Diagrams | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/water-cycle-diagrams)
```

A water budget is a quantitative approach used to assess the availability and sustainability of water supply. It essentially states that the change in the amount of water stored in a specific area, such as a watershed, is balanced by the water inflow and outflow rate. Understanding the water budget and the associated hydrological processes is vital for effective water resource and environmental planning and management. 

Monitoring changes in the water budget over time can help evaluate the impacts of climate variability and human activities on water resources. Comparing water budgets from different regions allows quantifying how geology, soil, vegetation, and land use influence the hydrological cycle. Additionally, the water budget significantly quantifies energy and mass transfer within the Earth's critical zone (CZ).

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

Precipitation is typically measured using either automated or manual rain gauges. To calculate the total precipitation ($P$) for a watershed, multiple measurements are often taken across the area to estimate an average value. Additionally, identifying the watershed boundary is crucial for accurate calculations, known as watershed delineation. Automated tools, such as those available on [StreamStats (usgs.gov)](https://streamstats.usgs.gov/ss/), can assist in delineating the watershed of interest.

Evapotranspiration ($ET$) plays a significant role in the water balance and influences soil moisture content, groundwater recharge, and streamflow. It is responsible for returning a substantial portion of the precipitation that falls on land to the atmosphere. Generally, $ET$ is considered a loss in the water budget since it decreases streamflow, storage, and available groundwater. Various methods are available to measure $ET$ (such as potted plants or lysimeters), but many research sites commonly employ the eddy covariance flux method. Due to the challenges in measuring $ET$, several estimation methods have been developed.

Darcy's law describes groundwater movement for saturated flow through porous media, expressed as follows:

$$
Q_{GW}= k_s A \frac{dh}{dl}
$$
where $Q_{GW}$ is groundwater discharge, $k_s$ is saturated hydraulic conductivity (function of the type of rock or aquifer), $A$ is an area of cross-section, and $dh/dl$ is the hydraulic gradient (slope of the flow.)

Streamflow in streams is commonly measured using the velocity-area method, as shown below:

$$
Q_{SW}=AV
$$
where, $Q_{SW}$ is stream discharge, $A$ is cross-sectional area of a stream, and $V$ is the average velocity at a given location. In smaller streams with diffuse flows, "flumes" are installed.  In large streams, complex methods are used to measure discharge. See [How Streamflow is Measured | U.S. Geological Survey (usgs.gov)](https://www.usgs.gov/special-topics/water-science-school/science/how-streamflow-measured). 

USGS measures streamflow and makes these data available in real-time at [USGS | National Water Dashboard](https://dashboard.waterdata.usgs.gov/app/nwd/en/?region=lower48&aoi=default). For example, [Click Here for stream data for the greater Charleston area.]( https://dashboard.waterdata.usgs.gov/app/nwd/en/?region=lower48&aoi=default&view=%7B%22basemap%22%3A%22EsriTopo%22%2C%22bounds%22%3A%22-81.3917271935721%2C32.525034335310814%2C-79.05330756375152%2C33.55722732300874%22%2C%22insetMap%22%3Afalse%2C%22panel%22%3A%7B%22checkbox%22%3A%220%2C9%2C19%2C20%2C21%2C22%22%2C%22range%22%3A%220%3A1.0%2C1%3A1.0%2C2%3A1.0%2C3%3A1.0%2C4%3A1.0%2C5%3A1.0%2C6%3A1.0%2C7%3A0.8%2C8%3A0.3%2C9%3A0.5%2C10%3A0.5%2C11%3A0.5%2C12%3A0.5%2C13%3A0.5%2C14%3A0.5%2C15%3A0.5%2C16%3A1.0%2C17%3A1.0%2C18%3A1.0%2C19%3A1.0%22%2C%22select%22%3A%220%3A0%2C1%3A0%2C2%3A0%2C3%3A0%2C4%3A0%2C5%3A0%2C6%3A0%2C7%3A0%2C8%3A0%2C9%3A0%2C10%3A0%2C11%3A0%2C12%3A0%2C13%3A0%2C14%3A0%2C15%3A0%2C16%3A0%2C17%3A0%2C18%3A0%22%7D%7D )
You can also create runoff simulations at [Model My Watershed® - WikiWatershed](https://wikiwatershed.org/model/).
 

## Readings and resources for this section

1. [Climate and Earth’s Energy Budget (nasa.gov)](https://earthobservatory.nasa.gov/features/EnergyBalance/page1.php)
2. [An open system framework for integrating CZ structure and function | SpringerLink](https://link.springer.com/article/10.1007/s10533-010-9476-8)
3. [CZ Services: Expanding Context, Constraints, and Currency beyond Ecosystem Services | Vadose Zone Journal | GeoScienceWorld](https://pubs.geoscienceworld.org/vzj/article/14/1/vzj2014.10.0142/91405/Critical-Zone-Services-Expanding-Context)
4. [USGS Circular 1308: Water Budgets: Foundations for Effective Water-Resources and Environmental Management](https://pubs.usgs.gov/circ/2007/1308/)