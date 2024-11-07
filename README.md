java c
MENG30011 Applied Solid Mechanics 
AY 2024/25 coursework assessment 
This assessment is designed to test  your   attainment of  the   Intended   Learning Outcomes for MENG30011 Applied Solid Mechanics. The assessment is a single piece of coursework which carries 
20 credits. This coursework has three parts. In Part A, you will analyse a mechanical component design using FEA and report on its suitability for service. In Part B you will answer questions about finite element theory. In Part  C  you  will answer questions about the failure of materials.  The three   parts  contribute separately to your overall unit mark; the weighting is Part A: 40%, Part B: 20%, Part C: 40%. You should hand in your work via submission point on the unit Blackboard page. There are separate page limits for each part. These must include all figures, references and appendices. If you exceed the page limit for any part, your response for that part will not be accepted. You should put your responses together and submit them as a single .pdf document without a cover sheet. 
This coursework must be done individually. You may discuss the coursework with other students but all work that you hand in, and any underlying analysis, must be entirely your own1 . 
Part A: FEA Investigation and Report 
Introduction 
Liquified Natural Gas (LNG) carriers are tanker vessels that move LNG between major ports (see Figure1). Natural gas is an important source of energy, and its large-scale transport allows the international energy  market  to  operate  efficiently  while  reducing  the  need  for  intercontinental  pipelines.  For transport by LNG carrier, natural gas is liquified by cooling in a special plant. The cold LNG is then pumped  into  large  tanks  onboard  the  carrier  vessel.  As  the  vessel  sails  between  ports,  gradual warming of the stored LNG inevitably causes some of it to boil off. To prevent a build-up of boil-off gas from over-pressurising the tanks, it must be re-liquified or gradually released. Any released boil-off gas is either: a.) diverted to the ship’s engines, or b.) simply burned off so that only combustion products are  released into the environment, rather than the more environmentally-damaging gas itself. LNG carriers use a large Gas Combustion Unit (GCU) to burn boil-off gas that cannot be either consumed by the engines or re-liquified and returned to the tanks. GCU modules are constructed in a factory and then lifted into place during fitting-out of the LNG carrier.You are a stress analyst on the design team of a major supplier for GCUs to the marine LNG transport industry. Your team is a part of a company project which aims to design a new low-cost type of large GCU for bulk LNG carriers and bring it to market. The new design is almost complete, and your team are now finalising the design of its lifting attachments. Other team members have suggested a design for a lifting lug to support the GCU as it is lifted into place on the ship. The lugs are used during lifting operations only: different attachments secure the GCU to the ship. The Team  Leader asks you to perform. stress analysis on the part and produce a written report that the team can use to justify their proposal to the Project Lead.

Figure 1: The Japanese-flagged Energy Innovator is an example of a modern LNG carrier. The GCU is installed in the blue exhaust stack towards the stern.
Design details The lifting lug design is designed to keep the GCU stable as it is lifted, while avoiding a set of hydraulic control lines and instrumentation cables on the side of the unit. The lug designed by the team is shown in  Figure 2. This shape will  be fabricated from S355JR structural steel of a  uniform. thickness and welded to the rigid sidewall of the GCU using two welds. The integrity of the welds will be considered by a separate team and does not need to be included in your analysis. The dimensions a, b and c shown in Figure 2 and the thickness of material used to fabricate the lifting lug are given in Table 2 in the Appendix below.
a.                                                                     b.

