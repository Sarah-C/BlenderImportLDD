# Blender Import LDD
-----------------------

Blender Lego Digital Designer importer.                    
For Blender 3.6 / 4.0

How to use:          
-----------
1: Download the BlenderImportLDD.py file to your desktop.           
2: In Blender, follow the process of importing a new plugin:            
... Go into the Blender preferences, either by clicking on Main Header>Edit>Preferences or by changing an editor type to 'preferences'.            
... Go to the 'Add-ons' category, and click on the 'Install...' button to install a new addon.               
... Choose the BlenderImportLDD.py file on your desktop, and click "Install Addon" button.            
... Click the empty box that appears along with "Import-Export: Import LEGO Digital Designer, this enables the plugin.               
... The option is now in the Import menu, see the image below.                        

Changes:          
--------
1: I've tweaked the old importer to combine the same materials, and export the decorations properly - it had started to error.              

2: Materials can be split if needed in Blender, but means all of the same material can be tweaked at once - much faster!          

3: Materials are also now named rather than just numbered.         

4: Bricks have their full name too.            

Where to find the new option:            
![image](https://github.com/Sarah-C/BlenderImportLDD/assets/1586332/dbd3ce95-15fa-4206-a2a9-24c5fc822d0a)                   
                 
Images still need a mixShader to enable correct alpha blending, as shown below:            
![image](https://github.com/Sarah-C/BlenderImportLDD/assets/1586332/c1283ae4-eb70-4c06-8c5d-97988f737f0d)               
               
Example scene:            
![image](https://github.com/Sarah-C/BlenderImportLDD/assets/1586332/aa122c7d-c3cf-4d47-b6fd-c30708ac9b23)                
                   
Example backlit scene:           
Transparent : 0.5       
Internal Transparent Roughness : 0.4                
![G__Plugins_Blender_BlenderImportLDD_sceneBacklit](https://github.com/Sarah-C/BlenderImportLDD/assets/1586332/2df3dc20-0772-4b7f-a3f1-e19c7c9f89fe)
