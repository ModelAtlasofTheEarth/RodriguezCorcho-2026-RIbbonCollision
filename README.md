# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Andres Felipe Rodriguez Corcho ([0000-0002-1521-7910](https://orcid.org/0000-0002-1521-7910))

**Model Creator(s):**  

- Andres Rodriguez‐Corcho ([0000-0002-1521-7910](https://orcid.org/0000-0002-1521-7910))  
- Sara Polanco   
- Daniel Sandiford ([0000-0002-2207-6837](https://orcid.org/0000-0002-2207-6837))  
- Rebecca Farrington   
- Louis Moresi   
  
**Model slug:**  

`RodriguezCorcho-2026-RIbbonCollision` 

(this will be the name of the model repository when created) 

**Model name:**  

_Subduction System Response to Ribbon Collision: Implications on the Intra-Plate Force Balance and the Style of Slab Deformation_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

- forward model   
  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[Subduction System Response to Ribbon Collision: Implications on the Intra‐Plate Force Balance and the Style of Slab Deformation](https://doi.org/10.1029/2025gc012769)_ 

**Short description:**  

These 3D purely mechanical models of subduction were designed to investigate how ribbon collision perturbs the strain and stress field at the surface, the slab interior, and intraplate force balance. The models examined how the slab responded to ribbons colliding at different orientations. We determined two styles of intra-slab deformation triggered by non-orthogonal and orthogonal ribbon collision.

**Abstract:**  

Ribbon collision is a process that can rapidly disturb the symmetry of subduction zones. Previous studies have demonstrated how ribbon collision causes rotation at the surface and contortion in the slab, but have only focused on the surface kinematics. We use three-dimensional mechanical models to investigate how ribbon collision perturbs the strain and stress field at the surface, the slab interior, and intraplate force balance. In our numerical simulations, we vary the angle between the trench and the ribbon to explore the slab response to ribbons colliding at different orientations. Our numerical simulations show that ribbon collision causes significant heterogeneity of stress, strain rate and vorticity near the surface and the slab itself. Slab deformation shows compartmentalization into low and high strain rate regions around a high vorticity zone, with strain rate variations of up to an order of magnitude occurring in the along-strike and down-dip directions. In the context of our idealized oceanic-continental subduction system, the simulations show that intra-plate stresses are affected to a similar degree by buoyancy contrasts (i.e., gravitational potential energy variations), slab-pull and ribbon collisions. This partitioning allows for significant heterogeneity in the intra-plate stress regime. This work highlights how the rapid changes in strain rate within the slab, caused by ribbon collision, can explain the seismicity gaps observed in collisional margins, which are often interpreted as slab-tears.

**Scientific Keywords:**  

- ribbon collision   
- stress regime   
- slab contortion   
- subduction   
- force balance   
  
**Funder(s):**  
-  (https://www.arc.gov.au/)  
- Ministerio de Ciencia   
- Colombian Association of Petroleum Geologists and Geophysicists (Asociación Colombiana de Geólogos y Geofísicos del Petróleo) fund (2019)   
- National Computational Infrastructure (NCI)   
- Nectar Research Cloud (projects q97   
- Auscope   
- National Collaborative Research Infrastructure Strategy (NCRIS)   
- Open access publishing facilitated by The University of Sydney   
  
## Section 2: your model code, output data  

**No embargo on model contents requested** 

**Include model code:**   

True 

**Model code existing URL/DOI:**   

https://doi.org/10.5281/zenodo.14943868 

**Model code notes:**   

The models are setup using python scripts. The requirements are a docker image with UWGeodynamics (version > 11) . The post-processing workflows need to be updated to reflect the user system directories.

<!-- Failed to upload "3D_Ribbon_Collision-V1.zip" --> 

**Include model output data:**   

True 

**Model output data notes:**   

The outputs consist of six 3D numerical models. One of the models starts at 0 Myr. This model does not include a colliding ribbon and is the base for the other five models that start at 11 Myr and display differents angles between the trench and the colliding ribbon. These angles of collision are 0, 25, 45, 65 and 85 degrees. 

## Section 3: software framework and compute details   
**Software Framework DOI/URL:**  

Found software: _[Underworld2](https://doi.org/10.21105/joss.01136)_ 

**Software Repository:**   

https://github.com/underworldcode/underworld2 

**Name of primary software framework:**  

Underworld2 

**Software & algorithm keywords:**  

- Python   
- Finite Element   
- MPI   
- Cython   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [graphics/Image.png](https://github.com/user-attachments/assets/be70df29-89be-4e04-8e85-d4b04badb1a0)  
Caption:  Styles of ribbon collision and intra-slab deformation. (a-c) Non-orthogonal collsiion; (d-f) Orthogonal collision; (g-i) Without collision. The different fields show the magnitude of the strain-rate tensor, the stress ratio and the vorticity.  
  
**Animation:**  

Filename: [graphics/animation](https://github.com/user-attachments/assets/20d6e433-bc82-4794-b95a-f468699e4386)  
Caption:  Evolution of ribbon collision with an angle of 0 degrees.  
  
**Graphic abstract:**  

Filename: [None]()  
  
**Model setup figure:**  

Filename: [graphics/Image.png](https://github.com/user-attachments/assets/f280169b-9ad4-4640-8db9-9e2e400030ef)  
Caption:  a) Model setup of the 3D subduction numerical models. (b-f) Structure of the crustal and lithospheric domains considered in the numerical models. (g-k) Mechanical properties: viscosity, density and plasticity of the continental and subducting plates and colliding ribbon.  
Description:  The numerical models use a cartesian domain to simulate the oblique collision of a buoyant ribbon in a three-dimensional box that is 6,000 km long, 3,000 km wide and 800 km deep. The ribbon is represented with a rectangle of 3,000 km in length and 210 km in width.

  
