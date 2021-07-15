# Stile gallery demo
Modeled in Blender.  
Webapp made with BabylonJS.

## Starting the web app
- run `npm install`
- run `node server.js`
- visit [localhost:80](localhost:80)

## Assets
Use [BabylonJS Blender exporter](https://github.com/BabylonJS/BlenderExporter) to generate the assets, following [these instructions](https://doc.babylonjs.com/extensions/Exporters/Blender).  
Place assets generated from Blender into `public/export` folder.  
The server looks for `export/GALLERY.babylon`.
