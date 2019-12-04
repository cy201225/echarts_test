### echarts的使用

+ vue使用地图图表时，需要引入china.js文件，该文件和echarts.min.js是同一文件（/node_modules/echarts/map/js/china.js）


+ 注意：

  vue中使用多个echarts图表,部分图表渲染不出来，使用this.$nextTick()来渲染。