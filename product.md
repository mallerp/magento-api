## 3.商品

<a name="getProductDetail" />
### 商品详情

**`GET` `/mobileapi/products/getproductdetail`**

商品详情接口，不需要带`cookies`.

**_Paramers_**

* `productid` - 商品id


**_Examples_**

```js
/mobileapi/products/getproductdetail?product_id=421
```

**_Response_**

```js
{
    code: 0, //0是成功，非0都是失败
    msg: null, //返回信息，null代表没有
    model: [
        {
            entity_id: "284", //商品id
            sku: "wbk002L", //商品编号
            name: "Black NoLIta Cami", //商品名称
            rating_summary: "100", //总体评分（100分为满分）
            reviews_count: "3", //多少人评论
            in_wishlist:true, //是否在用户的心愿清单里
            news_from_date: "2013-05-08 00:00:00", //新品开始时间
            news_to_date: null, //新品结束时间
            special_from_date: "2013-03-05 00:00:00", //特价开始时间
            special_to_date: null, //特价结束时间
            image_url: "http://120.24.64.28/media/catalog/product/cache/1/image/265x/9df78eab33525d08d6e5fb8d27136e95/w/b/wbk002t.jpg", //图片链接
            url_key: "http://120.24.64.28/nolita-cami-590.html", //商品url
            regular_price_with_tax: "150.00", //原价
            final_price_with_tax: "120.00", //当前商品价格，在特价周期内的价格，不在周期内为原价，0则表示没有特价
            description: "Gunmetal frame with crystal gradient polycarbonate lenses in grey. ", //商品描述
            symbol: "$" //货币符号
        }
    ］
}
```

---------------------------------------

<a name="getProductCustomeTags" />
### 获取商品自定义选项

**`GET` `/mobileapi/products/getCustomOption`**

商品选项接口，不需要带`cookies`.

**_Paramers_**

* `product_id` - 商品id


**_Examples_**

```js
/mobileapi/products/getCustomOption?product_id=57295
```

**_Response_**

```js
{
    "code": 0,
    "msg": null,
    "model": {
        "1": {
            "option_id": "27",
            "custom_option_type": "drop_down",
            "custom_option_title": "color",
            "is_require": "1",
            "price": "0.00",
            "max_characters": null,
            "custom_option_value": {
                "1": {
                    "option_type_id": "102",
                    "option_id": "27",
                    "sku": "5-Daisy-Orange",
                    "sort_order": "1",
                    "default_title": "5 Daisy + Orange",
                    "store_title": null,
                    "title": "5 Daisy + Orange",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "2": {
                    "option_type_id": "103",
                    "option_id": "27",
                    "sku": "5-Daisy-Green",
                    "sort_order": "2",
                    "default_title": "5 Daisy + Green",
                    "store_title": null,
                    "title": "5 Daisy + Green",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "3": {
                    "option_type_id": "104",
                    "option_id": "27",
                    "sku": "5-Daisy-Light-Blue",
                    "sort_order": "3",
                    "default_title": "5 Daisy + Light Blue",
                    "store_title": null,
                    "title": "5 Daisy + Light Blue",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "4": {
                    "option_type_id": "105",
                    "option_id": "27",
                    "sku": "5-Daisy-Pink",
                    "sort_order": "4",
                    "default_title": "5 Daisy + Pink",
                    "store_title": null,
                    "title": "5 Daisy + Pink",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "5": {
                    "option_type_id": "106",
                    "option_id": "27",
                    "sku": "5-Daisy-White",
                    "sort_order": "5",
                    "default_title": "5 Daisy + White",
                    "store_title": null,
                    "title": "5 Daisy + White",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "6": {
                    "option_type_id": "107",
                    "option_id": "27",
                    "sku": "5-Daisy-Yellow",
                    "sort_order": "6",
                    "default_title": "5 Daisy + Yellow",
                    "store_title": null,
                    "title": "5 Daisy + Yellow",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "7": {
                    "option_type_id": "108",
                    "option_id": "27",
                    "sku": "5-Daisy-Purple",
                    "sort_order": "7",
                    "default_title": "5 Daisy + Purple",
                    "store_title": null,
                    "title": "5 Daisy + Purple",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "8": {
                    "option_type_id": "109",
                    "option_id": "27",
                    "sku": "5-Daisy-Rose",
                    "sort_order": "8",
                    "default_title": "5 Daisy + Rose",
                    "store_title": null,
                    "title": "5 Daisy + Rose",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "9": {
                    "option_type_id": "110",
                    "option_id": "27",
                    "sku": "5-Daisy-red",
                    "sort_order": "9",
                    "default_title": "5 Daisy + red",
                    "store_title": null,
                    "title": "5 Daisy + red",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "10": {
                    "option_type_id": "111",
                    "option_id": "27",
                    "sku": "5-Daisy-fluorescent-yellow",
                    "sort_order": "10",
                    "default_title": "5 Daisy + fluorescent yellow",
                    "store_title": null,
                    "title": "5 Daisy + fluorescent yellow",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "11": {
                    "option_type_id": "112",
                    "option_id": "27",
                    "sku": "Large-peach-models-Sky-Blue",
                    "sort_order": "11",
                    "default_title": "Large peach models + Sky Blue",
                    "store_title": null,
                    "title": "Large peach models + Sky Blue",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "12": {
                    "option_type_id": "113",
                    "option_id": "27",
                    "sku": "Large-peach-models-light-purple",
                    "sort_order": "12",
                    "default_title": "Large peach models + light purple",
                    "store_title": null,
                    "title": "Large peach models + light purple",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "13": {
                    "option_type_id": "114",
                    "option_id": "27",
                    "sku": "Large-peach-models-Beige",
                    "sort_order": "13",
                    "default_title": "Large peach models + Beige",
                    "store_title": null,
                    "title": "Large peach models + Beige",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "14": {
                    "option_type_id": "115",
                    "option_id": "27",
                    "sku": "Large-peach-models-champagne",
                    "sort_order": "14",
                    "default_title": "Large peach models + champagne",
                    "store_title": null,
                    "title": "Large peach models + champagne",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "15": {
                    "option_type_id": "116",
                    "option_id": "27",
                    "sku": "Large-peach-models-Green",
                    "sort_order": "15",
                    "default_title": "Large peach models + Green",
                    "store_title": null,
                    "title": "Large peach models + Green",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "16": {
                    "option_type_id": "117",
                    "option_id": "27",
                    "sku": "Large-peach-models-Red",
                    "sort_order": "16",
                    "default_title": "Large peach models + Red",
                    "store_title": null,
                    "title": "Large peach models + Red",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "17": {
                    "option_type_id": "118",
                    "option_id": "27",
                    "sku": "Large-peach-models-Rose",
                    "sort_order": "17",
                    "default_title": "Large peach models + Rose",
                    "store_title": null,
                    "title": "Large peach models + Rose",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "18": {
                    "option_type_id": "119",
                    "option_id": "27",
                    "sku": "Large-peach-models-pink",
                    "sort_order": "18",
                    "default_title": "Large peach models + pink",
                    "store_title": null,
                    "title": "Large peach models + pink",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "19": {
                    "option_type_id": "120",
                    "option_id": "27",
                    "sku": "Large-peach-models-orange-powder",
                    "sort_order": "19",
                    "default_title": "Large peach models + orange powder",
                    "store_title": null,
                    "title": "Large peach models + orange powder",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                },
                "20": {
                    "option_type_id": "121",
                    "option_id": "27",
                    "sku": "Large-peach-models-purple",
                    "sort_order": "20",
                    "default_title": "Large peach models + purple",
                    "store_title": null,
                    "title": "Large peach models + purple",
                    "default_price": "0.0000",
                    "default_price_type": "fixed",
                    "store_price": null,
                    "store_price_type": null,
                    "price": "0.0000",
                    "price_type": "fixed"
                }
            }
        }
    }
}
```

