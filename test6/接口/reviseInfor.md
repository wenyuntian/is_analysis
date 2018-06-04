
# 接口：reviseInfor  [返回](../README.md)
用例： [查询个人信息](../用例/修改个人信息.md)

- 功能：
    修改个人信息
    
- 权限：
    老师、学生  
    
- API请求地址：     
    接口基本地址/v1/api/reviseInfor

- 请求方式 ：
    POST

- 请求实例：

        {
            "user_id": 789154,
            "name": "daydaywen",
            "github_username": "wenyuntian",
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  | user_id | 用户id（来自USERS表） |
  | name | 用户真实名字（来自USERS表） |
  | github_username | 用户的github账号（来自USERS表） |
  

- 返回实例：

        {         
            "status": "true"
            "infor": "修改成功"
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |infor| 返回操作结果 |


