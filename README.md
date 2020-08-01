//------------------------  GET请求  ------------------------------
//获取所有用户信息
http://localhost:3000/users

//获取用户id为1的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取单个公司的信息
http://localhost:3000/companies

//获取所有公司id为3的用户
http://localhost:3000/companies/3/users

//根据公司名字获取信息
http://localhost:3000/companies?name=Apple

//根据多个公司名字获取信息
http://localhost:3000/companies?name=Apple&name=Microsoft

// 获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//生序排序 asc升序 desc降序
http://localhost:3000/companies?_sort=name&order=asc

//根据年龄获取有用户信息(年龄30及以上的)
http://localhost:3000/users?age_gte=30

//根据年龄获取有用户信息(年龄30-40之间的)
http://localhost:3000/users?age_gte=30&age_gte=40

//搜索用户信息
http://localhost:3000/users?q=uu