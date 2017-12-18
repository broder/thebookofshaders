## Mediump

Used to specify a variable precision between the highest and lowest.

### Example
```glsl
mediump int mediumpInt = 1;
mediump float mediumpFloat = 1.0;

mediump ivec4 mediumpIVec4 = ivec4(1, 1, 1, 1);
mediump vec4 mediumpVec4 = vec4(1.0, 1.0, 1.0, 1.0);
```

### Description

The variable should be a float or int, or a vector or matrix of these types.
The exact range of precision from the qualifier is dependent on the specific OpenGL implementation.
Using a lower precision may result in an increase in performance but a loss in quality.
If no precision is specified, the highest available precision is used in vertex shaders and medium precision in fragment shaders.

### See Also

[lowp](/glossary/?search=lowp), [highp](/glossary/?search=highp), [precision](/glossary/?search=precision)
