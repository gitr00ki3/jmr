# Regularization on rapidly varying manifold
A higher order Third derivative(Jerk) baseed regularization technique has been proposed that expolits the information resides on the inflection points of the manifold which vanishes when computed with second order based regularization techniuque.

## The second order based manifold regularization techniques(Laplacian and Hessian) vanishes on the point of inflection. To take into account these data points on manifold, the third order (Jerk) based regularization has been proposed which can acommadate the information laying on these points. 
The following theorm explains the third order comptation on infection   
<img src="0001.png" width=1000></img>

## How to use?
Run **nldr_interactive.m** file to open the interactive window. 

<table border ="1" align ="center">
  <tr>
    <td><img src="results/04_1_NLDRSineCylinder.png" width=250></img></td>
    <td><img src="results/04_2_NLDRSineCylinder_JERK_NN3.png" width=250></img></td>
    <td><img src="results/04_3_NLDRSineCylinder_HESSIAN_NN3.png" width=250></img></td>
	<td><img src="results/04_4_NLDRSineCylinder_LE_NN3.png" width=250></img></td>
    <td><img src="results/04_5_NLDRSineCylinder_LLE_NN3.png" width=250></img></td>
    <td><img src="results/04_6_NLDRSineCylinder_ISOMAP_NN3.png" width=250></img></td>
	<td><img src="results/04_7_NLDRSineCylinder_LTSA_NN3.png" width=250></img></td>
  </tr>
   <tr>
    <td><img src="results/06_1_NLDRSineRot.png" width=250></img></td>
    <td><img src="results/06_2_NLDRSineRot_JERK_NN4.png" width=250></img></td>
    <td><img src="results/06_3_NLDRSineRot_HESSIAN_NN4.png" width=250></img></td>
	<td><img src="results/06_4_NLDRSineRot_LE_NN4.png" width=250></img></td>
    <td><img src="results/06_5_NLDRSineRot_LLE_NN4.png" width=250></img></td>
    <td><img src="results/06_6_NLDRSineRot_ISOMAP_NN4.png" width=250></img></td>
	<td><img src="results/06_7_NLDRSineRot_LTSA_NN4.png" width=250></img></td>
  </tr>
   <tr>
    <td><img src="results/08_1_NLDRSwissRollwHole.png" width=250></img></td>
    <td><img src="results/08_2_NLDRSwissRollwHole_JERK_NN35.png" width=250></img></td>
    <td><img src="results/08_3_NLDRSwissRollwHole_HESSIAN_NN35.png" width=250></img></td>
	<td><img src="results/08_4_NLDRSwissRollwHole_LE_NN35.png" width=250></img></td>
    <td><img src="results/08_5_NLDRSwissRollwHole_LLE_NN35.png" width=250></img></td>
    <td><img src="results/08_6_NLDRSwissRollwHole_ISOMAP_NN35.png" width=250></img></td>
	<td><img src="results/08_7_NLDRSwissRollwHole_LTSA_NN35.png" width=250></img></td>
  </tr>
   <tr>
    <td><img src="results/09_1_NLDRSwissRollwHole2.png" width=250></img></td>
    <td><img src="results/09_2_NLDRSwissRollwHole2_JERK_NN9.png" width=250></img></td>
    <td><img src="results/09_3_NLDRSwissRollwHole2_HESSIAN_NN9.png" width=250></img></td>
	<td><img src="results/09_4_NLDRSwissRollwHole2_LE_NN9.png" width=250></img></td>
    <td><img src="results/09_5_NLDRSwissRollwHole2_LLE_NN9.png" width=250></img></td>
    <td><img src="results/09_6_NLDRSwissRollwHole2_ISOMAP_NN9.png" width=250></img></td>
	<td><img src="results/09_7_NLDRSwissRollwHole2_LTSA_NN9.png" width=250></img></td>
  </tr>
   <tr>
    <td><img src="results/010_1_NLDRToroidalHelix.png" width=250></img></td>
    <td><img src="results/010_2_NLDRToroidalHelix_JERK_NN50.png" width=250></img></td>
    <td><img src="results/010_3_NLDRToroidalHelix_HESSIAN_NN50.png" width=250></img></td>
	<td><img src="results/010_4_NLDRToroidalHelix_LE_NN50.png" width=250></img></td>
    <td><img src="results/010_5_NLDRToroidalHelix_LLE_NN50.png" width=250></img></td>
    <td><img src="results/010_6_NLDRToroidalHelix_ISOMAP_NN50.png" width=250></img></td>
	<td><img src="results/010_7_NLDRToroidalHelix_LTSA_NN50.png" width=250></img></td>
  </tr>
   <tr>
    <td><img src="results/013_1_NLDRTwoSine.png" width=250></img></td>
    <td><img src="results/013_2_NLDRTwoSine_JERK_NN18.png" width=250></img></td>
    <td><img src="results/013_3_NLDRTwoSine_HESSIAN_NN18.png" width=250></img></td>
	<td><img src="results/013_4_NLDRTwoSine_LE_NN18.png" width=250></img></td>
    <td><img src="results/013_5_NLDRTwoSine_LLE_NN18.png" width=250></img></td>
    <td><img src="results/013_6_NLDRTwoSine_ISOMAP_NN18.png" width=250></img></td>
	<td><img src="results/013_7_NLDRTwoSine_LTSA_NN18.png" width=250></img></td>
  </tr>
</table>