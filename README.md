# vulkan
Vulkan learning

1. when vkCreateInstance, encout `VK_ERROR_INCOMPATIBLE_DRIVER`?
Solution:
add extension nane `VK_KHR_PORTABILITY_ENUMERATION_EXTENSION_NAME` does not work.
Then we just need add libMotltenVK.dylib to our `Link Binary with Libraries` and `Copy Files` in Build Phases.
