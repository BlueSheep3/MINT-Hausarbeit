# Culling

- first implementation
  - basics: for all voxels: cull
  - split into chunks
    - problem with sending over for async
    - (might mention single chunk data, not sure because you will probably always need to send it over for voxel textures)
    - (could of course already optimize boundary data, but kinda useless)
- transition to binary culling
  - find faces faster
  - send over less boundary data
  - probably include some code


# Greedy Meshing

- todo


# Other

- figure out how textures are even possible
  - should this really be in the Greedy Meshing section?
- exact benchmarks
  - wait for bevy 0.15 first, as that will have general performance changes
- thicker outlines in all images
- definetly include actual code somewhere
  - but where?
  - code is usually very long => hard to include
