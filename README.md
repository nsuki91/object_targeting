## Using


```bash
python main.py --filter HSV --webcam
```

## Working method
The algorithm tracks the object masked with filters by the user. Filters work with HSV color space. It masks image with max and min HSV values. After filtering algorithm selects the biggest masked object and locates the position of the object on the screen. It defines how to centralize objects to the user.
