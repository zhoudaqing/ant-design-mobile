---
order: 0
title: NavBar
---

````jsx
import { NavBar, Icon } from 'antd-mobile';

ReactDOM.render(
  <div>
    <div style={{ height: 8 }} />
    <NavBar leftContent="返回" mode="light"
      rightContent={[<Icon key="0" type="user" />, <Icon key="1" type="search" />, <Icon key="2" type="plus" />]}
    >NavBar</NavBar>
  </div>
, mountNode);
````
