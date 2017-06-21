# A3RT_SDK.js

これは[A3RT](https://a3rt.recruit-tech.co.jp/)のAPIをJavaScriptから利用するためのSDKです。

## Requirement

- jquery-2.X.X
  - 動作確認済：jquery-2.2.0.

## Installation
```html
<script type="text/javascript" src="./A3RT_SDK.js"></script>
```

## Usage

### 1. TEXT SUGGEST API
```js
a3rt_text_suggest(a3rt_key,a3rt_description,a3rt_style,a3rt_separation, a3rt_callback)
	.done(function(json){	/ 正常の処理		})
	.fail(function (XMLHttpRequest, textStatus, errorThrown) { /異常の処理	});
```

[https://a3rt.recruit-tech.co.jp/product/textSuggestAPI/](https://a3rt.recruit-tech.co.jp/product/textSuggestAPI/)


### 2. TEXT CLASSIFICATION API
```js
a3rt_text_suggest(a3rt_key,a3rt_description,a3rt_style,a3rt_separation, a3rt_callback)
	.done(function(json){	/ 正常の処理		})
	.fail(function (XMLHttpRequest, textStatus, errorThrown) { /異常の処理	});
```

[https://a3rt.recruit-tech.co.jp/product/textClassificationAPI/](https://a3rt.recruit-tech.co.jp/product/textClassificationAPI/)

### 3. TALK API
```js
a3rt_talk(a3rt_key, a3rt_query, a3rt_callback)
	.done(function(json){	/ 正常の処理		})
	.fail(function (XMLHttpRequest, textStatus, errorThrown) { /異常の処理	});
```

[https://a3rt.recruit-tech.co.jp/product/talkAPI/](https://a3rt.recruit-tech.co.jp/product/talkAPI/)

### 4. IMAGE INFLUENCE API
```js
a3rt_image_infl(a3rt_key,a3rt_predict,a3rt_imagefile)
	.done(function(json){	/ 正常の処理		})
	.fail(function (XMLHttpRequest, textStatus, errorThrown) { /異常の処理	});
```

[https://a3rt.recruit-tech.co.jp/product/imageInfluenceAPI/](https://a3rt.recruit-tech.co.jp/product/imageInfluenceAPI/)

### 5. PLOOFREADING API
```js
a3rt_proofreading(a3rt_key,a3rt_sentence,a3rt_sensitivity,a3rt_callback)
	.done(function(json){	/ 正常の処理		})
	.fail(function (XMLHttpRequest, textStatus, errorThrown) { /異常の処理	});
```

[https://a3rt.recruit-tech.co.jp/product/proofreadingAPI/](https://a3rt.recruit-tech.co.jp/product/proofreadingAPI/)

## Author

- misa_t
- yuki_okuda
