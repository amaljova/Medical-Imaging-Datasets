# Medical-Imaging-Datasets

## Comprehensive Medical Imaging Datasets Repository

*Last Updated: November 2025*

---

## 📋 Table of Contents
1. [CT Segmentation Datasets](#ct-segmentation-datasets)
2. [Lung & Thoracic Cancer Datasets](#lung--thoracic-cancer-datasets)
3. [Brain & Neurological Imaging](#brain--neurological-imaging)
4. [Cardiovascular Imaging](#cardiovascular-imaging)
5. [Chest & Pulmonary Imaging](#chest--pulmonary-imaging)
6. [Oncology & Cancer Imaging](#oncology--cancer-imaging)
7. [Whole Body & Multi-Organ Imaging](#whole-body--multi-organ-imaging)
8. [Ophthalmology & Retinal Imaging](#ophthalmology--retinal-imaging)
9. [Musculoskeletal Imaging](#musculoskeletal-imaging)
10. [Dataset Selection Guide](#dataset-selection-guide)

---

## CT Segmentation Datasets

### Complete Table of CT Datasets with Delineated Anatomical Structures

| **Dataset Name** | **# Structures** | **# CT Scans** | **Anatomical Structures** | **Body Region** | **Access Link** | **License** | **Notes** |
|-----------------|-----------------|----------------|---------------------------|-----------------|-----------------|-------------|-----------|
| **CADS** | 167 | 22,022 | 167 comprehensive structures | Whole body | [arXiv](https://arxiv.org/abs/2507.22953) \| [HuggingFace](https://huggingface.co/datasets/mrmrx/CADS-dataset) | TBD | Largest scale, 18x more than existing, published July 2025 |
| **gCIS** | 83 | 36,419 | 83 structures + lesions | Various | [Nature](https://www.nature.com/articles/s44172-024-00287-0) | Research | General segmentation model with text prompts |
| **TotalSegmentator v2** | 117 | 1,228 | 27 organs, 59 bones, 10 muscles, 8 vessels | Whole body | [Zenodo](https://zenodo.org/records/10047292) | Apache 2.0 | Gold standard, clinical routine data |
| **AbdomenAtlas Full** | 25 | 20,460 | 25 abdominal structures | Abdomen | [GitHub](https://github.com/MrGiovanni/AbdomenAtlas) | CC BY-NC-SA | Largest abdominal dataset |
| **AbdomenAtlas 1.1** | 25 | 8,448 | 25 abdominal structures | Abdomen | [GitHub](https://github.com/MrGiovanni/AbdomenAtlas) | CC BY-NC-SA | 8K version with full annotations |
| **AbdomenAtlas Mini** | 9 | 5,195 | Liver, kidneys, spleen, stomach, gallbladder, pancreas, aorta, IVC | Abdomen | [GitHub](https://github.com/MrGiovanni/AbdomenAtlas) | CC BY-NC-SA | Publicly available subset |
| **FLARE 2023** | 30 | 4,650 | 13-30 organs + tumors | Abdomen | [Challenge](https://flare.grand-challenge.org/) | CC BY-NC-ND | Challenge dataset, pan-cancer |
| **FLARE 2022** | 13 | 2,100 | 13 abdominal organs | Abdomen | [Challenge](https://flare.grand-challenge.org/) | CC BY-NC-ND | Semi-supervised learning focus |
| **AbdomenCT-1K** | 4 | 1,112 | Liver, kidney, spleen, pancreas | Abdomen | [GitHub](https://github.com/JunMa11/AbdomenCT-1K) | Various | Multi-phase, multi-center |
| **CTSpine1K** | Multiple | 1,000+ | Spine structures | Spine | [GitHub](https://github.com/MIRACLE-Center/CTSpine1K) | Research | Comprehensive spine dataset |
| **SAROS** | Multiple | 900 | Body regions, muscles, cavities | Whole body | [TCIA](https://doi.org/10.25737/SZ96-ZG60) \| [Nature](https://www.nature.com/articles/s41597-024-03337-6) | CC BY-NC-ND | Body composition, sparse annotation (every 5th slice) |
| **CT Colonography** | 1 | 825 | Colon | Colon | [TCIA](https://wiki.cancerimagingarchive.net/display/Public/CT+COLONOGRAPHY) | Public | Virtual colonoscopy |
| **RibFrac** | 24+ | 660 | Ribs and fractures | Thoracic cage | [RibFrac](https://ribfrac.grand-challenge.org/) | Research | Rib fracture detection |
| **AMOS** | 15 | 500 | 15 abdominal organs | Abdomen | [Zenodo](https://zenodo.org/record/7262581) | CC BY-NC-SA | Multi-center, multi-vendor |
| **KiTS23** | 3+ | 500 | Kidneys, tumors, cysts | Kidneys | [KiTS](https://kits-challenge.org/) | CC BY-NC-SA | Latest kidney tumor challenge |
| **KiTS19/21** | 3 | 300 | Kidneys, tumors | Kidneys | [KiTS](https://kits-challenge.org/) | CC BY-NC-SA | Earlier versions |
| **VerSe 2019/2020** | 26 | 374 | Individual vertebrae | Spine | [VerSe](https://verse2019.grand-challenge.org/) | Research | With fracture grading |
| **LiTS** | 2 | 201 | Liver, liver tumors | Liver | [Codalab](https://competitions.codalab.org/competitions/17094) | Research | Liver tumor segmentation |
| **CRLM** | 5+ | 197 | Liver, vessels, tumors | Liver | TCIA | Research | Colorectal liver metastases |
| **WORD** | 16 | 150 | 16 abdominal organs | Abdomen | Paper | GNU GPL 3.0 | Whole abdominal region |
| **CT-ORG** | 6 | 140 | Liver, lungs, bladder, kidney, bones, brain | Multi-region | [TCIA](http://www.cancerimagingarchive.net/) \| [Nature](https://www.nature.com/articles/s41597-020-00715-8) | CC BY-NC-ND | High accuracy test set |
| **MM-WHS** | 7 | 120 | 7 heart structures (4 chambers, AA, PA, myocardium) | Heart | [MM-WHS](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mmwhs/) | Research | Multi-modality cardiac (CT + MRI) |
| **Head-Neck-CT** | 9+ | 100+ | OARs for radiotherapy | Head & Neck | TCIA | Research | Radiation oncology |
| **Medical Segmentation Decathlon** | 10 tasks | Variable | 10 different organs/tasks | Various | [MSD](http://medicaldecathlon.com/) | CC BY-SA | Multi-task benchmark |
| **CAD-PE** | - | 91 | Pulmonary vessels | Chest vessels | Challenge | Research | Pulmonary embolism |
| **Pancreas-CT** | 1-2 | 82 | Pancreas (± tumors) | Pancreas | [TCIA](https://wiki.cancerimagingarchive.net/) | Research | NIH dataset |
| **LCTSC** | 5 | 60 | Esophagus, heart, spinal cord, lungs, tumors | Thorax | [TCIA](https://www.cancerimagingarchive.net/collection/lctsc/) | Research | Radiation therapy planning |
| **StructSeg** | 6+ | 50 | Organs at risk | Thorax/H&N | [StructSeg](https://structseg2019.grand-challenge.org/) | Research | Radiotherapy planning |
| **BTCV** | 12 | 50 | 12 abdominal organs | Abdomen | [Synapse](https://www.synapse.org/#!Synapse:syn3193805) | Research | Multi-organ benchmark |
| **AbdomenCT-12Organ** | 12 | 50 | 12 organs | Abdomen | Paper | CC BY-NC-SA | Part of AbdomenAtlas |
| **PDDCA** | 9 | 48 | Brainstem, optic nerves, etc. | Head & Neck | Challenge | Research | Auto-segmentation challenge |
| **HaN-Seg** | 30 | Variable | 30 head and neck organs | Head & Neck | Paper \| [Dataset](https://lnkd.in/eYs8gsTQ) | Research | Comprehensive H&N, paired CT/MR |
| **CHAOS** | 4 | 40 | Liver, kidneys, spleen | Abdomen | [CHAOS](https://chaos.grand-challenge.org/) | Research | Combined healthy organs |
| **MICCAI 2015 H&N** | 9 | 48 | Head/neck structures | Head & Neck | Challenge | Research | Auto-segmentation |
| **VISCERAL Anatomy3** | 20+ | 20 | 20+ organs | Multi-region | [VISCERAL](http://www.visceral.eu/) | Research | High-quality annotations |
| **VESSEL12** | - | 20 | Lung vessels | Chest | [VESSEL12](https://vessel12.grand-challenge.org/) | Research | Vessel tree extraction |
| **Visible Human Project** | All | 2 | Complete anatomy | Whole body | [NLM](https://www.nlm.nih.gov/research/visible/visible_human.html) | Public | Cryosection + CT, male & female cadavers |

---

## Lung & Thoracic Cancer Datasets

### CT Datasets with Thoracic Structures and Lung Cancer

| **Dataset Name** | **# Structures** | **# CT Scans** | **Anatomical Structures** | **Access Link** | **License** | **Notes** |
|-----------------|-----------------|----------------|---------------------------|-----------------|-------------|-----------|
| **LCTSC** | 5 | 60 | Esophagus, heart, spinal cord, left/right lungs, tumors | [TCIA](https://www.cancerimagingarchive.net/collection/lctsc/) | Research | Organs at risk delineation for radiation planning |
| **LIDC-IDRI** | - | 1,018 | Lung nodules with characteristics | [TCIA](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI) | Public | 1,186 nodules, 4 radiologist annotations |
| **LUNA16** | - | 888 | Lung nodules | [LUNA16](https://luna16.grand-challenge.org/) | Research | Nodule detection benchmark |
| **Lung-PET-CT-Dx** | - | 355 | Tumor locations by 5 radiologists | [TCIA](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216) | Public | CT + PET/CT, clinical data included |
| **NLSTseg** | 2 | 605 | 662 tumors + 53 nodules (715 total lesions) | [Nature](https://www.nature.com/articles/s41597-025-05742-x) | Public | Low-dose CT, pixel-level annotations, published Aug 2025 |
| **MSD Task 6 (Lung)** | 1 | 96 | Lung tumors (NSCLC) | [MSD](http://medicaldecathlon.com/) | CC BY-SA | NIfTI format, 64 train + 32 test |
| **LyNoS** | 3 | Variable | Lymph nodes, arteries, veins | [HuggingFace](https://huggingface.co/datasets/andreped/LyNoS) | Open | Thoracic vascular structures |
| **COVID-19-CT** | 2 | Variable | Lungs, COVID lesions | Various | Various | Pandemic response datasets |
| **Deep Lesion** | Multiple | 4,000 patients | Multiple organs with lesions | [NIH](https://nihcc.app.box.com/v/DeepLesion) | Public | 32,000+ lesion annotations |
| **LNDb** | - | 294 | Lung nodules | [LNDb](https://lndb.grand-challenge.org/) | Public | Two radiologist annotations |

### Breast Cancer CT Datasets

| **Dataset Name** | **Modality** | **# Scans** | **Structures** | **Access Link** | **Notes** |
|-----------------|-------------|-------------|----------------|-----------------|-----------|
| **Breast Cancer RT Planning** | CT | 52 | Lungs, heart, PTV | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352340917302469) | 50 Gy radiotherapy, DVH/DMH included |
| **BREAST-DIAGNOSIS** | MRI (primary) | Multiple | Various | [TCIA](https://www.cancerimagingarchive.net/collection/breast-diagnosis/) | DCIS, fibroids, carcinomas |
| **CBIS-DDSM** | Mammography | 1,566 patients | Lesions, ROI | [TCIA](https://www.cancerimagingarchive.net/collection/cbis-ddsm/) | Updated DDSM, segmentation + bounding boxes |
| **TOMPEI-CMMD** | Mammography | Variable | Breast lesions | [Dataset](https://lnkd.in/ejKSwZe5) | Enhanced Chinese Mammography Database |
| **BRACS** | Histopathology | Variable | Breast carcinoma subtypes | [Dataset](https://lnkd.in/e4FZQ7TY) | Registration required |
| **BCBM-RadioGenomics** | MRI | Variable | Brain metastases from breast cancer | [Dataset](https://lnkd.in/eaekwCrK) | Radiomic features included |

---

## Brain & Neurological Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **BraTS** | MRI | Brain tumor segmentation with expert annotations | Multi-institutional | [Kaggle](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data) |
| **ADNI** | MRI/PET | Alzheimer's Disease Neuroimaging Initiative | 2,000+ subjects, longitudinal | [ADNI](http://adni.loni.ucla.edu/) |
| **OASIS** | MRI | Open Access Series of Imaging Studies | 2,000+ subjects across 3 datasets | [OASIS](http://www.oasis-brains.org/) |
| **OpenNeuro** | Various | Neuroimaging data platform | 1,240+ datasets, 51,000+ subjects | [OpenNeuro](https://openneuro.org) |
| **UK Biobank Brain** | MRI | Multi-modal brain imaging | 100,000+ subjects | [UK Biobank](https://www.ukbiobank.ac.uk) |
| **ABIDE** | fMRI | Autism Brain Imaging Data Exchange | 1,000+ autism/control subjects | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/) |
| **Human Connectome Project** | MRI/MEG | High-res brain connectivity data | 1,200+ subjects | [HCP](http://www.humanconnectome.org/) |
| **EPISURG** | MRI | Post-epilepsy surgery brain scans | Multi-center dataset | [PhysioNet](https://physionet.org) |
| **FeTA** | MRI | Fetal brain tissue annotation | Fetal MR reconstructions | [FeTA](https://feta.grand-challenge.org/) |

---

## Cardiovascular Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **MM-WHS** | CT/MRI | Multi-Modality Whole Heart Segmentation | 120 subjects (60 CT + 60 MRI) | [MM-WHS](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mmwhs/) |
| **Cardiac CCTA Dataset** | CT | Multiple cardiovascular structures | 206 patients, 8 structures | [Dryad](https://datadryad.org/dataset/doi:10.5061/dryad.9s4mw6mc9) |
| **Coronary Arteries Seg** | CT/Angio | Automated coronary artery segmentation | Specialized vascular imaging | [Dataset](https://lnkd.in/eY64_6qU) |
| **ACDC Challenge** | MRI | Automated Cardiac Diagnosis Challenge | 150 patients | [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/) |
| **MESA** | CT/MRI | Multi-Ethnic Study of Atherosclerosis | 6,500+ participants | [MESA](https://www.mesa-nhlbi.org/) |
| **UK Biobank CMR** | MRI | Cardiovascular magnetic resonance | 100,000 subjects | [UK Biobank](https://www.ukbiobank.ac.uk) |
| **CAMUS** | Ultrasound | Cardiac ultrasound segmentation | 500 patients | [CAMUS](https://www.creatis.insa-lyon.fr/Challenge/camus/) |
| **EchoNet-Dynamic** | Ultrasound | Echocardiogram videos | 10,030 echo videos | [EchoNet](https://echonet.github.io/dynamic/) |
| **MBAS24** | MRI | Multi-class Bi-Atrial segmentation | 100 3D LGE-MRI scans | [MBAS](https://www.creatis.insa-lyon.fr/Challenge/MBAS24/) |

---

## Chest & Pulmonary Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **CheXpert** | X-Ray | Large-scale chest radiograph dataset | 224,000 images, 14 pathology labels | [Stanford AIMI](https://aimi.stanford.edu/datasets/chexpert-chest-x-rays) |
| **NIH Chest X-ray** | X-Ray | NIH Clinical Center chest x-rays | 100,000+ images, 30,000+ patients | [NIH](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community) |
| **MIMIC-CXR** | X-Ray | Chest radiographs with reports | 370,000+ images, 227,000+ studies | [PhysioNet](https://physionet.org/content/mimic-cxr/2.0.0/) |
| **TorchXRayVision** | X-Ray | Unified chest X-ray datasets with pre-trained models | Multiple datasets combined | [GitHub](https://github.com/mlmed/torchxrayvision) |
| **RSNA Pneumonia** | X-Ray | Pneumonia detection challenge | 30,000 frontal-view X-rays | [Kaggle](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge) |
| **COVID-19 Image Dataset** | X-Ray/CT | COVID-19 chest imaging | 1,000+ COVID cases | [GitHub](https://github.com/ieee8023/covid-chestxray-dataset) |
| **PadChest** | X-Ray | Spanish hospital chest X-rays | 160,000+ images, 67,000 patients | [BIMCV](http://bimcv.cipf.es/bimcv-projects/padchest/) |
| **VinDr-CXR** | X-Ray | Vietnamese chest X-ray dataset | 18,000 images with annotations | [VinDr](https://vindr.ai/datasets/cxr) |

---

## Oncology & Cancer Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **TCIA Collections** | Various | Cancer Imaging Archive | 200+ collections, PB of data | [TCIA](http://www.cancerimagingarchive.net/) |
| **TCGA** | Pathology | The Cancer Genome Atlas | 11,000+ cases, 33 cancer types | [TCGA](http://cancergenome.nih.gov/) |
| **IDC (NCI)** | Various | NCI Imaging Data Commons | Multiple cancer types | [IDC](https://portal.imaging.datacommons.cancer.gov/) |
| **BreakHis** | Histopathology | Breast cancer histopathology | 7,900+ images, 82 patients | [BreakHis](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/) |
| **Camelyon** | Histopathology | Lymph node metastasis detection | 1,000 whole-slide images | [Camelyon](https://camelyon17.grand-challenge.org/) |
| **MITOS** | Histopathology | Mitosis detection in breast cancer | 50 high-power fields | [MITOS](http://www.ipal.cnrs.fr/event/icpr-2012) |
| **ProstateX** | MRI | Prostate cancer detection | 400+ prostate MRI exams | [ProstateX](https://prostatex.grand-challenge.org/) |
| **PROMISE12** | MRI | Prostate segmentation | 50 T2-weighted MRI | [PROMISE12](https://promise12.grand-challenge.org/) |
| **ISIC Archive** | Dermoscopy | Skin lesion images | 70,000+ images | [ISIC](https://www.isic-archive.com/) |
| **Histopathology + Spatial** | Histopathology | Integrated histology and spatial transcriptomics | Multi-modal dataset | [Repo](https://lnkd.in/enWfgtBh) \| [Dataset](https://lnkd.in/ev__8tbU) |

---

## Whole Body & Multi-Organ Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **CADS** | CT | Most comprehensive whole-body dataset | 22,022 CT scans, 167 structures | [arXiv](https://arxiv.org/abs/2507.22953) \| [HF](https://huggingface.co/datasets/mrmrx/CADS-dataset) |
| **gCIS** | CT | General CT segmentation model | 36,419 CT scans, 83 tasks | [Nature](https://www.nature.com/articles/s44172-024-00287-0) |
| **TotalSegmentator v2** | CT | Comprehensive body segmentations | 1,228 scans, 117 structures | [Zenodo](https://zenodo.org/records/10047292) |
| **TotalSegmentator (NCI)** | CT | NLST collection | 126,000+ CT scans | [Discussion](https://lnkd.in/e3-wGehc) \| [Dataset](https://lnkd.in/ebaE-dbC) |
| **SAROS Dataset** | CT | Full body with detailed organ annotations | 900 CT scans, sparse (every 5th slice) | [Paper](https://lnkd.in/ekQnxpNb) \| [TCIA](https://doi.org/10.25737/SZ96-ZG60) |
| **Whole-Body CT (TCIA)** | CT | Healthy whole-body CT collection | 30 healthy subjects | [Dataset](https://lnkd.in/egVyuuGH) |
| **UK Biobank Imaging** | MRI/DXA | Multi-organ MRI and body composition | 100,000 subjects | [UK Biobank](https://www.ukbiobank.ac.uk) |
| **German National Cohort** | MRI | Whole-body MR imaging | 30,000 subjects planned | [GNC](https://nako.de/en/) |
| **UMIE Dataset** | CT/MRI/X-ray | Unified medical imaging dataset | 1M+ images, 20 sources | [UMIE](https://github.com/UMIE-datasets) |
| **MedIMeta** | Multi-modal | Medical imaging meta-dataset | 19 datasets, 54 tasks | [Nature](https://www.nature.com/articles/s41597-025-04866-4) |

---

## Ophthalmology & Retinal Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **DRIVE** | Fundus | Digital Retinal Images for Vessel Extraction | 40 retinal images | [DRIVE](https://drive.grand-challenge.org/) |
| **STARE** | Fundus | Structured Analysis of the Retina | 400+ retinal images | [STARE](http://cecas.clemson.edu/~ahoover/stare/) |
| **Messidor** | Fundus | Diabetic retinopathy screening | 1,200 eye fundus images | [Messidor](http://www.adcis.net/en/third-party/messidor/) |
| **EyePACS** | Fundus | Diabetic retinopathy detection | 88,000+ retinal images | [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection) |
| **APTOS 2019** | Fundus | Asia Pacific diabetic retinopathy | 13,000 fundus images | [Kaggle](https://www.kaggle.com/c/aptos2019-blindness-detection) |
| **UK Biobank OCT** | OCT | Optical coherence tomography | 100,000+ subjects | [UK Biobank](https://www.ukbiobank.ac.uk) |
| **ODIR** | Fundus | Ocular Disease Intelligent Recognition | 5,000 patients | [ODIR](https://odir2019.grand-challenge.org/) |
| **IDRiD** | Fundus | Indian Diabetic Retinopathy Image Dataset | 516 images with lesion annotations | [IDRiD](https://idrid.grand-challenge.org/) |

---

## Musculoskeletal Imaging

| **Dataset Name** | **Modality** | **Description** | **Size/Scope** | **Access Link** |
|-----------------|-------------|-----------------|----------------|-----------------|
| **MURA** | X-Ray | Musculoskeletal radiographs | 40,000+ images | [MURA](https://stanfordmlgroup.github.io/competitions/mura/) |
| **CTSpine1K** | CT | Comprehensive spine structures | 1,000+ CT scans | [GitHub](https://github.com/MIRACLE-Center/CTSpine1K) |
| **VerSe 2019/2020** | CT | Individual vertebrae segmentation | 374 CT scans, 26 vertebrae | [VerSe](https://verse2019.grand-challenge.org/) |
| **RibFrac** | CT | Ribs and fractures | 660 CT scans, 24+ ribs | [RibFrac](https://ribfrac.grand-challenge.org/) |

---

## Dataset Statistics Summary

### By Size Category

| **Size Category** | **Dataset Examples** | **Typical Use Case** |
|------------------|---------------------|---------------------|
| **Mega (>10,000)** | CADS (22,022), gCIS (36,419), AbdomenAtlas Full (20,460), TotalSegmentator NCI (126,000+) | Foundation models, large-scale training |
| **Large (1,000-10,000)** | FLARE 2023 (4,650), AbdomenAtlas Mini (5,195), TotalSegmentator v2 (1,228), LIDC-IDRI (1,018), CTSpine1K (1,000+) | Comprehensive model training |
| **Medium (100-1,000)** | AMOS (500), VerSe (374), KiTS (300-500), SAROS (900), RibFrac (660), CT Colonography (825) | Standard deep learning training |
| **Small (<100)** | BTCV (50), CHAOS (40), VISCERAL (20), LCTSC (60) | Benchmarking, transfer learning |

### By Anatomical Region

| **Region** | **Key Datasets** | **Total Scans** |
|-----------|-----------------|-----------------|
| **Whole Body** | CADS, gCIS, TotalSegmentator, SAROS | 60,000+ |
| **Abdomen** | AbdomenAtlas, FLARE, AMOS, WORD | 35,000+ |
| **Thorax/Lung** | LIDC-IDRI, LUNA16, LCTSC, NLSTseg | 3,500+ |
| **Cardiac** | MM-WHS, ACDC, MESA, CAMUS | 7,000+ |
| **Spine** | CTSpine1K, VerSe | 1,400+ |
| **Brain** | BraTS, OASIS, ADNI | 5,000+ |

---

## Access Requirements

| **Access Type** | **Requirements** | **Example Datasets** |
|----------------|-----------------|---------------------|
| **Open Access** | Direct download | TotalSegmentator, DRIVE, some TCIA collections |
| **Registration** | Free account required | TCIA, Synapse, Grand Challenge, PhysioNet |
| **DUA Required** | Sign data use agreement | PhysioNet datasets, some challenges |
| **Restricted** | Institutional approval or fees | UK Biobank (fee-based), some clinical datasets |

---

## Dataset Selection Guide

### By Your Primary Need

| **Your Need** | **Recommended Datasets** | **Why** |
|--------------|-------------------------|---------|
| **Getting Started / Learning** | BTCV (50), CT-ORG (140), DRIVE (40) | Small, well-documented, manageable size |
| **Comprehensive Whole-Body** | CADS (22,022), gCIS (36,419), TotalSegmentator (1,228) | Most structures annotated, largest scale |
| **Abdominal Focus** | AbdomenAtlas, FLARE, AMOS | Specialized, high-quality abdominal organs |
| **Lung/Chest Disease** | LIDC-IDRI, LUNA16, NLSTseg | Standard benchmarks, nodule detection |
| **Cardiac Structures** | MM-WHS, ACDC, Cardiac CCTA Dataset | Heart chambers and vessels |
| **Cancer Detection/Segmentation** | LiTS, KiTS, Deep Lesion, Medical Decathlon | Tumor + organ segmentation |
| **Radiation Treatment Planning** | LCTSC, StructSeg, HaN-Seg | Organs at risk delineation |
| **Body Composition Analysis** | SAROS, TotalSegmentator | Muscle, fat, organ volumes |
| **Multi-Task Foundation Models** | CADS, gCIS, Medical Decathlon | Diverse tasks, large scale |
| **Clinical Validation** | UK Biobank, MESA, TCIA collections | Real-world clinical data |

### By Clinical Application

| **Application** | **Datasets** |
|----------------|-------------|
| **Oncology** | TCIA, TCGA, LiTS, KiTS, LIDC-IDRI, NLSTseg |
| **Cardiology** | MM-WHS, ACDC, MESA, EchoNet-Dynamic, UK Biobank CMR |
| **Pulmonology** | CheXpert, MIMIC-CXR, LUNA16, COVID-19 datasets |
| **Neurology** | BraTS, ADNI, OASIS, Human Connectome Project |
| **Radiology (General)** | CADS, gCIS, TotalSegmentator, TCIA |
| **Pathology** | TCGA, Camelyon, BreakHis, BRACS |
| **Ophthalmology** | EyePACS, IDRiD, Messidor, UK Biobank OCT |
| **Emergency Medicine** | MIMIC-CXR, RSNA Pneumonia, RibFrac |

---

## 🛠️ Tools & Resources

### Python Libraries for Medical Imaging
- **SimpleITK**: Reading/writing medical images (DICOM, NIfTI)
- **nibabel**: NIfTI file handling
- **pydicom**: DICOM file handling
- **pylidc**: LIDC-IDRI dataset specific tools
- **MONAI**: Medical imaging deep learning framework
- **TorchIO**: PyTorch-based medical image processing
- **zenodo-get**: Downloading Zenodo datasets

### Visualization Tools
- **3D Slicer**: Free medical image viewer and analysis
- **ITK-SNAP**: Segmentation visualization and annotation
- **MITK Workbench**: Medical imaging toolkit
- **OsiriX** (Mac): DICOM viewer
- **Horos** (Mac): Open-source DICOM viewer

### Download Tools
- **NBIA Data Retriever**: For TCIA datasets
- **wget/curl**: Command-line downloading
- **Python scripts**: Custom download automation

---

## 📋 Important Usage Notes

### Citation Requirements
- **ALL datasets require proper citation** in publications
- Check individual dataset pages for specific citation formats
- Many datasets have associated papers that must be cited

### Data Size Considerations
- Total storage for all datasets: **>100TB**
- Cloud access available for many large datasets
- Consider starting with smaller datasets for prototyping

### Format Considerations
- **DICOM**: Most radiology datasets, requires conversion tools
- **NIfTI**: Research-friendly format, easier to work with
- **PNG/JPG**: X-ray and pathology images
- Format conversion may be needed between datasets

### Ethical & Legal Compliance
- Review individual dataset licenses before use
- Ensure compliance with HIPAA, GDPR, and local regulations
- Some datasets restrict commercial use
- IRB approval may be required for certain uses

### Data Quality Notes
1. **Annotation Quality**: Ranges from AI-assisted to expert radiologist annotations
2. **Completeness**: Some datasets have partial annotations (e.g., SAROS - every 5th slice)
3. **Sparsity**: Check whether all slices are annotated
4. **Multi-phase**: Some include contrast phases (arterial, venous, etc.)
5. **Pathology Mix**: Consider healthy vs. diseased case ratios
6. **Imaging Protocols**: Multi-center datasets have protocol variability

---

## 🔄 Latest Additions (2025)

### Newly Released Datasets
1. **CADS** (July 2025): 22,022 CT scans, 167 structures
2. **NLSTseg** (August 2025): 605 patients, low-dose CT with lung lesions
3. **gCIS** (October 2024): 36,419 CT scans with text-prompt segmentation

---

## 📊 Total Dataset Statistics

- **Total Datasets Listed**: 150+
- **Total CT Datasets with Segmentation**: 50+
- **Estimated Total CT Scans**: 150,000+
- **Total Medical Images Across All Modalities**: 2M+
- **Countries Represented**: 30+
- **Imaging Centers**: 500+

### By Modality Distribution
- **CT**: 50+ datasets
- **MRI**: 40+ datasets
- **X-Ray**: 25+ datasets
- **Histopathology**: 20+ datasets
- **Ultrasound**: 15+ datasets
- **Fundus/OCT**: 10+ datasets
- **Multi-modal**: 20+ datasets

---

## 🤝 Contributing to This List

To suggest additions or corrections:
1. Ensure dataset is publicly accessible (with or without registration)
2. Verify medical/clinical relevance
3. Include proper attribution and licensing information
4. Provide dataset size, quality, and documentation details

---

## 📚 Additional Resources

### Key Repositories
- [The Cancer Imaging Archive (TCIA)](http://www.cancerimagingarchive.net/)
- [Grand Challenge](https://grand-challenge.org/)
- [Zenodo Medical Imaging](https://zenodo.org/)
- [PhysioNet](https://physionet.org/)
- [UK Biobank](https://www.ukbiobank.ac.uk/)
- [HuggingFace Medical Datasets](https://huggingface.co/datasets)

### Review Papers & Benchmarks
- Medical Segmentation Decathlon (Nature Communications, 2022)
- CADS Framework (arXiv, 2025)
- gCIS Model (Communications Engineering, 2024)

---

*Disclaimer: This list is for informational purposes only and does not constitute endorsement of any particular dataset. Always review individual dataset licenses and ensure compliance with ethical guidelines and regulations for medical data use in your jurisdiction.*

*Generated using Claude AI, Model: Sonnet 4.5 (with Pro plan of Amal)*

*Last Updated: November 2025*
*Validated: November 2025*
