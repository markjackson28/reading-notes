
# Class 14

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*14a Reading*

CSS Transforms

- transform property has 2d and 3d settings.
- 2d works with the x and y axis.
- 3d works with the x, y, and z axis.
- Different values for 2d and 3d: rotate, scale, translate, skew, and perspective.
- You can also combine the values to create something different.

CSS Transitions and Animations

- Use :hover, :focus, :active, and :target styles to determine different states of the transition.
- The transition-property determines what will be altered.
- Not all properties can use the transition-property.
- To use animations you should use the @keyframes rule.
- 8 simple ways to improve your transitions: fade in, change color, grow and shrink, rotate elements, square to circle, 3d shadow, swing, and inset border.

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
.stage {
  background: #eaeaed;
  border-radius: 6px;
  height: 150px;
  position: relative;
  min-width: 538px;
}
.stage:hover .ball {
  animation: slide 2s linear;
}
.ball {
  background: #2db34a;
  border-radius: 50%;
  height: 50px;
  position: absolute;
  width: 50px;
}
```

[CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

[CSS Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

[8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

[6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)

[CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)

[404](https://codepen.io/kieranfivestars/pen/MYdQxX)

[Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv)

*14b Reading*

Overall, that was a pretty good and important article to read. For the most part, I do agree with most of the article. Finding a perfect team is really hard to find when there are so many variables. I do believe that a team that should somehow connect on an emotional level. Especially with my military background, we had to get to really know each other really well since we would be working with each other for a while. Team bonding somehow is very important along with treating each other with respect. At my previous job, I did have a manager who was very talkative and never really care about his team. I brought up a personal situation about him and I, he got defensive and from then on, I never went to him again. I went into work, did my job, and left. I definitely did not feel like I was in a psychological safe space. I think it’s very important that jobs somehow incorporate psychological safety into the workspace. 


[What Google Learned From Its Quest to Build the Perfect Team](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)
