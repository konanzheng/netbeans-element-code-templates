<h1>Vue  eLement   Snippets for NetBeans</h1>


It is based on    : <a href="https://github.com/Chris2011/netbeans-angular2-code-templates">https://github.com/Chris2011/netbeans-angular2-code-templates</a>
This extension for NetBeans adds snippets for Element for Vue.


<h2>使用方法</h2>
跟其他代码模板一样输入部分代码然后提示

<h3>标签</h3>
0. **row** : `<el-row></el-row>`
1. **col** : `<el-col></el-col>`
2. **color** : `<color></color>`
3. **typography** : `<typography></typography>`
4. **icon** : `<icon></icon>`
5. **button** : `<el-button></el-button>`
6. **radio** : `<el-radio></el-radio>`
7. **rg** : `<el-radio-group></el-radio-group>`
8. **checkbox** : `<el-checkbox></el-checkbox>`
9. **cg** : `<el-checkbox-group></el-checkbox-group>`
10. **input** : `<el-input></el-input>`
11. **auto** : `<el-autocomplete></el-autocomplete>`
12. **in** : `<el-input-number></el-input-number>`
13. **select** : `<el-select></el-select>`
14. **opt** : `<el-option></el-option>`
15. **gopt** : `<el-option-group></el-option-group>`
16. **casc** : `<el-cascader></el-cascader>`
17. **switch** : `<el-switch></el-switch>`
18. **slider** : `<el-slider></el-slider>`
19. **tpicker** : `<el-time-picker></el-time-picker>`
20. **tselect** : `<el-time-select></el-time-select>`
21. **dp** : `<el-date-picker></el-date-picker>`
22. **datetime** : `<el-datetime-picker></el-datetime-picker>`
23. **upload** : `<el-upload></el-upload>`
24. **rate** : `<el-rate></el-rate>`
25. **cp** : `<el-color-picker></el-color-picker>`
26. **trans** : `<el-transfer></el-transfer>`
27. **form** : `<el-form></el-form>`
28. **fitem** : `<el-form-item></el-form-item>`
29. **table** : `<el-table></el-table>`
30. **tcol** : `<el-table-column></el-table-column>`
31. **tag** : `<el-tag></el-tag>`
32. **prog** : `<el-progress></el-progress>`
33. **tree** : `<el-tree></el-tree>`
34. **page** : `<el-pagination></el-pagination>`
35. **badge** : `<el-badge></el-badge>`
36. **loading** : `<v-loading></v-loading>`
37. **menu** : `<el-menu></el-menu>`
38. **submenu** : `<el-submenu></el-submenu>`
39. **mitem** : `<el-menu-item></el-menu-item>`
40. **tabs** : `<el-tabs></el-tabs>`
41. **tabp** : `<el-tab-pane></el-tab-pane>`
42. **bc** : `<el-breadcrumb></el-breadcrumb>`
43. **drop** : `<el-dropdown></el-dropdown>`
44. **dmenu** : `<el-dropdown-menu></el-dropdown-menu>`
45. **ditem** : `<el-dropdown-item></el-dropdown-item>`
46. **steps** : `<el-steps></el-steps>`
47. **dialog** : `<el-dialog></el-dialog>`
48. **tip** : `<el-tooltip></el-tooltip>`
49. **pop** : `<el-popover></el-popover>`
50. **card** : `<el-card></el-card>`
51. **caro** : `<el-carousel><el-carousel-item></el-carousel-item></el-carousel>`
52. **coll** : `<el-collapse><el-collapse-item></el-collapse-item></el-collapse>`

<h3>方法</h3>
1. **msg** : `this.$message({	message: 'text',type: 'info'});`
2. **alert** : `this.$alert('content', 'title', {confirmButtonText: 'confirm',callback: action => {}});`
3. **confirm** : `this.$confirm('content', 'title', {confirmButtonText: 'confirm',cancelButtonText: 'cancel',type: 'warning',}).then(() => {,	,}).catch(() => {});`
4. **prompt** : `this.$prompt('content', 'title', {confirmButtonText: 'confirm',cancelButtonText: 'cancel',inputPattern: /regExp/,inputErrorMessage: 'errormsg',}).then(({ value }) => {,	,}).catch(() => {});`
5. **msgb** : `this.$msgbox({,	title: 'title',message: 'string|VNode',showCancelButton: true,confirmButtonText: 'confirm',cancelButtonText: 'cancel',beforeClose: (action, instance, done) => {},}).then(action => {,	,});`
6. **notify** : `this.$notify({,	title: 'title',message: 'string|VNode',});`

