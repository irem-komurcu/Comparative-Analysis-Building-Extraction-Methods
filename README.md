<h1>Image Segmentation</h1>
This repo was created for academic research and test result. Repo will update after academic article online.
<br>
<br>
This repo contains weights of Unet++ model with SE-ResNeXt101 encoder trained with our private Istanbul dataset and Inria and Massachusetts datasets seperately. Trainings have been realized using <b>PyTorch</b> and <a href="https://github.com/qubvel/segmentation_models.pytorch"> segmentation models library</a>. We also provide an inference notebook to run prediction on <b> GeoTiff </b> images. This notebook also outputs prediction images as GeoTiff.

<h3>Weights Files</h3>
You can use the following links to download weights files:
<ul>
<li> Unet++ trained with Istanbul Dataset: <a href="https://drive.google.com/file/d/1ue3w5UqLgd3e0nKfNIl4QmgswzA2wtRt/view?usp=sharing">Download</a> </li>
<li> Unet++ trained with Inria Dataset: <a href="https://drive.google.com/file/d/17SClh43guLZACAVOgnN4huhm7FCA0-OB/view?usp=sharing">Download</a> </li> 
<li> Unet++ trained with Massachusetts Dataset: <a href="https://drive.google.com/file/d/1ZJfTTU92vPgKPUD0CT_93e3_vuohEhSp/view?usp=sharing">Download</a></li>
<li>Unet++ with InceptionResNetv2 encoder: <a href="https://drive.google.com/file/d/1Fnegirgyhh9kuMGzXsBVCWLUavSOvYd7/view">Download</a></li>
<li>Unet++ with EfficientNet-b6 encoder: <a href="https://drive.google.com/file/d/1gPJkQjnVTr-4R8dwi6RdTDFbhB2UtcJJ/view">Download</a></li>
<li>UNet with SE-ResNeXt101 encoder: <a href="https://drive.google.com/file/d/1TUBiFYq_BI4N6iNtMcLuIK0GsGtyAw6f/view">Download</a></li>
<li>UNet with InceptionResNetv2 encoder: <a href="https://drive.google.com/file/d/14p0XaGcnqi45_yL1OgTzNSNsK7Y4Mwr-/view">Download</a></li>
<li>UNet with EfficientNet-b6 encoder: <a href="https://drive.google.com/file/d/1zkHMfWW07qrr_jLSyztrFR0kd-GKGIr7/view">Download</a></li>
<li>DeepLabv3+ with SE-ResNeXt101 encoder:<a href="https://drive.google.com/file/d/1Rh65zOo26Eilkeb_Zf_ZoSFfBEuuIhtx/view">Download</a></li>
</ul>

<h3> Stack and Requirements </h3>
To run the notebook, following libraries are required:
<ul>
  <li>torch == 1.7.1</li>
  <li>segmentation-models-pytorch == 0.1.3</li>
  <li>scikit-image = 0.18.1</li>
  <li>GDAL == 3.2.1</li>
  <li>tifffile == 2021.2.1</li>
</ul>
