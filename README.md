# vulkan learning
### problem 1: when vkCreateInstance, encouter `VK_ERROR_INCOMPATIBLE_DRIVER`?
**Solution**:add extension nane `VK_KHR_PORTABILITY_ENUMERATION_EXTENSION_NAME` does not work.<br>
Just need to add libMotltenVK.dylib to our `Link Binary with Libraries` and `Copy Files` in Build Phases.
