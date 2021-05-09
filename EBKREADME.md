二板三板生成思路 

# 根据接口stk_limit

pro = ts.pro_api()

# 获取单日全部股票数据涨跌停价格
df = pro.stk_limit(trade_date='yesterday') ##yesterday指今日-1

df就是一个全部的股票数据

# 日线行情来看个股数据，从而进行比对
输入个股信息，ts_code trade_date 
输出昨日收盘价pre_close 涨停价up_limit 


# 写一个循环

for df第一位:df最后一位， 
 if  pre_close==up_limit, 

输出 这个

limit1.EBK
