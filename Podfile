# Uncomment this line to define a global platform for your project
# platform :ios, '6.0'

target 'BackgroundTester' do

# Mobile SDK 3.2.1 , sqlcipher 3.1 (pod) ==> doesn't work when phone locked
pod 'SalesforceMobileSDK-iOS', '3.2.1'

# For Mobile SDK 3.2.1 with sqlcipher v2.0.5 (static library) ==> doesn't work when phone locked
# pod 'SalesforceMobileSDK-iOS', :git => 'https://github.com/wmathurin/SalesforceMobileSDK-iOS.git', :branch => 'oldsqlcipher', :submodules => 'true'

# for Mobile SDK 3.3 with parent directory using NSFileProtectionComplete ==> doesn't work when phone locked
# pod 'SalesforceMobileSDK-iOS', :git => 'https://github.com/wmathurin/SalesforceMobileSDK-iOS.git', :commit => '63c2627', :submodules => 'true'

# for Mobile SDK 3.3 with parent directory using NSFileProtectionCompleteUntilFirstUserAuthentication ==> works when phone locked
# pod 'SalesforceMobileSDK-iOS', :git => 'https://github.com/wmathurin/SalesforceMobileSDK-iOS.git', :commit => '76b9853', :submodules => 'true'

# Local
# pod 'SalesforceMobileSDK-iOS', :path => '~/Development/github/wmathurin/SalesforceMobileSDK-iOS'

end

