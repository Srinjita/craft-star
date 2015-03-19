# craft-star
Parameterized star

## Install:

    $ npm install craft-star

## Parameters:

**sides:** To adjust the number of edges of the star

**radius:** To adjust radius of star

**height:** To adjust height of star

## Example:
  
```html
<craft>
    <craft name="star" module="craft-star"/>
    <lineup axis="x" spacing=0.5>
     <star></star>
     <star radius="7" sides="5" height="1"></star>
     <star radius="7" sides="7" height="2"></star>
     <star radius="9" sides="9"></star>
    </lineup>
</craft>
```

![example](example.png)
