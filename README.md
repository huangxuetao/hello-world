# hello-world
my first repository


<br><br>
一、在github上创建新的repository（代码库）  
//命令行操作git管理自己的代码
<br><br>
二、在本地git clone (+url)创建的repository
<br><br>
三、cd fileName  进入文件夹利用webpack生成项目(yarn init 初始化 或install 相关依赖)
<br><br>
四、配置相关文件，写代码
<br><br>
五、提交代码到GitHub上
<br>
1、`git status`  //查看当前git项目的一个状态
<br>
2、`git add -A` //将所有未track的文件一次性添加进来(-A 可替换为具体想track的文件名)
<br>
3、`git commit -m "提交说明"` // 提交代码并说明
<br>
4、`git push` /将所有代码push到gitHub上。
<br>
六、 gitignore
有时候我们不想把某些文件上传到github，但是未上传的文件在`git status`中会显示，有的人就感觉很难受
<br>
这时就可以用到gitignore，在仓库的根目录下创建`.gitignore`文件，然后在文件中配置想被忽略的文件（直接填写文件名）
