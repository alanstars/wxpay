微信支付功能封装，适用所有公众号微信支付、小程序微信支付支付、APP微信支付、JSSDK（H5支付）、二维码支付等
使用方法：
1、由于使用了命名空间，使用时要注意命名空间是否重复
2、$wechat = new \wechat\Wxpay($appid,$appsecret,$mch_id,$key,$notify_url);
3、  * @param $appid        应用ID
     * @param $appsecret    应用秘钥
     * @param $mch_id       商户号
     * @param $key          支付秘钥key
     * @param $notify_url   回调通知url
注意：由于退款要使用证书，因此需要把pem证书文件上传到指定目录
