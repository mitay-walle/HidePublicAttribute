using UnityEngine;
#if UNITY_EDITOR
using UnityEditor;
#endif

public class HidePublicAttribute : PropertyAttribute { }

#if UNITY_EDITOR
[CustomPropertyDrawer(typeof(HidePublicAttribute))]
public class HidePublicDrawer : PropertyDrawer
{
    public override float GetPropertyHeight(SerializedProperty property, GUIContent label) { return 0f;}
    public override void OnGUI(Rect position, SerializedProperty property, GUIContent label) { }
}
#endif
