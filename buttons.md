# Buttons

To create a button using typical iOS methods:

```
o = UIButton.buttonWithType(UIButtonTypeCustom)
o.setTitle(title, forState: UIControlStateNormal)
o.setTitleColor(color, forState: UIControlStateNormal)
o.setFont(font)
o.titleLabel.font = font
o.showsTouchWhenHighlighted = true
o.sizeToFit
o.frame = [[x,y],[w,h]]
view.addSubview(o)
```

To create a button using MotionAwesome:

```
MotionAwesome.button(:user, size: 40, text:"USER") do |o|
end
```

To create a button using our custom UIButtonX:

```
o = UIButtonX.make(title: title, font: font, target: self, action: "action")
```

