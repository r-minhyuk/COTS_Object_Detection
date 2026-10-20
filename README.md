# COTS_Object_Detection
Faster R-CNN의 원리를 학습하고, Kaggle의 『TensorFlow - Help Protect the Great Barrier Reef』 Competition에 참여해보았습니다.

## Details
- 전체 프레임 수의 90% 지점을 기준으로 앞쪽은 Train, 뒤쪽은 Validation data로 설정했습니다.
- HorizontalFlip, VerticalFlip을 사용해 데이터를 증강했습니다.
- 백본 모델로는 torchvision의 ImageNet으로 학습한 VGG16을 사용했습니다.
- Bias에는 weight decay를 적용하지 않았습니다.

## Blog
- [Faster R-CNN 논문 리뷰](https://icedtea.tistory.com/entry/%EB%A6%AC%EB%B7%B0Faster-R-CNNTowards-Real-Time-Object-Detection-with-Region-Proposal-NetworksNIPS-2015)

## References
- [TensorFlow - Help Protect the Great Barrier Reef](https://www.kaggle.com/competitions/tensorflow-great-barrier-reef)
- [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/abs/1506.01497)
