# FEZ (Finite Element Zurich)
[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://join.slack.com/t/finiteelementzurich/shared_invite/zt-npk1si4j-2~Cew80JO~DMxe5undnUpA)     
[![Website Link](https://img.shields.io/badge/FEZ-website-brightgreen)](https://fez-finite-element-zurich.github.io/)



# Vision Statement

Our vision is to create a virtual hub to share modeling workflows for finite element analysis (a modeling method used in biomechanics research). Our website will serve as a place to learn methods (including open access alternatives to commercial software) and form collaborations. The main goal is to form a finite element analysis community across various institutions and disciplines, and to increase access to this modeling methodology. 


# Instructions for Contributors  

*We welcome contributions of workflows for any stage of the finite element modeling process (including creating initial 3D models)! If you have any questions about using github to upload your workflow, please [email us](fezurich@gmail.com).

## Steps to contribute workflows:
1. Create github account   

2. Request membership to the FEZ Github organisation by creating a new Issue in this repository. In the Issue, write up your name and what you work on (just a few words, we're curious!) and a brief description of what you want to contribute. We'll accept all relevant contributions, this step is just for us to know who is contributing and what they are contributing and grant membership. Once we send you an invitation, you need to accept it (there should be an invite notification showing up on the github organisation when you look at that page. This is important because without accepting the invitation you will be unable to contribute workflows. Please ask us if you have any questions!

3. Make a repository for your workflow   
  - One repository can contain several documents, for example code, instructions (as a markdown file or PDF), etc  

4. When you create the repository, create a README.md file. This will be a summary of your workflow or technique. You can also include the protocol steps directly in the README file. This is also where you can credit other contributors of the workflow and link to papers and datasets. See [here](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax) for some tips on how to format text in .md documents.
  - Add this button to the top of your repository to show that it is part of the FEZ initiative! [![FEZ](https://img.shields.io/badge/FEZ-contributor-brightgreen)](https://github.com/FEZ-Finite-Element-Zurich). To add this, paste this code into the top of your README file (take out the spaces in between the different brackets): [![FEZ] (https://img.shields.io/badge/FEZ-contributor-brightgreen)] (https://github.com/FEZ-Finite-Element-Zurich)

5. Add the workflow/protocol. Workflow instructions can be added as different document types depending on whether you want them to be able to be updated. 
  - If you want people (including future you!) to be able to suggest updates to your protocol, you can add the workflow as a Github .md document (as part of your README file or a separate .md file). 
  - If you prefer, you can upload a PDF of your workflow (but any future changes will then require you to re-make the PDF).
  
6. Upload any code as separate documents.

7. Add a LICENSE.md file. Choose a license [here](https://choosealicense.com/) based on how you want the workflow to be used (e.g. are people allowed to modify it? How should they cite it?). Once you pick a license, create a new document in your repository titled "LICENSE.md" and 
  
8. Format your repository for indexing on our website  
  - We will link to all workflows via our website. *This section is in progress - for now, please add your name and a brief summary or keywords to the description, and we might re-format these in the future to ensure a more uniform format*
 
9. Once membership to the organisation is granted, fork your repository to Fez-Finite-Element-Zurich (on your repository, click the fork button in the top right hand corner, and select the FEZ organisation as the place you want to fork to. It will then show up both on your Github account and on the FEZ organisation, and will automatically show up on our website under the list of resources. 

____
## FEA Freeware (including for segmentation, surface mesh manipulation, tetrameshing, analysis)
*All of these are free resources except in some cases for Dragonfly

- [3D Slicer](https://www.slicer.org/): segmentation
- [Dragonfly](https://www.theobjects.com/dragonfly/get-non-commercial-licensing-program.html): segmentation, free non-commercial licenses except in certain regions
- [MITK-GM](https://araex.github.io/mitk-gem-site/): segmentation using GraphCut, surface mesh and tetrahedral mesh generation
- [MeshLab](https://www.meshlab.net/): surface mesh cleaning
- [Blender](https://www.blender.org/): surface mesh cleaning, assembling bones, creating hypothetical geometries, etc
- [TetGen](http://wias-berlin.de/software/tetgen/): tetrahedral mesh generator
- [Gibbon](https://github.com/gibbonCode/GIBBON): segmentation, surface meshing, TetGen for tetrahedral meshing, FE analaysis with FEBio, Matlab based
- [FEBio](https://github.com/Kevin-Mattheus-Moerman/febio2): finite-element analysis developed for biomechanics, uses uses TetGen for tetrahedral meshing
- [ArtiSynth](https://www.artisynth.org/Main/HomePage): finite element and multi-body dynamics analyses developed for biomechanics, uses TetGen for tetrahedral meshing, Java based

## Other Resources
- [**Funky Morph Users Group**](https://github.com/FunkyMUG/FunkyMUG) hosts interactive workshops for learning new open access techniques for biomechanics and morphology research
- Preprint ["How to get meaningful and correct results fromyour finite element model" - Martin Bäker](https://www.researchgate.net/publication/328956103_How_to_get_meaningful_and_correct_results_from_your_finite_element_model)
- For even more resources, check out this [awesome curated list by Luca Modenese](https://github.com/modenaxe/awesome-biomechanics) for all sorts of tools for biomechanics (not just limited to FEA!)
