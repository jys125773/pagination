# pagination
这是一个原生js的分页插件，不需要任何倚赖，api简介
self.pager = new Pagination({
  "id":"pagination",//组件wrapper id名
  "cur":curPage,//当前页码
  "total":maxPage,//总共页码
  "change":function(page){//当换页之后的回调函数，注入换到第几页的实参page
  }
});
