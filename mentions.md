# All Files that mention Vortek

Here are all mentions of Vortek in the APK (including xz-ed or zstd-ed tars as well)

## vortek-1.0.tzst/usr/lib/libvulkan_vortek.so

```bash
$ nm usr/lib/libvulkan_vortek.so
    000000000003d5a0 T ArrayDeque_addFirst
    000000000003d5d0 T ArrayDeque_addLast
    000000000003d664 T ArrayDeque_free
    000000000003d530 T ArrayDeque_init
    000000000003d584 T ArrayDeque_isEmpty
    000000000003d600 T ArrayDeque_removeFirst
    000000000003d634 T ArrayDeque_removeLast
    000000000003cbb4 T ArrayList_add
    000000000003cce0 T ArrayList_free
    000000000003cd50 T ArrayList_fromStrings
    000000000003cb74 T ArrayList_indexOf
    000000000003cca0 T ArrayList_remove
    000000000003cc30 T ArrayList_removeAt
    000000000003d230 T ArrayMap_free
    000000000003d140 T ArrayMap_get
    000000000003cdc0 T ArrayMap_indexOfKey
    000000000003d010 T ArrayMap_indexOfValue
    000000000003d054 T ArrayMap_put
    000000000003d1f4 T ArrayMap_remove
    000000000003d180 T ArrayMap_removeAt
    0000000000060220 B clientRing
    000000000003d6d0 T DescriptorUpdateTemplate_create
    000000000003d804 T DescriptorUpdateTemplate_fillDescriptorWrites
    000000000003d7d0 T DescriptorUpdateTemplate_free
    000000000003c884 T IntArray_add
    000000000003c8f4 T IntArray_addAll
    000000000003cb10 T IntArray_clear
    000000000003ca50 T IntArray_remove
    000000000003cb50 T IntArray_sort
    0000000000060260 B memoryPools
    0000000000060230 B memoryPoolsMutex
    000000000003dcd0 T RingBuffer_create
    000000000003dd90 T RingBuffer_free
    000000000003da00 T RingBuffer_freeSpace
    000000000003dcc0 T RingBuffer_getSHMemSize
    000000000003d9c0 T RingBuffer_hasStatus
    000000000003da24 T RingBuffer_read
    000000000003d980 T RingBuffer_setStatus
    000000000003d9d4 T RingBuffer_size
    000000000003d9a0 T RingBuffer_unsetStatus
    000000000003db70 T RingBuffer_write
    0000000000060210 D serverFd
    0000000000060228 B serverRing
    000000000003d430 T SparseArray_get
    000000000003d2a0 T SparseArray_indexOfKey
    000000000003d300 T SparseArray_indexOfValue
    000000000003d344 T SparseArray_put
    000000000003d4f0 T SparseArray_remove
    000000000003d470 T SparseArray_removeAt
    000000000003c500 T vk_icdGetInstanceProcAddr
    000000000003c590 T vk_icdNegotiateLoaderICDInterfaceVersion
    000000000003c5b0 T VkObject_create
    000000000003c780 T VkObject_free
    000000000003c754 T VkObject_fromHandle
    000000000003c750 T VkObject_fromId
    000000000003c704 T VkObject_toHandle
    0000000000009b60 T vortekInitOnce
    0000000000010990 T vt_call_vkAcquireNextImage2KHR
    000000000001c730 T vt_call_vkAcquireNextImageKHR
    0000000000026430 T vt_call_vkAllocateCommandBuffers
    0000000000031b94 T vt_call_vkAllocateDescriptorSets
    0000000000024e80 T vt_call_vkAllocateMemory
    0000000000032ef4 T vt_call_vkBeginCommandBuffer
    0000000000037f80 T vt_call_vkBindBufferMemory
    0000000000009e74 T vt_call_vkBindBufferMemory2
    0000000000037c60 T vt_call_vkBindImageMemory
    0000000000010980 T vt_call_vkBindImageMemory2
    000000000000c400 T vt_call_vkCmdBeginConditionalRenderingEXT
    0000000000013084 T vt_call_vkCmdBeginQuery
    000000000000d210 T vt_call_vkCmdBeginQueryIndexedEXT
    00000000000136e4 T vt_call_vkCmdBeginRendering
    0000000000014410 T vt_call_vkCmdBeginRenderPass
    0000000000014540 T vt_call_vkCmdBeginRenderPass2
    0000000000016d70 T vt_call_vkCmdBeginTransformFeedbackEXT
    0000000000010074 T vt_call_vkCmdBindDescriptorSets
    000000000000bab0 T vt_call_vkCmdBindIndexBuffer
    000000000000b1d0 T vt_call_vkCmdBindPipeline
    000000000000f570 T vt_call_vkCmdBindTransformFeedbackBuffersEXT
    0000000000016be0 T vt_call_vkCmdBindVertexBuffers
    000000000000f340 T vt_call_vkCmdBindVertexBuffers2
    000000000000fde4 T vt_call_vkCmdBlitImage
    000000000000e510 T vt_call_vkCmdBlitImage2
    00000000000125b0 T vt_call_vkCmdClearAttachments
    000000000000f970 T vt_call_vkCmdClearColorImage
    000000000000f754 T vt_call_vkCmdClearDepthStencilImage
    000000000000bf60 T vt_call_vkCmdCopyBuffer
    000000000000e060 T vt_call_vkCmdCopyBuffer2
    0000000000010c70 T vt_call_vkCmdCopyBufferToImage
    0000000000010a00 T vt_call_vkCmdCopyBufferToImage2
    0000000000010ed0 T vt_call_vkCmdCopyImage
    000000000000e270 T vt_call_vkCmdCopyImage2
    000000000000fb84 T vt_call_vkCmdCopyImageToBuffer
    000000000000e794 T vt_call_vkCmdCopyImageToBuffer2
    000000000000c6f4 T vt_call_vkCmdCopyQueryPoolResults
    000000000000beb0 T vt_call_vkCmdDispatch
    000000000000cd40 T vt_call_vkCmdDispatchBase
    0000000000011160 T vt_call_vkCmdDispatchIndirect
    000000000000bbd4 T vt_call_vkCmdDraw
    000000000000bc94 T vt_call_vkCmdDrawIndexed
    000000000000bd70 T vt_call_vkCmdDrawIndexedIndirect
    000000000000d060 T vt_call_vkCmdDrawIndexedIndirectCount
    00000000000119b0 T vt_call_vkCmdDrawIndirect
    000000000000d474 T vt_call_vkCmdDrawIndirectByteCountEXT
    0000000000012db0 T vt_call_vkCmdDrawIndirectCount
    000000000000c540 T vt_call_vkCmdEndConditionalRenderingEXT
    00000000000131b0 T vt_call_vkCmdEndQuery
    000000000000d350 T vt_call_vkCmdEndQueryIndexedEXT
    000000000000f004 T vt_call_vkCmdEndRendering
    000000000000cae0 T vt_call_vkCmdEndRenderPass
    000000000000cf60 T vt_call_vkCmdEndRenderPass2
    0000000000011814 T vt_call_vkCmdEndTransformFeedbackEXT
    000000000000cb70 T vt_call_vkCmdExecuteCommands
    000000000000c2c0 T vt_call_vkCmdFillBuffer
    000000000000ca50 T vt_call_vkCmdNextSubpass
    000000000000ce20 T vt_call_vkCmdNextSubpass2
    0000000000014b70 T vt_call_vkCmdPipelineBarrier
    0000000000017724 T vt_call_vkCmdPipelineBarrier2
    000000000000c8c0 T vt_call_vkCmdPushConstants
    0000000000016630 T vt_call_vkCmdPushDescriptorSetKHR
    0000000000015bc0 T vt_call_vkCmdPushDescriptorSetWithTemplateKHR
    00000000000133f0 T vt_call_vkCmdResetEvent
    000000000000edc0 T vt_call_vkCmdResetEvent2
    0000000000012f60 T vt_call_vkCmdResetQueryPool
    00000000000146a0 T vt_call_vkCmdResolveImage
    000000000000ea00 T vt_call_vkCmdResolveImage2
    000000000000b740 T vt_call_vkCmdSetBlendConstants
    000000000000eca0 T vt_call_vkCmdSetColorWriteEnableEXT
    000000000000d680 T vt_call_vkCmdSetCullMode
    000000000000b680 T vt_call_vkCmdSetDepthBias
    000000000000df40 T vt_call_vkCmdSetDepthBiasEnable
    000000000000b7f0 T vt_call_vkCmdSetDepthBounds
    000000000000dcc4 T vt_call_vkCmdSetDepthBoundsTestEnable
    000000000000dc34 T vt_call_vkCmdSetDepthCompareOp
    000000000000db14 T vt_call_vkCmdSetDepthTestEnable
    000000000000dba4 T vt_call_vkCmdSetDepthWriteEnable
    000000000000ccb0 T vt_call_vkCmdSetDeviceMask
    00000000000132d0 T vt_call_vkCmdSetEvent
    0000000000017300 T vt_call_vkCmdSetEvent2
    000000000000d710 T vt_call_vkCmdSetFrontFace
    000000000000d5d4 T vt_call_vkCmdSetLineStippleEXT
    000000000000b5e0 T vt_call_vkCmdSetLineWidth
    000000000000dfd0 T vt_call_vkCmdSetPrimitiveRestartEnable
    000000000000d7a0 T vt_call_vkCmdSetPrimitiveTopology
    000000000000deb0 T vt_call_vkCmdSetRasterizerDiscardEnable
    00000000000169c0 T vt_call_vkCmdSetSampleLocationsEXT
    000000000000b470 T vt_call_vkCmdSetScissor
    000000000000d9b0 T vt_call_vkCmdSetScissorWithCount
    000000000000b8a0 T vt_call_vkCmdSetStencilCompareMask
    000000000000dde4 T vt_call_vkCmdSetStencilOp
    000000000000ba00 T vt_call_vkCmdSetStencilReference
    000000000000dd54 T vt_call_vkCmdSetStencilTestEnable
    000000000000b950 T vt_call_vkCmdSetStencilWriteMask
    000000000000b2e4 T vt_call_vkCmdSetViewport
    000000000000d830 T vt_call_vkCmdSetViewportWithCount
    000000000000c150 T vt_call_vkCmdUpdateBuffer
    0000000000014f70 T vt_call_vkCmdWaitEvents
    0000000000016f00 T vt_call_vkCmdWaitEvents2
    000000000000c5d0 T vt_call_vkCmdWriteTimestamp
    000000000000eee0 T vt_call_vkCmdWriteTimestamp2
    000000000001f260 T vt_call_vkCreateBuffer
    000000000001ad90 T vt_call_vkCreateBufferView
    00000000000393a0 T vt_call_vkCreateCommandPool
    0000000000033900 T vt_call_vkCreateComputePipelines
    0000000000035240 T vt_call_vkCreateDescriptorPool
    0000000000026bd0 T vt_call_vkCreateDescriptorSetLayout
    0000000000017b40 T vt_call_vkCreateDescriptorUpdateTemplate
    0000000000019dd0 T vt_call_vkCreateDevice
    0000000000038670 T vt_call_vkCreateEvent
    0000000000023290 T vt_call_vkCreateFence
    0000000000027004 T vt_call_vkCreateFramebuffer
    0000000000028c84 T vt_call_vkCreateGraphicsPipelines
    00000000000267c4 T vt_call_vkCreateImage
    000000000001dd44 T vt_call_vkCreateImageView
    000000000002a844 T vt_call_vkCreateInstance
    000000000001ca04 T vt_call_vkCreatePipelineCache
    0000000000028190 T vt_call_vkCreatePipelineLayout
    0000000000010940 T vt_call_vkCreatePrivateDataSlot
    000000000003a9e0 T vt_call_vkCreateQueryPool
    000000000003b7b4 T vt_call_vkCreateRenderPass
    0000000000036470 T vt_call_vkCreateRenderPass2
    0000000000022100 T vt_call_vkCreateSampler
    000000000001b040 T vt_call_vkCreateSamplerYcbcrConversion
    0000000000028880 T vt_call_vkCreateSemaphore
    000000000001bfa0 T vt_call_vkCreateShaderModule
    0000000000025424 T vt_call_vkCreateSwapchainKHR
    0000000000009eb4 T vt_call_vkCreateXlibSurfaceKHR
    0000000000021ef0 T vt_call_vkDestroyBuffer
    00000000000218c0 T vt_call_vkDestroyBufferView
    0000000000021ce0 T vt_call_vkDestroyCommandPool
    0000000000025a60 T vt_call_vkDestroyDescriptorPool
    0000000000021ad0 T vt_call_vkDestroyDescriptorSetLayout
    0000000000017640 T vt_call_vkDestroyDescriptorUpdateTemplate
    0000000000020420 T vt_call_vkDestroyDevice
    0000000000021290 T vt_call_vkDestroyEvent
    000000000001f9d0 T vt_call_vkDestroyFence
    000000000001f7c0 T vt_call_vkDestroyFramebuffer
    0000000000020000 T vt_call_vkDestroyImage
    000000000001fbe0 T vt_call_vkDestroyImageView
    0000000000021080 T vt_call_vkDestroyInstance
    0000000000020a50 T vt_call_vkDestroyPipeline
    0000000000020840 T vt_call_vkDestroyPipelineCache
    00000000000214a0 T vt_call_vkDestroyPipelineLayout
    00000000000109d4 T vt_call_vkDestroyPrivateDataSlot
    0000000000020c60 T vt_call_vkDestroyQueryPool
    0000000000020210 T vt_call_vkDestroyRenderPass
    000000000001f5b4 T vt_call_vkDestroySampler
    0000000000020630 T vt_call_vkDestroySamplerYcbcrConversion
    000000000001fdf0 T vt_call_vkDestroySemaphore
    0000000000020e70 T vt_call_vkDestroyShaderModule
    000000000000ae60 T vt_call_vkDestroySurfaceKHR
    00000000000216b0 T vt_call_vkDestroySwapchainKHR
    0000000000031694 T vt_call_vkDeviceWaitIdle
    0000000000017c44 T vt_call_vkEndCommandBuffer
    00000000000242b0 T vt_call_vkEnumerateDeviceExtensionProperties
    0000000000009e30 T vt_call_vkEnumerateDeviceLayerProperties
    000000000001ebf0 T vt_call_vkEnumerateInstanceExtensionProperties
    0000000000009e20 T vt_call_vkEnumerateInstanceLayerProperties
    0000000000018494 T vt_call_vkEnumerateInstanceVersion
    0000000000022774 T vt_call_vkEnumeratePhysicalDeviceGroups
    000000000001da14 T vt_call_vkEnumeratePhysicalDevices
    000000000003ad50 T vt_call_vkFlushMappedMemoryRanges
    0000000000037930 T vt_call_vkFreeCommandBuffers
    0000000000035dc0 T vt_call_vkFreeDescriptorSets
    0000000000023c50 T vt_call_vkFreeMemory
    0000000000032c64 T vt_call_vkGetBufferDeviceAddress
    0000000000024090 T vt_call_vkGetBufferMemoryRequirements
    00000000000198e4 T vt_call_vkGetBufferMemoryRequirements2
    0000000000032740 T vt_call_vkGetBufferOpaqueCaptureAddress
    000000000001c250 T vt_call_vkGetDescriptorSetLayoutSupport
    0000000000034760 T vt_call_vkGetDeviceBufferMemoryRequirements
    0000000000009e70 T vt_call_vkGetDeviceGroupPeerMemoryFeatures
    0000000000009ef0 T vt_call_vkGetDeviceGroupPresentCapabilitiesKHR
    0000000000009e80 T vt_call_vkGetDeviceGroupSurfacePresentModesKHR
    0000000000034c40 T vt_call_vkGetDeviceImageMemoryRequirements
    0000000000017dd0 T vt_call_vkGetDeviceImageSparseMemoryRequirements
    000000000003c244 T vt_call_vkGetDeviceMemoryCommitment
    00000000000329d4 T vt_call_vkGetDeviceMemoryOpaqueCaptureAddress
    0000000000012534 T vt_call_vkGetDeviceProcAddr
    000000000002a5c0 T vt_call_vkGetDeviceQueue
    0000000000033640 T vt_call_vkGetDeviceQueue2
    0000000000030f14 T vt_call_vkGetEventStatus
    0000000000010970 T vt_call_vkGetFenceFdKHR
    0000000000031414 T vt_call_vkGetFenceStatus
    0000000000023e70 T vt_call_vkGetImageMemoryRequirements
    00000000000248a0 T vt_call_vkGetImageMemoryRequirements2
    0000000000018c00 T vt_call_vkGetImageSparseMemoryRequirements
    0000000000019540 T vt_call_vkGetImageSparseMemoryRequirements2
    0000000000035ae4 T vt_call_vkGetImageSubresourceLayout
    00000000000124c0 T vt_call_vkGetInstanceProcAddr
    0000000000010950 T vt_call_vkGetMemoryFdKHR
    0000000000009e64 T vt_call_vkGetMemoryFdPropertiesKHR
    0000000000009e60 T vt_call_vkGetPhysicalDeviceExternalBufferProperties
    00000000000109d0 T vt_call_vkGetPhysicalDeviceExternalFenceProperties
    00000000000109c0 T vt_call_vkGetPhysicalDeviceExternalSemaphoreProperties
    00000000000360a4 T vt_call_vkGetPhysicalDeviceFeatures
    000000000002b1c0 T vt_call_vkGetPhysicalDeviceFeatures2
    0000000000027740 T vt_call_vkGetPhysicalDeviceFormatProperties
    000000000001b310 T vt_call_vkGetPhysicalDeviceFormatProperties2
    0000000000039a60 T vt_call_vkGetPhysicalDeviceImageFormatProperties
    00000000000389c4 T vt_call_vkGetPhysicalDeviceImageFormatProperties2
    00000000000285e0 T vt_call_vkGetPhysicalDeviceMemoryProperties
    00000000000382a0 T vt_call_vkGetPhysicalDeviceMemoryProperties2
    00000000000279d0 T vt_call_vkGetPhysicalDeviceMultisamplePropertiesEXT
    0000000000009e90 T vt_call_vkGetPhysicalDevicePresentRectanglesKHR
    0000000000032194 T vt_call_vkGetPhysicalDeviceProperties
    000000000002dbd0 T vt_call_vkGetPhysicalDeviceProperties2
    0000000000039700 T vt_call_vkGetPhysicalDeviceQueueFamilyProperties
    0000000000019200 T vt_call_vkGetPhysicalDeviceQueueFamilyProperties2
    0000000000018ef0 T vt_call_vkGetPhysicalDeviceSparseImageFormatProperties
    000000000001b7c0 T vt_call_vkGetPhysicalDeviceSparseImageFormatProperties2
    000000000003b410 T vt_call_vkGetPhysicalDeviceSurfaceCapabilitiesKHR
    000000000001e8a0 T vt_call_vkGetPhysicalDeviceSurfaceFormatsKHR
    000000000001e240 T vt_call_vkGetPhysicalDeviceSurfacePresentModesKHR
    0000000000009e40 T vt_call_vkGetPhysicalDeviceSurfaceSupportKHR
    00000000000109b0 T vt_call_vkGetPhysicalDeviceToolProperties
    0000000000009e50 T vt_call_vkGetPhysicalDeviceXlibPresentationSupportKHR
    000000000001e564 T vt_call_vkGetPipelineCacheData
    0000000000009eb0 T vt_call_vkGetPrivateData
    000000000001cce4 T vt_call_vkGetQueryPoolResults
    0000000000023074 T vt_call_vkGetRenderAreaGranularity
    00000000000109a0 T vt_call_vkGetSemaphoreCounterValue
    0000000000010960 T vt_call_vkGetSemaphoreFdKHR
    000000000001ef00 T vt_call_vkGetSwapchainImagesKHR
    00000000000109e0 T vt_call_vkImportFenceFdKHR
    00000000000109c4 T vt_call_vkImportSemaphoreFdKHR
    000000000003a660 T vt_call_vkInvalidateMappedMemoryRanges
    0000000000035710 T vt_call_vkMapMemory
    000000000003b0d0 T vt_call_vkMergePipelineCaches
    000000000001cfb0 T vt_call_vkQueueBindSparse
    0000000000023624 T vt_call_vkQueuePresentKHR
    0000000000039df0 T vt_call_vkQueueSubmit
    0000000000018640 T vt_call_vkQueueSubmit2
    0000000000030c90 T vt_call_vkQueueWaitIdle
    0000000000024650 T vt_call_vkResetCommandBuffer
    000000000002aee0 T vt_call_vkResetCommandPool
    0000000000032454 T vt_call_vkResetDescriptorPool
    0000000000031914 T vt_call_vkResetEvent
    00000000000341a0 T vt_call_vkResetFences
    00000000000261c4 T vt_call_vkResetQueryPool
    0000000000031194 T vt_call_vkSetEvent
    0000000000009ea0 T vt_call_vkSetPrivateData
    00000000000109f0 T vt_call_vkSignalSemaphore
    0000000000037690 T vt_call_vkTrimCommandPool
    0000000000017a54 T vt_call_vkUnmapMemory
    0000000000027c60 T vt_call_vkUpdateDescriptorSets
    0000000000025c90 T vt_call_vkUpdateDescriptorSetWithTemplate
    000000000001bb70 T vt_call_vkWaitForFences
    0000000000022b04 T vt_call_vkWaitSemaphores
```