---------------------------------------

<a name="getProductCustomeValue" />
### 获取商品自定义属性

**`GET` `/mobileapi/products/getAdditionalData`**

商品属性接口，不需要带`cookies`.

**_Paramers_**

* `productid` - 商品id


**_Examples_**

```js
/mobileapi/products/getAdditionalData?product_id=57295
```

**_Response_**

```js
{
    "code": 0,
    "msg": null,
    "model": {
        "id_colors": {
            "label": "ID Colors",
            "value": "No",
            "code": "id_colors"
        },
        "size": {
            "label": "Size",
            "value": "Show as pic",
            "code": "size"
        },
        "material": {
            "label": "Material",
            "value": "Fabrics",
            "code": "material"
        }
    }
}
```
---------------------------------------

<a name="getOthersVisitProduct" />
### 获取其他用户浏览记录

---------------------------------------

<a name="listProductReview" />
### 获取商品评论列表

**`GET` `/mobileapi/review/list`**

根据某一商品ID获取商品评论.

**_Paramers_**

* `product_id` - 商品id


**_Examples_**

```js
    /mobileapi/review/list?product_id=418
```

**_Response_**

```js
{
    code: 0, //0是成功，非0都是失败
    msg: 'get reviews success!', //返回信息，null代表没有
    model: {
        total_results: 1,  //评论总数
        trade_rates: [
            {
                uname: "leo",   //评论人
                item_id: "418",   //评论的商品ID
                rate_score: 0,      //商品评分
                rate_content: "1234567897987",       //评论内容
                rate_date: "2015-05-12 06:48:04",    //评论时间
                rate_title: "is good test "          //评论标题
            }
        ]
    }
}
```

---------------------------------------

<a name="addProductReview" />
### 添加商品评论

**`POST` `/mobileapi/review/post`**

根据商品ID添加评论和评分.

**_Paramers_**

* `product_id` - 商品id
    
**_Form_**

* `ratings[1]` - Price评分 (需要加上10分)
* `ratings[2]` - Value评分 (需要加上5分)
* `ratings[3]` - Quality评分 
* `nickname` - 评论人名称
* `title` - 标题
* `detail` - 内容
* `validate_rating` - 验证是否打分，无需传入


**_Examples_**

```js
/mobileapi/review/post?product_id=421
    Form:  nickname=leoo
           title=haha
           detail=abcdefghi
           validate_rating=
           ratings[1]=5
           ratings[2]=10
           ratings[3]=15
```

**_Response_**

```js
{
    "code":0,   //0是成功，非0都是失败
    "msg":"Your review has been accepted for moderation.", //返回信息，null代表没有
    "model":true  //添加结果，true 代表添加成功
}
```