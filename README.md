100721001@qq.com
<!doctype html>
/*
echo "Hello, World!";
author：张三丰，ioszhangchao
100721001@qq.com
            // 磁盘路径
            'root'       => app()->getRootPath() . 'public/storage',
// +----------------------------------------------------------------------
// | Static Plugin for ThinkAdmin
// +----------------------------------------------------------------------
// | 版权所有 2014~2024 ThinkAdmin [ thinkadmin.top ]
// +----------------------------------------------------------------------
// | 官方网站: https://thinkadmin.top
// +----------------------------------------------------------------------
// | 开源协议 ( https://mit-license.org )
// | 免责声明 ( https://thinkadmin.top/disclaimer )
// +----------------------------------------------------------------------
// | gitee 代码仓库：https://gitee.com/zoujingli/think-plugs-static
// | github 代码仓库：https://github.com/zoujingli/think-plugs-static
// +----------------------------------------------------------------------
*/
<html>
    <head>
        <meta charset="UTF-8">
        <title>后台管理系统</title>
        <link rel="stylesheet" type="text/css" href="/public/css/admin/css/style.css" />
        <script>
            if (top.location != self.location) {
                parent.window.location.reload();

            }
        </script>
    </head>
    <body>

        <div class="header">
            <div class="logo"><img src="/public/css/admin/images/logo.png" style=" height: 60px;"></div>
        </div>
        <form method="post">
            <div class="main">
                <div class="login">
                    <div class="login-img"><img src="/public/css/admin/images/login-img.jpg"></div>
                    <div class="login-form">
                        <div class="login-form-tit">后台管理系统</div>
                        <div class="login-form-list">
                            <ul>
                                <li><input type="text" name="username"  placeholder="账　号" class="inp inp1"></li>
                                <li><input type="password"  name="password" placeholder="密　码" class="inp inp1"></li>
                                <li><input type="text"  name="code" placeholder="验证码" class="inp inp2"><a href="javascript:void(0);" class="yzm"><img id="codeimg" src="/service/code.php" alt="看不清楚点击刷新！" onclick="this.src = '/service/code.php?r=' + Math.random();" /></a><div class="clear"></div></li>
                                <li><input type="submit" value="登录" class="btn"></li>
                            </ul>
                        </div>
                    </div>
                    <div class="clear"></div>
                </div>
            </div>
            <input value="add" name="action" type="hidden" />
        </form>

    </body>
</html>
