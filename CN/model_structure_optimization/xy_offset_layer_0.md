起始层水平扩展
===

### **参数描述**

此设置仅拓宽或收缩位于打印平台上（或多层粘附上）的起始层。类似于[水平扩展](xy_offset.md)，正值会使起始层变宽，负值会使起始层缩小。

![原始模型](../images/xy_offset_layer_0_original.png) 
![起始层缩小](../images/xy_offset_layer_0_enabled.png)

### **参数使用**

起始层通常在加热打印平台上打印，这会使材料略微保持液态，以改善与打印平台的附着。起始层通常也会比其它层厚得多。这为起始层向周围延展留出了充足的时间和材料，产生了一种被称为“象脚”的现象，即打印件的底层略微突出。你可通过此设置收缩起始层，从而减轻“象脚”现象。将其设为负值，即可使起始层收缩变窄。

您也可以设置一个较大的正值，大幅拓宽起始层，在打印件底部产生一个伪单层粘附。这可以与其他粘附（如多层粘附）结合使用。

但是，将此设置与单层粘附相结合，却无法产生更多效果。因为单层粘附本身就会在起始层周围生成一个较大的单层平面。