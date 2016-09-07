- 在Android的sdk21(5.0)以上的版本中，用到之前的API，如下(在sdk23版本中会报错)：
![image](https://github.com/xx753940262/notes/raw/master/images/sdkdif.png)

- 修改方法：在app目录中的build.gradle中添加代码 
```python
useLibrary 'org.apache.http.legacy'
```
![image](https://github.com/xx753940262/notes/raw/master/images/build_gradle.png)