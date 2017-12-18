## Lowp

Used to specify the lowest available precision for a variable.

### Example
```glsl
lowp int lowpInt = 1;
lowp float lowpFloat = 1.0;

lowp ivec4 lowpIVec4 = ivec4(1, 1, 1, 1);
lowp vec4 lowpVec4 = vec4(1.0, 1.0, 1.0, 1.0);
```

### Description

The variable should be a float or int, or a vector or matrix of these types.
The exact range of precision from the qualifier is dependent on the specific OpenGL implementation.
Using a lower precision may result in an increase in performance but a loss in quality.
If no precision is specified, the highest available precision is used in vertex shaders and medium precision in fragment shaders.

### See Also

[mediump](/glossary/?search=mediump), [highp](/glossary/?search=highp), [precision](/glossary/?search=precision)
