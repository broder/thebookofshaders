## Precision

Used to specify the default precision for a given type.

### Example
```glsl
precision highp float;
precision mediump float;
```

### Description

The type should be a float or int, or a vector or matrix of these types.
The exact range of precision from the qualifier is dependent on the specific OpenGL implementation.
Using a lower precision may result in an increase in performance but a loss in quality.
If no precision is specified, the highest available precision is used in vertex shaders and medium precision in fragment shaders.

### See Also

[lowp](/glossary/?search=lowp), [mediump](/glossary/?search=mediump), [highp](/glossary/?search=highp)
