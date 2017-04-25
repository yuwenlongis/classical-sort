# Classical Sort
**使用java FX实现的排序过程的可视化。**    
只记录了排序的过程，即是每次待排序的数据有变化时记录下来，所以这个过程并不能代表该种排序算法的排序速度。    
- 冒泡排序
![](https://github.com/spareyaya/classical-sort/blob/master/BubbleSort.gif)    
    
- 插入排序
![](https://github.com/spareyaya/classical-sort/blob/master/InsertionSort.gif)    
    
- 快速排序
![](https://github.com/spareyaya/classical-sort/blob/master/QuickSort.gif)    
    
这里只是实现了几种，更多的排序方法可以自行实现，通过`implements Sort`接口或者`extends SortAdapter`类皆可。算法实现中当每次排序时数据发生变化时，请调用`DataUtils#add(int[])`方法来记录排序过程以便在直方图中看到排序过程。    
主界面的下拉菜单有冒泡排序、插入排序、快速排序、堆排序、希尔排序、归并排序、选择排序，其中冒泡、插入、快速、选择已经实现，如果需要实现其它的排序算法，比如基数排序等，可以自行在主界面的下拉菜单添加。

