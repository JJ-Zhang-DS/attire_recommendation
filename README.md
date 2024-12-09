# attire_recommendation

数据集描述
文件描述
train_users.csv：训练数据集中的用户id
train_items.csv：训练数据集中的商品id
train_interactions.csv：训练数据集中的用户购买商品记录
test_users.csv：测试数据集中的用户
test_items.csv：测试数据集中的商品
sample.csv：为测试数据集中的每位用户, 从测试数据集中随机挑选20件商品。此文件为输出格式样本
数据字段
以下是数据描述文件中的简要版本
user_id：用户身份识别码
item_ID：商品识别码
item_name：商品名称，包含商品基本信息
order_time：用户购买商品的时间
brand：商品品牌
channel：商品出货渠道
unit_price：商品单价
category：商品子类别
size：商品尺码
color：商品颜色
discount：商品出售折扣
gender：商品所适合的客户性别（由商品名称 item_name 信息补全商品性别 sex 中的 NaN）
class_map：商品大类别
bk_sku_id：商品识别编号
category.1：部分商品别类
style：商品风格
brand_location_map：品牌所在国家（由 ChatGPT 根据品牌补全 country_in_stock 中的部分 NaN）
materials_map：商品材料构成
sex：商品性别
country_size：所在国家尺码
country_in_stock：品牌所在国家
tag：商品标签
price_range：价格范围
country：国家
style_50：商品所属主要风格
color_50：商品所属主要色系
