# Setting Up a Graph for Generative Design

## Inputs

To set up a Dynamo graph for use with generative design tools, right-click on each node used to drive the graph and ensure that the _`Is Input`_ option is checked. Renaming the node with a standard approach such as _`IN_description`_ will help to distinguish these inputs in the Create Study dialog.

1. Right-click on each node used to drive the graph and ensure that the 'Is Input' option is checked.
2. Rename the node as explained above. 
3. For slider nodes set values for Min, Max, and Step values. 

_Note: Currently all inputs must be 'Number' or 'Integer' slider, 'Boolean', or 'Revit Selection' nodes._

<img src="../assets/hello/setting1.png" style="width:200px;"/>

## Outputs

To define outputs for use with the generative design tools, right-click on the watch nodes and select the _`Is Output`_ option. Renaming the node with a standard approach such as _`OUT_description`_ will help to distinguish these outputs in Generative Design.

1. Right-click on the watch nodes and select the 'Is Output' option. 
2. Rename the node as explained above. 

_Note: Currently all outputs must be watch nodes with a 'Number' data type._

<img src="../assets/hello/setting2.png" style="width:200px;"/>

## Export to Generative Design

Once both inputs and outputs are set up correctly and your graph is saved,  it can be exported for use with the generative design toolset.  In Dynamo, navigate to the toolbar and select _`Generative Design> Export for Generative Design`_

Dynamo will then create a copy of your graph which will be available to launch in with Create Study. 

To create an export to use with Generative Design, please do the following:

1. In Dynamo, navigate to the toolbar and select Generative Design &gt; Export for Generative Design. Generative Design will then create a copy of your graph which will be available to launch.

<img src="../assets/hello/setting23.png" style="width:200px;"/>

_Note: Graphs with the same name will be overwritten._

<img src="../assets/hello/setting22.png" style="width:200px;"/>

## Launch Generative Design

To launch Generative Design, please do the following:

1. In Dynamo, navigate to the toolbar and select Generative Design &gt; Create Study.

<img src="../assets/hello/setting21.png" style="width:200px;"/>

Once the Create Study dialog has launched, select a study type that you have exported from Dynamo.

<img src="../assets/hello/setting3.png" style="width:200px;"/>

