---
title: "PREEVENTS:  A Dynamic Unified Framework for Hurricane Storm Surge Analysis and Prediction Spanning across the Coastal Floodplain and Ocean"
feature_text: Research

---
<br />

National Science Foundation





Clint Dawson, UT Austin; Joannes Westerink, University of Notre Dame; Ethan Kubatko, Ohio State University; Laxmikant Kale, University of Illinois-Urbana Champagne

Storm-driven coastal flooding is influenced by many physical processes including riverine flows, regional rainfall, wind, atmospheric pressure, wave-induced set up, wave runup, tides, and fluctuating baseline ocean water levels. Operational storm surge models such as NOAA's Extratropical Surge and Tide Operational Forecast System (ESTOFS) incorporate a variety of these processes including riverine discharges, atmospheric winds and pressure, waves, and tides. However, coastal surge models do not typically incorporate the impact of rainfall across the coastal floodplain nor fluctuations in background water levels due to the oceanic density structure. Nonetheless, the floodplain hydrology and ocean baseline water levels provide vital controls in riverine and estuarine environments (e.g., the dramatic effect seen in the Houston metropolitan region during Hurricane Harvey in 2017 and in North Carolina during Hurricane Florence in 2018). Recent events have shown that a unified approach that incorporates all of the relevant physical processes is critical for accurate predictive simulations of coastal flooding due to extreme events. This project will tackle this challenge by melding hydrology, hydraulics, and waves into a dynamic unified computational framework that uses unstructured meshes spanning from the deep ocean to upland areas and across the coastal floodplain. More accurate coastal flood forecast and analysis models will better inform forecasters in the National Weather Service and state and local disaster managers to issue warnings for evacuation and emergency planning. In addition, insurance companies and planners will be better able to assess flood risk in coastal zones.  Finally, improved flood models will lead to better guidance on development and construction practices and will help make cities more resilient and will reduce risk for coastal populations and infrastructure.


The unified framework will improve the predicted water level gradient and flows throughout the coastal floodplain by integrally considering the rainfall-driven hydrology within the coastal floodplain and improving the background open ocean water level. Well-developed but coarse global ocean models will be heterogeneously coupled to a high-resolution 2D shallow water equation model in order to account for large-scale baroclinic ocean processes that impact coastal water levels. Specifically temperature and salinity fields and vertical velocity profiles will be extracted from a global three dimensional HYCOM model and downscaled and used to drive baroclinic pressure gradient terms and internal tide generation/dissipation terms in a high resolution two dimensional implementation of ADCIRC. This will account for the impact of the ocean’s baroclinicity and current systems on coastal and inland water levels.  Across the coastal floodplain, rainfall runoff will be gravity driven and is described well by the kinematic wave equation. On the other hand, as storm surge propagates overland, the flow pressurizes and the flow is described by the shallow water equations. We will develop strategies to dynamically apply the correct governing equations/physics depending on the prevailing hydraulics. Interface strategies and conditions between heterogeneous physics will be developed that allow the interfaces to move in time and space for the range of physics, from dry to surface runoff to pressurized flow. Applying the right physics and associated mathematical models as the storms evolve will result in more robust, accurate and efficient models. Thus our approach will dynamically account for the hydrologic-hydrodynamic interaction of water across the floodplain. Dynamic load balancing will account for widely varying CPU costs for each set of physics and the dynamic migration of the physics will be implemented within a heterogeneous parallel computing environment.


{% include button.html text="Back" link="/research_page/" %}


