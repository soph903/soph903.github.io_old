# minimal mistake: some settings

### change page font size

add font-size attribute in _page.scss -> page content -> class p 

```
p{
    font-size: 0.75em;
}
```


### change the position of navi menu btn

_navigation.scss -> visible-links

``` 
justify-content: flex-start;
```

default: flex-end, the navi menu btns locate at the top right of the page
changed to flex-start such that the btns locats at the top left

