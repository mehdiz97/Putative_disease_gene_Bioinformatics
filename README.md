Our study employs a network-based approach to identify potential disease genes and repurposable drugs for ciliopathies, using algorithms like DIAMOnD, DiaBLE, and Diffusion-based methods. This report details our methodology, algorithmic comparisons, and the potential of our findings in the context of drug repurposing for ciliopathies, aiming to contribute to developing effective treatments for these disorders.

**MATERIALS AND METHODS**

PPI and GDA Data Gathering and Interactome Reconstruction:


Source: BioGRID database, DisGeNET database.

Selection Criteria: Human protein interactions, GDAs related to the specified disease.

Data Extraction Method: Utilization of the latest BioGRID release, Employing the most recent DisGeNET release.

Nodes Representation: Each protein in the PPI dataset.

Edges Representation: Interactions between proteins.

Integration of Data: Merging PPI network with GDA data.

Largest Connected Component (LCC) Analysis:

Identification: Focusing on the largest subset of interconnected nodes.

Characterization: Computing node degree, clustering coefficients, and path lengths.

Comparative Analysis of Disease Genes Identification Algorithms:

**Algorithm Implementation:**

DIAMOnD, DiaBLE, and Diffusion-based algorithms.

