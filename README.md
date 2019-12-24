# 期末项目

产品需求文档

|发布日期|2019年12月1日|
|:-|:-:|
|APP名称|记录小助手|
|文件状态|未完成|
|文件的主人|刘庆雯|
|领头设计者|刘庆雯|
|领头开发者|刘庆雯|
|领头测试者|刘庆雯|

### 产品简介
记录小助手是一个通过提取文本，手写识别等API来为用户在做笔记时提供方便，我们的产品可以通过用户导入图片进行图片中的文字识别，其中图片内容可以是中文以及英文，识别后可以将其进行整理，储存至我们的APP中，同时用户可以将其进行分类整理，为后期的查看提供方便。在APP中用户能够通过搜索的功能搜素关键字就能查看相关内容的笔记，为用户在课后复习时提供方便。而且我们加入了图像清晰度功能，减少因为图像质量原因导致出现识别错误的现象出现。在图片的基础上我们增加了语音识别的功能，目前用户可以通过语音识别成文字的方式记录自己的想法及笔记。


### 背景
现在许多的大学生会有这样的情况，在课堂上老师在讲授课程，听与写的能力较难同时进行，当能完全清楚地了解老师讲的内容，笔记的部分缺失；当做了笔记，但老师讲的内容可能没能完全吸收。同时大部分的学生都是拿出手机拍摄了老师的PPT的照片，但课后没能及时整理做笔记，导致期末准备考试时出现无从下手的情况。同时也有大部分的人希望能够通过语音识别成文字记录老师的讲课内容或者记录自己某一时刻的想法（灵感），怕自己没过多久就完记。

### 目的
为你提供更便捷的做笔记方式，提高你的学习与工作效率。

## PRD 价值主张设计
#### PRD1 加值宣言

- 微软Azure API中的提取文本API的价值
可以通过拍摄老师课上的PPT，识别PPT中的文字提取文本，节省学生在课上做笔记的时间，能更好地听老师讲课。

- 百度开放API中的手写文字识别的价值
1. 可以将我们平时手写书摘、读书笔记、课堂笔记等内容的识别，实现对手写文字内容的扫描及线上存储。
2. 老师对学生日常作业及考试试卷中的手写内容进行自动识别，对于一些学生比较潦草的字体能更加方便老师的阅读

- 百度开放API中图像清晰度增强的价值
拍摄时可能因为拍摄距离/手机像素等原因导致图像模糊不清导致文字识别出现错误的情况，这时图像清晰图增强可以使图像变清晰，减少识别错误的情况。

- 百度开放API中的语音识别成文字的价值
当用户在某一时刻想要记录自己的想法/与老师讨论时记录老师的观点时，可以通过语音识别成文字的功能，为用户提供方便。

#### PRD2.核心价值

- 核心价值宣言（最小可用产品）：
通过运用图像清晰度增强，提取文本以及手写文字识别等功能，为学生在课堂上做笔记，或者老师在审阅试卷时提供方便，节省用户的时间。

通过使用语音识别成文字的功能，让用户随时记录自己的想法，防止果断时间后忘记。

通过运用图像清晰度增强API为拍摄时因各种原因造成的图像模糊情况进行改善，然后通过导入图片进行文字识别提取文字的内容扫描并在线上储存，为日后翻看笔记提供
方便。



#### PRD3.核心价值与用户痛点

- 用户痛点

###### 场景一：
在课堂上听老师讲授知识以及抄写笔记是比较难同时进行的一件事，一心难以二用。

###### 场景二：
老师在批改作业时总会出现写字潦草的学生，这会增加其工作的时间与难度

###### 场景三：
对于一些会议手写记录需要整理成电子档，需要手动输入到电脑中

###### 场景四：
手写的笔记整理，后期查找相应内容较为麻烦

###### 场景五
当用户突然灵感一闪，想出了某个问题的解决办法，但身边没有纸笔。

#### PRD4.人工智能概率性与用户痛点


#### PRD5需求列表与人工智能API加值

