# wepy-slide
在小程序wepy框架使用的侧滑组件
```
npm install wepy-slide --save
```
```
<!-- speed是动画持续时间，可不传 -->
<slide :speed="300" >
  <repeat >
    <image class="slide-img" src="{{item.image}}"></image>
  </repeat>
</slide>

<script>
import slide from 'wepy-slide'
export default class HomeIndex extends wepy.page {
  components = {
    slide: slide
  }
}
</script>
```