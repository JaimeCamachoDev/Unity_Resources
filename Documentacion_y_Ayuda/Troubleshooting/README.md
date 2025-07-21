# Troubleshooting

Recopilación de errores comunes y soluciones en Unity.

## Shader fullscreen

https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@15.0/manual/fullscreen-shader.html

## Error Messages

Special thanks to [este post](https://answers.unity.com/questions/155200/stuff-is-going-wacky-checklist-compiler-errors-syn.html) por muchos de los mensajes de error.

### !slot->GetLocalAABB().IsValid()

This can be caused by an object having a scale of zero or a very large number.
- <https://answers.unity.com/questions/8276/what-causes-error-sh-maabbisvalid.html>
- <https://answers.unity.com/questions/11016/what-does-slot-getlocalaabbisvalid-mean.html>

### "Some objects were not cleaned up when closing the scene"

This error appears when a GameObject is created while the scene is closing. Avoid creating objects in `OnDestroy`.

- <https://answers.unity.com/questions/1274772/some-objects-were-not-cleaned-up-when-closing-the-4.html>
- <https://feedback.unity3d.com/suggestions/improve-some-objects-were-not-cleaned-up-when-closing-the-scene-error-message>

## Additional links

- [Error: m_CoroutineEnumeratorGCHandle == 0](https://answers.unity.com/questions/158917/error-quotmcoroutineenumeratorgchandle-0quot.html)
- [Internal Error: Too many pairs created, new pairs will be ignored](https://answers.unity.com/questions/359835/internal-error-too-many-pairs-created-new-pairs-wi.html)
- [Mecanim issue Animator has not been initialized](https://forum.unity.com/threads/mecanim-issue-animator-has-not-been-initialized.158874/)
- [Destroying asset is not permitted to avoid data lose](https://answers.unity.com/questions/164283/destroying-assets-is-not-permitted-to-avoid-data-l.html)
- [Solved Screen Position out of View Frustum](https://forum.unity.com/threads/solved-screen-position-out-of-view-frustum.60851/)


