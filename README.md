# Magnitude-phase-Mixer

Designing and implementing a piece of software that explains the relative importance of the magnitude and phase components.
This task is applied on a 2D signal (i.e. image) just for clarity but the same concept applies to any signal. 
The software have the following features:
1.	Ability to open and show two images. For each image, the software have two displays (one fixed display for the image, while the second display can show several components based on a combo-box/drop-menu selection of 1) FT Magnitude, 2) FT Phase, 3) FT Real component, 4) FT Imaginary component.
Note: the software should impose that the two images have the same size. i.e. when opening the second image, the sw checks it has the same size of the one previously opened. Otherwise, give an error message.
2.	A mixing panel where an output will be formed based on the mix of two components. Each one of these components are determined from:
a.	which image (via a combo or drop-menu). Available images are image 1, and image 2.
b.	Which component of the image FT (via a combo or drop-menu). Available components are: Magnitude, Phase, Real, Imaginary, uniform magnitude (i.e. all magnitude values are set to 1), uniform phase (i.e. all phase values are set to 0).
c.	the mixing ratio (via a slider ranging from 0 to 100%).
3.	Based on the mixing panel, an output image is generated and displayed for the user. There are two available displays, each for one output. The mixing panel are sending the output to either display-Output 1 or 2. The display is determined using a drop-menu in the mixing panel. And the output image is updated whenever the user makes a change in the mixing options. The output is generated on the fly whenever the user changes a mixing option.
