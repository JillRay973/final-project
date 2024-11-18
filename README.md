# Final Project!

Mesh to Hair Generator
---
### Design Doc:
https://docs.google.com/document/d/1r5VBZ0fsACgkfDzaMOe3No1-Vr6eTOwqbpKIuY9Kpcg/edit?usp=sharing

## Milestone 1: Implementation part 1 (due 11/13)

  Jill:
    Goal: Creating a Mesh to Hair generator in Houdini. Utilizing Meshes from Unreal Engine's Digital Human, as well as a custom mesh to test for generality, I utilized several resources and tutorials online to create a system that when inputting an fbx mesh generates guide curves, and from those guide curves generates hair splines that can be rendered like real hair! One important fact to note is that it is necessary for the mesh to be rather high in polygon/vertex count because the more edges, the more curves will be generated, and the more polished the hair will look in the final result. My further goals for the next milestone are to fiddle around with some more different types of meshes, including working with some metahuman meshes or more meshes from digital human, and then combining it with the procedural hair coils of my partner's part of the project. I also further generalized the pipeline so it works with any hair mesh fbx file.
    
![Screenshot 2024-11-13 123034](https://github.com/user-attachments/assets/64b3f9bf-08cf-4279-a490-8532c536d350)

![Screenshot 2024-11-13 123314](https://github.com/user-attachments/assets/aa5ea976-3c73-45a4-b16b-4763374c0ddb)


![Screenshot 2024-11-13 134225](https://github.com/user-attachments/assets/6c58c70f-4e2d-41fb-9a26-2f443059d859)


![Screenshot 2024-11-13 134913](https://github.com/user-attachments/assets/d7f8c94f-7990-4d8d-9c7f-1851f9ca4a96)

Clara: Documentation and description here: https://docs.google.com/document/d/1C57lQaYFIFPOGSd862Vk_UuKPzDx82gH-poj0TLbuiA/edit?usp=sharing


## Milestone 2: Implementation part 2 (due 11/25)
We're over halfway there! This week should be about fixing bugs and extending the core of your generator. Make sure by the end of this week _your generator works and is feature complete._ Any core engine features that don't make it in this week should be cut! Don't worry if you haven't managed to exactly hit your goals. We're more interested in seeing proof of your development effort than knowing your planned everything perfectly. 

Put all your code in your forked repository.

Submission: Add a new section to your README titled: Milestone #3, which should include
- written description of progress on your project goals. If you haven't hit all your goals, what did you have to cut and why? 
- Detailed output from your generator, images, video, etc.
We'll check your repository for updates. No need to create a new pull request.

Come to class on the due date with a WORKING COPY of your project. We'll be spending time in class critiquing and reviewing your work so far.

## Final submission (due 12/2)
Time to polish! Spen this last week of your project using your generator to produce beautiful output. Add textures, tune parameters, play with colors, play with camera animation. Take the feedback from class critques and use it to take your project to the next level.

Submission:
- Push all your code / files to your repository
- Come to class ready to present your finished project
- Update your README with two sections 
  - final results with images and a live demo if possible
  - post mortem: how did your project go overall? Did you accomplish your goals? Did you have to pivot?
