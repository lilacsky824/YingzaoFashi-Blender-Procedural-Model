This project explores how to use Blender's Geometry Nodes to procedurally generate architectural components based on the "Yingzao Fashi" (Treatise on Architectural Methods) from the Song Dynasty. 
Please read my blog post (only available in Traditional Chinese) for the implementation process.

Please note that implementations will require the use of Custom Geometry Nodes. This will necessitate modifications to the Blender source code.
Please refer to the [modified version](https://github.com/lilacsky824/blender-self-use-custom-geometry-node).

# Models and Nodes
The files for each model and node have the same name as their respective titles.

## BasicNode
Some basic calculation nodes, such as units, are converted from the units recorded in the 'Yingzao Fashi' into nodes.
For more details, please refer to the related introduction of ['Yingzao Fashi'](https://zh.wikipedia.org/zh-tw/%E8%90%A5%E9%80%A0%E6%B3%95%E5%BC%8F) on Wikipedia (available only in Traditional Chinese).

## Column (梭柱)
![01](https://github.com/user-attachments/assets/9145d0f8-1d0e-4015-8c34-8db3391fdbc1)
[Blog post](https://lilacsky824.blogspot.com/2024/07/blendergeometry-node.html)

## Custom Nodes
Those nodes are included in a modified version of Blender.

### Entasis Node (卷殺折線)
Automatically generate the n segments entasis polylines in "Yingzao Fashi".
[Blog post](https://lilacsky824.blogspot.com/2024/07/blendergeometry-node_23.html)
<video src="https://github.com/user-attachments/assets/cc5dd8e3-5a49-4aed-bbb0-8c626c0d2e83"></video>
