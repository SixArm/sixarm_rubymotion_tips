# Categories

To add new methods to existing classes, Objective-C uses "categories", and Ruby uses re-opening classes.

Example:

```oc
@interface UIBarButtonItem (ImageItem)
+ (UIBarButtonItem*)barItemWithImage:(UIImage*)image target:(id)target action:(SEL)action;
@end
```

```ruby
class UIBarButtonItem
  def self.barItemWithImage(image, target: target, action: action)
    ...
  end
end
```
