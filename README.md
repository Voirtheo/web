# web

不让父组件向子组件乱传数据，我们可以在子组件定义父组件可以传入的类型<br>
例如：<br>
```    
static propTypes = {
    comment: PropTypes.object
}
```    
则表示父组件只能往子组件传对象类型的数据
