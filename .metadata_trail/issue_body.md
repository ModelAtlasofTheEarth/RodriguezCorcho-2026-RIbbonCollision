### -> submitter ORCID (or name)

0000-0002-1521-7910

### -> slug

RodriguezCorcho-2026-RIbbonCollision

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

forward model

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1029/2025GC012769

### -> model creators

_No response_

### -> title

Subduction System Response to Ribbon Collision: Implications on the Intra-Plate Force Balance and the Style of Slab Deformation

### -> description

These 3D purely mechanical models of subduction were designed to investigate how ribbon collision perturbs the strain and stress field at the surface, the slab interior, and intraplate force balance. The models examined how the slab responded to ribbons colliding at different orientations. We determined two styles of intra-slab deformation triggered by non-orthogonal and orthogonal ribbon collision.

### -> abstract

Ribbon collision is a process that can rapidly disturb the symmetry of subduction zones. Previous studies have demonstrated how ribbon collision causes rotation at the surface and contortion in the slab, but have only focused on the surface kinematics. We use three-dimensional mechanical models to investigate how ribbon collision perturbs the strain and stress field at the surface, the slab interior, and intraplate force balance. In our numerical simulations, we vary the angle between the trench and the ribbon to explore the slab response to ribbons colliding at different orientations. Our numerical simulations show that ribbon collision causes significant heterogeneity of stress, strain rate and vorticity near the surface and the slab itself. Slab deformation shows compartmentalization into low and high strain rate regions around a high vorticity zone, with strain rate variations of up to an order of magnitude occurring in the along-strike and down-dip directions. In the context of our idealized oceanic-continental subduction system, the simulations show that intra-plate stresses are affected to a similar degree by buoyancy contrasts (i.e., gravitational potential energy variations), slab-pull and ribbon collisions. This partitioning allows for significant heterogeneity in the intra-plate stress regime. This work highlights how the rapid changes in strain rate within the slab, caused by ribbon collision, can explain the seismicity gaps observed in collisional margins, which are often interpreted as slab-tears.

### -> scientific keywords

ribbon collision, stress regime, slab contortion, subduction, force balance

### -> funder

https://www.arc.gov.au/, IH130200012
https://www.arc.gov.au/, LP210100173
https://www.arc.gov.au/, FT190100829 
https://www.arc.gov.au/, DP150102887
Ministerio de Ciencia, Tecnología, e Innovación, 783 (Colombia)
Colombian Association of Petroleum Geologists and Geophysicists (Asociación Colombiana de Geólogos y Geofísicos del Petróleo) fund (2019) 
National Computational Infrastructure (NCI), LE190100021
Nectar Research Cloud (projects q97, mw52, m18)
Auscope
National Collaborative Research Infrastructure Strategy (NCRIS)
Open access publishing facilitated by The University of Sydney, as part of the Wiley - The University of Sydney agreement via the Council of Australasian University Librarians.

### -> model embargo?

_No response_

### -> include model code ?

- [x] yes

### -> model code/inputs DOI

https://doi.org/10.5281/zenodo.14943868

### -> model code/inputs notes

The models are setup using python scripts. The requirements are a docker image with UWGeodynamics (version > 11) . The post-processing workflows need to be updated to reflect the user system directories.

<!-- Failed to upload "3D_Ribbon_Collision-V1.zip" -->

### -> include model output data?

- [x] yes

### -> data creators

0000-0002-1521-7910

### -> model output data DOI

_No response_

### -> model output data notes

The outputs consist of six 3D numerical models. One of the models starts at 0 Myr. This model does not include a colliding ribbon and is the base for the other five models that start at 11 Myr and display differents angles between the trench and the colliding ribbon. These angles of collision are 0, 25, 45, 65 and 85 degrees.

### -> model output data size

Model output data has a estimated size of 800 Gb

### -> software framework DOI/URI

https://doi.org/10.21105/joss.01136

### -> software framework source repository

https://github.com/underworldcode/underworld2

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld2

### -> software framework authors

_No response_

### -> software & algorithm keywords

Python, Finite Element, MPI, Cython

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

<img width="4236" height="4345" alt="Image" src="https://github.com/user-attachments/assets/be70df29-89be-4e04-8e85-d4b04badb1a0" />

Styles of ribbon collision and intra-slab deformation. (a-c) Non-orthogonal collsiion; (d-f) Orthogonal collision; (g-i) Without collision. The different fields show the magnitude of the strain-rate tensor, the stress ratio and the vorticity.

### -> add an animation (if relevant)

https://github.com/user-attachments/assets/20d6e433-bc82-4794-b95a-f468699e4386

Evolution of ribbon collision with an angle of 0 degrees.

### -> add a graphic abstract figure (if relevant)

_No response_

### -> add a model setup figure (if relevant)

<img width="3691" height="5487" alt="Image" src="https://github.com/user-attachments/assets/f280169b-9ad4-4640-8db9-9e2e400030ef" />

a) Model setup of the 3D subduction numerical models. (b-f) Structure of the crustal and lithospheric domains considered in the numerical models. (g-k) Mechanical properties: viscosity, density and plasticity of the continental and subducting plates and colliding ribbon.

### -> add a description of your model setup

The numerical models use a cartesian domain to simulate the oblique collision of a buoyant ribbon in a three-dimensional box that is 6,000 km long, 3,000 km wide and 800 km deep. The ribbon is represented with a rectangle of 3,000 km in length and 210 km in width.

### Please provide any feedback on the model submission process?

There are some issues when uploading heavy files of more than 30 Mb, otherwise its great!