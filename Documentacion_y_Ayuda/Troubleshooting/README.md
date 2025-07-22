# Solución de Problemas

Recopilación de errores comunes y enlaces de ayuda para Unity.

## Shader de pantalla completa

- [Guía oficial](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@15.0/manual/fullscreen-shader.html) - Cómo implementar shaders a pantalla completa.

## Mensajes de error

Agradecimientos a [este post](https://answers.unity.com/questions/155200/stuff-is-going-wacky-checklist-compiler-errors-syn.html) por recopilar muchos mensajes de error.

### !slot->GetLocalAABB().IsValid()

Ocurre cuando un objeto tiene una escala de cero o un valor muy grande.

- <https://answers.unity.com/questions/8276/what-causes-error-sh-maabbisvalid.html>
- <https://answers.unity.com/questions/11016/what-does-slot-getlocalaabbisvalid-mean.html>

### "Some objects were not cleaned up when closing the scene"

Sucede cuando se crea un GameObject mientras la escena se cierra. Evita crear objetos en `OnDestroy`.

- <https://answers.unity.com/questions/1274772/some-objects-were-not-cleaned-up-when-closing-the-4.html>
- <https://feedback.unity3d.com/suggestions/improve-some-objects-were-not-cleaned-up-when-closing-the-scene-error-message>

## Enlaces adicionales

- [Error: m_CoroutineEnumeratorGCHandle == 0](https://answers.unity.com/questions/158917/error-quotmcoroutineenumeratorgchandle-0quot.html)
- [Internal Error: Too many pairs created, new pairs will be ignored](https://answers.unity.com/questions/359835/internal-error-too-many-pairs-created-new-pairs-wi.html)
- [Mecanim issue Animator has not been initialized](https://forum.unity.com/threads/mecanim-issue-animator-has-not-been-initialized.158874/)
- [Destroying asset is not permitted to avoid data lose](https://answers.unity.com/questions/164283/destroying-assets-is-not-permitted-to-avoid-data-l.html)
- [Solved Screen Position out of View Frustum](https://forum.unity.com/threads/solved-screen-position-out-of-view-frustum.60851/)


