# CompassServant
这是一个仿魅族分贝仪的自定义 View，也可以叫Compass 或者 Dashboard，可以自己设置颜色渐变，
xml 支持4种颜色值，也可以使用 setGalaxyColors 方法设置更多种颜色渐变（never mind）。
                                                              ----中二病也要敲代码

# ScreenShot Video
![](https://github.com/dyzs/CompassServant/blob/master/video/compass_servant.gif)

# Features
This repo...

# Usage
Use it in xml
    <com.dyzs.compassservant.CompassServant
            android:id="@+id/compass_servant"
            android:layout_width="match_parent"
            android:layout_height="300dp"
            android:background="@color/black"
            app:cs_color_commander="3"
            />

and add listener and start tension when you reset pointer
    compass_servant.setServantListener(this);


# License

    Copyright (C) 2018 MisakaMikoto

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
