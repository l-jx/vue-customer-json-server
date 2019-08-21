### json-server+postman(测试http请求的工具)

json-server：https://github.com/typicode/json-server

jsonplaceholder：https://jsonplaceholder.typicode.com/

postman：网上下载

```
获取所有用户的信息
http:localhost:3000/users
```
```
获取id为1的用户信息
http:localhost:3000/users/1
```
```
获取公司的所有信息
http:localhost:3000/companies
```
```
获取单个公司的信息
http:localhost:3000/companies/1
```
```
获取所有公司id为3的用户
http:localhost:3000/companies/3/users
```
```
根据公司名字获取信息
http:localhost:3000/companies?name=Apple
```
```
根据多个名字获取公司信息
http:localhost:3000/companies?name=Apple&name=Google
```
```
获取一页中只有两条数据
http:localhost:3000/companies?_page=1&_limit=2
```
```
根据名字升序排序 asc升序 desc降序
http:localhost:3000/companies?_sort=name&_order=asc
```
```
获取年龄35及以上的
http:localhost:3000/users?age_gte=35
```
```
获取年龄在35到45之间
http:localhost:3000/users?age_gte=35&age_lte=40
```
```
搜索用户信息 q=想搜索的内容
http:localhost:3000/users?q=h
```
