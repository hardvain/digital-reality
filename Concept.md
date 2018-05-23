# Definition
* Define objects
  * can be 2D shapes
  * can be 3D shapes
  * can be digital objects
* Each object have some basic set of properties along with specific properties for their size alone
* Each property can vary with respect to time (Only practical properties)

# Basic Properties
* Position as 3D Co-Ordinate values
* Opacity to define the visibility of the material used
* Scale (Can be accomplished by position?)
* Anchor point
* Rotation (Can be accomplished by position?)

# Position
* An object's position can be mentioned using a combination of lattitude, longitude and height (Or should we use 3D Cartesian Cordinates?)
* An object's motion is represented by varying the position with respect to time

# Animation
* Variation of a property with respect to time can be a function of time 
* This function can be unlimited
* But when generating a scene out of it, the starttime and duration of the scene influences the domain of the function

# Opacity
* Each object is added in its own layer and each layer has a priority 
* Toggling an object's opacity reveals layer beneath it

# Scene
* A scene represents something that is live
* Properties of each object can be described as a function of time and this along with a scene determines how the object will look


# Rendering a scene
* A scene can be rendered into a 2D or 3D film
* During rendering the scene, the rendering engine, for each pixel will calculate the color of the pixel based on the arrangement of the layers, and the opacity of the top most layer
* The time in the film can be paused to see what was happening in real time
* In case of a 3D film, when the time is paused, the location of the camera can be changed to get different views
* The camera angle is also encoded as a function of time which will be taken into account during rendering the scene thus enable to chasnge the view of the camera in between the scene
