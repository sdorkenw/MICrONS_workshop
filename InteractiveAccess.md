# Interactive Access

To quickly explore the EM volumes, you can use a small collection of web apps to search and visualize the data.
These apps will help you look at data tables, run simple queries, assess neuronal connectivity, and vizualize the data in Neuroglancer.
A list of all apps can be found [at this like](https://minnie.microns-daf.com/dash/datastack/minnie65_public), or from the [datastack info](https://global.daf-apis.com/info/datastack/minnie65_public) page under "Dash Apps".
These apps were created using the [Dash](https://plotly.com/dash/) framework, hence the name.
Additional documentation can be found [online](https://alleninstitute.github.io/microns_tutorial/em_05_dash_apps.html).

## Table Viewer

The [**Table Viewer**](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/table_viewer/?datastack=%22minnie65_public%22) app allows you to query individual tables in the database, filter them, and look at the results in Neuroglancer.

In the Table Viewer, you first select what materialization version you want.
For the most recent public data, you can choose "Latest".
Next, select one of the tables from a dropdown in the upper left side and click submit.

## Connectivity and Cell Type Viewer

The other tool is the [**Connectivity Viewer**](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/connectivity/?datastack=%22minnie65_public%22), which is designed to let you glance at the synaptic output or input of a given cell and group connectivity by cell type or other annotations.

