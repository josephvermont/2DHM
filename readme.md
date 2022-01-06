# <p align="center"> Phase Retrieval methods by the Transport of Intensity Equation and Digital Off-axis Holography   </p>

*Joseph Vermont B. Bandoy*

# Introduction
Quantitative Phase Imaging allows observation of cells which could lead to better imaging and help provide better understanding of diseases. The aim of the research is to perform different holographic methods including mach-zender interferometer, in-line and off-axis interferometer, flipping holography and common path off-axis holography with gratings. From there, two or three holographic microsopes are combined to have the capability of simulaneous imaging and analysis. Usually, digital holography uses interferometric methods for phase retrieval but recent studies are looking for quantitative phase retrieval method called the transport of intensity, which requires non-interferometric methods.

# Concepts: Phase Retrieval by Off-axis Holography using Gratings and the Transport of Intesity Equation
![KakaoTalk_Snapshot_20220105_134335](https://user-images.githubusercontent.com/80727364/148162018-28ac8ea0-8336-4773-8b0b-41d656fe4dff.png)
<p align="center"> Figure 1. Holographic Method (above). Transport of Intensity (below) </p>

Phase retrieval can be done in two ways. The first is holographic method . In this experiment. The beam is diffracted by the gratings causing it to have orders spread. In this case, the first and the DC term is used (see Figure 1) as it is focused by the lens. A pinhole must be used in one of the beam to erase the information of the object leading to that path being the reference beam. With the use of the 2nd lens, it is collimated and combined with the camera. The hologram is captured by the camera. Digital Holographic Method is done to perform reconstruction.

![KakaoTalk_Snapshot_20220105_143705](https://user-images.githubusercontent.com/80727364/148166003-c9eebc04-4bd1-44f5-bcf9-e4f264a52ccd.png)
<p align="center"> Figure 2. Transport of Intensity Equation </p>

Phase retrieval is by the transport of intensity Equation is done by only using the reference beam. However, a translation must be done in the z-axis and capture three images. Namely, undefocused, focused and overfocused, which must be exactly a z distance apart from the focused image. The transport of intensity relates the intesity of the images with the phase. using the equation below, 
<p align="center"> 𝜑(𝑥,𝑦,𝑣)=𝐼𝐹𝑇{1/(𝑘_𝑥^2+𝑘_𝑦^2 ) [(𝐹𝑇[𝐼(𝑥,𝑦,𝑧)]−𝐹𝑇[𝐼(𝑥,𝑦,−𝑧)])/𝐼(𝑥,𝑦,𝑣) ]} </p>

# <p align="center"> Off-axis Holographic Methods </p>

# I: Combined Common path off-axis and FDIA
![KakaoTalk_Snapshot_20220103_202528](https://user-images.githubusercontent.com/80727364/147925383-df7e9fbf-b79a-4df4-bc9d-d9b7592d38fb.png)
<p align="center">  Figure 3. Experiment setup. The set-up involves two microscopes with two cameras. The first beam leads to the FDIA (Flipping with Double the Imaging Area) while the other beam leads ot the common path off-axis holography </p>

A He-Ne laser, operating at 10mW with wavelength of 632nm was used as a light source. It enters a polizer, a mirror, an analyzer and then reflected by the second mirror for proper laser alignment. A spatial filter is used to produce a clean gaussian beam. As the light was collimated, the sample was illuminated followed by the objective lens and the tube lens with 200mm focal length. From this point, an image can be imaged as a conventional microscope. A set of mirrors was used to reflect the beams that leads both the flipping holographic module can be replaced with the triangular hologram or an off-axis tau hologram. The 4f system used in this module has 75mm for each lens. For the tau hologram, a pinhole is used with the mirror to erase the information of the object so it serves as a reference beam. The other beam goes through a relay lens for the diffractive hologram (off-axis hologram) with gratings. As light enters the gratings, it splits the beam into different order. In this case, the first order enters the pinhole and the other is blocked, the second lens combine them for the interfererence.

# I.A: Combined Common path off-axis and FDIA
![image](https://user-images.githubusercontent.com/80727364/147925573-e977ee2c-29d8-4981-87b0-27475b7059ca.png)
<p align="center">  Figure 4. Preliminary results of common path off-axis holography. These are the images taken from Camera 1. The left image is the object beam and the image on the right is the object beam. </p>

# I.B: Off-axis Holography: Flipping Holography with Double the Imaging Area
![image](https://user-images.githubusercontent.com/80727364/147925554-3bf3f7f1-533f-43c0-ae5f-edb34e6dcaa5.png)
<p align="center">  Figure 5.  The images are taken from camera 1. Holograms from two mirrors and the retroreflective mirrors. The second image (right) is a hologram without the retroreflective mirror. </p>

# *Discussion*

Simultaneous imaging and analysis can be done from the set-up. The holograms are achieved for both set-up. Intensity is an issue for both microscopes as the retroreflective mirror needs a neutral density filter to have comparable intensities to have better intereference. Regarding the Common path, it can be seen that the object beam was not erased based from the improvised pinhole. Reconstruction can be done when the reference beam is erased. Multiplexing may be done in the future when current issues are addressed. From there, phase imaging methods may be done to maximize its use.
The resolution target used is NBS 1963A 1x R2L2S1P1. The resolution of the microscope has 25 cycles/mm or 25 line pairs per mm or 0.04 mm cycle size.

# Direction/Re-direction
Tunable lens - Instead of moving the lens, we can use the ETL to adjust the focus electrical
Inverted microscope must be implemented and to establish the focus versus current (mA).
Shearing Interferometry - doesn't need a pinhole to obtain the hologram. To investigate how reconstruction is done. 
![LAM2021030005-4](https://user-images.githubusercontent.com/80727364/148332882-1d3c391a-1845-4e2b-8858-95b50610c4fc.jpg)


# II. Mach-Zender Based Holography
In Physics, the Mach-Zender interferometer is a device used to determine the relative phase shift variations between two collimated beams derived by splitting light from a single source. The interferometer has been used among other things, to measure phase shifts between the two beams caused by a sample or a change in length of one of the paths. The apparatus is named after physicists Ludwig Mach and Ludwig Zehnder. Demonstration of Mach-Zender interferometry with particles other than photons (particles of light) had been demonstrated as well in multiple experiments.

![KakaoTalk_Snapshot_20220105_132025](https://user-images.githubusercontent.com/80727364/148161240-3521455f-609d-43f8-8773-8532ba931dc9.png)
<p align="center">  Figure 5.  Mach-Zender based holography set-up. </p>

In the experiment, the set of lenses were used to magnify the beam 20x a prerequisite to achieve a good collimation which is important in mach zender interferometry. The beam that goes to the mirror M1 and M2 then a 4f system to collimate the beam. Another 4-f system after the object beam is used for imaging. M1 and M2 will be replaced with SLM and the Galvanometer in the future experiment

# III: Compact and portable off-axis interferometer for Quantitative Phase Microscopy*
![KakaoTalk_Snapshot_20220103_201414](https://user-images.githubusercontent.com/80727364/147924614-c747f9eb-50a8-4b2b-8863-e5b2c4f1aaf6.png)
<p align="center">  Figure 6.  Inline and off-axis interferometer. </p>

The tau interferometer has a pinhole right after the M4 to to serve as a reference beam. The M3 beam reflects the object beam. After which, they are to be interfered with each other with the camera. In line holography was demonstrated but reconstruction was not done. For the off-axis holograhy, the pinhole used with the mirror was not successful as it did not serve as a reference beam as thought. Other papers demonstrated a method for this. 
![KakaoTalk_Snapshot_20220103_201632](https://user-images.githubusercontent.com/80727364/147924679-2d07dcd3-1e05-496a-8180-db9b9921359e.png)


# *Discussion*
Part II and Part III set-up were done before part one. Phase retrieval has to be done using the transport of intensity and the FDIA module.
Further reconstruction must be done as the set up needs to be realigned and retake images. Study which samples will be investigated
