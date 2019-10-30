//获取所有用户信息
http://localhost:3000/users

//获取id=1的用户信息
http://localhost:3000/users/1

//获取所有公司信息
http://localhost:3000/companies

//获取单个公司信息
http://localhost:3000/companies/1

//获取所有公司中id=3的用户
http://localhost:3000/companies/3/users

//获取公司名称为Apple的信息
http://localhost:3000/companies?name=Apple

//根据多个名字获取公司信息
http://localhost:3000/companies?name=Apple&name=Google

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//根据name升序排序  asc升序，desc降序
http://localhost:3000/companies?_sort=name&_order=asc

//获取age>=30且age<=40的用户信息
http://localhost:3000/users?age_gte=30&age_lte=40

//获取除id=1的用户信息
http://localhost:3000/users?id_ne=1

//获取name中含有om的用户信息
http://localhost:3000/users?name_like=om

//搜索用户信息(对全部字段进行搜索)
http://localhost:3000/users?q=h

//给所有用户增加hobby属性
http://localhost:3000/users?_embed=hobby

//postman地址
https://app.getpostman.com/join-team?invite_code=07dcea79c3b76d0d60accd7528270292
username:499243647@qq.com
password：qwer1234