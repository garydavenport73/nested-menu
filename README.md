# Simple Hamburger Menu
## This makes a collapsible menu which will show or hide all siblings:

```
    <div>
        <div class="nested-menu">≡</div>
        <div>brother</div>
        <div>sister</div>
        <div>whatever else</div>
    </div>
```
## And you can nest menus within menus:
```
    <div>
        <div class="nested-menu">≡</div>
        <div>-brother</div>
        <div>
            <div class="nested-menu">-sister</div>
            <div>--nephew</div>
        </div>
        <div>-whatever else</div>
    </div>
```