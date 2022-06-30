<h1 align="center">
  <a href="https://github.com/sdxqw/TCL-Java">TCL-MDK</a>
</h1>

<h4 align="center">TCL based on Tweaker Class and Mixins.</h4>

<h3 align="center">
    <a href="#get-start">Get start</a> •
     <a href="#building-with-optfine">Building With Optfine</a> •
    <a href="#key-features">Key Features</a> •
    <a href="#thanks">Thanks</a> •
    <a href="#contributing">Contributing</a> •
</h3>

## Get start

If you are here you need to setup our project!. Please follow this steps:

* Open the file "build.gradle"
* 1 - Change the line 26 with your group id ex: "io.github.axst"
* 2 - Change the line 19 with your tweaker name or client name (will be the most important part of this setup) (dont touch "mixins.")
* 3 - Change the line 18 "io.github.axst.launch.TCLTweaker" to your tweaker dir!
* 4 - Change the line 25 with your client version
* Open the file "mixins.tcl.json"
* 5 - Change the line 5 with your package where mixins should be.
* 6 - Change the line 6 "mixins.tcl.refmap.json" to "mixins.TWEAKER-OR-CLIENT-NAME-STEP-2.refmap.json" please use the tweaker or client name in step 2!
* 7 - Now the client should work! have fun learing mixins!
* 8 - If the client wont start make sure to set the package to MAIN and not API. (IJ IDEA)

## COMMON ERROR

if you get this error:

```java
TCL-Java:main:Could not find net.minecraft:minecraftBin:1.8.9.
```

click the gradle icon. gradle > forgegradle > SetupDecompWorkspace.
wait the procces finish, click refresh icon, and the error will be fixed.

## Building With Optfine

Today you gonna learn how to build an client!

!!!!!MAKE SURE TO HAVE OPTFINE INSTALLED!!!!!

follow those step:

* 1 Click this icon:
 
![image](https://user-images.githubusercontent.com/94248011/174458486-81236a8a-14af-440a-add3-9ab0b4d39cac.png)

* 2 task > build > jar
 
![image](https://user-images.githubusercontent.com/94248011/174458537-8fbf1386-6137-401a-b377-21062c3d32e6.png)

* 3 you should have the .jar for minecraft.

![image](https://user-images.githubusercontent.com/94248011/175834316-dffefe34-821a-4059-b0bc-3de7d0e3d193.png)

* 4 check ![CLICK ME](https://github.com/sdxqw/TCL-Java/blob/master/MyClient.json) and modify only this things:
* 1: rename the file to your client name.
* 1-2: "id" -> your client name.
* 2: "name": "myclient:MyClient:0.1" -> this its the folder and the jar should be name.
* the "myclient" -> its the folder for .minecraft/libraries.
* "Myclient:0.1" -> its where the .jar its located and how should be named like:

![image](https://user-images.githubusercontent.com/94248011/174458665-b5c9b301-8648-428f-927d-bee9c46c965c.png)

![image](https://user-images.githubusercontent.com/94248011/174458673-c3cb342e-25f0-4b8d-9486-26567894d507.png)

![image](https://user-images.githubusercontent.com/94248011/174458678-0638df0e-2546-4549-9a8e-edaf9b8cdae7.png)

![image](https://user-images.githubusercontent.com/94248011/174458688-04895a23-a776-43e1-9beb-4f0768ba02ca.png)

* 5 now make an folder with the name of your client like:

![image](https://user-images.githubusercontent.com/94248011/174458710-b81be596-42be-44ad-9099-edd96de659e7.png)

where put your MyClient.json like:

![image](https://user-images.githubusercontent.com/94248011/174458736-6b37d09b-4518-4bc9-a9f1-e9b5b0bae656.png)

* 7 put your "myclient" folder in "AppData\Roaming\.minecraft\libraries"
* 8 put your "My Client" folder in "AppData\Roaming\.minecraft\versions"
* 9 your done!, check in your minecraft client and should be the first.

## Key Features

* Good guide!
* 1.8.9 Optimized tcl for your client!
* Guide for build it with optfine. (LEGAL!)
* Example client!

# Thanks

thanks to xcfrg for repo!
thanks to TheKodeToad for his repo so i could fix mine

## Contributing

Want to help improve TCL-Java?, but how?:

* By making an fork of the project
* Sharing this repo
* Help improve the guide

---
<h6 align="center">
  | GitHub - <a href="https://github.com/sdxqw">@sdxqw</a> 
  |
</h6>
