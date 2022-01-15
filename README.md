# Example asset repository

## What is an asset repository?

Game modes and maps uses assets like textures, skyboxes, sound effects and so on. An asset repository provides
these assets in asset collections.

## Which asset types exists?

1. crosshairs
2. fonts
3. icons
4. images
5. maps
6. models
7. skyboxes
8. sound effects
9. sound tracks
10. textures

## Why asset repositories?

Inexor can handle multiple repositories from different sources. Everyone can create its own repository. An
asset repository is basically a public git repository which follows a certain structure.

## What is the structure of an asset repository? 

This example repository provides a full example how an asset repository is structured.

The folder structure is as following:

<pre>
  /collections
    /name_of_the_collection
      /assets
        /crosshairs
          /name_of_the_crosshair
            crosshair.toml
        /fonts
          /name_of_the_font
            font.toml
        /images
          /name_of_the_image
            image.toml
        /icons
          /name_of_the_icon
            icon.toml
        /maps
          /name_of_the_map
            map.toml
        /models
          /name_of_the_model
            model.toml
        /skyboxes
          /name_of_the_skybox
            skybox.toml
        /sound_effects
          /name_of_the_sound_effect
            sound_effect.toml
        /sound_tracks
          /name_of_the_sound_track
            sound_track.toml
        /textures
          /name_of_the_texture
            texture.toml
</pre>

## What is the advantage of this structure?
 
* An asset repository can provide multiple asset collections
* An asset repository can provide multiple assets of each asset type
* A single asset can consist of multiple files (for example textures or skyboxes)
* Meta-information about the asset must be provided
* Extendable for future asset types
