# Reflection

Working on the BrewMetrics BI project with GitHub Copilot helped me understand how AI assistance can be combined with a version-controlled BI workflow. Copilot was directly useful when creating the DAX measures. It provided starting points for the Month-over-Month Sales Growth, Running Total Sales, Target Attainment, and Item Sales Rank measures. The suggestions helped reduce the time required to write the initial DAX and made it easier to understand the structure of the calculations.

However, the suggestions still needed to be reviewed carefully before being added to the Power BI semantic model. In particular, the TMDL measure declarations and indentation required correction before Power BI accepted the measures. This showed me that Copilot-generated code should be treated as a starting point rather than automatically trusted.

Working with individual Git commits also changed how I approached the project. Instead of making all changes at once, I completed and committed the schema, each DAX measure, and the dashboard as separate steps. This made the development process easier to track and provided a clear history of how the model evolved.

Overall, the project showed me how Power BI, GitHub, and Copilot can work together to create a more organized, reviewable, and auditable BI development process.
