platform :ios, '9.0'

target 'Flash Chat' do
  # Pods for Flash Chat
  use_frameworks!

  pod 'Firebase'
  pod 'Firebase/Auth'
  pod 'Firebase/Database'
  pod 'ChameleonFramework'
  pod 'SwiftyJSON'
  pod 'Alamofire'
  pod 'SVProgressHUD' 
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
