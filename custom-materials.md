# Creating custom materials


## Rough notes
* You will need [VTFEdit](https://developer.valvesoftware.com/wiki/VTFEdit)
* Creating an image
    * Use an image editor of your choice
    * Make sure both the width and height are a power of 2
        * E.g. 128, 256, 512, 1024, 2048
    * Example resolutions
        * 1024x2048 (wide), 512x512 (square), 1024x512 (tall)
* Importing the image to the source engine
    * Open VTFEdit
    * Import your image
        * File -> Import -> Find your image
        * Resolution
            * Set the "Maximum Width" to your image width
            * Set the "Maximum Height" to your image height
        * Transparency
            * Set Alpha format to DXT5 to support transparency
            * If you don't need it, turn it off by setting Alpha format to DXT1
        * Use mipmaps if your texture will be viewed from different distances
    * Set required flags
        * On the left side, tick any relevant flags
        * See https://developer.valvesoftware.com/wiki/VTF_(Valve_Texture_Format)#Image_flags
    * Export the VTF file
        * File -> Save as
        * Save the file in the appropriate material folder
            * E.g. assets/materials/your_name/my_material.vtf
    * Export the VMT file
        * Tools -> Create VMT File
        * Make sure the "Base Texture 1" is set to the relative path of your material
            * E.g. your_name/my_material.vtf
        * Check the options
            * Set the surface 1 type
                * E.g. concrete
            * Enable translucent if your texture is transparent
            * See https://developer.valvesoftware.com/wiki/Category:List_of_Shader_Parameters
    * Copy these files into your gmod folder
        * Workshop addon, classic addon, materials folder, ...
        * E.g. gmod_folder/addons/myaddon/materials/your_name/
            * my_material.vtf
            * my_material.vmt


<br>

## More info
* VTF files- https://developer.valvesoftware.com/wiki/VTF_(Valve_Texture_Format)
* VMT files- https://developer.valvesoftware.com/wiki/Category:List_of_Shader_Parameters
