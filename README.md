# Flutter Animated Button

## Installing

### Depend on it

Add this to your package's pubspec.yaml file:

   ```
   dependencies:
  flutter_animated_button: <latest_version>
   ```

### Import it

Now in your Dart code, you can use:

   ```
   import 'package:flutter_animated_button/flutter_animated_button.dart';
   ```

## Usage

You can override the animationDuration of animation of the button by setting its duration in each AnimatedButton class, also you can get animationController for animation status and animation value during the animation. You can change text style, selected textColor and background color of button by textStyle,selectedTextColor,backgroundColor and selectedBackgroundColor. If you want revert animation when button already select then you can do it by isReverse property.

   ```
   AnimatedButton(
                width: 200,
                text: 'SUBMIT',
                selectedTextColor: Colors.black,
                transitionType: TransitionType.BOTTOM_TO_TOP,
                textStyle: TextStyle(
                    fontSize: 28,
                    letterSpacing: 5,
                    color: Colors.deepOrange,
                    fontWeight: FontWeight.w300),
              )
   ```

### Animation On

1. AnimatedOn.onTap

2. AnimatedOn.onHover
