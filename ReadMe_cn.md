# action-ipadown
使用 Github Actions 下载商店或者旧版 IPA，不需要电脑!

**注意: 当前不支持有双重验证(2FA)的 Apple ID**.

# 功能
* 购买和下载应用
* 下载旧版本的应用程序
* 查询App版本历史
* 根据 bundleID 或 appID 查找应用信息


# 用法
## 准备工作
1. Fork 本仓库
> ![image](https://user-images.githubusercontent.com/116707514/198005171-4232e6dd-bb0b-4bb0-80f1-3358fce459cd.png)
2. 在 Fork 后的仓库中允许 Action
> * 单击工具栏中的 `Actions`
> * 点击 `I understand my workflows, go ahead and enable them`
> ![image](https://user-images.githubusercontent.com/5344431/167505409-ef077008-2450-4e2d-9d43-2067244ac931.png)
3. 开始使用

## 开始使用
### 下载商店 ipa
1. 在 `Actions` 页面左侧点击 `IPA Down`
> ![image](https://user-images.githubusercontent.com/5344431/167505630-1a741d9c-69de-470c-978e-1b8944dcfd3b.png)
2. 在右侧点击 `Run workflow`
> ![image](https://user-images.githubusercontent.com/5344431/167505748-52e0bba9-b9ec-44e1-9370-4452d3c3c66b.png)
3. 输入你的 Apple ID 和密码，Operation 输入 download (具体说明见后面)，输入 bundle id ([可以在这里查](https://armconverter.com/appinfo/cn))和商店地区等
> ![image](https://user-images.githubusercontent.com/116707514/198008371-41b2fcb6-995e-440b-8ac0-c5dab9ee5c23.png)
4. 点击 `Run workflow`
5. 在仓库的 `Release` 页面找到 IPA 文件然后就可以下载安装了
> ![image](https://user-images.githubusercontent.com/5344431/167506938-c3e3529c-ee91-4661-a251-a12a2d0576cb.png)

**如果有运行失败，请检查你的 ID 有没有开启双重验证，或者是否有参数设置错误。**

### Operation 说明
