# ngAnimate 做了什么? #

- ngAnimate 模型可以添加或移除 class 。

- ngAnimate 模型并不能使 HTML 元素产生动画，但是 ngAnimate 会监测事件，类似隐藏显示 HTML 元素 ，如果事件发生 ngAnimate 就会使用预定义的 class 来设置 HTML 元素的动画。

## AngularJS 添加/移除 class 的指令: ##

    ng-show
    ng-hide
    ng-class
    ng-view
    ng-include
    ng-repeat
    ng-if
    ng-switch

ng-show 和 ng-hide 指令用于添加或移除 ng-hide class 的值。

其他指令会在进入 DOM 会添加 ng-enter 类，移除 DOM 会添加 ng-leave 属性。

当 HTML 元素位置改变时，ng-repeat 指令同样可以添加 ng-move 类 。

此外， 在动画完成后，HTML 元素的类集合将被移除。例如： ng-hide 指令会添加一下类：

    ng-animate
    ng-hide-animate
    ng-hide-add (如果元素将被隐藏)
    ng-hide-remove (如果元素将显示)
    ng-hide-add-active (如果元素将隐藏)
    ng-hide-remove-active (如果元素将显示)
