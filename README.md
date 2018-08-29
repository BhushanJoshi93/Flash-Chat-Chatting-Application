# Flash-Chat📱 |

## Simple chatting application which uses firebase for data transfer across devices.
## Similar Project is also available for Android. Link will be available shortly.
 Pro: Git clone to your Xcode projects folder.

 ## Podfile Configuration
 ```
 post_install do |installer|
     installer.pods_project.targets.each do |target|
         target.build_configurations.each do |config|
             config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
         end
     end
 end
 ```
