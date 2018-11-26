```
darkflow$ python setup.py build_ext --inplace
```

```
$ python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo testset/test_video_01f.mov --gpu 1.0 --saveVideo True
```

## Results

```
$ python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo testset/test_video_01f.mov --gpu 1.0 --saveVideo True
```

> 507.57sec

```
$ python flow --model cfg/tiny-yolo-voc.cfg --load bin/tiny-yolo-voc.weights --demo testset/test_video_01f.mov --gpu 1.0 --saveVideo True
```

> 95.77sec

yolo / tiny-yolo-voc -> X
yolo-voc / yolo.weights -> X