## vortek-1.0.tzst/usr/share/vulkan/icd.d/vortek_icd.aarch64.json

```json
    {
        "ICD": {
            "api_version": "1.1.128",
            "library_path": "/data/data/com.winlator/files/rootfs/lib/libvulkan_vortek.so"
        },
        "file_format_version": "1.0.0"
    }
```

## Winlator_10.0.apk/app/src/main/lib/arm64-v8a/libvortekrenderer.so

```bash
$ nm app/src/main/lib/arm64-v8a/libvortekrenderer.so
    0000000000036a28 T acquireNextImage
    0000000000035320 T checkFormatProperties
    0000000000036618 T createSwapchain
    000000000003544c T createVkContext
    0000000000036940 T destroySwapchain
    000000000003591c T destroyVkContext
    0000000000035000 T disableUnsupportedFeatures
    0000000000037d3c T getCompressedImageFormatProperties
    00000000000350e8 T getExposedDeviceExtensionProperties
    00000000000352bc T getFeatureNames
    000000000001a42c T getHandleRequestFunc
    0000000000034874 T getMemoryPropertyFlags
    0000000000034820 T getMemoryTypeIndex
    00000000000369e4 T getSurfaceFormats
    0000000000036610 T getSwapchainMinImageCount
    0000000000036564 T getWindowExtent
    00000000000365d0 T getWindowHardwareBuffer
    000000000003bd50 D handleRequestFuncs
    000000000002daf4 T initVulkanDevice
    000000000002c924 T initVulkanInstance
    00000000000348e4 T injectExtensions
    0000000000034c88 T injectExtensions2
    0000000000037d2c T isCompressedFormat
    0000000000038e3c T isFormatScaled
    00000000000348a8 T isHostVisibleMemory
    000000000000e314 T Java_com_winlator_xenvironment_components_VortekRendererComponent_createVkContext
    000000000000e43c T Java_com_winlator_xenvironment_components_VortekRendererComponent_destroyVkContext
    000000000003ce08 B memoryPools
    000000000003ce18 B memoryPoolsMutex
    0000000000034f7c T overrideMemoryHeapSize
    0000000000036b48 T presentImage
    0000000000035db8 T ResourceMemory_allocate
    00000000000364dc T ResourceMemory_free
    0000000000036c48 T RingBuffer_create
    0000000000036fbc T RingBuffer_free
    0000000000036d10 T RingBuffer_freeSpace
    0000000000036ce8 T RingBuffer_getSHMemSize
    0000000000036c34 T RingBuffer_hasStatus
    0000000000036d38 T RingBuffer_read
    0000000000036bf4 T RingBuffer_setStatus
    0000000000036cf0 T RingBuffer_size
    0000000000036c14 T RingBuffer_unsetStatus
    0000000000036e60 T RingBuffer_write
    00000000000383e8 T ShaderInspector_create
    0000000000038498 T ShaderInspector_createModule
    00000000000385e4 T ShaderInspector_inspectShaderStages
    0000000000037be8 T TextureDecoder_addBoundBuffer
    000000000003784c T TextureDecoder_containsImage
    00000000000376f8 T TextureDecoder_copyBufferToImage
    0000000000037008 T TextureDecoder_create
    0000000000037890 T TextureDecoder_createImage
    000000000003709c T TextureDecoder_decodeAll
    0000000000037050 T TextureDecoder_destroy
    0000000000037b04 T TextureDecoder_destroyImage
    0000000000037cb0 T TextureDecoder_removeBoundBuffer
    00000000000365f0 T updateWindowContent
    000000000000e444 T VkObject_create
    000000000000e5ec T VkObject_free
    000000000000e5d0 T VkObject_fromHandle
    000000000000e5cc T VkObject_fromId
    000000000000e594 T VkObject_toHandle
    0000000000023890 T vt_handle_vkAcquireNextImage2KHR
    000000000001dd38 T vt_handle_vkAcquireNextImageKHR
    0000000000019b04 T vt_handle_vkAllocateCommandBuffers
    0000000000018160 T vt_handle_vkAllocateDescriptorSets
    0000000000011924 T vt_handle_vkAllocateMemory
    0000000000019e28 T vt_handle_vkBeginCommandBuffer
    0000000000012270 T vt_handle_vkBindBufferMemory
    0000000000023834 T vt_handle_vkBindBufferMemory2
    000000000001244c T vt_handle_vkBindImageMemory
    0000000000023838 T vt_handle_vkBindImageMemory2
    000000000001cbd8 T vt_handle_vkCmdBeginConditionalRenderingEXT
    000000000001cac8 T vt_handle_vkCmdBeginQuery
    00000000000279a4 T vt_handle_vkCmdBeginQueryIndexedEXT
    0000000000029924 T vt_handle_vkCmdBeginRendering
    000000000001cffc T vt_handle_vkCmdBeginRenderPass
    0000000000026e28 T vt_handle_vkCmdBeginRenderPass2
    0000000000027704 T vt_handle_vkCmdBeginTransformFeedbackEXT
    000000000001aa1c T vt_handle_vkCmdBindDescriptorSets
    000000000001abfc T vt_handle_vkCmdBindIndexBuffer
    000000000001a4a8 T vt_handle_vkCmdBindPipeline
    0000000000027570 T vt_handle_vkCmdBindTransformFeedbackBuffersEXT
    000000000001ac8c T vt_handle_vkCmdBindVertexBuffers
    0000000000028118 T vt_handle_vkCmdBindVertexBuffers2
    000000000001b4a8 T vt_handle_vkCmdBlitImage
    0000000000028910 T vt_handle_vkCmdBlitImage2
    000000000001c008 T vt_handle_vkCmdClearAttachments
    000000000001bcb0 T vt_handle_vkCmdClearColorImage
    000000000001be54 T vt_handle_vkCmdClearDepthStencilImage
    000000000001b100 T vt_handle_vkCmdCopyBuffer
    00000000000285e0 T vt_handle_vkCmdCopyBuffer2
    000000000001b6c4 T vt_handle_vkCmdCopyBufferToImage
    0000000000028ac8 T vt_handle_vkCmdCopyBufferToImage2
    000000000001b288 T vt_handle_vkCmdCopyImage
    0000000000028738 T vt_handle_vkCmdCopyImage2
    000000000001b8f0 T vt_handle_vkCmdCopyImageToBuffer
    0000000000028cf8 T vt_handle_vkCmdCopyImageToBuffer2
    000000000001cde8 T vt_handle_vkCmdCopyQueryPoolResults
    000000000001b00c T vt_handle_vkCmdDispatch
    0000000000023894 T vt_handle_vkCmdDispatchBase
    000000000001b07c T vt_handle_vkCmdDispatchIndirect
    000000000001addc T vt_handle_vkCmdDraw
    000000000001ae50 T vt_handle_vkCmdDrawIndexed
    000000000001af70 T vt_handle_vkCmdDrawIndexedIndirect
    0000000000027494 T vt_handle_vkCmdDrawIndexedIndirectCount
    000000000001aed4 T vt_handle_vkCmdDrawIndirect
    0000000000027acc T vt_handle_vkCmdDrawIndirectByteCountEXT
    00000000000273b8 T vt_handle_vkCmdDrawIndirectCount
    000000000001cca4 T vt_handle_vkCmdEndConditionalRenderingEXT
    000000000001cb54 T vt_handle_vkCmdEndQuery
    0000000000027a40 T vt_handle_vkCmdEndQueryIndexedEXT
    0000000000029e10 T vt_handle_vkCmdEndRendering
    000000000001d104 T vt_handle_vkCmdEndRenderPass
    0000000000026fe4 T vt_handle_vkCmdEndRenderPass2
    0000000000027854 T vt_handle_vkCmdEndTransformFeedbackEXT
    000000000001d12c T vt_handle_vkCmdExecuteCommands
    000000000001bc14 T vt_handle_vkCmdFillBuffer
    000000000001d0b8 T vt_handle_vkCmdNextSubpass
    0000000000026f10 T vt_handle_vkCmdNextSubpass2
    000000000001c808 T vt_handle_vkCmdPipelineBarrier
    000000000002941c T vt_handle_vkCmdPipelineBarrier2
    000000000001cec8 T vt_handle_vkCmdPushConstants
    0000000000023228 T vt_handle_vkCmdPushDescriptorSetKHR
    000000000001c45c T vt_handle_vkCmdResetEvent
    0000000000029244 T vt_handle_vkCmdResetEvent2
    000000000001cccc T vt_handle_vkCmdResetQueryPool
    000000000001c1b8 T vt_handle_vkCmdResolveImage
    0000000000028eac T vt_handle_vkCmdResolveImage2
    000000000001a820 T vt_handle_vkCmdSetBlendConstants
    0000000000029084 T vt_handle_vkCmdSetColorWriteEnableEXT
    0000000000027e1c T vt_handle_vkCmdSetCullMode
    000000000001a7b0 T vt_handle_vkCmdSetDepthBias
    0000000000028548 T vt_handle_vkCmdSetDepthBiasEnable
    000000000001a8ac T vt_handle_vkCmdSetDepthBounds
    00000000000283e0 T vt_handle_vkCmdSetDepthBoundsTestEnable
    0000000000028394 T vt_handle_vkCmdSetDepthCompareOp
    00000000000282fc T vt_handle_vkCmdSetDepthTestEnable
    0000000000028348 T vt_handle_vkCmdSetDepthWriteEnable
    000000000002383c T vt_handle_vkCmdSetDeviceMask
    000000000001c3d8 T vt_handle_vkCmdSetEvent
    000000000002916c T vt_handle_vkCmdSetEvent2
    0000000000027e68 T vt_handle_vkCmdSetFrontFace
    0000000000027dbc T vt_handle_vkCmdSetLineStippleEXT
    000000000001a764 T vt_handle_vkCmdSetLineWidth
    0000000000028594 T vt_handle_vkCmdSetPrimitiveRestartEnable
    0000000000027eb4 T vt_handle_vkCmdSetPrimitiveTopology
    00000000000284fc T vt_handle_vkCmdSetRasterizerDiscardEnable
    000000000002392c T vt_handle_vkCmdSetSampleLocationsEXT
    000000000001a658 T vt_handle_vkCmdSetScissor
    000000000002801c T vt_handle_vkCmdSetScissorWithCount
    000000000001a908 T vt_handle_vkCmdSetStencilCompareMask
    0000000000028478 T vt_handle_vkCmdSetStencilOp
    000000000001a9c0 T vt_handle_vkCmdSetStencilReference
    000000000002842c T vt_handle_vkCmdSetStencilTestEnable
    000000000001a964 T vt_handle_vkCmdSetStencilWriteMask
    000000000001a52c T vt_handle_vkCmdSetViewport
    0000000000027f00 T vt_handle_vkCmdSetViewportWithCount
    000000000001bae8 T vt_handle_vkCmdUpdateBuffer
    000000000001c4e0 T vt_handle_vkCmdWaitEvents
    00000000000292c8 T vt_handle_vkCmdWaitEvents2
    000000000001cd58 T vt_handle_vkCmdWriteTimestamp
    0000000000029898 T vt_handle_vkCmdWriteTimestamp2
    00000000000143fc T vt_handle_vkCreateBuffer
    000000000001455c T vt_handle_vkCreateBufferView
    0000000000019928 T vt_handle_vkCreateCommandPool
    0000000000016edc T vt_handle_vkCreateComputePipelines
    0000000000017d7c T vt_handle_vkCreateDescriptorPool
    0000000000017c38 T vt_handle_vkCreateDescriptorSetLayout
    000000000000fa60 T vt_handle_vkCreateDevice
    0000000000013da4 T vt_handle_vkCreateEvent
    000000000001331c T vt_handle_vkCreateFence
    0000000000018adc T vt_handle_vkCreateFramebuffer
    000000000001535c T vt_handle_vkCreateGraphicsPipelines
    00000000000146dc T vt_handle_vkCreateImage
    00000000000149dc T vt_handle_vkCreateImageView
    000000000000e630 T vt_handle_vkCreateInstance
    0000000000014f34 T vt_handle_vkCreatePipelineCache
    000000000001752c T vt_handle_vkCreatePipelineLayout
    0000000000014080 T vt_handle_vkCreateQueryPool
    0000000000018f84 T vt_handle_vkCreateRenderPass
    0000000000025908 T vt_handle_vkCreateRenderPass2
    0000000000017788 T vt_handle_vkCreateSampler
    0000000000025478 T vt_handle_vkCreateSamplerYcbcrConversion
    0000000000013a50 T vt_handle_vkCreateSemaphore
    0000000000014dc4 T vt_handle_vkCreateShaderModule
    000000000001d69c T vt_handle_vkCreateSwapchainKHR
    0000000000014504 T vt_handle_vkDestroyBuffer
    0000000000014698 T vt_handle_vkDestroyBufferView
    0000000000019a3c T vt_handle_vkDestroyCommandPool
    0000000000018098 T vt_handle_vkDestroyDescriptorPool
    0000000000017d38 T vt_handle_vkDestroyDescriptorSetLayout
    0000000000010a24 T vt_handle_vkDestroyDevice
    0000000000013eb0 T vt_handle_vkDestroyEvent
    00000000000135d0 T vt_handle_vkDestroyFence
    0000000000018f40 T vt_handle_vkDestroyFramebuffer
    000000000001482c T vt_handle_vkDestroyImage
    0000000000014d80 T vt_handle_vkDestroyImageView
    000000000000ea08 T vt_handle_vkDestroyInstance
    00000000000174e8 T vt_handle_vkDestroyPipeline
    000000000001507c T vt_handle_vkDestroyPipelineCache
    0000000000017744 T vt_handle_vkDestroyPipelineLayout
    000000000001419c T vt_handle_vkDestroyQueryPool
    000000000001981c T vt_handle_vkDestroyRenderPass
    0000000000017bf4 T vt_handle_vkDestroySampler
    00000000000255d0 T vt_handle_vkDestroySamplerYcbcrConversion
    0000000000013d60 T vt_handle_vkDestroySemaphore
    0000000000014ee0 T vt_handle_vkDestroyShaderModule
    000000000001db04 T vt_handle_vkDestroySwapchainKHR
    00000000000118ac T vt_handle_vkDeviceWaitIdle
    000000000001a370 T vt_handle_vkEndCommandBuffer
    0000000000010d44 T vt_handle_vkEnumerateDeviceExtensionProperties
    0000000000010d40 T vt_handle_vkEnumerateDeviceLayerProperties
    0000000000010ae8 T vt_handle_vkEnumerateInstanceExtensionProperties
    0000000000010ae4 T vt_handle_vkEnumerateInstanceLayerProperties
    0000000000010a64 T vt_handle_vkEnumerateInstanceVersion
    0000000000023428 T vt_handle_vkEnumeratePhysicalDeviceGroups
    000000000000ea34 T vt_handle_vkEnumeratePhysicalDevices
    0000000000011e40 T vt_handle_vkFlushMappedMemoryRanges
    0000000000019d0c T vt_handle_vkFreeCommandBuffers
    00000000000187f0 T vt_handle_vkFreeDescriptorSets
    0000000000011d60 T vt_handle_vkFreeMemory
    0000000000027c44 T vt_handle_vkGetBufferDeviceAddress
    000000000001219c T vt_handle_vkGetBufferMemoryRequirements
    0000000000023b48 T vt_handle_vkGetBufferMemoryRequirements2
    0000000000027b88 T vt_handle_vkGetBufferOpaqueCaptureAddress
    000000000002574c T vt_handle_vkGetDescriptorSetLayoutSupport
    0000000000024874 T vt_handle_vkGetDeviceBufferMemoryRequirements
    0000000000023830 T vt_handle_vkGetDeviceGroupPeerMemoryFeatures
    0000000000023888 T vt_handle_vkGetDeviceGroupPresentCapabilitiesKHR
    000000000002388c T vt_handle_vkGetDeviceGroupSurfacePresentModesKHR
    0000000000024c6c T vt_handle_vkGetDeviceImageMemoryRequirements
    0000000000025070 T vt_handle_vkGetDeviceImageSparseMemoryRequirements
    00000000000120f8 T vt_handle_vkGetDeviceMemoryCommitment
    0000000000027d00 T vt_handle_vkGetDeviceMemoryOpaqueCaptureAddress
    0000000000010f5c T vt_handle_vkGetDeviceQueue
    0000000000025614 T vt_handle_vkGetDeviceQueue2
    0000000000013ef4 T vt_handle_vkGetEventStatus
    0000000000023420 T vt_handle_vkGetFenceFdKHR
    0000000000013710 T vt_handle_vkGetFenceStatus
    0000000000012378 T vt_handle_vkGetImageMemoryRequirements
    0000000000023f24 T vt_handle_vkGetImageMemoryRequirements2
    0000000000012538 T vt_handle_vkGetImageSparseMemoryRequirements
    00000000000244a0 T vt_handle_vkGetImageSparseMemoryRequirements2
    000000000001489c T vt_handle_vkGetImageSubresourceLayout
    0000000000023408 T vt_handle_vkGetMemoryFdKHR
    000000000002340c T vt_handle_vkGetMemoryFdPropertiesKHR
    0000000000023404 T vt_handle_vkGetPhysicalDeviceExternalBufferProperties
    000000000002341c T vt_handle_vkGetPhysicalDeviceExternalFenceProperties
    0000000000023410 T vt_handle_vkGetPhysicalDeviceExternalSemaphoreProperties
    000000000000f568 T vt_handle_vkGetPhysicalDeviceFeatures
    000000000001e1fc T vt_handle_vkGetPhysicalDeviceFeatures2
    000000000000f7f8 T vt_handle_vkGetPhysicalDeviceFormatProperties
    0000000000021d0c T vt_handle_vkGetPhysicalDeviceFormatProperties2
    000000000000f8f4 T vt_handle_vkGetPhysicalDeviceImageFormatProperties
    00000000000220e4 T vt_handle_vkGetPhysicalDeviceImageFormatProperties2
    000000000000f3c4 T vt_handle_vkGetPhysicalDeviceMemoryProperties
    0000000000022be8 T vt_handle_vkGetPhysicalDeviceMemoryProperties2
    0000000000023a60 T vt_handle_vkGetPhysicalDeviceMultisamplePropertiesEXT
    0000000000023928 T vt_handle_vkGetPhysicalDevicePresentRectanglesKHR
    000000000000ec08 T vt_handle_vkGetPhysicalDeviceProperties
    000000000001f484 T vt_handle_vkGetPhysicalDeviceProperties2
    000000000000f208 T vt_handle_vkGetPhysicalDeviceQueueFamilyProperties
    00000000000228ac T vt_handle_vkGetPhysicalDeviceQueueFamilyProperties2
    000000000001271c T vt_handle_vkGetPhysicalDeviceSparseImageFormatProperties
    0000000000022e9c T vt_handle_vkGetPhysicalDeviceSparseImageFormatProperties2
    000000000001d22c T vt_handle_vkGetPhysicalDeviceSurfaceCapabilitiesKHR
    000000000001d338 T vt_handle_vkGetPhysicalDeviceSurfaceFormatsKHR
    000000000001d550 T vt_handle_vkGetPhysicalDeviceSurfacePresentModesKHR
    000000000001d228 T vt_handle_vkGetPhysicalDeviceSurfaceSupportKHR
    0000000000027e18 T vt_handle_vkGetPhysicalDeviceToolProperties
    00000000000150c0 T vt_handle_vkGetPipelineCacheData
    00000000000141e0 T vt_handle_vkGetQueryPoolResults
    0000000000019860 T vt_handle_vkGetRenderAreaGranularity
    000000000002707c T vt_handle_vkGetSemaphoreCounterValue
    0000000000023414 T vt_handle_vkGetSemaphoreFdKHR
    000000000001db34 T vt_handle_vkGetSwapchainImagesKHR
    0000000000023424 T vt_handle_vkImportFenceFdKHR
    0000000000023418 T vt_handle_vkImportSemaphoreFdKHR
    0000000000011f9c T vt_handle_vkInvalidateMappedMemoryRanges
    0000000000011d7c T vt_handle_vkMapMemory
    0000000000015228 T vt_handle_vkMergePipelineCaches
    0000000000012924 T vt_handle_vkQueueBindSparse
    000000000001de48 T vt_handle_vkQueuePresentKHR
    000000000001105c T vt_handle_vkQueueSubmit
    00000000000294bc T vt_handle_vkQueueSubmit2
    0000000000011834 T vt_handle_vkQueueWaitIdle
    000000000001a45c T vt_handle_vkResetCommandBuffer
    0000000000019a80 T vt_handle_vkResetCommandPool
    00000000000180dc T vt_handle_vkResetDescriptorPool
    0000000000013ffc T vt_handle_vkResetEvent
    0000000000013614 T vt_handle_vkResetFences
    0000000000014380 T vt_handle_vkResetQueryPool
    0000000000013f78 T vt_handle_vkSetEvent
    00000000000273b4 T vt_handle_vkSignalSemaphore
    0000000000023398 T vt_handle_vkTrimCommandPool
    0000000000011e3c T vt_handle_vkUnmapMemory
    000000000001890c T vt_handle_vkUpdateDescriptorSets
    0000000000013794 T vt_handle_vkWaitForFences
    0000000000027080 T vt_handle_vkWaitSemaphores
    000000000003c660 B vulkanWrapper
```

