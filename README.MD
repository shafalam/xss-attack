# Demo:

## Possibity-1:
 Write the below code in the message area:
 ```
    <script>alert("Hacked")</script>
 ```

 It is likely that it won't work. Because, modern browser doesn't let the innerHTML script to run.

## Possibilty - 2:
Write the below code in the image are:
```
someInValidImageAddress" onerror="alert('hacked')"
```

In this case it might work. What happens, is that in this case, the image link is invalid. As a result, the onerror handler function will be called. In this case, it's just a alert banner. However, it can be much more malicious.




