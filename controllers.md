# Controllers

To init without a nib or bundle:

```
def init
  initWithNibName(nil, bundle:nil)
  self
end
```

To get a typical controller's base name:

```
self.class.name.sub(/Controller$/,'')
```
