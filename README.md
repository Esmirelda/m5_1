import '../flutter_flow/flutter_flow_theme.dart';
import '../flutter_flow/flutter_flow_util.dart';
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';

class RegistrationWidget extends StatefulWidget {
  const RegistrationWidget({Key? key}) : super(key: key);

  @override
  _RegistrationWidgetState createState() => _RegistrationWidgetState();
}

class _RegistrationWidgetState extends State<RegistrationWidget> {
  final scaffoldKey = GlobalKey<ScaffoldState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      key: scaffoldKey,
      backgroundColor: FlutterFlowTheme.of(context).primaryBackground,
      body: SafeArea(
        child: GestureDetector(
          onTap: () => FocusScope.of(context).unfocus(),
          child: Column(
            mainAxisSize: MainAxisSize.max,
            children: [
              Container(
                width: 500,
                height: 100,
                decoration: BoxDecoration(
                  color: Color(0xD4E91E63),
                ),
                child: Align(
                  alignment: AlignmentDirectional(0, 0),
                  child: Text(
                    'Home page ',
                    style: FlutterFlowTheme.of(context).title1.override(
                          fontFamily: 'Poppins',
                          color: FlutterFlowTheme.of(context).primaryBackground,
                          fontSize: 30,
                          fontWeight: FontWeight.bold,
                        ),
                  ),
                ),
              ),
              Image.asset(
                'assets/images/DATING_APP-512.webp',
                width: 370,
                height: 670,
                fit: BoxFit.cover,
              ),
            ],
          ),
        ),
      ),
    );
  }
}
import '../flutter_flow/flutter_flow_theme.dart';
import '../flutter_flow/flutter_flow_util.dart';
import '../flutter_flow/flutter_flow_widgets.dart';
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';

class LoginWidget extends StatefulWidget {
  const LoginWidget({Key? key}) : super(key: key);

  @override
  _LoginWidgetState createState() => _LoginWidgetState();
}

