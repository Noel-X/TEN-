# TEN
Training
python train.py
--epochs 400
--batch-size 32
--lr 0.0001
--weights https://download.pytorch.org/models/resnet34-333f7ec4.pth

Testing
python confusion_matrix_MSG.py
--batch-size 2
