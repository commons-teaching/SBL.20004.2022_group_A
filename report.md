# Metabolomics analysis report: Investigation of similitudes and differences between Amaryllidaceae and Lamiaceae families
SBL.20004 

18.05.2022

----
Group A
- Staedler Maxime
- Velti Carola
- Gillon Alisson
----


## Introduction

This project was started in March 2022, and at this point it was asked to think about a project to do during the following weeks. 
The first thing to do was to decide the plants to study, having a precise aim making the choice. Finally, it was decided to investigate 6 smelly plants, devided in two groups composed by 3 plants. The two groups were devided by family of plants, the first group containing Allium ursinum, Allium insubricum and allium fistulosum from the family of Amaryllidaceae and the second one containing Mentha x piperita, Melissa officinalis and Lavandula angustifolia being part of the Lamiaceae family. One of the main aim of the project was to investigate if these two families of plants were correlated one with another, or if the metabolites produced by the plants were more similar among one family than between the two. 
Furthermore, a second aim of the project, was to study which extraction and analysis method was the best for our plants, trying to get a good protocol for future investigations.


## Material & Methods

### Sample collection
 

The samples were collected in the botanical garden of Fribourg, in date 13. 04. 2022. The precise location of the collection of each sample is represented in the following picture, showing the 6 precise places. Furthermore, the links reported under the picture represent the specific links for the iNaturalist page of each collected plant. 


<img width="1439" alt="Schermata 2022-05-18 alle 15 24 47" src="https://user-images.githubusercontent.com/103575088/169052258-60dbe46b-f98d-4073-b950-680b7cf3cf42.png">


Allium Fistulosum: https://www.inaturalist.org/observations/112942553

Allium insubricum: https://www.inaturalist.org/observations/112942497

Allium ursinum: https://www.inaturalist.org/observations/111308148

Mentha x piperita https://www.inaturalist.org/observations/112942446

Melissa officinalis: https://www.inaturalist.org/observations/112942402

Lavandula angustifolia: https://www.inaturalist.org/observations/111309381

Regarding the collection method, some leaves of each plant were cutted with a cutter and immediately immersed in liquid nitrogen, to froze the cells without breaking them and to shut down the metabolitic pathways as soon as possible. The samples were then stored at -80°C until sample preparation. 

For more informations about the 6 samples, see the following table on githib: https://github.com/commons-teaching/SBL.20004.2022_group_A/blob/main/observations-238518.csv


### Sample preparation

The frozen samples were taken out from the freezer and they were crumbled with a cold scissor, to enable better extraction. 
For each plant, it was decided to extract with three different solvents: heptane and dichloromethane for samples for GC-MS analysis and methanol for samples for LC-MS analysis. 
Around 200 mg of crumbled plant tissue were weighed and putted into a glass erlenmeyer flask and immediately covered with 20 mL of the given solvent; this procedure was used for all the samples and all the extraction solvents. 
In the following table the exact weighted masses for each sample are reported:

<img width="298" alt="Schermata 2022-05-18 alle 16 19 14" src="https://user-images.githubusercontent.com/103575088/169063944-849187d6-32a2-49e0-9bc6-83ed9d0f13fa.png">

The erlenmeyer containing the solvents and the plant tissues were covered with an aliuminium foil to avoid excessive evaporation and shaked overnight under the fume hood. 
The extracted samples were then filtered with filter paper and putted into small glass tubes, before being putted at -20°C until sample injection.
The day of injection, the samples were putted in specific LC or GC glass tubes and injected in the machine. 

### LCMS Analysis

- Describe the LC conditions
- Describe the MS conditions

### GCMS Analysis

- Describe the LC conditions
- Describe the MS conditions

### Data treatment

- Describe the software and parameters used.
- GNPS Molecular Networking and Spectral Library Search : https://gnps.ucsd.edu/ProteoSAFe/result.jsp?task=99e8ef38b7fa4642888af4f49aa6b2ab&view=written_description

## Results
GNPS job file link : https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=99e8ef38b7fa4642888af4f49aa6b2ab


### MS1

Regarding GC-MS, 70 features were in the end cleaned, in contrary to the LC-MS where 69 features were found. 
A link to the final feature list (uploaded to github).

#### LC-MS

Looking at the molecular network of our plants, it was possible to select some interesting metabolites which are represented below: 


Eucalyptol is a monoterpene and cyclohexanol derivative that is the major component of EUCALYPTUS OIL. Eucalyptol, or 1,8-Cineole, is a compound produced by many different species of plants, including Lavandula augustifolia. In our case, we found it in Mentha x peperita, but not in Lavandula augustifolia https://pubchem.ncbi.nlm.nih.gov/compound/2758#section=Taxonomy


<img width="465" alt="eucalyptol" src="https://user-images.githubusercontent.com/103575088/169078425-c8e76817-19ce-415e-af5e-70a8df325a07.png">