class _LoginWidgetState extends State<LoginWidget> {
  final scaffoldKey = GlobalKey<ScaffoldState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      key: scaffoldKey,
      appBar: AppBar(
        backgroundColor: FlutterFlowTheme.of(context).primaryColor,
        automaticallyImplyLeading: false,
        title: Text(
          'login',
          style: FlutterFlowTheme.of(context).title2.override(
                fontFamily: 'Poppins',
                color: Colors.white,
                fontSize: 22,
              ),
        ),
        actions: [],
        centerTitle: false,
        elevation: 2,
      ),
      backgroundColor: Color(0xD8E91E63),
      body: SafeArea(
        child: GestureDetector(
          onTap: () => FocusScope.of(context).unfocus(),
          child: Column(
            mainAxisSize: MainAxisSize.max,
            children: [
              Divider(),
              Image.network(
                'https://picsum.photos/seed/349/600',
                width: MediaQuery.of(context).size.width,
                height: MediaQuery.of(context).size.height * 0.25,
                fit: BoxFit.cover,
              ),
              Divider(),
              Align(
                alignment: AlignmentDirectional(0, 0),
                child: FFButtonWidget(
                  onPressed: () {
                    print('Button pressed ...');
                  },
                  text: 'Email /phone  number ',
                  options: FFButtonOptions(
                    width: 300,
                    height: 50,
                    color: Color(0xFF39D2C0),
                    textStyle: FlutterFlowTheme.of(context).bodyText1.override(
                          fontFamily: 'Lexend Deca',
                          color: Colors.white,
                          fontSize: 14,
                          fontWeight: FontWeight.normal,
                        ),
                    elevation: 2,
                    borderSide: BorderSide(
                      color: Colors.transparent,
                      width: 1,
                    ),
                  ),
                ),
              ),
              FFButtonWidget(
                onPressed: () {
                  print('Button pressed ...');
                },
                text: 'Password ',
                options: FFButtonOptions(
                  width: 300,
                  height: 50,
                  color: Color(0xFF39D2C0),
                  textStyle: FlutterFlowTheme.of(context).bodyText1.override(
                        fontFamily: 'Lexend Deca',
                        color: Colors.white,
                        fontSize: 14,
                        fontWeight: FontWeight.normal,
                      ),
                  elevation: 2,
                  borderSide: BorderSide(
                    color: Colors.transparent,
                    width: 1,
                  ),
                ),
              ),
              Divider(),
              Divider(),
              FFButtonWidget(
                onPressed: () {
                  print('Button pressed ...');
                },
                text: 'login ',
                options: FFButtonOptions(
                  width: 130,
                  height: 40,
                  color: FlutterFlowTheme.of(context).primaryColor,
                  textStyle: FlutterFlowTheme.of(context).subtitle2.override(
                        fontFamily: 'Poppins',
                        color: Colors.white,
                      ),
                  borderSide: BorderSide(
                    color: Colors.transparent,
                    width: 1,
                  ),
                  borderRadius: BorderRadius.circular(8),
                ),
              ),
              FFButtonWidget(
                onPressed: () {
                  print('Button pressed ...');
                },
                text: 'create  new  acccount ',
                options: FFButtonOptions(
                  width: 200,
                  height: 50,
                  color: Color(0xEAF1F8F3),
                  textStyle: FlutterFlowTheme.of(context).bodyText1,
                  elevation: 2,
                  borderSide: BorderSide(
                    color: Colors.transparent,
                    width: 1,
                  ),
                ),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
import '../flutter_flow/flutter_flow_theme.dart';
import '../flutter_flow/flutter_flow_util.dart';
import '../flutter_flow/flutter_flow_web_view.dart';
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';

class Feature2Widget extends StatefulWidget {
  const Feature2Widget({Key? key}) : super(key: key);

  @override
  _Feature2WidgetState createState() => _Feature2WidgetState();
}

class _Feature2WidgetState extends State<Feature2Widget> {
  final scaffoldKey = GlobalKey<ScaffoldState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      key: scaffoldKey,
      appBar: AppBar(
        backgroundColor: FlutterFlowTheme.of(context).primaryColor,
        automaticallyImplyLeading: false,
        title: Text(
          'Lets  mingle ',
          style: FlutterFlowTheme.of(context).title2.override(
                fontFamily: 'Poppins',
                color: Colors.white,
                fontSize: 22,
              ),
        ),
        actions: [],
        centerTitle: false,
        elevation: 2,
      ),
      backgroundColor: FlutterFlowTheme.of(context).primaryBackground,
      body: SafeArea(
        child: GestureDetector(
          onTap: () => FocusScope.of(context).unfocus(),
          child: Column(
            mainAxisSize: MainAxisSize.max,
            children: [
              FlutterFlowWebView(
                url: 'https://www.snapchat.com/',
                bypass: true,
                height: 500,
                verticalScroll: true,
                horizontalScroll: true,
              ),
            ],
          ),
        ),
      ),
    );
  }
}
import '../flutter_flow/flutter_flow_theme.dart';
import '../flutter_flow/flutter_flow_util.dart';
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';

class DashboardWidget extends StatefulWidget {
  const DashboardWidget({Key? key}) : super(key: key);

  @override
  _DashboardWidgetState createState() => _DashboardWidgetState();
}

class _DashboardWidgetState extends State<DashboardWidget> {
  final scaffoldKey = GlobalKey<ScaffoldState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      key: scaffoldKey,
      appBar: AppBar(
        backgroundColor: FlutterFlowTheme.of(context).primaryColor,
        automaticallyImplyLeading: false,
        title: Text(
          'Dashboard',
  Image source={require('./my-icon.png')} />
  <Image source={require('./img/check.png')} />
  // GOOD
<Image source={require('./my-icon.png')} />;

// BAD
var icon = this.props.active
  ? 'my-icon-active'
  : 'my-icon-inactive';
<Image source={require('./' + icon + '.png')} />;

// GOOD
var icon = this.props.active
  ? require('./my-icon-active.png')
  : require('./my-icon-inactive.png');
<Image source={icon} />;
  <Image
  source={{ uri: 'app_icon' }}
  style={{ width: 40, height: 40 }}
/>
  <Image
  source={{ uri: 'asset:/app_icon.png' }}
  style={{ width: 40, height: 40 }}
/>
  // GOOD
<Image source={{uri: 'https://reactjs.org/logo-og.png'}}
       style={{width: 400, height: 400}} />

// BAD
<Image source={{uri: 'https://reactjs.org/logo-og.png'}} />
  <Image
  source={{
    uri: 'https://reactjs.org/logo-og.png',
    method: 'POST',
    headers: {
      Pragma: 'no-cache'
    },
    body: 'Your Body goes here'
  }}
  style={{ width: 400, height: 400 }}
/>
  // include at least width and height!
<Image
  style={{
    width: 51,
    height: 51,
    resizeMode: 'contain'
  }}
  source={{
    uri: 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADMAAAAzCAYAAAA6oTAqAAAAEXRFWHRTb2Z0d2FyZQBwbmdjcnVzaEB1SfMAAABQSURBVGje7dSxCQBACARB+2/ab8BEeQNhFi6WSYzYLYudDQYGBgYGBgYGBgYGBgYGBgZmcvDqYGBgmhivGQYGBgYGBgYGBgYGBgYGBgbmQw+P/eMrC5UTVAAAAABJRU5ErkJggg=='
       <Image
  source={{
    uri: 'https://reactjs.org/logo-og.png',
    cache: 'only-if-cached'
  }}
  style={{ width: 400, height: 400 }}
/>{"__packager_asset":true,"uri":"my-icon.png","width":591,"height":573}
  Image source={{ uri: 'something.jpg' }} />
  return (

  <ImageBackground source={...} style={{width: '100%', height: '100%'}}>
    <Text>Inside</Text>
    RCTSetImageCacheLimits(4*1024*1024, 200*1024*1024);
    .
├── button.js
└── img
    ├── check.png
    ├── check@2x.png
    └── check@3x.png
    <Image source={require('./img/check.png')} />
    dependencies {
    // ...

    if (enableHermes) {
+       implementation("com.facebook.react:hermes-engine:+") {
+           exclude group:'com.facebook.fbjni'
+       }
-       def hermesPath = "../../node_modules/hermes-engine/android/";
-       debugImplementation files(hermesPath + "hermes-debug.aar")
-       releaseImplementation files(hermesPath + "hermes-release.aar")
    } else {
        implementation jscFlavor
    }
}
    // Build a debug version of Hermes
./gradlew :ReactAndroid:hermes-engine:assembleDebug
// Build a release version of Hermes
./gradlew :ReactAndroid:hermes-engine:assembleRelease
    exclude group:'com.facebook.fbjni'
    
    
  </ImageBackground>
);
  
          style: FlutterFlowTheme.of(context).title2.override(
                fontFamily: 'Poppins',
                color: Colors.white,
                fontSize: 22,
              ),
        ),
        actions: [],
        centerTitle: false,
        elevation: 2,
      ),
      backgroundColor: FlutterFlowTheme.of(context).primaryBackground,
      body: SafeArea(
        child: GestureDetector(
          onTap: () => FocusScope.of(context).unfocus(),
          child: Column(
            mainAxisSize: MainAxisSize.max,
            children: [
              Container(
                width: MediaQuery.of(context).size.width,
                height: MediaQuery.of(context).size.height * 1,
                child: Stack(
                  children: [
                    Align(
                      alignment: AlignmentDirectional(-0.76, -0.32),
                      child: Image.network(
                        'https://play-lh.googleusercontent.com/fMNJP18ARr0XYrgvq7aMPYrgO-2i83ECZEgOmJNR6I6-CIShAXgu-NPJ4eCPUBOqw7Y=w240-h480-rw',
                        width: 100,
                        height: 100,
                        fit: BoxFit.cover,
                      ),
                    ),
                    Align(
                      alignment: AlignmentDirectional(-0.11, -0.89),
                      child: Image.network(
                        'https://picsum.photos/seed/557/600',
                        width: MediaQuery.of(context).size.width,
                        height: 100,
                        fit: BoxFit.cover,
                      ),
                    ),
                    Align(
                      alignment: AlignmentDirectional(0.59, -0.09),
                      child: Image.network(
                        'https://i0.wp.com/miamimorningstar.com/wp-content/uploads/2018/11/snapchat-icon-medium-1920.png?fit=1920%2C1080&ssl=1',
                        width: 100,
                        height: 100,
                        fit: BoxFit.cover,
                      ),
                    ),
                  ],
                ),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
import '../flutter_flow/flutter_flow_theme.dart';
import '../flutter_flow/flutter_flow_util.dart';
import '../flutter_flow/flutter_flow_web_view.dart';
import 'package:flutter/material.dart';
import 'package:google_fonts/google_fonts.dart';

class Feature1Widget extends StatefulWidget {
  const Feature1Widget({Key? key}) : super(key: key);

  @override
  _Feature1WidgetState createState() => _Feature1WidgetState();
}

class _Feature1WidgetState extends State<Feature1Widget> {
  final scaffoldKey = GlobalKey<ScaffoldState>();

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      key: scaffoldKey,
      appBar: AppBar(
        backgroundColor: FlutterFlowTheme.of(context).primaryColor,
        automaticallyImplyLeading: false,
        title: Text(
          'Link ',
          style: FlutterFlowTheme.of(context).title2.override(
                fontFamily: 'Poppins',
                color: Colors.white,
                fontSize: 30,
                fontWeight: FontWeight.bold,
              ),
        ),
        actions: [],
        centerTitle: false,
        elevation: 2,
      ),
      backgroundColor: FlutterFlowTheme.of(context).primaryBackground,
      body: SafeArea(
        child: GestureDetector(
          onTap: () => FocusScope.of(context).unfocus(),
          child: Column(
            mainAxisSize: MainAxisSize.max,
            children: [
              FlutterFlowWebView(
                url: 'https://www.2go.dating/\n\n',
                bypass: true,
                height: 500,
                verticalScroll: true,
                horizontalScroll: true,
              ),
            ],
          ),
        ),
      ),
    );
  }
}
dependencies {
    // ...

    if (enableHermes) {
+       implementation("com.facebook.react:hermes-engine:+") {
+           exclude group:'com.facebook.fbjni'
+       }
-       def hermesPath = "../../node_modules/hermes-engine/android/";
-       debugImplementation files(hermesPath + "hermes-debug.aar")
-       releaseImplementation files(hermesPath + "hermes-release.aar")
    } else {
        implementation jscFlavor
    }
}./gradlew generateCodegenArtifactsFromSchema
app/build/generated/source/codegen
├── java
│   └── com
│       └── example
│           └── samplelibrary
│               └── NativeAwesomeManagerSpec.java
├── jni
│   ├── Android.mk
│   ├── CMakeLists.txt
│   ├── react
│   │   └── renderer
│   │       └── components
│   │           └── samplelibrary
│   │               ├── ComponentDescriptors.h
│   │               ├── EventEmitters.cpp
│   │               ├── EventEmitters.h
│   │               ├── Props.cpp
│   │               ├── Props.h
│   │               ├── ShadowNodes.cpp
│   │               └── ShadowNodes.h
│   ├── samplelibrary-generated.cpp
│   └── samplelibrary.h
└── schema.json
import androidx.annotation.NonNull;

import com.example.samplelibrary.NativeAwesomeManagerSpec;
import com.facebook.react.bridge.Promise;
import com.facebook.react.bridge.ReactApplicationContext;

public class NativeAwesomeManager extends NativeAwesomeManagerSpec {

    public static final String NAME = "NativeAwesomeManager";

    public NativeAwesomeManager(ReactApplicationContext reactContext) {
        super(reactContext);
    }

    @Override
    public void getString(String id, Promise promise) {
        // Implement this method
    }

    @NonNull
    @Override
    public String getName() {
        return NAME;
    }
}
public class MyApplication extends Application implements ReactApplication {

  private final ReactNativeHost mReactNativeHost =
    new ReactNativeHost(this) {

      // Add those lines:
      @Nullable
      @Override
      protected JSIModulePackage getJSIModulePackage() {
        return new JSIModulePackage() {
          @Override
          public List<JSIModuleSpec> getJSIModules(
              final ReactApplicationContext reactApplicationContext,
              final JavaScriptContextHolder jsContext) {
            final List<JSIModuleSpec> specs = new ArrayList<>();
            specs.add(new JSIModuleSpec() {
              @Override
              public JSIModuleType getJSIModuleType() {
                return JSIModuleType.UIManager;
              }

              @Override
              public JSIModuleProvider<UIManager> getJSIModuleProvider() {
                final ComponentFactory componentFactory = new ComponentFactory();
                CoreComponentsRegistry.register(componentFactory);
                final ReactInstanceManager reactInstanceManager = getReactInstanceManager();

                ViewManagerRegistry viewManagerRegistry =
                    new ViewManagerRegistry(
                        reactInstanceManager.getOrCreateViewManagers(
                            reactApplicationContext));

                return new FabricJSIModuleProvider(
                    reactApplicationContext,
                    componentFactory,
                    new EmptyReactNativeConfig(),
                    viewManagerRegistry);
              }
            });
            return specs;
          }
        };
      }
    };
}
public class MainActivity extends ReactActivity {

  // Add the Activity Delegate, if you don't have one already.
  public static class MainActivityDelegate extends ReactActivityDelegate {

    public MainActivityDelegate(ReactActivity activity, String mainComponentName) {
      super(activity, mainComponentName);
    }

    @Override
    protected ReactRootView createRootView() {
      ReactRootView reactRootView = new ReactRootView(getContext());

      // Make sure to call setIsFabric(true) on your ReactRootView
      reactRootView.setIsFabric(true);
      return reactRootView;
    }
  }

  // Make sure to override the `createReactActivityDelegate()` method.
  @Override
  protected ReactActivityDelegate createReactActivityDelegate() {
    return new MainActivityDelegate(this, getMainComponentName());
  }
}
yarn react-native run-android
BUNDLE ./App.js
LOG Running "App" with {"fabric":true,"initialProps":{},"rootTag":1}
import codegenNativeComponent from 'react-native/Libraries/Utilities/codegenNativeComponent';

// babel-plugin-codegen will replace the function call to use NativeComponentRegistry
// 'RCTWebView' is interopped by RCTFabricComponentsPlugins

export default (codegenNativeComponent<NativeProps>(
  'RCTWebView',
): HostComponent<NativeProps>);
import type {Int32} from 'react-native/Libraries/Types/CodegenTypes';
import codegenNativeComponent from 'react-native/Libraries/Utilities/codegenNativeComponent';
import type {HostComponent} from 'react-native';
import type {ViewProps} from 'react-native/Libraries/Components/View/ViewPropTypes';

type NativeProps = $ReadOnly<{|
  ...ViewProps, // This is required.
  someNumber: Int32,
|}>;

[...]

export default (codegenNativeComponent<NativeProps>(
  'RNTMyNativeView',
): HostComponent<NativeProps>);
// View manager for MyNativeView components.
@ReactModule(name = MyNativeViewManager.REACT_CLASS)
public class MyNativeViewManager extends SimpleViewManager<MyNativeView>
        implements RNTMyNativeViewManagerInterface<MyNativeView> {

  public static final String REACT_CLASS = "RNTMyNativeView";

  private final ViewManagerDelegate<MyNativeView> mDelegate;

  public MyNativeViewManager() {
    mDelegate = new RNTMyNativeViewManagerDelegate<>(this);
  }

  @Nullable
  @Override
  protected ViewManagerDelegate<MyNativeView> getDelegate() {
    return mDelegate;
  }

  @NonNull
  @Override
  public String getName() {
    return REACT_CLASS;
  }

  @NonNull
  @Override
  protected MyNativeView createViewInstance(@NonNull ThemedReactContext reactContext) {
    return new MyNativeView(reactContext);
  }
}
public class MyApplication extends Application implements ReactApplication {

  private final ReactNativeHost mReactNativeHost = new ReactNativeHost(this) {
    @Override
    public boolean getUseDeveloperSupport() { /* ... */ }

    @Override
    protected List<ReactPackage> getPackages() {
      List<ReactPackage> packages = new PackageList(this).getPackages();

      // ... other packages or `TurboReactPackage added` here...

      // Add those lines.
      packages.add(new ReactPackage() {
        @NonNull
        @Override
        public List<NativeModule> createNativeModules(
            @NonNull ReactApplicationContext reactContext) {
          return Collections.emptyList();
        }

        @NonNull
        @Override
        public List<ViewManager> createViewManagers(
            @NonNull ReactApplicationContext reactContext) {
          // Your ViewManager is returned here.
          return Collections.singletonList(new MyNativeViewManager());
        }
      });
      return packages;
    }
  };
}
package com.awesomeproject;

import com.facebook.jni.HybridData;
import com.facebook.proguard.annotations.DoNotStrip;
import com.facebook.react.fabric.ComponentFactory;
import com.facebook.soloader.SoLoader;

@DoNotStrip
public class MyComponentsRegistry {
  static {
    SoLoader.loadLibrary("fabricjni");
  }

  @DoNotStrip private final HybridData mHybridData;

  @DoNotStrip
  private native HybridData initHybrid(ComponentFactory componentFactory);

  @DoNotStrip
  private MyComponentsRegistry(ComponentFactory componentFactory) {
    mHybridData = initHybrid(componentFactory);
  }

  @DoNotStrip
  public static MyComponentsRegistry register(ComponentFactory componentFactory) {
    return new MyComponentsRegistry(componentFactory);
  }
}
public class MyApplication extends Application implements ReactApplication {

  private final ReactNativeHost mReactNativeHost = new ReactNativeHost(this) {
    @Nullable
    @Override
    protected JSIModulePackage getJSIModulePackage() {
      return new JSIModulePackage() {
        @Override
        public List<JSIModuleSpec> getJSIModules(
                final ReactApplicationContext reactApplicationContext,
                final JavaScriptContextHolder jsContext) {
          final List<JSIModuleSpec> specs = new ArrayList<>();
          specs.add(new JSIModuleSpec() {
            // ...

            @Override
            public JSIModuleProvider<UIManager> getJSIModuleProvider() {
              final ComponentFactory componentFactory = new ComponentFactory();
              CoreComponentsRegistry.register(componentFactory);

              // Add this line just below CoreComponentsRegistry.register
              MyComponentsRegistry.register(componentFactory);

              // ...
            }
          });
          return specs;
        }
      };
    }
  };
}
#pragma once

#include <ComponentFactory.h>
#include <fbjni/fbjni.h>
#include <react/renderer/componentregistry/ComponentDescriptorProviderRegistry.h>
#include <react/renderer/componentregistry/ComponentDescriptorRegistry.h>

namespace facebook {
namespace react {

class MyComponentsRegistry
    : public facebook::jni::HybridClass<MyComponentsRegistry> {
  public:
  constexpr static auto kJavaDescriptor =
      "Lcom/awesomeproject/MyComponentsRegistry;";

  static void registerNatives();

  MyComponentsRegistry(ComponentFactory *delegate);

  private:
  friend HybridBase;

  static std::shared_ptr<ComponentDescriptorProviderRegistry const>
  sharedProviderRegistry();

  const ComponentFactory *delegate_;

  static jni::local_ref<jhybriddata> initHybrid(
      jni::alias_ref<jclass>,
      ComponentFactory *delegate);
};

} // namespace react
} // namespace facebook
#include "MyComponentsRegistry.h"

#include <CoreComponentsRegistry.h>
#include <fbjni/fbjni.h>
#include <react/renderer/componentregistry/ComponentDescriptorProviderRegistry.h>
#include <react/renderer/components/rncore/ComponentDescriptors.h>
#include <react/renderer/components/samplelibrary/ComponentDescriptors.h>

namespace facebook {
namespace react {

MyComponentsRegistry::MyComponentsRegistry(
    ComponentFactory *delegate)
    : delegate_(delegate) {}

std::shared_ptr<ComponentDescriptorProviderRegistry const>
MyComponentsRegistry::sharedProviderRegistry() {
  auto providerRegistry = CoreComponentsRegistry::sharedProviderRegistry();

  providerRegistry->add(concreteComponentDescriptorProvider<
                        RNTMyNativeViewComponentDescriptor>());

  return providerRegistry;
}

jni::local_ref<MyComponentsRegistry::jhybriddata>
MyComponentsRegistry::initHybrid(
    jni::alias_ref<jclass>,
    ComponentFactory *delegate) {
  auto instance = makeCxxInstance(delegate);

  auto buildRegistryFunction =
      [](EventDispatcher::Weak const &eventDispatcher,
          ContextContainer::Shared const &contextContainer)
      -> ComponentDescriptorRegistry::Shared {
    auto registry = MyComponentsRegistry::sharedProviderRegistry()
                        ->createComponentDescriptorRegistry(
                            {eventDispatcher, contextContainer});

    auto mutableRegistry =
        std::const_pointer_cast<ComponentDescriptorRegistry>(registry);

    mutableRegistry->setFallbackComponentDescriptor(
        std::make_shared<UnimplementedNativeViewComponentDescriptor>(
            ComponentDescriptorParameters{
                eventDispatcher, contextContainer, nullptr}));

    return registry;
  };

  delegate->buildRegistryFunction = buildRegistryFunction;
  return instance;
}

void MyComponentsRegistry::registerNatives() {
  registerHybrid({
      makeNativeMethod("initHybrid", MyComponentsRegistry::initHybrid),
  });
}

} // namespace react
} // namespace facebook
#include <fbjni/fbjni.h>
#include "MyApplicationTurboModuleManagerDelegate.h"
// Add this import
#include "MyComponentsRegistry.h"

JNIEXPORT jint JNICALL JNI_OnLoad(JavaVM *vm, void *) {
  return facebook::jni::initialize(vm, [] {
    facebook::react::MyApplicationTurboModuleManagerDelegate::registerNatives();

    // Add this line
    facebook::react::MyComponentsRegistry::registerNatives();
  });
}
yarn react-native run-android