## Winlator_10.0.apk/app/src/main/res/values/public.xml

```xml
    <public type="layout" name="vortek_config_dialog" id="0x7f0c00b5" />
```

## Winlator_10.0.apk/app/src/main/res/values/arrays.xml

```xml
    <array name="graphics_driver_entries">
        <item>Turnip (Adreno)</item>
        <item>Vortek (Universal)</item>
        <item>VirGL (Universal)</item>
    </array>
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/ContainerDetailFragment.java

```java
    public static void showGraphicsDriverConfigDialog(String graphicsDriver, View vGraphicsDriverConfig) {
        char c;
        switch (graphicsDriver.hashCode()) {
            case -862428572:
                if (graphicsDriver.equals("turnip")) {
                    c = 0;
                    break;
                }
                c = 65535;
                break;
            case -810705759:
                if (graphicsDriver.equals("vortek")) {
                    c = 1;
                    break;
                }
                c = 65535;
                break;
            case 112216388:
                if (graphicsDriver.equals("virgl")) {
                    c = 2;
                    break;
                }
                c = 65535;
                break;
            default:
                c = 65535;
                break;
        }
        switch (c) {
            case 0:
                new TurnipConfigDialog(vGraphicsDriverConfig).show();
                break;
            case 1:
                new VortekConfigDialog(vGraphicsDriverConfig).show(); // HERE
                break;
            case 2:
                new VirGLConfigDialog(vGraphicsDriverConfig).show();
                break;
        }
    }
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/contentdialog/VortekConfigDialog.java

