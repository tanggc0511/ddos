# DeleteIp {#doc_api_ddosbgp_DeleteIp .reference}

调用DeleteIp接口将被防护IP从防护包中移除，取消防护。

**说明：** DDoS防护包的API接口目前仅对企业版DDoS防护包用户开放。

## 调试 {#api_explorer .section}

[您可以在OpenAPI Explorer中直接运行该接口，免去您计算签名的困扰。运行成功后，OpenAPI Explorer可以自动生成SDK代码示例。](https://api.aliyun.com/#product=ddosbgp&api=DeleteIp&type=RPC&version=2018-07-20)

## 请求参数 {#parameters .section}

|名称|类型|是否必选|示例值|描述|
|--|--|----|---|--|
|Action|String|是|DeleteIp|要执行的操作，取值：**DeleteIp**。

 |
|InstanceId|String|是|ddosbgp-cn-xxx|要操作的防护包ID。

 |
|IpList|String|是|1.1.1.1,2.2.2.2|要从防护包中移除的被防护IP，多个IP间以逗号分隔。

 |

## 返回数据 {#resultMapping .section}

|名称|类型|示例值|描述|
|--|--|---|--|
|RequestId|String|C33EB3D5-AF96-43CA-9C7E-37A81BC06A1E|本次请求的ID。

 |

## 示例 {#demo .section}

请求示例

``` {#request_demo}

http(s)://[Endpoint]/?Action=DeleteIp
&InstanceId=ddosbgp-cn-xxx
&IpList=1.1.1.1,2.2.2.2
&<公共请求参数>

```

正常返回示例

`XML` 格式

``` {#xml_return_success_demo}
<DeleteIpResponse>
      <RequestId>C33EB3D5-AF96-43CA-9C7E-37A81BC06A1E</RequestId>
</DeleteIpResponse>
```

`JSON` 格式

``` {#json_return_success_demo}
{
	"RequestId":"4C467B38-3910-447D-87BC-AC049166F216"
}
```

## 错误码 { .section}

访问[错误中心](https://error-center.aliyun.com/status/product/ddosbgp)查看更多错误码。

