# Font Awesome

To get Font Awesome:

```
font = UIFont.fontWithName("FontAwesome", size: 24)
```

To set a Unicode character, e.g. for a Font Awesome icon "fa-user":

```
icon = '0xf007'.hex.chr(Encoding::UTF_8)
```

To use MotionAwesome to make a Font Awesome buttons:

```
MotionAwesome.button(:camera, size: 40, text: "Photos") do |o|
  ...
end


### FontAwesomeKit pod

The `FontAwesomeKit` pod creates icon images from the FontAwesome font. 

Be sure to download the font file `FontAwesome.otf` and add it to the resources, e.g. copy it to `./resources/`

Be aware there's a bug -- to work around it, do not lazy load. 

See https://github.com/PrideChung/FontAwesomeKit/blob/master/KnownIssues.md


### motion-iconic gem

The `motion-iconic` gem is a wrapper of `FontAwesomeKit`. 

It looks promising but forces an older cocoapods:

```
  In Gemfile:
    motion-iconic (>= 0) ruby depends on
      motion-cocoapods (~> 1.4.0) ruby
```