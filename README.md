# CNC-Mach3-BRAIL-Setup

## Setup Part Solid to Mastercam X5
```
* Setup part from solidwork and convert with save as to dxf, dwg, or parasolid xt.
```
![image](https://user-images.githubusercontent.com/97509777/149074474-7fa965d6-d57b-4cce-96fa-837053988031.png)
```
* Open the file from dxf to mastercam X5
```
## Contour Part 1
![image](https://user-images.githubusercontent.com/97509777/149075151-0d26460e-21b6-4885-a884-d9c4471ab592.png)
```
* Select Xform > Move to origin for determine zero point
```
![image](https://user-images.githubusercontent.com/97509777/149075324-38689c1c-f13a-4405-b43b-8cdb34800b9a.png)
![image](https://user-images.githubusercontent.com/97509777/149075428-3cdc2bdd-1679-4182-89df-762f9220a7d7.png)
```
* Select machine type > default to dispay machine group
```
![image](https://user-images.githubusercontent.com/97509777/149075538-70478245-7d12-4edd-9acc-b54c5b07328c.png)
![image](https://user-images.githubusercontent.com/97509777/149075627-5683fe53-acf6-4622-ab02-10b211023850.png)
```
* Select Stock Setup and determine Lenght, width and thickness material acording to part size
```
![image](https://user-images.githubusercontent.com/97509777/149075855-98ada61e-d93c-497f-8b0d-790de86a72a7.png)
```
* Click right on your mouse and then select Mill toolpath > Contour
```
![image](https://user-images.githubusercontent.com/97509777/149076333-157b73d6-ee06-4d7e-8b42-e3f95dc4b74f.png)
```
* Select the hole you want to make
```
![image](https://user-images.githubusercontent.com/97509777/149076546-f9d790f1-e394-4333-85e0-3d8cfdc46b20.png)
```
* Select Toolpath Type > Contour
```
![image](https://user-images.githubusercontent.com/97509777/149078092-47487b8d-2bae-4bce-915e-296bf97695d5.png)
```
* Select Tool and then you guys can create new tool with click right on your mouse and select endmill
```
![image](https://user-images.githubusercontent.com/97509777/149078353-cb56ae34-bd72-46c9-bd3d-998daef31e6a.png)
```
* Determine the size according to the endmill you have, like in a picture i am set size 4 mm
```
![image](https://user-images.githubusercontent.com/97509777/149081239-b0fa8ea2-b693-405f-94f0-e5a20e79dd57.png)
```
* Determine the feed rate, plunge rate and spindle speed according machine type
```
![image](https://user-images.githubusercontent.com/97509777/149081576-2c5387d7-cee2-423c-a437-1eb1d463cb1e.png)
```
* Select Lead in/out for deactivated check box
```
![image](https://user-images.githubusercontent.com/97509777/149082231-bd015c6d-4ef2-443d-ab77-5a0ec2752af0.png)
```
* Select depth cut and then activated check box and set max rough step according to you, in this picture i set 0.2 mm and finish step 0 mm
```
![image](https://user-images.githubusercontent.com/97509777/149082662-f859a30d-d3f2-4424-8029-b812dca46419.png)
```
* Select Linking parameters and change/select incremental to absolute and then set retract, feed plane, top of stock, depth according material part 
```
![image](https://user-images.githubusercontent.com/97509777/149083052-52a2b80c-47cf-451a-8301-34e0d0363b53.png)
```
* NB : if you get the case like this picture, you can select Parameters > cut parameter and then change left to right or right to left and then debug that file or confirmation with cheklist like a picture 3
```
![image](https://user-images.githubusercontent.com/97509777/149083527-a87ef33b-0555-46fc-9da7-e972eac93d29.png)
![image](https://user-images.githubusercontent.com/97509777/149083703-194963f3-8140-4b6d-842d-3b7fce173acc.png)
![image](https://user-images.githubusercontent.com/97509777/149085687-00a0126c-7985-4859-9a39-283b97dd95ca.png)
![image](https://user-images.githubusercontent.com/97509777/149084415-2e1aa217-cf4d-429c-8838-4ae6b44a085a.png)
![image](https://user-images.githubusercontent.com/97509777/149084428-004b406c-087a-43e4-a4b4-058119683318.png)

## Make G-code
```
* Select like in a picture from your mastercam
```
![image](https://user-images.githubusercontent.com/97509777/149085852-a9e0feb8-30cf-4458-b8c7-af663dd299d4.png)
```
* remove the program as in the tagged photo
```
![image](https://user-images.githubusercontent.com/97509777/149086093-3af162ea-3a61-4ea6-87f6-113316b0d06d.png)
![image](https://user-images.githubusercontent.com/97509777/149086134-310f61fa-c768-425b-b722-2e2551984118.png)
![image](https://user-images.githubusercontent.com/97509777/149086174-6698bf3f-7750-4a7f-a238-6f00eb40eb50.png)
![image](https://user-images.githubusercontent.com/97509777/149086223-fa0486ac-f79b-4e63-897f-48b4e3fbf0e4.png)
![image](https://user-images.githubusercontent.com/97509777/149086253-461a0776-d5b0-4c06-945d-b551aca272e2.png)
![image](https://user-images.githubusercontent.com/97509777/149086273-9fa855de-f0f9-400c-88cc-4841b90415e3.png)
![image](https://user-images.githubusercontent.com/97509777/149086310-f953fc89-e550-4638-a3a2-5b64a24ca7d0.png)
![image](https://user-images.githubusercontent.com/97509777/149086350-ad9df2d9-c912-43c4-b973-c023f99cdde9.png)

```
NB : every machine has programs that are removed and added and it's different for each machine
```
```
* Click like in a picture for preview result
```
![image](https://user-images.githubusercontent.com/97509777/149089074-22605218-f240-4dae-93c8-7704f863e87f.png)
![image](https://user-images.githubusercontent.com/97509777/149089100-f2e0178c-09ae-4d27-b32e-c6d83e43e9ec.png)

## Contour Part 2 

```
* So in the second part it's the same as the first part, only the outside is contoured like in the photo
```
![image](https://user-images.githubusercontent.com/97509777/149089933-2661479a-bf1d-4fa5-9d34-5a4cafc7e52b.png)
```
NB : for the selection of the size of the endmill, it must be in accordance with the provisions and needs, so here I can not explain in detail, because this is only my understanding for this manufacture, you can learn more from lecturers or seniors who understand more, and also you can see the cnc archives that have been made. I made it, you can see what size endmill I have used, for the file you can download at the top
```


















