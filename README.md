# MonuMAI dataset
<img align="left" width="60%" height="60%" src="/pictures/logo.jpg" title="MonuMAI logo">

[**monumai.ugr.es**](https://monumai.ugr.es/)

It is a monumental heritage image database that is public and rich in expert knowledge. Monumai dataset was annotated by three experts using two types of annotations and is designed according to the defined monumental heritage taxonomy, for architectural styles classification and key elements detection tasks.

<p align="center">
	<img width="90%" height="90%" src="/pictures/taxonomy.JPG">
</p>

The used images for building Monumai were selected so that the monument is centered, fill most of the image, and have high quality so the monument features can be observable. The images were selected from Internet and from smartphone cameras thanks to the Monumai app ([Android](https://play.google.com/store/apps/details?id=es.everywaretech.monumai) and [iOS](https://itunes.apple.com/es/app/monumai/id1397249529?mt=8) developed under a citizen science project.



### Architectural style classification
Monumai database contains 1.514 RGB images of monument facades of four architectural styles Hispanic-Muslim, Gothic, Renaissance, and Baroque. Where the used images for building Monumai were selected so that the monument is centered, fill most of the image, and have high quality so the monument features can be observable.

<p align="center">
	<img width="75%" height="75%" src="/pictures/styles.JPG">
</p>

A summary of the characteristics of MonuMAI dataset is shown below.

| Architectural style 	| #images 	| Style rate(%) |
|---------------------	|---------	|----------	|
| Hispanic-Muslim     	|   327   	|   21.6   	|
| Gothic              	|   359   	|   23.7   	|
| Renaissance         	|   312   	|   20.6   	|
| Baroque             	|   516   	|   34.1   	|
|                     	|   1514  	|          	|


### Key architectural elements detection
Besides the label that indicates the monument style, additional expert knowledge aboutthe existent key elements in each image is provided. The area where each characteristicelement is located in the image is delimited using a bounding box and labeled usingthe  name  of  one  of  the  fifteen  key elements,  horseshoe  arch,  lobed  arch,  flat  arch,pointed arch, ogee arch, trefoil arch, Gothic pinnacle, triangular pediment, segmentalpediment, serliana, porthole, lintelled doorway, rounded arch, broken pediment, andsolomonic column. The architectural element and annotation are illustrated in the figure below.

<p align="center">
	<img width="52%" height="52%" src="/pictures/labelling.JPG">
	<img width="42%" height="42%" src="/pictures/elements.JPG">
</p>

MonuMAI dataset includes 6650 annotated key elements distributed into the fifteen architectural element classes. A statistic analysis of these elements is shown in the Table.

| Architectural element 	| Count 	| Element rate (%) 	| Repetition ratio 	| Architectural style 	|
|-----------------------	|-------	|------------------	|------------------	|---------------------	|
| Horseshoe arch        	|  640  	|       9.62       	|       2.09       	|     Hispanic-Muslim 	|
| Lobed arch            	|  148  	|       2.23       	|       3.44       	|     Hispanic-Muslim 	|
| Flat arch             	|  161  	|       2.42       	|       1.42       	|     Hispanic-Muslim 	|
| Pointed arch          	|  495  	|       7.44       	|       2.03       	|              Gothic 	|
| Ogee arch             	|  238  	|       3.58       	|       1.58       	|              Gothic 	|
| Trefoil arch          	|   57  	|       0.87       	|       1.36       	|              Gothic 	|
| Gothic pinnacle       	|  346  	|        5.2       	|       4.81       	|              Gothic 	|
| Triangular pediment   	|  743  	|       11.17      	|       2.07       	|         Renaissance 	|
| Segmental pediment    	|  258  	|       3.88       	|       1.91       	|         Renaissance 	|
| Serliana              	|   77  	|       1.16       	|       1.13       	|         Renaissance 	|
| Porthole              	|  392  	|       5.89       	|       3.27       	| Renaissance/Baroque 	|
| Lintelled doorway     	|  1150 	|       17.29      	|       2.73       	| Renaissance/Baroque 	|
| Rounded arch          	|  1044 	|       15.7       	|       1.87       	| Renaissance/Baroque 	|
| Broken pediment       	|  604  	|       9.08       	|       1.41       	|             Baroque 	|
| Solomonic column      	|  297  	|       4.47       	|       3.67       	|             Baroque 	|

Detection annotation is provided in Pascal VOC format XML.


### Terms of use
The annotation in this dataset along with the images are licensed under a [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode).