#pureUI

基于purcss和Appframework.js的轻量级移动框架。

#使用

##面板

类似AFUI面板使用方法， \#content>div 第一个div为默认显示。可使用data-selected="true"指定默认显示面板。例如：

            <div id="content" class="content">
                <div id="intro">
                    <h2 class="content-subhead">什么是pureUI</h2>
                    <p>
                        基于purcss和Appframework.js的轻量级移动框架。
                    </p>
                </div>
                <div id="about">
                    <h2 class="content-subhead">关于pureUI</h2>
                    <p>
                        基于purcss和Appframework.js的轻量级移动框架。
                    </p>
                </div>
                <div id="home" data-selected="true">
                    <h2 class="content-subhead">Home</h2>
                    <p>
                        基于purcss和Appframework.js的轻量级移动框架。
                    </p>
                </div>
            </div>

面板加载后执行js:data-load

#缓存

$.ui.cache

 - hashContentDivSelected 是否手动设定默认面板
 - activeContentDiv 当前活动面板的id

#CSS补充

文本对其: .text-left/center/right