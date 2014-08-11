# RubyMotion Tips

This page collects the various tips we use.

Feel free to add yours and do a pull request.


## Fonts

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

## Layout

Apple iOS official layout height values:

```
STATUS_BAR_HEIGHT = 20
NAVIGATION_BAR_HEIGHT = 44
TAB_BAR_HEIGHT = 49
TABLE_VIEW_CELL_HEIGHT = 44
```


