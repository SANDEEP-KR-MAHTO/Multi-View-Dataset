
# Multi-view Datasets
## 1. Usage
All dataset files contain two attributes, `X` and `y`. 
- `X` is the multi-view data as a cell, each element in this cell is an _N_-by-_D_ matrix _X<sub>k</sub>_, where _N_ is the number of data points and _D_ is the feature dimensions. So rows of _X<sub>k</sub>_ correspond to data points.
- `y` is the vector of ground-truth labels.

**Note: Due to Github's limitation on file size, files larger than 20MB will be stored in other repositories**：
1. [Baidu](https://pan.baidu.com/s/1vAIi4Tdhuk9c3XNf-48_4Q),  code：yeog
2. [Google](https://drive.google.com/drive/folders/1wkQA0z-cAKVzFIk1izOALCXdqdwsPvx2?usp=share_link)

## 2. Dataset Details
| Dataset | Instances | Clusters | Views(dimension) | Description | Type           |
|---------|-----------|----------|------------------|-------------|----------------|
| 3Sources | 169 | 6 | Reuters(3068), BBC(3560), Guardian(3631) | A new multi-view text dataset collected from three well-known online news sources: [BBC](http://mlg.ucd.ie/datasets/news.bbc.co.uk), [Reuters](http://reuters.co.uk/),and [The Guardian](http://www.guardian.co.uk/) [[14]](#weiFuzzyClusteringMultiview2022). | Text           |
| 100Leaves | 1600 | 100 | SD(64), FSM(64), TH(64) | Sixteen samples of leaf each of one-hundred plant species [[16]](#yangMultiViewAdjacencyConstrainedHierarchical2022). | Image          |
| ACM | 3025 | 3 | View1(1870), View2(3025), View2(3025), View2(3025), View2(3025) | The dataset extracts papers published in KDD, SIGMOD, SIGCOMM, MobiCOMM, and VLDB. |                |
| ALOI-1k | 110250 | 1000 | CS(77), Haralick(13), HSV(64), RGB(125) | The [Amsterdam Library of Object Images](http://aloi.science.uva.nl/) is a collection of 110250 images of 1000 small objects, taken under various light conditions and rotation angles [[25]](#zhangFacilitatedLowrankMultiview2023). | Object         |
| ALOI | 10800 | 100 | CS(77), Haralick(13), HSV(64), RGB(125) | A subset of ALOI-1k [[25]](#zhangFacilitatedLowrankMultiview2023). | Object         |
| Animal | 11673 | 20 | View1(2688), View2(2000), View3(2001), View4(2000), | A selected set of the Animals with Attributes dataset [[12]](#lampertLearningDetectUnseen2009). | Animal         |
| BBCSport | 544 | 5 | View1(3183), View2(3203) | This document dataset contains 544 documents  from the BBC Sport website, and they are aboutthe sports news between 2004 and 2005 [[4]](#chenLowrankTensorBased2022). | Text           |
| BBC4view | 685 | 5 | View1(4659), View2(4633), View3(4665), View4(4684) | Similar to BBCSport, this dataset consists of 685 documents from the BBC Sport website about sports news [[4]](#chenLowrankTensorBased2022). | Text           |
| COIL20 | 1440 | 20 | Intensity(1024), LBP(944), Gabor(4096) | It is the abbreviation of the Columbia object image library dataset [[24]](#wuEssentialTensorLearning2019). | Object         |
| Caltech101-7 | 1474 | 7 | GABOR(48), WM(40), CENT(254), HOG(1984), GIST(512), LBP(928) | This dataset contains 1474 images belonging to seven classes, which are faces, motorbikes, dollar bill, Garfield, stop sign, and windsor chair [[4]](#chenLowrankTensorBased2022). | Object         |
| Caltech101-20 | 2386 | 20 | GABOR(48), WM(40), CENT(254), HOG(1984), GIST(512), LBP(928) | This is the frequently used subsets of Caltech101 consisting of 20 categories of images built for object recognition tasks [[5]](#liMultiviewClusteringScalable2022). | Object         |
| Caltech101-all | 9144 | 102 | GABOR(48), WM(40), CENT(254), HOG(1984), GIST(512), LBP(928) | The Caltech101 dataset contains images from 101 object categories and **background** (e.g., “helicopter”, “elephant” and “chair” etc.) and a background category that contains the images not from the 101 object categories [[8]](#zhangBinaryMultiViewClustering2019). | Object         |
| CiteSeer | 3312 | 6 | Content(3703), Cites(4732) | The archive contains 3312 documents over the 6 labels (Agents,IR,DB,AI,HCI,ML) [[13]](#fangEfficientMultiviewClustering2023). | Text           |
| Cora | 2708 | 7 | Content(1433),  Inbound(2708), Outbound(2708), Cites(2708) | The archive contains 2708 documents over the 7 labels (Neural_Networks, Rule_Learning, Reinforcement_Learning, Probabilistic_Methods, Theory, Genetic_Algorithms,Case_Based) [[13]](#fangEfficientMultiviewClustering2023). | Text           |
| Handwritten | 2000 | 10 | FOU(76), FAC(216), KAR(64), PIX(240), ZER(47), MOR(6) | This dataset consists of features of handwritten numerals ('0'--'9') extracted from a collection of Dutch utility maps [[7]](#nieMultiviewClusteringAdaptively2018). | Image          |
| MNIST-10k | 10000 | 10 | ISO(30), LDA(9), NPE(30) | A freely available and well-known handwritten database for image recognition consisting of four categories from digit 0 to digit 9, and each category has 1,000 samples evenly [[1]](#dengMNISTDatabaseHandwritten2012). | Handwritten    |
| MNIST-4 | 4000 | 4 | ISO(30), LDA(9), NPE(30) | MNIST-4 is a subset of MNIST-10k consisting of four categories from digit 0 to digit 3 [[5]](#liMultiviewClusteringScalable2022). | Handwritten    |
| Movies | 617 | 17 | Keywords(1878), Actors(1398) | It is a movie corpus extracted from IMDb. [[22]](#xieGeneralizedMultiviewLearning2022) | Text           |
| MSRC-v5 | 210 | 7 | CM(24), HOG(576), GIST(512), LBP(256), CENT(254) | A subset of the Microsoft Research in Cambridge dataset [[21]](#xiaTensorizedBipartiteGraph2023). | Image          |
| NUS-WIDE-OBJ | 30000 | 31 | CH(65), CM(226), CORR(145), EDH(74), WT(129) | It is a dataset for object recognition which consists of 30000 images in 31 classes[[9]](#liLargescaleMultiviewSpectral2015). | Image          |
| NUS-WIDE | 2400 | 12 |  CH(64), CORR(144), EDH(75), WT(128), CM55(225) | 12 categories of animal images selected from the NUS-WIDE-OBJ dataset, and the first 200 images are selected for each category [[3]](#chuaNUSWIDERealworldWeb2009). | Object         |
| ORL | 400 | 40 | View1(4096), View2(3304), View3(6750) | Face dataset contains 400 images of 40 distinct subjects. For each category, images were taken at different times, lights, facial expressions (open / closed eyes, smiling or not) and facial details (with glasses / without glasses) [[23]](#luoConsistentSpecificMultiView2018) .| Face           |
| OutdoorScene | 2688 | 8 | GIST(512), HOG(432), LBP(256), Gabor(48) |  The dataset has 2688 outdoor scene images consisting of 8 groups [[13]](#fangEfficientMultiviewClustering2023). | Object         |
| ProteinFold | 694 | 27 | View1(27), View2(27), View3(27), View4(27), View5(27), View6(27), View7(27), View8(27), View9(27), View10(27), View11(27), View12(27) | Multiply kernel learning dataset on protein fold prediction [[19]](#liuEfficientEffectiveRegularized2021). | Protein        |
| Prokaryotic | 551 | 4 | gene-repert(393), proteome-comp(3), Text(438) | It contains prokaryotic species described with heterogeneous multi-view data including textual data and different genomic representations.[[20]](#niuMultiviewEnsembleClustering2023) | Genome         |
| Reuters-1200 | 1200 | 6 | English(2000), French(2000), German(2000), Spanish(2000), Italian(2000) | It contains 6 samples of 1200 documents over 6 labels, and desribed by 5 views of 2000 words each [[15]](#huangAutoweightedMultiviewClustering2020). | Text           |
| Reuters-1500 | 1500 | 6 | English(21531), French(24893), German(34279), Spanish(15506), Italian(11547) | The dataset is collection of 1500 documents which are expressed in five different languages (Italian, Spanish, French, German and English) and the corresponding translations [[14]](#weiFuzzyClusteringMultiview2022). | Text           |
| Reuters | 18758 | 6 | English(21531), French(24893), German (34279), Spanish (15506), Italian(11547) | This dataset consists of documents that are written in five different languages and their translations[[9]](#liLargescaleMultiviewSpectral2015). | Text           |
| UCI | 2000 | 10 | Intensity(240), FOU(76), MOR(6) | Obtained from the UCI machine learning repository, this dataset consists of 2000 handwritten digit images belonging to 10 digits with each digit containing 200 samples [[4]](#chenLowrankTensorBased2022). | Handwritten    |
| WebKB | 1051 | 2 | Anchor(1,840), Content(3,000) | The dataset for web pages collected from computer science department web sites at four universities: Cornell University, University of Washington,University of Wisconsin, and University of Texas [[6]](#qiangFastMultiviewDiscrete2021). | Text           |
| Wikipedia | 2866 | 10 | Word(128), SIFT(10) | Wikipedia dataset is the most widely-used dataset for cross-media retrieval. It is based on Wikipedia’s "featured articles", a continually updated article collection [[11]](#rasiwasiaNewApproachCrossmodal2010). | Text           |
| Wikipedia-test | 693 | 10 | Word(128), SIFT(10) | The test set of the Wikipedia collection [[10]](#shiFastMultiViewClustering2023). | Text           |
| Yale | 165 | 15 | Intensity(4096), LBP(3304), Gabor(6750) | This dataset consists of 165 gray-scale face images belonging to 15 subjects with each subject containing 11 images [[4]](#chenLowrankTensorBased2022). | Face           |








<div id="zhangFacilitatedLowrankMultiview2023"></div>

[25] G.-Y. Zhang, D. Huang, and C.-D. Wang, “Facilitated low-rank multi-view subspace clustering,” _Knowledge-Based Systems_, vol. 260, p. 110141, Jan. 2023, doi: [10.1016/j.knosys.2022.110141](https://doi.org/10.1016/j.knosys.2022.110141).