```java
public class VortekConfigDialog extends ContentDialog {
    public static final String DEFAULT_VK_MAX_VERSION;

    static {
        StringBuilder sb = new StringBuilder();
        int i = VortekRendererComponent.VK_MAX_VERSION;
        sb.append(GPUHelper.vkVersionMajor(i));
        sb.append(".");
        sb.append(GPUHelper.vkVersionMinor(i));
        DEFAULT_VK_MAX_VERSION = sb.toString();
    }

    public VortekConfigDialog(final View anchor) {
        super(anchor.getContext(), R.layout.vortek_config_dialog);
        Context context = anchor.getContext();
        setIcon(R.drawable.icon_display_settings);
        setTitle("Vortek " + context.getString(R.string.configuration));
        final Spinner sVkMaxVersion = (Spinner) findViewById(R.id.SVkMaxVersion);
        final Spinner sMaxDeviceMemory = (Spinner) findViewById(R.id.SMaxDeviceMemory);
        final MultiSelectionComboBox mscbExposedExtensions = (MultiSelectionComboBox) findViewById(R.id.MSCBExposedExtensions);
        final String[] deviceExtensions = GPUHelper.vkGetDeviceExtensions();
        mscbExposedExtensions.setPopupWindowWidth(360);
        mscbExposedExtensions.setDisplayText(context.getString(R.string.multiselection_combobox_display_text));
        mscbExposedExtensions.setItems(deviceExtensions);
        KeyValueSet config = new KeyValueSet(anchor.getTag());
        String exposedDeviceExtensionsVal = config.get("exposedDeviceExtensions", "all");
        if (exposedDeviceExtensionsVal.equals("all")) {
            mscbExposedExtensions.setSelectedItems(deviceExtensions);
        } else if (!exposedDeviceExtensionsVal.isEmpty()) {
            mscbExposedExtensions.setSelectedItems(exposedDeviceExtensionsVal.split("\\|"));
        }
        AppUtils.setSpinnerSelectionFromValue(sVkMaxVersion, config.get("vkMaxVersion", DEFAULT_VK_MAX_VERSION));
        AppUtils.setSpinnerSelectionFromNumber(sMaxDeviceMemory, config.get("maxDeviceMemory", String.valueOf(4096)));
        setOnConfirmCallback(new Runnable() { // from class: com.winlator.contentdialog.VortekConfigDialog$$ExternalSyntheticLambda0
            @Override // java.lang.Runnable
            public final void run() {
                VortekConfigDialog.lambda$new$0(sVkMaxVersion, sMaxDeviceMemory, mscbExposedExtensions, deviceExtensions, anchor);
            }
        });
    }

    public static /* synthetic */ void lambda$new$0(Spinner sVkMaxVersion, Spinner sMaxDeviceMemory, MultiSelectionComboBox mscbExposedExtensions, String[] deviceExtensions, View anchor) {
        KeyValueSet newConfig = new KeyValueSet();
        newConfig.put("vkMaxVersion", StringUtils.parseNumber(sVkMaxVersion.getSelectedItem(), "0"));
        newConfig.put("maxDeviceMemory", StringUtils.parseNumber(sMaxDeviceMemory.getSelectedItem()));
        String[] selectedItems = mscbExposedExtensions.getSelectedItems();
        if (selectedItems.length > 0) {
            if (selectedItems.length == deviceExtensions.length) {
                newConfig.put("exposedDeviceExtensions", "all");
            } else {
                newConfig.put("exposedDeviceExtensions", String.join("|", selectedItems));
            }
        }
        anchor.setTag(newConfig.toString());
    }
}
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/R.java

```java
        public static final int vortek_config_dialog = 0x7f0c00b5;
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/container/Container.java

