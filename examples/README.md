## Examples
### Running the examples locally
Running the examples locally requires a websocket connection.  


### Contents of the folder

#### Basic Example
Showcases the capabilities of inbuilt classes in Amphion to get started with minimal effort.  
In this example, we initialize a ROS instance and `Amphion.TfViewer`. Then add visualizations for path, marker and a robot model in less than 20 lines of code
![](../assets/examples/basic.gif)

#### 3D Viewer
An example of `Amphion.Viewer3d` which works similar to `Amphion.TfViewer` but does not subscribe to `/tf` and `/tf_static`.  
Visualizations added are placed at the origin
![](../assets/examples/3d_viewer.gif)

#### 2D Viewer
An example of `Amphion.Viewer2d` which has a top down camera with controls to zoom, pan and rotate in the 2d context
![](../assets/examples/2d_viewer.gif)

#### Custom View
An example of `Amphion.Scene` used with a custom renderer and controls
![](../assets/examples/custom_view.gif)

#### Custom Scene
An example of visualizations added to `THREE.Scene` with custom controls
![](../assets/examples/custom_scene.gif)

#### Multiple views
An example of the same `Amphion.Scene` used with `Amphion.Viewer2d` and `Amphion.Viewer3d` rendered independently on two different containers
![](../assets/examples/custom_view.gif)