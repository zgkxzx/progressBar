自定义progressbar  http://write.blog.csdn.net/postedit/52090094
主要是分段时progressbar的颜色不一样
Canvas：https://developer.android.com/reference/android/graphics/Canvas.html
mProgressbarView.setProgress(30,true); 和 mProgressbarView.setProgress(50); 同一个控件只能调用一个

        <attr name="p_width" format="dimension"/> <!-- 控件宽度 -->
        <attr name="p_height" format="dimension"/><!-- 控件官高度 -->
        <attr name="p_maxValue" format="integer"/><!-- 控件progress最大值 -->
        <attr name="p_progressValue" format="integer"/><!--  当前 progress value -->
        <attr name="p_shapeType" format="enum"><!-- 控件类型 矩形，圆，圆角矩形 -->
            <enum name="rectangle" value="0" />
            <enum name="circle" value="1" />
            <enum name="square" value="2" />
        </attr>
        <attr name="p_progressColor" format="color"/><!-- progress 进度条颜色 -->
        <attr name="p_progressBackColor" format="color"/><!-- progress 背景 颜色 -->
        <attr name="p_progressSegmentColor" format="color"/><!-- progress 分段 颜色 -->
        <attr name="p_progressDoubleSegColor" format="color"/><!-- progress 分段间隔 颜色 -->
        <attr name="p_circle_radius" format="dimension"/><!-- 圆 半径 -->
        <attr name="p_circle_X_Y" format="dimension"/><!-- 圆 心 横坐标或者纵坐标 > 半径（正方形嘛）-->
        <attr name="p_showText" format="boolean"/><!-- 是否显示文字 -->
        <attr name="p_textSize" format="dimension"/><!-- 文字大小 -->
        <attr name="p_textLowColor" format="color"/><!-- 1/3 文字颜色 -->
        <attr name="p_textMiddleColor" format="color"/><!-- 1/3 - 2/3文字颜色 -->
        <attr name="p_textHighColor" format="color"/><!-- 2/3文字颜色 -->
        <attr name="p_square_radius" format="dimension"/><!-- 圆角矩形 半径-->