```java
public class Container {
    // ...
    private String screenSize = "1280x720";
    private String envVars = "ZINK_DESCRIPTORS=lazy ZINK_DEBUG=compact MESA_SHADER_CACHE_DISABLE=false MESA_SHADER_CACHE_MAX_SIZE=512MB mesa_glthread=true WINEESYNC=1 TU_DEBUG=sysmem,noconform";
    private String graphicsDriver = "vortek";
    private String dxwrapper = "dxvk";
    private String dxwrapperConfig = "";
    // ...
}
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/XServerDisplayActivity.java

```java
public class XServerDisplayActivity extends AppCompatActivity implements NavigationView.OnNavigationItemSelectedListener {
    // ...
    private XServerView xServerView;
    private String graphicsDriver = "vortek";
    private String audioDriver = "alsa";
    private String dxwrapper = "dxvk";
    // ...

    private void setupXEnvironment() {
        String str;
        String rootPath = this.rootFS.getRootDir().getPath();
        this.envVars.put("MESA_DEBUG", "silent");
        this.envVars.put("MESA_NO_ERROR", "1");
        this.envVars.put("WINEPREFIX", rootPath + "/home/xuser/.wine");
        this.envVars.put("WINE_DO_NOT_UPDATE_IF_TABLE", "1");
        this.envVars.put("WINE_DO_NOT_CREATE_DXGI_DEVICE_MANAGER", "1");
        // ...
        if (this.graphicsDriver.equals("virgl")) {
            this.environment.addComponent(new VirGLRendererComponent(this.xServer, UnixSocketConfig.create(rootPath, "/tmp/.virgl/V0")));
        } else if (this.graphicsDriver.equals("vortek")) {
            VortekRendererComponent.Options options2 = VortekRendererComponent.Options.fromKeyValueSet(this.graphicsDriverConfig);
            VortekRendererComponent vortekRendererComponent = new VortekRendererComponent(this.xServer, UnixSocketConfig.create(rootPath, "/tmp/.vortek/V0"), options2);
            this.environment.addComponent(vortekRendererComponent);
        }
        // ...
    }

