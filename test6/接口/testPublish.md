<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：testPublish [返回](../README.md)
用例： [登录](../用例/发布作业.md)

- 功能：
    发布作业及作业要求
    
- 权限：
    教师。    
    
- API请求地址： 
    接口基本地址/v1/api/testPublish

- 请求方式 ：
    POST

- 请求实例：

        {
            "course_id": "654321",
            "test_id": "84641",
            "describe": "学生将实验上传到github上......"
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |course_id| 课程id |
  |test_id| 课程对应的实验id |
  |describe| 实验要求，可以是文件格式，也可以是文本格式 |
  
- 返回实例：

        { 
            "status": true,
            "info": "发布作业成功",    
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info| 返回结果说明信息 |


