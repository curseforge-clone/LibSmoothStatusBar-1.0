# LibSmoothStatusBar-1.0

Smoothly animates status bar

This library is based on oUF Smooth Update by Xuerian.  
This library exposes two simple functions to enable or disable animation on a specific StatusBar frame (created by `CreateFrame("StatusBar", ..)`).


## Functions

### `:SmoothBar(bar)`
Enables smooth animation for the bar. The `bar:SetValue()` method will be overloaded to handle animation.  
Arguments:
* `bar` - StatusBar frame - The StatusBar to be animated


### `:ResetBar(bar)`
Restores the bar to its original state. Disabling animation.  
Arguments:
* `bar` - StatusBar frame - The StatusBar to be restored
