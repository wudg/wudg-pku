---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /other/
---

<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        img {
            width: 721px;
            height: 455px
        }
        
        .focus {
            position: relative;
            width: 721px;
            height: 455px;
            background-color: white;
            padding-left: 0px;
            overflow: hidden;
        }
        /* 父盒子宽度比较小，而liimg里面加起来宽度很大，不能一行显示，就会竖着显示 */
        /* 解决：把ul的宽度设置的大一点 */
        
        .focus ul li {
            float: left;
            list-style: none;
        }
        
        .focus ul {
            width: 400%;
            position: absolute;
            left: 0px;
            top: 0px;
            margin: 0px;
            padding: 0px
        }
        
        .arrow-l,
        .arrow-r {
            /* display: none; */
            background: rgba(0, 0, 0, 0.3);
            position: absolute;
            top: 50%;
            margin-top: -20px;
            width: 24px;
            height: 24px;
            text-decoration: none;
            z-index: 7;
            color: white;
            text-align: center;
            line-height: 24px;
        }
        
        .arrow-l {
            left: 0px;
        }
        
        .arrow-r {
            right: 0px
        }
        
        .circle {
            width: 90px;
            height: 40px;
            position: absolute;
            bottom: 0px;
            left: 245px;
            /* margin: 0px;
            padding: 0px; */
            z-index: 1;
            text-align: center;
            line-height: 40px;
        }
        
        .circle li {
            width: 30px;
            height: 30px;
            float: left;
            list-style: circle;
            color: white;
        }
        
        .circle .current {
            list-style: disc
        }
    </style>
    <script src="{{site.url}}/js/animate.js"></script>
    <!-- 注意顺序 -->
    <script src="{{site.url}}/js/index.js"></script>
</head>
 
<body>
    <div class="focus">
        <a href="javascript:;" class="arrow-l">←</a>
        <a href="javascript:;" class="arrow-r">→</a>
        <!-- 核心滚动区域 -->
        <!-- 要让所有图片排在一行显示，不要什么都用div解决 -->
        <ul>
				<li>
					<a href="#"><img src="{{site.url}}/imgs/research_images/turkey_changeSize.png" alt=""></a>
				</li>
				<li>
					<a href="#"><img src="{{site.url}}/imgs/research_images/slumgullion_sar_2018_modified_compressed.jpg" alt=""></a>
				</li>
				<li>
					<a href="#"><img src="{{site.url}}/imgs/research_images/SLV_aquifer_compressed.jpg" alt=""></a>
				</li>
				<li>
					<a href="#"><img src="{{site.url}}/imgs/research_images/slumgullion_oli_2019268_modified_compressed.png" alt=""></a>
				</li> 
        </ul>
        <ol class="circle">
 
        </ol>
    </div>
</body>
 
</html>


We are the Natural Hazard Remote Sensing (NHRS) Lab at Peking University. We changed our lab name from Geological Hazards and Shallow Processes Remote Sensing (GSPRS) as now we are working on more general hazards including extreme climate hazards. We focus on using remote sensing tools, e.g., Synthetic Aperture Radar (SAR), to characterize ground deformation and land alternations associated with natural hazards in terrestrial planets. We have been working on mapping, monitoring, and modeling landslides, aquifers, dams, mines, coasts, earthquakes, extreme precipitation events, etc. We are dedicated to investigating their natural or anthropogenic triggerings and environmental forcings using statistical, analytical, numerical models and artificial intelligence (AI). Our multidisciplinary research spans the fields of geomatics, geophysics, hydrology, geology, tectonics, climate change, civil and environmental engineering, and computer sciences.

We are always looking for highly motivated students and postdocs to join our lab. The next application to <a href="https://postdocs.pku.edu.cn/tzgg/134998.htm" target="_blank"><i>Boya Postdoc Fellowship at Peking University</i></a> is due in early Fall. We have interesting research data and topics to help strengthen your academic profile and career development! Please contact PI Xie Hu if you are interested.