|用户案例|对应API|重要程度|
|:-|:-:|-:|
|用户在课堂做笔记的同时跟不上老师讲课的节奏？|提取文本API|重要|
|老师在审阅试卷时学生的字体太潦草难以查阅？|手写文字识别|重要|
|用户在日常生活中想到一个灵感/想要记录某一个知识点但没有纸币|语音识别文字API|重要|
|学生拍摄的图片太模糊导致文字识别缺失/错误？|图像清晰度增强|次重要|

- 具体应用场景
1. 在课堂上，小明正一边听着老师讲课一边写着PPT的笔记，但当记完一段笔记时，发现老师已经讲完那一章节的内容已经翻页了，正打算空出一部分页面来继续记下面的笔记，这时小明发现自己下了一个新的APP，能够通过拍照识别文字，这时小明拿出手机点开趣印APP，对着PPT拍摄照片，点击识别的按钮，PPT的文字便自动识别在手机屏幕上。

2. 小花老师刚成为老师没多久，还不太适应学生的各种较为潦草的字体，当他在审阅学生作文时，发现有一个学生的作文字体写得像草书一样，他只能一个字一个字地猜他的文字写的是什么，正苦恼该怎么办的时候，他想起了同事推荐的趣印APP，他拿出手机对着学生的作文拍摄后，手写的字体进行扫描出来成为宋体，他便很快地知道学生作文的内容并给学生评分。同时也因为学生的字体潦草扣了分数。

3. 小明因为太晚才到课室，发现靠前的座位已经被占满了，他只能坐在后排，当拿出手机准备拍照记录PPT笔记的时候发现因为距离的原因导致图片有点模糊，当他直接扫描文字时发现有部分文字缺少，然后他选择了图像清晰的按钮，使图片变得清晰，缺失的文字也出现了。

4. 当小红在记录需要买什么东西时，你本想拿起纸笔记录，后来想起自己有记录小助手这个APP，他拿起手机把需要买的东西语音录入到手机上，等到到了商场，他便能较为方便地对照着手机的清单购物。

## 原型

超链接（原型文档下载区）
原型文档交互展示


### 产品架构图


### 产品流程图


### AXURE原型文档展示





## API 产品使用关键AI或机器学习之API的输出入展示

### API1.使用水平




### API4.加分项

### 1. 微软Azure API中的提取文本API

