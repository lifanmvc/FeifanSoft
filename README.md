# FeifanSoft
管理信息平台开发工程

下载用打开项目，打开文件【Entity.tt】,设置ms sql 数据库链接字符串：
string connectionString="Server=服务器地址;Database=数据库名称;User ID=sa;Password=密码;";
设置正确后，模板运行自动生成实例类。编译，把 FeifanSoft.ORM.dll 文件拷贝到站点，更新院文件。
如果无法覆盖，先停止站点，覆盖后再启动站点。

注意：
【Entity.tt】中，不要修改命名空间。
