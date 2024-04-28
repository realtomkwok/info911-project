# MLP - INFO911 Project

## Logs
```text
Model Summary:

Model Name: model-pca-17
Data: PCA

MLP2(
  (fc1): Linear(in_features=256, out_features=512, bias=True)
  (fc2): Linear(in_features=512, out_features=256, bias=True)
  (fc3): Linear(in_features=256, out_features=128, bias=True)
  (fc4): Linear(in_features=128, out_features=120, bias=True)
  (relu): ReLU()
  (dropout): Dropout(p=0.5, inplace=False)
)
Initial Input shape: 256
Epoch 1, Training Loss: 6.435772895812988, Validation Loss: 2.4263486864386747
Epoch 2, Training Loss: 1.1649330854415894, Validation Loss: 1.6433264217335575
Epoch 3, Training Loss: 0.823453962802887, Validation Loss: 1.4215809886293331
Epoch 4, Training Loss: 0.7673424482345581, Validation Loss: 1.3404232842156003
Epoch 5, Training Loss: 0.636387050151825, Validation Loss: 1.2892383307460438
Epoch 6, Training Loss: 0.8075140714645386, Validation Loss: 1.244354161038872
Epoch 7, Training Loss: 0.9040495157241821, Validation Loss: 1.2100505887360002
Epoch 8, Training Loss: 0.926012396812439, Validation Loss: 1.173562185907827
Epoch 9, Training Loss: 1.0407460927963257, Validation Loss: 1.1442365184218053
Epoch 10, Training Loss: 1.0905556678771973, Validation Loss: 1.122496619919742
Epoch 11, Training Loss: 1.0842207670211792, Validation Loss: 1.095634696606495
Epoch 12, Training Loss: 1.0103240013122559, Validation Loss: 1.076544961880815
Epoch 13, Training Loss: 1.1021920442581177, Validation Loss: 1.0574983331174979
Epoch 14, Training Loss: 0.975902259349823, Validation Loss: 1.0393838244822433
Epoch 15, Training Loss: 0.9598208069801331, Validation Loss: 1.026167720972444
Epoch 16, Training Loss: 0.876633882522583, Validation Loss: 1.013194665101247
Epoch 17, Training Loss: 0.8719236850738525, Validation Loss: 1.0006070837664527
Epoch 18, Training Loss: 0.817072868347168, Validation Loss: 0.9923061003393053
Epoch 19, Training Loss: 0.8269803524017334, Validation Loss: 0.984825390911315
Epoch 20, Training Loss: 0.7587500214576721, Validation Loss: 0.9777060398978291
Epoch 21, Training Loss: 0.774736225605011, Validation Loss: 0.9725405612923593
Epoch 22, Training Loss: 0.7459337115287781, Validation Loss: 0.9674691308828187
Epoch 23, Training Loss: 0.7176001667976379, Validation Loss: 0.9629607911223623
Epoch 24, Training Loss: 0.692373514175415, Validation Loss: 0.9588150266763438
Epoch 25, Training Loss: 0.6589736938476562, Validation Loss: 0.9557294264909514
Epoch 26, Training Loss: 0.6319143176078796, Validation Loss: 0.9525302115399488
Epoch 27, Training Loss: 0.6146252155303955, Validation Loss: 0.9499220160312931
Epoch 28, Training Loss: 0.5916603803634644, Validation Loss: 0.9477305787157578
Epoch 29, Training Loss: 0.5741016864776611, Validation Loss: 0.9455386131373072
Epoch 30, Training Loss: 0.557862401008606, Validation Loss: 0.9435602846063881
Epoch 31, Training Loss: 0.549297571182251, Validation Loss: 0.9418899419308582
Epoch 32, Training Loss: 0.551176905632019, Validation Loss: 0.9406087143393234
Epoch 33, Training Loss: 0.5495169758796692, Validation Loss: 0.9394133504823226
Epoch 34, Training Loss: 0.5450249910354614, Validation Loss: 0.9382300331145719
Epoch 35, Training Loss: 0.5402745008468628, Validation Loss: 0.9375621637749201
Epoch 36, Training Loss: 0.5353966355323792, Validation Loss: 0.9367466609156043
Epoch 37, Training Loss: 0.5298949480056763, Validation Loss: 0.9360470669474712
Epoch 38, Training Loss: 0.5305822491645813, Validation Loss: 0.935427398390861
Epoch 39, Training Loss: 0.5314707159996033, Validation Loss: 0.9350002290522874
Epoch 40, Training Loss: 0.5271596908569336, Validation Loss: 0.9345544490538304
Epoch 41, Training Loss: 0.5263242125511169, Validation Loss: 0.9341615956553465
Epoch 42, Training Loss: 0.5289758443832397, Validation Loss: 0.9338131634694582
Epoch 43, Training Loss: 0.5276659727096558, Validation Loss: 0.9335210348455681
Epoch 44, Training Loss: 0.527825117111206, Validation Loss: 0.9332102326296444
Epoch 45, Training Loss: 0.5289103388786316, Validation Loss: 0.932987258689601
Epoch 46, Training Loss: 0.5315529704093933, Validation Loss: 0.9327747990399399
Epoch 47, Training Loss: 0.5322100520133972, Validation Loss: 0.9325856803506516
Epoch 48, Training Loss: 0.5343174338340759, Validation Loss: 0.9324319957538035
Epoch 49, Training Loss: 0.5372808575630188, Validation Loss: 0.9322978224728852
Epoch 50, Training Loss: 0.5397002100944519, Validation Loss: 0.9321688547124601
Finished Training
--------------------------------------------------
Model Summary:
MLP2(
  (fc1): Linear(in_features=256, out_features=512, bias=True)
  (fc2): Linear(in_features=512, out_features=256, bias=True)
  (fc3): Linear(in_features=256, out_features=128, bias=True)
  (fc4): Linear(in_features=128, out_features=120, bias=True)
  (relu): ReLU()
  (dropout): Dropout(p=0.5, inplace=False)
)

Loss function:
CrossEntropyLoss()

Optimizer:
Adam (
Parameter Group 0
    amsgrad: False
    betas: (0.9, 0.999)
    capturable: False
    differentiable: False
    eps: 1e-08
    foreach: None
    fused: None
    initial_lr: 0.001
    lr: 5.15377520732012e-06
    maximize: False
    weight_decay: 0.01
)

Number of Epochs: 50

Final Training Loss: 0.5397002100944519
Final Validation Loss: 0.9321688547124601

Final Validation Accuracy: 0.7211111111111111

Total Training Time: 33.0 minutes, 35.155251026153564 seconds
```
```text
Model Summary:
Model Name: model-pca-20240428-211634
Data: PCA and 50 features

Training data: torch.Size([10200, 50]), Training labels: torch.Size([10200])
Validation data: torch.Size([1800, 50]), Validation labels: torch.Size([1800])


--------------------


MLP3(
  (fc1): Linear(in_features=50, out_features=100, bias=True)
  (fc2): Linear(in_features=100, out_features=200, bias=True)
  (fc3): Linear(in_features=200, out_features=128, bias=True)
  (fc4): Linear(in_features=128, out_features=120, bias=True)
  (relu): ReLU()
  (dropout): Dropout(p=0.5, inplace=False)
)
Initial Input shape: 50
Epoch 1, Training Loss: 1.4765398502349854, Validation Loss: 2.4697428028202717
Epoch 2, Training Loss: 1.3818618059158325, Validation Loss: 1.6132958441827536
Epoch 3, Training Loss: 0.8195878267288208, Validation Loss: 1.4141999934601417
Epoch 4, Training Loss: 0.8171063661575317, Validation Loss: 1.3193213302618176
Epoch 5, Training Loss: 0.7292091250419617, Validation Loss: 1.2729750596183456
Epoch 6, Training Loss: 0.7459471821784973, Validation Loss: 1.2345456845083067
Epoch 7, Training Loss: 0.7848841547966003, Validation Loss: 1.205815089753208
Epoch 8, Training Loss: 0.7729723453521729, Validation Loss: 1.1738692445147576
Epoch 9, Training Loss: 0.752031683921814, Validation Loss: 1.148128446790959
Epoch 10, Training Loss: 0.7675915360450745, Validation Loss: 1.1285983990606232
Epoch 11, Training Loss: 0.8224028944969177, Validation Loss: 1.1103726778573926
Epoch 12, Training Loss: 0.8136557936668396, Validation Loss: 1.0942765405134478
Epoch 13, Training Loss: 0.8306647539138794, Validation Loss: 1.081257375773534
Epoch 14, Training Loss: 0.8212552666664124, Validation Loss: 1.0682552877194635
Epoch 15, Training Loss: 0.8013828992843628, Validation Loss: 1.0569051120590625
Epoch 16, Training Loss: 0.8107056617736816, Validation Loss: 1.0481096736915383
Epoch 17, Training Loss: 0.7931888699531555, Validation Loss: 1.0398635618472083
Epoch 18, Training Loss: 0.7917965054512024, Validation Loss: 1.0326949429695054
Epoch 19, Training Loss: 0.7585141062736511, Validation Loss: 1.0259187176039106
Epoch 20, Training Loss: 0.7544866800308228, Validation Loss: 1.0199398460196487
Epoch 21, Training Loss: 0.7556812763214111, Validation Loss: 1.0143198050111015
Epoch 22, Training Loss: 0.7535278797149658, Validation Loss: 1.0097219991577893
Epoch 23, Training Loss: 0.7350142598152161, Validation Loss: 1.005499339996475
Epoch 24, Training Loss: 0.7297743558883667, Validation Loss: 1.001379949720059
Epoch 25, Training Loss: 0.7234083414077759, Validation Loss: 0.9978415053985857
Epoch 26, Training Loss: 0.7078673243522644, Validation Loss: 0.9945051090192929
Epoch 27, Training Loss: 0.705875813961029, Validation Loss: 0.9916477905273334
Epoch 28, Training Loss: 0.7040061354637146, Validation Loss: 0.9890742729970305
Epoch 29, Training Loss: 0.6960321664810181, Validation Loss: 0.9865327106028174
Epoch 30, Training Loss: 0.6936492919921875, Validation Loss: 0.984731882767519
Epoch 31, Training Loss: 0.6858910322189331, Validation Loss: 0.9828052980152683
Epoch 32, Training Loss: 0.6823820471763611, Validation Loss: 0.9811640213466146
Epoch 33, Training Loss: 0.6777534484863281, Validation Loss: 0.9796601098314083
Epoch 34, Training Loss: 0.6737461686134338, Validation Loss: 0.9784021987503446
Epoch 35, Training Loss: 0.6686629056930542, Validation Loss: 0.9772725637436896
Epoch 36, Training Loss: 0.6651846170425415, Validation Loss: 0.976329009022512
Epoch 37, Training Loss: 0.6608237028121948, Validation Loss: 0.975490655985842
Epoch 38, Training Loss: 0.6556878089904785, Validation Loss: 0.9747022261389066
Epoch 39, Training Loss: 0.652536928653717, Validation Loss: 0.9740255240535932
Epoch 40, Training Loss: 0.6486602425575256, Validation Loss: 0.9734953516675806
Epoch 41, Training Loss: 0.6460981965065002, Validation Loss: 0.9730034309886266
Epoch 42, Training Loss: 0.6458196640014648, Validation Loss: 0.9725420804319179
Epoch 43, Training Loss: 0.6458266377449036, Validation Loss: 0.9721278031366334
Epoch 44, Training Loss: 0.6473273634910583, Validation Loss: 0.9717640342009771
Epoch 45, Training Loss: 0.6474525928497314, Validation Loss: 0.9714082888419378
Epoch 46, Training Loss: 0.6482560634613037, Validation Loss: 0.9711117711184003
Epoch 47, Training Loss: 0.6488006114959717, Validation Loss: 0.9708486519500407
Epoch 48, Training Loss: 0.6494182348251343, Validation Loss: 0.9705914096986331
Epoch 49, Training Loss: 0.6506023406982422, Validation Loss: 0.9703846491661776
Epoch 50, Training Loss: 0.651642382144928, Validation Loss: 0.9701823899743612
Finished Training


--------------------


--------------------------------------------------
Model Summary:
MLP3(
  (fc1): Linear(in_features=50, out_features=100, bias=True)
  (fc2): Linear(in_features=100, out_features=200, bias=True)
  (fc3): Linear(in_features=200, out_features=128, bias=True)
  (fc4): Linear(in_features=128, out_features=120, bias=True)
  (relu): ReLU()
  (dropout): Dropout(p=0.5, inplace=False)
)

Loss function:
CrossEntropyLoss()

Optimizer:
Adam (
Parameter Group 0
    amsgrad: False
    betas: (0.9, 0.999)
    capturable: False
    differentiable: False
    eps: 1e-08
    foreach: None
    fused: None
    initial_lr: 0.001
    lr: 5.15377520732012e-06
    maximize: False
    weight_decay: 0.01
)

Learning Rate Scheduler:
<torch.optim.lr_scheduler.ExponentialLR object at 0x29a168950>

Number of Epochs: 50

Final Training Loss: 0.651642382144928
Final Validation Loss: 0.9701823899743612

Final Validation Accuracy: 0.7211111111111111

Total Training Time: 7.0 minutes, 5.522812843322754 seconds


--------------------

Model saved as: model_pca-20240428-211634.pth

```