##### 使用的先决条件：
1.如果想在本地运行此示例，必须安装 Python。
2.必须具有计算机视觉的订阅密钥。 可以从试用认知服务获取免费试用密钥。 或者，按照创建认知服务帐户中的说明订阅计算机视觉并获取密钥。 然后，为密钥和服务终结点字符串创建环境变量，分别名为 COMPUTER_VISION_SUBSCRIPTION_KEY 和 COMPUTER_VISION_ENDPOINT。

 - 输入：

 ```
       import requests
import time
# If you are using a Jupyter notebook, uncomment the following line.
# %matplotlib inline
import matplotlib.pyplot as plt
from matplotlib.patches import Polygon
from PIL import Image
from io import BytesIO

# Add your Computer Vision subscription key and endpoint to your environment variables.
if 'key' in os.environ:
    subscription_key = os.environ['key']
else:
    print("\nSet the key environment variable.\n**Restart your shell or IDE for changes to take effect.**")
    sys.exit()

if 'endpoint' in os.environ:
    endpoint = os.environ['endpoint']

text_recognition_url = endpoint + "vision/v2.0/read/core/asyncBatchAnalyze"

# Set image_url to the URL of an image that you want to analyze.
image_url = "https://c-ssl.duitang.com/uploads/item/201804/26/20180426203556_xdfjn.jpeg"

headers = {'Ocp-Apim-Subscription-Key': subscription_key}
data = {'url': image_url}
response = requests.post(
    text_recognition_url, headers=headers, json=data)
response.raise_for_status()

# Extracting text requires two API calls: One call to submit the
# image for processing, the other to retrieve the text found in the image.

# Holds the URI used to retrieve the recognized text.
operation_url = response.headers["Operation-Location"]

# The recognized text isn't immediately available, so poll to wait for completion.
analysis = {}
poll = True
while (poll):
    response_final = requests.get(
        response.headers["Operation-Location"], headers=headers)
    analysis = response_final.json()
    print(analysis)
    time.sleep(1)
    if ("recognitionResults" in analysis):
        poll = False
    if ("status" in analysis and analysis['status'] == 'Failed'):
        poll = False

polygons = []
if ("recognitionResults" in analysis):
    # Extract the recognized text, with bounding boxes.
    polygons = [(line["boundingBox"], line["text"])
                for line in analysis["recognitionResults"][0]["lines"]]

# Display the image and overlay it with the extracted text.
plt.figure(figsize=(15, 15))
image = Image.open(BytesIO(requests.get(image_url).content))
ax = plt.imshow(image)
for polygon in polygons:
    vertices = [(polygon[0][i], polygon[0][i+1])
                for i in range(0, len(polygon[0]), 2)]
    text = polygon[1]
    patch = Polygon(vertices, closed=True, fill=False, linewidth=2, color='y')
    ax.axes.add_patch(patch)
    plt.text(vertices[0][0], vertices[0][1], text, fontsize=20, va="top")
       
  ```

 - 输出:
 
 ```
 {'status': 'Running'}
{'status': 'Succeeded', 'recognitionResults': [{'page': 1, 'clockwiseOrientation': 232.16, 'width': 1215, 'height': 1216, 'unit': 'pixel', 'lines': [{'boundingBox': [312, 929, 650, 764, 663, 791, 325, 956], 'text': 'NOTHING GOLD CAN STAY', 'words': [{'boundingBox': [314, 929, 437, 870, 449, 895, 327, 955], 'text': 'NOTHING'}, {'boundingBox': [445, 866, 516, 831, 529, 857, 458, 891], 'text': 'GOLD'}, {'boundingBox': [525, 827, 576, 802, 589, 828, 537, 853], 'text': 'CAN'}, {'boundingBox': [585, 797, 650, 765, 663, 792, 597, 823], 'text': 'STAY'}]}, {'boundingBox': [310, 584, 403, 543, 411, 562, 319, 603], 'text': 'Ron Rash', 'words': [{'boundingBox': [316, 583, 355, 565, 363, 584, 325, 601], 'text': 'Ron'}, {'boundingBox': [358, 564, 402, 544, 411, 563, 367, 582], 'text': 'Rash'}]}, {'boundingBox': [394, 337, 336, 256, 352, 244, 411, 325], 'text': 'TION OF YOUR', 'words': [{'boundingBox': [393, 333, 374, 309, 391, 298, 409, 322], 'text': 'TION'}, {'boundingBox': [372, 306, 361, 291, 378, 280, 388, 295], 'text': 'OF'}, {'boundingBox': [359, 288, 337, 256, 353, 246, 375, 277], 'text': 'YOUR'}]}, {'boundingBox': [436, 318, 392, 262, 405, 252, 448, 308], 'text': 'S BEFORE', 'words': [{'boundingBox': [434, 314, 428, 306, 440, 297, 446, 304], 'text': 'S', 'confidence': 'Low'}, {'boundingBox': [426, 304, 393, 262, 406, 253, 439, 295], 'text': 'BEFORE'}]}, {'boundingBox': [461, 307, 418, 254, 439, 240, 481, 292], 'text': 'TKT', 'words': [{'boundingBox': [456, 301, 421, 258, 441, 243, 475, 285], 'text': 'TKT'}]}]}]}
        
  ```



