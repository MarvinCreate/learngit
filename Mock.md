# Mock模拟数据
## 安装
    npm install mockjs
## 模板定义方式

### 1.模板定义
    Mock.mock({
    'age:1-100':1
    })
    
### 2.占位符定义
    {
      'age':Mock.mock('@integer(1,100)')
    }
    
    {
      'age':Mock.Random.integer(1,100)
    }
## 数据类型
### 1.Basic
    boolean natural integer float character string range
### 2.Date
    date    time    datetime    now
### 3.image
    image   dataImage
### 4.color
    color   hex     rgb     rgba    hsl
### 5.text
    paragraph   sentence    word    title   cparagraph  csentence   cword   ctitle
### 6.name
    first   last    name    cfirst  clast   cname
### 7.web
    url     domain    protocol    tld    email   ip
### 8.address
    region      province    city    county  zip
### 9.helper
    capitalize   upper   lower   pick    shuffle
### 10.Miscellaneous
    guid    id  increment

