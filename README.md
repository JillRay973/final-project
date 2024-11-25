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
Class Critique (11/25) Feedback:
Lighting and Material Physically Based: probably requires exporting into another system.
Making Busts for Renders

Progress Made: Combined both parts to make generalized mesh to hair tool that can be modified to three different hair types: wavy, loose curls, and tight loc curls.

![wavybrownbun](https://github.com/user-attachments/assets/8735f3f8-2373-4684-b846-d18c36646a2c)
![wavyblondepony](https://github.com/user-attachments/assets/4649109c-20ae-45cd-9ece-7ad71fb4f56d)
![redcurlypony](https://github.com/user-attachments/assets/fdb9b5d7-7567-497d-b6be-b7517693ce9d)
![bunlocspurple](https://github.com/user-attachments/assets/2abe674f-5e3d-43d6-8a46-31d943cff965)

Link to 11/25 critique presentation: https://docs.google.com/presentation/d/1LpllukBR21gXvDsFZ9iFhl2O3g5xpQ6qLk-FhuubAMI/edit#slide=id.p

Left To Do:
- Possibly modify curling mechanism so rather than separate states, the straight to wavy to loose curl to tight curl is more of a spectrum that can be used on a sliding scale to create in between looks.
- Create bust heads in zBrush and export curled hair pieces to then make textured renders with dynamic lighting.
  
## Final submission (due 12/2)
Time to polish! Spen this last week of your project using your generator to produce beautiful output. Add textures, tune parameters, play with colors, play with camera animation. Take the feedback from class critques and use it to take your project to the next level.

Submission:
- Push all your code / files to your repository
- Come to class ready to present your finished project
- Update your README with two sections 
  - final results with images and a live demo if possible
  - post mortem: how did your project go overall? Did you accomplish your goals? Did you have to pivot?
