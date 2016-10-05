source 'https://github.com/CocoaPods/Specs.git'
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end
platform :ios, '10.0'
use_frameworks!

target ‘OpenWeatherMap’ do
    pod 'Alamofire', '~> 4.0'
    pod ‘SwiftyJSON’
    pod 'RealmSwift'
    
end
