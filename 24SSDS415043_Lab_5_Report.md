# LAB 5: D3.JS FORCE-DIRECTED GRAPHS & GITHUB PAGES DEPLOYMENT

**Student:** 24SSDS415043  
**Course:** BSc Data Sciences & Analytics | Semester V

## Problem Statement

Static dashboards and charts provide fixed views of data, whereas interactive visualizations allow users to explore relationships through actions such as hovering and dragging. This lab focuses on developing interactive D3.js visualizations and preparing them for deployment through GitHub Pages. The work includes a force-directed graph, a Sankey diagram, and a treemap representing a data-processing pipeline.

## Steps Done

A D3.js v7 force-directed graph was implemented with seven pipeline stages: Data Cleaning, EDA, Feature Engineering, Model Training, Evaluation, Visualization, and Deployment. Nodes are connected using links, can be dragged, and respond to hover interaction.

A Sankey diagram was developed using the d3-sankey library. It displays data flowing from Web Logs, Mobile App, and CRM Export through Data Cleaning, EDA, Feature Engineering, Model Training, and Evaluation, with Visualization and Deployment output paths. Link widths represent flow values, and nodes have a smooth hover color transition.

A hierarchical treemap was implemented using d3.hierarchy() and d3.treemap(). It displays pipeline volume across Input Sources, Processing, and Output. Leaf nodes are labeled, sized according to their values, and include hover effects. The visualizations are provided as standalone HTML files, including index.html and treemap.html.

The files are committed to the GitHub repository below. GitHub Pages still needs to be enabled from Settings → Pages using the main branch and /(root) folder; therefore the public Pages URL is listed as pending verification.

## Conclusion

The lab demonstrates how D3.js can transform a data pipeline into interactive visualizations. The force-directed graph shows relationships between pipeline stages, the Sankey diagram represents data flow and volume, and the treemap provides a hierarchical view of pipeline data. The work also provides experience exporting visualizations as standalone HTML files and preparing a GitHub Pages deployment.

## Submission Links

- **GitHub Repository:** https://github.com/Pubby-15/D3-Lab-5-24SSDS415034
- **Expected GitHub Pages URL:** https://pubby-15.github.io/D3-Lab-5-24SSDS415034/ *(pending activation and verification)*
