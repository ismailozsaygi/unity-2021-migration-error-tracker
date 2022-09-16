# Editor

1. _Assets/FacebookSDK/Examples/Scripts/ConsoleBase.cs(243,42): error CS0619: 'ScreenOrientation.Landscape' is obsolete: 'Use LandscapeLeft instead (UnityUpgradable) -> LandscapeLeft'_\
``Resolution: Go to the exact place of compile error and apply suggested API call.``

2. _A native collection has not been disposed, resulting in a memory leak. Enable full stack traces to get more detail._\
``There are no resolutions for this issue yet.``

3. ``Could not find the member 'm_PropertyDrawer' on internal Unity type 'UnityEditor.PropertyHandler'; cannot correctly set internal Unity state for drawing of custom Unity property drawers - drawers which call EditorGUI.PropertyField or EditorGUILayout.PropertyField will be drawn partially twice.
UnityEngine.Debug:LogError (object)
Sirenix.OdinInspector.Editor.UnityPropertyHandlerUtility:CouldNotFindMemberError (System.Type,string) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/Value Drawers/UnityPropertyHandlerUtility.cs:141)
Sirenix.OdinInspector.Editor.UnityPropertyHandlerUtility:.cctor () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/Value Drawers/UnityPropertyHandlerUtility.cs:106)
Sirenix.OdinInspector.Editor.AbstractTypeUnityPropertyDrawer`3<RocketUtils.Editor.SerializableDictionary.SerializableDictionaryPropertyDrawer, RocketUtils.SerializableDictionary.SerializableDictionaryBase, CpiTemplate.Game.Scripts.Behaviours.CharacterItemDictionary>:.ctor () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/Value Drawers/AbstractTypeUnityPropertyDrawer.cs:35)
(wrapper dynamic-method) object:Sirenix.OdinInspector.Editor.AbstractTypeUnityPropertyDrawer`3[[RocketUtils.Editor.SerializableDictionary.SerializableDictionaryPropertyDrawer, com.rocket.rocketutils.editor, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null],[RocketUtils.SerializableDictionary.SerializableDictionaryBase, com.rocket.rocketutils, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null],[CpiTemplate.Game.Scripts.Behaviours.CharacterItemDictionary, Assembly-CSharp, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null]]_FastCreator ()
Sirenix.OdinInspector.Editor.DefaultDrawerChainResolver:CreateDrawer (System.Type) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/Drawer Chains/DefaultDrawerChainResolver.cs:54)
Sirenix.OdinInspector.Editor.DefaultDrawerChainResolver:GetDrawerChain (Sirenix.OdinInspector.Editor.InspectorProperty) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/Drawer Chains/DefaultDrawerChainResolver.cs:30)
Sirenix.OdinInspector.Editor.InspectorProperty:GetActiveDrawerChain (bool&) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/InspectorProperty.cs:534)
Sirenix.OdinInspector.Editor.InspectorProperty:GetActiveDrawerChain () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/InspectorProperty.cs:521)
Sirenix.OdinInspector.Editor.InspectorProperty:Draw (UnityEngine.GUIContent) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/InspectorProperty.cs:675)
Sirenix.OdinInspector.Editor.InspectorProperty:Draw () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/InspectorProperty.cs:658)
Sirenix.OdinInspector.Editor.Drawers.UnityObjectRootDrawer`1<CpiTemplate.Game.Scripts.Behaviours.CharacterBehaviour>:DrawPropertyLayout (UnityEngine.GUIContent) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/Value Drawers/UnityObjectRootDrawer.cs:25)
Sirenix.OdinInspector.Editor.OdinDrawer:DrawProperty (UnityEngine.GUIContent) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/OdinDrawer.cs:109)
Sirenix.OdinInspector.Editor.InspectorProperty:Draw (UnityEngine.GUIContent) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/InspectorProperty.cs:770)
Sirenix.OdinInspector.Editor.PropertyTree:DrawProperties () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/PropertyTree.cs:485)
Sirenix.OdinInspector.Editor.PropertyTree:Draw (bool) (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Core/PropertyTree.cs:389)
Sirenix.OdinInspector.Editor.OdinEditor:DrawTree () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/OdinEditor.cs:93)
Sirenix.OdinInspector.Editor.OdinEditor:DrawOdinInspector () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/OdinEditor.cs:216)
Sirenix.OdinInspector.Editor.OdinEditor:OnInspectorGUI () (at X:/Repositories/sirenix-development/Sirenix Solution/Sirenix.OdinInspector.Editor/Drawers/OdinEditor.cs:85)
UnityEngine.GUIUtility:ProcessEvent (int,intptr,bool&)``
