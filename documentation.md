<h1>[WIP]3D Scanning Apps for iPhone/iPad users</h1>


<h3>Summary</h3>
This project aims to identify and catalog appropriate 3D scanning apps for students and give suggestions of 3D scanning apps under specific circumstance. One object have been scanned using 5 different 3D scanning apps and the results are documented in Sketchfab. 

<h3>Testing device and scanning object</h3>
![001|690x348](upload://jMyv7dJ4Ld8sSuytd0Brjb3zW3L.jpeg) 

I used [Iphone7](https://support.apple.com/kb/SP743?viewlocale=en_US&locale=en_US) and [Ipad Pro 12.9-inch(3rd generation)](https://support.apple.com/kb/SP785?viewlocale=en_US&locale=en_US) as a 3D scanning device, and used 100mm height froggy bank as a object to run 3D scan.

<h3>Candidates, 3D scanning apps/programs with good reputation</h3>

Starting the research, I listed up test candidate apps by searching frequently recommended 3d scanning apps.I found two recently written articles, and referenced a list of photogrammatory apps/software posted in this discourse before. 
+ [The 8 best 3D scanning apps for smartphones in 2020 (free!)](https://www.aniwaa.com/buyers-guide/3d-scanners/best-3d-scanning-apps-smartphones/)
+ [2020 Best 3D Scanner Apps for Android & iPhone](https://all3dp.com/2/5-best-3d-scanner-apps-for-your-smartphone/)<br>

From those references, I got 13 possible testing 3D apps available in the market.  

<h3> 3D scanning apps hardware restrictions and key features</h3>

Many of apps require additional device, or specific camera spec. For example, Canvas requires extra $499 Structure sensor, Qlone needs printed AR Mat, and Heges needs camera with FaceID function. More detailed restrictions and app features are listed below. 


I checked the apps whether they works in iPhone7 and iPad Pro by downloading and operating it. Some apps only exist in Andriod apps stores, and some other scanning apps requires additional divice like Structure sensor. Meshroom and ReCap are software runs in PC not smartphones or tablets. Lastely, Display.land announced discontiue of the service from August, so it was not available in the ios store anymore. 

After removing the apps that can not be tested using my devices, I foucsed on testing 5 remaining apps, **Capture, Heges, Qlone, Scandy Pro, and Trino**. 


| Index | Name | ios | Hardware restrictions | Key features(free) | Key features(paid) |
| ----- | ---- | --- |----------------- | -------------------- | ------------------- | 
| 01 | [3D Creator](https://play.google.com/store/apps/details?id=com.sonymobile.scan3d&hl=en) | X | - | - | - |
| 02 | [3DsizeMe](https://techmed3d.com/products/3dsizeme/) | O | iPad with [Structure sensor](https://techmed3d.com/products/structure-sensor-mark-ii/)    | - | - |
| 03 | [Bellus 3D](https://www.bellus3d.com/) | O | iPhones and iPads with FaceID | - | - |
| 04 | [Canvas](https://canvas.io/) | O | iPad with [Structure sensor($499)](https://canvas.io/package) or LiDAR-enabled 2020 iPad Pros | - | - |
| 05 | [Capture: 3D scan anything](https://apps.apple.com/us/app/capture-3d-scan-anything/id1444183458) | O | iPhones and iPads with FaceID  | <li>View model from browser</li>  <li>High-resoultion scaning mode(Quadruple data points)</li> <li>Export only pointcloud </li> <li>Export USDZ / PLY / OBJ </li> | - | 
| 06 | [Display.land](https://get.display.land/)<br> (Will be discontinued on August 11) | O | - | - | - | 
| 07 | [Heges](https://hege.sh/) | O | iPhones and iPads with FaceID | - | <li> $8.99 </li> <li>PLY / STL Export</li>| 
| 08 | [ItSeez3D](https://itseez3d.com/) | O | iPad with Structure sensor   | - | - | 
| 09 | [Meshroom](https://alicevision.org/)<br>(Stand-alone software) | X | - | - | - | 
| 10 | [Qlone](https://www.qlone.pro/) | O | Need [AR Mat](https://28201f68-fc5e-48bf-ae38-d8fec5beca48.filesusr.com/ugd/0dc13a_00f1c793e9274ea4897766276c116ca1.pdf) | <li> Export GIF, jpeg | <li>$29.99</li> <li>Export model in various file format</li> | 
| 11 | [ReCap](https://www.autodesk.com/products/recap/overview)<br>(Stand-alone software)| X | - | - | - |
| 12 | [Scandy Pro](https://www.scandy.co/apps/scandy-pro) | O | iPhones and iPads with FaceID | - | <li>$1.99/W, $5.99/M, $49.99/Y</li> <li>In-app mesh editting</li> |
| 13 | [Trnio](https://www.trnio.com/) | O | - | <li>Three free scan</li> | <li>$5.99</li> <li>Export OBJ</li> |

<h3> 3D scanning test results</h3>

+ iPhone7 Test: Qlone, Trino
+ iPad Pro(3rd) Test: Capture, Heges, Scandy Pro
<br>
<details open>
<summary> <strong>|05| Capture: 3D scan anything</strong></summary>

<ul>

One of the most outstanding feature of this app is that it is free. The app was only one app which does not request you to subscribe or buy pro version to use all functions the app has. Even though many of 3D scanning apps are free to download at first, most of them requires you to pay to unlock some functions. However, in this app, you can 3D scan and download the models without limitation. 

There are some drawbacks. First, the app only provides you [point cloud data](https://en.wikipedia.org/wiki/Point_cloud) instead of [triangulated mesh](https://en.wikipedia.org/wiki/Polygon_mesh). It means you need do extra effort to make mesh using other programs such as Rhino, Catia, ... to make mesh. On top of it, if you are using Apple devices which has TrueDepthCamera on faceside of the device, it is very hard to aim right direction to capture the object. In this case I used the camera on the face side of the iPad, so 

<h4>Pros :</h4>
<li> Totally free app</li>
<li> Unlimited 3D scanning and downloading</li>
<li> View model in web browser</li>

<h4>Cons :</h4>
<li>Provides only point cloud </li>

<h4> Possible data export formats : </h4>
<li>USDZ / PLY / OBJ</li>
</ul>
</details>
<br>
<summary> <strong>|07| Heges </strong></summary>

<ul>
<h4>Results :</h4>

<h4>Pros :</h4>

<h4>Cons :</h4>

<h4> Possible data export formats : </h4>

</ul>


Capture:
Please be aware that this PLY file contains a point cloud representation of the scan. Our SDK supports meshing, but we currently do not export meshes from the Capture App.

Some programs will not display point cloud data without mesh faces, but you can use a free program like MeshLab to convert a point cloud into a mesh. The tutorial below walks through converting a point cloud into a mesh using MeshLab.

I used [Iphone7](https://support.apple.com/kb/SP743?viewlocale=en_US&locale=en_US) and [Ipad Pro 12.9-inch(3rd generation)](https://support.apple.com/kb/SP785?viewlocale=en_US&locale=en_US) as a 3D scanning device, and used 100mm height froggy bank as a object to run 3D scan. 

2020 Best 3D Scanner Apps for Android & iPhone


The 8 best scanning apps for smartphones in 2020 (free)

PHYS S-12
Introduction to Digital Fabrication
