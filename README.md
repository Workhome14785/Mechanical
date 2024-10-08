Comparative Analysis of 1D, 2D, and 3D Cantilever Beam Models Using Ansys Workbench
 
Abstract
This project focuses on the analysis of behavioural studies of 1D, 2D and 3D models of a cantilever beam under uniformly distributed load using Ansys Workbench. In the analysis, total displacement, stress distribution, and natural frequencies are performed in each model. The results show that 1D and 2D models give a reasonable estimate of the displacement which however lacks resolution in terms of the stresses, especially stress concentrations. The 3D model delivers the highest results’ accuracy and can provide a wide-ranging perspective on stress distribution and structural dynamics. This work reveals the need to choose the right model that will enhance the right results and work efficiency in structural analysis.
Keywords: Finite Element Analysis, Mesh, Natural Frequency, Displacement, Stress, Modal Analysis, Cantilever Beam
1. Introduction 
This work examines the task of modelling and analysing a cantilever beam in Ansys workbench to compare the efficiency of 1D, 2D, and 3D modelling approaches. The beam is modelled with a rectangular cross-section and subjected to a uniformly distributed load, and the analyses of deformation, stress variation and natural frequencies are compared between the models. Thus, to determine the models’ precision and solution calculation, the project employs finite element analysis (FEA). Thus, the study draws useful conclusions about the strengths and weaknesses of each dimensional approach to choosing the appropriate model for analysing engineering systems.
2. Model Set-up
2.1 Geometry Model as Question 1
 
Figure 2.1: 1D line geometry with cross-section
In this figure, the 1D line geometry of the cantilever beam with the beam's cross-section is shown below. As mentioned above the cross-sectional area should be 0.4m height by 0.2m width. 
 
Figure 2.2: 2D surface body 
The above figure shows the cantilever beam with all its dimensions simplified as a 2D model. This surface body model makes a certain level of increase to think about the thickness. The cross-sectional shape of the pipe is also rectangular as seen in this figure, and has a width of 0.2m and height of 0.4m. 
 
Figure 2.3: 3D Model Geometry 
In this figure, all the geometries of the complete 3D model of the cantilever beam are illustrated. 

2.2 Cross section and thickness in Question 2
 
Figure 2.4: Cross-section area 
This figure has underlined the cross-sectional area. The figure illustrates perfectly the cross-sectional dimensions which comprises 0.4 meters in height and 0.2 meters in width.
 
Figure 2.5: Thickness of 0.2 m
This is the width of the cantilever beam utilized in the 2D analysis of the figure herein. The thickness of the concrete section as shown as 0.2m is an important factor when analysing stresses and deformation of the beam under loads of various applications.
2.3 Boundary Conditions in Question 3
 
Figure 2.6: Applied boundary conditions 
Fixed support and 1kn/m have been applied to the beam for all cases. 
3. Post-processing result 
3.1 Displacement of the beam as Question 4
 
Figure 3.1 Displacement of the 1D model
The figure above reveals the displacement result for the 1D model of the beam. The maximum displacement is obtained from the second pulse with 5.869e-003m, and the minimum displacement is zero. The average displacement differential of all the nodes in the length of the beam is 2.3516e-003 m meaning that the free end of the cantilever bends slightly.
 
Figure 3.2 Displacement of the 2D model
In the present simplification in 2D, the maximum displacement has been noted to be equal to 5.8639e-003m and the average displacement of 2.3499e-003 m. 
 
Figure 3.3 Displacement of the 3D model

These figures reveal that the 3D model results in a maximum displacement of 5.8583e-003 m at the maximum nodal displacement point. The average displacement is 2.3464e-003 m, slightly lower than 1D and 2D but comparable for this analysis of within 5% of one another.
3.2 Maximum Stress and Equivalent Stress
 
Figure 3.4: Developed Maximum stress of the 1D model
The following figure shows the stress histogram in the 1D model the maximum stress value reaches 9.375e+006 Pa and the minimum one is equal to 2.4899e-004 Pa. Overall, the average stress is 3.1289e+006 Pa and the maximum stresses are located near the fixed support, as for the cantilever beam with uniformly distributed load [1].

 
Figure 3.5: Developed Maximum stress of the 2D model
While performing the 2D model the maximum stress achieved was 1.1161e+007Pa and the minimum stress was 0 Pa. The mean of stress is 8.389e+005 Pa, and the maximum stress is greater than that of the 1D model because of the complication of the engineering surface body.
 
Figure 3.6: Developed Maximum stress of the 3D model
In the 3D model, the maximum stress is equal to 1.8919e+007 Pa, and the minimum stress is equal to -3.4725e+006 Pa. The final average stress of 8.2573e+005 Pa reveals a larger range of the stress values reflecting the increased stress detail in the 3D model results.



 
Figure 3.7: Equivalent stress of the 1D model Equivalent stress in the 1D model is found to be in the range of -9.375 * 10^6 Pa to - 2.4899 * 10^-4 Pa. The average stress is -31289 Pa which is the total average normal and shear stress on the beam length.
 
Figure 3.8: Equivalent stress of the 2D model
In general structures 2D analysis gives the minimum equivalent stress as 50.324 Pa and the maximum stress as 1007600. The average stress is extracted to be 1.6728 x 10^6 Psi with stress concentrations in different repeated units varying due to the cases of distributed loading and geometry [2].
 
