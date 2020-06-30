# 基于A* 算法和降阶法的四阶数字华容道问题快速求解方法

视频演示见 https://b23.tv/BV1az4y1X72f 


* 四阶数字华容道（15P）的复杂度相较于三阶的有非常大的提升。使用普通bfs算法三阶可能需要几秒而四阶就到了几分钟。
* 这里使用了A* 算法和降阶法结合的思路对四阶进行快速求解。得到的解并不是全局最优解，而是分三步的三个最优解的和。快的时候不到一秒出解，慢的时候可能到十秒左右。
* 视频中主要耗时在第一步读取数字上，pytesseract准确率不咋样还很耗时。。其实只是识别15个数字，可以尝试图片匹配等思路快速读取。

仅上传了求解过程的代码，而且这个代码感觉非常冗余，好多部分都是重复的，暂时懒得改进了。
