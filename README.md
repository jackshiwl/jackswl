# Climate Research

Most papers in well-known journals have high-level descriptions of the various methodologies and terminologies used, which I find difficulties sourcing for other simpler forms of explanations and information. Therefore, this [journal](https://jackshiwl.github.io/jackswl/) is created to document websites, articles, and videos that I found useful along the way. 

## Introduction to Climate Models 
These websites provide a detailed history and introduction to climate models. <br />
[[Carbon Brief] How do climate models work?](https://www.carbonbrief.org/qa-how-do-climate-models-work/) <br />
[[Carbon Brief] Timeline: The history of climate modelling](https://www.carbonbrief.org/timeline-history-climate-modelling/) <br /> 



## Reanalysis and Reforecast
These websites provide explanations to what are reforecast and reanalysis data <br />
[[ECMWF] Fact sheet: Reanalysis](https://www.ecmwf.int/en/about/media-centre/focus/2020/fact-sheet-reanalysis#:~:text=Reanalysis%20combines%20past%20short%2Drange,system%20as%20their%20starting%20point.) <br />

I found these 2 videos to be much more intuitive in explaining reanalysis data. In the present day, we are continuously observing the weather all over the world, and this video compares that with the filming of a football kick. In the past, weather observations were rare, which the video compares that to having three different pictures of the football kick instead of a full film. Hence, reanalysis is a model based on physical equations in hope of reconstructing the full football trajectory using the three different pictures. <br />
[Analogy between reanalysis and football kick](https://www.youtube.com/watch?v=7Vcm7WSpPAg) <br />
[Analogy between reanalysis and jigsaw puzzle](https://www.youtube.com/watch?v=FAGobvUGl24)

> Re-forecasts are forecasts produced at the current time but starting from some point in the past. They are used to estimate a forecast model climate, which is needed to calibrate forecast products. Like all forecasts, re‑forecasts require a set of initial conditions, which reanalysis can readily supply. ECMWF uses 11‑member operational ensemble re-forecasts initialised every Monday and Thursday and covering the past 20 years to construct an extended-range model climate as a function of forecast lead time. This is in turn used to calculate extended-range forecast anomalies, e.g. weekly mean departures of predicted variables, such as 2‑metre temperature or precipitation, from the model climate. [[ECMWF] Use of ERA5 reanalysis to initialise re‑forecasts proves beneficial](https://www.ecmwf.int/en/newsletter/161/meteorology/use-era5-reanalysis-initialise-re-forecasts-proves-beneficial)

> These are retrospective weather forecasts generated with a fixed numerical model. Model developers
could use them for diagnosing model bias, thereby facilitating the development of new, improved versions of the model. Others could use them as data for statistically correcting weather forecasts, thereby developing improved, user-specific products [e.g., model output statistics (MOS) Glahn and Lowry 1972; Carter et al. 1989]. Others may use them for studies of atmospheric predictability. Unfortunately, extensive sets of reforecasts are not commonly produced utilizing the same model version as is run operationally. These computationally expensive reforecasts are "squeezed out" by operational data assimilation and forecast models that are run at as fine a resolution as possible. [Hamill, T. M., Whitaker, J. S., & Mullen, S. L. (2006). Reforecasts: An important dataset for improving weather predictions. Bulletin of the American Meteorological Society, 87(1), 33-46.](https://journals.ametsoc.org/view/journals/bams/87/1/bams-87-1-33.xml)


## Downscaling
Downscaling of climate change models is the procedure of using large-scale climate models to make climate predictions at finer temporal and spatial scales to fit the purpose of local level analysis and planning. <br />
[Climate Model Downscaling](https://www.gfdl.noaa.gov/climate-model-downscaling/) <br />
[A Review of Downscaling Methods for Climate Change Projections](http://www.ciesin.org/documents/Downscaling_CLEARED_000.pdf)

## Statistical Downscaling
In progress

## Dynamical Downscaling
### Grid nesting
> Grid nesting is very common in mesoscale and limited-area modeling but is not often used in global modeling. A nested grid is a model grid which covers a smaller area than its ‘parent’ or coarse grid but has a smaller grid spacing, allowing for smaller scale features to be better resolved. The boundary conditions for the nested grid are then formed from coarse-grid data, a procedure for which few satisfactory methods are known to exist. The nested-grid data can then feed back onto the coarse grid through ‘two-way’ nesting, in which the coarse-grid solution is periodically replaced with that on the nested grid. This procedure allows for nested-grid disturbances to influence their large-scale environment, which is necessary for simulating hurricanes, and may also cause smaller reflections at the boundary of the nested grid than if there were no feedback. [Grid nesting and stretching in the GFDL atmosphere dynamical core](https://www.gfdl.noaa.gov/lucas-harris-nesting/)

> The principle behind nested modelling is that, consistent with the large-scale atmospheric circulation, realistic regional climate information can be generated by integrating an RCM if the following premises are satisfied: time-varying large-scale atmospheric fields (winds, temperature and moisture) are supplied as lateral boundary conditions (LBCs) and SST and sea ice as lower boundary conditions; the control from the LBCs keeps the interior solution of the RCM consistent with the driving atmospheric circulation; and sub-grid scale physical processes are suitably parametrized, including fine-scale surface forcing such as orography, land-sea contrast and land use. [Nested Regional Climate Models](https://archive.ipcc.ch/publications_and_data/ar4/wg1/en/ch11s11-10-1-2.html)

### Parameterization
> Numerical models used for weather prediction and climate simulation must in principle account for such averaged effects of processes that cannot be resolved. The term ‘parameterization’ has come into general use in reference to representing the effects of such processes in terms of quantities that can be resolved in numerical models. These parameterized representations of unresolved processes invariably depend explicitly or implicitly on the spatial resolutions and other factors that are not necessarily directly related to the mathematical process that was used to derive the basic approximate set of algebraic equations. <br />

> A fundamental concept in parameterization is that it is possible to account for the important effects of unresolved processes in terms of those that can be resolved. This concept assumes the existence of robust relationships between processes that have different spatial and temporal scales such that the essential properties of the relevant unresolved processes are determined by the resolved scales to a sufficient degree to enable quantification of their effects in terms of the variables that are resolved and predicted. [Parameterizations: representing key processes in climate models without resolving them](https://onlinelibrary.wiley.com/doi/pdf/10.1002/wcc.122)

## Deep Learning Models
### CNN
Here are some stackoverflow links explaining different dimensions of convolutions within CNN <br />
[Intuitive understanding of 1D, 2D and 3D convolutions in CNN](https://stackoverflow.com/questions/42883547/intuitive-understanding-of-1d-2d-and-3d-convolutions-in-convolutional-neural-n/44628011#44628011) <br />
[Difference between the input shape for a 1D CNN, 2D CNN and 3D CNN](https://stackoverflow.com/questions/66220774/difference-between-the-input-shape-for-a-1d-cnn-2d-cnn-and-3d-cnn)

## Papers
In progress
