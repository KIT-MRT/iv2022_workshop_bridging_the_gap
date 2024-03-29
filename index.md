---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.01"
  overlay_image: assets/images/header_bertha_big.png
  caption: "rviz"
title: 'Bridging the gap between map-based and map-less driving'
excerpt: 'An upcoming IV2022 workshop'
---

This workshop has been accepted at the [33nd IEEE Intelligent Vehicles Symposium (IV)](https://iv2022.com/) and will take place on June 5th in Aachen, Germany. It addresses researchers who target the deployment of fully automated driving in large-scale, changing environments and have to consider both uncertainty-affected perception and potentially outdated HD maps. The workshop will particularly benefit from the discussions between experts from a wide range of specializations such as behavior and motion planning, prediction, localization and mapping and environmental modelling. Also, we aim for the exchange between developers from academia and industry who have already gained experience with their research vehicles on public roads.

## Workshop Program
The workshop will be organized in a hybrid format. Starting from 12:25, our session will take place in Room K7 at Eurogress Aachen. If you wish to participate online, please contact bieder@fzi.de and attach your workshop registration. 

|Time (CEST)   | Title                  | Speaker |
|--------------|--------------------------------------|-----------|
|12:25 - 12:50 | **Introduction** | [Frank Bieder](https://www.mrt.kit.edu/mitarbeiter_bieder.php), [Ö. Sahin Tas](https://www.omersahintas.com/) - KIT & FZI, Germany (chairs)
|12:50 - 13:15 | **Map Perception for Mapless Urban Automated Driving** | [Annika Meyer](https://www.mrt.kit.edu/mitarbeiter_meyer.php) - KIT, Germany (Keynote)
|13:15 - 13:45 | **Seeing Without a Camera: Going from LiDAR Point Clouds to Panoramic Color Images** | [Eren Erdal Aksoy](https://aksoyeren.github.io/) - Halmstadt University, Sweden (Keynote)
|13:45 - 14:15 | **Which Maps are Needed for Autonomous Driving?** | [Igor Gilitschenski](https://www.gilitschenski.org/igor/) - University of Toronto, Canada (Keynote)
|14:15 - 14:45 | **A data-driven (r)evolution: From nuScenes to nuPlan and beyond** | [Holger Caesar](https://sites.google.com/it-caesar.de/homepage/) - TU Delft, the Netherlands (Keynote)
|14:45 - 15:30 | *Coffee break*
|15:30 - 15:50 | **A Monte Carlo particle filter formulation for mapless-based localization** | [André Przewodowski](https://cabraile.github.io/) - Universidade de Sao Paulo, Brazil
|15:50 - 16:10 | **HD maps: Exploiting OpenDRIVE potential for Path Planning and Map Monitoring** | [Alejandro Diaz](https://scholar.google.com.tr/citations?user=A4Uv_3sAAAAJ&hl=en) - University of Alcala, Spain
|16:10 - 16:30 | **HD Lane Map Generation Based on Trail Map Aggregation** | [Pascal Colling](https://www.researchgate.net/profile/Pascal-Colling-2) - Aptiv & Univ. Wuppertal, Germany
|16:30 - 16:50 | **Clothoidal Mapping of Road Line Markings for Autonomous Driving High-Definition Maps** | [Barbara Gallazzi](https://it.linkedin.com/in/barbara-gallazzi) - Politecnico di Milano, Italy
|16:50 - 17:00 | **Conclusion and Farewell** | [Frank Bieder](https://www.mrt.kit.edu/mitarbeiter_bieder.php), [Ö. Sahin Tas](https://www.omersahintas.com/) - KIT & FZI, Germany




## Scope and Topics

Today, most automated driving systems still heavily depend on HD maps. They serve as a crucial information source for various safety-critical tasks such as localization, prediction and behavior planning. By not suffering from limited range, affected by occlusions or dependent on favorable weather/light conditions, HD maps extend the foresight of an autonomous system and the robustness towards sensor failure. At the same time HD maps are expensive to acquire and even more expensive to maintain due to frequent changes of the environment. Even with huge efforts in keeping HD maps updated, they stay a snapshot of the past and can obtain outdated information, while being a crucial requirement for map-based driving. In light of this situation, many researchers tackle the future vision of map-less driving: The recent developments in sensor, sensor fusion and machine learning technologies enable a rapidly improving online modeling of the vehicle’s surrounding and on-the-fly estimation of HD map information. While there are already many approaches to predict the surrounding semantics and detect/track objects, current research also addresses the online estimation of higher-level scene understanding layers such as lane topology and traffic rules. 

While both philosophies have their strengths and are frequently considered on their own, they can both benefit from the unique advantages of the respective other. This workshop aims to bring both perspectives closer together and explore how future approaches might consider a hybrid solution. However, the workshop is not limited to this. It welcomes a wide range of contributions regarding map-based and map-less driving solutions.  

The topics of interest of the workshop include, but are not limited to:
- Online fusion of uncertainty-affected on-the-fly map estimation with potentially outdated HD maps.
- Motion and behavior planning considering uncertainty-affected map estimation and/or potentially outdated maps
- Certifiable robustness / validation of map-based, map-less or hybrid systems
- Data sets for learning higher-level scene understanding e.g. lane topologies, traffic rules.
- Leveraging existing HD maps to generate training data for on-the-fly road modeling and map estimation.
- Online road modelling and on-the-fly map estimation for autonomous driving.
- Map change detection, map update and map validation


## Contributions

 Accepted papers will be published in the conference proceeding. Papers should not exceed 6 pages (two additional pages allowed with a fee) and meet the requirements stated in the [IEEE IV 2022 Guidelines](https://iv2022.com/program/review-guidelines/). Each paper will undergo a peer-reviewing process by at least three independent reviewers. Contributions will be reviewed according to relevance, originality and novel ideas, technical soundness and quality of presentation.

Authors are encouraged to submit high-quality, original (i.e. not been previously published or accepted for publication in substantially similar form in any peer-reviewed venue including journal, conference or workshop) research. Authors of accepted workshop papers will have their paper published in the conference proceeding. For publication, at least one author needs to be registered for the workshop and the conference and present their work.

Please check the conference webpage for the details of submission guidelines - see [https://iv2022.com/workshops/](https://iv2022.com/workshops/). The Papercept submission code is 66666. Important dates (updated February 21th):  
- **Workshop paper submission deadline**: March 15th, 2022 (**extended!**)
- **Acceptance/rejection notification**: April 22th, 2022
- **Final workshop paper due**: May 1st, 2022
- **Workshop day**: June 5th, 2022

<!---
While preparing your manuscript, please follow the formatting guidelines of IEEE available here and listed below. Papers submitted to this workshop as well as IV2022 must be original, not previously published or accepted for publication elsewhere, and they must not be submitted to any other event or publication during the entire review process.
-->

## Organizers

The workshop is jointly organized by researchers from Karlsruhe Institute of Technology, University of Applied Science Esslingen, FZI Research Institute of Information Technology and Mercedes Benz AG. The organizers are:

- **Frank Bieder**, PhD Student at FZI Research Center for Information Technology
- **Haohao Hu**, PhD Student at Karlsruhe Institute of Technology
- **Florian Ries**, Development Engineer at Mercedes-Benz AG
- **Ömer Şahin Taş**, Manager at FZI Research Center for Information Technology
- **Martin Haueis**, Head of R&D Vehicle Localization Group at Mercedes-Benz AG
- **Martin Lauer**, Research Group Leader at Karlsruhe Institute of Technology
- **Thao Dang**, Professor at University of Applied Sciences Esslingen


