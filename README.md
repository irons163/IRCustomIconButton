# IRCustomIconButton

## Install
### Git
- Git clone this project.
- Copy this project into your own project.

### Donwload
- Download `IRCustomIconButton.h` and `IRCustomIconButton.m`.
- Copy these two files into your own project.

## Usage

@property (nonatomic, assign) IBInspectable UIViewContentMode imageViewContentMode;
- Set UIViewContentMode to the imageView of button.

@property (nonatomic, assign) IBInspectable NSInteger iconContentMode;
- Set iconContentMode to button.
```objc
typedef NS_ENUM(NSInteger, IconContentMode) {
    IconContentModeCenter       = 0,
    IconContentModeLeft,
    IconContentModeRight
};
```

@property (nonatomic, assign) IBInspectable CGSize iconSizePersent; // >0
- Set iconSizePersent to button.

@property (nonatomic, assign) IBInspectable CGFloat cornerRadius;
- Set cornerRadius to button.

@property (nonatomic, assign) IBInspectable CGFloat borderWidth;
- Set borderWidth to the border of button.

@property (nonatomic, strong) IBInspectable UIColor *borderColor;
- Set UIColor to the border of button.

@property (nonatomic, assign) IBInspectable CGFloat titleEdgeTop;

@property (nonatomic, assign) IBInspectable CGFloat titleEdgeLeft;

@property (nonatomic, assign) IBInspectable CGFloat titleEdgeBottom;

@property (nonatomic, assign) IBInspectable CGFloat titleEdgeRight;
- Set titleEdge to button.
