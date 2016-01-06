# MVVMC
Model View ViewModel Coordinator

## What is a coordinator?
- https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191
- http://khanlou.com/2015/10/coordinators-redux/
- https://github.com/backchannel/BackchannelSDK-iOS

## Code

### Info.plist
- Do not use storyboard as main interface (remove UIMainStoryboardFile key).

### AppDelegate.swift
- Set window and its root view controller.
- Add coordinate variable.
- Set coordinator and its view controller.
- Start coordinator.
