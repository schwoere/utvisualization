utvisualization
===============
This is the utvisualization Ubitrack submodule.

Usage
-----
In order to use it, you have to clone the buildenvironment, change to the ubitrack directory and add the utvisualization by executing:

    git submodule add https://github.com/schwoere/utvisualization.git modules/utvisualization

Description
----------
The utvisualization contains a standalone 3D rendering module. Mostly it for quick visualizations and debugging.

Dependencies
----------
In addition, this module has to following submodule dependencies which have to be added for successful building:

<table>
  <tr>
    <th>Dependency</th><th>Dependent Components</th><th>optional Dependency</th>
  </tr>
  <tr>
    <td>utdataflow, utvision</td><td>HighuiWindow, Renderer</td><td>no</td>
  </tr>
</table>
