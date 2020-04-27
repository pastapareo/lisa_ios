workspace 'KoreBotSDK'
project 'Lisa/Lisa.xcodeproj'

inhibit_all_warnings!

def import_pods
    pod 'Mantle', '2.0.2'
    pod 'AFNetworking', '3.2.0'
    pod 'SwiftJWT'
end

target 'Lisa' do
    platform :ios, '11.4'
    pod 'Charts','3.2.0'

    use_frameworks!
    import_pods
    pod 'KoreBotSDK', :git => 'https://github.com/Koredotcom/iOS-kore-sdk.git'
    project 'Lisa.xcodeproj'
end
