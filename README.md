# Measuring-the-strength-of-a-metal-cube-by-Comsol
This is a training task to learn "how to use COMSOL Multiphysics"

## Start

![Screenshot_131](https://github.com/user-attachments/assets/a5eac54f-da32-4e6c-b192-a043f1cdc8d6)

Choose "Model Wizard"

Choose 3d

![Screenshot_131](https://github.com/user-attachments/assets/4ef441f2-f249-4d9c-aee7-e7f5ff5cd016)

![Screenshot_131](https://github.com/user-attachments/assets/271b5edf-f7bf-453a-be04-349a67088cf6)

Stationary

![Screenshot_134](https://github.com/user-attachments/assets/7e8fb9b9-4a71-4824-974a-59441e953580)

Give a name for geometry - "Block 1"

![Screenshot_136](https://github.com/user-attachments/assets/b682e80b-cb4a-4719-be1e-31816a114a4d)

Create a model of block

![Screenshot_137](https://github.com/user-attachments/assets/13086422-6256-40a1-88e7-c3e54f163b14)

By default, the units of measurement are meters, but we need millimeters.

![Screenshot_138](https://github.com/user-attachments/assets/4c4b4b44-d0e2-42e7-8fae-5a22f989216a)

changing the units of measurement. in 6.x v in model builder

![Screenshot_140](https://github.com/user-attachments/assets/d875fed4-38f5-4038-810a-eb637850c997)

setting the measurement parameters: 10*10*80 mm, solid, corner, Cartesian coordinate system, xy-working plane

![Screenshot_143](https://github.com/user-attachments/assets/356c4cf1-ef10-4c5f-a91f-15ca97bae996)

build a model

![Screenshot_142](https://github.com/user-attachments/assets/295db9cf-a359-4db5-acf2-df1caaa52ab3)

We have a new model. Zoom out to see it better.

![Screenshot_144](https://github.com/user-attachments/assets/554fe9be-220a-49c3-9a3e-f0b5db33ea10)

add material

![Screenshot_145](https://github.com/user-attachments/assets/682fdbb4-4845-47ff-b165-84079b41b855)

in the window on the right, select aluminum alloys.

![Screenshot_146](https://github.com/user-attachments/assets/83f4d660-9e60-4b4e-8b97-23af65b8fc54)

6061/solid/T6/temper

![Screenshot_147](https://github.com/user-attachments/assets/b3ea096f-110a-4c69-ae65-fe2cc5d9df32)

select "boundary" and choose it in model (need red color)

![Screenshot_148](https://github.com/user-attachments/assets/4b4fc17f-5cd9-40eb-b692-fc91c97cd889)

add physics

![Screenshot_149](https://github.com/user-attachments/assets/5e55302b-933b-4749-9d04-f433f3dbce98)

in "solid mechanics" (left side) choose a "Fixed Constrait"

![Screenshot_150](https://github.com/user-attachments/assets/609b7ee7-794c-4adf-8af0-2928dabebd8c)

then we select the part of the model that should be fixed (stationary). click on it to turn it blue.

![Screenshot_151](https://github.com/user-attachments/assets/3b68870d-e5c4-4188-8edb-693f8f6c4917)

then, in the "Solid Physics" field on the left, select the load.

![Screenshot_152](https://github.com/user-attachments/assets/25c816de-5b07-4bf5-a93a-b1ff6333397b)

we select the load level (in our case 100 Newtons) along the "y" axis. on the model, select the area where the load will be applied and click on it to turn it blue

![Screenshot_154](https://github.com/user-attachments/assets/18abf384-3125-4134-b4a7-d3a5c2b8a2a2)

in the "mesh" field on the left, click "build all". Please note that I clicked "solid mechanics 2" by mistake. If you do too, just uncheck it.

![Screenshot_156](https://github.com/user-attachments/assets/b07597fb-e54f-4aa8-926c-c51e59ebb792)

You can select "extra fine" as the element size to make the measurement more accurate. click "build all" again and see how the number of polygons on our model has increased.

![Screenshot_157](https://github.com/user-attachments/assets/86feace6-1d49-4bef-a791-8c181f67952a)

in the "global definitions" field on the left, select "load..." and "load group"

![Screenshot_158](https://github.com/user-attachments/assets/aadc578f-2123-4f86-9c21-476ceeb45a6b)

in the menu on the left, select "study"/stationary, then "add"

![Screenshot_159](https://github.com/user-attachments/assets/fffb2c24-7e73-43f4-9806-73c78e4c811f)

let's move on to the simulation itself

let's add a check mark in define load cases in the study/stationary and select our case (next 2 screenshots).

![Screenshot_161](https://github.com/user-attachments/assets/fa904455-e732-476c-8f21-a5236cabde3c)



![Screenshot_160](https://github.com/user-attachments/assets/2ed87a2f-1cab-40f6-94d3-8bd1542ecd01)

Weight is our load factor (load * weight)

choose "compute"

![Screenshot_162](https://github.com/user-attachments/assets/f525a19d-8c5c-4844-81a1-caf1dad27904)

Error, something goes wrong...






































