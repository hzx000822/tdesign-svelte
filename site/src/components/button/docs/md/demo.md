---
title: Button 按钮
description: 按钮用于开启一个闭环的操作任务，如“删除”对象、“购买”商品等。
isComponent: true
usage: { title: '', description: '' }
spline: base
---

[[toc]]

### 基础按钮

基础按钮包括填充按钮、描边按钮、虚框按钮、和文字按钮。

#### 填充按钮

一般用于主按钮，是用户在整个页面需要关注优先级最高的操作，引导用户关注并操作。

#### 描边按钮

描边按钮常见白底加文字的形式，在视觉强调程度上弱于填充按钮，通常与填充按钮搭配成组使用。

#### 虚框按钮

按钮边框线为虚线，常用于表单中的添加配置项。

#### 文字按钮

直接使用文字作为按钮。是视觉吸引力最弱的一个按钮，通常出现在表格操作栏、标题和字段旁等。

<script>
import Base from "../../example/Base.svelte"
</script>

<Base></Base>

### 图标按钮

图标按钮由图标+文字或图标构成。通过图标可增强识别性，以便直观理解。

<script>
import Icon from "../../example/Icon.svelte"
</script>

<Icon></Icon>

### 幽灵按钮

幽灵按钮将按钮的内容反色，背景变为透明，一般是底色透明。常用于有色背景上，例如 banner 图等。

<script>
import Ghost from "../../example/Ghost.svelte"
</script>

<Ghost></Ghost>

### Block 按钮

Block 按钮在宽度上充满其所在的父容器（无 padding 和 margin 值）。该按钮常见于移动端和一些表单场景中。

<script>
import Block from "../../example/Block.svelte"
</script>

<Block></Block>

### 不同颜色主题按钮

提供浅灰色、蓝色、红色、黄色和绿色为主题的按钮。

<script>
import Theme from "../../example/Theme.svelte"
</script>

<Theme></Theme>

### 不同状态的按钮

提供加载、禁用两种状态。

<script>
import Status from "../../example/Status.svelte"
</script>

<Status></Status>

### 不同尺寸的按钮

提供大、中（默认）、小三种尺寸。

<script>
import Size from "../../example/Size.svelte"
</script>

<Size></Size>

### 不同形状的按钮

提供长方形、正方形、圆角长方形、圆形四种形状。

<script>
import Shape from "../../example/Shape.svelte"
</script>

<Shape></Shape>
