<template>
  <div class="page">
    <au-panel class="section" title="组件描述">
      <p class="paragraph">
        一个简单的面板组件
      </p>
      <!-- 组件示例 -->
      <div class="component-example">
        <au-panel title="Panel Panel" icon="home" style="width: 500px;">
          <div slot="title-right">
            <au-icon type="bars"></au-icon>
          </div>
          <p class="au-theme-color--base-3">
            Minim anim minim consectetur non veniam sint tempor ea irure aliqua reprehenderit. Adipisicing est ut elit elit. Et cillum anim aute do sunt exercitation anim excepteur incididunt.
          </p>
        </au-panel>
      </div>
      <!-- 组件示例 -->
    </au-panel>
    <au-panel class="section" title="Props">
      <au-table>
        <thead>
          <tr>
            <th>字段</th>
            <th>必填</th>
            <th>类型</th>
            <th>默认</th>
            <th>可选</th>
            <th>说明</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>title</td>
            <td>
              <!-- <au-icon type="check" class="au-theme-color--success"></au-icon> -->
              <au-icon type="times"></au-icon>
            </td>
            <td>String</td>
            <td><au-icon type="minus"></au-icon></td>
            <td><au-icon type="minus"></au-icon></td>
            <td>
              面板的标题
            </td>
          </tr>
          <tr>
            <td>icon</td>
            <td>
              <!-- <au-icon type="check" class="au-theme-color--success"></au-icon> -->
              <au-icon type="times"></au-icon>
            </td>
            <td>String</td>
            <td>
              详情参考<router-link class="au-theme-color--info" :to="{name: 'icon'}">icon</router-link>组件
            </td>
            <td><au-icon type="minus"></au-icon></td>
            <td>
              面板标题左侧的图标
            </td>
          </tr>
        </tbody>
      </au-table>
    </au-panel>
    <au-panel class="section" title="Slots">
      <au-table>
        <thead>
          <tr>
            <th>名称</th>
            <th>说明</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>默认slot</td>
            <td>
              面板内容
            </td>
          </tr>
          <tr>
            <td>title-right</td>
            <td>
              标题右侧的内容<br>
              可以放置一些icon之类的
            </td>
          </tr>
        </tbody>
      </au-table>
      <!-- <au-icon type="minus"></au-icon> -->
    </au-panel>
    <au-panel class="section" title="Events">
      <!-- <au-table>
        <thead>
          <tr>
            <th>名称</th>
            <th>参数</th>
            <th>说明</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>event1</td>
            <td>
              <ol class="option-list">
                <li class="au-theme-border-color--base-8">arg1</li>
                <li class="au-theme-border-color--base-8">arg2</li>
              </ol>
            </td>
            <td>
              该事件及参数的详细说明
            </td>
          </tr>
        </tbody>
      </au-table> -->
      <au-icon type="minus"></au-icon>
    </au-panel>
    <au-panel class="section" title="Methods">
      <!-- <au-table>
        <thead>
          <tr>
            <th>名称</th>
            <th>参数</th>
            <th>说明</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>method1</td>
            <td>
              <ol class="option-list">
                <li class="au-theme-border-color--base-8">arg1</li>
                <li class="au-theme-border-color--base-8">arg2</li>
              </ol>
            </td>
            <td>
              该方法及参数的详细说明
            </td>
          </tr>
        </tbody>
      </au-table> -->
      <au-icon type="minus"></au-icon>
    </au-panel>
    <au-panel class="section" title="使用示例">
      <h4 class="title-1">基础用例</h4>
      <code-h lang="html" content='
        <au-panel title="Panel" style="width: 500px;">
          <div slot="title-right">
            <au-icon type="bars"></au-icon>
          </div>
          <p class="au-theme-color--base-3">
            Minim anim minim consectetur non veniam sint tempor ea irure aliqua reprehenderit. Adipisicing est ut elit elit. Et cillum anim aute do sunt exercitation anim excepteur incididunt.
          </p>
        </au-panel>
      '></code-h>
    </au-panel>
  </div>
</template>
<script>
export default {
  name: 'panel-examples'
}
</script>
