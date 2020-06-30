# Introduction

Add developer documentation here.

# Block Attributes

This section covers information about block attributes.

## Default Attributes

This is how we handle default values for style block attributes. e.g. Question and Answer margin and padding.

(*Note: This might not be true for ALL style block attributes.*)

1. Set the default style via SCSS so that if this feature isn't included the free version default settings will still be applied. Users just won't be able to adjust them via block/shortcode attributes. In this case the block attribute can be an empty string.
2. In JSON add default to override SCSS value (if it exists for a particular attribute), or to just specify the base default value if no corresponding SCSS value exists.
    1. This can be a full JSON declaration or for some attributes (or is this for border only) you can specify an object with a literal property and string value). show examples.
4. If no default is specified in JSON then the inspector control will initially be empty.
