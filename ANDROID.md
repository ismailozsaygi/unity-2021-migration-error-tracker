# Android

1. _"Custom Main Manifest" was not enabled in the template project._\
``Resolution: Enable "Custom Main Manifest" boolean in template project and export it again.``

2. _Error building Player: Incompatible color space with graphics API_\
``Resolution 0: Go to File> Build> Player Settings> Other Settings> Color Space > Change the option from Linear to Gamma.``\
``Resolution 1: Remove OpenGL2.0 and disable "Auto graphics API" option.``