    // ...

    private void extractGraphicsDriverFiles() {
        // ...
        switch (this.graphicsDriver) {
            case "turnip":
                cacheId = cacheId + "-" + this.graphicsDriverConfig.get("version", "25.0.0") + "-22.2.5";
                break;
            case "vortek": // HERE
                cacheId = cacheId + "-1.0-22.2.5";
                break;
            case "virgl":
                cacheId = cacheId + "-23.1.9";
                break;
        }
        boolean changed = !cacheId.equals(this.container.getExtra("graphicsDriver"));
        File rootDir = this.rootFS.getRootDir();
        File libDir = this.rootFS.getLibDir();
        if (changed) {
            FileUtils.delete(new File(libDir, "libvulkan_freedreno.so"));
            FileUtils.delete(new File(libDir, "libvulkan_vortek.so")); // HERE
            FileUtils.delete(new File(libDir, "libGL.so.1.7.0"));
            File vulkanICDDir = new File(rootDir, "/usr/share/vulkan/icd.d");
            FileUtils.delete(vulkanICDDir);
            vulkanICDDir.mkdirs();
            this.container.putExtra("graphicsDriver", cacheId);
            this.container.saveData();
        }
        switch (this.graphicsDriver) {
            case "turnip":
                this.envVars.put("GALLIUM_DRIVER", "zink");
                this.envVars.put("ZINK_CONTEXT_THREADED", "1");
                this.envVars.put("MESA_VK_WSI_PRESENT_MODE", "mailbox");
                this.envVars.put("WINEVKUSEPLACEDADDR", "1");
                TurnipConfigDialog.setEnvVars(this.graphicsDriverConfig, this.envVars);
                if (changed) {
                    InstallableComponents.extractFile(InstallableComponents.Type.TURNIP, this, this.graphicsDriverConfig.get("version", "25.0.0"), "25.0.0");
                    TarCompressorUtils.extract(TarCompressorUtils.Type.ZSTD, this, "graphics_driver/zink-22.2.5.tzst", rootDir);
                    break;
                }
                break;
            case "vortek": // HERE
                this.envVars.put("GALLIUM_DRIVER", "zink");
                this.envVars.put("ZINK_CONTEXT_THREADED", "1");
                this.envVars.put("MESA_GL_VERSION_OVERRIDE", "3.3");
                this.envVars.put("WINEVKUSEPLACEDADDR", "1");
                this.envVars.put("VORTEK_SERVER_PATH", rootDir + "/tmp/.vortek/V0");
                if (this.dxwrapper.equals("dxvk")) {
                    this.dxwrapperConfig.put("constantBufferRangeCheck", "1");
                }
                if (changed) {
                    TarCompressorUtils.Type type = TarCompressorUtils.Type.ZSTD;
                    TarCompressorUtils.extract(type, this, "graphics_driver/vortek-1.0.tzst", rootDir);
                    TarCompressorUtils.extract(type, this, "graphics_driver/zink-22.2.5.tzst", rootDir);
                    break;
                }
                break;
            case "virgl":
                this.envVars.put("GALLIUM_DRIVER", "virpipe");
                this.envVars.put("VIRGL_NO_READBACK", "true");
                this.envVars.put("VIRGL_SERVER_PATH", rootDir + "/tmp/.virgl/V0");
                VirGLConfigDialog.setEnvVars(this.graphicsDriverConfig, this.envVars);
                if (changed) {
                    TarCompressorUtils.extract(TarCompressorUtils.Type.ZSTD, this, "graphics_driver/virgl-23.1.9.tzst", rootDir);
                    break;
                }
                break;
        }
        // ...
    }
}
```

## Winlator_10.0.apk/app/src/main/java/com/winlator/xenvironment/components/VortekRendererComponent.java

```java
public class VortekRendererComponent extends EnvironmentComponent implements ConnectionHandler, RequestHandler {
    public static final int VK_MAX_VERSION = GPUHelper.vkMakeVersion(1, 3, 128);
    private XConnectorEpoll connector;
    private final Options options;
    private final UnixSocketConfig socketConfig;
    private final XServer xServer;

