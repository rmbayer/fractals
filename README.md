# Sierpinski Fractals
The noetbook provided generates Sierpinski fractals from various polygons based on [n-flakes](https://en.wikipedia.org/wiki/N-flake)

The algorithm, at it's simplest form is

## Step 1
![](images/Slide1.PNG)

## Step 2
![](images/Slide2.PNG)

## Step 3
![](images/Slide3.PNG)

## Step 4
![](images/Slide4.PNG)

## Step 5
![](images/Slide5.PNG)

## Step 6 is repeated
![](images/Slide6.PNG)

## This will yeild
![](images/hexa_sns.gif)

The `fractile(sides=3, size=3, frac=(2/3), points=100000)` function arguments can be manipulated to create variations of the fractas produced

```
sides (int) - Number of sides for the polygon
size (int) - Length of polygon sides
frac (float) - Ditance to the draw the generated point
points (int) - Number of points to draw
```

```fractile_gif()``` funtion will animate points 1 by 1 for a more precise, however slower, animated plot

```fractile_sns_gif()``` funtion will animate points by iterations of 50, for a faster animated plot


