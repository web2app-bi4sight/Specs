# Podfile
source 'https://github.com/web2app-bi4sight/Specs.git' # Huntmobi私有源，必须放在首位

source 'https://cdn.cocoapods.org/' # CocoaPods官方CDN源

target 'YourApp' do
  # 从此处开始，你可以像往常一样声明依赖
  pod 'com_huntmobi_web2app', '3.1.4' # 从私有源获取
  # ... 其他依赖
end
