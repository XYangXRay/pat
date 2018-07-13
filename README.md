# This an initial project for Photoacoustic Tomography (PAT) reconstruction

The project is the collaboration between FS-Petra of DESY and ASC of HZM

The plan of the working flow is:
1. Translate the SMV toolbox to be python.
2. Translate the forword model of PAT to be tensorflow.
3. Test the PAT data with inverse engine of deep learning.

There is also an ambitious plan:
1. Understand the difference of the geometry between PAT and parallel beam X-ray CT. 
2. Develop a convertor for the data structure from PAT to parallel beam X-ray CT.
3. After the PAT data can be convert to the gerneral sinogram, test all different existing CT algorithms for PAT.
4. Also test the converted PAT sinogram with my inverse engine of deep learning.
5. Keep collecting the all other unique tomography problems and develop the corresponding convertor. After collect most of the tomography data convertor. We can transfer the tomography recontruction problems universally for different measurement facilities.
