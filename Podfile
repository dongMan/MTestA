platform :ios, '11.0'
inhibit_all_warnings!
use_frameworks!

install! 'cocoapods', :deterministic_uuids => false

#不加下面这句话会报错，具体参考：https://www.jianshu.com/p/2360866a5191
install! 'cocoapods', :disable_input_output_paths => true


source 'https://github.com/dongMan/dxjRouter.git'
source 'https://github.com/CocoaPods/Specs.git'


target 'MTestA' do
  project 'MTestA.xcodeproj'

  pod 'MBasis', :path => "../MBasis/MBasis.podspec"
  pod 'MBasis/YSSDK', :path => "../MBasis/MBasis.podspec"

end
