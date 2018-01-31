# LazyAppFrame
android 快速开发框架
该框引用了以下库<br/>
[Dagger2](https://github.com/google/dagger "Dagger2")、[RxTools](https://github.com/vondear/RxTools "工具类集合")、
[Alerter](https://github.com/Tapadoo/Alerter "顶部alert提示")、[fastjson](https://github.com/alibaba/fastjson "解析json数据")、
[RxAndroid](https://github.com/ReactiveX/RxAndroid)<br/>[Retrofit](https://github.com/square/retrofit)、

## How to use
### To get a Git project into your build
#### Step 1. Add the JitPack repository to your build file
    Add it in your root build.gradle at the end of repositories:
    
    allprojects {
	  repositories {
		...
		maven { url 'https://jitpack.io' }
	  }
     }

#### Step 2. Add the dependency
     dependencies {
     		compile 'com.github.ActorMing:LazyAppFrame:v1.0.0'
     }

### 在项目中的应用
