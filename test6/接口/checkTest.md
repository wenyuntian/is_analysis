
# 接口：checkTest  [返回](../README.md)
用例： [登出](../用例/登出.md)

- 功能：
    查看学生实验
    
- 权限：
    老师    
    
- API请求地址： 
    接口基本地址/v1/api/checkTest

- 请求方式 ：
    GET

- 请求实例：

        {
            "course_id ": 654321,
            "student_id": 201510414121,
            "test_id": 864243
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |course_id| 课程id |
  |student_id| 评阅学生的id |
  |test_id| 评阅的实验id |
  

- 返回实例：

        {         
            
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  | | 直接跳转到该学生的github页面对应的实验 |


