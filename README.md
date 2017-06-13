# m555
1. https://github.com/nsuinteger/ImageMaskingExample
2. https://github.com/deepakbhati99/UIImageMask
3. https://github.com/themausam/image-masking
1. https://www.youtube.com/watch?v=NeYAwB6C4A0 - get and post method
2.  https://www.youtube.com/watch?v=PU92i_A-K6o - get and post 2
3. https://www.youtube.com/watch?v=MDiKvqiP9zA - webservices detailed
https://www.youtube.com/watch?v=obJ2AmbrHgQ


1. #import <QuartzCore/QuartzCore.h>

// remember to include Framework as well

CALayer *mask = [CALayer layer];

mask.contents = (id)[[UIImage imageNamed:@"mask.png"] CGImage];

mask.frame = CGRectMake(0, 0, <img_width>, <img_height>);

yourImageView.layer.mask = mask;


yourImageView.layer.masksToBounds = YES;

2. https://github.com/Werbary/WBMaskedImageView wbmaskedimageview

3. self.defaultImageView.mask = self.maskImageView

4. https://github.com/TinyCrayon/TinyCrayon-iOS-SDK - refer

5. http://www.cnblogs.com/YouXianMing/p/4483095.html - imp mask

6. https://dannygtech.wordpress.com/2014/04/08/uiimageview-and-masks-with-objective-c/ - refer calyer

7. https://gist.github.com/travisjeffery/3278809 - refer imp

8. UIImageView *image=[[UIImageView alloc]initWithImage:[UIImage imageNamed:@"balloon_selected_left.png"] ];

    self.maskImage.layer.mask=image.layer;
    
9. https://stackoverflow.com/questions/8630869/add-sublayer-to-a-imageview-layer - imp2

10. https://stackoverflow.com/questions/14670985/adding-a-circle-mask-layer-on-an-uiimageview - refer imp

11. https://stackoverflow.com/questions/31947269/how-to-move-and-crop-image-from-masked-image - pan imp

12. https://stackoverflow.com/questions/17663686/displaying-a-view-over-an-imageview-which-is-moveable - imp2

13. https://stackoverflow.com/questions/11808114/how-to-move-image-with-in-the-frame-using-gestures-in-iphone-sdk - imp 3

14. imageView.layer.contentsRect = CGRectMake(0.0, 0.0, 0.3, 0.3);  -- imp

15. https://stackoverflow.com/questions/419710/how-do-i-pan-the-image-inside-a-uiimageview - image moving with scrolling imp


16.