    private native long createVkContext(int i, Options options);

    private native void destroyVkContext(long j);

    static {
        System.loadLibrary("vortekrenderer");
    }

    public static class Options {
        public int vkMaxVersion = VortekRendererComponent.VK_MAX_VERSION;
        public int maxDeviceMemory = 4096;
        public String[] exposedDeviceExtensions = null;

        public static Options fromKeyValueSet(KeyValueSet config) {
            if (config == null || config.isEmpty()) {
                return new Options();
            }
            Options options = new Options();
            String exposedDeviceExtensions = config.get("exposedDeviceExtensions", "all");
            if (!exposedDeviceExtensions.isEmpty() && !exposedDeviceExtensions.equals("all")) {
                options.exposedDeviceExtensions = exposedDeviceExtensions.split("\\|");
            }
            String str = VortekConfigDialog.DEFAULT_VK_MAX_VERSION;
            String vkMaxVersion = config.get("vkMaxVersion", str);
            if (!vkMaxVersion.equals(str)) {
                String[] parts = vkMaxVersion.split("\\.");
                options.vkMaxVersion = GPUHelper.vkMakeVersion(Integer.parseInt(parts[0]), Integer.parseInt(parts[1]), 128);
            }
            options.maxDeviceMemory = config.getInt("maxDeviceMemory", 4096);
            return options;
        }
    }

