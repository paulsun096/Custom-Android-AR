<h3>Upload Custom .obj models into Android AR</h3>

AR-Shibuya is based on: https://developers.google.com/ar/develop/java/sceneform/import-assets

- import the art assets as (single .obj file, no texture) into the sceneform sample project using the sceneform android plugin.
- convert .obj -> .sbf 
- replace Uri.parse value to the custom .sfb file
![](custom_obj.png)



Dependencies: 
- Android SDK
- Sceneform android plugin

Result using custom .obj model: @takaarts

![](ARGif.gif)





