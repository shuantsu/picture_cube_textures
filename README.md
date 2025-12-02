# Cube Textures

## How to Clone the Repository

```bash
git clone https://github.com/shuantsu/picture_cube_textures.git
```

## How to Use TEXTURE_TEMPLATE.psd

Download the [TEXTURE_TEMPLATE.psd](./TEXTURE_TEMPLATE.psd) file which contains cube faces arranged in a cube net format (unfolded cube). These will be automatically saved using the appropriate option in Photoshop or Photopea by saving as named slices, as seen in the example folders that used this template to export cube textures.

![Texture Template Preview](./TEXTURE_TEMPLATE.png)

### Steps:
1. Open `TEXTURE_TEMPLATE.psd` in Photoshop or Photopea
2. Add your texture/image to each face of the cube net
3. Use "Export > Export As" or "Save for Web" with slice options
4. The named slices will automatically generate the individual face textures

The exported textures can then be used for cube mapping in your 3D applications.

## Example Configuration

See [example.json](./example.json) for a sample configuration showing how to reference the exported cube textures.

## Picture Cube Simulator

Try the [Picture Cube Simulator](https://filipeteixeira.com.br/new/picturecube/) to test your cube textures.