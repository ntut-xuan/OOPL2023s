# Game Framework Practice

After you finished to build the project, you should start to practice the game framework with `game-framework-practice` project.



## Stage 1. Change Image

Change the image `gray.bmp` to `giraffe.bmp`, you should do it when loading the image.



## Stage 2. Move the image

Move the image `giraffe.bmp` to specific rectangle area.

You should do it in `OnKeyDown(UINT nChar, UINT nRepCnt, UINT nFlags)` function with virtual key detect.

The value of `nChar` will return what key user pressed.



You can check the Virtual-Key Code from [here](https://learn.microsoft.com/zh-tw/windows/win32/inputdev/virtual-key-codes).

```cpp
if (nChar == some_key){
	// Do something...
}
```

Move the `giraffe.bmp` image with `CMovingBitmap::SetTopLeft(x, y)` function.



## Stage 3. Image interactive

Let the `chest.bmp` disappear when `giraffe.bmp` interact with `chest.bmp`.

Check two image is overlap on `OnMove()` function.



## Stage 4. Image animation (infinite)

Let the `bee.bmp` have infinite two-frame animation. Check `CMovingBitmap::SetAnimation(time, once)` function.



## Stage 5. Images interactive

Let the doors open when `giraffe.bmp` overlap the door.

You can load the door `CMovingBitmap` object with two images (`door_open.bmp` and `door_close.bmp`), and select and show the second image when `graffe.bmp` overlap the doors. Check `CMovingBitmap::SelectShowBitmap()` function.



## Stage 6. Image animation (Finite and toggle)

Let the ball count-down with animation, the animation should show once.

Check `CMovingBitmap::SetAnimation()` and set `once=true`.

Note: When the animation has been set to execute once, you should **toggle the animation** with `CMovingBitmap::ToggleAnimation()`. Once you toggle the animation, the animation will start and only execute once.

