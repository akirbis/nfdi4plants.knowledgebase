---
layout: docs
title: Uploading files
author:
  - name: Hamed Jalali
    github: https://github.com/hamedjalali1982
    orcid: https://orcid.org/0000-0002-1190-5652
add toc: false
add sidebar: _sidebars/mainSidebar.md
status: published
date: 2024-06-13
---

According to the  [ISA Metadata Model](https://www.nfdi4plants.de/nfdi4plants.knowledgebase/docs/ArcCommanderManual/arc_isa.html), each `study` is connected to an `Investigation` and can contain several `assays`.  Generally the raw data should be uploaded into  `assay` folder. Therefore, we need to first create the  `study`  folder and its relevant `assays`.  


1. In the `studies` folder, click on the `ADD` button to create a study. Then, follow the same procedure in the `assays` folder.
   </br>
    <p float="center">
        <img src="./img/05_uploading_files/add_study.png" width="500" style="border: 2px solid  gray;" /> 
    </p>

      <p float="center">
        <img src="./img/05_uploading_files/add_assay.png" width="500" style="border: 2px solid  gray;" />
    </p> </br>

2. Now according to the ISA model, the investigation, studies, and assays should be linked to each other, studies to investigation and assays to studies. The **SYNC** functions perform these tasks. 

    In the project folder, click on `SYNC STUDY/INVEST` and choose the study created before.  Then click on `SYNC ASSAY/STUDY` and link the relevant studies and assays.  

    <p float="center">
        <img src="./img/05_uploading_files/sync_study.png" width="500" style="border: 2px solid  gray;"  /> 
    </p>

    <p float="center">
    <img src="./img/05_uploading_files/sync_assay.png" width="500" style="border: 2px solid  gray;"/>
    </p>

3. Assume we need to add some raw data in the assay folder. Then, in the relevant assay, go to the `dataset` folder and use the `UPLOAD File(s)` button. Then, in the local system, select the data files.

    <p float="center">
        <img src="./img/05_uploading_files/upload_command.png" width="500" style="border: 2px solid  gray;" /> 
    </p>
    <p float="center">
        <img src="./img/05_uploading_files/upload_data.png" width="500" style="border: 2px solid  gray;" />
    </p>

    If the size of the data files is large (>100Mb), the  large file system package in Git is needed. To use this function for an upload, check the  `LFS` option:

    <p float="center">
        <img src="./img/05_uploading_files/lfs.png" width="500" style="border: 2px solid  gray;" />
    </p>




