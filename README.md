## Using


```bash
python main.py --filter HSV --webcam
```

## Working method
Algorithm tracks the object masked with filters by user. Filters work with HSV color space. It masks image with max and min HSV values.
After filtering algorithm selects biggest masked object and locates position of object on screen. It defines how to centralize objects to the user.
