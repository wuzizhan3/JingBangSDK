# JingBangSDK
精帮SDK 集成文档

导入SDK
CocoaPods pod 'JingBangWebSDK'

引入
#import <JingBangWebSDK/JB.h>


使用

OC
JBHomeViewController *vc = [[JBHomeViewController alloc] init];
vc.jbUrl = @"https://www.mayijingbang.com";
vc.jbToken = @"";
[self.navigationController pushViewController:vc animated:YES]

Swift
let vc = JBHomeViewController()
navigationController?.pushViewController(v, animated: true)