Figure 2: Proposed design of the GCU lifting lug. a.) Overall design showing loading and attachments to the GCU body. b.) Dimensions of the lifting lug (in mm). The values of dimensions a and b can be found in Table 2.The lifting arrangement used to install the GCU is shown in Figure 3. The GCU is roughly cylindrical and six lifting lugs of the type shown in Figure 2 are positioned around its circumference so that the load is shared roughly equally between them. The overall mass of the GCU is 36,000 kg. It is essential that the GCU can be  lifted safely during installation, and that the  lifting  lugs will  not  break.  For  lifting equipment of this type, a typical safety factor is:Safe working load/Breaking strength of the component ≈ 5The breaking strength of a component is the maximum load that it will support (e.g. when tested to destruction). The safe working load is the  load  below which a component  is  intended to  be  used normally without fear of it breaking.
Table 1: Ambient-temperature mechanical properties of the structural steel which will be used for the lifting lugs (Steel, EN 10025-2 – S355JR).
Property 
Value 
Young’s modulus 
209 GPa 
Poisson’s ratio 
0.3 
Yield strength 
355 MPa 
Ultimate tensile strength 
630 MPa 
Elongation at failure 
22% 
Density 
8010 kg m-3 
Figure 3: Vertical lifting arrangement to be used for installing the GCU. Six lugs are spaced equally around the circumference of the object. It can be assumed that all cables, shackles and harnesses used in the lifting operation will be appropriate for the loads involved.
Report 
You must produce a report on your analysis. This report will be delivered to the Project Lead, who will make the final decision on whether to go ahead with this design. In your report, you should:
.     Briefly outline the problem that you are aiming to solve.
.     Explain and justify any analysis methods and simulation setup that you have used.
.     Use appropriate methods to demonstrate that your stress analysis results are valid and accurate.
.     Clearly present and interpret the results of your stress analysis.
.     Give a clear and well-justified recommendation on whether the lifting lug design is adequate or whether there is a potential safety hazard.
Additionally, the Team Leader has asked you to include two specific pieces of information in the report and highlight them in yellow :
.    The maximum vertical deflection of the end of the lifting lug (i.e. the furthest point from the GCU wall) that would be expected during the lifting operation.
.    The maximum value of von Mises’ stress anywhere on the lug, excluding the contact region 
between the lug and lifting shackle, that would be expected during the lifting operation.You may use any format or structure for the report – there is no set template. However, it must not exceed 4 sides of A4 and you must use Arial 11-point font or larger. Any figures, tables, equations, references and appendices must be included within this limit. You can assume that the Project Lead has a good knowledge of stress analysis, FEA and mechanics of materials.You must decide what sort of FEA to perform. and what software you use. You could use Abaqus, Python, MATLAB, any of the FEA packages suggested in the formative coursework information, or any other software that you want.  However,  in  the  report you  must  carefully  explain  and justify  any analysis that you have performed.
Part A report marking
Your Part A report will be marked on three criteria:
.    Accuracy (30%) – The numerical accuracy of the results presented.
.     Credibility (50%) – The overall persuasiveness of your report and its conclusions. This includes the quality of the analysis and how well-justified it is, the credibility of any arguments that you make, and how well these arguments are explained in relation to the boarder context of the work (e.g. any existing literature).
.     Presentation (20%) - The quality of presentation seen in the written report, including figures
etc. Sensible formatting and margin sizes should be used.Each report will be marked individually. Marking will follow the University’s standard 21-point scale. Marks for each of the criteria with be weighted and then summed together. This total mark will be converted to an overall percentage for Part A.


Part B: Theory of FEA 
Introduction Part B of this coursework comprises a single theory task. You should answer it using代 写MENG30011 Applied Solid Mechanics 2024/25Python
代做程序编程语言 no more than 3 sides of A4 with Arial 11-point font or larger. You may use equations and/or figures if you want to; they are included in the page limit. You may use any layout you like for your response to Part B so long as it is clear; there is no fixed template.
Task 
Download the PartB.pyc file. Run it through Anaconda as explained in the instructional video using: >> pip install meshpy
>> python PartB.pyc my_student_codereplacing  my_student_code with your  own 7-digit student  code. This will generate and save two figures in the working directory. The file Mesh.png shows a 2D domain which has been discretized using a mesh made up of constant strain triangle elements. The file OneElement.png represents a piece of isotropic linear elastic material modelled with a single triangle element, which is extractedfrom Mesh.png. The Young’s modulus is 200 GPa and Poisson’s ratio is 0.28. The script. will print if this single element is considered in plane stress or plane strain conditions. It will also print node indices in OneElement.png and the forces f1x  and f1y that are necessary to solve question 3.
Now answer the following questions in your Part B report:
1.    How many: a.) elements, b.) nodes and c.) degrees-of-freedom does the mesh in Mesh.png
have?
2.    What is the stiffness matrix of the element shown in OneElement.png? You do not need to
show a full derivation of formulae for the stiffness matrix, but you should show the most important steps of your procedure.
3.    Consider the element in OneElement.png alone. Imagine the situation where:
.     Nodes 2 and Node 3 are restrained against movement in both the x and y directions. Node 1 remains unrestrained.
.     Forces f1x and f1y are applied at Node 1 in the x and y directions. The values of these
forces per unit thickness of material are given by the pyc script.
What is the magnitude of the reaction force at Node 2? Show your working.
4.    Consider the domain shown in Mesh.png again. If you knew:
.    The distribution of mass in the domain.
.     Its boundary conditions.
.    That any material damping was negligible.
Describe how you could find its natural frequencies of vibration. You do not need to determine these frequencies.


