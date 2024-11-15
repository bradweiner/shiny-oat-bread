# ShinyLive Bread Timing App

This is a web-based bread timing calculator built with **Shiny** and **ShinyLive**, designed to track the various steps in making bread. Each step is dependent on the previous one, and users can dynamically adjust times based on when they complete each step. The app is fully deployable as a static website using **ShinyLive**.

## Features
- Input times for each step in a bread recipe.
- Subsequent steps adjust automatically if any time is changed.
- Easy-to-use interface with 12-hour AM/PM time inputs.
- Real-time recalculation of step timings.
- Reset button to return all steps to their default times.
  
## Steps in the Recipe
1. Feed Starter
2. Start Autolyse & Make Porridge
3. Add Salt and Start Bulk Fermentation
4. First Turn and Mix-in Oats
5. Turn
6. Turn
7. Turn
8. Turn and leave for 2.5 hours
9. Turn on Counter and Shape for Bench Rest
10. Fold and Fridge

## How to Deploy Locally

1. **Install R and Required Packages**:
   Ensure you have R installed. You'll need the `shiny` and `shinylive` packages:
   ```r
   install.packages("shiny")
   remotes::install_github("rstudio/shinylive")
