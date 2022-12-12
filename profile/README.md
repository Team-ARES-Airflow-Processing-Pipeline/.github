# Welcome to Team ARES!

## The Project - AirFlow Processing Pipeline
Integrated Software for Imagers and Spectrometers (ISIS) is a software package consisting of over 300 individual programs utilized by the USGS (United States Geological Survey) Astrogeology Research Program for cartographic image processing. In its current form, the ISIS workflow is challenging and unintuitive for researchers, having been written as C++ programs executed via linux terminal. The team at the USGS are envisioning a plan to provide greater ease-of-use and accessibility to these programs via the construction of pipelines, ie. easily reproducable “recipes” that process input data through a series of programs in sequence.

## The Solution
Our ultimate goal is to modernize the current ISIS workflow into a Directed Acylic Graph (DAG) pipeline format. We plan to use Apache AirFlow, an established processing pipeline software, along with its corresponding Python bindings to wrap ISIS programs into graph nodes. Each node can then be utilized by researchers in Apache AirFlow generate visual workflow graphs, an easy method of visualizing processing tasks and their order of operations. By doing this, researchers at the USGS will be able to quickly, efficiently, and easily create actionable products, in the form of Mars imaging, through the use of our pipelines. They will also be able to save and create new pipelines to make the process smooth and intuitive.

## Introduction Video
[![Everything Is AWESOME](https://img.youtube.com/vi/Q8ULtCwcadw/0.jpg)](https://www.youtube.com/watch?v=Q8ULtCwcadw "Team ARES Introduction Video")
