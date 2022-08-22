外壁流量
====
### **参数描述**
该参数可调节打印外壁时材料的流量速率。 

### **参数使用**
外壁的流量速率可以与内壁的流量速率分开调节。

调节外壁的流量速率可临时解决挤出速率或尺寸精度相关的问题。还可以通过调节[外壁线宽](../resolution/wall_line_width_0.md)和[外壁嵌入](../shell/wall_0_inset.md)参数解决问题，但该设置可能是一种更直观的初始调整方式。

如果在外壁打印过程中出现挤出速率异常，建议检查[打印速度](../speed/speed_wall_0.md)和[打印温度](material_print_temperature.md)。可能是由于推动力不足导致材料无法通过喷嘴，这时可以提高打印速度。也可能是由于线条太细而无法正常挤出。或者是由于材料温度过低或过高。

如果尺寸精度出现异常，建议检查[线宽](../resolution/wall_line_width_0.md)、[水平扩展](../shell/xy_offset.md)和[打印指令](../shell/outer_inset_first.md)。

