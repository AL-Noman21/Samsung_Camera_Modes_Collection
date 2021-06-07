# Note :  Add theme into camera-feature.xml 

Location - system/cameradata folder
or
system/system/cameradata folder

Please add order serial number in every feature .



# 01 - Selfie Focus .

    <local name="SHOOTING_MODE_LIVE_FOCUS" front="SELFIE_FOCUS" enable="true" more="false" order=" Serial Number "/>

# 02 - Sports Mode.
    
    <local name="SHOOTING_MODE_SPORTS" back="SPORTS" enable="true" more="true" order=" Serial Number "/>

# 03 - Night Mode .

    <local name="SHOOTING_MODE_NIGHT" back="NIGHT" front="NIGHT" enable="true" more="true" order=" Serial Number "/>

# 04 - Food Mode.

    <local name="SHOOTING_MODE_FOOD" back="FOOD" enable="true" more="true" order=" Serial Number "/>

# 05 - QR Code Scan.

    <local name="SUPPORT_QR_CODE_DETECTION" value="true" />

# 06 - 2X Zoom .

    <local name="BACK_TELE_CAMERA_ID" value="50"/>

# 07 - Floating Cemera Button.

    <local name="SUPPORT_FLOATING_CAMERA_BUTTON" value="true" />

# 08 - Camera Watermark.

    <local name="SUPPORT_WATERMARK" value="true" />
    <local name="SUPPORT_AUTO_WATERMARK" value="true" />
    <local name="CAMERA_AUTO_WATERMARK_NUMBER_OF_CAMERAS" value=" Your Devices Camera Number " />
    <local name="SUPPORT_CAMERA_AUTO_WATERMARK_MODEL_NAME" value="Your Device Name " />

# 09 - Intelligent recognition.

    <local name="SUPPORT_INTELLIGENT_GUIDE_TIPS" value="true" />
    <local name="SUPPORT_INTELLIGENT_RECOGNITION_TIPS" value="true" />
    <local name="SUPPORT_ADDITIONAL_SCENE_DOCUMENT_SCAN" value="true" />
    <local name="SUPPORT_SMART_SCAN_MANUAL_CROP" value="true" />

# 10 - Composition guide.

    <local name="SUPPORT_COMPOSITION_GUIDE" value="true"/>

# 11 - Support HEIF format picture.
   
    <local name="SUPPORT_HEIF_FORMAT" value="true"/>

# 12 - Ar Doodle 

    <local name="SHOOTING_MODE_AR_DOODLE" back="AR_DOODLE" enable="true" more="true" order="Serial Number"/>

# 13 - Pro Mode 
    
    <local name="SHOOTING_MODE_PRO" back="PRO" enable="true" more="true" order="Serial Number"/>

# 14 - Tap to take picture

    <local name="SUPPORT_TAP_TO_TAKE_PICTURES" value="true" />

# 15 - Floating camera button 

    <local name="SUPPORT_FLOATING_CAMERA_BUTTON" value="true"/>

# 16 - Live blur 

    <local name="SUPPORT_LIVE_BLUR" value="true" />

# 17 - Video stabilistion 

    <local name="SUPPORT_VIDEO_STABILISATION_MENU_IN_SETTING" value="true" />
  
