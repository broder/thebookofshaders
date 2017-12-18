## Highp

Used to specify the highest available precision for a variable.

### Example
```glsl
highp int highpInt = 1;
highp float highpFloat = 1.0;

highp ivec4 highpIVec4 = ivec4(1, 1, 1, 1);
highp vec4 highpVec4 = vec4(1.0, 1.0, 1.0, 1.0);
```

### Description

The variable should be a float or int, or a vector or matrix of these types.
The exact range of precision from the qualifier is dependent on the specific OpenGL implementation.
Using a lower precision may result in an increase in performance but a loss in quality.
If no precision is specified, the highest available precision is used in vertex shaders and medium precision in fragment shaders.

### See Also

[lowp](/glossary/?search=lowp), [mediump](/glossary/?search=mediump), [precision](/glossary/?search=precision)
