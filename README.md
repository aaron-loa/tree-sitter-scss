# tree-sitter-scss

SCSS grammar for [tree-sitter](https://github.com/tree-sitter/tree-sitter).

Based on [tree-sitter-css](https://github.com/tree-sitter/tree-sitter-css).

I want to extend this to be able to parse these:
``` sass

// 

.foo {
    --some-value: #{$variable};
}

$bar: (
    "color": #123456;
    "nested": (
        "nested_color: #abcdef;
    ),
);
```

I have never done this before, lets go!
