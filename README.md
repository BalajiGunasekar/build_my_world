# build_my_world

Repository Structure

    .build_my_world                    # Build My World Project 
    ├── model                          # Model files 
    │   ├── house
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── mobile_robot
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # C++ Plugin script      
    │   ├── message.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── office_world.world
    ├── CMakeLists.txt                 # Link libraries 
    └──       
    
## Project Aspects
 Build Gazebo world where I can identify:
* Office Enivorment : A building model designed on the Building Editor tool of Gazebo. The structure contains features, and colors.
* Mobile Robot: A model of Kuka youbot model imported in Model Editor  from Gazebo online Library.
* Tables: A model imported from the Gazebo online library.
* Result in Terminal: A welcome message generated from plugin script printedin terminal.

### My Output



*Office_world.world*

![Screenshot from 2022-06-16 23-45-32](https://user-images.githubusercontent.com/50603442/174171681-b53b9f83-b171-4f37-865d-4647ce50ece0.png)



*Office world Features*

![Screenshot from 2022-06-16 23-44-50](https://user-images.githubusercontent.com/50603442/174172150-f6e17f1a-1d27-4366-bb02-e886be2ea067.png)



*Robot Model*
![Screenshot from 2022-06-16 23-54-21](https://user-images.githubusercontent.com/50603442/174185302-48c2ce88-15b0-435b-b5ab-9c3649a6fe4f.png)



### Key Takeaways

* Understanding of Gazebo Building Editor and its tool to develop a Building model
* Model Editior utilisation in custom modelling of model and it Online 
* Precise Underdatnding of structure of Model with .sdf and .config files
* Modeleing World with created Models and Building 
