platform :iOS, '10.0'
use_frameworks!
target 'NRCocoa' do
    # 用来方便调试iOS UI的库，需要配合 Mac 版 Reveal 使用
    # pod 'Reveal-iOS-SDK', :configurations => ['Debug']
    # 加载图片库
    # pod 'SDWebImage'
    # 自动布局库
    # pod 'Masonry'
    # 上拉/下拉刷新库
    pod 'MJRefresh'
    # JSON 和 Model 互转的库
    # pod 'JSONModel'
    # XML 解析库
    # pod 'Ono'
    # 网络库
    # pod 'AFNetworking'
    # 富文本库
    # pod 'DTCoreText'
    # 数据库
    # pod 'FMDB'
    
    # 函数式编程
    # pod 'ReactiveCocoa'
    pod 'RxSwift'
    pod 'RxCocoa'
    # 侧滑返回
    pod 'FDFullscreenPopGesture'
    
    #测试
    abstract_target 'Tests' do
        # inherit! :search_paths
        target "NRCocoaTests"
        target "NRCocoaUITests"

        pod 'Quick'
        pod 'Nimble'
    end
end
