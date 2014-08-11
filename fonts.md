# Fonts

To list all the installed fonts:

```
UIFont.familyNames.sort
```

To add a custom font:

```Rakefile
Motion::Project::App.setup do |app|
  app.fonts = ['foo.ttf']
end
```