Gardenin B a tetramethoxyflavone. It is not known to be produced by any of the plants we decided to study. In our case, Mentha x peperita produced it.
https://pubchem.ncbi.nlm.nih.gov/compound/96539#section=Taxonomy

<img width="470" alt="gardeninB" src="https://user-images.githubusercontent.com/103575088/169078454-9ec3eef1-49fb-454e-8f9b-80d7cc589eac.png">




Hesperidin was also detected in the Mentha x peperita. Hesperidin is a flavanone glycoside found in CITRUS fruit peels. A few Mentha species are known to produce it, but it was not reported to be produced in Mentha x peperita. https://pubchem.ncbi.nlm.nih.gov/compound/10621#section=Taxonomy

<img width="479" alt="hesperidin" src="https://user-images.githubusercontent.com/103575088/169078486-1f010162-18e1-433a-a1da-a50ea57c8f54.png">


A spectral match to D-fructose was found only in Allium ursinum. However, it is a bit weird that such a supposedely ubiquitous compound was found only in Allium ursinum and not in the other plants.
![D-fructose_Allium_ursinum](https://user-images.githubusercontent.com/103576860/171428083-f36f1a51-2c2c-4113-9a9f-88841f26344c.png)

Herniarin was found specifically in Lavandula augustifolia.
![Herniarin_Lavandula_augustifolia](https://user-images.githubusercontent.com/103576860/171432685-9183a138-a85e-4466-8634-ddfaf1756a8f.png)

In Melissa officinalis, we could detect (3S)-3-(3,4-dihydroxyphenyl)-6,8-dihydroxy-2,3-dihydrochromen-4-one
![Melissa_officinalis_(3S)-3-(3,4-dihydroxyphenyl)-6,8-dihydroxy-2,3-dihydrochromen-4-one](https://user-images.githubusercontent.com/103576860/171436076-e349cf19-3c3f-4715-a7c8-0b2881dc7a21.png)

Some compounds were only found in Allium insubricum. However, since there is no match in the databases, we are unable to show them here.

The same happened for Allium fistulosum.

Some compounds were only found in the Lamiaceae, such as caffeic acid. It is an hydroxycinnamic acid derivative and polyphenol, with potential anti-oxidant, anti-inflammatory, and antineoplastic activities. This compound is produced by a very wide range of species, including Allium fistulosum. However, we didn't detect it in our samples for Allium fistulosum.
![Caffeic_acid_Lamiaceae](https://user-images.githubusercontent.com/103576860/171444531-e1f8be20-a9ae-47f9-9695-76dcdf76162d.png)


### Molecular Network

Before the representation of the found molecular network, the colour legend is reported: 

![LC_Colors](https://user-images.githubusercontent.com/103575088/169083957-43d7d7c7-f745-44e7-aaa0-8f13541d2b83.png)


1 = Allium ursinum

2 = Lavandula angustifolia

3 = Melissa officinalis

4 = Mentha x peperita

5 = Allium insubricum

6 = Allium fistulosum

7 = blanc (methanol)
















The following pictures represent the molecular network and some clusters of interest of the project




Overall Cytoscape Network for LC conditions :
![LC_Cytoscape_Network](https://user-images.githubusercontent.com/103575088/169084570-eff543ba-5f11-4fcf-aa54-0ff78c3993db.png)




Allium fistulosum network :
![LC_Cytoscape_Network_Allium_fistulosum](https://user-images.githubusercontent.com/103575088/169084454-0cacd600-68a3-4d73-9d78-ac4e27c6d5d8.png)




Allium insubricum network :
![LC_Cytoscape_Network_Allium_insubricum](https://user-images.githubusercontent.com/103575088/169084470-ab34eb35-b354-45e5-9696-9c02a264bf55.png)




Allium ursinum network :
![LC_Cytoscape_Network_Allium_ursinum](https://user-images.githubusercontent.com/103575088/169084483-668fe150-7fcb-4b49-8f75-3955ebfb39bd.png)




Lavandula augustifolia network :
![LC_Cytoscape_Network_Lavandula_augustifolia](https://user-images.githubusercontent.com/103575088/169084499-db8aff8e-22cc-4ef4-a351-2e70cd04b626.png)




Melissa officinalis network :
![LC_Cytoscape_Network_Melissa_officinalis](https://user-images.githubusercontent.com/103575088/169084529-7ad57978-8ad4-4113-9909-3ca81129d08d.png)




Mentha x piperita network :
![LC_Cytoscape_Network_Mentha_x_piperita](https://user-images.githubusercontent.com/103575088/169084548-919b4f67-c60f-4386-84cd-9490334dec30.png)






Link to the GNPS job.
Link to the GNPS identification table.

## Conclusion

Some conclusion that you could get out of this preliminary study.

# References

Note that you can make a footnot like this [^1]

[^1]: Ref X
