# Summary of existing datasets
## 1.CWRU（凯斯西储大学轴承数据中心）
下载连接（https://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website）

CWRU数据集是使用最为广泛的，文献较多。不一一举例。其中University of New South Wales 的Wade A. Smith在2015年进行了比较全面的总结和对比[1]。比较客观的综述和分析了使用数据进行诊断和分析研究的情况。官方网站提供的是.mat格式的数据，MATLAB直接使用比较方便。

Github上有人分享了在python中自动下载和使用的方法。https://github.com/Litchiware/cwru
R语言中使用的方法：https://github.com/coldfir3/bearing_fault_analysis

Smith W A, Randall R B. Rolling element bearing diagnostics using the Case Western Reserve University data: A benchmark study[J]. Mechanical Systems and Signal Processing, 2015,64-65:100-131.

## 2.MFPT（机械故障预防技术学会）
数据链接：（https://mfpt.org/fault-data-sets/）

声学和振动数据库链接（http://data-acoustics.com/measurements/bearing-faults/bearing-2/）

NRG Systems总工程师Eric Bechhoefer博士代表MFPT组装和准备数据。该数据集发布于2012年，使用该数据集的相比于CWRU少一些。

MATLAB 文档关于MFPT轴承数据的故障诊断举例
https://ww2.mathworks.cn/help/predmaint/examples/Rolling-Element-Bearing-Fault-Diagnosis.html）

论文：
Lee D, Siu V, Cruz R, et al. Convolutional neural net and bearing fault analysis[C]//Proceedings of the International Conference on Data Mining (DMIN). The Steering Committee of The World Congress in Computer Science, Computer Engineering and Applied Computing (WorldComp), 2016: 194.

## 3.德国Paderborn大学
**链接：** https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter/

**数据描述：较新，挖掘空间较大，相关论文较少**

**论文**
Bin Hasan M. Current based condition monitoring of electromechanical systems. Model-free drive system current monitoring: faults detection and diagnosis through statistical features extraction and support vector machines classification.[D]. University of Bradford, 2013.
Lessmeier C, Kimotho J K, Zimmer D, et al. Condition monitoring of bearing damage in electromechanical drive systems by using motor current signals of electric motors: a benchmark data set for data-driven classification: Proceedings of the European conference of the prognostics and health management society, 2016[C].

## 4.FEMTO-ST轴承数据集
**数据链接** FEMTO-ST网站：https://www.femto-st.fr/en

**数据描述： 由FEMTO-ST研究所发布，PHM IEEE 2012数据挑战期间使用的数据集**

**数据相关信息**
github链接：https://github.com/wkzs111/phm-ieee-2012-data-challenge-dataset
http://data-acoustics.com/measurements/bearing-faults/bearing-6/

**论文**
Porotsky S, Bluvband Z. Remaining useful life estimation for systems with non-trendability behaviour: Prognostics & Health Management, 2012[C].
Nectoux P, Gouriveau R, Medjaher K, et al. PRONOSTIA: An experimental platform for bearings accelerated degradation tests.: IEEE International Conference on Prognostics and Health Management, PHM’12., 2012[C]. IEEE Catalog Number: CPF12PHM-CDR.
E. S, H. O, A. S S V, et al. Estimation of remaining useful life of ball bearings using data driven methodologies: 2012 IEEE Conference on Prognostics and Health Management, 2012[C].2012-18-21 June 2012.

## 5.辛辛那提IMS
**数据链接** https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/

**论文**
Gousseau W, Antoni J, Girardin F, et al. Analysis of the Rolling Element Bearing data set of the Center for Intelligent Maintenance Systems of the University of Cincinnati: CM2016, 2016[C].
Qiu H, Lee J, Lin J, et al. Wavelet filter-based weak signature detection method and its application on rolling element bearing prognostics[J]. Journal of Sound and Vibration, 2006,289(4):1066-1090.

## 6.University of Connecticut
**数据链接** https://figshare.com/articles/Gear_Fault_Data/6127874/1

**数据描述**
Time domain gear fault vibration data (DataForClassification_TimeDomain)
And Gear fault data after angle-frequency domain synchronous analysis (DataForClassification_Stage0)
Number of gear fault types=9={‘healthy’,‘missing’,‘crack’,‘spall’,‘chip5a’,‘chip4a’,‘chip3a’,‘chip2a’,‘chip1a’}
Number of samples per type=104
Number of total samples=9x104=903
The data are collected in sequence, the first 104 samples are healthy, 105th ~208th samples are missing, and etc.

**论文**
P. C, S. Z, J. T. Preprocessing-Free Gear Fault Diagnosis Using Small Datasets With Deep Convolutional Neural Network-Based Transfer Learning[J]. IEEE Access, 2018,6:26241-26253.

## 7.XJTU-SY Bearing Datasets（西安交通大学 轴承数据集）
**数据链接** http://biaowang.tech/xjtu-sy-bearing-datasets/

**数据描述** 由西安交通大学雷亚国课题组王彪博士整理

**论文**
B. W, Y. L, N. L, et al. A Hybrid Prognostics Approach for Estimating Remaining Useful Life of Rolling Element Bearings[J]. IEEE Transactions on Reliability, 2018:1-12.

## 8.东南大学
**github链接** https://github.com/cathysiyu/Mechanical-datasets
**数据描述** 由东南大学严如强团队博士生邵思羽完成。
“Highly Accurate Machine Fault Diagnosis Using Deep Transfer Learning”
Gearbox dataset is from Southeast University, China. These data are collected from Drivetrain Dynamic Simulator. This dataset contains 2 subdatasets, including bearing data and gear data, which are both acquired on Drivetrain Dynamics Simulator (DDS). There are two kinds of working conditions with rotating speed - load configuration set to be 20-0 and 30-2. Within each file, there are 8rows of signals which represent: 1-motor vibration, 2,3,4-vibration of planetary gearbox in three directions: x, y, and z, 5-motor torque, 6,7,8-vibration of parallel gear box in three directions: x, y, and z. Signals of rows 2,3,4 are all effective.
**论文**
Siyu S , Stephen M A , Ruqiang Y , et al. Highly-Accurate Machine Fault Diagnosis Using Deep Transfer Learning[J]. IEEE Transactions on Industrial Informatics, 2018:1-1.

## 9.Acoustics and Vibration Database（振动与声学数据库）
提供一个手机振动故障数据集的公益性网站链接：http://data-acoustics.com/

## 10.机械设备故障诊断数据集及技术资料大全
有比较多的机械设备故障数据资料：https://mekhub.cn/machine-diagnosis

## 11.贾维斯的小屋——机器学习+故障诊断
https://5663015.github.io/
