# TIMER

TIM1使用的APB2时钟（64M）

## demo1  

**参考**  
[stm32Cube TIM1 定时器 中断](https://blog.csdn.net/penglijiang/article/details/116234535)  
向上计数 1s 触发一次更新事件  

## demo2

参考 数据手册的P1410 外部时钟源模式2

## demo3

输入捕获模式  
**参考**  
[STM32 HAL库 STM32CubeMX -- TIM（定时器输入捕获）](https://blog.csdn.net/Dir_x/article/details/129006634)  
while中打印的是高电平持续时间  
输入捕获的分辨率和定时器溢出时间有关  

## demo4

PWM输出  
**参考**  
[STM32H743+CubeMX-定时器TIM输出PWM（PWM Generation模式）+ 中断](https://blog.csdn.net/wallace89/article/details/118581314?spm=1001.2014.3001.5501)  
