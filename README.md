# Gllllnimloader

## 简介：
### 这是一个nim的加载器，我用Python将它进行脚本化快速编译，与其它ShellCode加载器不同的是，它是一个PowerShell的加载器，出于PowerShell语言的灵活性，Gllllnimloader可以加载任何形式上的powershell

# 视频教程：https://www.bilibili.com/video/BV1r541117nK/

## 优点：
## 1.能够无视卡巴斯基和Windows Defender的内存扫描 
## 2.避免了敏感API,比如说VirtualAlloc、VirtualProtect、CreatProcess、WriteProcessMemory

## 缺点：
## 1.依赖于磁盘加载二进制文件
## 2.由于System.Management.Automation.dll存在兼容性问题，需要在有高版本的Powershell环境中才能运行，因此编译过后的二进制文件可能不能在win10/win2016以下的PC端运行。（我一直在尝试解决这个问题，如果你找到了解决方案，请马上与我联系）
          

# 用法：

## 提前配置好nim和python3的环境，需要在windows下进行编译

## 用CobaltStrike生成一个stageless的Powershell脚本
![image](https://user-images.githubusercontent.com/89376703/165303519-bce20d59-6ffb-4f09-bcfb-15dfc8c04d5e.png)

## 将Powershell脚本挂在公网，你也可以挂在pastebin(https://pastebin.com) 或者Github上，或者你也可以本地起一个http服务，然后输入网址链接即可编译

![image](https://user-images.githubusercontent.com/89376703/165304429-a801191f-3334-429f-80c4-27d74d475224.png)

![image](https://user-images.githubusercontent.com/89376703/165304900-f276f5d0-4f76-4823-a5f3-a89df583ca9b.png)

# 免杀效果：

### Karpersky
#### 仅弹计算器作演示，lasass dump暂时不考虑
![image](https://user-images.githubusercontent.com/89376703/165305458-d4a074d6-5adb-4cc6-9996-5d32abdc0b21.png)

### Windows Defender(win 2016)
![image](https://user-images.githubusercontent.com/89376703/165306383-b304bce6-1911-4671-8777-36557f06f0f8.png)

# 提示：
## 1.不要上传任何包括但不仅限于VirusTotal的公网沙箱，如果我发现样本失效过快，会停止该项目的维护
## 2.此项目仅用于教育目的，禁止将该技术用于非法途径


# 项目赞助：
### ![image](https://user-images.githubusercontent.com/89376703/165323770-c4e55fae-e747-47e0-8e17-57d1cb999741.png) 
# +知识星球学习免杀:

![image](https://user-images.githubusercontent.com/89376703/165324647-52f42926-cd0f-4da6-91cb-73bceffd5224.png)


