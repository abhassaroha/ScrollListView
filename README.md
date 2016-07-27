# ScrollListView

The class implements a bounded scroll view with list of items. The scroll view allows scrolling in directions:

* Horizontal
* Vertical

## Example

The code above includes an example implementation where drawable elements are created in cocos builder.

## Small memory footprint

The actual number of visual list items is bounded based on size of the scroll view container and individual list item. This keeps the memory foot print low even with a large list of items.

## Speed of scrolling

The logic is pretty optimal and scrolling of the list items is very smooth.

## Supported cocos version

The above code is implemented in cocos2dx version 3.6. The outline of the implementation can be used to port it to older versions.

# TODO

* add code to make the list multiple columns/rows based on if its vertical/horizontal scroll list.
