# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur
# 特点
1. vite的
2. Vue3
3. IconPark作为图标库
4. UnoCss 的（后续加...）
5. UI框架使用radix-vue(后续加...)
6. 支持打包成单个html文件

## 1. vite
该模板采用 vite 作为构建工具，你可以在根目录下的 vite.config.ts 对项目的构建进行配置。

对于众多主流插件的引入和繁杂配置已经整合到根目录下的预设 presets 中，大多数情况下你是不需要重新对它们进行配置的。
## 2. vue3的


## 3. IconPark作为图标库
  使用步骤:
  1. 在IconPark官网选取需要的图标
  2. 引用图标和对应的样式
  3. 在Vue中以组件的方式使用图标
   
   `
    <import { CheckOne } from '@icon-park/vue'
    <import 'icon-park/vue/styles/index.css'
    <check-one theme="filled" size="32" fill="#17bd08">
   `
   