<!--
 * @Description: Vant Typescript Snippets
 * @Author: sands
 * @Date: 2019-12-12
 * @LastEditTime: 2019-12-12
 * @LastEditors: 
 -->
## Vant VS Code Snippets

### Snippets List
 work in .vue file 

#### Basic 
vantpl
```
<template>
    <div>
    </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator';
import { Row, Col, Cell, CellGroup } from 'vant';
@Component({
     name: '组件名',
     components: {
         [Row.name]: Row,
         [Col.name]: Col,
         [Cell.name]: Cell,
         [CellGroup.name]: CellGroup
     }
})
export default class 组件名 extends Vue {
     created() {

     }
}
</script>

<style lang="scss">
</style>
```

#### Basic Part
|  No.  | Trigger&nbsp;Key | Vant Tag                |
| :---: | :--------------: | :---------------------- |
|  1.   |      `vanr`      | `<van-row>`             |
|  2.   |      `vanc`      | `<van-col>`             |
|  3.   |     `vanrf`      | `<van-row type="flex">` |
|  4.   |      `vanb`      | `<van-button>`          |
|  5.   |    `vancell`     | `<van-cell>`            |
|  6.   |    `vanicon`     | `<van-icon>`            |
|  7.   |     `vanimg`     | `<van-image>`           |
|  8.   |    `vanpopup`    | `<van-popup>`           |


#### Form Part

|  No.  | Trigger&nbsp;Key | Vant Tag                |
| :---: | :--------------: | :---------------------- |
|  1.   |     `vanfd`      | `<van-field>`           |
|  2.   |     `vanrd`      | `<van-radio>`           |
|  3.   |     `vanck`      | `<van-checkbox>`        |
|  4.   |    `vanrate`     | `<van-rate>`            |
|  5.   |   `vansearch`    | `van-search`            |
|  6.   |   `vanslider`    | `van-slider`            |
|  7.   |   `vanstepper`   | `<van-stepper>`         |
|  8.   |   `vanswitch`    | `<van-switch>`          |
|  9.   |     `vanpk`      | `<van-picker>`          |
|  10.  |    `vandate`     | `<van-datetime-picker>` |
|  11.  |     `vanup`      | `<van-uploader>`        |


#### Action Part

|  No.  | Trigger Key | Vant Tag              |
| :---: | :---------: | :-------------------- |
|  1.   |   `vandg`   | `<van-dialog>`        |
|  2.   |   `vanal`   | `Dialog Alert({})`    |
|  3.   |   `vancf`   | `Dialog Confirm({})`  |
|  4.   |   `vannt`   | `Notify({})`          |
|  5.   |   `vants`   | `Toast({})`           |
|  6.   |   `vanld`   | `<van-loading>`       |
|  7.   |   `vanol`   | `<van-overlay>`       |
|  8.   |   `vanas`   | `<van-action-sheet>`  |
|  9.   |   `vandm`   | `<van-dropdown-menu>` |
|  10.  |   `vanpr`   | `<van-pull-refresh>`  |
|  11.  |   `vansc`   | `<van-swipe-cell>`    |


#### Display Part

|  No.  |  Trigger Key  | Vant Tag           |
| :---: | :-----------: | :----------------- |
|  1.   |  `vancircle`  | `<van-circle>`     |
|  2.   | `vanprogress` | `<van-progress>`   |
|  3.   | `vancollapse` | `<van-collapse>`   |
|  4.   |    `vancd`    | `<van-count-down>` |
|  5.   |    `vandv`    | `<van-divider>`    |
|  6.   |    `vanlz`    | `<van-lazy>`       |
|  7.   |   `vanlist`   | `<van-list>`       |
|  8.   |   `vanntb`    | `<van-notice-bar>` |
|  9.   |    `vanpn`    | `<van-panel>`      |
|  10.  |    `vansk`    | `<van-skeleton>`   |
|  11.  |  `vansteps`   | `<van-steps>`      |
|  12.  |  `vansticky`  | `<van-sticky>`     |
|  13.  |    `vansw`    | `<van-swipe>`      |
|  14.  |   `vantag`    | `<van-tag>`        |


#### Navigation Part

|  No.  | Trigger Key | Vant Tag            |
| :---: | :---------: | :------------------ |
|  1.   |  `vangrid`  | `<van-grid>`        |
|  2.   |   `vanib`   | `<van-index-bar>`   |
|  3.   |   `vannb`   | `<van-nav-bar>`     |
|  4.   |   `vanpg`   | `<van-pagination>`  |
|  5.   |   `vansd`   | `<van-sidebar>`     |
|  6.   |  `vantabs`  | `<van-tabs>`        |
|  7.   |  `vantbar`  | `<van-tabbar>`      |
|  8.   |  `vantrs`   | `<van-tree-select>` |

#### Business Part
|  No.  | Trigger Key | Vant Tag             |
| :---: | :---------: | :------------------- |
|  1.   |  `vanade`   | `<van-address-edit>` |
|  2.   |  `vanadl`   | `<van-address-list>` |
|  3.   |  `vanarea`  | `<van-area>`         |
|  4.   |  `vancard`  | `<van-card>`         |
|  5.   |  `vanctc`   | `<van-contact-card>` |
|  6.   |  `vancoup`  | `<van-coupon>`       |
|  7.   | `vangoods`  | `<van-goods-action>` |
|  8.   |  `vansbar`  | `<van-submit-bar>`   |
|  9.   |  `vansku`   | `<van-sku>`          |
