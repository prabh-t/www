### Projects

Some of the projects I contribute to can be found in [Github](https://github.com/prabh-t).

#### DEMA
A proposal to rewrite the core analytics module of VELaSSCo to run on a Tier 0 HPC system (ARCHER).

#### VELaSSCo - Big Data and HPC

VELaSSCo[VELaSSCo](http://velassco.atosresearch.eu/) project [url] The open-source platform comprising of the core analytics module implemented using Hadoop/HBase is going to be made available in a [public repository](https://github.com/velassco/VELASSCO) soon.

VELaSSCo aims to provide new visual analysis methods for large-scale simulations serving the petabyte era and preparing the exabyte era. It does this by adopting Big Data tools and architectures for the engineering and scientific community and by leveraging new ways of in-situ processing for data analytics and hardware accelerated interactive visualization. 

My main involvement relates to the implement of core analytics queries as MapReduce jobs. One example of such queries is the discrete-to-continuum (D2C) transform.

<img class="thumb" onclick="showImgBox(this);" src="img/velassco/fb-d2c.jpg" alt="Fluidised Bed d2c transformation" />
<img class="thumb" onclick="showImgBox(this);" src="img/velassco/d2c.jpg" alt="Spatial and temporal averaging" />

<div id="imgBox" onclick="hideImgBox(this);">
<span class="helper"></span>
<img id="largeImg" />
</div>


#### ORIGIN - Improving weather forecast using machine learning

[ORIGIN](http://www.origin-energy.eu) is a sophisticated intelligent ICT system for the management of energy in communities. I worked on parallelising and optimising a machine learning algorithm that learns and makes localised short-term weather predictions from large datasets. The prediction model is generated after extensive processing of data from various sources to learn an accurate model using feature selection, correlation analysis and regression.


#### Haskell evaluation strategies

Haskell evaluation strategies library [url](https://hackage.haskell.org/package/parallel) I extended the strategies library to include evaluation strategies defined for tree and graph data structures using advanced parallelism control mechanisms in evaluating sub-components of the structure.


#### Parallel implementations of the n-body 

I have several implementations of the n-body problem (using hierarchical tree-based algorithms) in a number of languages: Haskell, Scala, F#, Java, C, etc. These are meant for performance comparison across the languages using a variety of parallel programming models and system architectures.
