# Installation
npm install react-navigation --save

npm install --save react-native-gesture-handler

npm react-native link

npm install

## Import this lines in java -> mainactivity.java

import com.facebook.react.ReactActivityDelegate;

import com.facebook.react.ReactRootView;

import com.swmansion.gesturehandler.react.RNGestureHandlerEnabledRootView;


    @Override
	protected ReactActivityDelegate createReactActivityDelegate() {
      return new ReactActivityDelegate(this, getMainComponentName()) {
      @Override
      protected ReactRootView createRootView() {
      return new RNGestureHandlerEnabledRootView(MainActivity.this);
       }
     };
    }
