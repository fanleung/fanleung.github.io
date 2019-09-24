<!-- ---
layout: page
type: about
---


本人擅长嵌入式开发，蓝牙开发，会 Python / Matlab.

如有项目合作或工作介绍，请联系我 :p

邮箱  ：619772263@qq.com

github: <a href="https://github.com/fanleung">https://github.com/fanleung</a> -->


<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="//cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
        <style>
            .main ul{
                display: none;
            }
        </style>
    </head>
    <body>
        <ul>
            <li class="main">
                <a href="#">菜单项1</a>
                <ul>
                    <li>
                        <a href="#">子菜单项11</a>
                        <ul>
                            <li>
                                <a href="#">子菜单11-1</a>
                                <ul>
                                    <li><a>子菜单111-1</a></li>
                                    <li><a>子菜单111-2</a></li>
                                    <li><a>子菜单111-3</a></li>
                                </ul>
                            </li>
                            <li><a>子菜单11-2</a></li>
                            <li><a>子菜单11-3</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">子菜单项12</a>
                        <ul>
                            <li><a>子菜单12-1</a></li>
                            <li><a>子菜单12-2</a></li>
                            <li><a>子菜单12-3</a></li>
                        </ul>
                    </li>
                </ul>
            </li>
            <li class="main">
                <a href="#">菜单项2</a>
                <ul>
                    <li>
                        <a href="#">子菜单项21</a>
                        <ul>
                            <li><a>子菜单2-1</a></li>
                            <li><a>子菜单2-2</a></li>
                            <li><a>子菜单2-3</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">子菜单项22</a>
                    </li>
                </ul>
            </li>
            <li class="main">
                <a href="#">菜单项3</a>
                <ul>
                    <li>
                        <a href="#">子菜单项31</a>
                    </li>
                    <li>
                        <a href="#">子菜单项32</a>
                    </li>
                </ul>
            </li>
        </ul>
        <script>
            $(document).ready(function () {
                $(".main  a").click(
                        function () {
                            $(this).next().toggle();
                        }
                );
            });
        </script>
    </body>
</html>