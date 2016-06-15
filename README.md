# jyDate
# 根据自己的项目做的日期控件，菜鸟一枚，大牛勿喷
# 属性dataInterval和属性dataArr不可同时设置,其余的都可以同时设置--*/
        >初始化日期,当前日高亮
        'jyDate().init();'

***
        >属性data(格式为yyyy-mm-dd),入参日期高亮
        'jyDate().init({
            data: '2016-5-4'
        });'
        
    ***
    
        >属性isActiveToday,当前日不高亮
        'jyDate().init({
            isActiveToday: false
        });
    '
    ***
        >属性isChangMonth,左右按钮不可切换
        'jyDate().init({
            isChangMonth: false
        });'
    ***
    
        >属性isClickDay,页面不可点击
          'jyDate().init({
            isClickDay: false
        });'
    ***
    
        >属性clickType(移动端可以为'tap(需要自己封装或框架支持)')
        'jyDate().init({
            clickType: 'tap'
        });'
    ***
    
          >属性inputType(默认多选设置'radio'为单选)
        'jyDate().init({
            inputType: 'radio'
        });'
    ***
        >属性dataArr(格式为yyyy-mm-dd的数组),入参日期高亮
        'jyDate().init({
                dataArr: ['2016-5-23', '2016-6-3', '2017-4-2']
            });'
    ***
    
        >属性dataInterval(传人天数即可)(注:属性dataInterval和属性dataArr不可同时设置)
        'jyDate().init({
            dataInterval: 7
        });'