Part B marking 
Your response to Part B will be marked based on:
.    The accuracy of your answers (primary criterion, 40%).
.    Your use and explanation of methods (secondary criterion, 40%).  Is an appropriate  method
being used/proposed? Is any working clear and straightforwardly explained?
.     Presentation (secondary criterion, 20%). Your response must be clear and legible.
Your responses will be marked individually. Marking will follow the University’s standard 21-point scale. The mark will be converted to a percentage for Part B.
Part C: Failure of Materials 
Introduction You are asked to complete two research investigations, related to the structural integrity of service systems on board the LNG carrier. To complete these tasks, you may need to perform. some numerical calculations. You can use any software (for example, you can write a program in Python or MATLAB). You do not need to show your code. However, you need to clearly describe all formulas and methods you are using.   During your analysis you can use any  reasonable approximations. It is important to clearly describe and justify them. You may use any layout you like for your response to Part C so long as it is clear; there is no fixed template. There is no page limit for Part C.
Part C questions 
Question 1 One  of  the  load-bearing  structural  components  represents  a  large  plate  with  rectangular  cross- section. The material is aluminium and has a yield stress of 400 MPa, an elastic modulus of 70 GPa, a Poisson’s ratio of 0.3 and a fracture toughness of 20 MPa √m  . The  plate  is  loaded  by  (unknown) normal stresses σx and σy as shown in Figure 4. In order to measure these stresses a test is performed. The stresses are calculated from strains, which are measured by strain gauges bonded to the plate. It is assumed that these stresses are not sufficient to cause yielding.
Q1a. What is the smallest number of strain measurements required to determine σx  and σy? Q1b. Calculate applied stresses σx  and σy from strain measurements.
1)   Define the orientations of the necessary strain gauges.
2)    The relevant strain values can be obtained using the pyc file provided as explained below.In order to ensure the structural integrity of the component during the service an additional normal stress σp  must be taken into account. It is assumed the magnitude of this stress  |σp| ≤ 400 MPa and its direction is defined by the angle θp  = 300  as shown in Fig.4. It is also assumed that a central crack of an arbitrary orientation can be developed due to environmental and loading conditions (see Fig. 4). The crack can be identified by ultrasonic non-destructive testing, however, the minimum detection size is 5 mm.
Q1c. Provide analysis of the possible component’s failure mechanisms as a function of stress σp  and crack orientation.
You can consider the following points:
1)   Analyse safety factors, corresponding to different failure mechanisms.
2)    Define the range of stress σp, which is safe for the structural integrity of the component.
3)    Find the most dangerous orientation of the crack.
4)   The results can be presented using diagrams, graphs, or tables.
5)   Try to give a physical explanation of obtained results where it is possible.
In order to calculate strain gauge measurements for Q1b download and run the PartC_Q1 .pyc file. Run it through Anaconda as explained in the instructional video using:
>> python PartC_Q1.pyc my_student_code theta
and replacing my_student_code with your own 7-digit student code. The variable theta is a floating point number representing the strain gauge orientation angle θ in degrees (see Fig.4).

Figure 4: Stressed plate containing an inclined crack with a strain gauge attached.
Question 2 The LNG carrier has a complicated pipework which is required to support its service systems. It is very important to maintain structural integrity of the pipework, therefore, routine inspections must be performed in certain time intervals. One section of the pipework represents a steel pipe with closed ends, an outer diameter of D = 200 mm and a wall thickness of t = 10 mm. The pipe works in cycling loading with  internal  pressure  varying from  zero to p = 40 MPa  and  back.  Additionally, there  is  a possibility of a valve fault which can cause a sudden short-term increase of the maximum working pressure by a factor of 2. It is assumed that during the service a semi-circular crack can occur in a pipe weld  as  shown  in  Figure  5.  The  pipe  is  regularly  inspected,  and  the  crack  can  be  detected  with probability of detection described by the function ppod(a), where a is the crack radius (the function ppod(a) corresponds to the probability that all cracks with the radius greater than a are detected). Inspections can be assumed to be independent (probability of finding a crack during one inspection doesn't depend on the previous inspections).
The steel has a fracture toughness of KIC = 90 MPa √m. The fatigue crack growth is described by Paris’
law with constants C = 10-12  and m = 4. The geometry correction factor for the semi-circular
crack of radius a is given by:

The probability of crack detection function ppod (a) is given by:
ppod(a) = 1 − e-(a/a0)4 ,
where the parameter ao  is given in Table 3 in the Appendix below.
Q2a. How does the pipe’s probability of failure depend on the interval between pipe inspections? Q2b. Find the inspection interval, corresponding to the probability of failure equal to 0.01.
Tips:
1)   Determine the failure mechanism first.
2)    The inspection interval can be measured in terms of the number of cycles.
3)   Include quantitative results in Q2a (for example, by plotting the probability of failure as a function of inspection interval).

Figure 5: Service pipework containing a crack in the radial-circumferential plane.
Part C marking 
Your responses to Part C will be marked based on:
.    The correctness of your answers (40%).
.    The understanding of the methods involved (40%).
.     Presentation. Your explanations must be clear and legible (20%) .
Your responses will be marked individually. Marking will follow the  University’s standard 21-point scale. The mark will be converted to a percentage for Part C.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
