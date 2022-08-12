# CWatM-Israel
 This repository provides some specific developments aiming to model Israel water resources. It make use of the CWatM-Dev repository which includes some advanced management options, such as: reservoir operations and transfers and sector source abstraction fractions. 
 Ont op of it, this development introduces some new features as listed below:
 
 ## Wastewater module
 Make quantitative simulation of wastewater treatment, discharge and reuse avaialble. The module collects return flows (as wastewater) and urban runoff (subject to user decision). 
 It sends the water into wastewater treatment plants (either  intensive or extensive), and allow treated wastewater reuse, discharge, and export.
 
 ## Layered version of Modflow-CWatM
 This development allow the user to simualte complex groundwater systems, including confined and non confined aquifers, aquitards, etc. It allows increased user control on Modflow options, and resolve some 
 balancing issues from the current version of Modflow-CWatM. First, it limits groundwater recharge based on the aquifer vertical permeability and send Modflow's rejected recharge to interflow. Second, it now has a user defined setting allwoing to reduce
 discrepancy between CWatM and Modflow's groundwater pumping. 
 
 ## Desalination
 As part of the sector source abstraction fraction - users can now define desalination sectoral use fractions, and annual available desalinated seawater.
