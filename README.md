# MotionLayout sample
Sample application to test the new [MotionLayout](https://developer.android.com/reference/android/support/constraint/motion/MotionLayout). This sample app will display a fullscreen image of the Empire State Building and will provide some info when collapsing the image.

![demo](/assets/motions.gif)

## How it works
The `MotionLayout` works by defining `ConstraintSet`s that will define how the motion looks when it starts and how it looks when it finishes the motion. Further more, a transition is defined where duration, interpolators, etc. can be set.

Each `ConstraintSet` is then added to a `MotionScene` where `OnSwipe` or `OnClick` events can be defined to trigger the motion.

## Libraries
* [Android Support Library](https://developer.android.com/topic/libraries/support-library/features)
* [ConstraintLayout](https://developer.android.com/reference/android/support/constraint/ConstraintLayout)
