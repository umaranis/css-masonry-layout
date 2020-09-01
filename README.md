## Create Masonry Layout with CSS (Grid with variable-sized contents arranged in columns)

Source code for examples in [my article here](http://umaranis.com/2020/09/01/create-masonry-layout-with-css-grid-with-variable-sized-contents-arranged-in-columns/).

### Grid
  - :-1: doesn't handle variable size

![Masonry layout using Grid](http://umaranis.com/wp-content/uploads/2020/08/image.png)

### Flex
  - :+1: handles variable size
  - :-1: need to set the height of container to wrap items into the second column
  - :-1: doesn't put the second item in second column, rather puts it as the second item in first column

![Masonry layout using Flex](http://umaranis.com/wp-content/uploads/2020/08/image-1.png)

### Flex (Firefox)
  - :-1: perfect but only in firefox

![Masonry layout using Flex in Firefox](http://umaranis.com/wp-content/uploads/2020/08/image-2.png)
    
### column-count
  - :+1: handles variable size
  - :+1: no need to set the height of container to wrap items into the second column 
  - :-1: doesn't put the second item in second column, rather puts it as the second item in first column

![Masonry layout using column-count](http://umaranis.com/wp-content/uploads/2020/08/image-1.png)
