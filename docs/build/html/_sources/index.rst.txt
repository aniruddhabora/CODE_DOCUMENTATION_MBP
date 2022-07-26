.. Lumache documentation master file, created by
   sphinx-quickstart on Sat Jul 23 10:18:09 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Quantification of extreme weather events and their future changes using Physics-Informed DeepONet modeling and functional priors
================================================================================================================================




The governing equations of climate and weather prediction models
are chaotic, non-linear and multi-scale in nature. This is in part due to the underlying turbulent fluid motions which are strongly coupled with other multi-physics processes such as convection, particle transport etc. Given the ubiquitous effects of weather and climate dynamics on civilization, the ability to observe, measure, reconstruct and predict the evolution of weather and climate systems is of utmost importance. 
%This remains a tall task and is heavily reliant on a computational approach for various predictions from an initial state.
*Exact* computations  themselves are prohibitively expensive due to the large degrees of freedom that are active in the climate system [`Zhou_et_al:2021 <https://doi.org/10.2151/jmsj.2021-029>`_]. Therefore, a wide range of critically needed subgrid physics parameterizations there is a critical need for reduced order models that can have been developed to simulate the physical processes and their interactions with atmospheric circulations [`Satoh_et_al:2019 <https://doi.org/10.2151/jmsj.2021-029>`_]. These models lay on a sliding scale of well-characterized physics and experimental empiricism. Within computation, subgrid physics parameterizations are used to simulate subgrid-scale processes, while processes at or larger than the model grid-scale are explicitly resolved. As uncertainty in subgrid physics parameterizations is a major source of uncertainty in modeling climate change, recent work has used data-driven methods to parameterize the subgrid physics used in coarse-scale climate models to improve the fidelity of such models and reduce uncertainty in climate projections [`Bretherton_et_al_2022 <https://doi.org/10.1029/2021MS002794>`_].

.. toctree::
   :maxdepth: 2
   :caption: Contents:




Hybrid Modelling
----------------



.. toctree::
   :maxdepth: 2
   :caption: Contents:
  
  modules/Data
  modules/Extreme_Events
  modules/DeepONet_Online
  modules/LSTM_based_offline_correction
  


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`



