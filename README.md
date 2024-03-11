# Awesome Computational Primatology
List of projects, model applications, and datasets at the intersection of deep learning and (non-human) primatology (and occasionally other animals).

TODOS
- [ ] Update list
  - [ ] other bala, deepwild, hobaiter etc, marmoset, that one matlab facs one
- [ ] Incorporate audio stuff
- [ ] Sort by modality (cv, audio, other...)
- [ ] Sort by tasks
- [ ] Write review with talmo, dave, seyfarth, cory, david rolnick: 2d/3d, dangers, etc., open-data

**Topic Legend**
- PD = Primate detection
- BPE = Body pose estimation
- FD = Face detection
- FLE = Facial landmark estimation
- FR = Face recognition and/or Re-Identification
- HD = Hand detection
- HPE = Hand pose estimation
- BR = Behavior recognition and/or modeling
- AM = Avatar/Mesh
- SI = Species Identification

deepwild

## By year
| Year | Shorthand | Topic | Animal | Open Model? | Open dataset? | Image Count | 
|------|-----------|-------|---------|------------|---------------|-------------|
| 2024 | [MacAction](https://www.biorxiv.org/content/10.1101/2024.01.29.577734v1.full.pdf) | AM | Macaque | No | No | N/A |
| 2023 | [DeepWild](https://besjournals-onlinelibrary-wiley-com.proxy.library.upenn.edu/doi/full/10.1111/1365-2656.13932) | 2D BPE | Chimp, Bonobo | [Yes](https://github.com/Wild-Minds/DeepWild) | [Upon request](https://doi-org.proxy.library.upenn.edu/10.5281/zenodo.5600472) | N/A |
| 2023 | [Kaneko et al.](https://www.biorxiv.org/content/10.1101/2023.10.16.561623v1.full.pdf) | 3D BM | Marmoset | No | No | N/A |
| 2023 | [Matsumoto et al.](https://www.biorxiv.org/content/10.1101/2023.09.13.556332v1.full.pdf) | 3D BM | Macaque | No | No | N/A |
| 2023 | [ChimpAct](https://proceedings.neurips.cc/paper_files/paper/2023/file/57a95cd3898bf4912269848a01f53620-Paper-Datasets_and_Benchmarks.pdf) | 2D BPE, FR, BR | Yes | Yes | 160,500 |
| 2023 | OpenMonkeyChallenge | 2D BPE | Cross-species | No | [Yes](http://openmonkeychallenge.com/) | 111,529 |
| 2022 | [SIPEC](https://www-nature-com.proxy.library.upenn.edu/articles/s42256-022-00477-5) | 2D BPE, FR, BR | Macaque | [Some](https://www.dropbox.com/sh/y387kik9mwuszl3/AABBVWALEimW-hrbXvdfjHQSa?dl=0) | Upon request | N/A |
| 2021| [Bain et al.](https://www-science-org.proxy.library.upenn.edu/doi/full/10.1126/sciadv.abi4883) | BR | Chimp | No | [Some](https://datadryad.org/stash/share/UUfSTzsL9eTbAo-78pdaXPdaIUJmdJzSuqhXcb48vHM) | N/A |
| 2021 | OpenApePose | 2D BPE | Cross-species | No | Yes | 71,868 |
| 2021 | AP10k | 2D BPE | Cross-species | [Yes](https://github.com/open-mmlab/mmpose/tree/main/configs/animal_2d_keypoint/topdown_heatmap/ap10k) | Yes | 10,015 (675 primates) |
| 2021 | MacaquePose | 2D BPE | Macaque | Yes | Yes | 13,000 |
| 2020 | Sakib & Burghardt | BR | Chimp | [Yes](https://github.com/fznsakib/great-ape-behaviour-detector) | [Yes: Labeled Pan African](https://data.bris.ac.uk/data/dataset/jh6hrovynjik2ix2h7m6fdea3) | 180,000 |
| 2020 | AnimalWeb | FD, FLE | Cross-species | No | Yes | 21,921 (not all prims) |
| 2020 | OpenMonkeyStudio | 3D BPE | Macaque | No | [Yes](https://github.com/OpenMonkeyStudio/OMS_Data) | 195,228 |
| 2020 | [Tri-A](https://www.sciencedirect.com/science/article/pii/S2589004220306027#mmc1) | FD, FR | 41 species | No | [Yes](https://data.mendeley.com/datasets/z3x59pv4bz/2) | 102,399 |
| 2020 | [Sanakoyeu et al.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Sanakoyeu_Transferring_Dense_Pose_to_Proximal_Animal_Classes_CVPR_2020_paper.pdf) | AM | Chimp | [Kind of](https://github.com/asanakoy/densepose-evolution) | No | N/A
| 2019 | [Schofield et al.](https://www-science-org.proxy.library.upenn.edu/doi/full/10.1126/sciadv.aaw0736) | FD, FR | Chimp | No | No | N/A |
| 2019 | Yang et al. | PD | Chimp | No | [Yes: Labeled Pan African](https://data.bris.ac.uk/data/dataset/jh6hrovynjik2ix2h7m6fdea3) | 180,000 |
| 2018 | [Deb et al.](https://ieeexplore-ieee-org.proxy.library.upenn.edu/abstract/document/8698538/authors) | FR | Cross-species | No | No | N/A |
| 2018 | Witham | FLE | Macaque | [Yes](http://www.mackenziemathislab.org/dlc-modelzoo) | [Yes](https://figshare.com/articles/dataset/Macaque_Faces/9862586/1?file=17682749) | 4,000 |
| 2017 | [LemurFaceID](https://link-springer-com.proxy.library.upenn.edu/article/10.1186/s40850-016-0011-9) | FD, FR | Lemur | No | [Yes](http://biometrics.cse.msu.edu/Publications/Databases/MSU_LemurFaceID/) | 462
| 2016 | [Nakamura et al.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0166154) | 3D BM | Macaque | No | No | N/A |
| 2016 | [Freytag et al.](https://link-springer-com.proxy.library.upenn.edu/chapter/10.1007/978-3-319-45886-1_5) | FR | Chimp | No | [Yes](https://github.com/cvjena/chimpanzee_faces) | 6,486 |
| 2013 | [Loos & Ernst](https://link-springer-com.proxy.library.upenn.edu/article/10.1186/1687-5281-2013-49) | FD, FR | Chimp | No | [For purchase](http://www.saisbeco.com/) | 6,522 |
| 2011 | Ernst & Küblbeck | FD | Chimp, Gorilla | No | No | N/A |

## Modality
- Computer vision
- Audio
- Behavioral Modeling
  
## Related
- Macaque Face Avatars
  - [Siebert et al., 2020](https://www.eneuro.org/content/eneuro/7/4/ENEURO.0524-19.2020.full.pdf)
  - [Murphy & Leopold 2019](https://www.sciencedirect.com/science/article/pii/S0165027019301591#sec0160)
