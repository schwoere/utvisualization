utvisualization
===============
This is the utvisualization Ubitrack submodule.

Description
----------
The utvisualization contains a standalone 3D rendering module. Mostly it for quick visualizations and debugging.

Usage
-----
In order to use it, you have to clone the buildenvironment, change to the ubitrack directory and add the utvisualization by executing:

    git submodule add https://github.com/Ubitrack/utvisualization.git modules/utvisualization


Dependencies
----------
In addition, this module has to following submodule dependencies which have to be added for successful building:

<table>
  <tr>
    <th>Component</th><th>Dependency</th>
  </tr>
  <tr>
    <td>all</td><td>utDataflow, utVision</td>
  </tr>
</table>
