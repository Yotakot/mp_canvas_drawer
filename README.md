

### fork自<a href='https://github.com/kuckboy1994/mp_canvas_drawer/'>mp_canvas_drawer</a>

#### 增加图片裁剪，避免图片变形

##### 未开启图片裁剪

 ```
  {
            type: 'image',
            url: '/images/img_vertical.jpg',
            top: 136,
            left: 42.5,
            width: 290,
            scaleSrc:false,
            height: 186
 }
 ```
 <image src="https://github.com/Yotakot/mp_canvas_drawer/blob/master/images/preview.png"/>

##### 开启图片裁剪
```
  {
            type: 'image',
            url: '/images/img_vertical.jpg',
            top: 136,
            left: 42.5,
            width: 290,
            scaleSrc:true,
            height: 186
 }
 ```
 <image src="https://github.com/Yotakot/mp_canvas_drawer/blob/master/images/scale_preview.png"/>
