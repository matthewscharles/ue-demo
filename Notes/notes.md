# Dynamic Footstep Demo

- To extend the existing foley in the Game Animation Sample project to incorporate other surface materials, while maintaining compatibility with the original project.

## Methods
The original project uses a data asset to store MetaSound presets retrievable by gameplay tag. I have extended this model to fetch variations for different surfaces underfoot.

## Advantages
- Separation of logic from data
- Extendable for multiple parameters

## Limitations
- Adding surfaces can be time-consuming, since the Default parameter musr be re-assigned.

## Notes
- Submix sends also need to be modified through any MetaSound Source presets.