Figure 3.9: Equivalent stress of the 3D model
Using the 3D model here a maximum equivalent stress of 1.4364e+007 Pa and a minimum stress of 11.956 Pa has been developed. The mean equivalent stress is 164730 Pa, and with the 3D model, we get a finer stress analysis of the part.
3.3 Modal Analysis
Mode	Frequency [Hz] for 1D model	Frequency [Hz] for 2D model	Frequency [Hz] for 3D model
1	0	0	0
2	5.47E-04	0	0
3	5.51E-04	0	0
4	6.11E-04	0	1.10E-03
5	8.33E-04	5.38E-04	1.31E-03
6	1.82E-03	6.71E-04	2.87E-03
7	10.362	10.362	10.362
8	20.634	20.64	20.636
9	28.486	28.49	28.492
10	55.623
 	55.642
 	55.648
Table 3.1: Model Analysis
 
  

Figure 3. 10: Modal Analysis
A bar plot of the natural frequencies is used to show the first 10 natural frequencies for the 1D cantilever beam, the 2D cantilever beam and the 3D cantilever beam models. Mode 1 to mode 3 of the 2D and 3D models have zero frequency and the 1D model has very low frequencies (on the order of 10^-4 Hz). Starting from mode 4, all the frequency values are no longer zero and the 3D model exhibits slightly higher values than the 1D and 2D models. The frequencies within the 1D model are from 0.000547 for mode 2 and increase progressively while the 2D model overlays the 1D model starting from the seventh mode at 10.36 Hz to the tenth mode at 55.623 Hz. Comparing the three models of higher modes, the results demonstrate that their frequencies are nearly identical with only a small difference and therefore the models presented a representative dynamic characteristic [3]. This plot shows variation with frequencies of different models and increased precision of the 3D work in structural vibration at lower modes.
3.4 Discussion and Comparison (Question 7)
The analysis of deformation and stress results of the cantilever beam in 1D, 2D and 3D models gives a general understanding of the influence of the dimensional modelling on the precision of the results. Regarding deformation, engineers’ predictions in all the models are quite close. The maximum displacement of the first harmonic in the 1D model is equal to 5.869 mm, and in 2D and 3D models to 5.864 and 5.858 mm, respectively. The small difference observed in these results suggests that 1D models can give a good approximation of overall deformation to simple beam problems [4]. Stress analysis results show wider differences between the models. While for the actual geometry adopting the 1D model, the maximum stress evaluates to 9.375 MPa, for the actual 2D and 3D geometries the maximum stress is significantly larger and equal to about 11.161 MPa and 18.919 MPa. The observed rise in stress values when the model complexity is raised will show the inadequacy of 1D models in the stress estimation in beams [5]. In conclusion, the pre-plasticity 1D and 2D models offer reasonable estimates for displacement, but the stress calculation is not a strong aspect in the multiple geometries [6]. 
4. Reflection
In this project, I used a systematic and logical way of solving the problems that were incurred. I first pre-processed the task by studying the given instructions and then disassembling it to obtain workable subtasks. I modelled the cantilever beam in 1D, 2D, and 3D Using Ansys Workbench while making sure that I took the following instructions: Such an approach was beneficial because it enabled me to control every part of the problem, including the geometry setup, boundary conditions and types of analysis. In general, this strategy worked well for me as I was able to produce good levels of deformation and stress which were fairly uniform across all cases and passed through the correct validation checks.
Whenever(there were) mistakes or, shortcomings, for example in the first step, misunderstanding the specific conditions of the problem, or, making minor mistakes in the formulation of the models, I accepted full responsibility. I returned to the areas and taking lessons from it enhanced my knowledge and awareness about Ansys Workbench and Simulation processes. All these learning experiences have enabled me to be more assured when applying finite element analysis in future work.
References
[1] Babu, S.S., Mourad, A.H.I. and Al-Nuaimi, S., 2022, February. Numerical assessment of interlaminar stresses in tapered composite laminates: A comparative analysis with FEM and VAM. In 2022 Advances in Science and Engineering Technology International Conferences (ASET) (pp. 1-6). IEEE. https://ieeexplore.ieee.org/abstract/document/9734914/ 
[2] El Khadiri, I., Zemzami, M., Hmina, N., Lagache, M. and Belhouideg, S., 2021, May. Topology optimization of structures obtained by additive manufacturing: case of 3D beam. In 2021 7th International Conference on Optimization and Applications (ICOA) (pp. 1-4). IEEE. https://ieeexplore.ieee.org/abstract/document/9442628/ 
[3] Shah, A.S., 2024. Elliptic Integral Approach to Large Deflection in Cantilever Beams: Theory and Validation (Doctoral dissertation, Purdue University Graduate School). https://hammer.purdue.edu/articles/thesis/ELLIPTIC_INTEGRAL_APPROACH_TO_LARGE_DEFLECTION_IN_CANTILEVER_BEAMS_THEORY_AND_VALIDATION/26332378 
[4] Kattimani, M.A., Hussain, S.M., Khasge, P., Mohrir, S., Suman, S. and Masum, H., 2024. Utilizing finite element analysis to evaluate the monitoring of sandwich beam conditions. Brazilian Journal of Development, 10(4), pp.e68942-e68942. https://ojs.brazilianjournals.com.br/ojs/index.php/BRJD/article/view/68942 
[5] Im, J., Jang, E. and Song, C., 2024. Analytical Modeling and Implementation of an Imaging Cantilever With a Thermoplastic Stiffener. IEEE/ASME Transactions on Mechatronics. https://ieeexplore.ieee.org/abstract/document/10481511/ 
[6] Baviskar, D., Rao, A.S. and Raut, P., 2024. Design of Flexure Mechanism using FEA and Experimental Method. International Journal of Research Publication and Reviews, 5(1), pp.4957-4963. https://www.researchgate.net/profile/Prasanna-Raut-6/publication/377662641_Design_of_Flexure_Mechanism_using_FEA_and_Experimental_Method/links/65c5beef1e1ec12eff7c416a/Design-of-Flexure-Mechanism-using-FEA-and-Experimental-Method.pdf 
