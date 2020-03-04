# Java-IO
## 分类
    按流向分：
               输入流 读取数据
               输出流 写出数据
              
    按数据类型分：
                字节流：
                        字节输入流   InputStream
                        字节输出流   OutputStream
                      
                字符流：
                        字符输入流   Reader
                        字符输出流   Writer
                   
## 字节流实现类

### 基本字节流
    FileInputStream
    FileOutputStream

### 高效字节流 
    BufferedInputStream
    BufferedOutputStream

## 转换流   
    字符 = 字节 + 编码
    
    InputStreamReader(InputStreaem is)  用默认编码读取数据
    InputStreamReader(InputStreaem is,String charsetName)  用指定编码读取数据
    
    OutputStreamWriter(OutputStream os)  根据默认编码把字节流转换为字符流
    OutputStreamWriter(OutputStream os, String charsetName)  用指定编码把字节流转换为字符流
    
## 字符流实现类
    FileWriter
    FileReader
    
## 字符缓冲流
    BufferedWriter
    BufferedReader
    
