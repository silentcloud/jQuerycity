# jQuerycity

---

// description

基于seajs的城市三级联动,依赖select组件

---

## 使用说明

   **defaultProvince** : 设置默认显示的省<br>
   **selectId**: 对应下拉框的dom元素id<br>

## API

    $(function(){
        $("body").jQueryCity({
            defaultProvince: "海外",
            selectId : {
                province : "province",
                city     : "city" ,
                area     : "area"
              }
        })
    })

