<h1>[WIP]3D Scanning Apps for iPhone/iPad users</h1>

![002|690x327](upload://drgAEjS6sKKpcAqjpzlW36xsTii.jpeg) 

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


![003_capture|690x385, 95%](upload://dJwH9TTTifTsPFl7JslT1vPQJ1g.jpeg) 
[View Capture test scan 3D model](https://skfb.ly/6TXXZ)

<details open>
<summary> <strong>|05| Capture: 3D scan anything</strong></summary>

<ul>

One of the most outstanding features of this app is that it is free. The app was only one app that does not request you to subscribe or buy the pro version to use all functions the app has. Even though many 3D scanning apps are free to download at first, most of them require you to pay to unlock some features. However, in this app, you can 3D scan and download the models without limitation.

https://youtu.be/iT-DjA79X7M

However, there are some drawbacks. First, the app only provides you with [point cloud data](https://en.wikipedia.org/wiki/Point_cloud) instead of [a triangulated mesh](https://en.wikipedia.org/wiki/Polygon_mesh). It means you need to make extra effort to make mesh using other programs such as [Meshlab](https://www.meshlab.net/) to make mesh data. On top of it, if you are using devices which has TrueDepthCamera on the face side, it is hard to aim in the direction to capture the object. To check my scanning process, I had to mirror the iPad screen into my laptop with 5Kplayer in the above video. 

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

![003_heges|690x385, 95%](upload://rCoqgvYGiLOI0CZOpOAaie2lhGI.jpeg) 
[View Heges test scan 3D model](https://skfb.ly/6TXXL)
<details open>
<summary> <strong>|07| Heges</strong></summary>

<ul>

Heges uses TrueDepth Camera, and the scanning process of Heges was as same as that of Capture. This app was so sensitive to the device's movement, and it often creates duplicated scanned data in different coordinates.I tested multiple times scanning froggy bank, face, and other objects to get acceptable results but failed. Moreover, it collects data so fast that it often results in large 3D scan files. While I was scanning a 2m height tree in a pot, after I scanned a few seconds, the data size reached 1GB, causing my device to freeze.

<h4>Pros :</h4>
<li> Not sure</li>

<h4>Cons :</h4>
<li>$8.99 In-app purchase to use the app</li>
<li>Very sensitive to the movement </li>
<li>Large data size</li>

<h4> Possible data export formats : </h4>
<li> PLY / STL</li>
</ul>

</details>
<br>

![006_Qlone|690x386, 95%](upload://yFmbBzd8AKasMZKyPpVyYyssIIG.jpeg) 
[View Qlone test scan 3D model](https://skfb.ly/6TYPu)
<details open>
<summary> <strong>|10| Qlone </strong></summary>

<ul>

The scanning process of Qlone is similar to that of David SLS 3D Scanner at GSD. You need to set-up a printed AR mat, checker pattern sheet, and walk around an object to capture images. You can use a rotation platform instead of walking around the object. Scanning process takes 2-3 minutes but easy and fun thanks to good interface design. You can easily check which part of the model should be captured more by color indication of the sectioned hemisphere. 

Qlone gives overall good results of the 3D model but the top side. Even though it provides various exporting options, it is the most expensive app among the tested apps. 

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

![005_ScandyPro|690x387, 95%](upload://wDLZkk08ShRxAlxaeAiCZcdM8LO.jpeg) 
[View Scandy Pro test scan 3D model](https://skfb.ly/6TYPx)
<details open>
<summary> <strong>|12| Scandy Pro </strong></summary>

<ul>
[Raw](https://skfb.ly/6TYPw)

aaa

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

![007_Trino|690x387](upload://oci4kVJatHawS7vprLGYdMsl0Rx.jpeg) 
[View Trino test scan 3D model](https://skfb.ly/6TXVM)
<details open>
<summary> <strong>|13| Trino </strong></summary>

<ul>


https://youtu.be/onIKjI-32sM
The 3D scanning process using Trino was the easiest among the tested apps. You can simply tap the camera button and walk around the object taking 30-40 pictures from all sides. When the app collects photos, it also collects relative coordinate between taken photos and displays the location ass yellow dots. After finish taking pictures, you can upload those images set to Trino's server. Then, they take care of everything. It sends you back the 3D model in 10-15 minutes. This scanning works well with either small and large objects, indoor and outdoor. Please find one more 3D scan sample of the statue taken outdoor. <br>
![009_Trino_statue|690x388, 50%](upload://tkEWVbgBkZLtLmQyQIKVSVplPnS.jpeg) ![009_Trino_statue2|471x500, 39%](upload://ve9pwF74PT1D771pJq4oRCYRhX6.jpeg) 

Unlike Capture or Scandy Pro, you cannot use this app with a rotating platform since it collects relative locations between photos. So, you must walk around the object and capture multiple images, which takes a few minutes. 


<h4>Pros :</h4>
<li> Easy scanning process</li>
<li> One click upload to Sketchfab</li>
<li> Do not need TrueDepth Camera</li>

<h4>Cons :</h4>
<li> $5.99 for unlimited use</li>
<li> Internet connection needed</li>
<li> Takes 10-15 minute to review 3D scanning results </li>
<li> Cannot use rotation platform </li>

<h4> Possible data export formats : </h4>
<li>OBJ</li>
</ul>

</details>
<br>