2. 百度API手写文字识别API
- 接口描述:对手写中文汉字、数字进行识别
- 请求方法：POST
- 接口地址： https://aip.baidubce.com/rest/2.0/ocr/v1/handwriting
- 将代码进行修改，可进行多张图片上传进行手写文字识别，逐页识别

 ```
import requests
import json
import base64


def get_file_content(filePath):
	""" 读取图片base64 """
	with open(filePath, 'rb') as fp:
		return base64.b64encode(fp.read())


def get_access_token():
	# API_Key,Secret_Key 需要在 https://console.bce.baidu.com/ai/?fromai=1#/ai/ocr/app/list 创建应用才能获得
	API_Key = 'Your API_key'
	Secret_Key = 'Your Secret_Key'
	r = requests.post('https://aip.baidubce.com/oauth/2.0/token?grant_type=client_credentials&client_id='+API_Key+'&client_secret='+Secret_Key)
	print(r.text)
	j = json.loads(r.text)
	access_token = j.get('access_token')
	print(access_token )
	return access_token 


def recognise_handwriting_pic(access_token,image_path):
	image = get_file_content(image_path)
	r = requests.post(
		url = 'https://aip.baidubce.com/rest/2.0/ocr/v1/handwriting?access_token='+access_token,
		headers={"Content-Type":"application/x-www-form-urlencoded"},
		data = {'image':image})
	#print(r.text)
	j = json.loads(r.text)
	words_result = j.get('words_result')
	for i in words_result:
		print(i.get('words'))

access_token = get_access_token()  # 获取一次保存下来就够了，一般1个月有效期

# 上传本地图片，逐页识别
for p in range(1,2):
	print('\n\n%s\n\n第%d页'%(' *'*20,p))
	recognise_handwriting_pic(access_token,image_path='C:/Users/Lenovo/Desktop/timg (2).jpg')
   ```


- 输出

 ```
{"refresh_token":"25.7c41d3c00e4fbd19894906a0a4150925.315360000.1891957464.282335-18049732","expires_in":2592000,"session_key":"9mzdCPA10uBmafzKCSh2AK\/YKTRt6yfKx\/tPzB2ZHsxHNvwNFg+bhdgfG6gL52lngVas+CEmZsa75LSRbl8D4Luabio2Qw==","access_token":"24.34f9810b39c507bfcff6af2b4139097d.2592000.1579189464.282335-18049732","scope":"public vis-ocr_ocr brain_ocr_scope brain_ocr_general brain_ocr_general_basic vis-ocr_business_license brain_ocr_webimage brain_all_scope brain_ocr_idcard brain_ocr_driving_license brain_ocr_vehicle_license vis-ocr_plate_number brain_solution brain_ocr_plate_number brain_ocr_accurate brain_ocr_accurate_basic brain_ocr_receipt brain_ocr_business_license brain_solution_iocr brain_qrcode brain_ocr_handwriting brain_ocr_passport brain_ocr_vat_invoice brain_numbers brain_ocr_business_card brain_ocr_train_ticket brain_ocr_taxi_receipt vis-ocr_household_register vis-ocr_vis-classify_birth_certificate vis-ocr_\u53f0\u6e7e\u901a\u884c\u8bc1 vis-ocr_\u6e2f\u6fb3\u901a\u884c\u8bc1 vis-ocr_\u673a\u52a8\u8f66\u68c0\u9a8c\u5408\u683c\u8bc1\u8bc6\u522b vis-ocr_\u8f66\u8f86vin\u7801\u8bc6\u522b vis-ocr_\u5b9a\u989d\u53d1\u7968\u8bc6\u522b vis-ocr_\u4fdd\u5355\u8bc6\u522b brain_ocr_vin brain_ocr_quota_invoice brain_ocr_birth_certificate brain_ocr_household_register brain_ocr_HK_Macau_pass brain_ocr_taiwan_pass brain_ocr_vehicle_certificate brain_ocr_insurance_doc wise_adapt lebo_resource_base lightservice_public hetu_basic lightcms_map_poi kaidian_kaidian ApsMisTest_Test\u6743\u9650 vis-classify_flower lpq_\u5f00\u653e cop_helloScope ApsMis_fangdi_permission smartapp_snsapi_base iop_autocar oauth_tp_app smartapp_smart_game_openapi oauth_sessionkey smartapp_swanid_verify smartapp_opensource_openapi smartapp_opensource_recapi fake_face_detect_\u5f00\u653eScope vis-ocr_\u865a\u62df\u4eba\u7269\u52a9\u7406 idl-video_\u865a\u62df\u4eba\u7269\u52a9\u7406","session_secret":"4f954a8cbf512607ac7b2ff0772e8cd9"}

24.34f9810b39c507bfcff6af2b4139097d.2592000.1579189464.282335-18049732


 * * * * * * * * * * * * * * * * * * * *

第1页
既然目标是地平线
留给世界的只能是背影
—《热爱生命》汪国真

 ```
 


















