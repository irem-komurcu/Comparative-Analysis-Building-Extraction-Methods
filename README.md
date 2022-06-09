<h1>Comparative Analysis of Deep Learning Based Building Extraction Methods</h1>

Our article "Comparative analysis of deep learning based building extraction methods with the new VHR Istanbul dataset" has just been published in the journal of Expert Systems with Applications. My first academic paper is online! (Q1, IF: 6.954)
<br><br>
More than 60 experiments were conducted by applying state-of-the-art architectures such as <b/> U-Net, Unet++, DeepLabv3+, FPN and PSPNet with different pre-trained encoders and hyperparameters </b>. Our experiments showed that Unet++ architecture using SE-ResNeXt101 encoder pre-trained with ImageNet provides the best results with <b/>93.8% IoU </b> on the Istanbul dataset.
<br>

![Article Head](https://github.com/irem-komurcu/Comparative-Analysis-Building-Extraction-Methods/blob/main/Sample_Images/image/article-head.png)

This repo contains weights of Unet++ model with SE-ResNeXt101 encoder trained with our private Istanbul dataset and Inria and Massachusetts datasets seperately. Trainings have been realized using <b>PyTorch</b> and <a href="https://github.com/qubvel/segmentation_models.pytorch"> segmentation models library</a>. We also provide an inference notebook to run prediction on <b> GeoTiff </b> images. This notebook also outputs prediction images as GeoTiff. <br><br>

![Sample Images Corresponding Building Labels](https://github.com/irem-komurcu/Comparative-Analysis-Building-Extraction-Methods/blob/main/Sample_Images/image/sample-images-corresponding-building-labels.jpg)

<i/>Sample images and corresponding building labels from the Istanbul Dataset. Only building boundaries (in red) are shown for better visibility.</i>

![Image prediction result with 3 different datasets](https://github.com/irem-komurcu/Comparative-Analysis-Building-Extraction-Methods/blob/main/Sample_Images/image/prediction-result-with-3datasets.jpg)

<i/>Prediction results using network trained with Istanbul (red lines – a, d, g), Inria (blue lines – b, e, h) and Massachhusets (green lines – c, f, i) dataset for sample test images from Istanbul (first row), Inria (middle row) and Massachusetts (last row) dataset.</i>

<h3/>Our Paper:</h3>
Comparative analysis of deep learning-based building extraction methods with the new VHR Istanbul dataset:<br>
<a href="https://authors.elsevier.com/a/1f1XN3PiGTLohZ">This link </a>provides 50 days of free access to the article. Anyone clicking on this link before June 26, 2022, will be taken directly to the final version of your article on ScienceDirect, which they are welcome to read or download.
<br><br>
Also, you can reach my <a href="https://iremkomurcu.medium.com/comparative-analysis-building-extraction-methods-4caf9961936b">Medium article </a>about this repo.

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
