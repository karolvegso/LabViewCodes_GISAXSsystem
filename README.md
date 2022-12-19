# LabViewCodes_GISAXSsystem
I post here the GISAXS system composed mainly from the Thorlabs motors. 

This is old software for controlling GISAXS system written in LabView. The GISAXS system was developed for solid samples and nanoparticle samples on the liquid surface such as air-water interface. The software manipulates mainly Thorlabs motors such as:
--> MTS25/M-Z8 Thorlabs motros.
(linear stage, travel range 25 mm)
--> L490MZ/M (LabJack, linear stage, travel range 50 mm)
--> PRM1/MZ8 (rotation stage)
--> CR1/M-Z7 (rotation stage)
Here, for solid sample manipulation for GISAXS or grazing-incidence, you need one linear stage MTS25/M-Z8 from Thorlabs and one rotational stage PRM1/MZ8 from Thorlabs. The adjustment of zero angle of incidence in GISAXS for solid sample is automated using Thorlabs motors mentioned above and Pilatus 100K detector. For details please see tab Rocking Curve.
The GISAXS system has two pinholes. First pinhole composed from XY Newfocus motors. Second pinhole composed from lateral and vertical MTS25/M-Z8 Thorlabs motors.
The microfocus X-ray source from Incoatec is attached to the vertical and rotational Newport stages, which allow to adjust angle of incidence of X-rays on the liquid surface. 
The activation of necessary motorized stages is done in S/N (Serial Number) tab in the main tab window. 
There are many great scanning algorithms possible in the LabView software, which can be used in the sample adjustment for sample on the solid surface or sample like nanoparticles spread on the liquid surface. 
