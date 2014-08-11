# Table View


## Table View Cell

To set the cell color, adjust the cell immediately before it is displayed:

```
def tableView(tableView, willDisplayCell:cell, forRowAtIndexPath:indexPath)
  cell.textLabel.textColor = UIColor.redColor
  cell.detailTextLabel.textColor = UIColor.greenColor
  cell.backgroundColor = UI.blackColor
end
```

(Note that setting the colors in the `TableViewCell` class does not work, due to an issue with iOS always resetting the cell colors to the defaults)