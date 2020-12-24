# multi-roboot-demo-with-segmap
An example about how to run multi-robot-slam test with segmap 

1.download launch file from: https://github.com/gopi231091/SegMap-Multi-Robot-Demo 

2.Split files through the tools provided on the site: https://github.com/ethz-asl/segmap/tree/master/tools 
(1)use cut.py to split bags into four new bags 
(2)use remap.py to add prefix before original topic: e.g.python2 remap_bag.py -i na0.bag -o out_na0.bag -p /na0 

3.run the cnn_kitti_loop_closure_multi.launch
