# android_device_oneplus_oneplus2
device tree for lineage latest commits (build success on pixys os). 
TO NUKE: touch folder and sepolicy/hal_lineage_touch.te.

if you get this error: error: libaudiopolicyservice (SHARED_LIBRARIES android-arm64) missing libaudiopolicymanager (SHARED_LIBRARIES android-arm64)
 -- change "USE_CUSTOM_AUDIO_POLICY" from 1 to 0 in BoardConfig.mk

NUKE file_contexts from their respective directories if file_context error arises: 
device/qcom/sepolicy-legacy/common 
device/qcom/sepolicy-legacy/legacy-common 
device/qcom/sepolicy-legacy/msm8994 
system/sepolicy/vendor 
device/qcom/sepolicy-legacy/test 
device/qcom/sepolicy-legacy/legacy-common 
device/pixys/sepolicy/qcom/common 
device/oneplus/oneplus2/sepolicy
