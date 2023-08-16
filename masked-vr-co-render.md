 # Co-rendering VR using masks
 A way to enable server-side rendering for virtual reality using masks to signal what has been rendered

### Abstract
This is a protocol using flat images sent between the server and the client with markings around the edges signaling what has been rendered.

### The process
The server and client would share all code needed to process logic and control. The server may make an initial mask of the world that it will render, or a specific distance
from the player, it may render. 
* The image mask during live rendering may need to take into account ray tracing as light doesn't move to the user in a singular straight path.
* It would also be helpful if the server can base a new frame on another user's frame by adjusting it to a new angle.
It is important that the server's rendering mask has the ability to adjust itself based on "cost", the server's workload, and amount of users online.

In theory the mask could be done in the border of the image with 2 colors, it could either mark the image where the server hasn't rendered if there are more details needed
could be binary packets
