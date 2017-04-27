# reading
inteliJ

在下载下来后 先去file/settings, 或者如果你是MAC用户 去inteliJ / preference/搜Maven 选import Maven Projects automatically
然后右侧有个ant build 双击后应该有个tomcat 7 -run 直接双击运行
会弹出网页  输入URL = http://localhost:8080/test-project/app/index.html#/home
或者你可以用http://localhost:8080/test-project/test
前段的配置 你要在整体文件夹运行npm install -g bower (如果你是windows run as admin)
然后在
webApp 文件下 运行 npm install 与 bower install

你可以执行 grunt watch 网页任何修改都会自动refresh
