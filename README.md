# Draw an arbitrary photonic device
Playground for drawing weird shapes, workspace for NYUAD students working in the development of an inverse designed AWG. We will generate an extruded strcture from this polygon to be our planar integarted photonic system.

### Notes to students:
I dropped a few lines of code that can help you draw an arbitrary polygon using a few parameters. Here I used sinusoidal functions but you can use whatever you can imagine. Try playing with this and think about how you can change it to generate any other possible shape, either a more complex one, or a completely different type of shape. Remember that what you are to design is a system capable of separating various colors (wavelengths) of light. This is often done using an arrayed waveguide grating (AWG), so look for existing shapes of AWGs and see if you can up with a form of equation that could describe the shape of the said existing device. Use as many parameters as you can imagine may be necessary. In the future, we will use that function to run our optimization process.

Also remember that in your application, the system will have optical inputs and outputs that are not part of the optimizable device, so those should somehow constrain your shape. Can you add inouts and outputs to the polygon in the code and show me how that would look?


