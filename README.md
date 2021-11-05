# HW_03_ZQN

In this project we finish 2 tasks



> todo 1: Refresh every second to keep the pointer moving
>
> ```kotlin
> handler.postDelayed({invalidate()},1000)
> ```



> todo 2: Drawing the minute hand and hour hand
>
> ```kotlin
> private fun drawNeedles(canvas: Canvas) {
>     ...
> 	drawPointer(canvas, POINTER_TYPE_MINUTES, nowMinutes )
>     ...
> }
> 
> 
> private fun drawPointer(canvas: Canvas, pointerType: Int, value: Int) {
>     ...
>             POINTER_TYPE_MINUTES -> {
>                 degree = value * UNIT_DEGREE
>                 needlePaint.color = Color.RED
>                 pointerHeadXY = getPointerHeadXY(minutePointerLength, degree)
>             }
>     ...
> }
> ```

