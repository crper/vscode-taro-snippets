
# VSCode-taro-snippets

[![Version](http://vsmarketplacebadge.apphb.com/version/crper.vscode-taro-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=crper.vscode-taro-snippets)
[![Install](http://vsmarketplacebadge.apphb.com/installs-short/crper.vscode-taro-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=crper.vscode-taro-snippets)

为了少敲重复代码,节约时间,这个东东就出来了;

用JS的格式,但是智能提示响应范围包括如下

- `typescript`
- `javascript`
- `javascriptreact`
- `typescriptreact`

部分位置设置了占位符,可以初始化的时候修改及`tab`切换


-----

# 效果

![演示Demo](images/show.gif)


---

# 代码片段

- `tarocc`

```javascript
import Taro , { Component } from '@tarojs/taro';
import { View, Text , Button} from '@tarojs/components';

export default class Index extends Component {

   config = {
       navigationBarTitleText: ''
  }

  state={}

  componentWillMount () {}
  componentDidMount () {}
  componentWillReceiveProps (nextProps,nextContext) {}
  componentWillUnmount () {}
  componentDidShow () {}
  componentDidHide () {}
  componentDidCatchError () {}
  componentDidNotFound () {}
  render() {
    return (
      <View>

      </View>
    );
  }
}
export default Index;

```

- `taropc`


```javascript

import Taro , { PureComponent } from '@tarojs/taro';
import { View, Text , Button} from '@tarojs/components';

class Index extends PureComponent {

   config = {
       navigationBarTitleText: ''
  }

  state={}

  componentWillMount () {}
  componentDidMount () {}
  componentWillReceiveProps (nextProps,nextContext) {}
  componentWillUnmount () {}
  componentDidShow () {}
  componentDidHide () {}
  componentDidCatchError () {}
  componentDidNotFound () {}
  render() {
    return (
      <View>

      </View>
    );
  }
}
export default Index;

```

- `taroaf`


```json
config = {
  pages: [
    'pages/index/index'
     ],
  window: {
    backgroundTextStyle: 'light',
    navigationBarBackgroundColor: '#fff',
    navigationBarTitleText: 'WeChat',
    navigationBarTextStyle: 'black'
    }
}

```

- `taroimd`

```javascript
import {} from '@tarojs/mobx'
```


- `taroird`

```javascript
import {} from '@tarojs/redux'
```

- `taroimm`

```javascript
import {} from '$tarojs/'
```


- `taroir`


```javascript
import { connect } from '@tarojs/redux'
```


- `taroim`


```javascript
import {inject, observer} from '@tarojs/mobx'
```

- `imo`

```javascript
import { action, observable, computed, toJS } from 'mobx'
```


---

# 其他


没有做专门的`ts`版本,有兴趣的小伙伴可以提交`PR`
