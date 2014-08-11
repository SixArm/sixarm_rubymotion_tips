# Geometry

See CGGeometry Reference
https://developer.apple.com/library/mac/documentation/graphicsimaging/Reference/CGGeometry/Reference/reference.html

### CGRectInset

To inset e.g. to make a margin, or padding, etc.:

```
smaller_rect = CGRectInset(rect, dx, dy)
```

### UIEdgeInsets

To make:

```
UIEdgeInsets UIEdgeInsetsMake (
   CGFloat top,
   CGFloat left,
   CGFloat bottom,
   CGFloat right
);
```

To adjust a rectangle by the given edge insets:

```
CGRect UIEdgeInsetsInsetRect (
   CGRect rect,
   UIEdgeInsets insets
);
```