**NEWS**
<body>
    <table>
        <tbody>
	   <tr>
                <td>8/2023</td>
		<td>Dr. Susu Xu from Stony Brook University | Johns Hopkins University was invitied to visit our lab and give her talk entitled "Causality-informed Rapid Assessment of Seismic Multi-hazards and Impacts from InSAR imagery".</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Xiao got her job as an AI Remote Sensing Scientist in Illinois State Water Survey, UIUC. Big Congrats!</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
	        <td>Xie, as the PI, was granted a Chinese NSF grant on Berkeley Hills landslides over East SF Bay area.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Xie gave a talk in 2023 AOGS in Singapore and the International Symposium on Geo-disaster Reduction in Shanghai, and Xie also joined a field survey on tranditional villages in Hubei Province led by Prof. Fang Wang.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Penghui, Yuqi, Sayyed, Feng, and Xie got some hands-on experience on drone survey in Tianjin.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Penghui gave a talk on Henan floods in CYWater, held in Beijing.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Yuqi, Yiling, and Xie gave talks and posters in the National Symposium on Landform and Quaternary Research in Taiyuan, Shanxi Province. Multiple exciting ongoing studies were covered: SegmentAnythingModel results on Martian craters with diameter of 10s' meters, implications for active layer thickness of permafrost in Tibet Plateau from ground deformation, and large-scale flood mapping in Beijing-Tianjin-Hebei using Geofen-3 and Sentinel-1 SAR images..</td>
       	   </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Penghui, Yuqi, and Yiling flied drone over steep landslides in Lvliang, Shanxi Province.</td>
           </tr>
	   <tr>
                <td>7/2023</td>
		<td>Dr. Sayyed Mohammad Javad Mirzadeh officially joined us as a postdoc fellow!</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Prof. Zhou Zhang and his lab from Zhejiang University visited our lab and had some colloquial talks.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
		<td>Yiling, Penghui, and Xie had a quick training on drone survey in Tianjin.</td>
           </tr>
	   <tr>
    		<td>&nbsp;</td>
     		<td>Yiling and Xie had a few days' fieldwork on slumps (moving frozen land on gentle slopes) in Qinghai-Tibet Plateau (Beiluhe region, Qinghai Province).</td>
           </tr>
	   <tr>
    		<td>6/2023</td>
	   	<td>Prof. Guoquan Wang from the University of Houston and Dr. Yuexin Li from Caltech were invited to visit our lab and give talks.</td>
           </tr>
    	   <tr>
		<td>&nbsp;</td> 
		<td>Congrong, Yongxuan, and Yiling received their B.S. degree from PKU, WHU, and BNU, respectively. Big Congrats!</td>
	   </tr>
    	   <tr>
                <td>5/2023</td>
		<td>Xie gave talks in the National Symposium on Remote Sensing Application in Chengdu and the National Symposium on Chinese Society for Rock Mechanics & Engineeringin in Beijing.</td>
           </tr>
	   <tr>
                <td>4/2023</td>
		<td>We published a paper on slow-moving landslides nested in Pingding-Huama fault zone in Northwest China in <a href="https://doi.org/10.1002/esp.5594" target="_blank"><i>Earth Surface Processes and Landforms</i></a>. Dr. Xuguo Shi from China University of Geosciences led this research.</td>
           </tr>
	   <tr>
		<td>&nbsp;</td> 
		<td>Xie participated the National 1st Symposium Of Data Riven Earth Science Developmentiodes in Zhuhai, 5th Congress of China Geodesy and Geophysics in Wuhan, and 2023 EGU in Vienna, Austria. She also visited the Institute of Geodesy and Geophysics, Chinese Academy of Sciences during her stay in Wuhan.</td>
           </tr>
	   <tr>
                <td>3/2023</td>
		<td>Xiao published a paper on the alleviation of land subsidence in Tianjin due to the National South-to-North Water Diversion Project in <a href="https://doi.org/10.3390/rs15061647" target="_blank"><i>Remote Sensing</i></a>.</td>
            </tr>
	    <tr>
		<td>&nbsp;</td> 
		<td>Dr. Yelu Zeng from China Agricultural University was invited to give a talk on vegetation indices and remote sensing on 3/13.</td>
            </tr>
	    <tr>
		<td>&nbsp;</td> 
		<td>Collaborative research report entitled "M7.8 Turkey-Syria Earthquake Impact Estimates from Near-real-time Crowdsourced and Remote Sensing Data" led by Dr. Susu Xu's lab at Stony Brook University was published in DesignSafe-CI.</td>
            </tr>
            <tr>
                <td>2/2023</td>
		<td>We are collaborating with Dr. Susu Xu's lab at Stony Brook University to assess the building damage in the 2023 M7.8 Turkey-Siyra earthquake <a href="https://arcg.is/09Wzy5" target="_blank"><i>Interactive Map</i></a> from Susu.</td>
	    </tr>
            <tr>
	        <td>&nbsp;</td> 
		<td>Xie, as the PI, was granted a Chinese NSF grant on Martian landslides and craters and their analogs on the Earth.</td>
            </tr>
            <tr>
                <td>12/2022</td>
		<td>NHRS members presented at 2022 AGU remotely -- Yiling (NH44A-02), Xiao (G42D-0249), Sayyed (G41A-07), Yuqi (G41A-02), Penghui (NH31B-03), Xie (NH23C-01).</td>
            </tr>
            <tr>
		<td>&nbsp;</td> 
		<td>Collaborative research paper (in Chinese) entitled "Collapse and subsidence mechanism of compacted loess and suitability of mountain bulldozing and city creation projects in the Loess Plateau of China" led by Dr. Shengwen Qi from CAS was published in Science Bulletin.</td>
            </tr>
	    <tr>
		<td>&nbsp;</td> 
                <td>NHRS Lab virtually celebrated Xiao's graduation ceremony at UH. Big Congrats, Dr. Yu!</td>
            </tr>
            <tr>
		<td>&nbsp;</td> 
                <td>Yuqi was awarded the Best Presentation Award in 2022 International Graduate Workshop on GeoInformatics. Big Congrats!</td>
            </tr>
            <tr>
		<td>11/2022</td> 
                <td>Dr. Lingchao Huang from CU Boulder was invited to give a virtual talk on deep learning on 11/9.</td>
            </tr>
            <tr>
                <td>10/2022</td>
		<td>Yiling was awarded the National Undergraduate Scholarship. Big Congrats!</td>
	    </tr>
            <tr>
		<td>&nbsp;</td> 
		<td>Dr. Zan Wang from CAS was invited to give a talk on machine learning application in monitoring carbon sequestration on 10/26.</td>
            </tr>
	    <tr>
		<td>&nbsp;</td>
                <td>Xie, as the PI, was granted a Chinese NSF grant on natural hazards.</td>
            </tr>
	    <tr>
                <td>9/2022</td>
                <td>Xie obtained the <a href="https://eos.org/agu-news/2022-agu-section-awardees-and-named-lecturers" target="_blank">2022 AGU Natural Hazards Early Career Award</a>. Read <a href="https://mp.weixin.qq.com/s/YTeDEQdhrV15d6SxjbNf-w" target="_blank"><i>News</i></a>!</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Xiao was awarded the 3-minute thesis/dissertation competition at the University of Houston. Big Congrats!</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Yuqi and Penghui officially started their graduate program at PKU. Big Welcome!</td>
            </tr>
            <tr>
                <td>8/2022</td>
                <td>Xiao published a paper on quantifying large-scale snow depth during the winter storm and national major disaster across Texas in February 2021 using SAR scenes and machine learning methods in <a href="https://doi.org/10.1029/2022GL099119" target="_blank"><i>GRL</i></a>. Big Congrats!</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Xie co-hosted the Hydroclimate Hazards section and Xiao gave a talk in 2022 CYWater on 8/28.</td>
            </tr>
            <tr>
                <td>7/2022</td>
                <td>Yongxuan Ran (undergrad from Wuhan University) and Yiling Lin (undergrad from Beijing Normal University) joined the GSPRS lab and will start their graduate program officially next fall.</td>
            </tr>
            <tr>
                <td>5/2022</td>
                <td>Our 2022 EGU session <a href="https://meetingorganizer.copernicus.org/EGU22/session/43347" target="_blank"><i>Remote Sensing Big Data Analysis and Applications in Geoscience</i></a> leading by <a href="https://research.utwente.nl/en/persons/ling-chang" target="_blank">Dr. Ling Chang</a> from ITC, <a href="https://www.gfz-potsdam.de/en/staff/mahdi.motagh" target="_blank">Dr. Mahdi Motagh</a> from GFZ, <a href="https://www.tudelft.nl/en/ceg/about-faculty/departments/geoscience-remote-sensing/staff/scientific-staff/profdrir-rf-ramon-hanssen/" target="_blank">Dr. Ramon Hanssen</a> from Delft, <a href="https://www.professoren.tum.de/en/zhu-xiaoxiang/" target="_blank">Dr. Xiaoxiang Zhu</a> from TUM, and Dr. Xie Hu from PKU held successfully. Xiao, Yuqi, and Xie gave their presentations.</td>
            </tr>
            <tr>
                <td>4/2022</td>
                <td>Dr. Lin Liu from CNHK was invited to give a virtual talk on geodetic studies of frozen ground on 4/26.</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Chao's paper on landslide hazard mapping in the Three Gorges Reservoir Area was published in <a href="https://doi.org/10.1007/s10346-021-01796-1" target="_blank"><i>Landslides</i></a>.</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Penghui joined the lab as a Research Assistant.</td>
            </tr>
            <tr>
                <td>2/2022</td>
                <td>Xie, as the PI, was awarded the PAZ's satellite imagery program: Joint DLR-INTA Scientific Announcement of Opportunity.</td>
            </tr> 
            <tr>
                <td>1/2022</td>
                <td>Xie, as the PI, was awarded JAXA's satellite imagery program: The 3rd Research Announcement on the Earth Observations.</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Qingyu started his PhD program at the Southern Methodist University.</td>
            </tr>
            <tr>
                <td>&nbsp;</td> 
                <td>Invited talk in the Forum of Satellite Gravity and Hydrology on 1/15.</td>
            </tr>
            <tr>
                <td> 12/2021 </td>
                <td> Welcome to our AGU poster on the crustal surgery in Yan'an (NH15D-0488) and the 2021 Texas winter storm (GG45B-0411)!</td>
            </tr>
            <tr>
                <td> 11/2021 </td>
                <td>Our paper on machine-learning characterization of the natural and anthropogenic sources of ground deformation in California was published in <a href="https://doi.org/10.1029/2021JB022373" target="_blank"><i>JGR</i></a>.</td>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>Our paper on elastic stress perturbations relating to the 2020 M5.7 Magna earthquake from centrurial industrial mine waste transport and surface water variations was accepted by <a href="https://meetingorganizer.copernicus.org/EGU22/session/43347" target="_blank"><i>JGR</i></a>.</td>
            </tr>
            <tr>
                <td> 10/2021 </td>
                <td>Our paper on the unprecedented mountain excavation and city construction in Yan'an China was published in <a href="https://doi.org/10.1029/2021GL095230" target="_blank"><i>GRL</i></a>.</td>
            </tr>
            <tr>
                <td>9/2021</td>
                <td>Virtual seminar talk at UTIG - UT Austin.</td>
            </tr>
            <tr>
                <td>8/2021</td>
                <td>Our paper on the shift of hydrological forcing in the movements of Guobo Slope besides the Laxiwa hydropower station in China was published in <a href="https://doi.org/10.1016/j.rse.2021.112664" target="_blank"><i>RSE</i></a>.</td>
            </tr>
            <tr>
                <td>7/2021</td>
                <td>I moved to Peking University. I'm grateful for all help and kindness from the teams that I was in.</td>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>Ground-based InSAR survey at the Slumgullion landslide, CO.</td>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>Talk in 2021 CYWater.</td>
            </tr>
            <tr>
                <td>6/2021</td>
                <td>Poster presentation in FRINGE 2021.</td>
            </tr>
            <tr>
                <td>5/2021</td>
                <td>Our paper on phase unwrapping in extraordinary high-gradient scenarios such as at the Slumgullion landslide was published in <a href="https://doi.org/10.1109/TGRS.2021.3081039" target="_blank"><i>IEEE Transactions on Geoscience and Remote Sensing</i></a>.</td>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>Seminar talks.</td>
            </tr>
            <tr>
                <td>4/2021</td>
                <td>Our 2021 vEGU session NH6.2 : SAR remote sensing for anthropogenic and natural hazards was held successfully.</td>
            </tr>
            <tr>
                <td>&nbsp;</td>
                <td>Delighted to join the Editorial Board of <a href="https://www.springer.com/journal/24" target="_blank"><i>Pure and Applied Geophysics</i></a>. Welcome to submit!</td>
            </tr>
            <tr>
                <td>3/2021</td>
                <td> Awarded NASA New (Early Career) Investigator Program (NIP) in Earth Science. Read <a href="https://www.egr.uh.edu/news/202103/hu-earns-nasa-funding-award" target="_blank"><i>News</i></a>!</td>
            </tr>
            <tr>
                <td>2/2021</td>
                <td>Our paper led by Dr. Guoqiang Shi on decadal spatiotemporal ground deformation in response to the restrictions of groundwater pumping in Suzhou, China was published in <a href="https://doi.org/10.1016/j.rse.2021.112327" target="_blank"><i>RSE</i></a>.</td>
            </tr>
            <tr>
                <td>1/2021</td>
                <td>Seminar talks.</td>
            </tr>
        </tbody>
    </table>
    <br>
    <br>
    <br>
    <br>
</body>
