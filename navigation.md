# Navigation

To show the navigation bar back button as just an arrow without any text, we set a blank title immediately before pushing:

```
navigationItem.backBarButtonItem =
  UIBarButtonItem.alloc.initWithTitle(
    "",
    style: UIBarButtonItemStylePlain,
    target: nil,
    action: nil
  )
navigationController.pushViewController(controller, animated: true)
```
