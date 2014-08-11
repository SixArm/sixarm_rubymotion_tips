# Text

### Text Field

To set the color of the border:

  * Import QuartzCore framework in you class:

```ruby
# Rakefile
app.frameworks << 'QuartzCore'
```

```oc
#import <QuartzCore/QuartzCore.h>
```

Then:

```ruby
textField.layer.cornerRadius = 8
textField.layer.masksToBounds = true
textField.layer.borderColor = UIColor.redColor.CGColor
textField.layer.borderWidth = 1
```

```oc
textField.layer.cornerRadius = 8.0f;
textField.layer.masksToBounds = YES;
textField.layer.borderColor = [[UIColor redColor]CGColor];
textField.layer.borderWidth = 1.0f;
```


To revert:

```ruby
textField.layer.cornerRadius = 0
textField.layer.masksToBounds = true
textField.layer.borderColor = UIColor.blackColor.CGColor
textField.layer.borderWidth = 0
```

```oc
textField.layer.cornerRadius = 0.0f;
textField.layer.masksToBounds = YES;
textField.layer.borderColor = [[UIColor blackColor] CGColor];
textField.layer.borderWidth = 0.0f;
```

