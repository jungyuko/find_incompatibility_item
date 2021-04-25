# negative outfit

## 목표
`polyvore-dataset-master` 파일내에 있는 `train_no_dup.json`, `valid_no_dup.json`, `test_no_dup.json`을 활용하여 negative item을 갖는 dataset을 생성한다.

### TODO
  * 기존의 outfit을 구성하는 item들 중에서 50%를 넘지 않는 선에서 random하게 k개의 item을 선택한다.
  * 선택된 item은 negative item으로 대체되어진다.
    **negative item의 조건**
    1. negative item은 outfit을 구성하는 나머지 item들과 다른 outfit에서 단 한번도 함께 등장하지 않은 item이어야한다.
    2. negative item은 선택된 item과 같은 category를 갖고 있어야한다.
  * negative item으로 대체한다.
  * negative item으로 교체된 outfit data의 image를 저장한다. (결과 확인)
