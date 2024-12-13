<p align="center">
  <img src="https://github.com/Ationet/ationetdocs/raw/master/Content/Images/ATIOnetLogo_250x70.png" />
</p>

|**Document information**||
|--- |--- |
|**File:**|README_RN_ENG_API.md|
|**Version Doc:**|1.0|
|**Release Date:**|Dec 12, 2024|
|**Author:**|ATIONET LLC|

|**Changes Log**|||
|--- |--- |--- |
|**Version**|**Date**|**Change Summary**|
|1.0|Dec 12, 2024|- Initial version


# Contents
-[API Native](#api-native)

-[API Rest](#api-rest)

# API Native

### December 02, 2024
- The CPInterfaceAPI role can now be assigned to multiple companies with the same user


# API Rest

### December 02, 2024
- Change in Rest Users API to void users notification
  - A new boolean parameter is added to the API https://api.ationet.com/Users that allows to indicate whether or not the welcome email to ATIONET will be sent to the user who was created (or to whom the new role was added).
By default, this parameter will allow the welcome email to be sent to the user.
    
