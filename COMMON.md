# Editor

1. _Assets/FacebookSDK/Examples/Scripts/ConsoleBase.cs(243,42): error CS0619: 'ScreenOrientation.Landscape' is obsolete: 'Use LandscapeLeft instead (UnityUpgradable) -> LandscapeLeft'_\
``Resolution: Go to the exact place of compile error and apply suggested API call.``

2. _A native collection has not been disposed, resulting in a memory leak. Enable full stack traces to get more detail._\
``There are no resolutions for this issue yet.``

3. _Popups are buggy on their first open call._\
``Resolution: Set popup local scale to Vector3.zero on open.``

4. _Inspector bugs out and becomes unscaleable._\
``Resolution 0: Updated version of Unity to 2021.3.11f1, let's see if this fixed it.``

5. Could not find the member 'm_PropertyDrawer' on internal Unity type 'UnityEditor.PropertyHandler'; cannot correctly set internal Unity state for drawing of custom Unity property drawers - drawers which call EditorGUI.PropertyField or EditorGUILayout.PropertyField will be drawn partially twice.
``Resolution: Try to update Odin inspector for 2021.``
