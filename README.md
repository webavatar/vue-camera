# vue-camera
Vue Camera Component

## Usage
This component is designed to be usable by Vue browser version. To use follow below steps

- Include Vue v2.X required javascript browser version libraries
- Include the camera component in your index.html as source javascript
- Include the camera in any component in the components property
- Include the camera component in the template ( <camera v-on:photo-clicked="photoClicked"/>  )
- Add photo-clicked event listener on the camera component and get notified once camera is clicked
- The event will receive the image as a json containing imageData which is image url base64 encoded and the image type (image/png)
- Done !!!
