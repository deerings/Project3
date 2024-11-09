# DSC 209R Project3: Interactive Visualization
8-Nov-2024

Mengkong Aun,
Alison Cher,
and Sean Deering

For our project, we created an interactive plot using the Bight 18 Sediment Toxicity Water Quality dataset from The Southern California Coastal Water Research Project (SCCWRP).

A bight is a long, gradual bend or recess in the shoreline that forms a large, open bay. Bight 18 is one such region of Southern California that spans from San Diego to Los Angeles.

The dataset that we used is available on this Github page as well as <a href=https://dataportal.sccwrp.org/datasets/sccwrp::bight-18-sediment-toxicity-water-quality/explore>here</a>.

We chose to display pH levels recorded at various sites within Bight 18 over various timepoints (a feature in the data that ranged from -10 to 10. This was achieved using a dot plot, and one or more site readings can be toggled on and off using a drop-down menu which allows users to select sites to display pH readings recorded within Bight 18 at different time points. We experimented with a few different variations of dot plots and line plots, but ultimately setted on the dot plot as we felt it was most easy to interpret. We also felt that it made sense to encode the site IDs as different colors, such that when different pH readings of sites were overlaid it would be easier to distinguish between them. In addition to the dropdown menu to toggle sites, we felt that using a tooltip (on mouseover) to display pH readings and timepoints would also be useful to users of our visualization.

Our team met to brainstorm ideas at an initial zoom meeting, and each member presented an idea for a data source as well as their proposed method of visualizing said data. We settled on Alison's choice of dataset (linked above). Our group decided on Mengkong's choice of visualization style after workshopping a couple of different ideas, and Sean handled pushing the finished prototype to Github and deploying the Github pages site. We held zoom calls periodically throughout the week where we worked through the D3.js coding process together, and went through a few different iterations of our plot before we decided on the final prototype. We spent approximately 12 people hours total on this project, and the most difficult part was probably coming up with out initial idea for the plot, although the actual coding in D3.js proved to be a bit of a learning curve. Similarly, deciding on our final style/aesthetics of the plot and interactive features took a good bit of time.

Thank you for checking out of plot, we hope you enjoy it!
