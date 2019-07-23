# scroll-view-autoLayout
How to configure a UIScrollView with Auto Layout in Interface Builder. <br />
We saw many ios beginner developers are stuck on scrollView with dynamic width and height. We will show you a good way of handling this things. In this approach we are doing this with storyboard only. As per your requirement create your design(Any height) it will automatically take care all things. <br />
Follow this steps: <br />
1. Create new project( eg. scrollViewAutoLayout). <br />
    ![image 1](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112126/Screen_Shot_2017-04-24_at_6.21.58_PM_tk5ny0.png) <br />
2. After creating project go to Main.storyboard file. <br />
    ![image 2](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112258/Screen_Shot_2017-04-24_at_6.22.17_PM_baqtfz.png) <br />  
3. Now you can see empty view controller on storyboard. <br />
    ![image 3](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112257/Screen_Shot_2017-04-24_at_6.22.42_PM_a8dkxo.png) <br />
4. Drag scrollView from object library to view controller.<br />
    ![image 4](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112257/Screen_Shot_2017-04-24_at_6.29.37_PM_tzcn3m.png) <br />
5. now it’s time to set constraint for scroll view. <br />
6. Set scroll view constraint (top, bottom, leading and trailing) as (0,0,0,0). <br />
    ![image 5](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112257/Screen_Shot_2017-04-24_at_6.30.23_PM_rpaao2.png) <br />
7. Now update the frame. <br />
8. Now we require contentView for scroll view. <br />
9. Drag view from object library to scroll View. <br />
    ![image 6](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112258/Screen_Shot_2017-04-24_at_6.34.29_PM_jekvg9.png) <br />
10. now it’s time to set constraint for view(inside scroll view). <br />
    ![image 7](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112258/Screen_Shot_2017-04-24_at_6.34.46_PM_v6sxhm.png) <br />
11. Set view constraint (top, bottom, leading and trailing) as (0,0,0,0). <br />
12. Now you can see hierarchy like this view -> scroll view -> view(content view). <br />
    ![image 8](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112259/Screen_Shot_2017-04-24_at_6.34.59_PM_qxchj8.png) <br />
13. Now we need add more constraint for content view. <br />
* Most important step * <br />
14. Our content view must have equal width and equal height with parent view. <br />
    ![image 9](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112259/Screen_Shot_2017-04-24_at_6.36.17_PM_gczljc.png) <br />
15. Now select height constraint of content view and set priority with low(250). <br />
    ![image 10](http://res.cloudinary.com/dykhnkdyi/image/upload/v1493112260/Screen_Shot_2017-04-24_at_6.38.42_PM_cgrnup.png) <br />
16. We are done with our setup. <br />
17. Now you can design your view with any height. <br />
18. Congrats you are done with scroll view with autolayout. <br />

## Found a bug?
Let us know! Send a pull request or a patch. Questions? Ask! We're here to help. We will respond to all filed issues.

## Contributors
[Click here](https://github.com/GKM-IT/scroll-view-autoLayout/contributors) to see a list of the contributors to this library.