    public VortekRendererComponent(XServer xServer, UnixSocketConfig socketConfig, Options options) {
        this.xServer = xServer;
        this.socketConfig = socketConfig;
        this.options = options;
    }

    @Override // com.winlator.xenvironment.EnvironmentComponent
    public void start() {
        if (this.connector != null) {
            return;
        }
        XConnectorEpoll xConnectorEpoll = new XConnectorEpoll(this.socketConfig, this, this);
        this.connector = xConnectorEpoll;
        xConnectorEpoll.setInitialInputBufferCapacity(1);
        this.connector.setInitialOutputBufferCapacity(0);
        this.connector.start();
    }

    @Override // com.winlator.xenvironment.EnvironmentComponent
    public void stop() {
        XConnectorEpoll xConnectorEpoll = this.connector;
        if (xConnectorEpoll != null) {
            xConnectorEpoll.stop();
            this.connector = null;
        }
    }

    @Keep
    private int getWindowWidth(int windowId) {
        Window window = this.xServer.windowManager.getWindow(windowId);
        if (window != null) {
            return window.getWidth();
        }
        return 0;
    }

    @Keep
    private int getWindowHeight(int windowId) {
        Window window = this.xServer.windowManager.getWindow(windowId);
        if (window != null) {
            return window.getHeight();
        }
        return 0;
    }

    @Keep
    private long getWindowHardwareBuffer(int windowId) {
        Window window = this.xServer.windowManager.getWindow(windowId);
        if (window != null) {
            Drawable drawable = window.getContent();
            Texture texture = drawable.getTexture();
            if (!(texture instanceof GPUImage)) {
                XServerView xServerView = this.xServer.getRenderer().xServerView;
                Objects.requireNonNull(texture);
                xServerView.queueEvent(texture::destroy);
                drawable.setTexture(new GPUImage(drawable.width, drawable.height, false, false));
            }
            return ((GPUImage) drawable.getTexture()).getHardwareBufferPtr();
        }
        return 0L;
    }

    @Keep
    private void updateWindowContent(int windowId) {
        Window window = this.xServer.windowManager.getWindow(windowId);
        if (window != null) {
            Drawable drawable = window.getContent();
            synchronized (drawable.renderLock) {
                drawable.forceUpdate();
            }
        }
    }

    @Override // com.winlator.xconnector.ConnectionHandler
    public void handleConnectionShutdown(Client client) {
        if (client.getTag() != null) {
            long contextPtr = ((Long) client.getTag()).longValue();
            destroyVkContext(contextPtr);
        }
    }

    @Override // com.winlator.xconnector.ConnectionHandler
    public void handleNewConnection(Client client) {
        client.createIOStreams();
    }

    @Override // com.winlator.xconnector.RequestHandler
    public boolean handleRequest(Client client) throws IOException {
        XInputStream inputStream = client.getInputStream();
        if (inputStream.available() < 1) {
            return false;
        }
        byte requestCode = inputStream.readByte();
        if (requestCode == 1) {
            long contextPtr = createVkContext(client.clientSocket.fd, this.options);
            if (contextPtr > 0) {
                client.setTag(Long.valueOf(contextPtr));
            } else {
                this.connector.killConnection(client);
            }
        }
        return true;
    }
}
```